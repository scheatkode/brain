# Microsoft-Windows-Ntfs

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>1</td><td>RundownStart</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>2</td><td>RundownComplete</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>3</td><td>RundownVolumeInformation VolumeId: %1, DeviceName: %3</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>4</td><td>The NTFS volume has been successfully mounted.

           Volume GUID: %4
           Volume Name: %6
           Volume Label: %8
           Device Name: %3
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>98</td><td>Volume %1 (%2) %3</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>100</td><td>NTFS global corruption action state is now %1.</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>139</td><td>The file system structure that maintains security information on volume %1 (%2) has grown excessively large and fragmented.  The structure has reached %3%% of its maximum fragmentation limit.  If the structure continues to grow and reaches this limit, it may not be possible to create new files on this volume.  It is strongly recommended that the volume be taken offline for preventative maintenance.</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>140</td><td>The system failed to flush data to the transaction log. Corruption may occur in VolumeId: %1, DeviceName: %2.
(%3)</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>141</td><td>An operation failed because the disk was full.

           Process: %5
           Free space in bytes: %7
           Total reserved space in bytes: %8
           Txf TotalAbortReservation space in bytes: %9
           Requested space in bytes: %10
           Page file size in bytes: %11
           Volume guid: %1
           Volume name: %3
           Is boot volume: %6

Your disk &#39;%3&#39; is full. Use disk cleanup to free up disk space by deleting unnecessary files. If this is a thinly provisioned volume the physical storage backing this volume may have been exhausted.
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>142</td><td>Summary of disk space usage, since last event:

           Lowest free space in bytes: %4
           Highest free space in bytes: %5
           Page file size in bytes: 0
           Volume guid: %1
           Volume name: %3
           Is boot volume: %6
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>143</td><td>Surprise removal of a persistent memory device with active DAX mappings. This might lead to data corruption.

           Volume GUID: %4
           Volume Name: %6
           Volume Label: %8

Guidance:
A reboot is required to clean up the DAX mappings.</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>144</td><td>A volume that already has DAX mappings is being mounted. This generally occurs after surprise removal. This might lead to data corruption.

           Volume GUID: %4
           Volume Name: %6

