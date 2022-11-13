# Microsoft-Windows-SMBServer

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1</td><td>SMB2 Request Negotiate</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>2</td><td>SMB2 Request Session Setup</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>3</td><td>SMB2 Request Logoff</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>4</td><td>SMB2 Request Tree Connect</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>5</td><td>SMB2 Request Tree Disconnect</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>6</td><td>SMB2 Request Echo</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>7</td><td>SMB2 Request Cancel</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>8</td><td>SMB2 Request Create</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>9</td><td>SMB2 Request Close</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>10</td><td>SMB2 Request Flush</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>11</td><td>SMB2 Request Read</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>12</td><td>SMB2 Request Write</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>13</td><td>SMB2 Request Break Oplock</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>14</td><td>SMB2 Request Notify Break Lease</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>15</td><td>SMB2 Request Acknowledge Break Lease</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>16</td><td>SMB2 Request Lock</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>17</td><td>SMB2 Request Ioctl</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>18</td><td>SMB2 Request Query Directory</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>19</td><td>SMB2 Request Change Notify</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>20</td><td>SMB2 Request Query Info</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>21</td><td>SMB2 Request Set Info</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>101</td><td>SMB2 Response Negotiate</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>102</td><td>SMB2 Response Session Setup</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>103</td><td>SMB2 Response Logoff</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>104</td><td>SMB2 Response Tree Connect</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>105</td><td>SMB2 Response Tree Disconnect</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>106</td><td>SMB2 Response Echo</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>108</td><td>SMB2 Response Create</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>109</td><td>SMB2 Response Close</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>110</td><td>SMB2 Response Flush</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>111</td><td>SMB2 Response Read</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>112</td><td>SMB2 Response Write</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>113</td><td>SMB2 Response Break Oplock</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>115</td><td>SMB2 Response Acknowledge Break Lease</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>116</td><td>SMB2 Response Lock</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>117</td><td>SMB2 Response Ioctl</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>118</td><td>SMB2 Response Query Directory</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>119</td><td>SMB2 Response Change Notify</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>120</td><td>SMB2 Response Query Info</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>121</td><td>SMB2 Response Set Info</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>122</td><td>SMB2 Response Error</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>200</td><td>SMB2 Work Item Component Transition</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>201</td><td>SMB2 Work Item allocated</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>202</td><td>SMB2 Work Item released</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>203</td><td>SMB2 Work Item activity id transfer</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>204</td><td>SMB2 Work Item external activity id stop</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>500</td><td>SMB2 Connection accepted</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>501</td><td>SMB2 Connection Disconnected by Peer</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>502</td><td>SMB2 Connection Terminated</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>550</td><td>SMB2 Session Allocated</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>551</td><td>Smb Session Authentication Failure</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>551</td><td>SMB Session Authentication Failure

Client Name: %11
Client Address: %6
User Name: %9
Session ID: %7
Status: %4 (%3)

Guidance:

You should expect this error when attempting to connect to shares using incorrect credentials.

This error does not always indicate a problem with authorization, but mainly authentication. It is more common with non-Windows clients.

This error can occur when using incorrect usernames and passwords with NTLM, mismatched LmCompatibility settings between client and server, duplicate Kerberos service principal names, incorrect Kerberos ticket-granting service tickets, or Guest accounts without Guest access enabled</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>551</td><td>SMB Session Authentication Failure

Client Name: %11
Client Address: %6
User Name: %9
Session ID: %7
Status: %4 (%3)
SPN: %12
SPN Validation Policy: %13

Guidance:

You should expect this error when attempting to connect to shares using incorrect credentials.

This error does not always indicate a problem with authorization, but mainly authentication. It is more common with non-Windows clients.

