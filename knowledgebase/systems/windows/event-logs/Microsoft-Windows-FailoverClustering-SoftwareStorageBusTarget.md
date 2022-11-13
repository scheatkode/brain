# Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>101</td><td>Storage Spaces Direct has successfully provisioned a disk for the cache.

Cache mode: %11

Disk GUID: %1
Disk number: %2
Manufacturer: %3
Product ID: %4
Serial: %5

Enclosure location:
Enclosure slot: %6
Enclosure manufacturer: %7
Enclosure product ID: %8
Enclosure serial: %9</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>102</td><td>Storage Spaces Direct cannot provision a disk for the cache due to an error.

Error: %14
Stage: %13

Disk GUID: %1
Disk number: %2
Manufacturer: %3
Product ID: %4
Serial: %5

Enclosure location:
Enclosure slot: %6
Enclosure manufacturer: %7
Enclosure product ID: %8
Enclosure serial: %9

Cache mode: %11

Guidance:
The most recent error code is listed above. Any prior errors about provisioning the disk are in the event details. The disk has been removed from Storage Spaces Direct. Check to ensure that cabling to your storage devices is fully seated and intact. Ensure that the disk is still present and is healthy, and that you have the latest drivers and firmware for the device and the storage controller.

To find the disk in PowerShell, use the following commands:
Get-PhysicalDisk |? ObjectId -Match &quot;%1&quot;
Get-PhysicalDisk -SerialNumber %5
Get-Disk -Number %2</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>110</td><td>Storage Spaces Direct found a disk that cannot be used for the cache because data partitions already exist on the disk.

Disk GUID: %1
Disk number: %2
Manufacturer: %3
Product ID: %4
Serial: %5

Enclosure location:
Enclosure slot: %6
Enclosure manufacturer: %7
Enclosure product ID: %8
Enclosure serial: %9

Cache mode: %11

Guidance:
To use the disk for Storage Spaces Direct, you must delete all data partitions off of the disk.
To see which partitions are on the disk, run the following PowerShell cmdlet:
Get-Disk -Number %2 | Get-Partition

To delete all data partitions on the disk, run the following PowerShell cmdlet:
Set-Disk -Number %2 -IsOffline $false
Set-Disk -Number %2 -IsReadOnly $false
Clear-Disk -Number %2 –RemoveData -RemoveOEM</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>111</td><td>Storage Spaces Direct found a disk that cannot be used for the cache because the disk is not initialized as a GPT disk.

Disk GUID: %1
Disk number: %2
Manufacturer: %3
Product ID: %4
Serial: %5

Enclosure location:
Enclosure slot: %6
Enclosure manufacturer: %7
Enclosure product ID: %8
Enclosure serial: %9

Cache mode: %11

Guidance:
To use the disk for Storage Spaces Direct, you must initialize the disk as a GPT disk. First, ensure that the disk does contain any data that you want to save, then clear the disk using the following instructions.

To clear the disk:
Set-Disk -Number %2 -IsOffline $false
Set-Disk -Number %2 -IsReadOnly $false
Clear-Disk -Number %2 –RemoveData -RemoveOEM</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>112</td><td>Storage Spaces Direct found a disk that cannot be used for the cache because it has insufficient disk space for the reserved metadata portion.

Configured reserved bytes: %12

Disk GUID: %1
Disk number: %2
Manufacturer: %3
Product ID: %4
Serial: %5

Enclosure location:
Enclosure slot: %6
Enclosure manufacturer: %7
Enclosure product ID: %8
Enclosure serial: %9

Cache mode: %11

Guidance:
To use the disk for Storage Spaces Direct, you must reduce the amount of metadata reserve bytes.
To reduce the metadata reserve bytes, run the following PowerShell command:
(Get-Cluster).S2DMetadataReserveBytes = (%12 / 2)</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>113</td><td>Storage Spaces Direct found a disk that cannot be used for the cache due to an unexpected error.

Disk GUID: %1
Disk number: %2
Manufacturer: %3
Product ID: %4
Serial: %5

Enclosure location:
Enclosure slot: %6
Enclosure manufacturer: %7
Enclosure product ID: %8
Enclosure serial: %9

Cache mode: %11

