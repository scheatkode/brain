# Microsoft-Windows-StorageSpaces-Driver

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>102</td><td>Majority of the physical disks of storage pool %1 failed a configuration update, which caused the pool to go into a failed state. Return Code: %2</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>103</td><td>The capacity consumption of the storage pool %1 has exceeded the threshold limit set on the pool. Return Code: %2</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>104</td><td>The capacity consumption of the storage pool %1 is now below the threshold limit set on the pool. Return Code: %2</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>200</td><td>Windows was unable to read the disk header for physical disk %1. If you know the disk is still usable, then resetting the disk health by using command line or GUI may clear this failure condition and enable you to reassign the disk to its storage pool. Return Code: %2</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>202</td><td>Physical disk %1 has invalid meta-data. Resetting the health status, using command line or GUI, might resolve the issue. Return Code: %2</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>203</td><td>Physical disk %1 failed an IO operation. Return Code: %2. Additional related events may be found in the System event log for Disk %3.                  
                  
This disk may need to be replaced. To view its reliability counters, run this command in PowerShell:                  
Get-PhysicalDisk | ?{ $_.ObjectId -Match &quot;%1&quot; } | Get-StorageReliabilityCounter                  
                  
This disk may be located using the following information:                  
                  
Drive Manufacturer: %4                  
Drive Model Number: %5                  
Drive Serial Number: %6                  
                  
More information can be obtained using this PowerShell command:                  
Get-PhysicalDisk | ?{ $_.ObjectId -Match &quot;%1&quot; }                  
                  
If this disk is in an enclosure, it may be located using the following information:                  
                  
Enclosure Manufacturer: %7                  
Enclosure Model Number: %8                  
Enclosure Serial Number: %9                  
Enclosure Slot: %10                  
                  
It may also be located by running this command in PowerShell:                  
Get-PhysicalDisk | ?{ $_.ObjectId -Match &quot;%1&quot; } | Enable-PhysicalDiskIndication</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>204</td><td>Physical disk %1 is reporting an impending failure. Sense Code (KEY ASC/ASCQ): %2 %3/%4. Additional related events may be found in the System event log for Disk %5.                  
                  
This disk may need to be replaced. To view its reliability counters, run this command in PowerShell:                  
Get-PhysicalDisk | ?{ $_.ObjectId -Match &quot;%1&quot; } | Get-StorageReliabilityCounter                  
                  
This disk may be located using the following information:                  
                  
Drive Manufacturer: %6                  
Drive Model Number: %7                  
Drive Serial Number: %8                  
                  
More information can be obtained using this PowerShell command:                  
Get-PhysicalDisk | ?{ $_.ObjectId -Match &quot;%1&quot; }                  
                  
If this disk is in an enclosure, it may be located using the following information:                  
                  
Enclosure Manufacturer: %9                  
Enclosure Model Number: %10                  
Enclosure Serial Number: %11                  
Enclosure Slot: %12                  
                  
It may also be located by running this command in PowerShell:                  
Get-PhysicalDisk | ?{ $_.ObjectId -Match &quot;%1&quot; } | Enable-PhysicalDiskIndication</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>205</td><td>Windows lost communication with physical disk %1. This can occur if a cable failed or was disconnected, or if the disk itself failed.                  
                  
This disk may be located using the following information:                  
                  
Drive Manufacturer: %2                  
Drive Model Number: %3                  
Drive Serial Number: %4                  
                  
If this disk is in an enclosure, it may be located using the following information:                  
                  
Enclosure Manufacturer: %5                  
Enclosure Model Number: %6                  
Enclosure Serial Number: %7                  
Enclosure Slot: %8                  
                  
More information can be obtained using this PowerShell command:                  
Get-PhysicalDisk | ?{ $_.ObjectId -Match &quot;%1&quot; }                  
                  
