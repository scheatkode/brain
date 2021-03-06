---
author: scheatkode
title: DHCP superscope is a bad idea
tags:
   - administration
   - system
   - windows
   - network
   - dhcp
   - troubleshooting
---

<p align="center">
   <img src="../../.assets/xkcd/zealous_autoconfig.png" alt="banner" />
</p>

<h1 align="center">DHCP superscope is a bad idea</h1>

Recently, I  had to troubleshoot  an issue  where users moving  between floors
with different subnets/VLANs were not getting the correct LAN IP address (i.e.
first floor was `192.168.1.0/24` and the second was `192.168.2.0/24`).

Verified the  network devices  had IP  Helpers, that  this wasn't  some hidden
Layer 2 loop on the switches, even temporarily disabled DHCP failover (2012R2+
feature) to rule that out ... nothing.

Whenever the machine switched from one floor to another, even running `IPCONFIG
/RELEASE` & `IPCONFIG /RENEW` did not help.  Checking the logs on the DHCP server
indicated that the traffic  was making it there and the DHCP  server saw it as
renewing the lease, which it allowed rather than rejecting handing out that IP
address and assigning one for the correct range.

It turned out to be DHCP Superscoping that was causing this issue. Many people
set  up  Superscoping  because  they  think   it  is  just  another  layer  of
administrative abstraction/consolidation. You know, grouping multiple VLANs by
physical location into one Superscope.

The  problem with  that is  Microsoft’s Superscope  only works  when you  have
multiple subnets  sharing the  same underlying  VLAN in  which case,  it works
fine, and users would be OK  maintaining their previous IP address because the
default gateway would continue to  route traffic properly. However, because of
the way that  subnets and VLANs work, every network  administrator is going to
assign only one subnet per VLAN, instead of multiple.

I have never seen a network environment where this was being done, therefore I
have never seen  a network where Superscoping  was appropriate. Unfortunately,
there is not  enough documentation (at least  that I have ever  seen) for this
functionality. And depending  on the type of devices in  use and the frequency
of moving subnets, users and admins may not even notice.

Because this was an environment where  each floor of the building was assigned
a different subnet for each floor, users are assigned laptops and often switch
jacks, we noticed the issue fairly  quickly. If this were an environment where
there was only one  LAN subnet for all floors and/or  desktops in use instead,
then  the issue  would  take a  while  to manifest  (only  if moving  desktops
frequently between floors or outside the building).

So yeah, lesson learned. **Don’t ever  use Superscoping for DHCP** because it does
not help you  out in any way  functionally, and there are  almost no scenarios
where a network would be deployed in such a way that Superscoping made sense.
