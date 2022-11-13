# Microsoft-Windows-FailoverClustering

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1000</td><td>Cluster service suffered an unexpected fatal error at line %1 of source module %2. The error code was %3.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1001</td><td>Cluster service failed a validity check on line %1 of source module %2. &quot;%3&quot;</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1002</td><td>Cluster service handled an unexpected error at line %1 of source module %2. The error code was %3.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1006</td><td>Cluster service was halted due to incomplete connectivity with other cluster nodes.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1007</td><td>A new node, %1, has been added to the failover cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1011</td><td>Cluster node %1 has been evicted from the failover cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1024</td><td>The registry checkpoint for cluster resource &#39;%1&#39; could not be restored to registry key HKEY_LOCAL_MACHINE\%2. The resource may not function correctly. Make sure that no other processes have open handles to registry keys in this registry subtree.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1034</td><td>Cluster physical disk resource &#39;%1&#39; cannot be brought online because the associated disk could not be found. The expected signature of the disk was &#39;%2&#39;. If the disk was replaced or restored, in the Failover Cluster Manager snap-in, you can use the Repair function (in the properties sheet for the disk) to repair the new or restored disk. If the disk will not be replaced, delete the associated disk resource.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1035</td><td>While disk resource &#39;%1&#39; was being brought online, access to one or more volumes failed with error &#39;%2&#39;. Run the Validate a Configuration wizard to check your storage configuration. Optionally you may want to run Chkdsk to verify the integrity of all volumes on this disk.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1037</td><td>The file system for one or more partitions on the disk for resource &#39;%1&#39; may be corrupt. Run the Validate a Configuration wizard to check your storage configuration. Optionally, you may want to run Chkdsk to verify the integrity of all volumes on this disk.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1038</td><td>Ownership of cluster disk &#39;%1&#39; has been unexpectedly lost by this node. Run the Validate a Configuration wizard to check your storage configuration.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1039</td><td>Generic application &#39;%1&#39; could not be brought online (with error &#39;%2&#39;) during an attempt to create the process.  Possible causes include: the application may not be present on this node, the path name may have been specified incorrectly, the binary name may have been specified incorrectly.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1040</td><td>Generic service &#39;%1&#39; could not be brought online (with error &#39;%2&#39;) during an attempt to open the service.  Possible causes include: the service is either not installed or the specified service name is invalid.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1041</td><td>Generic service &#39;%1&#39; could not be brought online (with error &#39;%2&#39;) during an attempt to start the service.  Possible cause: the specified service parameters might be invalid.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1042</td><td>Generic service &#39;%1&#39; failed with error &#39;%2&#39;. Please examine the application event log.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1044</td><td>Encountered a failure when attempting to create a new NetBIOS interface while bringing resource &#39;%1&#39; online (error code &#39;%2&#39;). The maximum number of NetBIOS names may have been exceeded.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1045</td><td>No matching network interface found for resource &#39;%1&#39; IP address &#39;%2&#39; (return code was &#39;%3&#39;).  If your cluster nodes span different subnets, this may be normal.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1046</td><td>Cluster IP address resource &#39;%1&#39; cannot be brought online because the subnet mask value is invalid.  Please check your IP address resource properties.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1047</td><td>Cluster IP address resource &#39;%1&#39; cannot be brought online because the address value is invalid.  Please check your IP address resource properties.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1048</td><td>Cluster IP address resource &#39;%1&#39; failed to come online. Configuration data for the network adapter corresponding to cluster network interface &#39;%2&#39; could not be determined (error code was &#39;%3&#39;). Please check that the IP address resource is configured with the correct address and network properties.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1049</td><td>Cluster IP address resource &#39;%1&#39; cannot be brought online because a duplicate IP address &#39;%2&#39; was detected on the network.  Please ensure all IP addresses are unique.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1050</td><td>Cluster network name resource &#39;%1&#39; cannot be brought online because name &#39;%2&#39; matches this cluster node name.  Ensure that network names are unique.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1051</td><td>Cluster network name resource &#39;%1&#39; cannot be brought online. Ensure that the network adapters for dependent IP address resources have access to at least one DNS server. Alternatively, enable NetBIOS for dependent IP addresses.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1052</td><td>Cluster Network Name resource &#39;%1&#39; cannot be brought online because the name could not be added to the system. The associated error code is stored in the data section.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1053</td><td>Cluster File Share &#39;%1&#39; cannot be brought online because the share could not be created.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1054</td><td>Health check for file share resource &#39;%1&#39; failed.  Retrieving information for share &#39;%2&#39; (scoped to network name %3) returned error code &#39;%4&#39;.  Ensure the share exists and is accessible.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1055</td><td>Health check for file share resource &#39;%1&#39; failed.  Retrieving information for share &#39;%2&#39; (scoped to network name %3) indicated that the share does not exist (error code &#39;%4&#39;).  Please ensure the share exists and is accessible.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1057</td><td>The cluster database could not be loaded. The file may be missing or corrupt. Automatic repair might be attempted.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1061</td><td>The Cluster service successfully formed the failover cluster &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1062</td><td>This node has successfully joined the failover cluster &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1063</td><td>The Cluster service was successfully stopped.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1066</td><td>Cluster disk resource &#39;%1&#39; indicates corruption for volume &#39;%2&#39;. Chkdsk is being run to repair problems. The disk will be unavailable until Chkdsk completes. Chkdsk output will be logged to file &#39;%3&#39;.
 Chkdsk may also write information to the Application Event Log.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1068</td><td>Cluster file share resource &#39;%1&#39; cannot be brought online.  Creation of file share &#39;%2&#39; (scoped to network name %3) failed due to error &#39;%4&#39;.  This operation will be automatically retried.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1069</td><td>Cluster resource &#39;%1&#39; in clustered role &#39;%2&#39; failed.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1069</td><td>Cluster resource &#39;%1&#39; of type &#39;%3&#39; in clustered role &#39;%2&#39; failed.

Based on the failure policies for the resource and role, the cluster service may try to bring the resource online on this node or move the group to another node of the cluster and then restart it.  Check the resource and group state using Failover Cluster Manager or the Get-ClusterResource Windows PowerShell cmdlet.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1069</td><td>Cluster resource &#39;%1&#39; of type &#39;%3&#39; in clustered role &#39;%2&#39; failed. The error code was &#39;%5&#39; (&#39;%4&#39;).

Based on the failure policies for the resource and role, the cluster service may try to bring the resource online on this node or move the group to another node of the cluster and then restart it.  Check the resource and group state using Failover Cluster Manager or the Get-ClusterResource Windows PowerShell cmdlet.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1069</td><td>Cluster resource &#39;%1&#39; of type &#39;%3&#39; in clustered role &#39;%2&#39; failed. The error code was &#39;%4&#39;.

Based on the failure policies for the resource and role, the cluster service may try to bring the resource online on this node or move the group to another node of the cluster and then restart it.  Check the resource and group state using Failover Cluster Manager or the Get-ClusterResource Windows PowerShell cmdlet.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1069</td><td>Cluster resource &#39;%1&#39; of type &#39;%3&#39; in clustered role &#39;%2&#39; failed due to an attempt to block a required state change in that cluster resource.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1070</td><td>The node failed to join failover cluster &#39;%1&#39; due to error code &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1071</td><td>The operation attempted on cluster resource &#39;%1&#39; of type &#39;%3&#39; in clustered role &#39;%2&#39; could not be completed because the resource or one of its providers has locked status.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1071</td><td>The operation attempted on cluster resource &#39;%1&#39; of type &#39;%3&#39; in clustered role &#39;%2&#39; could not be completed because the resource or one of its dependents has locked status.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1073</td><td>The Cluster service was halted to prevent an inconsistency within the failover cluster. The error code was &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1077</td><td>Health check for IP interface &#39;%1&#39; (address &#39;%2&#39;) failed (status is &#39;%3&#39;). Run the Validate a Configuration wizard to ensure that the network adapter is functioning properly.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1078</td><td>Cluster IP address resource &#39;%1&#39; cannot be brought online because WINS registration failed on interface &#39;%2&#39; with error &#39;%3&#39;. Ensure that a valid, accessible WINS server has been specified.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1080</td><td>The Cluster service failed to update the cluster database (error code &#39;%1&#39;). Possible causes are insufficient disk space or file system corruption.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1090</td><td>The Cluster service cannot be started. An attempt to read configuration data from the Windows registry failed with error &#39;%1&#39;. Please use the Failover Cluster Management snap-in to ensure that this machine is a member of a cluster. If you intend to add this machine to an existing cluster use the Add Node Wizard. Alternatively, if this machine has been configured as a member of a cluster, it will be necessary to restore the missing configuration data that is necessary for the Cluster Service to identify that it is a member of a cluster. Perform a System State Restore of this machine in order to restore the configuration data.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1092</td><td>Failed to form cluster &#39;%1&#39; with error code &#39;%2&#39;. Failover cluster will not be available.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1093</td><td>The Cluster service cannot identify node &#39;%1&#39; as a member of failover cluster &#39;%2&#39;. If the computer name for this node was recently changed, consider reverting to the previous name. Alternatively, add the node to the failover cluster and if necessary, reinstall clustered applications.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1094</td><td>The cluster common property SecurityLevel cannot be changed on this cluster. The cluster security level cannot be changed because the cluster is currently configured for no authentication mode.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1105</td><td>The Cluster service failed to start because it was unable to register interface(s) with the RPC service.  The error code was &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1116</td><td>Cluster network name resource &#39;%1&#39; failed to renew its DNS registration. Ensure that the network adapters for dependent IP address resources have access to at least one DNS server. Alternatively, enable NetBIOS for dependent IP addresses. It is possible that the DNS server may be temporarily unavailable - the DNS registration attempt will be retried.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1119</td><td>Cluster network name resource &#39;%1&#39; failed to register DNS name &#39;%2&#39; over adapter &#39;%4&#39; for the following reason: 