Guidance:
Check to ensure that cabling to your storage devices is fully seated and intact. Ensure that the disk is still present and is healthy, and that you have the latest drivers and firmware for the device and the storage controller.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>201</td><td>Storage Spaces Direct is optimizing the cache. While the cache is being optimized, some IOs to this node will not be cached and you may notice a performance degradation. Event 203 will be logged when optimization is complete.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>202</td><td>Storage Spaces Direct has selected the following drive to be rebalanced during optimization. While the cache is being optimized, some IOs to this drive cannot be cached. Event 203 is logged when cache optimization is completed for all the drives.

Disk GUID: %1
Disk number: %2
Manufacturer: %3
Product ID: %4
Serial: %5

Enclosure location:
Enclosure slot: %6
Enclosure manufacturer: %7
Enclosure product ID: %8
Enclosure serial: %9

</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>203</td><td>Storage Spaces Direct has finished optimizing the cache.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>204</td><td>Storage Spaces Direct cannot optimize the cache on a device.

Disk GUID: %1
Disk number: %2
Manufacturer: %3
Product ID: %4
Serial: %5

Enclosure location:
Enclosure slot: %6
Enclosure manufacturer: %7
Enclosure product ID: %8
Enclosure serial: %9

Guidance:
This occurs when some of the disks on this computer are not in a healthy state. Wait for all the disks to reach a healthy state, and then try to optimize the cache again.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>301</td><td>Storage Spaces Direct found that a flash drive is missing. The following disk is associated with that flash drive will not be able to serve IO until the problem is corrected.

Disk GUID: %1
Disk number: %2
Manufacturer: %3
Product ID: %4
Serial: %5

Enclosure location:
Enclosure slot: %6
Enclosure manufacturer: %7
Enclosure product ID: %8
Enclosure serial: %9

Timeout (seconds): %11

Guidance:
Storage Spaces Direct will wait for the flash drive to reappear. When the device reappears, it results in event 302. If the device does not reappear within the timeout period that is listed above, Storage Spaces Direct will associate this affected hybrid disk with another flash drive. If the device does not reappear, it results in event 303.
Check to ensure that cabling to your storage devices is fully seated and intact. Ensure that the disk is still present and is healthy, and that you have the latest drivers and firmware for the device and the storage controller.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>302</td><td>A missing flash device has reappeared. This hybrid disk will resume serving IO.

Disk GUID: %1
Disk number: %2
Manufacturer: %3
Product ID: %4
Serial: %5

Enclosure location:
Enclosure slot: %6
Enclosure manufacturer: %7
Enclosure product ID: %8
Enclosure serial: %9

Guidance:
This is the culmination of the preceding event 301. No further action is necessary.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>303</td><td>Storage Spaces Direct has timed out waiting for a missing flash drive to reappear and will now bind this hybrid to a different flash drive.

Disk GUID: %1
Disk number: %2
Manufacturer: %3
Product ID: %4
Serial: %5

Enclosure location:
Enclosure slot: %6
Enclosure manufacturer: %7
Enclosure product ID: %8
Enclosure serial: %9

Guidance:
This is the culmination of the preceding event 301. No further action is necessary.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>304</td><td>Storage Spaces Direct has found that a flash device has failed to initialize.

Disk GUID: %1
Disk number: %2
Manufacturer: %3
Product ID: %4
Serial: %5

Enclosure location:
Enclosure slot: %6
Enclosure manufacturer: %7
Enclosure product ID: %8
Enclosure serial: %9

Status: %12

Guidance:
This flash could not initialize cache. Try Repair-ClusterStorageSpacesDirect to recover</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>305</td><td>Storage Spaces Direct has found that a disk has reached the media error threshold.

Disk GUID: %1
Disk number: %2
Manufacturer: %3
Product ID: %4
Serial: %5

Enclosure location:
Enclosure slot: %6
Enclosure manufacturer: %7
Enclosure product ID: %8
Enclosure serial: %9

Guidance:
If this is a flash device, Storage Spaces Direct will bind any hybrid disks associated with this flash device to another flash device. No further action is necessary.</td></tr>
<tr><td>Microsoft-Windows-FailoverClustering-SoftwareStorageBusTarget</td><td>401</td><td>The Storage Spaces Direct configuration has changed.

New configuration:

Cache state: %1
Cache metadata reserve bytes: %2
Cache behavior: %3

Old configuration:

Cache state %4
Cache metadata reserve bytes: %5
Cache behavior: %6</td></tr>
</table>
