# Microsoft-Windows-Directory-Services-SAM

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12288</td><td>SAM failed to write changes to the database. This is most likely due to a memory or disk-space shortage. The SAM database will be restored to an earlier state. Recent changes will be lost. Check the disk-space available and maximum pagefile size setting.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12289</td><td>SAM failed to restore the database to an earlier state. SAM has shutdown. You must reboot the machine to re-enable SAM.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12291</td><td>SAM failed to start the TCP/IP or SPX/IPX listening thread</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12293</td><td>There are two or more objects that have the same SID attribute in the SAM database. The Distinguished Name of the account is %1. All duplicate accounts have been deleted. Check the event log for additional duplicates.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12294</td><td>The SAM database was unable to lockout the account of %1 due to a resource error, such as a hard disk write failure (the specific error code is in the error data) . Accounts are locked after a certain number of bad passwords are provided so please consider resetting the password of the account mentioned above.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12295</td><td>The SAM database attempted to delete the file %1 as it contains account information that is no longer used.  The error is in the record data. Please have an administrator delete this file.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12296</td><td>The SAM database attempted to clear the directory %1 in order to remove files that were once used by the Directory Service. The error is in record data. Please have an admin delete these files.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12297</td><td>%1 is now the primary domain controller for the domain.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12298</td><td>The account %1 cannot be converted to be a domain controller account as its object class attribute in the directory is not computer or is not derived from computer. If this is caused by an attempt to install a pre Windows 2000 domain controller in a Windows 2000 domain or later, then you should pre-create the account for the domain controller with the correct object class.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12299</td><td>The attempt to check whether group caching has been enabled in the Security Accounts Manager has failed, most likely due to lack of resources. This task has been rescheduled to run in one minute.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12300</td><td>The group caching option in the Security Accounts Manager has now been properly updated.  Group caching is enabled.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12301</td><td>The group caching option in the Security Accounts Manager has now been properly updated. Group caching is disabled.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12302</td><td>The %1 package failed to update additional credentials for user %2.  The error code is in the data of the event log message.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12303</td><td>There are two or more well known objects that have the same SID attribute in the SAM database. The Distinguished Name of the duplicate account is %1. The newest account will be kept, all older duplicate accounts have been deleted. Check the event log for additional duplicates.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12304</td><td>There are two or more objects that have the same account name attribute in the SAM database. The system has automatically renamed object %1 to a system assigned account name %2.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>12305</td><td>An error occurred while creating new default accounts for this domain.  This maybe due to a transient error condition. The task will retry periodically until success and will log this message again in a week if the problem persists.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16384</td><td>The account %1 could not be upgraded since there is an account with an equivalent name.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16385</td><td>An error occurred upgrading user %1.  This account will have to be added manually upon reboot.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16386</td><td>An error occurred trying to read a user object from the old database.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16387</td><td>An error occurred upgrading alias %1. This account will have to be added manually upon reboot.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16388</td><td>An error occurred trying to read an alias object from the old database.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16389</td><td>An error occurred upgrading group %1. This account will have to be added manually upon reboot.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16390</td><td>An error occurred trying to read a group object from the old database.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16391</td><td>An error occurred trying to add account %1 to alias %2.  This account will have to be added manually upon reboot.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16392</td><td>The account with the sid %1 could not be added to group %2.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16393</td><td>An error occurred trying to add account %1 to group %2.  This account will have to be added manually upon reboot.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16394</td><td>The account with the rid %1 could not be added to group %2.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16395</td><td>A fatal error occurred trying to transfer the SAM account database into the directory service. A possible reason is the SAM account database is corrupt.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16398</td><td>An error occurred trying to upgrade a SAM user&#39;s User_Parameters attribute. The following Notification Package DLL might be the possible offender: %1. Check the record data of this event for the NT error code.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16399</td><td>An error occured trying to set User Parameters attribute for this user This operation is failed. Check the record data of this event for the NT error code.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16400</td><td>An error occured trying to upgrade the following SAM User Object - %1. We will try to continue upgrading this user. But it might contain inconsistent data. Check the record data of this event for the NT error code.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16401</td><td>An error occurred when trying to add the account %1 to the group %2. The problem, &quot;%3&quot;, occurred when trying to open the group. Please add the account manually.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16402</td><td>An error occurred when trying to add the account %1 to the group %2. The problem, &quot;%3&quot;, occurred when trying to add the account to the group.  Please add the account manually.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16403</td><td>The error &quot;%2&quot; occurred when trying to create the well known account %1. Please contact PSS to recover.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16405</td><td>During the installation of the Directory Service, this server&#39;s machine account was deleted hence preventing this Domain Controller from starting up.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16406</td><td>The Security Account Database detected that the well known account %1 does not exist. The account has been recreated.  Please reset the password for the account.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16407</td><td>The Security Account Database detected that the well known group or local group %1 does not exist. The group has been recreated.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16408</td><td>Domain operation mode has been changed to Native Mode. The change cannot be reversed.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16409</td><td>Active Directory Domain Services failed to add a security principal to well known security principals container. Please have an administrator add this security principal if needed. Security principal name: %1</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16410</td><td>Active Directory Domain Services failed to add all of the new security principals to well known security principals container. Please have an administrator add these security principals if needed.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16411</td><td>Active Directory Domain Services failed to rename a security principal in well known security principals container. Please have an administrator rename this security principal if needed. Security principal name: %1</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16412</td><td>Active Directory Domain Services failed to rename some of the security principals in well known security principals container. Please have an administrator rename these security principals if needed.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16413</td><td>An error occurred when trying to remove the account %1 from the group %2. The problem, &quot;%3&quot;, occurred when trying to remove the account from the group.  Please remove the member manually.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16642</td><td>The account-identifier allocator was unable to assign a new identifier. The identifier pool for this domain controller may have been depleted. If this problem persists, restart the domain controller and view the initialization status of the allocator in the event log.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16643</td><td>An initial account-identifier pool has not yet been allocated to this domain controller. A possible reason for this is that the domain controller has been unable to contact the master domain controller, possibly due to connectivity or network problems. Account creation will fail on this domain controller until the pool is obtained.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16644</td><td>The maximum domain account identifier value has been reached. No further account-identifier pools can be allocated to domain controllers in this domain.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16645</td><td>The maximum account identifier allocated to this domain controller has been assigned. The domain controller has failed to obtain a new identifier pool. A possible reason for this is that the domain controller has been unable to contact the master domain controller. Account creation on this controller will fail until a new pool has been allocated. There may be network or connectivity problems in the domain, or the master domain controller may be offline or missing from the domain. Verify that the master domain controller is running and connected to the domain.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16646</td><td>The computed account identifier is invalid because it is out of the range of the current account-identifier pool belonging to this domain controller. The computed RID value is %1. Try invalidating the account identifier pool owned by this domain controller. This will make the domain controller acquire a fresh account identifier pool.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16647</td><td>The domain controller is starting a request for a new account-identifier pool.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16648</td><td>The request for a new account-identifier pool has completed successfully.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16649</td><td>The account-identifier-manager object creation completed. If the record data for this event has the value zero, the manager object was created. Otherwise, the record data will contain the NT error code indicating the failure. The failure to create the object may be due to low system resources, insufficient memory, or disk space.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16651</td><td>The request for a new account-identifier pool failed. The operation will be retried until the request succeeds. The error is 
 &quot; %1 &quot;</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16652</td><td>The domain controller is booting to directory services restore mode.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16653</td><td>A pool size for account-identifiers (RIDs) that was configured by an Administrator is greater than the supported maximum. The maximum value of %1 will be used when the domain controller is the RID master. 
