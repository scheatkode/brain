# Microsoft-Windows-VolumeSnapshot-Driver

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>0</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>2</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>3</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>4</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>5</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>6</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>7</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>8</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>9</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>10</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>11</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>12</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>13</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>14</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>15</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>16</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>17</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>18</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>19</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>20</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>21</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>22</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>23</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>24</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>25</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>26</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>27</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>28</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>29</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>30</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>31</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>32</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>33</td><td></td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>100</td><td>The volume snapshot driver has begun processing for volume online.

Volume GUID: %1

Guidance:
When a volume is brought online the volume snapshot driver scans for any persistent snapshots that may be on the volume.

You should expect this event when a volume is brought online.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>101</td><td>The volume snapshot driver has completed processing for volume online.

Volume GUID: %1

Guidance:
The volume snapshot driver was able to scan for any persistent snapshots on this volume.

You should expect this event when a volume is brought online.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>102</td><td>The volume snapshot driver encountered an error while performing processing for volume online.

Error: %2

Volume GUID: %1

Guidance:
When a volume is brought online the volume snapshot driver scans for any persistent snapshots that may be on the volume.  In case of an error this scan is not performed.  The error may have originated in storage drivers beneath the volume snapshot driver; check their logs.

If the error is STATUS_DEVICE_NOT_CONNECTED this means the volume is in snapshot protection mode and has been taken offline to prevent loss of snapshots.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>103</td><td>Activation of discovered snapshots began.

Volume GUID: %1

Guidance:
When a volume is brought online or reverted to a snapshot, the volume snapshot driver scans for and activates any persistent snapshots that may be on the volume.

You should expect this event when a volume is brought online or reverted to a snapshot.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>104</td><td>Activation of discovered snapshots completed.

Volume GUID: %1
Total Number of Snapshots Found: %2
Number of Snapshots Marked for Delete: %3
Number of Visible Snapshots Found: %4

Guidance:
When a volume is brought online or reverted to a snapshot, the volume snapshot driver scans for and activates any persistent snapshots that may be on the volume.  Some snapshots may be marked &#39;visible&#39;, meaning they were exposed as a local volume or file share.  Some detected snapshots may be marked &#39;deleted&#39;, meaning they are no longer available for use and their diff area space will be reclaimed when all older snapshots are deleted.  Look for instances of event 106 to see each snapshot that was discovered and whether it was &#39;visible&#39; or &#39;deleted&#39;.

You should expect this event when a volume is brought online or reverted to a snapshot.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>105</td><td>Activation of discovered snapshots encountered an error.

Error: %2

Volume GUID: %1

Guidance:
When a volume is brought online or reverted to a snapshot, the volume snapshot driver scans for and activates any persistent snapshots that may be on the volume.  Unless the volume is in snapshot protection mode or the error code indicates the volume is offline, a failure during this process results in loss of all snapshots on the volume.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>106</td><td>A persistent snapshot was activated.

Volume GUID: %1
Snapshot GUID: %2
Snapshot Marked Deleted: %3
Snapshot Visible: %4
Snapshot Commit Timestamp: %5

Guidance:
When a volume is brought online or reverted to a snapshot, the volume snapshot driver scans for and activates any persistent snapshots that may be on the volume.  If the snapshot is &#39;visible&#39;, it was exposed as a local volume or file share.  If the snapshot is &#39;deleted&#39;, it is no longer available for use and its diff area space will be reclaimed when all older snapshots are deleted.

You should expect this event when a volume containing persistent snapshots is brought online or reverted to a snapshot.  If all discovered snapshots are successfully activated you should expect event 104, otherwise you will see event 105.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>107</td><td>Reading of a snapshot diff area&#39;s metadata began.

Volume GUID: %1
Snapshot GUID: %2

Guidance:
When a volume is brought online or reverted to a snapshot, the volume snapshot driver reads the diff area for the most-recent persistent snapshot (if any).  The diff area for earlier persistent snapshots is typically read the first time the snapshot is read from.

You should expect this event when a volume is brought online, reverted to a snapshot, or when reading from a persistent snapshot for the first time after bringing a volume online.  This event may also occur if a volume is dismounted that contains snapshots that have not been read since the volume was brought online.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>108</td><td>Reading of a snapshot diff area&#39;s metadata completed.

Volume GUID: %1
Snapshot GUID: %2
Count of 1MB Reads: %3
Count of 16KB Reads: %4
Diff Area Metadata Size: %5 Bytes
Total Data Read: %6 Bytes

