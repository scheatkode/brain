# Microsoft-Windows-PersistentMemory-Nvdimm

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>201</td><td>NVDIMM %1 failed to start. %3</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>202</td><td>NVDIMM %1 started successfully.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>203</td><td>NVDIMM %1 encountered an error that may have caused data loss.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>205</td><td>The driver could not confirm that the NVDIMM %1 is healthy. Consider backing up your data to another disk.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>206</td><td>NVDIMM %1 encountered an error while transferring your data to or from persistent media (see the Details tab for more information). Some of your data may have been lost.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.                    
                    
This NVDIMM may need to be replaced. It can be located using the following information:                    
                    
Slot number: %3                    
Manufacturer: %4                    
Model Number: %5                    
Serial Number: %6                    
Location: %7</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>207</td><td>NVDIMM %1 encountered an error that makes it unable to save your data if your computer shuts down. Consider backing up your data to another disk.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.                    
                    
This NVDIMM may need to be replaced. It can be located using the following information:                    
                    
Slot number: %3                    
Manufacturer: %4                    
Model Number: %5                    
Serial Number: %6                    
Location: %7</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>300</td><td>NVDIMM-N %1 encountered a serious problem that may cause data saved to this NVDIMM-N to be lost when the computer shuts down or restarts. Consider backing up your data to another disk.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.                    
                    
This NVDIMM-N may need to be replaced. It can be located using the following information:                    
                    
Slot number: %3                    
Manufacturer: %4                    
Model Number: %5                    
Serial Number: %6                    
Location: %7</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>301</td><td>The problem with NVDIMM-N %1 was resolved. Data saved to this NVDIMM-N is no longer at risk.                    
                    
This NVDIMM-N may be located using the following information:                    
                    
Slot number: %3                    
Manufacturer: %4                    
Model Number: %5                    
Serial Number: %6                    
Location: %7</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>302</td><td>NVDIMM-N %1 is in a degraded health state and may soon encounter serious problems. Consider backing up your data to another disk.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.                    
                    
This NVDIMM-N may need to be replaced. It can be located using the following information:                    
                    
Slot number: %3                    
Manufacturer: %4                    
Model Number: %5                    
Serial Number: %6                    
Location: %7</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>303</td><td>NVDIMM-N %1 has encountered %7 uncorrectable memory error(s). Uncorrectable memory errors can cause system instability and data loss. Consider replacing this NVDIMM-N.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.                    
                    
This NVDIMM-N can be located using the following information:                    
                    
Slot number: %3                    
Manufacturer: %4                    
Model Number: %5                    
Serial Number: %6                    
Location: %7</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>304</td><td>The warning threshold for correctable memory errors on NVDIMM-N %1 has been exceeded. A large number of correctable memory errors increases the likelihood of an uncorrectable memory error in the future and reduces system performance. Contact your hardware vendor to determine if this NVDIMM-N needs to be replaced.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.                    
                    
This NVDIMM-N can be located using the following information:                    
                    
Slot number: %3                    
Manufacturer: %4                    
Model Number: %5                    
Serial Number: %6                    
Location: %7</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>305</td><td>NVDIMM %1 notified the driver that its health state changed. See the Details tab for more information.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>306</td><td>The driver for NVDIMM %1 encountered an internal error. The information in the Details tab might help Microsoft or your platform vendor to diagnose the problem.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>400</td><td>NVDIMM %1 encountered a serious problem. All data that was saved to this NVDIMM may be lost when the computer shuts down or restarts. Consider backing up your data to another disk.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>401</td><td>The problem with NVDIMM %1 was resolved. Data that was saved to this NVDIMM will not be lost when the computer shuts down or restarts.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>402</td><td>NVDIMM %1 encountered a serious problem. Data that was recently saved to this NVDIMM may be lost when the computer shuts down or restarts. Consider backing up your data to another disk.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>403</td><td>The problem with NVDIMM %1 was resolved. Data that was saved to this NVDIMM will not be lost when the computer shuts down or restarts.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>404</td><td>NVDIMM %1 encountered a critical problem. Windows may not be able to read or write to this NVDIMM.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>405</td><td>The critical problem with NVDIMM %1 was resolved.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>406</td><td>NVDIMM %1 is in a degraded health state and may soon encounter serious problems. Consider backing up your data to another disk.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>407</td><td>NVDIMM %1 notified the driver that its health state changed. See the Details tab for more information.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>501</td><td>NVDIMM %1 notified the driver that its health state changed. See the Details tab for more information.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>502</td><td>NVDIMM %1 is in a critically unhealthy state and your data may be lost. Consider backing up your data to another disk.                   
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>503</td><td>NVDIMM %1 is in a critically degraded state and may need to be replaced soon. Consider backing up your data to another disk.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>504</td><td>NVDIMM %1&#39;s temperature is too high. To protect itself, the NVDIMM might be running slower than usual. If the temperature does not decrease, the system might shut down and some of your data may be lost.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>505</td><td>NVDIMM %1 is in a degraded state and may need to be replaced soon. Consider backing up your data to another disk.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>506</td><td>NVDIMM %1 is now healthy again.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>507</td><td>The energy source protecting NVDIMM %1 stopped working. The data saved to this NVDIMM may be lost when the computer shuts down or restarts. Consider backing up your data to another disk.                    
                    
In PowerShell, run Get-PmemPhysicalDevice for more information and Get-PmemDisk to see which disks are affected by this problem.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>508</td><td>The energy source protecting NVDIMM %1 is working again. The data saved to this NVDIMM is no longer at risk.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>509</td><td>NVDIMM %1 is locked and you won&#39;t be able to access its contents. Contact your platform vendor to learn how you can unlock the NVDIMM.</td></tr>
<tr><td>Microsoft-Windows-PersistentMemory-Nvdimm</td><td>900</td><td>NVDIMM %1 logged:             
             
 %2</td></tr>
</table>