This error can occur when using incorrect usernames and passwords with NTLM, mismatched LmCompatibility settings between client and server, an incorrect service principal name, duplicate Kerberos service principal names, incorrect Kerberos ticket-granting service tickets, or Guest accounts without Guest access enabled</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>552</td><td>SMB2 Session Authentication Success</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>553</td><td>SMB2 Session Bound to Connection</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>554</td><td>SMB2 Session Terminated</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>555</td><td>SMB2 Session Closed.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>600</td><td>SMB2 TreeConnect Allocated</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>601</td><td>SMB2 TreeConnect Disconnected</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>602</td><td>SMB2 TreeConnect Terminated</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>603</td><td>SMB2 TreeConnect Failed due to Cluster Endpoint Initializing</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>650</td><td>SMB2 Open established</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>651</td><td>SMB2 Open Disconnected - Preserved</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>652</td><td>SMB2 Open Reconnected</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>653</td><td>SMB2 Open Suspended - Preserved</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>654</td><td>SMB2 Open Closed</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>655</td><td>SMB2 Open Timed Out</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>656</td><td>SMB2 Open Terminated</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>657</td><td>SMB2 Open Clustered Client Failover Closed</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>658</td><td>File handle for file &quot;%8\%2&quot; was invalidated by user %4 from computer %6</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>700</td><td>SMB2 Share Added</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>701</td><td>SMB2 Share Modified</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>702</td><td>SMB2 Share Deleted</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1000</td><td>S4U2Self authentication failure - The client could not be reauthenticated with S4U2Self to obtain claims.  This may be expected if the account is not a domain account.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1001</td><td>SRV Disabled - The SMB1 negotiate request fails due to SMB1 is disabled.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1001</td><td>A client attempted to access the server using SMB1 and was rejected because SMB1 file sharing support is disabled or has been uninstalled.

Guidance:

An administrator has disabled or uninstalled server support for SMB1. Clients running Windows XP / Windows Server 2003 R2 and earlier will not be able to access this server. Clients running Windows Vista / Windows Server 2008 and later no longer require SMB1. To determine which clients are attempting to access this server using SMB1, use the Windows PowerShell cmdlet Set-SmbServerConfiguration to enable SMB1 access auditing.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1002</td><td>RKF failure - SRV2 failed to get acknowledgement from Resume Key filter for persistent handle request.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1003</td><td>The server received an unencrypted message from client %4. Message was rejected.

Guidance:

This event indicates that a client is sending unencrypted data even though the SMB share requires encryption.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1003</td><td>The server received an unencrypted message from client when encryption was required. Message was rejected.

Client Name: %4
Client Address: %8
User Name: %6
Session ID: %9
Share Name: %2

Guidance:

This event indicates that a client is sending unencrypted data even though the SMB share requires encryption.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1004</td><td>The server received an incorrectly signed message from client %2. Message was rejected.

Guidance:

This event indicates that a client is sending an incorrectly signed request.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1004</td><td>The server rejected an incorrectly signed message.

Client Name: %2
Client Address: %6
User Name: %4
Session ID: %7

Guidance:

This event indicates that a client is sending an incorrectly signed request.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1005</td><td>The server failed to validate negotiation from client %2. Connection was terminated.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1005</td><td>The server rejected an invalid negotiation request. Connection was terminated.

Client Name: %2
Client Address: %6
User Name: %4
Session ID: %13
Expected Dialect: %7
Expected Capabilities: %8
Expected Security Mode: %9
Received Dialect: %10
Received Capabilities: %11
Received Security Mode: %12

Guidance:

This event indicates that a client is attempting to negotiate a second connection using a mismatched dialect or capabilities.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1005</td><td>Negotiate integrity check failed.

Status: %2
Client Name: %4
Client Address: %8
User Name: %6
Session ID: %9

Guidance:

This event indicates that the client&#39;s negotiate request was altered on the network between the client and server due to errors or a &quot;man-in-the-middle&quot; attack. The client has been disconnected to prevent a security downgrade.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1006</td><td>The share denied access to the client.

Client Name: %10
Client Address: %6
User Name: %8
Session ID: %17
Share Name: %2
Share Path: %4
Status: %16 (%15)
Mapped Access: %11
Granted Access: %12
Security Descriptor: %14

Guidance:

You should expect access denied errors when a principal accesses a share without the necessary permissions. Usually, this indicates that the principal does not have direct security permissions or lacks membership in a group that has direct access permissions. To determine and correct the permissions on the specified share, an administrator can use the Security tab in File Explorer Properties dialog, the SMBSHARE Windows PowerShell module, or the NET SHARE command. You can also use the Effective Access tab in File Explorer to help diagnose the issue.

