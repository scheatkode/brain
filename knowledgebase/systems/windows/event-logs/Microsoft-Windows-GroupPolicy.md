# Microsoft-Windows-GroupPolicy

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1002</td><td>The processing of Group Policy failed because of a system allocation failure. Please ensure the computer is not running low on resources (memory, available disk space). Group Policy processing will be attempted at the next refresh cycle.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1006</td><td>The processing of Group Policy failed. Windows could not authenticate to the Active Directory service on a domain controller. (LDAP Bind function call failed). Look in the details tab for error code and description.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1007</td><td>The processing of Group Policy failed. Windows could not determine the site associated for this computer, which is required for Group Policy processing.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1030</td><td>The processing of Group Policy failed. Windows attempted to retrieve new Group Policy settings for this user or computer. Look in the details tab for error code and description. Windows will automatically retry this operation at the next refresh cycle. Computers joined to the domain must have proper name resolution and network connectivity to a domain controller for discovery of new Group Policy objects and settings. An event will be logged when Group Policy is successful.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1052</td><td>The processing of Group Policy failed. Windows could not determine the role of this computer. Role information (Workgroup, Member Server, or Domain Controller) is required to process Group Policy.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1053</td><td>The processing of Group Policy failed. Windows could not resolve the user name. This could be caused by one of more of the following: 
a) Name Resolution failure on the current domain controller. 
b) Active Directory Replication Latency (an account created on another domain controller has not replicated to the current domain controller).</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1054</td><td>The processing of Group Policy failed. Windows could not obtain the name of a domain controller. This could be caused by a name resolution failure. Verify your Domain Name System (DNS) is configured and working correctly.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1055</td><td>The processing of Group Policy failed. Windows could not resolve the computer name. This could be caused by one of more of the following: 
a) Name Resolution failure on the current domain controller. 
b) Active Directory Replication Latency (an account created on another domain controller has not replicated to the current domain controller).</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1058</td><td>The processing of Group Policy failed. Windows attempted to read the file %9 from a domain controller and was not successful. Group Policy settings may not be applied until this event is resolved. This issue may be transient and could be caused by one or more of the following: 
a) Name Resolution/Network Connectivity to the current domain controller. 
b) File Replication Service Latency (a file created on another domain controller has not replicated to the current domain controller). 
c) The Distributed File System (DFS) client has been disabled.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1065</td><td>The processing of Group Policy failed. Windows could not evaluate the Windows Management Instrumentation (WMI) filter for the Group Policy object %8. This could be caused by RSOP being disabled  or Windows Management Instrumentation (WMI) service being disabled, stopped, or other WMI errors. Make sure the WMI service is started and the startup type is set to automatic. New Group Policy objects or settings will not process until this event has been resolved.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1068</td><td>The processing of Group Policy was interrupted. Windows prematurely ended the discovery and enforcement of Group Policy settings because the computer was requested to shutdown or the user logged off. Group Policy processing will be attempted next refresh cycle, on the next computer reboot, or the next user logon.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1079</td><td>The processing of Group Policy failed. Windows could not obtain the list of Group Policy objects applicable for this computer or user. View the event details for more information.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1080</td><td>The processing of Group Policy failed. Windows could not search the Active Directory organization unit hierarchy. View the event details for more information.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1085</td><td>Windows failed to apply the %8 settings. %8 settings might have its own log file. Please click on the &quot;More information&quot; link.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1088</td><td>The processing of Group Policy failed. Windows attempted to query the list of Group Policy objects and exceeded the maximum limit (999).</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1089</td><td>Windows failed to record Resultant Set of Policy (RSoP) information, which describes the scope of Group Policy objects applied to the computer or user. This could be caused by RSOP being disabled or Windows Management Instrumentation (WMI) service being disabled, stopped, or other WMI errors. Group Policy settings successfully applied to the computer or user; however, management tools may not report accurately.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1090</td><td>Windows failed to record Resultant Set of Policy (RSoP) information, which describes the scope of Group Policy objects applied to the computer or user. This could be caused by Windows Management Instrumentation (WMI) service being disabled, stopped, or other WMI errors. Group Policy settings successfully applied to the computer or user; however, management tools may not report accurately.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1091</td><td>Windows could not record  the Resultant Set of Policy (RSoP) information for the Group Policy extension &lt;%8&gt;. Group Policy settings successfully applied to the computer or user; however, management tools may not report accurately.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1095</td><td>Windows encountered an error while recording Resultant Set of Policy (RSoP) information, which describes the scope of Group Policy objects applied to the computer or user. Group Policy settings successfully applied to the computer or user; however, management tools may not report accurately.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1096</td><td>The processing of Group Policy failed. Windows could not apply the registry-based policy settings for the Group Policy object %8. Group Policy settings will not be resolved until this event is resolved. View the event details for more information on the file name and path that caused the failure.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1097</td><td>The processing of Group Policy failed. Windows could not determine the computer account to enforce Group Policy settings. This may be transient. Group Policy settings, including computer configuration, will not be enforced for this computer.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1101</td><td>The processing of Group Policy failed. Windows could not locate the directory object %8. Group Policy settings will not be enforced until this event is resolved. View the event details for more information on this error.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1104</td><td>Windows was unable to read the Windows Management Instrumentation (WMI) filter information associated with the Group Policy object %8.This may be caused by a deleted WMI Filter defined in the domain that is still in use by Group Policy objects. Group Policy settings for this Group Policy object will not be enforced. Other Group Policy objects may still apply. Windows will attempt to retrieve this information at the next policy cycle. This specific problem may be resolved by identifying all GPOs that reference the WMI filter and removing the references. Contact an administrator if this event recurs for several hours.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1109</td><td>The user account is in a different forest than the computer account. The processing of Group Policy from another forest is not allowed. Group Policy will be processed using Loopback Replace mode. The scope of the user policy settings will be determined by the location of the computer object in Active Directory. The settings will be acquired from the User Configuration of these policies.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1110</td><td>The processing of Group Policy failed. Windows could not determine if the user and computer accounts are in the same forest. Ensure the user domain name matches the name of a trusted domain that resides in the same forest as the computer account.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1112</td><td>The Group Policy Client Side Extension %8 was unable to apply one or more settings because the changes must be processed before system startup or user logon. The system will wait for Group Policy processing to finish completely before the next startup or logon for this user, and this may result in slow startup and boot performance.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1125</td><td>The processing of Group Policy failed because of an internal system error. Please see the Group Policy operational log for the specific error message. An attempt will be made to process Group Policy again at the next refresh cycle.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1126</td><td>Windows was unable to determine whether new Group Policy settings defined by a network administrator should be enforced for this user or computer because this computer&#39;s clock is not synchronized with the clock of one of the domain controllers for the domain. Because of this issue, this computer system may not be in compliance with the network administrator’s requirements, and users of this system may not be able to use some functionality on the network. Windows will periodically attempt to retry this operation, and it is possible that either this system or the domain controller will correct the time settings without intervention by an administrator, so the problem will be corrected. 

