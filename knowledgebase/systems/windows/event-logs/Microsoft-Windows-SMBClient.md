# Microsoft-Windows-SMBClient

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>101</td><td>Create SrvCall Error: %1 Location: %2 Context: %3</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>201</td><td>Session Setup Error: %1 Location: %2 Context: %3</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>301</td><td>Tree Connect Error: %1 Location: %2 Context: %3</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>401</td><td>Create VNetRoot Error: %1 Location: %2 Context: %3</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>501</td><td>Create File Error: %1 Location: %2 Context: %3</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>2000</td><td>Packet Fragment (%2 bytes)</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>20001</td><td>Transitioned to State: %1 Context: %2</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30103</td><td>SMB exchange suspended: RxContext %1 Exchange %2 ListHead %3</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30104</td><td>SMB exchange resumed: RxContext %1 Exchange %2 ExchangeState %3 ExchangeStatus %4</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30105</td><td>SMB buffer context suspended: BufferCtxt %1 Exchange %2 MidCharge %3 Window %4 CurrentWindowLimit %5 ThrottlingWindowLimit %6 CurrentWindowSize %7</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30106</td><td>SMB buffer context resumed: BufferCtxt %1 Exchange %2 MidCharge %3 Window %4 CurrentWindowLimit %5 ThrottlingWindowLimit %6 CurrentWindowSize %7</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30108</td><td>SMB Mid window blocked: Window %1 HungSession %2</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30109</td><td>SMB rechunk multi-credit request: BufferCtxt %1 Exchange %2 MidCharge %3 Window %4 CurrentWindowLimit %5 ThrottlingWindowLimit %6 CurrentWindowSize %7</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30110</td><td>SMB initialize Mid window: Server %2 Window %3</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30111</td><td>SMB Mid window state: Window %1 CurrentWindowSize %2 CurrentWindowLimit %3 ThrottlingWindowLimit %4 OldestPendingMid %5 NextAvailableMid %6 CreditsGranted %7</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30112</td><td>SMB teardown Mid window: Server %2 Window %3</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30113</td><td>SMB copy data completion: Status %1 VcEndpoint %2</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30114</td><td>SMB send completion: Status %1 VcEndpoint %2</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30203</td><td>WSK connect: SocketAddress %2 VcEndpoint %3 Socket %4</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30204</td><td>WSK connect completion: VcEndpoint %1 Socket %2 Status %3</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30205</td><td>WSK send: VcEndpoint %1 Socket %2 SendMdl %3 SendLength %4</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30206</td><td>WSK send completion: VcEndpoint %1 Socket %2 SendMdl %3 SendLength %4 Status %5</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30207</td><td>WSK receive: VcEndpoint %1 Socket %2 ReceiveMdl %3 ReceiveLength %4</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30208</td><td>WSK receive completion: VcEndpoint %1 Socket %2 ReceiveMdl %3 ReceiveLength %4 Status %5</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30401</td><td>SMB session expired: SessionEntry %1 ServerName %3</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30402</td><td>SMB 3 part SPN reauth: SessionEntry %1 ServiceName %3</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30403</td><td>SMB reconnect durable open: Fcb %1 SrvOpen %2</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30404</td><td>SMB defer open: Fcb %1 SrvOpen %2</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30405</td><td>SMB undefer open: Fcb %1 SrvOpen %2</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30406</td><td>SMB send[%1]: [%2] (Mid/Sid/Tid) (%3/%4/%5) MidCharge %6 Creds %7 SendLengh %8 VcEndpoint %9</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30407</td><td>SMB receive: [%1] (Mid/Sid/Tid) (%2/%4/%5) Creds %6 Status %7 VcEndpoint %8</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30408</td><td>SMB receive interim: [%1] (Mid/AsyncId/Sid/Tid) (%2/%3/%4/%5) Creds %6 Status %7 VcEndpoint %8</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30409</td><td>SMB receive async: [%1] (AsyncId/Sid/Tid) (%3/%4/%5) Creds %6 Status %7 VcEndpoint %8</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30410</td><td>SMB registry key: %1 = %2</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30501</td><td>SMB update file info cache: RxContext %1 Fcb %2 FileName %4</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30502</td><td>SMB fetch file info cache: RxContext %1 Fcb %2 FileName %4 Status %5</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30503</td><td>SMB invalidate file info cache: RxContext %1 Fcb %2 FileName %4</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30504</td><td>SMB update file not found cache: RxContext %1 Fcb %2 FileName %4</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30505</td><td>SMB fetch file not found cache: RxContext %1 Fcb %2 FileName %4 Result %5</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30506</td><td>SMB invalidate file not found cache: RxContext %1 Fcb %2 FileName %4</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30507</td><td>SMB populate dir cache: RxContext %1 Fcb %2 DirName %4</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30508</td><td>SMB fetch dir cache: RxContext %1 Fcb %2 FileName %4 Status %5</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30600</td><td>Session %1 to %6 transitioned from [%2] to [%3] with Status %4</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30601</td><td>Share connection %1 to %6 transitioned from [%2] to [%3] with Status %4</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30603</td><td>Open handle %1 to %10%12 transitioned from [%5] to [%6] with Status %7</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30604</td><td>The local computer didn&#39;t received an SMB1 negotiate response in the last 20 minutes.n
Guidance:

This event indicates that no attempt was made to contact this computer via the SMB1 protocol. After %1 online days of no SMB1 contact attempts, the SMB1 Client service will automatically uninstall.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30611</td><td>Failed to reconnect a persistent handle.

Error: %7

FileId: %2:%3
CreateGUID: %4
Path: %10%12

Reason: %8

Previous reconnect error: %13
Previous reconnect reason: %14

Guidance:
A persistent handle allows transparent failover on Windows File Server clusters. This event has many causes and does not always indicate an issue with SMB. Review online documentation for troubleshooting information.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30612</td><td>Failed to reconnect a resilient handle.

Error: %7

FileId: %2:%3
Path: %10%12

Reason: %8.

Previous reconnect error: %13
Previous reconnect reason: %14

Guidance:
A resilient handle provides guarantees to applications requesting it. This event has many causes and does not always indicate an issue with SMB. Review online documentation for troubleshooting information.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30613</td><td>Failed to open a persistent handle.

Error: %7

FileId: %2:%3
CreateGUID: %4
Path: %10%12

Reason: %8

Guidance:
A persistent handle allows transparent failover on Windows File Server clusters. This event has many causes and does not always indicate an issue with SMB. Review online documentation for troubleshooting information.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30701</td><td>An invalid FSCTL_QUERY_NETWORK_INTERFACE_INFO response was sent by the server %2</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30702</td><td>The client failed to connect to the server %2 from the local IP address %4 to the remote IP address %6 over TCP transport. Error: %7</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30703</td><td>The client failed to connect to the server %2 from the local IP address %4 to the remote IP address %6 over RDMA transport. Error: %7</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30704</td><td>The client connected to the server %2 from the local IP address %4 to the remote IP address %6 over TCP transport successfully</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30705</td><td>The client connected to the server %2 from the local IP address %4 to the remote IP address %6 over RDMA transport successfully</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30800</td><td>The server name cannot be resolved.

Error: %2

Server name: %4

Guidance:
The client cannot resolve the server address in DNS or WINS. This issue often manifests immediately after joining a computer to the domain, when the client&#39;s DNS registration may not yet have propagated to all DNS servers. You should also expect this event at system startup on a DNS server (such as a domain controller) that points to itself for the primary DNS. You should validate the DNS client settings on this computer using IPCONFIG /ALL and NSLOOKUP.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30801</td><td>%1.

Error: %2

Server name: %4</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30802</td><td>%1.

Error: %2

Server name: %4</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30803</td><td>Failed to establish a network connection.

Error: %2

Server name: %4
Server address: %6
Connection type: %7

Guidance:
This indicates a problem with the underlying network or transport, such as with TCP/IP, and not with SMB. A firewall that blocks TCP port 445, or TCP port 5445 when using an iWARP RDMA adapter, can also cause this issue.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30803</td><td>Failed to establish a network connection.

Error: %2

Server name: %4
Server address: %6
Instance name: %9
Connection type: %10

Guidance:
This indicates a problem with the underlying network or transport, such as with TCP/IP, and not with SMB. A firewall that blocks TCP port 445, or TCP port 5445 when using an iWARP RDMA adapter, can also cause this issue.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30804</td><td>A network connection was disconnected.