&#39;%3&#39;</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1121</td><td>Encrypted settings for cluster resource &#39;%1&#39; could not be successfully applied to the container name &#39;%2&#39; on this node.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1125</td><td>Cluster network interface &#39;%1&#39; for cluster node &#39;%2&#39; on network &#39;%3&#39; is operational (up). The node can communicate with all other available failover cluster nodes on the network.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1126</td><td>Cluster network interface &#39;%1&#39; for cluster node &#39;%2&#39; on network &#39;%3&#39; is unreachable by at least one other cluster node attached to the network. The failover cluster was not able to determine the location of the failure. Run the Validate a Configuration wizard to check your network configuration. If the condition persists, check for hardware or software errors related to the network adapter. Also check for failures in any other network components to which the node is connected such as hubs, switches, or bridges.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1127</td><td>Cluster network interface &#39;%1&#39; for cluster node &#39;%2&#39; on network &#39;%3&#39; failed. Run the Validate a Configuration wizard to check your network configuration. If the condition persists, check for hardware or software errors related to the network adapter. Also check for failures in any other network components to which the node is connected such as hubs, switches, or bridges.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1128</td><td>Cluster network &#39;%1&#39; is operational (up). All available failover cluster nodes attached to the network can communicate using it.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1129</td><td>Cluster network &#39;%1&#39; is partitioned. Some attached failover cluster nodes cannot communicate with each other over the network. The failover cluster was not able to determine the location of the failure. Run the Validate a Configuration wizard to check your network configuration. If the condition persists, check for hardware or software errors related to the network adapter. Also check for failures in any other network components to which the node is connected such as hubs, switches, or bridges.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1130</td><td>Cluster network &#39;%1&#39; is down. None of the available nodes can communicate using this network. Run the Validate a Configuration wizard to check your network configuration. If the condition persists, check for hardware or software errors related to the network adapter. Also check for failures in any other network components to which the node is connected such as hubs, switches, or bridges.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1131</td><td>Cluster network interface &#39;%1&#39; was added for node &#39;%2&#39; on network &#39;%3&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1132</td><td>Cluster network interface &#39;%1&#39; for node &#39;%2&#39; on network &#39;%3&#39; was removed.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1133</td><td>Cluster network &#39;%1&#39; was added to the failover cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1134</td><td>Cluster network &#39;%1&#39; was removed from the failover cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1135</td><td>Cluster node &#39;%1&#39; was removed from the active failover cluster membership. The Cluster service on this node may have stopped. This could also be due to the node having lost communication with other active nodes in the failover cluster. Run the Validate a Configuration wizard to check your network configuration. If the condition persists, check for hardware or software errors related to the network adapters on this node. Also check for failures in any other network components to which the node is connected such as hubs, switches, or bridges.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1136</td><td>The cluster service has detected an Azure host maintenance event is about to occur.  This maintenance event may cause the virtual machine hosting this node to become unavailable during this time. 

 Node: %1 
 Approximate Time: %2 
 Details: %3</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1137</td><td>Move of cluster role &#39;%1&#39; for drain could not be completed.  The operation failed with error code %2.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1138</td><td>Cluster file share resource &#39;%1&#39; cannot be brought online. Creation of DFS namespace root failed with error &#39;%3&#39;. This may be due to failure to start the &#39;DFS Namespace&#39; service or failure to create the DFS-N root for share &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1139</td><td>The cluster service has detected an Azure host maintenance event has been scheduled.  This maintenance event may cause the virtual machine hosting this node to become unavailable during this time. 

 Node: %1 
 Approximate Time: %2 
 Details: %3</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1140</td><td>The cluster service has detected an Azure host maintenance event has been rescheduled.  This maintenance event may cause the virtual machine hosting this node to become unavailable during this time. 

 Node: %1 
 Original Time: %2 
 New Time: %3</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1141</td><td>Cluster file share resource &#39;%1&#39; cannot be brought online. Resynchronization of DFS root target &#39;%2&#39; failed with error &#39;%3&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1142</td><td>Cluster file share resource &#39;%1&#39; for DFS Namespace cannot be brought online due to error &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1146</td><td>The cluster Resource Hosting Subsystem (RHS) process was terminated and will be restarted. This is typically associated with cluster health detection and recovery of a resource. Refer to the System event log to determine which resource and resource DLL is causing the issue.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1149</td><td>The DNS Host (A) and Pointer (PTR) records associated with Cluster resource &#39;%1&#39; were not removed from the resource&#39;s associated DNS server. If necessary, they can be deleted manually. Contact your DNS administrator to assist with this effort.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1150</td><td>The removal of the DNS Pointer (PTR) record &#39;%2&#39; for host &#39;%3&#39; which is associated with the cluster network name resource &#39;%1&#39; failed with error &#39;%4&#39;. If necessary, the record can be deleted manually. Contact your DNS administrator for assistance.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1151</td><td>The removal of the DNS Host (A) record &#39;%2&#39; associated with the cluster network name resource &#39;%1&#39; failed with error &#39;%3&#39;. If necessary, the record can be deleted manually. Contact your DNS administrator for assistance.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1153</td><td>The Cluster service is attempting to fail over the clustered role &#39;%1&#39; from node &#39;%2&#39; to node &#39;%3&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1154</td><td>The Cluster service is attempting to fail back the clustered role &#39;%1&#39; from node &#39;%2&#39; to node &#39;%3&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1155</td><td>The pending move for the role &#39;%1&#39; did not complete.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1156</td><td>Cluster resource &#39;%1&#39; was added to the failover cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1157</td><td>Cluster resource &#39;%1&#39; was removed from the failover cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1158</td><td>Cluster role &#39;%1&#39; was added to the failover cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1159</td><td>Cluster role &#39;%1&#39; was removed from the failover cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1177</td><td>The Cluster service is shutting down because quorum was lost. This could be due to the loss of network connectivity between some or all nodes in the cluster, or a failover of the witness disk. 
Run the Validate a Configuration wizard to check your network configuration. If the condition persists, check for hardware or software errors related to the network adapter. Also check for failures in any other network components to which the node is connected such as hubs, switches, or bridges.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1181</td><td>Cluster resource &#39;%1&#39; cannot be brought online because the associated service failed to start. The service return code is &#39;%2&#39;. Please check for additional events associated with the service and ensure the service starts correctly.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1182</td><td>Cluster resource &#39;%1&#39; cannot be brought online because the associated service failed an attempted restart. The error code is &#39;%2&#39;. The service required a restart in order to update parameters. However, the service failed before it could be stopped and restarted. Please check for additional events associated with the service and ensure the service is functioning correctly.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1183</td><td>Cluster disk resource &#39;%1&#39; contains an invalid mount point. Both the source and target disks associated with the mount point must be clustered disks, and must be members of the same group. 
Mount point &#39;%2&#39; for volume &#39;%3&#39; references an invalid source disk. Please ensure that the source disk is also a clustered disk and in the same group as the target disk (hosting the mount point).</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1186</td><td>The password associated with the Cluster service domain account is being updated on this node.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1190</td><td>Cluster network name resource &#39;%1&#39; successfully deleted its associated computer object in domain &#39;%2&#39;. The object was deleted due to failure of network name resource &#39;%1&#39; to come online.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1191</td><td>Cluster network name resource &#39;%1&#39; failed to delete its associated computer object in domain &#39;%2&#39;. The error code was &#39;%3&#39;. 
Please have a domain administrator manually delete the computer object from the Active Directory domain.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1192</td><td>Cluster network name resource &#39;%1&#39; failed to delete its associated computer object in domain &#39;%2&#39; for the following reason:
%3. 

Please have a domain administrator manually delete the computer object from the Active Directory domain.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1193</td><td>Cluster network name resource &#39;%1&#39; failed to create its associated computer object in domain &#39;%2&#39; for the following reason: %3.

The associated error code is: %5

Please work with your domain administrator to ensure that:
- The cluster identity &#39;%4&#39; can create computer objects. By default all computer objects are created in the &#39;Computers&#39; container; consult the domain administrator if this location has been changed.
- The quota for computer objects has not been reached.
- If there is an existing computer object, verify the Cluster Identity &#39;%4&#39; has &#39;Full Control&#39; permission to that computer object using the Active Directory Users and Computers tool.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1194</td><td>Cluster network name resource &#39;%1&#39; failed to create its associated computer object in domain &#39;%2&#39; during: %3.

The text for the associated error code is: %4

Please work with your domain administrator to ensure that:
- The cluster identity &#39;%5&#39; has Create Computer Objects permissions. By default all computer objects are created in the same container as the cluster identity &#39;%5&#39;.
- The quota for computer objects has not been reached.
- If there is an existing computer object, verify the Cluster Identity &#39;%5&#39; has &#39;Full Control&#39; permission to that computer object using the Active Directory Users and Computers tool.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1195</td><td>Cluster network name resource &#39;%1&#39; failed registration of one or more associated DNS name(s). The error code was &#39;%2&#39;. Ensure that the network adapters associated with dependent IP address resources are configured with access to at least one DNS server.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1196</td><td>Cluster network name resource &#39;%1&#39; failed registration of one or more associated DNS name(s) for the following reason:
%2.

Ensure that the network adapters associated with dependent IP address resources are configured with at least one accessible DNS server.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1197</td><td>Cluster network name resource &#39;%1&#39; failed to delete or disable its associated computer object &#39;%2&#39; during resource deletion. The error code was &#39;%3&#39;. 
Please check if the site is Read-Only. Ensure that the cluster name object has the appropriate permissions on the &#39;%2&#39; object in Active Directory.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1198</td><td>Cluster network name resource &#39;%1&#39; failed to delete computer object with guid &#39;%2&#39;. The error code was &#39;%3&#39;. 
Please check if the site is Read-Only. Ensure that the cluster name object has the appropriate permissions on the &#39;%2&#39; object in Active Directory.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1200</td><td>The Cluster service is attempting to bring the clustered role &#39;%1&#39; online.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1201</td><td>The Cluster service successfully brought the clustered role &#39;%1&#39; online.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1203</td><td>The Cluster service is attempting to bring the clustered role &#39;%1&#39; offline.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1204</td><td>The Cluster service successfully brought the clustered role &#39;%1&#39; offline.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1205</td><td>The Cluster service failed to bring clustered role &#39;%1&#39; completely online or offline. One or more resources may be in a failed state. This may impact the availability of the clustered role.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1206</td><td>The computer object associated with the cluster network name resource &#39;%1&#39; could not be updated in domain &#39;%2&#39;. The error code was &#39;%3&#39;. The cluster identity &#39;%4&#39; may lack permissions required to update the object. Please work with your domain administrator to ensure that the cluster identity can update computer objects in the domain.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1207</td><td>The computer object associated with the cluster network name resource &#39;%1&#39; could not be updated in domain &#39;%2&#39; during the 
%3 operation.

The text for the associated error code is: %4
 
The cluster identity &#39;%5&#39; may lack permissions required to update the object. Please work with your domain administrator to ensure that the cluster identity can update computer objects in the domain.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1208</td><td>Cluster disk resource &#39;%1&#39; contains an invalid mount point. Both the source and target disks associated with the mount point must be clustered disks, and must be members of the same group. 
Mount point &#39;%2&#39; for volume &#39;%3&#39; references an invalid target disk. Please ensure that the target disk is also a clustered disk and in the same group as the source disk (hosting the mount point).</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1209</td><td>Cluster service is requesting a bus reset for device &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1211</td><td>Cluster network name resource &#39;%1&#39; cannot be brought online. Attempt to locate a writeable domain controller (in domain %2) in order to create or update a computer object associated with the resource failed. The error code was &#39;%3&#39;. Ensure that a writeable domain controller is accessible to this node within the configured domain. Also ensure that the DNS server is running in order to resolve the name of the domain controller.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1212</td><td>Cluster network name resource &#39;%1&#39; cannot be brought online. Attempt to locate a writeable domain controller (in domain %2) in order to create or update a computer object associated with the resource failed for the following reason:
%3.

 The error code was &#39;%4&#39;. Ensure that a writeable domain controller is accessible to this node within the configured domain. Also ensure that the DNS server is running in order to resolve the name of the domain controller.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1213</td><td>Cluster network name resource &#39;%1&#39; could not completely rename the associated computer object on domain controller &#39;%2&#39;. Attempting to rename the computer object from new name &#39;%3&#39; back to its original name &#39;%4&#39; has also failed. The error code was &#39;%5&#39;. This may affect client connectivity until the network name and its associated computer object name are consistent. Contact your domain administrator to manually rename the computer object.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1214</td><td>Cluster Network Name resource cannot be registered with Netbios. 

Network Name: &#39;%3&#39; 
Reason for failure: %2 
Resource name:&#39;%1&#39; 

 Run nbtstat for the network name to ensure that the name is not already registered with Netbios.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1215</td><td>Cluster network name resource &#39;%1&#39; failed a health check. Network name &#39;%2&#39; is no longer registered on this node.  The error code was &#39;%3&#39;. Check for hardware or software errors related to the network adapter. Also, you can run the Validate a Configuration wizard to check your network configuration.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1216</td><td>A name change operation on the cluster core netname resource has failed. Attempting to revert the name change operation back to the original name has also failed. The error code was &#39;%1&#39;. You may not be able to remotely manage the cluster using the cluster name until this situation has been manually corrected.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1217</td><td>Cluster network name resource &#39;%1&#39; successfully changed the name property from &#39;%2&#39; to &#39;%3&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1218</td><td>Cluster network name resource &#39;%1&#39; failed to perform a name change operation (attempting to change original name &#39;%3&#39; to name &#39;%4&#39;).  The computer object could not be found on the domain controller &#39;%2&#39; (where it was created). An attempt will be made to recreate the computer object the next time the resource is brought online. Additionally, please work with your domain administrator to ensure that the computer object exists in the domain.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1219</td><td>Cluster network name resource &#39;%1&#39; failed to perform a name change operation.  The domain controller &#39;%2&#39; where computer object &#39;%3&#39; was being renamed, could not be contacted. The error code was &#39;%4&#39;. Ensure a writeable domain controller is accessible and check for any connectivity issue.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1220</td><td>The computer account for resource &#39;%1&#39; failed to be renamed from %2 to %3 using Domain Controller %4. The associated error code is stored in the data section.
 