Applications may generate access denied errors if they attempt to open files in a writable mode first, and then reopen the files in a read-only mode. In this case, no user action is required.

If access to the share is denied and this event is not logged, you can examine the file and folder NTFS/REFS permissions.

This error does not indicate a problem with authentication, only authorization.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1007</td><td>The share denied anonymous access to the client.

Client Name: %8
Client Address: %6
Share Name: %2
Share Path: %4

Guidance:

You should expect this error when a client attempts to connect to shares and does not provide any credentials. This indicates that the client is not providing a user name (and domain credentials, if necessary). By default, anonymous access to shares is denied.

This error does not always indicate a problem with authorization, but mainly authentication. It is more common with non-Windows clients.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1009</td><td>The server denied anonymous access to the client.

Client Name: %4
 Client Address: %2
Session ID: %5

Guidance:

You should expect this error when a client attempts to connect to shares and does not provide any credentials. This indicates that the client is not providing a user name (and domain credentials, if necessary). By default, Windows Server denies anonymous access to shares.

This error does not always indicate a problem with authorization, but mainly authentication. It is more common with non-Windows clients.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1010</td><td>Endpoint added.

Name: %2
Domain Name: %4
Transport Name: %6
Transport Flags: %7

Guidance:

You should expect this event when the server starts listening on an interface, such as during system restart or when enabling a network adaptor. No user action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1011</td><td>Endpoint removed.

Name: %2
Domain Name: %4
Transport Name: %6

Guidance:

You should expect this event when the server stops listening on an interface, such as during shutdown or when disabling a network adaptor. No user action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1012</td><td>The network name information changed.

Change Type: %1
Net Name: %3
IP Address: %9
Flags: %4
Interface Index: %5
Capability: %6
Link Speed: %7

Guidance:

You should expect this event on a Windows Failover Cluster node during failover operations, at system startup, or during network configuration. No user action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1013</td><td>Endpoint coming online.

Endpoint Name: %2
Transport Name: %4

Guidance:

You should expect this event on a Windows Failover Cluster node during failover operations. No user action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1014</td><td>Endpoint going offline.

Endpoint Name: %2
Transport Name: %4

Guidance:

You should expect this event on a Windows Failover Cluster node during failover operations. No user action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1015</td><td>Decrypt call failed.

Client Name: %2
Client Address: %4
Session ID: %7
Status: %6 (%5)

Guidance:

This event commonly occurs because a previous SMB session no longer exists. It may also be caused by packets that are altered on the network between the computers due to either errors or a &quot;man-in-the-middle&quot; attack.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1016</td><td>Reopen failed.

Client Name: %7
Client Address: %9
User Name: %13
Session ID: %14
Share Name: %11
File Name: %16
Resume Key: %20
Status: %2 (%1)
RKF Status: %4 (%3)
Durable: %17
Resilient: %18
Persistent: %19
Reason: %21

Guidance:

The client attempted to reopen a continuously available handle, but the attempt failed. This typically indicates a problem with the network or underlying file being re-opened.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1017</td><td>Handle scavenged.

Share Name: %7
File Name: %9
Resume Key: %5
Persistent File ID: %3
Volatile File ID: %4
Durable: %1
Resilient or Persistent: %2

Guidance:

The server closed a handle that was previously reserved for a client after 60 seconds. You should expect this event on a computer that is continuously available where a client did not gracefully close its session. For instance, this may occur when the client unexpectedly restarted.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1018</td><td>Backchannel invalidation of session completed.

Session ID: %1
Status: %3 (%2)
Task Status: %5 (%4)

Guidance:

You should expect this event on a computer that is continuously available. No user action is required</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1019</td><td>Backchannel invalidation of file completed.

Resume Key: %1
Status: %3 (%2)
Task Status: %5 (%4)

Guidance:

You should expect this event on a computer that is continuously available. No user action is required</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1020</td><td>File system operation has taken longer than expected.

Client Name: %8
Client Address: %10
User Name: %6
Session ID: %3
Share Name: %12
File Name: %14
Command: %1
Duration (in milliseconds): %15
Warning Threshold (in milliseconds): %16