Server name: %4
Server address: %6
Connection type: %7

Guidance:
This indicates that the client&#39;s connection to the server was disconnected.

Frequent, unexpected disconnects when using an RDMA over Converged Ethernet (RoCE) adapter may indicate a network misconfiguration. RoCE requires Priority Flow Control (PFC) to be configured for every host, switch and router on the RoCE network. Failure to properly configure PFC will cause packet loss, frequent disconnects and poor performance.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30805</td><td>The client lost its session to the server.

Error: %1

Server name: %5
Session ID: %2

Guidance:
If the server is a Windows Failover Cluster file server, then this message occurs when the file share moves between cluster nodes. There should also be an anti-event 30806 indicating the session to the server was re-established. If the server is not a failover cluster, it is likely that the server was previously online, but it is now inaccessible over the network.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30806</td><td>The client re-established its session to the server.

Server name: %5
Server address: %7
Session ID: %2

Guidance:
You should expect this event if there was a previous event 30805, but the client successfully resumed the cached connection before the timeout expired.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30807</td><td>The connection to the share was lost.

Error: %1

Share name: %5
Session ID: %2
Tree ID: %3

Guidance:
If the server is a Windows Failover Cluster file server, then this message occurs when the file share moves between cluster nodes. There should also be an anti-event 30808 indicating the session to the server was re-established. If the server is not a failover cluster, it is likely that the server was previously online, but it is now inaccessible over the network.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30808</td><td>The connection to the share was re-established.

Share name: %5
Server address: %7
Session ID: %2
Tree ID: %3

Guidance:
You should expect this event if there was a previous event 30807, but the client successfully resumed the cached connection before the timeout expired.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30809</td><td>A request timed out because there was no response from the server.

Server name: %6
Session ID:%3
Tree ID:%4
Message ID:%2
Command: %1
Instance Name: %9
RetryCount: %10
ElapsedTime(ms): %11

Guidance:
The server is responding over TCP but not over SMB. Ensure the Server service is running and responsive, and the disks do not have high per-IO latency, which makes the disks appear unresponsive to SMB. Also, ensure the server is responsive overall and not paused; for instance, make sure you can log on to it.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30810</td><td>Added a TCP/IP transport interface.

Name: %2
InterfaceIndex: %3

Guidance:
A TCP/IP binding was added to the specified network adapter for the SMB client. The SMB client can now send and receive SMB traffic on this network adapter using TCP/IP. You should expect this event when a computer restarts or when a previously disabled network adaptor is re-enabled. No user action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30811</td><td>Deleted a TCP/IP transport interface.

Name: %2
InterfaceIndex: %3

Guidance:
A TCP/IP binding was removed from the specified network adapter for the SMB client. You should expect this event when a computer shuts down or when a previously enabled network adaptor is disabled. No user action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30812</td><td>Added a TDI transport interface.

Name: %2

Guidance:
A TDI (NetBIOS) binding was added to the specified network adapter for the SMB client. The SMB client can now send and receive SMB traffic on this network adapter using TDI. You should expect this event when a computer restarts or when a previously disabled network adaptor is re-enabled. No user action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30813</td><td>Deleted a TDI transport interface.

Name: %2

Guidance:
A TDI (NetBIOS) binding was removed from the specified network adapter for the SMB client. You should expect this event when a computer shuts down or when a previously enabled network adaptor is disabled. No user action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30814</td><td>Witness registration has completed.

Status: %1

Cluster share name: %4
Cluster share type: %2
File server cluster address: %6

Guidance:
The client successfully registered with the SMB Witness through RPC using TCP (port 135, then an endpoint port above 1023). No action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30815</td><td>Witness deregistration has completed.

Status: %1

Cluster share name: %4
Cluster share type: %2

Guidance:
The client successfully de-registered with the SMB Witness through RPC using TCP (port 135, then an endpoint port above 1023). No action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30816</td><td>The server failed the negotiate request.

Error: %2

Server name: %4

Guidance:
The server does not support any dialect that the client is trying to negotiate, such as the client has SMB2/SMB3 disabled and the server has SMB1 disabled.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30817</td><td>Close request failed.

Error: %2

Path: %4%6