The computer account for this resource was in the process of being renamed and did not complete. This was detected during the online process for this resource. In order to recover, the computer account must be renamed to the current value of the Name property, i.e., the name presented on the network.
 
The Domain Controller where the renamed was attempted might not be available; if this is the case, wait for the Domain Controller to be available again. The Domain Controller could be denying access to the account; after resolving access, try to bring the name online again.
 
If this is not possible, disable and re-enable Kerberos Authentication and an attempt will be made to find the computer account on a different DC. You eed to change the Name property to %2 in order to use the existing CComputer account.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1221</td><td>Cluster network name resource &#39;%1&#39; has a name &#39;%2&#39; which does not match the corresponding computer object name &#39;%3&#39;.  It is likely that a previous name change of the computer object has not replicated to all domain controllers in the domain. You will be unable to rename the network name resource until the names become consistent. If the computer object has not been recently changed, please contact your domain administrator to rename the computer object and thereby make it consistent. Also, ensure that replication across domain controllers has been successfully completed.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1222</td><td>The computer object associated with cluster network name resource &#39;%1&#39; could not be updated.

The text for the associated error code is: %2
 
The cluster identity &#39;%3&#39; may lack permissions required to update the object. Please work with your domain administrator to ensure that the cluster identity can update computer objects in the domain.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1223</td><td>Cluster IP address resource &#39;%1&#39; cannot be brought online because the cluster network &#39;%2&#39; is not configured to allow client access. Please use the Failover Cluster Manager snap-in to check the configured properties of the cluster network.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1224</td><td>Cluster IP address resource &#39;%1&#39; has been moved to cluster network &#39;%2&#39; because its IP address and subnet mask match. To reverse this assignment, take resource &#39;%1&#39; offline, restore the &#39;%1&#39; Network property to its former value, set the &#39;%1&#39; OverrideAddressMatch property to 1, and bring resource &#39;%1&#39; back online.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1226</td><td>Network Name resource &#39;%1&#39; (with associated network name &#39;%2&#39;) has Kerberos Authentication support enabled. Failed to add required credentials to the LSA - the associated error code &#39;%3&#39; indicates insufficient privileges normally required for this operation. The required privilege is &#39;Trusted Computing Base&#39; and must be locally enabled on each node comprising the cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1227</td><td>Network Name resource &#39;%1&#39; (with associated network name &#39;%2&#39;) has Kerberos Authentication support enabled. Failed to add required credentials to the LSA - the associated error code is &#39;%3&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1228</td><td>Cluster network name resource &#39;%1&#39; encountered an error enabling the network name on this node. The reason for the failure was: 
 &#39;%2&#39;.

 The error code was &#39;%3&#39;. 

 You may take the network name resource offline and online again to retry.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1229</td><td>Cluster network name resource &#39;%1&#39; was unable to identify any IP addresses to register with a DNS server. Ensure that there is one or more networks that are enabled for cluster use with the &#39;Allow clients to connect through this network&#39; setting, and that each node has a valid IP address configured for the networks.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1230</td><td>A component on the server did not respond in a timely fashion. This caused the cluster resource &#39;%1&#39; (resource type &#39;%2&#39;, DLL &#39;%3&#39;) to exceed its time-out threshold. As part of cluster health detection, recovery actions will be taken. The cluster will try to automatically recover by terminating and restarting the Resource Hosting Subsystem (RHS) process that is running this resource. Verify that the underlying infrastructure (such as storage, networking, or services) that are associated with the resource are functioning correctly.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1230</td><td>A component on the server did not respond in a timely fashion. This caused the cluster resource &#39;%1&#39; (resource type &#39;%2&#39;, DLL &#39;%3&#39;) to exceed its time-out threshold while processing control code &#39;%4;&#39;. As part of cluster health detection, recovery actions will be taken. The cluster will try to automatically recover by terminating and restarting the Resource Hosting Subsystem (RHS) process that is running this resource. Verify that the underlying infrastructure (such as storage, networking, or services) that are associated with the resource are functioning correctly.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1231</td><td>Cluster network name resource &#39;%1&#39; encountered an error logging on to the domain. The reason for the failure was: 
 &#39;%2&#39;.

 The error code was &#39;%3&#39;. 

 Ensure that a domain controller is accessible to this node within the configured domain.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1232</td><td>Entry point &#39;%2&#39; in cluster generic script resource &#39;%1&#39; did not complete execution in a timely manner. This could be due to an infinite loop or other issues possibly resulting in an infinite wait. Alternatively, the specified pending timeout value may be too short for this resource. Please review the &#39;%2&#39; script entry point to ensure all possible infinite waits in the script code have been corrected. Then, consider increasing the pending timeout value if deemed necessary.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1233</td><td>Cluster generic script resource &#39;%1&#39;: request to perform the &#39;%2&#39; operation will not be processed. This is due to a previously failed attempt to execute the &#39;%3&#39; entry point in a timely fashion. Please review the script code for this entry point to ensure there does not exist any infinite loop or other issues possibly resulting in an infinite wait. Then, consider increasing the resource pending timeout value if deemed necessary.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1234</td><td>The Cluster service has detected that its service account is missing one or more of the required privileges. The missing privilege list is: &#39;%1&#39; and is not currently granted to the service account. Use the &#39;sc.exe qprivs clussvc&#39; to verify the privileges of the Cluster service (ClusSvc). Additionally check for any security policies or group policies in Active Directory Domain Services that may have altered the default privileges. Type the following command to grant the Cluster service the necessary privileges to function correctly: 

sc.exe privs clussvc SeBackupPrivilege/SeRestorePrivilege/SeIncreaseQuotaPrivilege/SeIncreaseBasePriorityPrivilege/SeTcbPrivilege/SeDebugPrivilege/SeSecurityPrivilege/SeAuditPrivilege/SeImpersonatePrivilege/SeChangeNotifyPrivilege/SeIncreaseWorkingSetPrivilege/SeManageVolumePrivilege/SeCreateSymbolicLinkPrivilege/SeLoadDriverPrivilege</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1237</td><td>Cluster resource &#39;%1&#39; entered maintenance mode. The associated status is &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1238</td><td>Cluster resource &#39;%1&#39; exited maintenance mode. The associated status is &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1239</td><td>Cluster IP address resource &#39;%1&#39; obtained a leased IP address &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1240</td><td>Cluster IP address resource &#39;%1&#39; failed to obtain a leased IP address.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1241</td><td>Cluster IP address resource &#39;%1&#39; released lease of IP address &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1242</td><td>Lease of IP address &#39;%2&#39; associated with cluster IP address resource &#39;%1&#39; has expired or is about to expire, and currently cannot be renewed. Ensure that the associated DHCP server is accessible and properly configured to renew the lease on this IP address.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1243</td><td>Cluster IP address resource &#39;%1&#39; failed to release the lease for IP address &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1244</td><td>Cluster IP address resource &#39;%1&#39; renewed the lease for IP address &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1245</td><td>Cluster IP address resource &#39;%1&#39; failed to renew the lease for IP address &#39;%2&#39;. Ensure that the DHCP server is accessible and properly configured to renew the lease on this IP address.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1246</td><td>Settings have changed for cluster network &#39;%2&#39; which affect cluster IP address resource &#39;%1&#39;. Attempting to renew lease for the IP address resource.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1247</td><td>The Security Identifier (SID) type for the cluster service is configured as &#39;%1&#39; but the expected SID type is &#39;Unrestricted&#39;. The cluster service is automatically modifying its SID type configuration with the Service Control Manager (SCM) and will restart in order for this change to take effect.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1248</td><td>The Security Identifier (SID) &#39;%1&#39; associated with the cluster service is not present in the process token. The cluster service will automatically correct this problem and restart.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1249</td><td>Cluster IPv6 tunnel address resource &#39;%1&#39; has been updated to match the tunnel type supported by the cluster node. The tunnel type has changed from &#39;%2&#39; to &#39;%3&#39; and the address has been set to &#39;%4&#39;. If this change is unexpected, please check the IP address resource on which the IPv6 tunnel address resource &#39;%1&#39; depends, as well as the IPv6 configuration of your network and all cluster nodes.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1250</td><td>Cluster resource &#39;%1&#39; in clustered role  &#39;%2&#39; has received a critical state notification.  For a virtual machine this indicates that an application or service inside the virtual machine is in an unhealthy state. Verify the functionality of the service or application being monitored within the virtual machine.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1251</td><td>Clustered role &#39;%2&#39; was taken offline. This role was preempted by the higher priority clustered role &#39;%1&#39;. The cluster service will attempt to bring clustered role &#39;%2&#39; online later when system resources are available.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1252</td><td>Cluster resource &#39;%1&#39; in clustered role &#39;%2&#39; rejected a move request to node &#39;%3&#39;. The error code was &#39;%4&#39;.  Cluster resource &#39;%1&#39; may be busy or in a state where it cannot be moved.  The cluster service may automatically retry the move.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1253</td><td>Resource &#39;%1&#39; of the clustered role &#39;%2&#39; vetoed the untargeted move with application specific error code &#39;%3&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1254</td><td>Clustered role &#39;%1&#39; has exceeded its failover threshold.  It has exhausted the configured number of failover attempts within the failover period of time allotted to it and will be left in a failed state.  No additional attempts will be made to bring the role online or fail it over to another node in the cluster.  Please check the events associated with the failure.  After the issues causing the failure are resolved the role can be brought online manually or the cluster may attempt to bring it online again after the restart delay period.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1255</td><td>Cluster resource &#39;%1&#39; in clustered role  &#39;%2&#39; has received a critical state notification.  For a virtual machine this indicates that a critical network of the virtual machine is in an unhealthy state. Verify the network connectivity of the virtual machine and the virtual networks that the virtual machine is configured to use.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1256</td><td>Cluster network name resource failed registration of one or more associated DNS names(s) because the corresponding DNS Zone does not accept dynamic updates.

Cluster Network name: &#39;%1&#39;
DNS Zone: &#39;%2&#39;

Guidance:
Ensure that the DNS is configured as a Dynamic DNS zone. If the DNS server does not accept dynamic updates uncheck the   &#39;Register this connection&#39;s&#39; addresses in DNS&#39; in the properties of the network adapter.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1257</td><td>Cluster network name resource failed registration of one or more associated DNS names(s) because the access to update the secure DNS Zone was denied.

Cluster Network name: &#39;%1&#39;
DNS Zone: &#39;%2&#39;

Ensure that cluster name object (CNO) is granted permissions to the Secure DNS Zone.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1258</td><td>Cluster network name resource failed registration of one or more associated DNS name(s) because the a DNS server could not be reached.

Cluster Network name: &#39;%1&#39;
DNS Zone: &#39;%2&#39;
DNS Server: &#39;%3&#39;

Ensure that the network adapters associated with dependent IP address resources are configured with at least one accessible DNS server.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1259</td><td>Cluster network name resource failed registration of one or more associated DNS name(s) because the cluster service failed clean up the existing records corresponding to the network name.

Cluster Network name: &#39;%1&#39;
DNS Zone: &#39;%2&#39;

Ensure that cluster name object (CNO) is granted permissions to the Secure DNS Zone.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1260</td><td>Cluster network name resource failed to modify the DNS registration.

Cluster Network name: &#39;%1&#39;
Error code: &#39;%2&#39;

Guidance:
Ensure that the network adapters associated with dependent IP address resources are configured with access to at least one DNS server.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1261</td><td>Cluster network name resource failed to modify the DNS registration.

Cluster Network name: &#39;%1&#39;
Reason: &#39;%2&#39;

Guidance:
Ensure that the network adapters associated with dependent IP address resources are configured with access to at least one DNS server.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1263</td><td>Cluster network name resource failed to publish the PTR record in the DNS reverse lookup zone.

