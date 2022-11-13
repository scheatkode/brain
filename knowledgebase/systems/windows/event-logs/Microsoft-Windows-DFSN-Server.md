# Microsoft-Windows-DFSN-Server

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>1</td><td>A referral request has been received.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>2</td><td>A DC referral request has been processed.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>3</td><td>A root referral request has been processed.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>4</td><td>A normal referral request has been processed.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>5</td><td>A referral response has been generated.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>6</td><td>A referral response has been posted.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>7</td><td>IP address %1 resolved to site %2.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>11</td><td>NetrDfsAdd arrived.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>21</td><td>NetrDfsRemove arrived.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>31</td><td>NetrDfsSetInfo arrived.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>41</td><td>NetrDfsGetInfo arrived.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>61</td><td>NetrDfsMove arrived.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>71</td><td>NetrDfsAddFtRoot arrived.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>81</td><td>NetrDfsRemoveFtRoot arrived.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>91</td><td>NetrDfsAddStdRoot arrived.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>101</td><td>NetrDfsRemoveStdRoot arrived.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>112</td><td>LockAcquiredDomainInfo.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>121</td><td>LookupRootFolderDone.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>131</td><td>LookupLinkFolderDone.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>191</td><td>NetrDfsEnum arrived.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>501</td><td>Referral request received for dfspath %1 from client with IPAddress %2 and site %3.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>502</td><td>DFS has resolved server %1 to IPAddress %2 and site %3.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>503</td><td>Failed to obtain IPAddress for server %1. This may cause the client to access high-cost or out-of-site targets.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>504</td><td>Failed to resolve IPAddress %1 to site name. This may cause the client to access high-cost or out-of-site targets.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>505</td><td>Referral generated for DFS path %2 and client whose site is %3. Targets information can be found in the event payload.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>506</td><td>Request for creating new folder or adding target to existing folder completed with status:%6. DfsFolder:%1 TargetServer:%2 TargetShare:%3</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>507</td><td>Request for deleting a link or removing target of existing link completed with status:%4. DfsFolder:%1 TargetServer:%2 TargetShare:%3</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>508</td><td>Request to modify properties of %1 completed with status %5.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>509</td><td>Request to retrieve properties of %1 completed with status %5.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>510</td><td>Request to enumerate contents of \\%1 completed with status %4.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>511</td><td>Request to move dfs folders from %1 to %2 completed with status %4.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>512</td><td>Request to create a new dfs namespace or add target to existing namespace completed with status %6. The namespace server and share name are DfsServer:%1 Share:%2.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>513</td><td>Request to remove a dfs namespace or remove target from existing namespace completed with status %5. The namespace server and share name are DfsServer:%1 Share:%2.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>514</td><td>Request to create a new standalone or clustered dfs namespace completed with status %5. The namespace server and share name are DfsServer:%1 Share:%2.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>515</td><td>Request to remove standalone or clustered dfs namespace completed with status %4. The namespace server and share name are DfsServer:%1 Share:%2.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>516</td><td>DFSN service has started performing complete refresh of metadata for namespace %1. This task can take time if the namespace has large number of folders and may delay namespace administration operations.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>517</td><td>DFSN service completed performing refresh of metadata for namespace %1 with status %4. Time taken to perform this operation %5 milliseconds.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>518</td><td>DFSN service has successfully deleted DFS reparse point %1 on volume %3. The reparse point was deleted because it was not belonging to any of the namespaces on this server.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>519</td><td>DFSN service has failed to deleted DFS reparse point %1 on volume %3 with status %4. The service attempted to delete this reparse point as it does not belong to any of the namespaces on this server.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>520</td><td>The DFS Namespace service could not obtain site costs for the following Active Directory Domain Services site: %1. This might cause clients to access folder targets in other sites. Error code: %2.</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>521</td><td>The DFS Namespace service is unable to contact Active Directory Domain Services. 

Domain: %1 
Domain Controller: %2 
LDAP Error: %3</td></tr>
<tr><td>Microsoft-Windows-DFSN-Server</td><td>522</td><td>A DFS folder has incorrect metadata in the registry. The standalone namespace that contains this DFS folder is offline.
To bring the namespace back online, delete the following registry entry and then restart the DFS Namespace service. After the namespace is online, recreate the missing DFS folder or restore the DFS folder from a backup of the DFS namespace.

Registry Path: %1 
Status: %2</td></tr>
</table>