Guidance:
A persistent handle (Continuous Availability) or a resilient handle failed to close.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30818</td><td>RDMA interfaces are available but the client failed to connect to the server over RDMA transport.

Server name: %2

Guidance:
Both client and server have RDMA (SMB Direct) adaptors but there was a problem with the connection and the client had to fall back to using TCP/IP SMB (non-RDMA).</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30819</td><td>The SMB client received a request to move to a different node on a file server cluster.

File server cluster name: %4
New file server cluster address: %6

Guidance:
Continuous Availability (Transparent Failover) is in use and the client computer is going to move to a different node after an SMB witness request over RPC using TCP (first contacting port 135, then contacting an endpoint port above 1023). No user action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30820</td><td>The SMB client successfully moved to a different node on a file server cluster.

File server cluster name: %4
 New file server cluster address: %6

Guidance:
Continuous Availability (Transparent Failover) is in use and the client computer successfully moved to a different node after an SMB witness request over RPC using TCP (first contacting port 135, then contacting an endpoint port above 1023). No user action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30821</td><td>The SMB client failed to move to a different node on a file server cluster.

Error: %1

File server cluster name: %4

Guidance:
Continuous Availability (Transparent Failover) is in use and the client computer failed to move to a different node after an SMB witness request over RPC using TCP (first contacting port 135, then contacting an endpoint port above 1023). The attempt to connect to the destination server failed, which is typically due to a network configuration issue. For example, this issue may occur if the destination node&#39;s IP address cannot be resolved, if the destination node is behind a firewall, or if there is no network route from the client to the node.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30822</td><td>Failed to establish an SMB multichannel network connection.

Error: %2

Server name: %4
Server address: %6
Client address: %7
Instance name: %9
Connection type: %10

Guidance:
This indicates a problem with the underlying network or transport, such as with TCP/IP, and not with SMB. A firewall that blocks TCP port 445, or TCP port 5445 when using an iWARP RDMA adapter, can also cause this issue. Since the error occurred while trying to connect extra channels, it will not result in an application error. This event is for diagnostics only.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30823</td><td>The connection was terminated due to one or more IO request timeouts.

Error: %2

Name: %4
Server address: %6
Client address: %7
Instance name: %9
Connection type: %10

Guidance:
This indicates a problem with the underlying network or the storage stack on the remote server. IO operations were not completed within the allotted time. The application may not see this failure because IOs are usually retried on a different connection. This event is for diagnostics only.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30828</td><td>The client established its session to the server.

Server name: %4
Server address: %6!S!
Client address: %8!S!
Session ID: %2</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30829</td><td>The client failed to establish its session to the server.

Error: %1

Server name: %4
Server address: %6!S!
Client address: %8!S!
Session ID: %2</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30900</td><td>The handle was created without persistence.

File ID: %2:%3
CreateGUID: %4
Path: %10%12

Guidance:
The server supports Continuous Availability (persistent handles) and the request to create the handle succeeded. However, the server did not grant persistence. You should verify that the Resume Key Filter is running on the server and is attached to the target volume.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30904</td><td>The server does not support multichannel.

Server name: %2

Guidance:
The client attempted to use SMB Multichannel, but an administrator has disabled multichannel support on the server. This may also be a non-Microsoft file server that does not support multichannel or has multichannel disabled. You can enable SMB Multichannel on the server using this Windows PowerShell cmdlet: Set-SmbServerConfiguration -EnableMultiChannel:$true. This event does not apply to the multichannel settings of SMB client, which are controlled by the Set-SmbClientConfiguration Windows PowerShell cmdlet. Enabling or disabling client multichannel support does not affect server multichannel support.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30905</td><td>The client cannot connect to the server due to a multichannel constraint registry setting.

Server name: %2

Guidance:
The client attempted to use SMB Multichannel, but an administrator has configured multichannel support to prevent multichannel on the client. You can configure SMB Multichannel on the client using the Windows PowerShell cmdlets: New-SmbMultichannelConstraint and Remove-SmbMultichannelConstraint.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30906</td><td>A request on persistent/resilient handle failed because the handle was invalid or it exceeded the timeout.

Status: %7

Type: %1
Path: %4%6
Restart count: %2

