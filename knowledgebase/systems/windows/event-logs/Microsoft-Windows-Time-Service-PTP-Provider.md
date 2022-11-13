# Microsoft-Windows-Time-Service-PTP-Provider

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Time-Service-PTP-Provider</td><td>512</td><td>PTP provider started receiving announcements from the PTP Master %1 with IP Address %2 and the following PTP parameters:
Clock Identity:%3
Port Number:%4
Domain Number:%5
Utc Offset Valid:%6
Current UTC Offset:%7
Flags:%8
Grandmaster Clock Id:%9
Steps Removed From GM:%10
Time Source Code:%11
Announce Interval (Log2):%12

Number of active Masters:%13
Current Tick Count:%14
For more information, see https://go.microsoft.com/fwlink/?linkid=873491.</td></tr>
<tr><td>Microsoft-Windows-Time-Service-PTP-Provider</td><td>513</td><td>PTP provider has chosen the PTP Master %1 with IP Address %2 as the best master and the source of time. This master is announcing the following PTP parameters:
Clock Identity:%3
Port Number:%4
Domain Number:%5
Utc Offset Valid:%6
Current UTC Offset:%7
Flags:%8
Grandmaster Clock Id:%9
Steps Removed From GM:%10
Time Source Code:%11
Announce Interval (Log2):%12

Current Tick Count:%13
If the best master keeps changing frequently, verify that the masters and this client have the same announce interval configured. For more information, see https://go.microsoft.com/fwlink/?linkid=873491.</td></tr>
<tr><td>Microsoft-Windows-Time-Service-PTP-Provider</td><td>514</td><td>PTP Master %1 with IP Address %2 has made no announcements in the last announce timeout window (%3 milliseconds). It is excluded from being considered as a (potential) time source. PTP Master parameters:
Clock Identity:%4
Port Number:%5
Announce Interval (Log2):%6

Number of active Masters:%7
Current Tick Count:%8
For more information, see https://go.microsoft.com/fwlink/?linkid=873491.</td></tr>
<tr><td>Microsoft-Windows-Time-Service-PTP-Provider</td><td>515</td><td>Ptp Provider Configuration:

Allowed Masters:%1
Announce Interval:%2(msec)
Delay Poll Interval:%3(msec)
IfTstmp:%4

PTP provider status:

PTP Best Master Details:
Name:%5
IP Address:%6
Clock Identity:%7
Port Number:%8
Tick Count At Last Time Sample:%9

ActiveMasterCount:%10
MulticastRxEnabled:%11
Current Tick Count:%12
For more information, see https://go.microsoft.com/fwlink/?linkid=873491.</td></tr>
</table>
