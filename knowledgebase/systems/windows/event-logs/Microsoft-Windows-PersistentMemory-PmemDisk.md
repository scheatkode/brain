# Microsoft-Windows-PersistentMemory-PmemDisk

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>1</td><td>Reported memory resource.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>2</td><td>Memory operation duration, in hundreds of nanoseconds.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>3</td><td>Request servicing time taken by lower driver stack(s).</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>101</td><td>Dispatching a read request.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>102</td><td>Dispatching a write request.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>103</td><td>Dispatching a read request.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>104</td><td>Dispatching a write request.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>105</td><td>Completing an IO (read/write) request.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>106</td><td>Dispatching an IOCTL.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>107</td><td>Completing a non-read/write request.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>108</td><td>Dispatching a PnP request.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>109</td><td>Completing a PnP request.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>202</td><td>Persistent memory disk %1 failed to start.                    
Reason: %5                    
NTSTATUS code: %6</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>203</td><td>Persistent memory disk %1 started successfully.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>204</td><td>One of the NVDIMMs that make up persistent memory disk %1 encountered an error while transferring your data to or from persistent media (see the Details tab for more information). Some of your data may have been lost. As a precaution, this persistent memory disk is now in read-only mode. If you want to keep using it, run the Reset-PhysicalDisk command to make it writeable again.                    
                    
Look at the events logged by the physical NVDIMM driver for more details.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>205</td><td>During a previous boot session, one of the NVDIMMs that make up persistent memory disk %1 encountered an error while transferring your data to or from persistent media. Some of your data may have been lost then. As a precaution, Windows made this persistent memory disk temporarily read-only. If you want to keep using this persistent memory disk, use the Reset-PhysicalDisk command to make it writeable again.                    
                    
Look at the events logged by the physical NVDIMM driver for more details.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>206</td><td>NVDIMM %5 notified persistent memory disk %1 of a change in its health state. The NVDIMM now has the following health status: %7.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>207</td><td>One of the NVDIMMs that make up the persistent memory disk %1 encountered a serious problem and the disk is now in read-only mode. Data that was saved to this disk may be lost when the computer shuts down or restarts. Consider backing up your data to another disk.                    
                    
Use the Get-PhysicalDisk command to get more information about the disk&#39;s health status.                    
Look at the events logged by the physical NVDIMM driver for more details.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>209</td><td>The computer didn&#39;t assign any memory resources to persistent memory disk %1. You won&#39;t be able to access the data on the device, but you can still query its health status by using the Get-PhysicalDisk command.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>210</td><td>Some physical memory locations on persistent memory disk %1 are corrupt. In order to protect your computer, Windows will not access those locations and you may see failures trying to read or write to your data. Contact your hardware vendor to learn what recovery steps are available.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>211</td><td>The problem with the persistent memory disk %1 was resolved and it is now back in read-write mode.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>212</td><td>One of the NVDIMMs that make up the persistent memory disk %1 is in a degraded health state and may soon encounter serious problems. Consider backing up your data to another disk.                    
                    
Look at the events logged by the physical NVDIMM driver for more details.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>213</td><td>The physical devices that make up persistent memory disk %1 have an atomicity setting that is incompatible with the data on the disk. Windows didn&#39;t start the disk to prevent data loss.             
             
This type of problem can happen when you update your computer&#39;s firmware, or when you upgrade from a version of Windows that doesn&#39;t look at atomicity settings to one that does.             
             
To recover the disk, follow these steps:             
1. Open the registry editor (regedit) and navigate to &#39;Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum\ACPI\ACPI0012\&lt;instance ID&gt;\Device Parameters&#39;. There will only be one instance ID key.             
2. Create a registry key named &#39;ScmBus&#39;. Inside it, create a new DWORD value named &#39;IgnoreLabels&#39; and set it to 1.             
3. Restart your computer.             
4. When Windows starts again, your persistent memory disks will be accessible. Back up **all the data** on **all of them** to a different disk. NOTE: these recovery steps will clear all persistent memory disks, even the ones that aren&#39;t affected by this problem, so it&#39;s important to back up all your data.             
5. Open the registry editor, navigate to the &#39;IgnoreLabels&#39; value you created and set it to 0.             
6. Restart your computer.             
7. The persistent memory disk will be inaccessible again. To use it, you will have to reinitialize all physical persistent memory devices on the system. Open an elevated PowerShell window and run &#39;Get-PmemPhysicalDevice | Initialize-PmemPhysicalDevice&#39;.             
8. The last step is to recreate the persistent memory disks. You can do that in the elevated PowerShell window by running &#39;Get-PmemUnusedRegion | New-PmemDisk&#39;. Look at the help content for &#39;New-PmemDisk&#39; to learn how to specify the disks&#39; atomicity modes.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>214</td><td>The persistent memory disk %1 is inaccessible because at least one of its NVDIMMs are locked. Contact your hardware vendor for instructions on how to unlock the NVDIMMs.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>215</td><td>The driver for persistent memory disk %1 encountered an internal error. The information in the Details tab might help Microsoft or your platform vendor to diagnose the problem.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>300</td><td>Persistent memory disk %1 is now in read-only mode.  Use the Get-PhysicalDisk command to get the device’s health status.  The Microsoft-Windows-PersistentMemory-PmemDisk/Operational event log may also contain more information.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>301</td><td>Persistent memory disk %1 is no longer in read-only mode.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>302</td><td>Windows does not support this configuration: two or more NVDIMMs on this system are part of an interleaved set. Back up the data on the interleaved set to a different drive and then break up the interleaved set. Consider using Storage Spaces if NVDIMM capacity needs to be aggregated.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-PmemDisk</td><td>900</td><td>Persistent memory disk %1 logged:             
             
 %2</td></tr>
</table>