Cluster Network name: &#39;%1&#39;
Error Code: &#39;%2&#39;

Guidance:

Ensure that the network adapters associated with dependent IP address resources are configured with access to at least one DNS server and that the DNS reverse lookup zone exists.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1264</td><td>Cluster network name resource failed to publish the PTR record in the DNS reverse lookup zone.

Cluster Network name: &#39;%1&#39;
Reason: &#39;%2&#39;

Guidance:

Ensure that the network adapters associated with dependent IP address resources are configured with access to at least one DNS server and that the DNS reverse lookup zone exists.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1265</td><td>Cluster resource type &#39;%1&#39; timed out while processing the control code %2. The cluster will try to automatically recover by terminating and restarting the Resource Hosting Subsystem (RHS) process that was processing the call.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1280</td><td>Sponsor tried to Create Security Context using Package=&#39;%1&#39; with Context Requirement =&#39;%2&#39; and Timeout =&#39;%3&#39;</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1281</td><td>Joiner tried to Create Security Context using Package=&#39;%1&#39; with Context Requirement =&#39;%2&#39; and Timeout =&#39;%3&#39; for the target = &#39;%4&#39;</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1282</td><td>Security Handshake between local and remote endpoints &#39;%2&#39; did not complete in &#39;%1&#39; seconds, node terminating the connection</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1289</td><td>The Cluster Service was unable to access network adapter &#39;%1&#39;. Verify that other network adapters are functioning properly and check the device manager for errors associated with adapter &#39;%1&#39;. If the configuration for adapter &#39;%1&#39; has been changed, it may become necessary to reinstall the failover clustering feature on this computer.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1360</td><td>Cluster IP address resource &#39;%1&#39; failed to come online. Ensure the network property &#39;%2&#39; matches a cluster network name or the address property &#39;%3&#39; matches one of the subnets on a cluster network. If this is an IPv6 Address type, please verify that the cluster network matching this resource has at least one IPv6 prefix that is not link-local or tunnel.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1361</td><td>IPv6 Tunnel address resource &#39;%1&#39; failed to come online because it does not depend on an IP Address (IPv4) resource. Dependency on at least one IP Address (IPv4) resource is required.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1362</td><td>Cluster IP address resource &#39;%1&#39; failed to come online because the &#39;%2&#39; property could not be read. Please ensure that the resource is correctly configured.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1363</td><td>IPv6 tunnel address resource &#39;%1&#39; failed to come online. Cluster network &#39;%2&#39; associated with dependent IP address (IPv4) resource &#39;%3&#39; does not support ISATAP tunneling. Please ensure that the cluster network supports ISATAP tunneling.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1537</td><td>A backup operation of the cluster configuration data has been initiated.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1538</td><td>The backup operation for the cluster configuration data completed successfully. The snapshot ID is &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1539</td><td>A restore operation of the cluster configuration data has been initiated.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1540</td><td>The restore operation for the cluster configuration data completed successfully.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1541</td><td>The backup operation for the cluster configuration data has been aborted because quorum for the cluster has not yet been achieved. Please retry this backup operation after the cluster achieves quorum.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1542</td><td>The restore request for the cluster configuration data has failed. This restore failed during the &#39;pre-restore&#39; stage usually indicating that some nodes comprising the cluster are not currently operational. Ensure that the cluster service is running successfully on all nodes comprising this cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1543</td><td>The restore operation of the cluster configuration data has failed. This restore failed during the &#39;post-restore&#39; stage usually indicating that some nodes comprising the cluster are not currently operational. It is recommended that you replace the current cluster configuration data file (ClusDB) with &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1544</td><td>The backup operation for the cluster configuration data has been canceled. The cluster Volume Shadow Copy Service (VSS) writer received an abort request.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1545</td><td>The restore operation for the cluster configuration data has failed. This was due to insufficient privileges associated with the user account performing the restore. Please ensure that the user account has local administrator privileges.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1546</td><td>Node &#39;%1&#39; failed to form a failover cluster. This was due to one or more nodes executing incompatible versions of the cluster service software. If node &#39;%1&#39; or a different node in the cluster has been recently upgraded, please re-verify that all nodes are executing compatible versions of the cluster service software.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1547</td><td>Node &#39;%1&#39; attempted to join a failover cluster but failed due to incompatibility between versions of the cluster service software. If node &#39;%1&#39; or a different node in the cluster has been recently upgraded, please verify that the changed cluster deployment with different versions of the cluster service software is supported.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1548</td><td>Node &#39;%1&#39; established communication with node &#39;%2&#39; and detected that it is running a different, but compatible, version of the operating system. We recommend that all nodes run the same version of the operating system. After all nodes have been upgraded, run the Update-ClusterFunctionalLevel Windows PowerShell cmdlet to complete upgrading the cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1549</td><td>Node &#39;%1&#39; successfully became part of a failover cluster and detected that its cluster service software has been updated.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1550</td><td>Node &#39;%1&#39; established a communication session with node &#39;%2&#39; without performing a version compatibility check because version compatibility checking is disabled. Disabling version compatibility checking is not supported.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1551</td><td>Node &#39;%1&#39; formed a failover cluster without performing a version compatibility check because version compatibility checking is disabled. Disabling version compatibility checking is not supported.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1552</td><td>The cluster service detected that the witness disk designation has changed - usually indicating that the current node has stale cluster configuration data. This condition will be automatically reconciled when the current node connects to other nodes that have the latest configuration data. Please ensure that all cluster nodes are running.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1553</td><td>This cluster node has no network connectivity. It cannot participate in the cluster until connectivity is restored.  Run the Validate a Configuration wizard to check your network configuration. If the condition persists, check for hardware or software errors related to the network adapter. Also check for failures in any other network components to which the node is connected such as hubs, switches, or bridges.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1554</td><td>This cluster node has lost all network connectivity. It cannot participate in the cluster until connectivity is restored. The cluster service on this node will be terminated.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1555</td><td>Attempting to use IPv4 for &#39;%1&#39; network adapter failed. This was due to a failure to disable IPv4 auto-configuration and DHCP. This may be expected if the DHCP Client service is already disabled.  IPv6 will be used if enabled, otherwise this node may not be able to participate in a failover cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1556</td><td>The cluster service encountered an unexpected problem and will be shut down. The error code was &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1557</td><td>Cluster service failed to update the cluster configuration data on the witness resource. Please ensure that the witness resource is online and accessible.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1558</td><td>The cluster service detected a problem with the witness resource. The witness resource will be failed over to another node within the cluster in an attempt to reestablish access to cluster configuration data.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1559</td><td>File share &#39;%1&#39; associated with the file share witness resource is currently hosted by server &#39;%2&#39;. This server &#39;%2&#39; has just been added as a new node within the failover cluster. Hosting of the file share witness by any node comprising the same cluster is not recommended. Please choose a file share witness that is not hosted by any node within the same cluster and modify settings of the file share witness resource accordingly.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1560</td><td>Cluster file share resource &#39;%1&#39; has detected shared folder conflicts. As a result, some of these shared folders may not be accessible. To rectify this situation, ensure multiple shared folders do not have the same share name.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1561</td><td>Cluster service failed to start because this node detected that it does not have the latest copy of cluster configuration data. Changes to the cluster occurred while this node was not in membership and as a result was not able to receive configuration data updates.

Guidance:
Attempt to start the cluster service on all nodes in the cluster so that nodes with the latest copy of the cluster configuration data can first form the cluster. This node will then be able join the cluster and will automatically obtain the updated cluster configuration data. If there are no nodes available with the latest copy of the cluster configuration data, run the &#39;Start-ClusterNode -FQ&#39; Windows PowerShell cmdlet. Using the ForceQuorum (FQ) parameter will start the cluster service and mark this node&#39;s copy of the cluster configuration data to be authoritative.  Forcing quorum on a node with an outdated copy of the cluster database may result in cluster configuration changes that occurred while the node was not participating in the cluster to be lost.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1562</td><td>File share witness resource &#39;%1&#39; failed a periodic health check on file share &#39;%2&#39;. Please ensure that file share &#39;%2&#39; exists and is accessible by the cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1563</td><td>File share witness resource &#39;%1&#39; failed to come online. Please ensure that file share &#39;%2&#39; exists and is accessible by the cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1564</td><td>File share witness resource &#39;%1&#39; failed to arbitrate for the file share &#39;%2&#39;. Please ensure that file share &#39;%2&#39; exists and is accessible by the cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1565</td><td>This cluster node is running with a different message security level (&#39;%1&#39;) than remote node &#39;%3&#39; (&#39;%2&#39;). These two nodes will attempt to negotiate a mutually compatible message security level for this connection. Please ensure that the &#39;%4&#39; cluster property is configured correctly and that the cluster service has been restarted on all nodes since it was last changed.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1566</td><td>Cluster network name resource &#39;%1&#39; cannot be brought online.  The network name resource was terminated by the resource host subsystem because it did not complete an operation in an acceptable time.  The operation timed out while performing:
 &#39;%2&#39;</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1567</td><td>Cluster service failed to change the trace log size. Please verify the ClusterLogSize setting with the &#39;Get-Cluster | Format-List *&#39; PowerShell cmdlet. Also, use the Performance Monitor snapin to verify the event trace session settings for FailoverClustering.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1568</td><td>Cluster disk resource &#39;%1&#39; found the disk identifier to be stale. This may be expected if a restore operation was just performed or if this cluster uses replicated storage. The DiskSignature or DiskUniqueIds property for the disk resource has been corrected.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1569</td><td>Network &#39;%1&#39; which has been disabled for failover cluster use, was found to be the only currently possible network that node &#39;%2&#39; can use to communicate with other nodes in the cluster. This may impact the node&#39;s ability to participate in the cluster. Please verify network connectivity of node &#39;%2&#39; and enable at least one network for cluster communication. Run the Validate a Configuration wizard to check your network configuration.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1570</td><td>Node &#39;%1&#39; failed to establish a communication session while joining the cluster. This was due to an authentication failure. Please verify that the nodes are running compatible versions of the cluster service software.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1571</td><td>Node &#39;%1&#39; failed to establish a communication session while joining the cluster. This was due to an authorization failure. Please verify that the nodes are running compatible versions of the cluster service software.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1572</td><td>Node &#39;%1&#39; failed to join the cluster because it could not send and receive failure detection network messages with other cluster nodes. Please run the Validate a Configuration wizard to ensure network settings. Also verify the Windows Firewall &#39;Failover Clusters&#39; rules.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1573</td><td>Node &#39;%1&#39; failed to form a cluster. This was because the witness was not accessible. Please ensure that the witness resource is online and available.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1574</td><td>The failover cluster database could not be unloaded. If restarting the cluster service does not fix the problem, please restart the machine.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1575</td><td>An attempt to forcibly start the cluster service has failed because the cluster configuration data on this node is either missing or corrupt. Please first start the cluster service on another node that has an intact and valid copy of the cluster configuration data. Then, reattempt the start operation on this node (which will attempt to obtain updated valid configuration information automatically). If no other node is available, please use WBAdmin.msc to perform a System State Restore of this node in order to restore the configuration data.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1576</td><td>Cluster network name resource &#39;%1&#39; failed to register the name &#39;%2&#39; over adapter &#39;%4&#39; in a secure DNS zone. This was due to an existing record with this name and the cluster identity does not have the sufficient privileges to update that record. The error code was &#39;%3&#39;. Please contact your DNS server administrator to verify the cluster identity has permissions on DNS record &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1576</td><td>Cluster network name resource &#39;%1&#39; failed to register the name &#39;%2&#39; over adapter &#39;%4&#39; in a secure DNS zone. This was due to an existing record with this name and the cluster identity does not have the sufficient privileges to update that record. The error code was &#39;%3&#39;. Please contact your DNS server administrator to verify the cluster identity has permissions on DNS record &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1577</td><td>Cluster network name resource &#39;%1&#39; failed to register the name &#39;%2&#39; over adapter &#39;%4&#39;. The DNS server could not be contacted. The error code was &#39;%3.&#39; Ensure that a DNS server is accessible from this cluster node. The DNS registration will be retried later.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1577</td><td>Cluster network name resource &#39;%1&#39; failed to register the name &#39;%2&#39; over adapter &#39;%4&#39;. The DNS server could not be contacted. The error code was &#39;%3.&#39; Ensure that a DNS server is accessible from this cluster node. The DNS registration will be retried later.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1578</td><td>Cluster network name resource &#39;%1&#39; failed to register dynamic updates for name &#39;%2&#39; over adapter &#39;%4&#39;. The DNS server may not be configured to accept dynamic updates. The error code was &#39;%3&#39;. Please contact your DNS server administrator to verify that the DNS server is available and configured for dynamic updates.