Guidance:
When a volume is brought online or reverted to a snapshot, the volume snapshot driver reads the diff area for the most-recent persistent snapshot (if any).  The diff area for earlier persistent snapshots is typically read the first time the snapshot is read from.  The size of the diff area metadata may be less than the total number of bytes read if the diff area is discontiguous on disk.

You should expect this event when a volume is brought online, reverted to a snapshot, or when reading from a persistent snapshot for the first time after bringing a volume online.  This event may also occur if a volume is dismounted that contains snapshots that have not been read since the volume was brought online.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>109</td><td>Reading of a snapshot diff area&#39;s metadata encountered an error.

Error: %3

Volume GUID: %1
Snapshot GUID: %2
Count of 1MB Reads: %4
Count of 16KB Reads: %5
Amount of Diff Area Metadata Read: %6 Bytes
Total Data Read: %7 Bytes

Guidance:
When a volume is brought online or reverted to a snapshot, the volume snapshot driver reads the diff area for the most-recent persistent snapshot (if any).  The diff area for earlier persistent snapshots is typically read the first time the snapshot is read from.  Unless the volume is in snapshot protection mode, a failure during this process results in loss of all snapshots on the volume.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>110</td><td>Validation of diff area files began.

Volume GUID: %1

Guidance:
When a volume is mounted, the volume snapshot driver reads and validates all the diff area files located on the volume.  These diff area files may be for persistent snapshots of the volume being mounted, or for persistent snapshots of other volumes.

You should expect this event when mounting a volume.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>111</td><td>Validation of diff area files completed.

Number of Diff Areas: %2

Guidance:
When a volume is mounted, the volume snapshot driver reads and validates all the diff area files located on the volume.  These diff area files may be for persistent snapshots of the volume being mounted, or for persistent snapshots of other volumes.

You should expect this event when mounting a volume.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>112</td><td>Validation of diff area files encountered an error.

Error: %2

Volume GUID: %1

Guidance:
When a volume is mounted, the volume snapshot driver reads and validates all the diff area files located on the volume.  These diff area files may be for persistent snapshots of the volume being mounted, or for persistent snapshots of other volumes.  A failure during this process results in loss of all snapshots whose diff area files are located on the volume, unless those snapshots are of volumes that are in snapshot protection mode.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>113</td><td>The volume is preparing to be taken offline.

Volume GUID: %1

Guidance:
Some system services, such as the cluster service, inform the volume snapshot driver when they are about to take the volume offline.

You should expect this event when an entity such as the cluster service prepares to take a volume offline.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>114</td><td>The volume snapshot driver has begun processing for dismount.

Volume GUID: %1

Guidance:
When a volume is dismounted, the volume snapshot driver closes any handles it may have open on the dismounting volume, such as handles to diff areas.  All auto-release snapshots that have diff areas on the dismounting volume are deleted at this time. The volume snapshot driver may also perform some work to detect whether any future direct writes to the volume are to diff area space for persistent snapshots.  If such writes occur this detection work allows the volume snapshot driver to destroy the snapshots, since the direct volume writes may corrupt them.

You should expect this event when a volume dismounts.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>115</td><td>The volume snapshot driver has completed processing for dismount.

Volume GUID: %1

Guidance:
When a volume is dismounted, the volume snapshot driver closes any handles it may have open on the dismounting volume, such as handles to diff areas.  All auto-release snapshots that have diff areas on the dismounting volume are deleted at this time. The volume snapshot driver may also perform some work to detect whether any future direct writes to the volume are to diff area space for persistent snapshots.  If such writes occur this detection work allows the volume snapshot driver to destroy the snapshots, since the direct volume writes may corrupt them.

You should expect this event when a volume dismounts.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>116</td><td>The volume snapshot driver has begun processing for volume offline.

Volume GUID: %1

Guidance:
When a volume is taken offline, the volume snapshot driver disables any persistent snapshots that still exist for the volume (autorelease snapshots were deleted when the volume was dismounted).  Snapshots of other volumes whose diff areas are on the offlining volume are destroyed, unless those volumes are in snapshot protection mode.  In that case those volumes are taken offline.

You should expect this event when a volume is taken offline.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>117</td><td>The volume snapshot driver has completed processing for volume offline.

Volume GUID: %1