To view the virtual disks affected, run this command in PowerShell:                  
Get-PhysicalDisk | ?{ $_.ObjectId -Match &quot;%1&quot; } | Get-VirtualDisk</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>206</td><td>Physical disk %1 was auto-retired.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>207</td><td>Physical disk %1 arrived.                  
Pool Id: %2                  
Drive Number: %3                  
Drive Manufacturer: %4                  
Drive Model Number: %5                  
Drive Serial Number: %6</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>208</td><td>Physical disk %2 failed while arriving. Return Code: %1.                  
Pool Id: %3                  
Drive Number: %4                  
Drive Manufacturer: %5                  
Drive Model Number: %6                  
Drive Serial Number: %7</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>300</td><td>Physical disk %1 failed to read the configuration or returned corrupt data for virtual disk %2. As a result the in-memory configuration may not be the most recent copy of configuration. Return Code: %3</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>301</td><td>All pool disks failed to read the configuration or returned corrupt data for virtual disk %1. As a result the virtual disk will not attach. Return Code: %2</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>302</td><td>Majority of the pool disks hosting space meta-data for virtual disk %1 failed a space meta-data update, which caused the storage pool to go in failed state. Return Code: %2</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>303</td><td>Drives hosting data for virtual disk %1 have failed or are missing. As a result, no copy of data is available at offset %3.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>304</td><td>The virtual disk %1 is in a degraded state. This can happen when a physical disk hosting the virtual disk fails, is disconnected, or experiences a write error.                  
                  
Windows will attempt to repair the virtual disk. No action is needed at this time.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>305</td><td>Virtual disk %1 is now healthy.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>306</td><td>The attempt to map, or allocate more storage for, the virtual disk %1 has failed. This is because there was a write failure involved in the updating the virtual disk metadata. Return Code: %2</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>307</td><td>The attempt to unmap or trim the virtual disk %1 has failed. Return Code: %2</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>309</td><td>Virtual disk %1 was detached due to an unexpected error. Return Code: %2</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>310</td><td>The attempt to allocate more storage for the virtual disk %1 has failed.                  
                  
Check the available capacity of the virutual disk; you may need to add additional                  
physical capacity to the pool.                  
                  
Once you have resolved the condition listed above,                  
you can online the disk by using the following commands in PowerShell:                  
                  
Get-VirtualDisk | ?{ $_.ObjectId -Match &quot;%1&quot; } | Get-Disk | Set-Disk -IsReadOnly $false                  
Get-VirtualDisk | ?{ $_.ObjectId -Match &quot;%1&quot; } | Get-Disk | Set-Disk -IsOffline  $false</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>311</td><td>Virtual disk %1 requires a data integrity scan.                  
                  
Data on the disk is out-of-sync and a data integrity scan is required.                  
To start the scan, run the following command:                  
                  
Get-ScheduledTask -TaskName &quot;Data Integrity Scan for Crash Recovery&quot; | Start-ScheduledTask                  
                  
Once you have resolved the condition listed above,                  
you can online the disk by using the following commands in PowerShell:                  
                  
Get-VirtualDisk | ?{ $_.ObjectId -Match &quot;%1&quot; } | Get-Disk | Set-Disk -IsReadOnly $false                  
Get-VirtualDisk | ?{ $_.ObjectId -Match &quot;%1&quot; } | Get-Disk | Set-Disk -IsOffline  $false</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>312</td><td>Virtual disk %1 has failed a write operation to all its copies.                  
                  
You can online the disk by using the following commands in PowerShell:                  
                  
Get-VirtualDisk | ?{ $_.ObjectId -Match &quot;%1&quot; } | Get-Disk | Set-Disk -IsReadOnly $false                  
Get-VirtualDisk | ?{ $_.ObjectId -Match &quot;%1&quot; } | Get-Disk | Set-Disk -IsOffline  $false</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>313</td><td>Virtual disk %1 could not be repaired because there is not enough free space in the storage pool.                  
                  
Replace any failed or disconnected physical disks. The virtual disk will then be repaired automatically or you can repair it by running this command in PowerShell:                  
Get-VirtualDisk | ?{ $_.ObjectId -Match &quot;%1&quot; } | Repair-VirtualDisk</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>400</td><td>A path to storage enclosure %1 has been detected. The number of available paths is %2.                  
This enclosure may be located using the following information:                  
                  
Manufacturer: %3                  
Model Number: %4                  
Serial Number: %5                  
Firmware Version: %6                  
                  
It may also be located by running this command in PowerShell:                  
Get-StorageEnclosure | ?{ $_.ObjectId -Match &quot;%1&quot; }</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>401</td><td>A path to storage enclosure %1 has been removed. The number of remaining paths is %2.                  
This enclosure may be located using the following information:                  
                  