Alternatively, you can disable dynamic DNS updates by unchecking the &#39;Register this connection&#39;s addresses in DNS&#39; setting in the advanced TCP/IP settings for adapter &#39;%4&#39; under the DNS tab.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1578</td><td>Cluster network name resource &#39;%1&#39; failed to register dynamic updates for name &#39;%2&#39; over adapter &#39;%4&#39;. The DNS server may not be configured to accept dynamic updates. The error code was &#39;%3&#39;. Please contact your DNS server administrator to verify that the DNS server is available and configured for dynamic updates.

Alternatively, you can disable dynamic DNS updates by unchecking the &#39;Register this connection&#39;s addresses in DNS&#39; setting in the advanced TCP/IP settings for adapter &#39;%4&#39; under the DNS tab.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1579</td><td>Cluster network name resource &#39;%1&#39; failed to update the DNS record for name &#39;%2&#39; over adapter &#39;%4&#39;. The error code was &#39;%3&#39;. Ensure that a DNS server is accessible from this cluster node and contact your DNS server administrator to verify the cluster identity can update the DNS record &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1579</td><td>Cluster network name resource &#39;%1&#39; failed to update the DNS record for name &#39;%2&#39; over adapter &#39;%4&#39;. The error code was &#39;%3&#39;. Ensure that a DNS server is accessible from this cluster node and contact your DNS server administrator to verify the cluster identity can update the DNS record &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1580</td><td>Cluster network name resource &#39;%1&#39; failed to register the name &#39;%2&#39; over adapter &#39;%4&#39; in a secure DNS zone. This was due to an existing record with this name and the cluster identity does not have the sufficient privileges to update that record. The error code was &#39;%3&#39;. Please contact your DNS server administrator to verify the cluster identity has permissions on DNS record &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1580</td><td>Cluster network name resource &#39;%1&#39; failed to register the name &#39;%2&#39; over adapter &#39;%4&#39; in a secure DNS zone. This was due to an existing record with this name and the cluster identity does not have the sufficient privileges to update that record. The error code was &#39;%3&#39;. Please contact your DNS server administrator to verify the cluster identity has permissions on DNS record &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1581</td><td>The restore request for the cluster configuration data failed to make a copy of the existing cluster configuration data file (ClusDB). While attempting to preserve the existing configuration, the restore operation was unable to create a copy at location &#39;%1&#39;. This might be expected if the existing configuration data file was corrupt. The restore operation has continued but attempts to revert to the existing cluster configuration may not be possible.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1582</td><td>Cluster Service failed to move the restored cluster hive at &#39;%1&#39; to &#39;%2&#39;.  This may prevent the restore operation from succeeding successfully.  If the cluster configuration was not properly restored, please retry the restore action.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1583</td><td>Cluster service failed to disable Internet Protocol security (IPsec) on the Failover cluster virtual adapter &#39;%1&#39;. This could have a negative impact on cluster communication performance. If this problem persists, please verify your local and domain connection security policies applying to IPSec and the Windows Firewall. Additionally, please check for events related to the Base Filtering Engine service.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1584</td><td>A backup application initiated a VSS snapshot on Cluster Shared Volume &#39;%1&#39; (&#39;%3&#39;) without properly preparing the volume for snapshot. This snapshot may be invalid and the backup may not be usable for restore operations. Please contact your backup application vendor to verify compatibility with Cluster Shared Volumes.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1585</td><td>Cluster file server resource &#39;%1&#39; failed a health check. This was due to the Server service not being started. Please use Server Manager to confirm the state of the Server service on this cluster node.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1586</td><td>Cluster file server resource &#39;%1&#39; failed a health check. This was because some of its shared folders were inaccessible. Verify that the folders are accessible from clients. Additionally, confirm the state of the Server service on this cluster node using Server Manager and look for other events related to the Server service on this cluster node. It may be necessary to restart the network name resource &#39;%2&#39; in this clustered role.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1587</td><td>Cluster file server resource &#39;%1&#39; failed a health check. This was because some of its shared folders were inaccessible. Verify that the folders are accessible from clients. Additionally, confirm the state of the Server service on this cluster node using Server Manager and look for other events related to the Server service on this cluster node.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1588</td><td>Cluster file server resource &#39;%1&#39; cannot be brought online. The resource failed to create file share &#39;%2&#39; associated with network name &#39;%3&#39;. The error code was &#39;%4&#39;. Verify that the folders exist and are accessible. Additionally, confirm the state of the Server service on this cluster node using Server Manager and look for other related events on this cluster node. It may be necessary to restart the network name resource &#39;%3&#39; in this clustered role.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1589</td><td>Cluster network name resource &#39;%1&#39; found one or more IP addresses associated with DNS name &#39;%2&#39; that are not dependent IP address resources. The additional addresses found were &#39;%3&#39;. This may affect client connectivity until the network name and its associated DNS records are consistent. Please contact your DNS server administrator to verify the records associated with name &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1592</td><td>Cluster node &#39;%1&#39; lost communication with cluster node &#39;%2&#39;.  Network communication was reestablished. This could be due to communication temporarily being blocked by a firewall or connection security policy update. If the problem persists and network communication are not reestablished, the cluster service on one or more nodes will stop.  If that happens, run the Validate a Configuration wizard to check your network configuration. Additionally, check for hardware or software errors related to the network adapters on this node, and check for failures in any other network components to which the node is connected such as hubs, switches, or bridges.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1593</td><td>The failover cluster database could not be unloaded and any potentially incorrect changes in memory could not be discarded.  The cluster service will attempt to repair the database by retrieving it from another cluster node.  If the cluster service does not come online, restart the cluster service on this node.  If restarting the cluster service does not fix the problem, please restart the machine.  If the cluster service fails to come online after a reboot, please restore the cluster database from the last backup.  The current database was copied to &#39;%1&#39;.  If no backups are available, please copy &#39;%1&#39; to &#39;%2&#39; and attempt to start the cluster service.  If the cluster service then comes online on this node, some cluster configuration changes may be lost and the cluster may not function properly.  Run the Validate a Configuration wizard to check your cluster configuration and verify that the hosted Services and Applications are online and functioning correctly.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1594</td><td>Cluster service successfully upgraded the cluster functional level.  \n\n Functional Level: %1 \n Upgrade Version: %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1600</td><td>Cluster service failed to set the permissions on the cluster computer object &#39;%1&#39;. Please contact your network administrator to check the cluster security descriptor of the computer object in Active Directory, verify that the DACL is not too big, and remove any unnecessary extra ACE(s) on the object if necessary.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1601</td><td>The Cluster service successfully brought the Scale-out file server clone online.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1602</td><td>The Cluster service successfully brought the Scale-out file server clone offline.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1603</td><td>Cluster service failed to create a clone of the Scale Out File Server resource. This node will not be able to accept SMB connections to the Scale Out File Server. The error code was &#39;0x%2&#39;. Ensure that the Server service is running and functional on this node. Moving the Scale Out File Server resource to another node will attempt to recreate the clone.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1604</td><td>Cluster disk resource &#39;%1&#39; detected corruption for volume &#39;%2&#39;. Spotfix Chkdsk is required to repair problems.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1605</td><td>Cluster disk resource &#39;%1&#39; completed running ChkDsk.exe /spotfix on volume &#39;%2&#39;. The return code was &#39;%4&#39;. Output from the ChkDsk has been logged to file &#39;%3&#39;.
 Check the application event log for additional information from ChkDsk.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1606</td><td>Cluster disk resource &#39;%1&#39; contains a BitLocker-protected volume, &#39;%2&#39;, but for this volume, the Active Directory cluster name account (also called the cluster name object or CNO) is not a BitLocker protector for the volume. This is required for BitLocker-protected volumes. To correct this, first remove the disk from the cluster. Next, use the Manage-bde.exe command-line tool to add the cluster name as an ADAccountOrGroup protector, using the format domain\ClusterName$ for the cluster name. Then add the disk back to the cluster. For more information, see the documentation for Manage-bde.exe;</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1607</td><td>Cluster disk resource &#39;%1&#39; was unable to unlock the BitLocker-protected volume &#39;%2&#39;. The cluster name object (CNO) is not set to be a valid BitLocker protector for this volume. To correct this, remove the disk from the cluster. Then use the Manage-bde.exe command-line tool to add the cluster name as an ADAccountOrGroup protector, using the format domain\ClusterName$, and add the disk back to the cluster. For more information, see the documentation for Manage-bde.exe.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1608</td><td>File Server could not start because expected dependency on &#39;Network Name&#39; resource was not found or it was not configured properly. Error=0x%2.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1609</td><td>Scale Out File Server could not start because expected dependency on &#39;Distributed Network Name&#39; resource was not found or it was not configured properly. Error=0x%2.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1632</td><td>The creation of the cluster failed.  Unable to create the cluster name object &#39;%1&#39; in active directory organizational unit &#39;%2&#39;. The object already exists in organizational unit &#39;%3&#39;.  Verify that the specified distinguished name path and the cluster name object are correct.  If the distinguished name path is not specified, the existing computer object &#39;%1&#39; will be used.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1633</td><td>The Cluster service failed to bring clustered role &#39;%1&#39; completely online or offline. One or more resources may be in a failed or an offline state. This may impact the availability of the clustered role.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1634</td><td>Clustered service or application &#39;%1&#39; has exceeded its failover threshold.  It has exhausted the configured number of failover attempts within the failover period of time alotted to it and will be left in a failed state.  No additional attempts will be made to bring the service or application online or fail it over to another node in the cluster.  Please check the events associated with the failure.  After the issues causing the failure are resolved the service or application can be brought online manually or the cluster may attempt to bring it online again after the restart delay period.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1635</td><td>Cluster resource &#39;%1&#39; in clustered role &#39;%2&#39; failed.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1635</td><td>Cluster resource &#39;%1&#39; of type &#39;%3&#39; in clustered role &#39;%2&#39; failed.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1636</td><td>The Cluster service has changed the password of account &#39;%1&#39; on node &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1637</td><td>Cluster resource &#39;%1&#39; in clustered role &#39;%2&#39; has transitioned from state %3 to state %4.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1637</td><td>Cluster resource &#39;%1&#39; in clustered role &#39;%2&#39; has transitioned from state %3 to state %4. Cluster resource &#39;%1&#39; is waiting on the following resources: %5.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1638</td><td>Cluster resource &#39;%1&#39; in clustered role &#39;%2&#39; has exceeded the maximum number of consecutive failures. It has exhausted the number of restart attempts within the failover period of time allotted to it and will be left in a failed state. No additional attempts will be made to bring the resource online. Check the events associated with the failure. After the issues causing the failure are resolved the resource can be brought online manually or the cluster may attempt to bring it online again after the restart delay period.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1639</td><td>Cluster resource &#39;%1&#39; in clustered role &#39;%2&#39; cannot come online due to an antiaffinity conflict.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1640</td><td>Clustered roles with priority less than &#39;%1&#39; are currently waiting on higher-priority roles to start.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1641</td><td>Clustered role &#39;%1&#39; is moving to cluster node &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1641</td><td>Clustered role &#39;%1&#39; is moving from cluster node &#39;%2&#39; to cluster node &#39;%3&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1648</td><td>Clustered role &#39;%1&#39; is currently waiting for the quorum witness resource to come online before starting.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1649</td><td>Cluster resource &#39;%1&#39; in clustered role &#39;%2&#39; has taken more than one minute to respond to a control code. The control code was &#39;%3&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1650</td><td>Cluster has established a UDP connection from local endpoint %1 connected to remote endpoint %2.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1650</td><td>Cluster has lost the UDP connection from local endpoint %1 connected to remote endpoint %2.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1650</td><td>Microsoft Failover Cluster Virtual Adapter (NetFT) has missed more than 40 percent of consecutive heartbeats.