See http://go.microsoft.com/fwlink/?LinkId=225963 for more information.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16654</td><td>A pool of account-identifiers (RIDs) has been invalidated. This may occur in the following expected cases:
1. A domain controller is restored from backup. 
2. A domain controller running on a virtual machine is restored from snapshot. 
3. An administrator has manually invalidated the pool. 
See http://go.microsoft.com/fwlink/?LinkId=226247 for more information.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16655</td><td>The global maximum for account-identifiers (RIDs) has been increased to %1. 
 See http://go.microsoft.com/fwlink/?LinkId=233329 for more information including important operating system interoperability requirements.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16656</td><td>Action required! An account-identifier (RID) pool was allocated to this domain controller. The pool value indicates this domain has consumed a considerable portion of the total available account-identifiers. 

A protection mechanism will be activated when the domain reaches the following threshold of total available account-identifiers remaining: %1.  The protection mechanism prevents the allocation of account-identifier (RID) pools needed to allow existing DCs to create additional users, computers and groups, or promote new DCs into the domain. The mechanism will remain active until the Administrator manually re-enables account-identifier allocation on the RID master domain controller. 

See http://go.microsoft.com/fwlink/?LinkId=228610 for more information.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16657</td><td>Action required! This domain has consumed a considerable portion of the total available account-identifiers (RIDs). A protection mechanism has been activated because the total available account-identifiers remaining is approximately: %1. 

The protection mechanism prevents the allocation of account-identifier (RID) pools needed to allow existing DCs to create additional users, computers and groups, or promote new DCs into the domain.  The mechanism will remain active until the Administrator manually re-enables account-identifier (RID) allocation on the RID master domain controller. 

