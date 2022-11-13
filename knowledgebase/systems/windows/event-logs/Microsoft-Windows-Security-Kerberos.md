# Microsoft-Windows-Security-Kerberos

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>2147483651</td><td>A Kerberos error message was received:
 on logon session %1
 Client Time: %2
 Server Time: %3
 Error Code: %4 %5
 Extended Error: %6
 Client Realm: %7
 Client Name: %8
 Server Realm: %9
 Server Name: %10
 Target Name: %11
 Error Text: %12
 File: %13
 Line: %14
 Error Data is in record data.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>1073741828</td><td>The Kerberos client received a KRB_AP_ERR_MODIFIED error from the server %1. The target name used was %3. This indicates that the target server failed to decrypt the ticket provided by the client. This can occur when the target server principal name (SPN) is registered on an account other than the account the target service is using. Ensure that the target SPN is only registered on the account used by the server. This error can also happen if the target service account password is different than what is configured on the Kerberos Key Distribution Center for that target service. Ensure that the service on the server and the KDC are both configured to use the same password. If the server name is not fully qualified, and the target domain (%2) is different from the client domain (%4), check if there are identically named server accounts in these two domains, or use the fully-qualified name to identify the server.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>1073741829</td><td>The Kerberos client received a KRB_AP_ERR_TKT_NYV error from the server %1. This indicates that the ticket presented to that server is not yet valid (due to a discrepancy between ticket and server time. Contact your system administrator to make sure the client and server times are synchronized, and that the time for the Key Distribution Center Service (KDC) in realm %2 is synchronized with the KDC in the client realm.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65541</td><td>An error occurred while retrieving a digital certificate from the inserted smart card. %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>2147483654</td><td>The Kerberos SSPI package generated an output token of size %1 bytes, which was too large to fit in the token buffer of size %2 bytes, provided by process id %3.
 
 The output SSPI token size is probably the result of the user %4 being a member of a large number of groups.
 
 It is recommended to minimize the number of groups a user belongs to. If the problem can not be corrected by reducing the group memberships of this user, contact your system administrator to increase the maximum token size, which is configured on each computer individually using the registry value: HKLM\SYSTEM\CurrentControlSet\Control\Lsa\Kerberos\Parameters\MaxTokenSize.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65542</td><td>An error occurred in while attempting to verify the inserted smart card: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>3221225479</td><td>The digitally signed Privilege Attribute Certificate (PAC) that contains the authorization information for client %1 in realm %2 could not be validated.
 
 This error is usually caused by domain trust failures; Contact your system administrator.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65543</td><td>An error occurred while signing a message using the inserted smart card: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>3221225480</td><td>The domain controller rejected the client certificate of user %2, used for smart card logon. The following error was returned from the certificate validation process: %1.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65544</td><td>An error occurred while verifying a signed message using the inserted smart card: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>3221225481</td><td>The client has failed to validate the domain controller certificate for %2. The following error was returned from the certificate validation process: %1.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65545</td><td>An error occurred while verifying the digital certificate retrieved from the inserted smart card: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>2147483658</td><td>The Kerberos subsystem currently cannot retrieve tickets from your domain controller using the UDP network protocol. This is typically due to network problems. Contact your system administrator.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65546</td><td>An error occurred while encrypting a message using the inserted smart card: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>3221225483</td><td>The Distinguished Name in the subject field of your smart card logon certificate does not contain enough information to identify the appropriate domain on an non-domain joined computer. Contact your system administrator.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65547</td><td>An error occurred while decrypting a message using the inserted smart card: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>2147483660</td><td>While using your smart card over a VPN connection, the Kerberos subsystem encountered an error. Typically, this indicates the card has been pulled from the card reader during the VPN session. One possible solution is to close the VPN connection, reinsert the card, and establish the connection again.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65548</td><td>An error occurred while building a certificate context: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>13</td><td>An error occurred while initializing the smart card logon library: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>2147483661</td><td>The smart card PIN stored in Credential Manager is missing or invalid. The smart card PIN is stored in memory only for the current interactive logon session, and is deleted if the card is removed from the card reader or when the user logs off. To resolve this error, keep the card in the reader, open Credential Manager in Control Panel, and reenter the PIN for the credential %1.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>2147483662</td><td>The password stored in Credential Manager is invalid. This might be caused by the logged on user changing the password from this computer or a different computer. To resolve this error, open Credential Manager in Control Panel, and reenter the password for the credential %1.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65550</td><td>An error occurred while signing a message: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>2147483663</td><td>The Kerberos SSPI package generated an output token of size %1 bytes, which was too large to fit in the token buffer of size %2 bytes, provided by process id %3.
 
 The application needs to be modified to supply a token buffer of size at least %4 bytes.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65551</td><td>An error occurred while verifying a signed message: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>3221225488</td><td>The Kerberos SSPI package failed to find the smart card certificate in the certificate store. To remedy this failure, logon as user %1 and insert the smart card into the smart card reader, then use the Certificates snap-in to verify that the smart card certificate is in the user&#39;s personal certificate store.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65552</td><td>An error occurred while encrypting a message: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>3221225489</td><td>The Kerberos SSPI package failed to locate the forest or domain %1 to search.  Ensure that the Use forest search order Group Policy is correctly configured, and that this forest or domain is available.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65553</td><td>An error occurred while decrypting a message: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>2147483666</td><td>The delegated TGT for the user (%2) has expired. A renewal was attempted and failed with error %8. The server logon session (%1) has stopped delegating the user&#39;s credential. For future unconstrained delegation to succeed, the user needs to authenticate again to the server. 

TGT Details:
    Client: %2
    Server: %3
    Flags: %4
    Start Time: %5
    End Time: %6
    Renew Until: %7</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65554</td><td>An error occurred while retrieving some provider parameter: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>2147483667</td><td>The KDC certificate for the domain controller does not contain the KDC Extended Key Usage (EKU): 1.3.6.1.5.2.3.5: Error Code %1. The domain administrator will need to obtain a certificate with the KDC EKU for the domain controller to resolve this error. When using Windows Server Certificate Services create a certificated based on the Kerberos Authentication Template.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>65555</td><td>An error occurred while generating a random number: %1</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>2147483668</td><td>The KDC certificate for the domain controller does not have the DNS name of domain %1 in the Subject Alternative Name (SAN) attribute: Error Code %2. The domain administrator will need to obtain a KDC certificate with the DNS domain name in the SAN attribute for the domain controller to resolve this error. When using Windows Server Certificate Services create a certificated based on the Kerberos Authentication Template.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>100</td><td>The service principal name (SPN) %1 is not registered, which caused Kerberos authentication to fail: %2. Use the setspn command-line tool to register the SPN.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>101</td><td>The service principal name (SPN) %1 is registered on multiple accounts which caused Kerberos authentication to fail: %2. Use the setspn command-line tool to identify the accounts and remove the duplicate registrations.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>102</td><td>Trust validation of the certificate for the Kerberos Key Distribution Center (KDC) %1 failed: %2. Use the CAPI2 diagnostic traces to identify the reason for the validation failure.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>103</td><td>Trust validation of the client certificate for %1 failed: %2 on KDC. Use the CAPI2 diagnostic traces to identify the reason for the validation failure.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>104</td><td>The Kerberos Key Distribution Center (KDC) for the domain %1 does not have a certificate installed or does not support logon using certificates: %2</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>105</td><td>The Kerberos client could not retrieve passwords for the group managed service account.

LogonId: %1:%2
DomainName: %3
UserName: %4
Refresh: %5
Current File Time: %6
Error Code: %7
</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>106</td><td>The Kerberos client received a KDC certificate that does not have KDC EKU (not based on Kerberos Authentication Template).

Error Code: %1
</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>107</td><td>The Kerberos client received a KDC certificate that does not have a matched domain name.

Expected Domain Name: %1
Error Code: %2
</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>108</td><td>The Kerberos client could not send a Kerberos proxy request.

ProxyServer:
  ServerName: %1
  ServerPort: %2
  ServerVdir:  %3
Error Code: %4
Status Code: %5
</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>109</td><td>The Kerberos client could not find a suitable credential to use with the authentication proxy:

AuthProxy:
  Proxy: %1
  ProxyBypass: %2
  Epoch: %3
  Supported Schemes: %4
  First Scheme: %5
Digest Credential:
  Initialized: %6
  DomainAndUserName: %7
  Epoch: %8
Basic Credential:
  Initialized: %9
  DomainAndUserName: %10
  Epoch: %11
</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>200</td><td>The Kerberos client could not locate a domain controller for domain %1: %2. Kerberos authentication requires communicating with a domain controller.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>201</td><td>Attempt to use Kerberos unconstrained delegation failed.

Target server: %1
Supplied user: %2
Supplied domain: %3
PID of client process: %4
Name of client process: %5
LUID of client process: %6
User identity of client process: %7
Domain name of user identity of client process: %8
Mechanism OID: %9

Kerberos unconstrained delegation is not allowed for this user. For more information, see https://go.microsoft.com/fwlink/?linkid=856824.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>202</td><td>Attempt to export TGT session key failed.

Target server: %1
Supplied user: %2
Supplied domain: %3
PID of client process: %4
Name of client process: %5
LUID of client process: %6
User identity of client process: %7
Domain name of user identity of client process: %8
Mechanism OID: %9

This device does not allow exporting TGT session keys. For more information, see https://go.microsoft.com/fwlink/?linkid=856825.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>203</td><td>When Credential Guard is enabled, Kerberos does not accept PKINIT KDC replies using public key encryption to ensure Kerberos tickets cannot be exported from the device. For more information, see https://go.microsoft.com/fwlink/?linkid=856823.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>300</td><td>The Kerberos client discovered domain controller %1 for the domain %2.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>301</td><td>The Kerberos client used credentials from the Credential Manager for the target: &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>302</td><td>The Kerberos client was bound to domain controller %1 for the domain %2 but could not access this domain controller at the time.

    DesiredFlags: %3
    CacheFlags: %4
    ErrorCode: %5</td></tr>
<tr><td>Microsoft-Windows-Security-Kerberos</td><td>303</td><td>The Kerberos client updated passwords for the group managed service account.

LogonId: %1:%2
DomainName: %3
UserName: %4
Update Current Passwords: %5
Update Old Passwords: %6
Refresh: %7
Previous File Time: %8
Current File Time: %9
</td></tr>
</table>