Guidance:
When a volume is taken offline, the volume snapshot driver disables any persistent snapshots that still exist for the volume (autorelease snapshots were deleted when the volume was dismounted).  Snapshots of other volumes whose diff areas are on the offlining volume are destroyed, unless those volumes are in snapshot protection mode.  In that case those volumes are taken offline.

You should expect this event when a volume is taken offline.  No user action is required.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>118</td><td>The volume snapshot driver encountered an error while performing processing for volume offline.

Error: %2

Volume GUID: %1

Guidance:
When a volume is taken offline, the volume snapshot driver disables any persistent snapshots that still exist for the volume (autorelease snapshots were deleted when the volume was dismounted).  Snapshots of other volumes whose diff areas are on the offlining volume are destroyed, unless those volumes are in snapshot protection mode.  In that case those volumes are taken offline.

If the error is STATUS_INSUFFICIENT_RESOURCES (0xc000009a), the volume snapshot driver may have been unable to allocate memory.  Other error codes originate from lower drivers.  Please check their log(s) for further information.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>119</td><td>The volume snapshot driver encountered an error while performing processing for dismount.

Error: %3
Error Details: %2

Volume GUID: %1

Guidance:
When a volume is dismounted, the volume snapshot driver closes any handles it may have open on the dismounting volume, such as handles to diff areas.  All auto-release snapshots that have diff areas on the dismounting volume are deleted at this time. The volume snapshot driver may also perform some work to detect whether any future direct writes to the volume are to diff area space for persistent snapshots.  If such writes occur this detection work allows the volume snapshot driver to destroy the snapshots, since the direct volume writes may corrupt them.

A failure during this process results in loss of all snapshots whose diff area files are located on the volume, unless those snapshots are of volumes that are in snapshot protection mode.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>120</td><td>Activation of discovered snapshots took too long and was aborted.

Volume GUID: %1
Timeout Value (in seconds): %2

Guidance:
When a volume is brought online or reverted to a snapshot, the volume snapshot driver scans for and activates any persistent snapshots that may be on the volume.  This process took longer than the amount of time allowed on this system, so activation has been aborted.  Unless the volume is in snapshot protection mode, all snapshots on this volume have been deleted.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>121</td><td>The volume snapshot driver was unable to log an event to the legacy System event log.

Volume Name: %2
Diff Volume Name (if applicable): %4
Original Error Event Code: %5
Original Error Status: %6
Cause of Logging Failure:%10</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>122</td><td>The volume snapshot driver encountered an error when attempting to determine whether the volume is clustered.

Error: %2

Volume GUID: %1

Guidance:
When a volume is brought online or reverted to a snapshot, the volume snapshot driver scans for and activates any persistent snapshots that may be on the volume.  This process attempts to determine whether the volume is part of a cluster shared resource, but the query to determine this failed.

This error does not indicate that any snapshots have been deleted.  You should expect this event if the volume is on a dynamic disk or is managed by a third-party volume manager.</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1000</td><td>PrepareForSnapshot (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1001</td><td>PrepareForSnapshot (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1002</td><td>PreExposure (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1003</td><td>PreExposure (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1004</td><td>AdjustBitmap (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1005</td><td>AdjustBitmap (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1006</td><td>EndCommit (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1007</td><td>EndCommit (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1008</td><td>Activate (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1009</td><td>Activate (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1010</td><td>SetIgnorable (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1011</td><td>SetIgnorable (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1012</td><td>ComputeIgnorableProduct (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1013</td><td>ComputeIgnorableProduct (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1014</td><td>Dismount (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1015</td><td>Dismount (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1016</td><td>Remount (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1017</td><td>Remount (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1018</td><td>DeleteProcess (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1019</td><td>DeleteProcess (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1020</td><td>Revert (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1021</td><td>Revert (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1022</td><td>ComputeProtectedBitmap (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1023</td><td>ComputeProtectedBitmap (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1024</td><td>FlushHoldFs (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1025</td><td>FlushHoldFs (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1026</td><td>ActivateLoop (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1027</td><td>ActivateLoop (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1028</td><td>ValidateDiffAreaFiles (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1029</td><td>ValidateDiffAreaFiles (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1030</td><td>VolumesSafeForWrite (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1031</td><td>VolumesSafeForWrite (Leave)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1032</td><td>DiscoverSnapshots (Enter)</td></tr>
<tr><td>Microsoft-Windows-VolumeSnapshot-Driver</td><td>1033</td><td>DiscoverSnapshots (Leave)</td></tr>
</table>
