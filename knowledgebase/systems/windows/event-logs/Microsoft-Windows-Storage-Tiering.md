# Microsoft-Windows-Storage-Tiering

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Storage-Tiering</td><td>11</td><td>The Storage Tiers Management service started monitoring a volume on a tiered storage space. No action is required.  Volume name: %2.</td></tr>
<tr><td>Microsoft-Windows-Storage-Tiering</td><td>12</td><td>The Storage Tiers Management service encountered an error with the database of manually assigned files and re-created the database. Confirm that files that were manually assigned to a particular storage tier are still assigned to the correct tier, as appropriate. Volume name: %2.</td></tr>
<tr><td>Microsoft-Windows-Storage-Tiering</td><td>13</td><td>The Storage Tiers Management service is monitoring a volume on a tiered storage space. No action is required.

           Local volume name: %2
           CSV name: %4</td></tr>
<tr><td>Microsoft-Windows-Storage-Tiering</td><td>21</td><td>The Storage Tiers Management service completed optimization of the tiered storage space. No action is required. Volume name: %2 Result: %7.  Processing time (in minutes): %8 Optimization time (in minutes): %9  Number of clusters requested to move to Performance tier: %3; to Capacity tier: %4  Actual number of clusters moved to Performance tier: %5; to Capacity tier: %6</td></tr>
<tr><td>Microsoft-Windows-Storage-Tiering</td><td>22</td><td>Storage Tier Optimization Report for volume %2

	% I/Os serviced from Perf tier		Performance tier size required
%3
Current size of the Performance tier: %4
Percent of total I/Os serviced from the Performance tier: %5% 

Size of files pinned to the Performance tier: %6
Percent of total I/Os: %7% 

Size of files pinned to the Capacity tier: %8
Percent of total I/Os: %9%</td></tr>
<tr><td>Microsoft-Windows-Storage-Tiering</td><td>31</td><td>The Storage Tiers Management service reached the limit of in-memory records of reads and writes to a tiered storage space. Additional read and write activity will not be recorded or considered during optimization of storage tiers on this storage space for the rest of the hour.  Consider increasing the MaxInMemoryTreeSize registry value. Memory entries limit: %3 Volume name: %2</td></tr>
</table>
