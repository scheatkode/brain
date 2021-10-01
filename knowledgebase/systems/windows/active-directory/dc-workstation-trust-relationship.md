---
author: scheatkode
title: Re-establishing trust relationship with Domain Controllers
tags:
   - active directory
   - administration
   - network
   - system
   - windows
---

<p align="center">
   <img src="../../../../.assets/banners/dc-workstation-trust-relationship.jpg"
</p>

<h1 align="center">Re-establishing trust relationship with Domain Controllers</h1>

Every  computer joined  to  an Active  Directory domain  has  its own  special
account, meaning each  computer actually has a "*username*" and  a password of
its own. The  username is the computer  name followed by a  dollar sign (*$*).
The  password   is  automatically  negotiated  between   computer  and  domain
controller when you join the computer to  AD and is renegotiated on a periodic
basis thereafter. This password is called machine password.

For this reason or other, sometimes one  needs to revert a member computer (or
an  AD) to  a previous  state  in time.  If  computer and  AD changed  machine
password meanwhile,  and you  restored only  one of them  to the  state before
that,  passwords are  out of  sync and  users  can no  longer log  in on  that
computer.

This can also cause some `ACCESS_DENIED` and obscure LDAP errors, and can also
prevent invoking `GPUpdate` successfully.

A  usual remedy  is to  log-in using  a local  administrator account,  un-join
computer from the domain,  and re-join it. Not the most  elegant of ways since
it  involves  at  least  two   restarts,  possible  removal  of  all  deployed
applications and their re-installation, etc.  Fortunately, it can be done with
a bit less of a fuss.

### The *maybe not so* historical way

In the  days before  PowerShell was  a thing,  Systems Administrators  used to
resolve this  issue using the  `nltest` and  `netdom` commands. The  latter is
missing  on Windows  workstations and  is available  on Windows  servers only.
Fortunately, one can copy the `netdom.exe` from the server's `System32` folder
and it should work fine on any Windows computer.

To make  sure this  is the  actual problem we're  dealing with,  the following
command should return an `ACCESS_DENIED` error.

```bat
nltest /sc_verify:<your-domain>
```

This is where the `netdom` utility comes  to the rescue. But it will refuse to
work if there are existing connections to the domain controller other than the
domain administrative account that will be  used to restore the trust. If that
is the case, start an elevated prompt  and use the `net use` command to delete
all existing connections to the server.

After which, restore the domain trust happens with the following command.

```bat
netdom resetpwd                    `
       /server:<domain-controller> `
       /UserD:<domain\admin>       `
       /PasswordD:<admin-password>
```

The operation  takes a few  seconds and, once  it's done, re-run  the previous
command to check if the trust has been re-established.

```bat
nltest /sc_verify:<your-domain>
```

### The modern way

The historical method  is still worth trying but the  following one is cleaner
and doesn't require adding random executable files.

Checking for the  trust relationship is a simple command  which returns either
`True` or `False`; usually `False` is when there is an issue.

```powershell
Test-ComputerSecureChannel
```

If a connection fails, the `-Repair`  parameter is handy to attempt to restore
it while the `-Verbose` parameter gets  more detailed test results. The Cmdlet
works much like `netdom.exe` where both utilites use the `NetLogon` service to
perform the requested actions.

Where `Test-ComputerSecureChannel`  fails, another  Cmdlet comes into  play to
repair the relationship more aggressively and is used like so.

```powershell
Reset-ComputerMachinePassword      `
  -Server <Domain Controller name> `
  -Credential (Get-Credential)
```
