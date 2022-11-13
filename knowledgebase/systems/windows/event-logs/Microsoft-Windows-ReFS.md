# Microsoft-Windows-ReFS

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>4</td><td>The ReFS volume has been successfully mounted.

Volume GUID:%4
Volume Name:%6
Volume Label:%8
Device Name:%3</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>5</td><td>ReFS failed to mount the volume.
Context: %1
Error: %2

Volume GUID:%3
DeviceName:%5
Volume Name:%7</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>6</td><td>ReFS is mounting the volume.
Context: %1
Progress: %2</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>7</td><td>ReFS failed to mount the volume. Version %4.%5 doesn&#39;t match expected value %2.%3 
Context: %1
</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>8</td><td>ReFS fast tier is filling up for volume.
 Context: %1
FillRatio: %2

Volume GUID:%3
DeviceName:%5
Volume Name:%7 </td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>130</td><td>The file system structure on volume %2 has now been repaired.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>131</td><td>The file system structure on volume %2 cannot be corrected.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>132</td><td>The file system detected a checksum error and was able to correct it. The name of the file or folder is &quot;%2&quot;.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>133</td><td>The file system detected a checksum error and was not able to correct it. The name of the file or folder is &quot;%2&quot;.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>134</td><td>The file system was unable to write metadata to the media backing volume %2. A write failed with status &quot;%3&quot; ReFS will take the volume offline. It may be mounted again automatically.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>135</td><td>Volume %2 is formatted as ReFS but ReFS is unable to mount it; ReFS encountered status %3.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>136</td><td>Volume &quot;%2&quot; was mounted in an older version of Windows. Some features may be lost.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>137</td><td>The file system was unable to write metadata to the media backing volume %2. Log redo failed with status &quot;%3&quot; . The volume is being mounted without the log applied.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>138</td><td>The file system was unable to open redo log for the media backing volume %2. Log redo failed with status &quot;%3&quot; . The volume is being mounted without the log applied.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>139</td><td>The file system detected a global metadata corruption and was able to repair it on volume %2. Space may be leaked as part of the repair. If future mounts fail, attempting a readonly volume mount may succeed.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>140</td><td>The file system detected a global metadata corruption and was not able to repair it on volume %2. Attempting a readonly volume mount may succeed.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>145</td><td>IO latency summary common data for volume:

           Volume Id: %1
           Volume name: %3

           Tier Index %5
           Max Acceptable IO Latency: %6 ms
           Read/Write latency buckets (ns): [%7, %8, %9, %10, %11, %12, %13]
           Trim latency buckets (ns): [%14, %15, %16, %17, %18, %19, %20]
           Flush latency buckets (ns): [%21, %22, %23, %24, %25, %26, %27]
</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>146</td><td>IO latency summary:

           Volume Id: %1
           Volume name: %3
           Tier index: %5

           Interval duration: %7 us

           Non-cached reads:
                     IO count: %8
                     Total bytes: %9
                     Avg latency: %10 ns

           Non-cached writes: 
                     IO count: %11
                     Total bytes: %12
                     Avg latency: %13 ns

           File flushes: 
                     IO count: %14
                     Avg latency: %15 ns

           Directory flushes: 
                     IO count: %16
                     Avg latency: %17 ns

           Volume flushes: 
                     IO count: %17
                     Avg latency: %18 ns

           File level trims: 
                     IO count: %20
                     Total bytes: %21
                     Extents count: %22
                     Avg latency: %23 ns

           Volume trims: 
                     IO count: %24
                     Total bytes: %25
                     Extents count: %26
                     Avg latency: %27 ns

 For more details see the details tab.
</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>147</td><td>An IO took more than %6 ms to complete:

           Process Id: %7
           Process name: %8
           File name: %10
           File offset: %13
           IO Type: %11
           IO Size: %12 bytes
           %15 cluster(s) starting at cluster %15
           Latency: %14 ms

           Volume Id: %1
           Volume name: %3
           Tier index: %5</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>148</td><td>A %10 failed with %15.

           Process Id: %6
           Process name: %7
           File name: %9
           IO Size: %11 bytes
           File offset: %12
           %14 cluster(s) starting at cluster %13

           Volume Id: %1
           Volume name: %3
           Tier index: %5
