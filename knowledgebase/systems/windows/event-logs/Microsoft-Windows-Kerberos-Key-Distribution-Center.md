# Microsoft-Windows-Kerberos-Key-Distribution-Center

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483651</td><td>Could not find principal %1</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483652</td><td>Domain %1 propagated to us but did not authenticate.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225477</td><td>The KDC failed to update policy class %1. The error is in the data.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225478</td><td>The KDC failed to update the trusted domain list. The error is in the data.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225479</td><td>The Security Account Manager failed a KDC request in an unexpected way. The error is in the data field. The account name was %1 and lookup type %2.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225480</td><td>The account %1 did not have a suitable key for generating a Kerberos ticket. If the encryption type is supported, changing or setting the password will generate a proper key.  The missing key type may be in the data field.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>9</td><td>The password on the KRBTGT account was changed.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225482</td><td>The attempt to change the password on the KRBTGT account failed. The error code is in the data field</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225483</td><td>The KDC encountered duplicate names while processing a Kerberos authentication request. The duplicate name is %1 (of type %2). This may result in authentication failures or downgrades to NTLM. In order to prevent this from occurring remove the duplicate entries for %1 in Active Directory.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483660</td><td>A request failed from client realm %1 for a ticket in realm %2. This failed because a trust link between the realms is non transitive.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225485</td><td>The account for %1 has corrupt keys stored in the DS. Changing or setting the password should restore correct keys.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225486</td><td>While processing an AS request for target service %1, the account %2 did not have a suitable key for generating a Kerberos ticket (the missing key has an ID of %3). The requested etypes : %4. The accounts available etypes : %5. Changing or resetting the password of %6 will generate a proper key.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225487</td><td>The request for an AS ticket for client %1 was forwarded to the PDC. An invalid response to this forwarded request was detected and could indicate an attempt to spoof your PDC. There may be additional information in the data field.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225488</td><td>While processing a TGS request for the target server %1, the account %2 did not have a suitable key for generating a Kerberos ticket (the missing key has an ID of %3). The requested etypes were %4. The accounts available etypes were %5. Changing or resetting the password of %6 will generate a proper key.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225489</td><td>When updating policy class %1, the KDC encountered invalid policy data and has failed to update the policy.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225490</td><td>During TGS processing, the KDC was unable to verify the signature on the PAC from %1. This indicates the PAC was modified.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483667</td><td>This event indicates an attempt was made to use smartcard logon, but the KDC is unable to use the PKINIT protocol because it is missing a suitable certificate.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483668</td><td>The currently selected KDC certificate was once valid, but now is invalid and no suitable replacement was found. Smartcard logon may not function correctly if this problem is not remedied. Have the system administrator check on the state of the domain&#39;s public key infrastructure. The chain status is in the error data.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483669</td><td>The client certificate for the user %1\%2 is not valid, and resulted in a failed smartcard logon. Please contact the user for more information about the certificate they&#39;re attempting to use for smartcard logon. The chain status was : %3</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483670</td><td>The KDC encountered a trust loop when building a list of trusted domains. This indicates that the route to the domain %1 from this KDC has more than one possible trust path.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483671</td><td>The KDC received invalid messages of type %1.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483672</td><td>A service ticket request by client %1 for %2 was rejected because User2User was required. The KDC responds with this error when a client requests a service ticket for a user principal (a security risk). The client must support User2User in order to obtain a service ticket for the requested service principal</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483673</td><td>The account %1 from domain %2 is attempting to use S4USelf for the target client %3, but is not allowed to perform group expansion on this client&#39;s user object. It may be necessary to adjust the ACL on the TokenGroupsGlobalAndUniversal attribute on the target client&#39;s user object to allow S4USelf to function correctly. This can also be accomplished by adding %1 to the Windows Authorization Access Group.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225498</td><td>While processing an AS request for target service %1, the account %2 did not have a suitable key for generating a Kerberos ticket (the missing key has an ID of %3). The requested etypes were %4. The accounts available etypes were %5.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>3221225499</td><td>While processing a TGS request for the target server %1, the account %2 did not have a suitable key for generating a Kerberos ticket (the missing key has an ID of %3). The requested etypes were %4. The accounts available etypes were %5.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483676</td><td>When generating a cross realm referral from domain %1 the KDC was not able to find the suitable key to verify the ticket. The ticket key version in the request was %2 and the available key version was %3. This most common reason for this error is a delay in replicating the keys. In order to remove this problem try forcing replication or wait for the replication of keys to occur.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483677</td><td>The Key Distribution Center (KDC) cannot find a suitable certificate to use for smart card logons, or the KDC certificate could not be verified. Smart card logon may not function correctly if this problem is not resolved. To correct this problem, either verify the existing KDC certificate using certutil.exe or enroll for a new KDC certificate.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483678</td><td>The Kerberos Key Distribution Center failed to locate the forest or domain %1 to search.  Please ensure that the forest search order policy is correctly configured, and that this forest or domain is available.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483679</td><td>A ticket to the service %2 is issued for account %1. The size of the encrypted part of this ticket is %3 bytes, which is close or greater than the configured ticket size threshold (%4 bytes). This ticket or any additional tickets issued from this ticket might result in authentication failures if the client or server application allocates SSPI token buffers bounded by a value that is close to the threshold value.
The size of ticket is largely determined by the size of authorization data it carries. The size of authorization data is determined by the groups the account is member of, the claims data the account is setup for, and the resource groups resolved in the resource domain.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483680</td><td>The Key Distribution Center (KDC) uses a certificate without KDC Extended Key Usage (EKU) which can result in authentication failures for device certificate logon and smart card logon from non-domain-joined devices. Enrollment of a KDC certificate with KDC EKU (Kerberos Authentication template) is required to remove this warning.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483681</td><td>The Key Distribution Center (KDC) encountered failures when updating the krbtgt account for the Dynamic Access Control and Kerberos armoring policy capability for the domain. This update was performed so that all the domain controllers including read-only domain controllers (RODCs) in this domain could advertise support for Dynamic Access Control and Kerberos armoring. This failure indicates that there could be domain controllers that have not received updated krbtgt account values. If the update to the krbtgt account is in transit, then you can run Gpupdate /force as a possible workaround to this failure. More information about this update:

  Object Rid: %1
  Update bits: %2
  Bitmask: %3
  Error Code: %4