Guidance:
After retrying a request on a Continuously Available (Persistent) handle or a Resilient handle, the client was unable to reconnect the handle. This event is the result of a handle recovery failure. Review other events for more details.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30907</td><td>The SMB Multichannel registry value is not configured with default settings.

Default Registry Value:
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanWorkstation\Parameters]
&quot;DisableMultiChannel&quot;=dword:0
Configured Registry Value:
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanWorkstation\Parameters]
&quot;DisableMultiChannel&quot;=dword:%2

Guidance:
You can configure SMB Multichannel on the client using the Windows PowerShell cmdlet Set-SmbClientConfiguration. Disabling SMB client multichannel support is not a recommended configuration, as it can lead to degraded performance and decreased reliability if one channel or network path fails.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30908</td><td>The SMB 3 and SMB 2 driver is not configured with the default start type.

Default Start Type: DEMAND_START
Configured Start Type: DISABLED

Guidance:
You should expect this event when disabling SMB2/SMB3 for the client using SC.EXE or editing the Windows registry. Microsoft does not recommend disabling SMB2/SMB3. Disabling SMB2/SMB3 prevents use of features such as SMB Transparent Failover, SMB Scale Out, SMB Multichannel, SMB Direct (RDMA), SMB Encryption, VSS for SMB file shares, and SMB Directory Leasing. SMB provides alternative troubleshooting workarounds to disabling SMB2/SMB3 in most cases.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30909</td><td>The client supports SMB Direct (RDMA) and SMB Signing is in use.

Share name: %2

Guidance:
For optimal SMB Direct performance, you can disable SMB Signing. This configuration is less secure and you should only consider this configuration on trustworthy private networks with strict access control.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30910</td><td>The client supports SMB Direct (RDMA) and SMB Encryption is in use.

Share name: %2

Guidance:
For optimal SMB Direct performance, you can disable SMB Encryption on the server for shares accessed by this client. This configuration is less secure and you should only consider this configuration on trustworthy private networks with strict access control.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30911</td><td>The Cipher Suite Order group policy setting is invalid.

Guidance:

This event indicates that an administrator has configured an invalid value for the &quot;Computer Configuration\Administrative Templates\Network\Lanman Workstation\Cipher Suite Order&quot; group policy setting. The client will use the default cipher suite order &quot;%1&quot; until this error is resolved.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>30912</td><td>The RequireSecureNegotiate setting has been removed.

Registry Key: HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanWorkstation\Parameters
Registry Value: RequireSecureNegotiate

Guidance:

You should expect this event when an administrator configures the RequireSecureNegotiate setting. Secure negotiate prevents man-in-the-middle attacks against SMB connection establishment. Previous versions of Windows allowed secure negotiate to be disabled. Disabling secure negotiate is no longer allowed. The client removed the setting from the registry. No user action is required.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>31000</td><td>%1.

Error: %2

Security status: %3
User name: %10
Logon ID: %4
Serrver name: %6</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>31001</td><td>%1.

Error: %2

Security status: %3
User name: %10
Logon ID: %4
Server name: %6
Principal name: %8</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>31002</td><td>The outbound authentication failed using a network token.

Error: %2

Server name: %4

Guidance:
This typically indicates that delegation must be configured for a Kerberos double-hop scenario. If delegation is configured, confirm that the services are configured correctly on the middle-tier server.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>31003</td><td>The LmCompatibilityLevel value is different from the default.

Configured LM Compatibility Level: %2
Default LM Compatibility Level: 3

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
<tr><td>Microsoft-Windows-SMBClient</td><td>31010</td><td>The SMB client failed to connect to the share.

Error: %2

Path: %4%6</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>31012</td><td>The negotiate validation failed.

From negotiate response:
Dialect: %1
SecurityMode: %2
Capabilities: %3
ServerGuid: %4

From FSCTL_VALIDATE_NEGOTIATE_INFO response:
Dialect: %5
SecurityMode: %6
Capabilities: %7
ServerGuid: %8

Guidance:
The client successfully negotiated SMB dialect, security mode, capabilities and server GUID with the server, but the validation of these values then failed after connecting to a share. This may be due to a &quot;man-in-the-middle&quot; compromise attempt.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>31013</td><td>The signing validation failed.

Error:%7

Server name: %6
Session ID:%3
Tree ID:%4
Message ID:%2
Command: %1

