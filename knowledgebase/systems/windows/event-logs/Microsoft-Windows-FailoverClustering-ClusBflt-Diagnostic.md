# Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>1</td><td>Disk %1 has arrived</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>2</td><td>Disk %1 is claimed by clusbflt</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>3</td><td>Disk %1 is not claimed by clusbflt, Status %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>8</td><td>Disk %1 was removed</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>51</td><td>Enclosure arrived</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>52</td><td>Enclosure removed</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>101</td><td>Path %1 (attributes=%3, type=%4) was created for device %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>102</td><td>Path %1 (attributes=%3, type=%4) was removed for device %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>103</td><td>Path %1 (attributes=%3, down path=%4) was paused for device %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>104</td><td>Path %1 (attributes=%3, down path=%4) was resumed for device %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>105</td><td>Path %1 (attributes=%3, down path=%4) was resumed on timeout for device %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>151</td><td>Received request to update membership to %1, flags = %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>152</td><td>Completed request to update membership to %1, flags = %2, status %3</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>153</td><td>Completed request to set registration key to %1, status %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>154</td><td>Client cluster with Id %1 and instance id %2 registered.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>155</td><td>Client cluster with Id %1 and instance id %2 unregistered on client request.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>156</td><td>Client cluster with Id %1 and instance id %2 unregistered because no hearbeat was received for 1 minute.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>157</td><td>Received client cluster membership update from node id %1. Cluster Id %2, instance id %3, membership sequence %4, nodeset mask %5. Existing cluster id %6, instance id %7, membership sequence %8, nodeset mask %9</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>158</td><td>Applied client cluster membership update from node id %1. Cluster Id %2, instance id %3, membership sequence %4, nodeset mask %5.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>159</td><td>Target create for cluster node id %1 for path %2 with cluster Id %3, instance id %4. Existing cluster id %5, instance id %6. Status=%7</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>160</td><td>Target create request rejected from cluster node id %1 for path %2 with cluster Id %3, instance id %4. Existing cluster id %5, instance id %6.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>201</td><td>Node %1 connected to path %2 device %3</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>202</td><td>Node %1 disconnected from path %2 device %3</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>251</td><td>Remove all partitions from device %1 (%2), Status=%3.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>252</td><td>Trim device %1 (%2), Status=%3.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>253</td><td>Create Hdd Cache partition on device %1 (%2), Status=%3.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>254</td><td>Initialize Hdd Cache partition on device %1 (%2), Status=%3.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>255</td><td>Initialize Ssd Cache Store partition on device %1 (%2), PartitionId %3, Status=%4.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>256</td><td>Create Ssd Cache Store partition on device %1 (%2), Reserve %3 percent, UnusedSize %4, Status=%5.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>257</td><td>Bind Hdd device %1 (%2) to Cache Store Partition %3 on device %4 (%5), Attributes %6, Status=%7.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>258</td><td>UnBind Hdd device %1 (%2), Options %3, AddedMissingPages=%4, Status=%5.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>259</td><td>Disable Binding on Sdd device %1 (%2), Partition Id %3, Binding %4, Hdd Device %5, Status=%6.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>260</td><td>Set Binding Attributes on device %1 (%2), Partition Id %3, Binding %4, Hdd Device %5, Attributes(mask) %6(%7), Status=%8.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>261</td><td>Disabled Read and Write Cache on Ssd Cache Store partition on device %1 (%2), PartitionId %3 due to IO Error=%4.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>301</td><td>Runtime error in %1@%2, Status=%3.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>351</td><td>Starting to load Cache Store on device %1 (%2), PartitionId %3, Status=%4.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>352</td><td>Loaded Cache Store on device %1 (%2), PartitionId %3, Status=%4.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>353</td><td>Failed to load Cache Store on device %1 (%2), PartitionId %3, Status=%4.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>401</td><td>Data mismatch detected at bottom layer. Disk %2, io_offset=%3, io_length=%4, mismatch_offset=%5, mismatch_length=%6</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>402</td><td>Data mismatch detected at top layer. Disk %2, io_offset=%3, io_length=%4, mismatch_offset=%5, mismatch_length=%6</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>403</td><td>Data mismatch detected at standby. Disk %2, io_offset=%3, io_length=%4, mismatch_offset=%5, mismatch_length=%6</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>404</td><td>Bad IO completion at bottom layer. Disk %2, io_offset=%3, io_length=%4, status=%5, informational=%6</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>405</td><td>Bad IO completion at top layer. Disk %2, io_offset=%3, io_length=%4, status=%5, informational=%6</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>406</td><td>Overlapping IOs detected</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-ClusBflt-Diagnostic</td><td>407</td><td>Prohibited IOCTL was rejected. Disk %2, ioctl=%3</td></tr>
</table>