</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483682</td><td>The Key Distribution Center (KDC) has the Dynamic Access Control and Kerberos armoring policy configured for a level which requires a higher domain functional level. Until the domain functional level is raised, the KDC will only support the level configured as Supported.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483683</td><td>The Key Distribution Center (KDC) encountered a ticket-granting-ticket (TGT) from another KDC (%1) that did not contain a PAC attributes field. See https://go.microsoft.com/fwlink/?linkid=2173051 to learn more.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483684</td><td>The Key Distribution Center (KDC) encountered a ticket that did not contain a PAC while processing a request for another ticket. This prevented security checks from running and could open security vulnerabilities. See https://go.microsoft.com/fwlink/?linkid=2173051 to learn more.

  Client: %1\\%2
  Ticket for: %3
</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483685</td><td>The Key Distribution Center (KDC) encountered a ticket that did not contain information about the account that requested the ticket while processing a request for another ticket. This prevented security checks from running and could open security vulnerabilities. See https://go.microsoft.com/fwlink/?linkid=2173051 to learn more.

  Ticket PAC constructed by: %1
  Client: %2\\%3
  Ticket for: %4
</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483686</td><td>The Key Distribution Center (KDC) encountered a ticket that contained inconsistent information about the account that requested the ticket. This could mean that the account has been renamed since the ticket was issued, which may have been part of an attempted exploit. See https://go.microsoft.com/fwlink/?linkid=2173051 to learn more.

  Ticket PAC constructed by: %1
  Client: %2\\%3
  Ticket for: %4
  Requesting Account SID from Active Directory: %5
  Requesting Account SID from Ticket: %6
</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483687</td><td>The Key Distribution Center (KDC) encountered a user certificate that was valid but could not be mapped to a user in a secure way (such as via explicit mapping, key trust mapping, or a SID). Such certificates should either be replaced or mapped directly to the user via explicit mapping. See https://go.microsoft.com/fwlink/?linkid=2189925 to learn more.

  User: %1
  Certificate Subject: %2
  Certificate Issuer: %3
  Certificate Serial Number: %4
  Certificate Thumbprint: %5
</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483688</td><td>The Key Distribution Center (KDC) encountered a user certificate that was valid but could not be mapped to a user in a secure way (such as via explicit mapping, key trust mapping, or a SID). The certificate also predated the user it mapped to, so it was rejected. See https://go.microsoft.com/fwlink/?linkid=2189925 to learn more.

  User: %1
  Certificate Subject: %2
  Certificate Issuer: %3
  Certificate Serial Number: %4
  Certificate Thumbprint: %5
  Certificate Issuance Time: %6
  Account Creation Time: %7
</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483689</td><td>The Key Distribution Center (KDC) encountered a user certificate that was valid but contained a different SID than the user to which it mapped. As a result, the request involving the certificate failed. See https://go.microsoft.com/fwlink/?linkid=2189925 to learn more.

  User: %1
 User SID: %2
 Certificate Subject: %3
  Certificate Issuer: %4
  Certificate Serial Number: %5
  Certificate Thumbprint: %6
  Certificate SID: %7