</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>149</td><td>In the past %5 seconds we had IO failures.

           High latency IO count: %6
           Failed writes: %7
           Failed reads: %8
           Volume Id: %1
           Volume name: %3
</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>150</td><td>SMR information summary:

           Volume Id: %1
           Volume name: %3

           Sample Duration: %4

           Free Space Minimum (Randomly-Writable Tier): %5
           Free Space Maximum (Randomly-Writable Tier): %6
           Free Space Average (Randomly-Writable Tier): %7

           Free Space Minimum (SMR Tier): %8
           Free Space Maximum (SMR Tier): %9
           Free Space Average (SMR Tier): %10

           Usable Free Space Mininum (SMR Tier): %11
           Usable Free Space Maximum (SMR Tier): %12
           Usable Free Space Average (SMR Tier): %13

           Write Serialization Aborted Writes: %14
           Write Serialization Events: %15
           Write Serialization Latency Average: %16
           Write Serialization Latency Maximum: %17
           Write Serialization Blocked Events: %18
           Write Serialization Blocked Latency Average: %19

           Start Garbage Collection Calls Invoked: %20
           Start Garbage Collection Calls Failed: %21
           Start Garbage Collection Full Speed Calls Invoked: %22
           Start Garbage Collection Full Speed Calls Failed: %23
           Pause Garbage Collection Calls Invoked: %24
           Pause Garbage Collection Calls Failed: %25
           Stop Garbage Collection Calls Invoked: %26
           Stop Garbage Collection Calls Failed: %27

           Full SMR Band Cluster Allocations: %28
           Shared SMR Band Cluster Allocations: %29

           Garbage Collection Read Latency Total: %30
           Garbage Collection Read Latency Average: %31
           Garbage Collection Read Latency Maximum: %32
           Garbage Collection Total Read IOs: %33
           Garbage Collection Write Latency Total: %34
           Garbage Collection Write Latency Average: %35
           Garbage Collection Write Latency Maximum: %36
           Garbage Collection Total Write IOs: %37
           Disk Full Requires Garbage Collection: %38

           SMR Zone Full Events: %39
           CMR Zone Full Events: %40

           Invalid Sector Errors: %41
           IO Device Errors: %42
           Write Errors: %43
           Read Errors: %44
           SMR Write-Head Requeries: %45
</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>237</td><td></td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>238</td><td></td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>272</td><td></td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>273</td><td></td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>274</td><td></td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>513</td><td>The file system detected a corruption on a file. The file has been removed from the file system namespace. The name of the file is &quot;%2&quot;.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>514</td><td>The file system detected a corruption on a file. The file system may have failed to remove it from the file system namespace. The name of the file is &quot;%2&quot;.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>515</td><td>The file system detected a corruption on a folder. Contents of the folder have been removed from the file system namespace. The name of the folder is &quot;%2&quot;.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>516</td><td>The file system detected a corruption on a folder. The file system may have failed to remove contents of the folder from the file system namespace. The name of the folder is &quot;%2&quot;.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>517</td><td>The file system determined that there were multiple volumes on the given disk so has disabled read cache for the volume &quot;%2&quot;.  Status is &quot;%3&quot;.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>518</td><td>The file system could not determine if there were multiple volumes on the given disk (status is &quot;%3&quot;) so has disabled read cache for the volume &quot;%2&quot;.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>519</td><td>The file system detected a corruption on file system metadata. The name of the stream is &quot;%2&quot;.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>520</td><td>The file system detected a corruption on file system metadata. The name of the stream is &quot;%2&quot;.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>521</td><td>Volume &quot;%2&quot; detected a corruption on file system metadata. It will lose self-healing features.</td></tr>
<tr><td>Microsoft-Windows-ReFS</td><td>522</td><td>The file system detected and fixed volume size inconsistency in boot sector of volume &quot;%2&quot;.</td></tr>
</table>