Guidance:
This error indicates that SMB messages are being modified in transit across the network from the server to the client. This may be due to the session ending on the server, a problem with the network, a problem with a third-party SMB server, or a &quot;man-in-the-middle&quot; compromise attempt.

PacketFragment:%9</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>31014</td><td>The client received an unencrypted message when encryption was expected.

Server name: %6
Session ID:%3
Tree ID:%4
Message ID:%2
Command: %1
Instance Name: %9

Guidance:
This error indicates that SMB messages are being modified in transit across the network from the server to the client. This may be due to the session ending on the server, a problem with the network, a problem with a third-party SMB server, or a &quot;man-in-the-middle&quot; compromise attempt.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>31015</td><td>Failed to decrypt an encrypted SMB message.

Error:%7

Server name: %6
Session ID:%3
Instance Name: %9

Guidance:
The client received an encrypted SMB message but cannot decrypt the data. This typically means that the communication came from a previous session that no longer exists. The encryption header may also have been damaged or tampered with on the network between the client and server.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>31016</td><td>The SMB Signing registry value is not configured with default settings.

Default Registry Value:
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanWorkstation\Parameters]
&quot;EnableSecuritySignature&quot;=dword:1
Configured Registry Value:
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanWorkstation\Parameters]
&quot;EnableSecuritySignature&quot;=dword:0

Guidance:
Even though you can disable, enable, or require SMB Signing, the negotiation rules changed starting with SMB2 and not all combinations operate like SMB1.

The effective behavior for SMB2/SMB3 is:
Client Required and Server Required = Signed
Client Not Required and Server Required = Signed
Server Required and Client Not Required = Signed
Server Not Required and Client Not Required = Not Signed

When requiring SMB Encryption, SMB Signing is not used, regardless of settings. SMB Encryption implicitly provides the same integrity guarantees as SMB Signing.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>31017</td><td>Rejected an insecure guest logon.

User name: %2
Server name: %4

Guidance:
This event indicates that the server attempted to log the user on as an unauthenticated guest and was denied by the client. Guest logons do not support standard security features such as signing and encryption. As a result, guest logons are vulnerable to man-in-the-middle attacks that can expose sensitive data on the network. Windows disables insecure guest logons by default. Microsoft does not recommend enabling insecure guest logons.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>31018</td><td>The %1 registry value is not configured with default settings.

Default Registry Value:
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanWorkstation\Parameters]
&quot;%1&quot;=dword:0
Configured Registry Value:
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanWorkstation\Parameters]
&quot;%1&quot;=dword:%2

Guidance:
This event indicates that an administrator has enabled insecure guest logons. An insecure guest logon occurs when a server logs the user on as an unauthenticated guest, typically in response to an authentication failure. Guest logons do not support standard security features such as signing and encryption. As a result, allowing guest logons makes the client vulnerable to man-in-the-middle attacks that can expose sensitive data on the network. Windows disables insecure guest logons by default. Microsoft does not recommend enabling insecure guest logons.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>31019</td><td>Mutual authentication was unexpectedly lost after re-authenticating to %6
User %8
LogonID %4
Status %2
 AuthProtocol Old %9  New %10
MutualAuthState Old %11 New %12
Clustered %13
</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>32000</td><td>SMB1 negotiate response received from remote device when SMB1 cannot be negotiated by the local computer. 

Dialect: %1

 Server name: %3

 Guidance:
The client has SMB1 disabled or uninstalled. For more information: https://go.microsoft.com/fwlink/?linkid=852747.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>32002</td><td>The local computer received an SMB1 negotiate response.

Dialect: %1

 SecurityMode %3

 Server name: %5

 Guidance:
 SMB1 is deprecated and should not be installed nor enabled. For more information, see https://go.microsoft.com/fwlink/?linkid=852747.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>32003</td><td>The local computer didn&#39;t received an SMB1 negotiate response in the last %1 days.n
Guidance:

This event indicates that after detecting no attempts to contact this computer via the SMB1 protocol for %1 online days, the SMB1 Client service was automatically uninstalled.</td></tr>
<tr><td>Microsoft-Windows-SMBClient</td><td>40000</td><td>Packet (%4 bytes)</td></tr>
</table>
