# LsaSrv

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>LsaSrv</td><td>100</td><td>The security package does not cache the credentials needed to authenticate to the server.

Package Name:	%1
User Name:	%2
Domain Name:	%3
Server Name:	%4
Protected User:	%5
Error Code:	%6
</td></tr>
<tr><td>LsaSrv</td><td>200</td><td>A security package received a network logon request after the logoff completed.

User Name:	%1
Domain Name:	%2
Logon ID:	%3
Logoff Time:	%4
PID:	%5
Program:	%6
Principal Name:	%7
Server Name:	%8
Package Name:	%9
Call Type:	%10
Error Code:	%11
</td></tr>
<tr><td>LsaSrv</td><td>300</td><td>Groups assigned to a new logon.

New Logon:
	Security ID:		%1
	Account Name:		%2
	Account Domain:		%3
	Logon ID:		%4
	Logon GUID:		%5

Event in sequence:		%6 of %7

Group Membership:		%8</td></tr>
<tr><td>LsaSrv</td><td>301</td><td>Claims assigned to a new logon.

New Logon:
	Security ID:		%1
	Account Name:		%2
	Account Domain:		%3
	Logon ID:		%4
	Logon GUID:		%5


	Logon Type:		%6



Event in sequence:		%7 of %8

User Claims:		%9

Device Claims:		%10

This event is generated when a new logon session is created and the user token associated with it contains user and/or device claims. The New Logon fields indicate the account that was logged on. If all the user and device claims in the user token cannot be accommodated in a single event, multiple such events are generated. The Event in sequence field indicates how many more events are generated for this logon session. Each user or device claim is represented in the following format:

	ClaimID ClaimTypeID : Value1, Value2 … 