It is extremely important that certain diagnostics be performed prior to re-enabling account creation to ensure this domain is not consuming account-identifiers at an abnormally high rate. Any issues identified should be resolved prior to re-enabling account creation. 

Failure to diagnose and fix any underlying issue causing an abnormally high rate of account-identifier consumption can lead to account-identifier (RID) pool exhaustion in the domain after which account creation will be permanently disabled in this domain. 

See http://go.microsoft.com/fwlink/?LinkId=228610 for more information.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16658</td><td>This event is a periodic update on the remaining total quantity of available account-identifiers (RIDs). The number of remaining account-identifiers is approximately: %1. 

Account-identifiers are used as accounts are created, when they are exhausted no new accounts may be created in the domain. 

See http://go.microsoft.com/fwlink/?LinkId=228745 for more information.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16935</td><td>Failed to secure the machine account %1.  Have an administrator remove the builtin\account operators full control Access Control Entry from the security descriptor on this object.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16936</td><td>Failed to secure the machine account %1.  This operation will be retried. Have an administrator verify the builtin\account operators full control Access Control Entry was removed from the security descriptor on this object.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16937</td><td>Secured the machine account %1.  The builtin\account operators full control Access Control Entry was removed from the security descriptor on this object.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16944</td><td>The certificate that is used for authentication does not have an issuance policy descriptor corresponding to OID %1 in the Active Directory database. This certificate will not be associated with a corresponding security identifier (SID), and the user may be denied access to some resources if you have resources whose access is restricted based on this issuance policy. The error is %2.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16945</td><td>The certificate issuance policy that is represented by OID %2 does not have a link to a security identifier (SID), or this link cannot be read. The link is represented by the attribute msDS-OIDToGroupLink on the msPKI-Enterprise-Oid object that represents the issuance policy. This certificate will not be associated with a corresponding SID, and the user may be denied access to some resources if you have resources whose access is restricted based on this issuance policy.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16946</td><td>Multiple certificate issuance policy descriptors were found in the Active Directory database. The attribute msPKI-Cert-Template-OID of these descriptors contains string %1.  This attribute should be able to uniquely identify an issuance policy descriptor; you should resolve this conflict. The issuance policies that are affected will not be associated with security identifiers (SIDs), and users who are authenticating using certificates that are issued by the corresponding policy may be denied access to some resources.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16947</td><td>The certificate issuance policy descriptor %2 is linked through its attribute msDS-OIDToGroupLink to a group that is not a security group, has members, or is not universal. The error is %6.
An issuance policy should be linked to a security identifier (SID) of a group that is security enabled, does not have members, and is universal. Users who are authenticating using certificates that are issued according to this policy may be denied access to some resources. The distinguished name (also known as DN) of the group that does not meet these requirements is %3.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16948</td><td>The requested modification for group %1 could not be performed. This is because this group is linked through msDS-OIDToGroupLinkBl to a certificate issuance policy descriptor. Such groups should be security enabled, they should not have any members, and they should be universal.
The requested operation was %4.
The error is %5.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16949</td><td>The certificate issuance policy descriptor %1 cannot be linked to group %2. Issuance policies can be linked through the attribute msDS-OIDToGroupLink only to universal, security-enabled groups that have an empty membership. You should ensure that this group meets these requirements.
The error is %5.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16950</td><td>The following invalid claims issued to user %1 have been dropped: %2.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16951</td><td>Claims issued to user %1 could not be validated and have been dropped. Error: %2.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16952</td><td>Claims issued to user %1 could not be validated and have been dropped. Error: %2.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16953</td><td>The password notification DLL %1 failed to load with error %4. Please verify that the notification DLL path defined in the registry, %2%3, refers to a correct and absolute path (&lt;drive&gt;:\&lt;path&gt;\&lt;filename&gt;.&lt;ext&gt;) and not a relative or invalid path. If the DLL path is correct, please validate that any supporting files are located in the same directory, and that the system account has read access to both the DLL path and any supporting files.  Contact the provider of the notification DLL for additional support. Further details can be found on the web at http://go.microsoft.com/fwlink/?LinkId=245898.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16960</td><td>SAM was configured to not listen on the TCP protocol.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16961</td><td>Legacy password validation mode has been enabled on this machine. If an Exchange ActiveSync policy is configured it will not be enforced for password validation requests.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16962</td><td>Remote calls to the SAM database are being restricted using the default security descriptor: %1.
For more information please see http://go.microsoft.com/fwlink/?LinkId=787651.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16963</td><td>Remote calls to the SAM database are being restricted using the configured registry security descriptor: %1.
For more information please see http://go.microsoft.com/fwlink/?LinkId=787651.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16964</td><td>The registry security descriptor is malformed: %1.
Remote calls to the SAM database are being restricted using the default security descriptor: %2.
For more information please see http://go.microsoft.com/fwlink/?LinkId=787651.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16965</td><td>A remote call to the SAM database has been denied.
Client SID: %1
Network address: %2
For more information please see http://go.microsoft.com/fwlink/?LinkId=787651.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16966</td><td>Audit only mode is now enabled for remote calls to the SAM database. SAM will log an event for clients who would have been denied access in normal mode. 
For more information please see http://go.microsoft.com/fwlink/?LinkId=787651.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16967</td><td>Audit only mode is now disabled for remote calls to the SAM database.
For more information please see http://go.microsoft.com/fwlink/?LinkId=787651.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16968</td><td>Audit only mode is currently enabled for remote calls to the SAM database.
The following client would have been normally denied access:
Client SID: %1 from network address: %2. 
For more information please see http://go.microsoft.com/fwlink/?LinkId=787651.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16969</td><td>%2 remote calls to the SAM database have been denied in the past %1 seconds throttling window.
For more information please see http://go.microsoft.com/fwlink/?LinkId=787651.</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16976</td><td>An error occurred while configuring one or more well-known accounts for this domain.  This may be due to a transient error condition. The task will retry periodically until successful. For more information please see https://go.microsoft.com/fwlink/?linkid=832473.
Status: %1</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16977</td><td>The domain is configured with the following minimum password length-related settings.

