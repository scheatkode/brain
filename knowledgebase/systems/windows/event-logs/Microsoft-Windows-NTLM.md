# Microsoft-Windows-NTLM

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-NTLM</td><td>100</td><td>NTLM authentication failed because the account was a member of the Protected User group.

Account Name:	%1
Device Name:	%2
Error Code:	%3</td></tr>
<tr><td>Microsoft-Windows-NTLM</td><td>101</td><td>NTLM authentication failed because access control restrictions are required.

Account Name:	%1
Device Name:	%2
Error Code:	%3

Authentication Policy Information:
	Silo Name:	%4
	PolicyName:	%5</td></tr>
<tr><td>Microsoft-Windows-NTLM</td><td>4001</td><td>NTLM client blocked: Outgoing NTLM authentication traffic to remote servers that is blocked.
Target server: %1
Supplied user: %2
Supplied domain: %3
PID of client process: %4
Name of client process: %5
LUID of client process: %6
User identity of client process: %7
Domain name of user identity of client process: %8
Mechanism OID: %9

NTLM authentication requests from this computer are blocked.

If you want to allow this computer to use NTLM authentication, set the security policy Network Security: Restrict NTLM: Outgoing NTLM traffic to remote servers to Allow all.

If you want only the target server %1 to accept NTLM authentication requests from this computer, set the security policy Network Security: Restrict NTLM: Outgoing NTLM traffic to remote servers to Deny all and then set the security policy Network Security: Restrict NTLM: Add remote server exceptions and list the target server %1 as an exception to use NTLM authentication.</td></tr>
<tr><td>Microsoft-Windows-NTLM</td><td>4002</td><td>NTLM server blocked: Incoming NTLM traffic to servers that is blocked
Calling process PID: %1
Calling process name: %2
Calling process LUID: %3
Calling process user identity: %4
Calling process domain identity: %5
Mechanism OID: %6

NTLM authentication requests to this server have been blocked.

If you want this server to allow NTLM authentication, set the security policy Network Security: Restrict NTLM: Incoming NTLM Traffic to Allow all.</td></tr>
<tr><td>Microsoft-Windows-NTLM</td><td>4003</td><td>NTLM server blocked in the domain: NTLM authentication in this domain that is blocked
User: %1
Domain: %2
Workstation: %3
PID: %4
Process: %5
Logon type: %6
InProc: %7
Mechanism: %8

NTLM authentication within the domain %2 is blocked.

If you want to allow NTLM authentication requests in the domain %1, set the security policy Network Security: Restrict NTLM: NTLM authentication in this domain to Disabled.

If you want to allow NTLM authentication requests only to specific servers in the domain %1, set the security policy Network Security: Restrict NTLM: NTLM authentication in this domain to Deny for domain servers or Deny domain accounts to domain servers, and then set the security policy Network Security: Restrict NTLM: Add server exceptions in this domain to define a list of servers in this domain as an exception to use NTLM authentication.</td></tr>
<tr><td>Microsoft-Windows-NTLM</td><td>4010</td><td>NTLM Minimum Client Security Block:
Calling process PID: %1
Calling Process Name: %2
Negotiated Security Flags: %3
Minimum Security Flags: %4</td></tr>
<tr><td>Microsoft-Windows-NTLM</td><td>4011</td><td>NTLM Minimum Server Security Block:
Calling process PID: %1
Calling Process Name: %2
Negotiated Security Flags: %3
Minimum Security Flags: %4</td></tr>
<tr><td>Microsoft-Windows-NTLM</td><td>4012</td><td>NTLM client used the domain password. The attempt to use the DC-generated NTLM secret failed, and fallback to the domain password succeeded.
Account Name:	%1
Device Name:	%2
</td></tr>
<tr><td>Microsoft-Windows-NTLM</td><td>4013</td><td>Attempt to use NTLMv1 failed.

Target server: %1
Supplied user: %2
Supplied domain: %3
PID of client process: %4
Name of client process: %5
LUID of client process: %6
User identity of client process: %7
Domain name of user identity of client process: %8
Mechanism OID: %9

This device does not support NTLMv1. For more information, see https://go.microsoft.com/fwlink/?linkid=856826.</td></tr>
<tr><td>Microsoft-Windows-NTLM</td><td>8001</td><td>NTLM client blocked audit: Audit outgoing NTLM authentication traffic that would be blocked.
Target server: %1
Supplied user: %2
Supplied domain: %3
PID of client process: %4
Name of client process: %5
LUID of client process: %6
User identity of client process: %7
Domain name of user identity of client process: %8
Mechanism OID: %9

Audit the NTLM authentication requests from this computer that would be blocked by the target server %1 if the security policy Network Security: Restrict NTLM: Outgoing NTLM traffic to remote servers is set to Deny all.

If you want all servers to accept NTLM authentication requests from this computer, set the security policy Network Security: Restrict NTLM: Outgoing NTLM traffic to remote servers to Allow all.

If you want only the target server %1 to accept NTLM authentication requests from this computer, set the security policy Network Security: Restrict NTLM: Outgoing NTLM traffic to remote servers to Deny all, and then set the security policy Network Security: Restrict NTLM: Add remote server exceptions and list the target server %1 as an exception to use NTLM authentication.</td></tr>
<tr><td>Microsoft-Windows-NTLM</td><td>8002</td><td>NTLM server blocked audit: Audit Incoming NTLM Traffic that would be blocked
Calling process PID: %1
Calling process name: %2
Calling process LUID: %3
Calling process user identity: %4
Calling process domain identity: %5
Mechanism OID: %6

Audit NTLM authentication requests to this server that would be blocked if the security policy Network Security: Restrict NTLM: Incoming NTLM Traffic is set to Deny all accounts or Deny all domain accounts.

If you want this server to allow NTLM authentication, set the security policy Network Security: Restrict NTLM: Incoming NTLM Traffic to Allow all.</td></tr>
<tr><td>Microsoft-Windows-NTLM</td><td>8003</td><td>NTLM server blocked in the domain audit: Audit NTLM authentication in this domain
User: %1
Domain: %2
Workstation: %3
PID: %4
Process: %5
Logon type: %6
InProc: %7
Mechanism: %8

Audit NTLM authentication requests within this domain that would be blocked if the security policy Network Security: Restrict NTLM: NTLM authentication in this domain is set to Deny for domain servers or Deny domain accounts to domain servers.

If you want to allow NTLM authentication requests in the domain %1, set the security policy Network Security: Restrict NTLM: NTLM authentication in this domain to Disabled.

If you want to allow NTLM authentication requests to specific servers in the domain %1, set the security policy Network Security: Restrict NTLM: NTLM authentication in this domain to Deny for domain servers or Deny domain accounts to domain servers, and then set the security policy Network Security: Restrict NTLM: Add server exceptions in this domain to define a list of servers in this domain to use NTLM authentication.</td></tr>
</table>