If this issue persists for more than an hour, checking the local system&#39;s clock settings to ensure they are accurate and are synchronized with the clocks on the network&#39;s domain controllers is one way to resolve this problem. A network administrator may be required to resolve the issue if correcting the local time settings does not address the problem.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1127</td><td>The processing of Group Policy failed due to an internal error. Please look into the Group Policy operational log for the specific error message. An attempt will be made to process Group Policy again at the next refresh cycle.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1128</td><td>The Group Policy Client Side Extension %3 may have caused the Group Policy Service to terminate unexpectedly. To prevent further failures in the Group Policy Service, this extension has been temporarily disabled until after the next system restart. Group Policy settings managed by this extension may no longer be enforced until the system is restarted. The vendor of this extension should be contacted if this issue recurs.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1129</td><td>The processing of Group Policy failed because of lack of network connectivity to a domain controller. This may be a transient condition. A success message would be generated once the machine gets connected to the domain controller and Group Policy has successfully processed. If you do not see a success message for several hours, then contact your administrator.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1130</td><td>%5 failed. 
	GPO Name : %6
	GPO File System Path : %7
	Script Name: %8</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1500</td><td>The Group Policy settings for the computer were processed successfully. There were no changes detected since the last successful processing of Group Policy.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1501</td><td>The Group Policy settings for the user were processed successfully. There were no changes detected since the last successful processing of Group Policy.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1502</td><td>The Group Policy settings for the computer were processed successfully. New settings from %6 Group Policy objects were detected and applied.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>1503</td><td>The Group Policy settings for the user were processed successfully. New settings from %6 Group Policy objects were detected and applied.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4000</td><td>Starting computer boot policy processing for %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4000</td><td>Starting computer boot policy processing for %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4001</td><td>Starting user logon Policy processing for %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4001</td><td>Starting user logon Policy processing for %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4002</td><td>Starting policy processing due to network state change for computer %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4002</td><td>Starting policy processing due to network state change for computer %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4003</td><td>Starting policy processing due to network state change for user %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4003</td><td>Starting policy processing due to network state change for user %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4004</td><td>Starting manual processing of policy for computer %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4004</td><td>Starting manual processing of policy for computer %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4005</td><td>Starting manual processing of policy for user %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4005</td><td>Starting manual processing of policy for user %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4006</td><td>Starting periodic policy processing for computer %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4006</td><td>Starting periodic policy processing for computer %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4007</td><td>Starting periodic policy processing for user %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4007</td><td>Starting periodic policy processing for user %2. 