Guidance:

The underlying file system has taken too long to respond to an operation. This typically indicates a problem with the storage and not SMB.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1020</td><td>File system operation has taken longer than expected.

Client Name: %8
Client Address: %10
User Name: %6
Session ID: %3
Share Name: %12
File Name: %14
Command: %1
Duration (in milliseconds): %15
Warning Threshold (in milliseconds): %16

Guidance:

The underlying file system has taken too long to respond to an operation. This typically indicates a problem with the storage and not SMB.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1021</td><td>LmCompatibilityLevel value is different from the default.

Configured LM Compatibility Level: %1
Default LM Compatibility Level: %2

Guidance:

LAN Manager (LM) authentication is the protocol used to authenticate Windows clients for network operations. This includes joining a domain, accessing network resources, and authenticating users or computers. This determines which challenge/response authentication protocol is negotiated between the client and the server computers. Specifically, the LM authentication level determines which authentication protocols the client will try to negotiate or the server will accept. The value set for LmCompatibilityLevel determines which challenge/response authentication protocol is used for network logons. This value affects the level of authentication protocol that clients use, the level of session security negotiated, and the level of authentication accepted by servers.

Value (Setting) - Description

0 (Send LM &amp; NTLM responses) - Clients use LM and NTLM authentication and never use NTLMv2 session security. Domain controllers accept LM, NTLM, and NTLMv2 authentication.

1 (Send LM &amp; NTLM - use NTLMv2 session security if negotiated) - Clients use LM and NTLM authentication, and use NTLMv2 session security if the server supports it. Domain controllers accept LM, NTLM, and NTLMv2 authentication.

2 (Send NTLM response only) - Clients use NTLM authentication only and use NTLMv2 session security if the server supports it. Domain controllers accept LM, NTLM, and NTLMv2 authentication.

3 (Send NTLM v2 response only) - Clients use NTLMv2 authentication only and use NTLMv2 session security if the server supports it. Domain controllers accept LM, NTLM, and NTLMv2 authentication.

4 (Send NTLMv2 response only/refuse LM) - Clients use NTLMv2 authentication only and use NTLMv2 session security if the server supports it. Domain controllers refuse LM and accept only NTLM and NTLMv2 authentication.

5 (Send NTLM v2 response only/refuse LM &amp; NTLM) - Clients use NTLMv2 authentication only and use NTLMv2 session security if the server supports it. Domain controllers refuse LM and NTLM and accept only NTLMv2 authentication.

Incompatibly configured  LmCompatibility levels between a client and server (such as 0 on a client and 5 on a server) prevent access to the server. Non-Microsoft clients and servers also provide these configuration settings.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1022</td><td>File and printer sharing firewall rule enabled.

Guidance:

You should expect this event when Windows Firewall is configured to enable the File and Printer Sharing rule, which allows inbound SMB traffic. This event occurs on a computer that has custom shares configured.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1023</td><td>One or more shares present on this server have access based enumeration enabled.

Guidance:

You should expect this event when enabling access-based enumeration on one or more shares by using either Server Manager or the Set-SmbShare Windows PowerShell cmdlet. Access-based enumeration can raise CPU utilization when clients connect to shares with folders containing many peer-level resources to which a user does not have access. You can control the CPU utilization by configuring the ABELevel value in the Windows registry:

HKEY_LOCAL_MACHINE\System\CurrentControlSet\Services\LanmanServer\Parameters\ABELevel [DWORD]

You can set the value for ABELevel to greater depths to minimize CPU overhead, but doing so diminishes the effectiveness of access-based enumeration:

Value = 0: access-based enumeration is enabled for all levels

Value = 1: access-based enumeration is enabled for a depth of 1 (example: \server\share)

Value = 2: access-based enumeration is enabled for a depth of 2 (example: \server\share\folder)

You can continue setting values for multiple depth levels.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1024</td><td>SMB2 and SMB3 have been disabled on this server.  This results in reduced functionality and performance.

Registry Key: HKLM\System\CurrentControlSet\Services\LanmanServer\Parameters
Registry Value: Smb2
Default Value: 1 (or not present)
Current Value: 0

Guidance:

You should expect this event when disabling SMB2/SMB3. Microsoft does not recommend disabling SMB2/SMB3. When SMB3 is disabled, you cannot use features such as SMB Transparent Failover, SMB Scale Out, SMB Multichannel, SMB Direct (RDMA), SMB Encryption, VSS for SMB file shares, and SMB Directory Leasing. In most scenarios, SMB provides a troubleshooting workaround as an alternative to disabling SMB2/SMB3. Use the Set-SmbServerConfiguration Windows PowerShell cmdlet to enable SMB2/SMB3.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1025</td><td>One or more named pipes or shares have been marked for access by anonymous users.  This increases the security risk of the computer by allowing unauthenticated users to connect to this server.

Registry Key: HKLM\System\CurrentControlSet\Services\LanmanServer\Parameters
Registry Values: NullSessionPipes, NullSessionShares
Default Value: Empty (or not present)
Current Value: Non-empty

Guidance:

You should expect this event when modifying the default values of NullSessionShares and NullSessionPipes. On a typical file server, these settings do not exist or do not contain values, which is the most secure configuration. By default, domain controllers populate the NullSessionShares entry with netlogon, samr, and lsarpc to allow legacy access methods.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1026</td><td>File leasing has been disabled for the SMB2 and SMB3 protocols.  This reduces functionality and can decrease performance.

Registry Key: HKLM\System\CurrentControlSet\Services\LanmanServer\Parameters
Registry Value: DisableLeasing
Default Value: 0 (or not present)
Current Value: non-zero

Guidance:

You should expect this event when disabling SMB 3 Leasing. Microsoft does not recommend disabling SMB Leasing. Once disabled, traffic from client to server may increase since metadata and data may no longer be retrieved from a local cache.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1027</td><td>The file and printer sharing firewall ports are currently closed.  This is the default configuration for a system that is not sharing content or is on a Public network.

Guidance:

You should expect this event when Windows Firewall is not configured to enable the File and Printer Sharing rule, which allows inbound SMB traffic. This event occurs on a computer that does not have custom shares configured. Clients cannot access SMB shares on this computer until SMB traffic is allowed through the firewall.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1028</td><td>The maximum cluster-supported SMB dialect has changed.

NewMaxDialect: %1
OldMaxDialect: %2

Guidance:

You should expect this event during a Windows Failover Cluster upgrade. No user action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1029</td><td>The Cipher Suite Order group policy setting is invalid.

Guidance:

This event indicates that an administrator has configured an invalid value for the &quot;Computer Configuration\Administrative Templates\Network\Lanman Server\Cipher Suite Order&quot; group policy setting. The server will use the default cipher suite order &quot;%1&quot; until this error is resolved.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1030</td><td>An MDL read or write completion request failed.

Server Name: %2
Share Name: %4
File Name: %6
IsRead: %7
Status: %8

Guidance:

The SMB server sends MDL completion requests to a file system upon completion of a buffered I/O to release system resources. The file system and its filter drivers must not fail MDL completion requests. Failures may result in memory leaks and degraded system performance and stability. Non-Microsoft file system filter drivers are the most common cause of failed MDL completion requests.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1031</td><td>The server detected a problem and has captured a live kernel dump to collect debug information.

Reason: %1
Dump Location: %SystemRoot%\LiveKernelReports

Guidance:

The server supports the Live Dump feature, where the detection of a problem results in a kernel memory dump, but no bugcheck and reboot. This allows Microsoft Support to examine memory dumps without requiring a reboot or manual intervention. The reason code indicates the type of problem that was detected.

Stalled I/O

An I/O is taking an unreasonably long time to complete. Malfunctioning third-party file system minifilter drivers are a common source of this problem. Other causes include failed disks or a client-driven I/O workload that greatly exceeds the server&#39;s capacity.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1032</td><td>The server detected a problem but was unable to capture a live kernel dump to collect debug information.

Reason: %1

Guidance:

The server supports the Live Dump feature, where the detection of a problem results in a kernel memory dump, but no bugcheck and reboot. This allows Microsoft Support to examine memory dumps without requiring a reboot or manual intervention. The reason code indicates the type of problem that was detected. In this case, the server&#39;s request to create a live kernel dump was rejected. This is usually due to the live kernel dump throttle, which prevents frequent dumps from consuming too much disk space. Either wait for the throttle limit to expire (by default, 7 days), or contact Microsoft Support for steps to override the throttle. This event is written to the log no more than once per day. The problem that caused the server to the request a live kernel dump may be occuring more frequently.

Stalled I/O

An I/O is taking an unreasonably long time to complete. Malfunctioning third-party file system minifilter drivers are a common source of this problem. Other causes include failed disks or a client-driven I/O workload that greatly exceeds the server&#39;s capacity.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1033</td><td>Sent RDMA %1 event to LanmanServer for interface %3.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1034</td><td>Send RDMA Endpoint notification failure - %1</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1035</td><td>RDMA Endpoint %4 for interface %2 was %1.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1036</td><td>RDMA Endpoint allocation failure - Endpoint allocation failed for interface %1. %2</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1037</td><td>RDMA listener creation failure - %1</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1038</td><td>RDMA Send endpoint notification RPC failure for device %3 - %1</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1039</td><td>Received Nsi notification type %1 for interface %2 with NdkOperationalState %3</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1040</td><td>Received Mib notification type %1 for interface %2</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1041</td><td>Error reading FSCTL properties information from the registry. Registry value entry %3 will be ignored. Error: %1</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1043</td><td>RDMA connection disconnected.

Transport name: %3
Milliseconds spent closing the connection: %1

Guidance:

Closing an RDMA connection should not take longer than 2 minutes. An RDMA IO that takes an abnormally long time to complete indicates a problem with the RDMA network adapters on this computer or its remote host. Contact your RDMA vendor for an updated driver and further troubleshooting.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1800</td><td>CA failure - Failed to set continuously available property on a new or existing file share as the file share is not a cluster share.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1801</td><td>CA failure - Failed to set continuously available property on a new or existing file share as Resume Key filter is not started or has failed to attach to the underlying volume.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1802</td><td>The server failed to reserve the next ID region in the cluster registry.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1803</td><td>The security descriptor differs from the default value.

 Path: HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanServer\DefaultSecurity\%1

 Guidance:

 This is typically caused by an administrator or a third party changing the security on the object manually. To reset the security back to the default value, delete the path shown above.
 Microsoft does not recommend changing the default security of %1 as it may cause application incompatibilities or security concerns.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1804</td><td>No SMB1 usage detected in the last 20 minutes.

Guidance:

This event indicates that no attempt was made to contact this computer via the SMB1 protocol. After %1 online days of no SMB1 contact attempts, the SMB1 Server service will automatically uninstall.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1900</td><td>TDI mode enabled: %1</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1901</td><td>Failed to allocate an NSI table for network interface enumeration: %1</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1902</td><td>Received notification of a newly-started network interface with Luid %2 on address family %1 (IPv4 == 2, IPv6 == 23)</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1903</td><td>Received notification of a stopped network interface with Luid %2 on address family %1 (IPv4 == 2, IPv6 == 23)</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1904</td><td>Failed to open network interface with Luid %1: error %2</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>1905</td><td>The server closed the session as part of periodic system cleanup.

Session Id: %1
Instance Id: %2
Reason: %3
</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>2000</td><td>Packet Fragment (%2 bytes)</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>3000</td><td>SMB1 access

Client Address: %1

Guidance:

This event indicates that a client attempted to access the server using SMB1. To stop auditing SMB1 access, use the Windows PowerShell cmdlet Set-SmbServerConfiguration.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>3002</td><td>A remote device attempted SMB1 connection to this computer.

Client Address: %1

Guidance:

This event indicates that a client attempted to access the server using SMB1. To stop auditing SMB1 access, use the Windows PowerShell cmdlet Set-SmbServerConfiguration.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>3003</td><td>SMB1 server service has been automatically uninstalled.n
Guidance:

This event indicates that after detecting no attempts to contact this computer via the SMB1 protocol for %1 online days, the SMB1 Server service was automatically uninstalled.</td></tr>
<tr><td>Microsoft-Windows-SMBServer</td><td>40000</td><td>Packet (%4 bytes)</td></tr>
</table>