Manufacturer: %3                  
Model Number: %4                  
Serial Number: %5                  
Firmware Version: %6</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>402</td><td>The health of storage enclosure %1 has changed from %2 to %3.                  
This enclosure may be located using the following information:                  
                  
Manufacturer: %4                  
Model Number: %5                  
Serial Number: %6                  
Firmware Version: %7                  
                  
It may also be located by running this command in PowerShell:                  
Get-StorageEnclosure | ?{ $_.ObjectId -Match &quot;%1&quot; }</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>403</td><td>A storage enclosure failed to initialize. Return Code: %1.                  
This enclosure may be located using the following information:                  
                  
Manufacturer: %2                  
Model Number: %3                  
Serial Number: %4                  
Firmware Version: %5</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1000</td><td>Space %1 failed to initialize at %2:%3 with status %4.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1001</td><td>Pool %1 is beginning transaction %2 at sequence number %3.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1002</td><td>Pool %1 completed transaction %2 with status %3 at sequence number %4.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1003</td><td>Space %1 is beginning transaction %2 at sequence number %3.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1004</td><td>Space %1 completed transaction %2 with status %3 at sequence number %4.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1005</td><td>IOCTL %1 started.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1006</td><td>IOCTL %1 completed with status %2.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1007</td><td>Space %1 reallocated %2 extents. NeedCapacity: %3.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1008</td><td>Space %1 has started to regenerate.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1009</td><td>Space %1 has completed regenerating. %2 bytes processed.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1010</td><td>Space %1 failed to regenerate at offset %2, length %3.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1011</td><td>Request to update metadata drives for config %1.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1012</td><td>Updated metadata drives for config %1.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1013</td><td>Space %1 was unable to reallocate at offset %2.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1017</td><td>Waited %1 ms to acquire the global lock.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1018</td><td>Held the global lock for %1 ms.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1019</td><td>Log scan for space %1 log %2 copy %3 completed at offset %4 with status %5.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1020</td><td>IO summary for enclosure %1. See details for additional information.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1021</td><td>Space %1 attached at %2 taking %3 us.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1022</td><td>Space %1 in pool %2 detached with reason %5 and status %6. This space was attached for %3 us and took %4 us to detach.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1023</td><td>Space %1 attached with %2 entries in the DRT. Scrub is required to remove these entries.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1024</td><td>Space %1 attached with no entries in the DRT. No scrub is needed.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1025</td><td>All clean entries in the DRT for space %1 have been removed.  Current entries: %2. Flush status: %3. Write statuses: %4 %5.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1026</td><td>Log advance failed for space %1, log %2, operation %3 with status %4.  Writes to this space may fail as a result.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1027</td><td>Space %1 in pool %2 repair summary. See details for more information.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1029</td><td>Space %2 in pool %1 failed to attach for reason %5 with status %6.  This space attempted attaching for %3 us and took %4 us to detach.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1030</td><td>Space %1 failed to destage on operation %2 with status %3. Writes to this space may fail as a result.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1100</td><td>Config %1 loaded at sequence %4 with %3 paths present out of %2 total and path %5 as the primary.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1101</td><td>Config %1 failed to load with status %2.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1102</td><td>Path %2 arrived for config %1 with flags: %3.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1103</td><td>Path %2 removed from config %1.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1104</td><td>Path %2 in config %1 synchronized.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1105</td><td>Path %2 in config %1 failed to synchronize with status %3.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1106</td><td>Path %2 in config %1 failed an IO with status %3.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1107</td><td>Config %1 failed to commit a transaction at sequence %4 with status %5. %3 paths out of %2 are present. Witness status: %6.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>1108</td><td>Config %1 is inquorate. %3 paths out of %2 are present. Current sequence is %4 and witness sequence is %6. Witness status: %5.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2000</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2001</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2002</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2003</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2004</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2005</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2006</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2007</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2008</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2009</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2010</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2011</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2100</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2101</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2102</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2103</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2104</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2200</td><td>For internal use.</td></tr>
<tr><td>Microsoft-Windows-StorageSpaces-Driver</td><td>2300</td><td>Read cache operation completed.                  
Id: %1                  
Operation/Function: %2                  
Length: %3                  
Disk Offset: %4                  
Relative Offset: %5                  
Cache Offset: %6                  
Status: %7</td></tr>
</table>