Local endpoint: %1
Remote endpoint: %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1651</td><td>Cluster has received notification that Adapter %1 is now in a connected state.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1651</td><td>Cluster has received notification that Adapter %1 is now in a disconnected state.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1652</td><td>Cluster node &#39;%1&#39; failed to join the cluster. A TCP connection could not be established to node(s) &#39;%2&#39;. Verify network connectivity and configuration of any network firewalls.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1652</td><td>Cluster node &#39;%1&#39; failed to join the cluster. A UDP connection could not be established to node(s) &#39;%2&#39;. Verify network connectivity and configuration of any network firewalls</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1652</td><td>Cluster node &#39;%1&#39; failed to join the cluster. A TCP connection using the Microsoft Failover Cluster Virtual Adapter could not be established to node(s) &#39;%2&#39;. Verify network connectivity and configuration of any network firewalls.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1653</td><td>Cluster node &#39;%1&#39; failed to join the cluster because it could not communicate over the network with any other node in the cluster. Verify network connectivity and configuration of any network firewalls.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1654</td><td>Cluster Disjoint IP address resource &#39;%1&#39; failed to come online. Configuration data for the network adapter corresponding to network adapter &#39;%2&#39; could not be determined (error code was &#39;%3&#39;). Check that the IP address resource is configured with the correct address and network properties.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1655</td><td>Cluster Disjoint IP address resource &#39;%1&#39; failed to come online. Configuration data for the network adapter corresponding to Virtual Subnet Id &#39;%2&#39; and Routing Domain Id &#39;%3&#39; could not be determined (error code was &#39;%4&#39;). Check that the IP address resource is configured with the correct address and network properties.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1656</td><td>Failed to add the IP Address &#39;%2&#39; for Disjoint IP address resource &#39;%1&#39; (error code was &#39;%3&#39;). Check for hardware or software errors related to the physical or virtual network adapters.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1657</td><td>Health check for IP interface &#39;%1&#39;(address &#39;%2&#39;) failed (status is &#39;%3&#39;). Check for hardware or software errors related to the physical or virtual network adapters.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1658</td><td>Cloud witness resource could not reach Microsoft Azure storage services.\n\nCluster resource: %1 \nCluster node: %2 \n\nGuidance:\nThis could be due to network communication between the cluster node and the Microsoft Azure service being blocked. Verify the node&#39;s internet connectivity to Microsoft Azure. Connect to the Microsoft Azure portal and verify that the storage account exists.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1659</td><td>Cloud witness resource failed to authenticate with Microsoft Azure storage services. An access denied error was returned while attempting to contact the Microsoft Azure storage account. \n\nCluster resource: %1 \n\nGuidance:\n The storage account&#39;s access key may no longer be valid. Use the Configure Cluster Quorum Wizard in the Failover Cluster Manager or the Set-ClusterQuorum Windows PowerShell cmdlet, to configure the Cloud witness resource with the updated storage account access key.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1664</td><td>Upgrading the functional level of the cluster failed. Check that all nodes of the cluster are currently running and are the same version of Windows Server, then run the Update-ClusterFunctionalLevel Windows PowerShell cmdlet again.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1665</td><td>Online operation for the Physical Disk resource &#39;%1&#39; is started.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1666</td><td>Online operation for the Physical Disk resource &#39;%1&#39; is completed with status &#39;%2&#39;. </td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1667</td><td>Offline operation for the Physical Disk resource &#39;%1&#39; is started.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1668</td><td>Offline operation for the Physical Disk resource &#39;%1&#39; is completed with status &#39;%2&#39;. </td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1669</td><td>Cluster physical disk resource took longer than expected to reach an online state.

Physical Disk resource name: %1

Guidance:
During the Online Pending phase the Physical Disk resource will wait for dependent components to be ready for the volumes to be mounted. Delays can occur when using replicated volumes if there is a large amount of data that needs to be replicated before the volume is ready to be mounted. The Cluster Service will wait for Storage Replication to respond that it is ready. Review the Storage Replication events for additional information on what operations are taking additional time to complete.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1670</td><td>Cluster physical disk resource successfully brought the resource online.

Physical Disk resource name: %1
Time Elapsed (seconds): %3</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1671</td><td>Cluster physical disk resource cannot be brought online.

Physical Disk resource name: %1
Error Code: %2
Time Elapsed (seconds): %3

Guidance:
Run the Validate a Configuration wizard to check your storage configuration. If the error code was ERROR_CLUSTER_SHUTDOWN then the Online Pending state was cancelled by an administrator. If this is a replicated volume then this could be the result of a failure to set the disk attributes.  Review the Storage Replication events for additional information.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1672</td><td>Cluster node &#39;%1&#39; has been quarantined.  The node experienced &#39;%2&#39; consecutive failures within a short amount of time and has been removed from the cluster to avoid further disruptions. The node will be quarantined until &#39;%3&#39; and then the node will automatically attempt to re-join the cluster.

Refer to the System and Application event logs to determine the issues on this node.  When the issue is resolved, quarantine can be manually cleared to allow the node to rejoin with the &#39;Start-ClusterNode –ClearQuarantine&#39; Windows PowerShell cmdlet.

Node Name : %1
Number of consecutive cluster membership loses: %2
Time quarantine will be automatically cleared: %3</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1673</td><td>Cluster node &#39;%1&#39; has entered the isolated state.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1673</td><td>Resource &#39;%1&#39; moved from group &#39;%2&#39; on node &#39;%3&#39; to group &#39;%4&#39; on node &#39;%5&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1674</td><td>Group &#39;%1&#39; has transitioned from state &#39;%2&#39; to state &#39;%3&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1675</td><td>Cluster node &#39;%1&#39; has been quarantined by &#39;%2&#39; and cannot join the cluster. The node will be quarantined until &#39;%3&#39; and then the node will automatically attempt to re-join the cluster. 

Refer to the System and Application event logs to determine the issues on this node.  When the issue is resolved, quarantine can be manually cleared to allow the node to rejoin with the &#39;Start-ClusterNode –ClearQuarantine&#39; Windows PowerShell cmdlet.

Node Name : %1
QuarantineType : Quarantine by %2
Time quarantine will be automatically cleared: %3</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1676</td><td>Local cluster node has been quarantined by &#39;%1&#39;. The node will be quarantined until &#39;%2&#39; and then the node will automatically attempt to re-join the cluster. 

Refer to the System and Application event logs to determine the issues on this node.  When the issue is resolved, quarantine can be manually cleared to allow the node to rejoin with the &#39;Start-ClusterNode –ClearQuarantine&#39; Windows PowerShell cmdlet.

QuarantineType : Quarantined by %1
Time quarantine will be automatically cleared: %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1677</td><td>Node drain failed on Cluster node %1. 

Reference the node&#39;s System and Application event logs and cluster logs to investigate the cause of the drain failure.  When the problem is resolved, you can retry the drain operation.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1680</td><td>Cluster node &#39;%1&#39; has exited the isolated state.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1681</td><td>Virtual machines on node &#39;%1&#39; have entered an unmonitored state. The virtual machines health will be monitored again once the node returns from an isolated state or may failover if the node does not return. The virtual machine no longer being monitored are: %2.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1682</td><td>Virtual machine &#39;%2&#39; which was unmonitored on the isolated node &#39;%1&#39; has been failed over to another node. The health of the virtual machine is once again being monitored.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1682</td><td>Node &#39;%1&#39; has rejoined the cluster and the following virtual machines running on that node are once again having their health state monitored: %2.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1683</td><td>The cluster service was unable to reach any available domain controller on the domain. This may impact functionality that is dependent on Cluster network name authentication.

DC Server: %1 

Guidance:
 Verify that domain controllers are accessible on the network to the cluster nodes.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1684</td><td>Cluster network name resource failed to find the associated computer object in Active Directory. This may impact functionality that is dependent on Cluster network name authentication.

Network Name: %1
Organizational Unit: %2

Guidance:

Restore the computer object for the network name from the Active Directory recycle bin. Alternately, offline the cluster network name resource and run the Repair action to recreate the computer object in Active Directory.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1685</td><td>Cluster network name resource failed to find the associated computer object in Active Directory. This may impact functionality that is dependent on Cluster network name authentication.

Network Name: %1
Organizational Unit: %2

Guidance:

Restore the computer object for the network name from the Active Directory recycle bin.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1686</td><td>Cluster network name resource found the associated computer object in Active Directory to be disabled. This may impact functionality that is dependent on Cluster network name authentication.

Network Name: %1
Organizational Unit: %2

Guidance:

Enable the computer object for the network name in Active Directory.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1687</td><td>Cluster network name resource found the associated computer object in Active Directory to be disabled. This may impact functionality that is dependent on Cluster network name authentication.

Network Name: %1
Organizational Unit: %2

Guidance:

Enable the computer object for the network name in Active Directory. Alternately, offline the cluster network name resource and run the Repair action to enable the computer object in Active Directory.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1688</td><td>Cluster network name resource detected that the associated computer object in Active Directory was disabled and failed in its attempt to enable it. This may impact functionality that is dependent on Cluster network name authentication.

Network Name: %1
Organizational Unit: %2

Guidance:

Enable the computer object for the network name in Active Directory.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1689</td><td>The cluster service detected a service which is not compatible with Failover Clustering. The service has been disabled to avoid possible problems with the Failover Cluster.

Service name: &#39;%1&#39;</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1690</td><td>The cluster role was not brought online automatically because IgnorePersistentStateOnStartup is enabled. This parameter is used for troubleshooting Cluster Service startup issues and prevents cluster roles from coming online automatically. 

 Role: %1 

 Guidance:
Once the troubleshooting is complete, this parameter can be disabled to allow roles to online automatically by using the following Windows PowerShell cmdlet: (Get-Cluster).IgnorePersistentStateOnStartup = 0</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1691</td><td>The cluster service started with the IgnorePersistentStateOnStartup parameter enabled. This parameter is used for troubleshooting Cluster Service startup issues and prevents cluster roles from coming online automatically. 

Guidance:
Once the troubleshooting is complete, this parameter can be disabled to allow roles to online automatically by using the following Windows PowerShell cmdlet: (Get-Cluster).IgnorePersistentStateOnStartup = 0</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1792</td><td>Cluster physical disk resource failed periodic health check. 

 Physical Disk resource name: %1 
 Device Number: %2 
 Device Guid: %3 
  Error Code: %4 
 Reason: %5</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1793</td><td>Cluster physical disk resource failed to come online.

Resource Name: %1
Device Number: %2
Device Guid: %3
Error Code: %4
Reason: %5</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1794</td><td>Cluster physical disk resource failed to go offline.

Physical Disk Resource Name: %1
Device Number: %2
Device Guid: %3
Error Code: %4
Additional reason: %5</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1795</td><td>Cluster physical disk resource encountered an error while attempting to terminate.

Phsyical Disk Resource Name: %1
Device Number: %2
Device Guid: %3
Error Code: %4
Reason: %5</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1808</td><td>The cluster load balancer has identified the current node is exceeding the CPU or memory usage threshold.  Virtual Machines will be moved to a new node to balance the cluster. 

 Current Node: %1 
 Virtual Machines: %2 
 New Node: %3</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1809</td><td>This node has been joined to a cluster that has Storage Spaces Direct enabled, which is not validated on the current build. The node will be quarantined.

