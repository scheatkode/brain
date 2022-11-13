# Microsoft-Windows-Wired-AutoConfig

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>13021</td><td>A pre-logon connection was not attempted.

Result: %1
Reason: %2
</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>13022</td><td>A pre-logon connection was attempted.

Result: %1
Interface GUID: %2
Requested Fields: %3
</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>13031</td><td>A post-logon connection was not attempted.

Result: %1
Reason: %2
</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>13032</td><td>A post-logon connection was attempted.

Result: %1
Interface GUID: %2
</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>13033</td><td>The post-logon connection attempt is complete.

Network connection attempt result: %1
Reason: %2
Interface GUID: %3
</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15500</td><td>The network adapter has been unplugged.

	Network Adapter: %2
	Interface GUID: %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15501</td><td>The network adapter has been connected.

	Network Adapter: %2
	Interface GUID: %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15502</td><td>The profile was applied on the network adapter.

	Network Adapter: %2
	Interface GUID: %1
	Profile Type: %3
	Profile Content: %4</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15503</td><td>Wired 802.1X Authentication was started.

	Network Adapter: %2
	Interface GUID: %1
	Connection ID: %3</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15504</td><td>Wired 802.1X Authentication was restarted.

	Network Adapter: %2
	Interface GUID: %1
	Connection ID: %3
	Restart Reason: %4</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15505</td><td>Wired 802.1X Authentication succeeded.

	Network Adapter: %2
	Interface GUID: %1
	Peer Address: %3
	Local Address: %4
	Connection ID: %5
	Identity: %6
	User: %7
	Domain: %8
	Reason: %9
	Reason Text: %10
	Error Code: %11</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15506</td><td>Network authentication attempts have been temporarily suspended on this network adapter.

	Network Adapter: %2
	Interface GUID: %1
	Reason Code: %3
	Length of block timer (seconds): %4</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15507</td><td>Network authentication attempts have been resumed on this network adapter.

	Network Adapter: %2
	Interface GUID: %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15508</td><td>There has been an NDIS Port state change on this network adapter.

	Network Adapter: %2
	Interface GUID: %1
	NDIS Control State: %3
	NDIS Auth State: %4</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15509</td><td>The operational state on the network adapter was identified.

	Network Adapter: %2
	Interface GUID: %1
	Service State: %3</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15510</td><td>A network adapter was added to the system.

	Network Adapter: %2
	Interface GUID: %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15511</td><td>The Wired AutoConfig service entered the running state.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15512</td><td>The Wired AutoConfig service entered the stopped state.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15513</td><td>A network adapter was removed from the system.

	Network Adapter: %2
	Interface GUID: %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15514</td><td>Wired 802.1X Authentication failed.

	Network Adapter: %2
	Interface GUID: %1
	Peer Address: %3
	Local Address: %4
	Connection ID: %5
	Identity: %6
	User: %7
	Domain: %8
	Reason: %9
	Reason Text: %10
	Error Code: %11</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15515</td><td>The Wired AutoConfig service is starting.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>15516</td><td>The Wired AutoConfig service is stopping.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20001</td><td>No interactive console session to send UI request</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20002</td><td>ACM: IntfCompleteTimely failed, error %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20003</td><td>There are no available connections</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20004</td><td>MSM failed to initialize the interface, error %1.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20005</td><td>Failed to load profile, error %1.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20006</td><td>No profile found in db, error %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20007</td><td>ACM: UI request could not be sent.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20008</td><td>IntfCompletePlap failed, error %1.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20009</td><td>Interface does not have any available networks</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20010</td><td>Invalid state of the adapter %1.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20011</td><td>Media is disconnected, SSO can&#39;t be done</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20012</td><td>Failed to make the PLAP runtime state , error %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20013</td><td>Failed to make the timely runtime state , error %1.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20014</td><td>Interface does not have a profile</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20015</td><td>OneXSetEapUserData failed, error %1.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20016</td><td>AcmQueryUserDataProperties failed, error %1.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20017</td><td>Dot3AcmQueryUserDataByGuid failed, error %1.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20018</td><td>DsRoleGetPrimaryDomainInformation failed, error %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20019</td><td>Adapter is connected , we have a valid IP</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20020</td><td>Don&#39;t have time to wait for DC connectivity. Returning now</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20021</td><td>Waiting for DC connectivity</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20022</td><td>Wait for ip address change successfully completed</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20024</td><td>Wait for ip address change timed out</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20025</td><td>Wait for ip address change failed with error (%1)</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20026</td><td>Waiting for ip address change notification</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20028</td><td>Wait for 1x completion successfully completed</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20029</td><td>Adapter not connected. Returning now.</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20030</td><td>1x completed with a failure %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20031</td><td>Wait for 1x completion failed with return code (%1)</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20032</td><td>Wait for 1x completion timed out</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20033</td><td>IntfDoTimely took longer than our timeout allows. Returning now</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20034</td><td>IntfDoTimely completed successfully</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20035</td><td>IntfDoTimely failed, error %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20036</td><td>No TIMELY profiles were found. Completing the timely processing</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20037</td><td>Timely1x - Interface %1, profile %3 - Start %4, Stop %5</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>20038</td><td>FindTimelyIntfAndProfile failed, error %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21001</td><td>DeviceLayerOpenHandle failed, Error %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21002</td><td>DeviceLayerQueryOID failed %1, OID %3</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21003</td><td>DeviceLayerSetOID failed %1, OID %3</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21004</td><td>DeviceLayerSendPacket failed, %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21005</td><td>DeviceLayerReceivePacket failed, %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21006</td><td>Packet only %4 bytes, skipped</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21007</td><td>Invalid packet type %4, skipped</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21008</td><td>The read request was cancelled</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21009</td><td>Receiving data error %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21010</td><td>Packet skipped, error %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21011</td><td>Send data failed, error %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21012</td><td>Interface(%4): pAcmConnectionProgress failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21013</td><td>Interface(%4): pAcmQueryUserData failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21014</td><td>Interface(%4): pAcmSetMsmProfile failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21015</td><td>Interface(%4): pAcmSetUserData failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21016</td><td>Interface(%4): pAcmMsmNotify failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21017</td><td>Interface(%4): pAcmMediaChange failed, error %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21018</td><td>Interface(%4): pAcmUIRequest failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21019</td><td>Interface(%4): pAcmConnectionCompletionRoutine failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21020</td><td>Interface(%1): State Transition %3 --&gt; %4</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21021</td><td>Interface(%4): Received AuthNotStarted result from 1x</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21022</td><td>Interface(%4): Received AuthInvalid result from 1x</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21023</td><td>Interface(%1): Start processing event: (%3)</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21024</td><td>Interface(%1): Completed processing event: (%3)</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21025</td><td>Interface(%4): StartOneXAuth failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21026</td><td>Interface(%4): SendOneXPacket failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21027</td><td>Interface(%4): TIMING OUT 802.1x Authentication</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21028</td><td>Interface(%4): NOT TIMING OUT 802.1x authentication, next timer in %3 msec</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21029</td><td>Interface(%4): DeviceLayerGetCurrentMediaState failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21030</td><td>No 1X port exists. Ignoring the packet received</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21031</td><td>Interface(%1): Set the SWITCH MAC address to %2</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21032</td><td>Interface(%4): OpenDeviceHandle failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21033</td><td>Interface(%1): Start processing event (%3)</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21034</td><td>Interface(%1): ProcessDot3MsmEvent:  Dot3MsmPerformStateMachineProcessing FAILed (%4), Event=%3</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21035</td><td>Interface(%1): Completed processing event (%3)</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21036</td><td>Finished initializing a new interface with id = %1 and friendly name = %2</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21037</td><td>Dot3MsmInit failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21038</td><td>Dot3MSMInitAdapter failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21039</td><td>Failed to parse original request %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21040</td><td>Failed to parse UI Response %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21041</td><td>Interface(%4): OneXUIResponse failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21042</td><td>Interface(%4): Dot3MsmQueryPendingUIRequest failed %1</td></tr>
<tr><td>Microsoft-Windows-Wired-AutoConfig</td><td>21043</td><td>OneXValidateProfile failed %1</td></tr>
</table>