Guidance:
A reboot is required to clean up the DAX mappings.</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>145</td><td>IO latency summary common data for volume:

           Volume Id: %1
           Volume name: %3
           Is boot volume: %4

           Max Acceptable IO Latency: %5 ms
           Read/Write latency buckets (ns): [%6, %7, %8, %9, %10, %11, %12]
           Trim latency buckets (ns): [%13, %14, %15, %16, %17, %18, %19]
           Flush latency buckets (ns): [%20, %21, %22, %23, %24, %25, %26]
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>146</td><td>IO latency summary:

           Volume Id: %1
           Volume name: %3
           Is boot volume: %4

           Interval duration: %6 us

           Non-cached reads:
                     IO count: %7
                     Total bytes: %8
                     Avg latency: %9 ns

           Non-cached writes: 
                     IO count: %10
                     Total bytes: %11
                     Avg latency: %12 ns

           File flushes: 
                     IO count: %13
                     Avg latency: %14 ns

           Volume flushes: 
                     IO count: %15
                     Avg latency: %16 ns

           File level trims: 
                     IO count: %17
                     Total bytes: %18
                     Extents count: %19
                     Avg latency: %20 ns

           Volume trims: 
                     IO count: %21
                     Total bytes: %22
                     Extents count: %23
                     Avg latency: %24 ns

 For more details see the details tab.
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>147</td><td>An IO took more than %5 ms to complete:

           Process Id: %6
           Process name: %7
           File name: %9
           File offset: %12
           IO Type: %10
           IO Size: %11 bytes
           %15 cluster(s) starting at cluster %14
           Latency: %13 ms

           Volume Id: %1
           Volume name: %3
           Is boot volume: %4
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>148</td><td>A %9 failed with %14.
This may indicate a failing disk.

           Process Id: %5
           Process name: %6
           File name: %8
           IO Size: %10 bytes
           File offset: %11
           %13 cluster(s) starting at cluster %12

           Volume Id: %1
           Volume name: %3
           Is boot volume: %4
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>149</td><td>In the past %5 seconds we had IO failures.
This may indicate a failing disk.

           High latency IO count: %6
           Failed writes: %7
           Failed reads: %8
           Bad clusters relocated: %9

           Volume Id: %1
           Volume name: %3
           Is boot volume: %4
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>150</td><td>An IO failed with %12 and NTFS has relocated the clusters. The original clusters are now marked as bad and they will not be reused.
This may indicate a failing disk.

           Process Id: %5
           Process name: %6
           File name: %8
           File offset: %9
           %11 cluster(s) were marked as bad starting at cluster %10

           Volume guid: %1
           Volume name: %3
           Is boot volume: %4
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>201</td><td>NtfsLogFileFull VolumeId: %1, Reason: %2</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>202</td><td>PeriodicCheckpointStart VolumeId: %1, Reason: %2, Usage: %3%</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>203</td><td>PeriodicCheckpointComplete VolumeId: %1, DirtyMetaDataPages: %2</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>204</td><td>CleanCheckpointStart VolumeId: %1, Reason: %2, Usage: %3%</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>205</td><td>CleanCheckpointComplete VolumeId: %1, DirtyMetaDataPages: %2</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>206</td><td>MftRecordRead VolumeId: %1, BaseFileId: %2, FileId: %3, CacheHit: %4</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>208</td><td>MftRecordRead VolumeId: %1, BaseFileId: %2, FileId: %3</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>210</td><td>Thinly provisioned volume %1 (%2)
were not being mapped between clusters %3 and %4.
It is now fixed.</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>211</td><td>Thinly provisioned volume %1 (%2)
were not being mapped between clusters %3 and %4.
Repair was unsucccessful.
Possibly out of available slabs.</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>230</td><td>WorkItem queued, WorkItem: %1, Reason: %2</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>231</td><td>WorkItem queue failed, WorkItem: %1, Reason: %2, Error: %3</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>232</td><td>WorkItem started, WorkItem: %1, Reason: %2</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>233</td><td>WorkItem completed, WorkItem: %1, Reason: %2</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>240</td><td>File metadata optimization started.

                    Volume guid: %1
                    Volume name: %3
                    File reference: %4
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>241</td><td>File metadata optimization completed.

                    Volume guid: %1
                    Volume name: %3
                    File reference: %4
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>300</td><td>NTFS volume dismount has started.

           Volume GUID: %4
           Volume Name: %6
           Volume Label: %8
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>301</td><td>NTFS has sent volume dismount event notification and is waiting for the notifications to complete.</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>302</td><td>The volume dismount event notification on the NTFS volume has completed.</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>303</td><td>The NTFS volume has successfully dismounted.

           Volume GUID: %4
           Volume Name: %6
           Volume Label: %8
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>304</td><td>The NTFS volume dismount failed.

           Error:%1
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>305</td><td>NTFS failed to mount the volume.

           Error: %1
           Volume GUID: %2
           Volume Name: %4

Guidance:
The volume is recognized by NTFS but it is corrupted that NTFS could not mount it. Run CHKDSK /F to fix any errors on this volume, and then try accessing it.</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>401</td><td>Efs offloading initiated.

                    Volume serial: %1
                    File reference: %2
                    File name: %4
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>402</td><td>Efs offloading read regular file.

                    Volume serial: %1
                    File reference: %2
                    File name: %4
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>403</td><td>Efs offloading write regular file.

                    Volume serial: %1
                    File reference: %2
                    File name: %4
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>404</td><td>Efs legacy initiated.

                    Volume serial: %1
                    File reference: %2
                    File name: %4
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>405</td><td>Efs legacy read regular file.

                    Volume serial: %1
                    File reference: %2
                    File name: %4
</td></tr>
<tr><td>Microsoft-Windows-Ntfs</td><td>406</td><td>Efs legacy write regular file.

                    Volume serial: %1
                    File reference: %2
                    File name: %4
</td></tr>
</table>