</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483690</td><td>The Kerberos Key Distribution Center lacks strong keys for account %1.

You must update the password of this account to prevent use of insecure cryptography. 

See https://go.microsoft.com/fwlink/?linkid=2210019 to learn more.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483691</td><td>The Key Distribution Center (KDC) encountered a ticket that it could not validate the full PAC Signature. See https://go.microsoft.com/fwlink/?linkid=2210019 to learn more.

  Client: %1\\%2
</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>2147483692</td><td>The Key Distribution Center (KDC) encountered a ticket that did not contained the full PAC Signature. See https://go.microsoft.com/fwlink/?linkid=2210019 to learn more.

  Client: %1\\%2
</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>100</td><td>AS exchange performance: AS-REQ processing begins</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>101</td><td>AS exchange performance: AS-REP or KRB-ERROR returned:

    client domain: %1
    client name: %2
    server domain: %3
    server name: %4
    ErrorCode: %5
    elapse: %6 milliseconds</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>102</td><td>TGS exchange performance: TGS-REQ processing begins</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>103</td><td>TGS exchange performance: TGS-REQ or KRB-ERROR returned:

    client domain: %1
    client name: %2
    server domain: %3
    server name: %4
    ErrorCode: %5
    elapse: %6 milliseconds</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>104</td><td>Kerberos preauthentication by using DES or RC4 failed because the account was a member of the Protected User group.

Account Information:
	Security ID:		%2
	Account Name:		%1

Service Information:
	Service Name:		%3

Network Information:
	Client Address:		%7
	Client Port:		%8

Additional Information:
	Ticket Options:		%4
	Failure Code:		%5
	Pre-Authentication Type:	%6

Certificate Information:
	Certificate Issuer Name:		%9
	Certificate Serial Number:		%10
	Certificate Thumbprint:		%11

Certificate information is only provided if a certificate was used for pre-authentication.

Pre-authentication types, ticket options and failure codes are defined in RFC 4120.

If the ticket was malformed or damaged during transit and could not be decrypted, then many fields in this event might not be present.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>105</td><td>A Kerberos Ticket-granting-ticket (TGT) was denied because the device does not meet the access control restrictions.

Account Information:
	Account Name:		%1
	Supplied Realm Name:	%2
	User ID:			%3

Authentication Policy Information:
	Silo Name:		%16
	Policy Name:		%17
	TGT Lifetime:		%18

Device Information:
	Device Name:		%4

Service Information:
	Service Name:		%5
	Service ID:		%6

Network Information:
	Client Address:		%11
	Client Port:		%12

Additional Information:
	Ticket Options:		%7
	Result Code:		%8
	Ticket Encryption Type:	%9
	Pre-Authentication Type:	%10

Certificate Information:
	Certificate Issuer Name:		%13
	Certificate Serial Number:		%14
	Certificate Thumbprint:		%15

Certificate information is only provided if a certificate was used for pre-authentication.

Pre-authentication types, ticket options, encryption types and result codes are defined in RFC 4120.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>106</td><td>A Kerberos service ticket was denied because the user, device, or both does not meet the access control restrictions.

Account Information:
	Account Name:		%1
	Account Domain:		%2
	Logon GUID:		%11

Authentication Policy Information:
	Silo Name:		%13
	Policy Name:		%14

Device Information:
	Device Name:		%3

Service Information:
	Service Name:		%4
	Service ID:		%5

Network Information:
	Client Address:		%8
	Client Port:		%9

Additional Information:
	Ticket Options:		%6
	Ticket Encryption Type:	%7
	Failure Code:		%10
	Transited Services:	%12

This event is generated every time access is requested to a resource such as a computer or a Windows service.  The service name indicates the resource to which access was requested.

This event can be correlated with Windows logon events by comparing the Logon GUID fields in each event.  The logon event occurs on the machine that was accessed, which is often a different machine than the domain controller which issued the service ticket.

Ticket options, encryption types, and failure codes are defined in RFC 4120.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>120</td><td>The Key Distribution Center (KDC) failed to validate its current KDC certificate. This KDC might not be enabled for smart card or certificate authentication.

Kdc Certificate Information:
  Issuer Name: %1
  Serial Number: %2
  Thumbprint: %3
  Template: %4
  Kerberos Error: %5
  Validation Error: %6
</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>200</td><td>The Key Distribution Center (KDC) cannot find a suitable certificate to use. This KDC is not enabled for smart card or certificate authentication.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>300</td><td>The Key Distribution Center (KDC) is being started.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>301</td><td>The Key Distribution Center (KDC) has stopped with error code: %1</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>302</td><td>The Key Distribution Center (KDC) uses the below KDC certificate for smart card or certificate authentication.