MinimumPasswordLength: %1

MinimumPasswordLengthAudit: %2

For more information see https://go.microsoft.com/fwlink/?LinkId=2097191.
</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16978</td><td>The following account has been configured with a password whose length is shorter than the current MinimumPasswordLengthAudit setting.

AccountName: %1

MinimumPasswordLength: %2

MinimumPasswordLengthAudit: %3

For more information see https://go.microsoft.com/fwlink/?LinkId=2097191.
</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16979</td><td>The domain is incorrectly configured with a MinimumPasswordLength setting that is greater than 14.

NOTE: until this is corrected, the domain will enforce a smaller MinimumPasswordLength setting of 14.

Currently configured MinimumPasswordLength value: %1

For more information see https://go.microsoft.com/fwlink/?LinkId=2097191.
</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16982</td><td>The security account manager is now logging verbose events for remote clients that call legacy password change or set RPC methods. This setting may cause large number of messages and should only be used for a short period time to diagnose problems.

For more information please see https://go.microsoft.com/fwlink/?linkid=2150956.
</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16983</td><td>The security account manager is now logging periodic summary events for remote clients that call legacy password change or set RPC methods.

For more information please see https://go.microsoft.com/fwlink/?linkid=2150956.
</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16984</td><td>The security account manager detected %1 legacy password change or set RPC method calls in the past %2 minutes.

For more information please see https://go.microsoft.com/fwlink/?linkid=2150956.
</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16985</td><td>The security account manager detected the use of a legacy password change or set RPC method from a network client.
Consider upgrading the client operating system or application to use the latest and more secure version of this method.

Details:

RPC Method: %1
Client Network Address: %4
Client SID: %3
Username: %2

For more information please see https://go.microsoft.com/fwlink/?linkid=2150956.
</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16986</td><td>The security account manager has detected one or more duplicated names for a local account. This inconsistency was remediated by keeping one account name and deleting the remaining names.

RID=%1(%2)

Retained account name: %3

Deleted account name(s): %4

For more information see https://go.microsoft.com/fwlink/?linkid=2134956.
</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16987</td><td>The security account manager has detected one or more duplicated names for a local account. This inconsistency may cause application failures and\or system instability. No changes were made since the policy is in detect-only mode.

Details:

RID=%1(%2)

Duplicate account names: %3

If the policy had been set to repair mode, the following account name would have been retained and all others deleted:

Account name to retain: %4

For more information see https://go.microsoft.com/fwlink/?linkid=2134956.
</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16990</td><td>The security account manager blocked a non-administrator from creating an Active Directory account in this domain with mismatched objectClass and userAccountControl account type flags.

Details:

Account name: %1
Account objectClass: %2
userAccountControl: %3
Caller address: %4
Caller SID: %5

For more information see https://go.microsoft.com/fwlink/?linkid=2173873.
</td></tr>
<tr><td>Microsoft-Windows-Directory-Services-SAM</td><td>16991</td><td>The security account manager blocked a non-administrator from creating or renaming a computer account using an invalid sAMAccountName. sAMAccountName on computer accounts must end with a single trailing $ sign.

Attempted sAMAccountName: %1
Recommended sAMAccountName: %1$

For more information see https://go.microsoft.com/fwlink/?linkid=2173873.
</td></tr>
</table>
