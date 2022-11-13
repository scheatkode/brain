# Microsoft-Windows-DistributedCOM

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10000</td><td>Unable to start a DCOM Server: %3. The error:
&quot;%2&quot;
Happened while starting this command:
%1</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10001</td><td>Unable to start a DCOM Server: %3 as %4/%5. The error:
&quot;%2&quot;
Happened while starting this command:
%1</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>3221235474</td><td>Access denied attempting to launch a DCOM Server. The server is:
%1
The user is %2/%3, SID=%4.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>3221235475</td><td>Access denied attempting to launch a DCOM Server using DefaultLaunchPermssion. The server is:
%1
The user is %2/%3, SID=%4.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10004</td><td>DCOM got error &quot;%1&quot; and was unable to logon %2\%3 in order to run the server:
%4</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10005</td><td>DCOM got error &quot;%1&quot; attempting to start the service %2 with arguments &quot;%3&quot; in order to run the server:
%4</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10006</td><td>DCOM got error &quot;%1&quot; from the computer %2 when attempting to activate the server:
%3</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>3221235479</td><td>DCOM got error &quot;%1&quot; when attempting to activate the server:
%2</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10008</td><td>DCOM got error &quot;%1&quot; from the computer %2 when attempting to the server:
%3 with file %4.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>3221235481</td><td>DCOM was unable to communicate with the computer %1 using any of the configured protocols.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10010</td><td>The server %1 did not register with DCOM within the required timeout.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>3221235483</td><td>The server %1 could not be contacted to establish the connection to the client</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>3221235484</td><td>There is an assertion failure in DCOM.  Context follows: %1 %2 %3</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10014</td><td>The activation for CLSID %1 failed because remote activations for COM+ are disabled. To enable this functionality use Server Manager to install the COM+ Network Access feature in the Application Server role.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10015</td><td>The machine wide limit settings do not grant %1 %2 permission for the COM Server application with CLSID 
%3
 and APPID 
%4
 to the user %5\%6 SID (%7) from address %8 running in the application container %9 SID (%10). This security permission can be modified using the Component Services administrative tool.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10016</td><td>The %1 permission settings do not grant %2 %3 permission for the COM Server application with CLSID 
%4
 and APPID 
%5
 to the user %6\%7 SID (%8) from address %9 running in the application container %10 SID (%11). This security permission can be modified using the Component Services administrative tool.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10017</td><td>The %1 permission settings do not grant %2 access permission to the COM Server application %3 with APPID 
%4
 to the user %5\%6 SID (%7) from address %8 running in the application container %9 SID (%10). This security permission can be modified using the Component Services administrative tool.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10018</td><td>The application-specific permission settings do not grant %1 access permission to the COM Server application %2 with APPID 
%3
 to the user %4\%5 SID (%6) from address %7 running in the application container %8 SID (%9). The application set this security permission programmatically; to modify this security permission contact the application vendor.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10019</td><td>The machine wide limit settings do not grant %1 access permission to the COM Server application %2 with APPID 
%3
 to the user %4\%5 SID (%6) from address %7 running in the application container %8 SID (%9). This security permission can be modified using the Component Services administrative tool.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10020</td><td>The machine wide %1 %2 security descriptor is invalid. It contains Access Control Entries with permissions that are invalid. The requested action was therefore not performed. This security permission can be corrected using the Component Services administrative tool.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10021</td><td>The launch and activation security descriptor for the COM Server application with APPID 
%1
 is invalid. It contains Access Control Entries with permissions that are invalid. The requested action was therefore not performed. This security permission can be corrected using the Component Services administrative tool.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10022</td><td>The %1 access security descriptor for the COM Server application %2 with APPID 
%3
 is invalid. It contains Access Control Entries with permissions that are invalid. The requested action was therefore not performed. This security permission can be corrected using the Component Services administrative tool.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10023</td><td>The application-specific access security descriptor for the COM Server application %1 with APPID 
%2
 is invalid. It contains Access Control Entries with permissions that are invalid. The requested action was therefore not performed.  The application set this security permission programmatically; to modify this security permission contact the application vendor.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10024</td><td>The machine wide group policy %1 Limits security descriptor is invalid. The security descriptor is defined as an invalid Security Descriptor Definitions Language (SDDL) string. The requested action was therefore not performed. Please contact your administrator to get the security descriptor corrected in the Group Policy settings.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>1073751850</td><td>The COM sub system is suppressing duplicate event log entries for a duration of %1 seconds.  The suppression timeout can be controlled by a REG_DWORD value named %2 under the following registry key: HKLM\%3.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10027</td><td>The machine wide limit settings do not grant %1 %2 permission for COM Server applications to the user %3\%4 SID (%5) from address %6 running in the application container %7 SID (%8). This security permission can be modified using the Component Services administrative tool.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10028</td><td>DCOM was unable to communicate with the computer %1 using any of the configured protocols; requested by PID %2 (%3), while activating CLSID %4.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10029</td><td>The activation of the CLSID %1 timed out waiting for the service %2 to stop.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10030</td><td>Unable to start a COM Server for debugging: %3. The error:
&quot;%2&quot;
Happened while starting this command:
%1</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10031</td><td>An unmarshaling policy check was performed when unmarshaling a custom marshaled object and the class %1 was rejected</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10032</td><td>An unmarshaling policy check was performed when unmarshaling a custom inproc handler and the class %1 was rejected</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10033</td><td>An unmarshaling policy check was performed when unmarshaling a COM+ envoy context property and the class %1 was rejected</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10034</td><td>An unmarshaling policy check was performed due to CLSCTX_NO_CUSTOM_MARSHAL and the class %1 was rejected</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10035</td><td>The COM standard marshaler was unable to fix a mismatch between the IID %1 provided by the server and the IID %2 requested by the client, with handler CLSID %3. The error code was %4.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10036</td><td>The server-side authentication level policy does not allow the user %1\%2 SID (%3) from address %4 to activate DCOM server. Please raise the activation authentication level at least to RPC_C_AUTHN_LEVEL_PKT_INTEGRITY in client application.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10037</td><td>Application %1 with PID %2 is requesting to activate CLSID %3 on computer %4 with explicitly set authentication level at %5. The lowest activation authentication level required by DCOM is 5(RPC_C_AUTHN_LEVEL_PKT_INTEGRITY). To raise the activation authentication level, please contact the application vendor.</td></tr>
<tr><td>Microsoft-Windows-DistributedCOM</td><td>10038</td><td>Application %1 with PID %2 is requesting to activate CLSID %3 on computer %4 with default activation authentication level at %5. The lowest activation authentication level required by DCOM is 5(RPC_C_AUTHN_LEVEL_PKT_INTEGRITY). To raise the activation authentication level, please contact the application vendor.</td></tr>
</table>