Kdc Certificate Information:
  Issuer Name: %1
  Serial Number: %2
  Thumbprint: %3
  Template: %4
</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>303</td><td>A Kerberos ticket-granting-ticket (TGT) was issued for a member of the Protected User group.

Account Information:
	Account Name:		%1
	Supplied Realm Name:	%2
	User ID:			%3

Authentication Policy Information:
	Silo Name:		%16
	Policy Name:		%17
	TGT Lifetime:		%18

Device Information:
	Device Name:		%4

Service Information:
	Service Name:		%5
	Service ID:		%6

Network Information:
	Client Address:		%11
	Client Port:		%12

Additional Information:
	Ticket Options:		%7
	Result Code:		%8
	Ticket Encryption Type:	%9
	Pre-Authentication Type:	%10

Certificate Information:
	Certificate Issuer Name:		%13
	Certificate Serial Number:		%14
	Certificate Thumbprint:		%15

Certificate information is only provided if a certificate was used for pre-authentication.

Pre-authentication types, ticket options, encryption types and result codes are defined in RFC 4120.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>304</td><td>A Kerberos service ticket was issued for a member of the Protected User group.

Account Information:
	Account Name:		%1
	Account Domain:		%2
	Logon GUID:		%11

Authentication Policy Information:
	Silo Name:		%13
	Policy Name:		%14

Device Information:
	Device Name:		%3

Service Information:
	Service Name:		%4
	Service ID:		%5

Network Information:
	Client Address:		%8
	Client Port:		%9

Additional Information:
	Ticket Options:		%6
	Ticket Encryption Type:	%7
	Failure Code:		%10
	Transited Services:	%12

This event is generated every time access is requested to a resource such as a computer or a Windows service.  The service name indicates the resource to which access was requested.

This event can be correlated with Windows logon events by comparing the Logon GUID fields in each event.  The logon event occurs on the machine that was accessed, which is often a different machine than the domain controller which issued the service ticket.

Ticket options, encryption types, and failure codes are defined in RFC 4120.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>305</td><td>A Kerberos ticket-granting-ticket (TGT) was issued, but it will be denied when Authentication Policy is enforced because the device does not meet the access control restrictions.

Account Information:
	Account Name:		%1
	Supplied Realm Name:	%2
	User ID:			%3

Authentication Policy Information:
	Silo Name:		%16
	Policy Name:		%17
	TGT Lifetime:		%18

Device Information:
	Device Name:		%4

Service Information:
	Service Name:		%5
	Service ID:		%6

Network Information:
	Client Address:		%11
	Client Port:		%12

Additional Information:
	Ticket Options:		%7
	Result Code:		%8
	Ticket Encryption Type:	%9
	Pre-Authentication Type:	%10

Certificate Information:
	Certificate Issuer Name:		%13
	Certificate Serial Number:		%14
	Certificate Thumbprint:		%15

Certificate information is only provided if a certificate was used for pre-authentication.

Pre-authentication types, ticket options, encryption types and result codes are defined in RFC 4120.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>306</td><td>A Kerberos service ticket was issued, but it will be denied when Authentication Policy is enforced for a member of the Protected User group because the user, device, or both does not meet the access control restrictions.

Account Information:
	Account Name:		%1
	Account Domain:		%2
	Logon GUID:		%11

Authentication Policy Information:
	Silo Name:		%13
	Policy Name:		%14

Device Information:
	Device Name:		%3

Service Information:
	Service Name:		%4
	Service ID:		%5

Network Information:
	Client Address:		%8
	Client Port:		%9

Additional Information:
	Ticket Options:		%6
	Ticket Encryption Type:	%7
	Failure Code:		%10
	Transited Services:	%12

This event is generated every time access is requested to a resource such as a computer or a Windows service.  The service name indicates the resource to which access was requested.

This event can be correlated with Windows logon events by comparing the Logon GUID fields in each event.  The logon event occurs on the machine that was accessed, which is often a different machine than the domain controller which issued the service ticket.

Ticket options, encryption types, and failure codes are defined in RFC 4120.</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>307</td><td>The Kerberos client did not supply a supported encryption type for use with the PKINIT protocol using encryption mode.
 Client Principal Name: %1
 Client IP Address: %2
 Client Supplied NetBIOS Name: %3</td></tr>
<tr><td>Microsoft-Windows-Kerberos-Key-Distribution-Center</td><td>308</td><td>A non-conforming PKINIT Kerberos client authenticated to this DC. The authentication was allowed because KDCGlobalAllowDesFallBack was set. In the future, these connections will fail authentication. Identify the device and look to upgrade its Kerberos implementation.
 Client Principal Name: %1
 Client IP Address: %2
 Client Supplied NetBIOS Name: %3</td></tr>
</table>