Activity id: %1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4016</td><td>Starting %2 Extension Processing. 

List of applicable Group Policy objects: (%5)

%6</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4017</td><td>%1 
%2</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4018</td><td>Starting %2 for %1.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4019</td><td>Running script name %1.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4115</td><td>Group Policy Service started.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4116</td><td>Started the Group Policy service initialization phase.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4117</td><td>Group Policy Session started.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4126</td><td>Group Policy receiving applicable GPOs from the domain controller.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4216</td><td>Starting to save policies to the local datastore.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4217</td><td>Starting to load policies from the local datastore.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4218</td><td>Starting the first WMI query for the policy.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4257</td><td>Starting to download policies.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>4326</td><td>Group Policy is trying to discover the Domain Controller information.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5016</td><td>Completed %3 Extension Processing in %1 milliseconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5017</td><td>%3 
%4
The call completed in %1 milliseconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5018</td><td>Completed %4 for %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5019</td><td>Completed %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5115</td><td>Group Policy Service stopped.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5116</td><td>Successfully completed the Group Policy Service initialization phase.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5117</td><td>Group policy session completed successfully.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5126</td><td>Group Policy successfully got applicable GPOs from the domain controller.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5216</td><td>Successfully saved policies to the local datastore.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5217</td><td>Successfully loaded policies from the local datastore.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5218</td><td>Successfully completed the first WMI query.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5257</td><td>Successfully completed downloading policies.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5308</td><td>Domain Controller details: 
	Domain Controller Name : %1
	Domain Controller IP Address : %2</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5309</td><td>Computer details: 
	Computer role : %1
	Network name : %2</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5310</td><td>Account details: 
	Account Name : %1
	Account Domain Name : %2
	DC Name : %3
	DC Domain Name : %4</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5311</td><td>The loopback policy processing mode is %1.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5312</td><td>List of applicable Group Policy objects: 

%1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5313</td><td>The following Group Policy objects were not applicable because they were filtered out : 

