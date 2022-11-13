# Microsoft-Windows-StorageReplica-Cluster

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>500</td><td>Storage Replica service is not installed.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>501</td><td>Storage Replica resource failed to open Service Control Manager to register for status change notifications.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>502</td><td>Storage Replica resource failed to register for service status change notifications.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>503</td><td>Storage Replica service is not running.

Guidance: The Storage Replica resource can be brought online only when the service is in the running state.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>504</td><td>Storage Replica cluster resource failed to read configuration from the metadata store.

Resource: %1
Status:%5</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>505</td><td>Storage Replica cluster resource is unable to detect disk resources connected to this node for the source replication group.

Resource: %1

Guidance: An attempt will now be made to choose a synchronous replication group that can take up the source role.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>506</td><td>Storage Replica cluster resource failed to persist the replication status of partner replication groups.

Resource: %1
PartnerReplicationGroupId: %5
ReplicationGroupInSync: %6
Status: %7</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>507</td><td>Storage Replica cluster resource failed to update possible owners.

Resource: %1
Status:%6
Possible owners: %5

Guidance: This can cause unexpected failover behavior. Resources should have the above possible owners.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>508</td><td>Storage Replica cluster resource could not find any replication group that can assume the source role on this cluster node.

Resource: %1

Guidance: Either the replication groups were not in the required synchronous state or some of the cluster disks were not connected to this node. Try moving the resource to a node where the disks are attached.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>509</td><td>Storage Replica cluster resource received a replication status change notification for one or more replication groups.

Resource: %1
Replication status: %5</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>510</td><td>Storage Replica cluster resource received a member status change notification for replication group.

Resource: %1
Replica state: %5</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>511</td><td>Storage Replica source cluster resource is not online.

Resource: %1

Guidance: The destination replication groups will periodically attempt to connect to source replication group.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>512</td><td>Storage Replica cluster resource is unable to detect disk resources connected to this node for this destination replication group.

Resource: %1</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>513</td><td>Storage Replica cluster resource has detected that the replication group is in suspended state and therefore cannot come online on any node.

Resource: %1</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>514</td><td>Storage Replica cluster resource has successfully updated possible owners based on storage and service availability.

Resource: %1
Possible owners: %5</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>515</td><td>Source Storage Replica cluster resource has succesfully completed recovery and has entered ready state.

Resource: %1</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>516</td><td>Storage Replica cluster resource failed to update possible owners.

Resource: %1
Status:%6
Possible owners list: %5

Guidance: This can cause unexpected failover behavior. Resource should have the above entries in the possible owners list but does not.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>517</td><td>Storage Replica cluster resource failed to update cluster disk unique identifier property. The source resource cannot come online unless this property can be updated successfully.

Resource: %1
Status:%5</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>518</td><td>Storage Replica cluster resource cannot be brought online as there is a source resource that represents the same replication group as this resource.

Resource: %1
Status:%5</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>519</td><td>Storage Replica cluster resource failed to come online.

Resource: %1
Status:%5</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>520</td><td>Storage Replica cluster resource is online.

Resource: %1</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>521</td><td>Storage Replica service has entered running state.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>522</td><td>Storage Replica cluster resource has detected incorrect resource dependency.

Resource 1: %5
Resource 2: %6

Guidance: The above cluster resource 1 must depend on resource 2, but does not.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>523</td><td>Storage Replica cluster resource has detected invalid resource group configuration.

Resource: %5
Cluster group: %6

Guidance: The above cluster resource must belong to the above resource group, but does not.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>524</td><td>Storage Replica cluster resource failed to bring destination resource offline.

Resource: %1
Status:%2</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>525</td><td>Storage Replica cluster resource failed to bring destination resource online.

Resource group: %1
Status:%2</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>526</td><td>Destination replication group is now disabled for automatic failover.

Resource: %1

Guidance: When the destination replication group achieves synchronous replication state, it will be enabled for automatic failover.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>527</td><td>Destination replication group is now enabled for automatic failover.

Resource: %1</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>528</td><td>The Network interface is not constrained. 

%Interface: %1
Status:%2

Guidance: An attempt was made to add the network interface to network constraint as it was part of the constrained network. Please make sure the specified network interface is Online in cluster.</td></tr>
<tr><td>Microsoft-Windows-StorageReplica-Cluster</td><td>529</td><td>Storage Replica cluster resource failed to grant permission for replication to a partner cluster. 

Resource: %1
PairedCluster:%3
Status:%4

Guidance: An attempt was made to pair a cluster account to this cluster&#39;s access control list. To resolve, run the following command:

 Grant-SrAccess.</td></tr>
</table>
