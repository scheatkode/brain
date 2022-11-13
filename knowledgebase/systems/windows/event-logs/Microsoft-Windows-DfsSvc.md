# Microsoft-Windows-DfsSvc

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>1073756142</td><td>Dfs received a referral request for &quot;%2&quot;.  The return code is in the data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>1073756324</td><td>NetrDfsEnum received an enumeration.  The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>1073756325</td><td>NetrDfsEnumEx received an enumeration.  The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239975</td><td>Dfs could not create reparse point for directory %1 under directory %2. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239976</td><td>Share %1 mapped to %2 does not support reparse points. Upgrade Filesystem and retry.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239977</td><td>Share %1 mapped to %2 directory overlaps an existing root. The DFS Root will not be created.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>1073756332</td><td>DFS re-established a connection to the PDC to initiate Domain DFS operations.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239981</td><td>Root %1 has too many errors. No further eventlogs will be logged on this root.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239982</td><td>DFS could not initialize winsock library. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239983</td><td>DFS could not initialize security library. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239984</td><td>DFS could not create DFS support thread. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239985</td><td>DFS could not initialize IP site cache. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239986</td><td>DFS could not synchronize all DFS roots. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239987</td><td>DFS could not create event handle. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239988</td><td>DFS could not get required computer information. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239989</td><td>DFS could not get required cluster information. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239990</td><td>DFS could not get required DC information. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239991</td><td>DFS could not initialize prefix table. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239992</td><td>DFS could not initialize DFS namespace.The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239993</td><td>DFS could not Register DFS Namespaces. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239994</td><td>DFS could not initialize User/kernel communication package. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239995</td><td>DFS could not contact any DC for Domain DFS operations. This operation will be retried periodically.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221239996</td><td>DFS could not initialize site support table. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>2147498174</td><td>DFS could not contact the %1 Active Directory. DFS will be using cached data. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>1073756353</td><td>DFS has connected to the %1 Active Directory.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221240002</td><td>DFS could not access its private data from the Active Directory. Please manually check network connectivity, security access, and/or consistency of DFS information in the Active Directory. This error occurred on root %1.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>1073756355</td><td>DFS server has finished initializing.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>1073756356</td><td>DFS has recovered from an error and is able to read its private data from the Active Directory. Root %1 is now able to read information from the Active Directory.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>1073756357</td><td>DFS has finished building all namespaces.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>2147498182</td><td>DFS Root %1 failed during initialization. The root will not be available.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221240007</td><td>DFS does not support multiple roots on Standard server SKU. Please cleanup the roots or upgrade.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>2147498184</td><td>DFS is unable to return the entire list of trusted domains to the client. There are too many trusted domains.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>1073756361</td><td>DFS is requesting the client for a larger buffer for trusted domain information. Some Win98 clients may not be able to access DFS namespaces.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>2147498186</td><td>DFS was unable to move all matching links of root: %1 for path %2 to new path %3</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221240011</td><td>DFS was unable to resynchronize this root target for root: %1. This may lead to inaccessability of portions of the DFS namespace.  Please verify the share %1 has all the link directories created for the DFS links. This error may occur if there are directories  on this share that may be preventing creation of links.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221240012</td><td>DFS was unable to delete link: %2  for root: %1 during a link move operation. </td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>2147498189</td><td>DFS link %1 was marked incorrectly as a DFS root. The DFS namespace is operational on this server. If this namespace is hosted on servers running Windows Server 2003 prior to Service Pack 2 (SP2), or if the server is running Windows 2000 Server, the namespace might not be fully functional on those servers.  Please consult the Microsoft Knowledge Base for more information on correcting this issue.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>2147498190</td><td>DFS metadata object %1 is empty in the metadata for DFS root %2. The DFS namespace is operational on this server. If this namespace is hosted on servers running Windows Server 2003 prior to Service Pack 2 (SP2), or if the server is running Windows 2000 Server, the namespace might not be fully functional on those servers.  Please consult the Microsoft Knowledge Base for more information on correcting this issue.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221240015</td><td>The list of folder targets for the following Distributed File System (DFS) folder is corrupt. DFS folder: %1</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221240016</td><td>A Distributed File System (DFS) folder with folder targets was created that contains other DFS folders. This can occur if two administrators on different namespace servers create conflicting folder structures at approximately the same time. Namespace: %1 DFS folder 1: %2 DFS folder 2: %3</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221240017</td><td>A Distributed File System (DFS) folder with folder targets was created that contains other DFS folders. This can occur if two administrators on different namespace servers create conflicting folder structures at approximately the same time. Namespace: %1 DFS folder: %2</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221240018</td><td>Dfs successfully created the reparse point for directory %1 under directory %2. This operation had previously failed.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221240019</td><td>A Distributed File System (DFS) folder was created with conflicting descriptions. This can occur if two administrators on different namespace servers create conflicting folder structures at approximately the same time. Namespace: %1 DFS folder path: %2 DFS folder 1: %3 DFS folder 2: %4</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221240020</td><td>The DFS Namespace service could not initialize the trusted domain information on this domain controller, but it will periodically retry the operation. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>1073756373</td><td>The DFS Namespace service successfully initialized the trusted domain information on this domain controller.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>3221240022</td><td>The DFS Namespace service could not initialize cross forest trust information on this domain controller, but it will periodically retry the operation. The return code is in the record data.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>1073756375</td><td>The DFS Namespace service successfully initialized cross forest trust information on this domain controller.</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>1073756376</td><td>The DFS Namespaces service has successfully initialized the following namespace: %1</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>2147498201</td><td>The DFS Namespaces service failed to initialize the shared folder that hosts the namespace root. Shared folder: %1</td></tr>
<tr><td>Microsoft-Windows-DfsSvc</td><td>1073756378</td><td>The DFS Namespaces service has successfully initialized the shared folder that hosts the namespace root. Shared folder: %1</td></tr>
</table>