The common claim types are: 0 (Invalid Type), 1 (64-bit Integer, 2 (Unsigned 64-bit Integer), 3 (String), 4 (FQBN), 5 (SID), 6 (Boolean) and 16 (Blob). If the claim value exceeds the max allowed length then the string is terminated by ...</td></tr>
<tr><td>LsaSrv</td><td>302</td><td>User %1 logged off notification is received.

LogonId:	%2
AuthorityName:	%3
AccountName:	%4
Timeout:	%5 seconds
</td></tr>
<tr><td>LsaSrv</td><td>303</td><td>The security package does not cache the user&#39;s sign on credentials.

Package Name:	%1
User Name:	%2
Domain Name:	%3
Protected User:	%4
</td></tr>
<tr><td>LsaSrv</td><td>320</td><td>Automatic restart sign on successfully configured the autologon credentials for:

	Account Name:		%1
	Account Domain:		%2</td></tr>
<tr><td>LsaSrv</td><td>321</td><td>Automatic restart sign on failed to configure the autologon credentials with error:

%1</td></tr>
<tr><td>LsaSrv</td><td>322</td><td>Automatic restart sign on successfully deleted autologon credentials from LSA memory</td></tr>
<tr><td>LsaSrv</td><td>5000</td><td>The security package %1 generated an exception. The exception information is the data.</td></tr>
<tr><td>LsaSrv</td><td>6027</td><td>Could not upgrade the global secret %1. Please check the status of all services in the system.</td></tr>
<tr><td>LsaSrv</td><td>6033</td><td>An anonymous session connected from %1 has attempted to open an LSA policy handle on this machine. The attempt was rejected with STATUS_ACCESS_DENIED to prevent leaking security sensitive information to the anonymous caller.
 The application that made this attempt needs to be fixed. Please contact the application vendor. As a temporary workaround, this security measure can be disabled by setting the \HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa\TurnOffAnonymousBlock DWORD value to 1.
 This message will be logged at most once a day.</td></tr>
<tr><td>LsaSrv</td><td>6035</td><td>During a logon attempt, the user&#39;s security context accumulated too many security IDs. This is a very unusual situation. Remove the user from some global or local groups to reduce the number of security IDs to incorporate into the security context.
User&#39;s SID is %1
If this is the Administrator account, logging on in safe mode will enable Administrator to log on by automatically restricting group memberships.</td></tr>
<tr><td>LsaSrv</td><td>6036</td><td>The program %2, with the assigned Process ID %1, supplied a NULL or empty target name for the pszTargetName parameter when calling the InitializeSecurityContext API to initiate an outbound NTLM security context. This is a security risk when mutual authentication is required.
 
 To help protect against a malicious attack, make your code more secure. To do this, change the program so that it specifies a target name in the pszTargetName parameter field, and then recompile the code.</td></tr>
<tr><td>LsaSrv</td><td>6037</td><td>The program %2, with the assigned process ID %1, could not authenticate locally by using the target name %3. The target name used is not valid. A target name should refer to one of the local computer names, for example, the DNS host name.
 
 Try a different target name.</td></tr>
<tr><td>LsaSrv</td><td>6038</td><td>Microsoft Windows Server has detected that NTLM authentication is presently being used between clients and this server. This event occurs once per boot of the server on the first time a client uses NTLM with this server.
 
NTLM is a weaker authentication mechanism. Please check:
 
      Which applications are using NTLM authentication?
      Are there configuration issues preventing the use of stronger authentication such as Kerberos authentication?
      If NTLM must be supported, is Extended Protection configured?
 
Details on how to complete these checks can be found at http://go.microsoft.com/fwlink/?LinkId=225699.</td></tr>
<tr><td>LsaSrv</td><td>6039</td><td>Microsoft Windows Server has detected that NTLM authentication is being used between clients and this server. This event occurs once per boot of the server on the first time a client uses NTLM with this server.
 
NTLM is a weaker authentication mechanism. Please check:
 
      Which applications are using NTLM authentication?
      Are there configuration issue preventing the use stronger authentication such as Kerberos authentication?
      If NTLM must be supported, is Extended Protection configured?
 
Details on how to complete these checks can be found at http://go.microsoft.com/fwlink/?LinkId=225699.</td></tr>
<tr><td>LsaSrv</td><td>6040</td><td>An authentication request for package %1 was rejected because the target information was invalid.  The authentication request did not match the target name of %2.</td></tr>
<tr><td>LsaSrv</td><td>6041</td><td>A CredSSP authentication to %1 failed to negotiate a common protocol version.  The remote host offered version %2 which is not permitted by Encryption Oracle Remediation.

See https://go.microsoft.com/fwlink/?linkid=866660 for more information.</td></tr>
<tr><td>LsaSrv</td><td>6144</td><td>A secret object private to LSA was queried by a client. This object was returned in encrypted format for security reasons.</td></tr>
<tr><td>LsaSrv</td><td>6145</td><td>An error occurred while retrieving new Central Access Policies for this machine.

Could not retrieve policies for the following DNs:
%1</td></tr>
<tr><td>LsaSrv</td><td>6146</td><td>An error occurred while processing new Central Access Policies for this machine. Validation failed for the following Central Access Rule referenced by one or more of the Central Access Policies:

	Error:		%1

	Name:		%2
	Description:	%3</td></tr>
<tr><td>LsaSrv</td><td>6147</td><td>Credential Guard is configured to run, but is not licensed. Credential Guard was not started.</td></tr>
<tr><td>LsaSrv</td><td>6148</td><td>The PDC completed an automatic trust scan operation for all trusts with no errors.

More information can be found at https://go.microsoft.com/fwlink/?linkid=2162089.</td></tr>
<tr><td>LsaSrv</td><td>6149</td><td>The PDC completed an automatic trust scan operation for all trusts and encountered at least one error.

More information can be found at https://go.microsoft.com/fwlink/?linkid=2162089.</td></tr>
<tr><td>LsaSrv</td><td>6150</td><td>The PDC completed an administrator-requested trust scan operation for the trust &#39;%1&#39; with no errors.

More information can be found at https://go.microsoft.com/fwlink/?linkid=2162089.</td></tr>
<tr><td>LsaSrv</td><td>6151</td><td>The PDC was unable to find the specified trust &#39;%1&#39; to scan. The trust either does not exist or it is neither an inbound or bidirectional trust.

More information can be found at https://go.microsoft.com/fwlink/?linkid=2162089.</td></tr>
<tr><td>LsaSrv</td><td>6152</td><td>The PDC completed an administrator-requested trust scan operation for the trust &#39;%1&#39; and encountered an error.

More information can be found at https://go.microsoft.com/fwlink/?linkid=2162089.</td></tr>
<tr><td>LsaSrv</td><td>6153</td><td>The PDC encountered an error trying to scan the named trust.

Trust: %1

Error: %2(%3)

More information can be found at https://go.microsoft.com/fwlink/?linkid=2162089.</td></tr>
<tr><td>LsaSrv</td><td>6182</td><td>LogonSession alive after interactive user logoff. Indicates a possible token leak in one of the services. 
Logon ID:%1
Account Name:%2
Domain Name:%3
</td></tr>
<tr><td>LsaSrv</td><td>6225</td><td></td></tr>
<tr><td>LsaSrv</td><td>6226</td><td></td></tr>
<tr><td>LsaSrv</td><td>6227</td><td></td></tr>
<tr><td>LsaSrv</td><td>6228</td><td></td></tr>
<tr><td>LsaSrv</td><td>6229</td><td></td></tr>
<tr><td>LsaSrv</td><td>6230</td><td></td></tr>
<tr><td>LsaSrv</td><td>6231</td><td></td></tr>
<tr><td>LsaSrv</td><td>6232</td><td></td></tr>
<tr><td>LsaSrv</td><td>32773</td><td>A lookup request was made that required connectivity to a domain controller in domain %1. The LSA was unable to find a domain controller in the domain and thus failed the request. Please check connectivity and secure channel setup from this domain controller to the domain %2.</td></tr>
<tr><td>LsaSrv</td><td>32774</td><td>A lookup request was made that required connectivity to the domain controller %1. The local LSA was unable to contact the LSA on the remote domain controller. Please check connectivity and secure channel setup from this domain controller to the domain controller %2.</td></tr>
<tr><td>LsaSrv</td><td>32775</td><td>A lookup request was made that required the lookup services on the remote domain controller %1. The remote domain controller failed the request thus the local LSA failed the original lookup request. Please check connectivity and secure channel setup from this domain controller to the domain controller %2.</td></tr>
<tr><td>LsaSrv</td><td>32777</td><td>The LSA was unable to register its RPC interface over the TCP/IP interface. Please make sure that the protocol is properly installed.</td></tr>
<tr><td>LsaSrv</td><td>32779</td><td></td></tr>
<tr><td>LsaSrv</td><td>32780</td><td>The LSA was unable to notify UBPM during startup with status %1.</td></tr>
<tr><td>LsaSrv</td><td>40960</td><td>The Security System detected an authentication error for the server %1. The failure code from authentication protocol %2 was %3.</td></tr>
<tr><td>LsaSrv</td><td>40961</td><td>The Security System could not establish a secured connection with the server %1. No authentication protocol was available.</td></tr>
<tr><td>LsaSrv</td><td>40962</td><td>The Security System was unable to authenticate to the server %1 because the server has completed the authentication, but the client authentication protocol %2 has not.</td></tr>
<tr><td>LsaSrv</td><td>40964</td><td>The Security System received an authentication attempt with an unknown authentication protocol. The request has failed.</td></tr>
<tr><td>LsaSrv</td><td>40965</td><td>The Security System has selected %2 for the authentication protocol to server %1.</td></tr>
<tr><td>LsaSrv</td><td>40966</td><td>The Security System has received an authentication attempt, and determined that the protocol %1 preferred by the client is acceptable.</td></tr>
<tr><td>LsaSrv</td><td>40967</td><td>The Security System has received an authentication request directly for authentication protocol %1.</td></tr>
<tr><td>LsaSrv</td><td>40968</td><td>The Security System has received an authentication request that could not be decoded. The request has failed.</td></tr>
<tr><td>LsaSrv</td><td>40969</td><td>The Security System has received an authentication attempt, and determined that the protocol %1 is the common protocol.</td></tr>
<tr><td>LsaSrv</td><td>40970</td><td>The Security System has detected a downgrade attempt when contacting the 3-part SPN 

 %1 

 with error code %2. Authentication was denied.</td></tr>
<tr><td>LsaSrv</td><td>45056</td><td>Logon cache was disabled. Intermittent authentication failures may result during periods of network latency or interrupts. Please contact your system administrator.</td></tr>
<tr><td>LsaSrv</td><td>45057</td><td>A failed logon attempt has caused a logon cache entry for user %1 to be deleted. The authentication package was %2, and the error message was %3.</td></tr>
<tr><td>LsaSrv</td><td>45058</td><td>A logon cache entry for user %1 was the oldest entry and was removed. The timestamp of this entry was %2.</td></tr>
</table>