%1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5314</td><td>A %6 link was detected. The Estimated bandwidth is %1 kbps. The slow link threshold is %3 kbps.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5315</td><td>Next policy processing for %1 will be attempted in %2 %3.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5320</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5321</td><td>%1 Parameter: %2</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5322</td><td>Group Policy waited for %3 milliseconds for the network subsystem at computer boot.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5323</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5324</td><td>Group Policy received the notification %1 from Winlogon for session %2.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5325</td><td>Group Policy received %1 notification from Service Control Manager.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5326</td><td>Group Policy successfully discovered the Domain Controller in %1 milliseconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5327</td><td>Estimated network bandwidth on one of the connections: %1 kbps.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5331</td><td>Service configuration update to standalone was attempted due to the presence of Group Policy client extension %1 that is not part of the operating system and completed with status %3.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5332</td><td>Group Policy waited for %3 milliseconds for the Direct Access CorpNet connectivity at computer boot.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5340</td><td>The Group Policy processing mode is %1.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>5351</td><td>Group policy session returned to winlogon.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6000</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6001</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6002</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6003</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6004</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6005</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6006</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6007</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6016</td><td>Completed %3 Extension Processing in %1 milliseconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6017</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6018</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6019</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6033</td><td>Skipped %1 Extension based on Group Policy client-side processing rules.  Refer to a Resultant Set of Policy report for more information.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6034</td><td>Group Policy changed from synchronous foreground to asynchronous foreground based on slow link detection.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6035</td><td>%1 Extension deferred processing until next synchronous foreground.  Refer to a Resultant Set of Policy report for more information.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6226</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6308</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6309</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6310</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6311</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6312</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6313</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6314</td><td>Group Policy bandwidth estimation failed. Group Policy processing will continue. Assuming %6 link.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6315</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6320</td><td>Warning: %1 Warning code %2.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6321</td><td>Warning: %1 Parameter: %3 : Warning code %2.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6322</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6323</td><td>Group Policy dependency (%1) did not start. As a result, network related features of Group Policy such as bandwidth estimation and response to network changes will not work.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6324</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6325</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6326</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6327</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6330</td><td>An unfinished invocation of the Group Policy Client Side Extension %1 from a previous instance of the Group Policy Service was detected.  This may indicate that the extension caused the Group Policy Client Service to terminate unexpectedly.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6331</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6332</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6337</td><td>Group Policy network connection is via Direct Access.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6338</td><td>Group Policy Winlogon status reporting has completed.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6339</td><td>Group Policy Winlogon Start Shell handling completed.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6341</td><td>A Group Policy setting was used to override the fast/slow link detection.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6342</td><td>The network connection is using a WWAN device for connectivity.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6344</td><td>Group Policy detected a slow link during sync mode processing.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6345</td><td>The connection to DC timed out during the Group Policy sync mode process.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>6346</td><td>Group Policy switched the sync mode process to async mode.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7000</td><td>Computer boot policy processing failed for %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7000</td><td>Computer boot policy processing failed for %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7001</td><td>User logon policy processing failed for %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7001</td><td>User logon policy processing failed for %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7002</td><td>Policy processing due to network state change failed for computer %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7002</td><td>Policy processing due to network state change failed for computer %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7003</td><td>Policy processing due to network state change failed for user %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7003</td><td>Policy processing due to network state change failed for user %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7004</td><td>Manual processing of policy failed for computer %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7004</td><td>Manual processing of policy failed for computer %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7005</td><td>Manual processing of policy failed for user %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7005</td><td>Manual processing of policy failed for user %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7006</td><td>Periodic policy processing failed for computer %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7006</td><td>Periodic policy processing failed for computer %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7007</td><td>Periodic policy processing failed for user %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7007</td><td>Periodic policy processing failed for user %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7016</td><td>Completed %3 Extension Processing in %1 milliseconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7017</td><td>%3 
%4
The call failed after %1 milliseconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7018</td><td>Script for %3 failed in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7019</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7117</td><td>Group policy session completed with error.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7126</td><td>Group Policy could not get applicable GPOs from the domain controller.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7216</td><td>Saved policies to the local datastore with error.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7217</td><td>Loaded policies from the local datastore with error.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7257</td><td>Downloaded policies with error.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7308</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7309</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7310</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7311</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7312</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7313</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7314</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7315</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7320</td><td>Error: %1 Error code %2.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7321</td><td>Error: %1 Parameter: %3 : Error code %2.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7322</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7323</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7324</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7325</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7326</td><td>Group Policy failed to discover the Domain Controller details in %1 milliseconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7327</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7331</td><td>Service configuration update to standalone was attempted due to the presence of Group Policy client extension %1 that is not part of the operating system and completed with status %3.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>7332</td><td>Invalid Error Message.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8000</td><td>Completed computer boot policy processing for %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8000</td><td>Completed computer boot policy processing for %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8001</td><td>Completed user logon policy processing for %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8001</td><td>Completed user logon policy processing for %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8002</td><td>Completed policy processing due to network state change for computer %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8002</td><td>Completed policy processing due to network state change for computer %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8003</td><td>Completed policy processing due to network state change for user %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8003</td><td>Completed policy processing due to network state change for user %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8004</td><td>Completed manual processing of policy for computer %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8004</td><td>Completed manual processing of policy for computer %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8005</td><td>Completed manual processing of policy for user %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8005</td><td>Completed manual processing of policy for user %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8006</td><td>Completed periodic policy processing for computer %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8006</td><td>Completed periodic policy processing for computer %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8007</td><td>Completed periodic policy processing for user %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8007</td><td>Completed periodic policy processing for user %3 in %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>8016</td><td>%1 Extension (%2) requests a sync mode process.</td></tr>
<tr><td>Microsoft-Windows-GroupPolicy</td><td>9001</td><td>This machine is configured to retrieve Group Policy files from a file share in an insecure way.

UNC Path: %1
Mutual Authentication Enforced: %2
Integrity Enforced: %3

Guidance: The UNC path contains logon scripts and/or files that control system security policies. Microsoft recommends configuring Windows to require both mutual authentication and integrity when accessing files on this UNC path.

For details on configuring Windows machines to require additional security when accessing specific UNC paths, visit http://support.microsoft.com/kb/3000483.</td></tr>
</table>