Microsoft recommends deploying SDDC on WSSD [https://www.microsoft.com/en-us/cloud-platform/software-defined-datacenter] certified hardware offerings for production environments. The WSSD offerings will be pre-validated on Windows Server 2019 in the coming months. In the meantime, we are making the SDDC bits available early to Windows Server 2019 Insiders to allow for testing and evaluation in preparation for WSSD certified hardware becoming available.

Customers interested in upgrading existing WSSD environments to Windows Server 2019 should contact Microsoft for recommendations on how to proceed. Please call Microsoft support [https://support.microsoft.com/en-us/help/4051701/global-customer-service-phone-numbers].</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1810</td><td>Cluster Physical Disk Resource added a protector to a BitLocker encrypted volume. 

ResourceName: %1
Volume: %2
ProtectorType: %3
ProtectorId: %4
TimeInMilliseconds: %5</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1811</td><td>Cluster Physical Disk Resource failed to add a protector to a BitLocker encrypted volume. 

ResourceName: %1
Volume: %2
ProtectorType: %3
TimeInMilliseconds: %4
Status: %5</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1812</td><td>Cluster Physical Disk Resource completed a storage operation. 

ResourceName: %1
Device: %2
Operation: %3
TimeInMilliseconds: %4
Status: %5
AdditionalInformation: %6</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1813</td><td>Cluster Physical Disk Resource completed resource online.

ResourceName: %1
OperationTimes: %2
TotalTimeInMilliseconds: %3
Status: %4</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1814</td><td>Cluster Physical Disk Resource completed resource offline.

ResourceName: %1
OperationTimes: %2
TotalTimeInMilliseconds: %3
Status: %4</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1815</td><td>Cluster Physical Disk Resource completed resource terminate.

ResourceName: %1
OperationTimes: %2
TotalTimeInMilliseconds: %3
Status: %4</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>1816</td><td>Cluster Physical Disk Resource could not find expected number of usable data volumes during online.

ResourceName: %1
Device: %2
VolumesExpected: %3
VolumesFound: %4</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>2049</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>2050</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>2051</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>2052</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4096</td><td>[NETFTAPI] received %1 for %2 (%3)</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4097</td><td>[NETFTAPI] received %1 for %2 (%3)</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4098</td><td>[NETFTAPI] received %1 for %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4099</td><td>[NETFTAPI] received %1 for %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4100</td><td>[NETFTAPI] received %1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4101</td><td>[NETFTAPI] Signaled %1 event for %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4102</td><td>[NETFTAPI] Signaled %1 event for %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4103</td><td>[NETFTAPI] Signaled %1 event, local address %2:%3 remote address %4:%5</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4104</td><td>[NETFTAPI] Signaled %1 event, local address [%2]:%3 remote address [%4]:%5</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4105</td><td>[NETFTAPI] Signaled %1 event, alias %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4106</td><td>[NETFTAPI] Failed to allocate %1 network address entry (status %2)</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4107</td><td>[NETFTAPI] Failed to allocate %1 network address entry (status %2)</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4108</td><td>[NETFTAPI] Failed to query initialization parameters for %1 (status %2)</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4109</td><td>[NETFTAPI] Failed to query initialization parameters for %1 (status %2)</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4110</td><td>[NETFTAPI] Failed to query parameters for %1 (status %2)</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4111</td><td>[NETFTAPI] Failed to query parameters for %1 (status %2)</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4112</td><td>[NETFTAPI] Subscriber thrown exception %1 processing NETFT notification</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4113</td><td>[NETFTAPI] Failed to allocate %1 network interface entry (status %2)</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4114</td><td>[NETFTAPI] The IPv4/802 provider is not present</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4115</td><td>[NETFTAPI] The IPv6/802 provider is not present</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4116</td><td>[NETFTAPI] Event processing thread failed to register for NETFT event (status %1)</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4117</td><td>[NETFTAPI] Event processing thread completed processing loop (status %1)</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4118</td><td>[NETFTAPI] The watchdog miniport is halting.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4608</td><td>The list of clustered disks has been retrieved during cluster node cleanup.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4609</td><td>Cluster service failed to retrieve the list of clustered disks while destroying the cluster. The error code was &#39;%1&#39;. If these disks are not accessible, execute the &#39;Clear-ClusterDiskReservation&#39; PowerShell cmdlet.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4610</td><td>Clustered disks have been released by the Partition Manager while destroying the cluster. These disks will be left in an offline state. For these released disks to be accessible, please bring them online on a single machine only, using the Disk Management utility.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4611</td><td>Clustered disk with ID &#39;%2&#39; was not released by the Partition Manager while destroying the cluster. The error code was &#39;%1&#39;. Restarting the machine will ensure the disk is released by the Partition Manager.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4612</td><td>The clustered disks database has been cleared as part of cluster node cleanup.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4613</td><td>The cluster service failed to properly cleanup a clustered disk with ID &#39;%2&#39; while destroying the cluster. The error code was &#39;%1&#39;. You may unable to access this disk until cleanup has been successfully completed. For manual cleanup, delete the &#39;AttachedDisks&#39; value of the &#39;HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\ClusDisk\Parameters&#39; key in the Windows registry.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4614</td><td>The cluster service has been stopped and set as disabled as part of cluster node cleanup.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4615</td><td>Disabling the cluster service during cluster node cleanup, has failed. The error code was &#39;%1&#39;. You may be unable to create or join a cluster with this machine until cleanup has been successfully completed. For manual cleanup, execute the &#39;Clear-ClusterNode&#39; PowerShell cmdlet on this machine.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4616</td><td>Termination of the cluster service during cluster node cleanup has not completed within the expected time period. Please restart this machine to ensure the cluster service is no longer running.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4617</td><td>The cluster service registry entries on this machine have been reset as part of cluster node cleanup.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4618</td><td>Resetting cluster service registry entries during cluster node cleanup failed. The error code was &#39;%1&#39;. You may be unable to create or join a cluster with this machine until cleanup has been successfully completed. For manual cleanup, execute the &#39;Clear-ClusterNode&#39; PowerShell cmdlet on this machine.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4619</td><td>The cluster Windows registry hive has been unloaded.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4620</td><td>Unloading the cluster service registry hive during cluster node cleanup failed. The error code was &#39;%1&#39;. You may be unable to create or join a cluster with this machine until cleanup has been successfully completed. For manual cleanup, execute the &#39;Clear-ClusterNode&#39; PowerShell cmdlet on this machine.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4621</td><td>This node was sucessfully removed from the cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4622</td><td>The Cluster service encountered an error during node cleanup. You may be unable to create or join a cluster with this machine until cleanup has been successfully completed. Use the &#39;Clear-ClusterNode&#39; PowerShell cmdlet on this node.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4623</td><td>The IPSec security association timeout has been reset on this machine as part of cluster node cleanup. This restores the IPSec security association timeout to the default policy for non-clustered machines.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4624</td><td>Resetting the IPSec security association timeout registry value failed during cluster node cleanup. The error code was &#39;%1&#39;. For manual cleanup, execute the &#39;Clear-ClusterNode&#39; PowerShell cmdlet on this machine. Alternatively, you may reset the IPSec security association timeout by deleting the &#39;%2&#39; value and the &#39;%3&#39; value from HKEY_LOCAL_MACHINE in the Windows registry.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4625</td><td>Resetting the IPSec security association timeout registry value failed during cluster node cleanup. This is because the IPSec security association timeout was modified after this machine was configured to be a member of a cluster. For manual cleanup, execute the &#39;Clear-ClusterNode&#39; PowerShell cmdlet on this machine. Alternatively, you may reset the IPSec security association timeout by deleting the &#39;%1&#39; value and the &#39;%2&#39; value from HKEY_LOCAL_MACHINE in the Windows registry.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4626</td><td>All clustered tasks on this node have been deleted as part of node cleanup.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4627</td><td>Deletion of clustered tasks during node cleanup failed. The error code was &#39;%1&#39;. Use Windows Task Scheduler to delete any remaining clustered tasks.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4628</td><td>During node cleanup, the local user account that is managed by the cluster was deleted.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4629</td><td>During node cleanup, the local user account that is managed by the cluster was not deleted.  The error code was &#39;%1&#39;. Open Local Users and Groups (lusrmgr.msc) to delete the account.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4864</td><td>Volume shadow copy service task resource &#39;%1&#39; creation failed. The error code was &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4865</td><td>Volume shadow copy service task resource &#39;%1&#39; failed. The error code was &#39;%2&#39;. This is because the associated task could not be stopped as part of an offline operation. You may need to stop it manually using the Task Scheduler snapin.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4866</td><td>Volume shadow copy service task resource &#39;%1&#39; failed. The error code was &#39;%2&#39;. This is because the associated task could not be deleted as part of an offline operation. You may need to delete it manually using the Task Scheduler snapin.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4867</td><td>Volume shadow copy service task resource &#39;%1&#39; failed. The error code was &#39;%2&#39;. This is because the associated task could not be added as part of an online operation. Please use the Task Scheduler snapin to ensure your tasks are properly configured.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4868</td><td>Cluster service failed to start the cluster log trace session. The error code was &#39;%2&#39;. The cluster will function properly, but supplemental logging information will be missing. Use the Performance Monitor snapin to verify the event channel settings for &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4869</td><td>User mode health monitoring has detected that the system is not being responsive. The Failover cluster virtual adapter has lost contact with the &#39;%1&#39; process with a process ID &#39;%2&#39;, for &#39;%3&#39; seconds. Please use Performance Monitor to evaluate the health of the system and determine which process may be negatively impacting the system.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4870</td><td>User mode health monitoring has detected that the system is not being responsive. The Failover cluster virtual adapter has lost contact with the &#39;%1&#39; process with a process ID &#39;%2&#39;, for &#39;%3&#39; seconds. Recovery action will be taken.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4871</td><td>The cluster service failed to start. This was because the failover cluster virtual adapter failed to initialize the miniport adapter. The error code was &#39;%1&#39;. Verify that other network adapters are functioning properly and check the device manager for errors. If the configuration was changed, it may be necessary to reinstall the failover clustering feature on this computer.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4872</td><td>The failover cluster virtual adapter failed to generate a unique MAC address. Either it was unable to find a physical Ethernet adapter from which to generate a unique address or the generated address conflicts with another adapter on this machine. Please run the Validate a Configuration wizard to check your network configuration.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4873</td><td>The cluster service has detected that the failover cluster virtual adapter has stopped. This is expected when hot replace CPU is performed on this node. Cluster service will stop and should automatically restart after the operation is complete. Please check for additional events associated with the service and ensure that the cluster service has been restarted on this node.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>4874</td><td>User mode health monitoring has detected that the system is not being responsive. The Failover Cluster virtual adapter has lost contact with a process. Recovery action will be taken.  

 Process: %1 
 Process ID: %2 
 Seconds: %3</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5120</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%2&#39;) has entered a paused state because of &#39;%3&#39;. All I/O will temporarily be queued until a path to the volume is reestablished.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5121</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%2&#39;) is no longer directly accessible from this cluster node. I/O access will be redirected to the storage device over the network to the node that owns the volume. If this results in degraded performance, please troubleshoot this node&#39;s connectivity to the storage device and I/O will resume to a healthy state once connectivity to the storage device is reestablished.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5122</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%2&#39;) has now resumed normal operation.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5123</td><td>Cluster service failed to create the Cluster Shared Volumes root directory &#39;%2&#39;. The error message was &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5124</td><td>Cluster Shared Volumes root directory &#39;%1&#39; already exists. The directory &#39;%1&#39; was renamed to &#39;%2&#39;. Please verify that applications accessing data in this location have been updated as necessary.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5125</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%3&#39;) has identified one or more active filter drivers on this device stack that could interfere with CSV operations. I/O access will be redirected to the storage device over the network through another Cluster node. This may result in degraded performance. Please contact the filter driver vendor to verify interoperability with Cluster Shared Volumes. 

Active filter drivers found:
%2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5126</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%3&#39;) has identified one or more active volume drivers on this device stack that could interfere with CSV operations. I/O access will be redirected to the storage device over the network through another Cluster node. This may result in degraded performance. Please contact the volume driver vendor to verify interoperability with Cluster Shared Volumes. 

Active volume drivers found:
%2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5128</td><td>Physical disk resource &#39;%1&#39; does not allow disabling short name generation. This may cause application compatibility issues. Please use &#39;fsutil 8dot3name set 2&#39; to allow disabling short name generation and then offline/online the resource.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5129</td><td>Cluster Shared Volumes has been enabled on this cluster by user &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5130</td><td>Cluster Shared Volumes has been disabled on this cluster by user &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5131</td><td>Cluster Disk &#39;%1&#39; has been added to Cluster Shared Volumes.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5132</td><td>Cluster Disk &#39;%1&#39; has been removed from Cluster Shared Volumes. The disk resource &#39;%1&#39; is now part of the &#39;Available Storage&#39; cluster group.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5133</td><td>Cluster Disk &#39;%1&#39; has been removed and placed back in the &#39;Available Storage&#39; cluster group. During this process an attempt to restore the original drive letter(s) has taken longer than expected, possibly due to those drive letters being already in use.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5134</td><td>Cluster service failed to set the permissions (ACL) on the Cluster Shared Volumes root directory &#39;%1&#39;. The error was &#39;%2&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5135</td><td>Cluster service failed to set the permissions on the Cluster Shared Volume directory &#39;%1&#39; (&#39;%2&#39;). The error was &#39;%3&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5136</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%2&#39;) redirected access was turned on. Access to the storage device will be redirected over the network from all cluster nodes that are accessing this volume. This may result in degraded performance. Turn off redirected access for this volume to resume normal operations.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5137</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%2&#39;) redirected access was turned off. The volume has now resumed normal operation.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5138</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%2&#39;) maintenance was turned on. This volume will not be accessible by the highly available service or application until maintenance is complete and the volume maintenance is turned off.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5139</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%2&#39;) maintenance was turned off.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5140</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%2&#39;) backup was turned on. Once the backup application completes the backup process, the Cluster Shared Volume backup mode will be turned off. If the backup application has not initiated a snapshot using the Volume Shadow Copy Service within %3 minutes, Cluster Shared Volume backup will be turned off.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5141</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%2&#39;) backup was turned off.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5142</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%2&#39;) is no longer accessible from this cluster node because of error &#39;%3&#39;. Please troubleshoot this node&#39;s connectivity to the storage device and network connectivity.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5143</td><td>Move of the disk (&#39;%2&#39;) is vetoed based on the current state of the Cache Manager on the node &#39;%1&#39; to prevent a potential deadlock. &#39;Cache Manager Dirty Pages Theshold&#39; is %3, and &#39;Cache Manager Dirty Pages&#39; is %4. Move is allowed if &#39;Cache Manager Dirty Pages&#39; is less than 70% of &#39;Cache Manager Dirty Pages Theshold&#39; or if &#39;Cache Manager Dirty Pages Theshold&#39; minus &#39;Cache Manager Dirty Pages&#39; is greater than 128000 pages (about 500MB if a page size is 4096 bytes). Cluster vetoed resource move to prevent potential deadlock due to Cache Manager throttling buffered writes while Cluster Shared Volumes on this disk are being paused.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5144</td><td>While adding the disk (&#39;%1&#39;) to Cluster Shared Volumes, setting explicit snapshot diff area association for volume (&#39;%2&#39;) failed with error &#39;%3&#39;. The only supported software snapshot diff area association for Cluster Shared Volumes is to self.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5145</td><td>Cluster disk resource &#39;%1&#39; failed to delete a software snapshot.  The diff area on volume &#39;%3&#39; could not be dissociated from volume &#39;%2&#39;. This may be caused by active snapshots. Cluster Shared Volumes requires that the software snapshot be located on the same disk.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5146</td><td>Move of the Cluster Shared Volume resource &#39;%1&#39; is vetoed because one of the volumes belonging to the resource is in dismounted state. Please retry the action after the dismount operation is completed.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5147</td><td>Move of the Cluster Shared Volume resource &#39;%1&#39; is vetoed because a snapshot is being created on one of the volumes belonging to the resource. Please retry the action after the snapshot creation is completed.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5148</td><td>Move of the Cluster Shared Volume resource &#39;%1&#39; is vetoed because an IO mode change operation (Direct IO to Redirected IO or vice versa) is in progress on one of the volumes belonging to the resource. Please retry the action after the operation is completed.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5149</td><td>Cache size resized to &#39;%1&#39; based on populated memory, user setsize is too high.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5150</td><td>Cluster physical disk resource &#39;%1&#39; failed.  The Cluster Shared Volume was put in failed state with the following error: &#39;%2&#39;</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5151</td><td>Cluster Shared Volume &#39;%1&#39; (resource &#39;%2&#39;) transitioned to state &#39;%3&#39; as part of processing &#39;%4&#39; initiated by node &#39;%5&#39; with sequence number &#39;%6&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5152</td><td>Cluster Shared Volume &#39;%1&#39; (resource &#39;%2&#39;) was unable to complete a  state transition. This was likely caused as part of processing &#39;%4&#39; with sequence number &#39;%5&#39; on nodes (&#39;%3&#39;). Cluster will attempt to create live dumps on the nodes.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5153</td><td>Cluster Shared Volume &#39;%1&#39; (resource &#39;%2&#39;) received event &#39;%3&#39; with sequence number &#39;%4&#39; which originated in node &#39;%5&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5154</td><td>Cluster Shared Volume &#39;%1&#39; (resource &#39;%2&#39;) completed processing event &#39;%3&#39; with sequence number &#39;%4&#39; which originated in node &#39;%5&#39;.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5155</td><td>Cluster Shared Volume resource &#39;%1&#39; completed processing request &#39;%2&#39; with sequence number &#39;%3&#39;. The slowest node was &#39;%4&#39;, which took %5 seconds.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5156</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%2&#39;) has entered a paused state because of &#39;%3&#39;. This error is encountered when the volsnap snapshots underlying the CSV volume are deleted outside of a user request. Possible causes of the snapshots getting deleted are lack of space in the volume for the snapshots to grow, or IO failure while trying to update the snapshot data. All I/O will temporarily be queued until the snapshot state is synchronized with volsnap.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5157</td><td>Cluster Shared Volume &#39;%1&#39; (&#39;%2&#39;) has entered a paused state because of &#39;%3&#39;. All I/O will temporarily be queued until a path to the volume is reestablished. This error is usually caused by an infrastructure failure. For example, losing connectivity to storage or the node owning the Cluster Shared Volume being removed from active cluster membership.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5200</td><td>Cluster service failed to create a cluster identity token for Cluster Shared Volumes. The error code was &#39;%1&#39;. Ensure the domain controller is accessible and check for connectivity issues. Until connection to the domain controller is recovered, some operations on this node against the Cluster Shared Volumes might fail.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5216</td><td>Software snapshot creation on Cluster Shared Volume &#39;%1&#39; (&#39;%2&#39;) failed with error %3. The resource must be online to support snapshot creation. Please check the state of the resource.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5217</td><td>Software snapshot creation on Cluster Shared Volume(s) (&#39;%1&#39;) with snapshot set id &#39;%2&#39; failed with error &#39;%3&#39;. Please check the state of the CSV resources and the system events of the resource owner nodes.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5218</td><td>Cluster physical disk resource &#39;%1&#39; deleted a software snapshot. The software snapshot on Cluster Shared Volume &#39;%2&#39; was deleted because it was older than &#39;%3&#39; day(s). The snapshot ID was &#39;%4&#39; and it was created from node &#39;%5&#39; at &#39;%6&#39;. It is expected that snapshots are deleted by a backup application after a backup job is completed.  This snapshot exceeded the time that is expected for a snapshot to exist. Verify with the backup application that backup jobs are completing successfully.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5219</td><td>Cluster service failed to register the Cluster Shared Volumes snapshot provider with the Volume Shadow Service (VSS). This may be due to the VSS service shutting down or may be a problem with the VSS service having a problem that causes it to not accept incoming requests. 

Error: %1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5220</td><td>Cluster Service detected the fault domain settings may not be configured optimally. The current settings could result in reduced storage resiliency. 

Current Resiliency Level: %1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5235</td><td>Task &#39;%1&#39; is successfully registered.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5237</td><td>Task &#39;%1&#39; is successfully changed.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5245</td><td>Task &#39;%1&#39; is successfully deleted.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5264</td><td>Physical Disk resource &#39;%1&#39; has been disconnected from this node.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5265</td><td>Cluster network &#39;%1&#39; is down because the network interfaces connected to it are not operational. Cluster network &#39;%1&#39; is configured such that cluster communication is not allowed; however, if this failure is unexpected, run the Validate a Configuration wizard to check your network configuration. If the condition persists, check for hardware or software errors related to the network adapter. Also check for failures in any other network components to which the node is connected such as hubs, switches, or bridges.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5266</td><td>Cluster network interface &#39;%1&#39; for cluster node &#39;%2&#39; on network &#39;%3&#39; is not operational. Network &#39;%3&#39; is configured such that cluster communication is not allowed; however, if this failure is unexpected, run the Validate a Configuration wizard to check your network configuration. If the condition persists, check for hardware or software errors related to the network adapter. Also check for failures in any other network components to which the node is connected such as hubs, switches, or bridges.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5377</td><td>An internal Cluster service operation exceeded the defined threshold of &#39;%2&#39; seconds. The Cluster service has been terminated to recover. Service Control Manager will restart the Cluster service and the node will rejoin the cluster.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5393</td><td>The Cluster detected that this node is slower than others and degrade Cluster performance. If the condition persists, check for hardware or software errors related to this node. To avoid repeated events it is supress for 24 hours unless the Cluster service is restarted.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5394</td><td>The Cluster service encountered some storage errors while trying to bring storage pool online. Run cluster storage validation to troubleshoot the issue.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5395</td><td>Cluster is moving the group for storage pool &#39;%1&#39; because current node &#39;%3&#39; does not have optimal connectivity to the storage pool physical disks.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5396</td><td>The Cluster service on this node is shutting down because it has detected that there are other cluster nodes that have quorum. This occurs when the Cluster service detects another node that was started with the Force Quorum switch (/fq).  The node which was started with the Force Quorum Switch will remain running.  Use Failover Cluster Manager to verify that this node automatically joined the cluster when the cluster service restarted.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5397</td><td>The cluster resource &#39;%1&#39; could not create or modify the replicated local user account &#39;%2&#39; on this node. Check the cluster logs for more information.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5398</td><td>Cluster failed to start. The latest copy of cluster configuration data was not available within the set of nodes attempting to start the cluster. Changes to the cluster occurred while the set of nodes were not in membership and as a result were not able to receive configuration data updates. .

Votes required to start cluster: %1
Votes available: %2
Nodes with votes: %3

Guidance:
Attempt to start the cluster service on all nodes in the cluster so that nodes with the latest copy of the cluster configuration data can first form the cluster. The cluster will be able to start and the nodes will automatically obtain the updated cluster configuration data. If there are no nodes available with the latest copy of the cluster configuration data, run the &#39;Start-ClusterNode -FQ&#39; Windows PowerShell cmdlet. Using the ForceQuorum (FQ) parameter will start the cluster service and mark this node&#39;s copy of the cluster configuration data to be authoritative.  Forcing quorum on a node with an outdated copy of the cluster database may result in cluster configuration changes that occurred while the node was not participating in the cluster to be lost.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5399</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5400</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5401</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5408</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5409</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5410</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5411</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>5412</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>43968</td><td>Volume %1 activating</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>43969</td><td>Volume %1 deactivating</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>43970</td><td>IO %1 is of type %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>43971</td><td>IO %1 now in state %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>43972</td><td>fsContext %1 opened for file %3</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>43973</td><td>fsContext %1 closed</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering</td><td>43974</td><td>fsContext %1 is in state %2</td></tr>
</table>
