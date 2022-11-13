# Microsoft-Windows-Diagnostics-Networking

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>1000</td><td>Network Diagnostics Framework started because the user requested a diagnostics session. 

Helper Class Name: %1 

Number of parameters: %2 

Attributes passed to helper class: 
%3</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>2000</td><td>Network Diagnostics Framework stopped because it completed the user initiated diagnostics session. 

Result: Success, no problems found. [%1]</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>2100</td><td>Network Diagnostics Framework stopped because it completed the user initiated diagnostics session. 

Result: Success, problems repaired. [%1]</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>2200</td><td>Network Diagnostics Framework stopped because it completed the user initiated diagnostics session. 

Result: Failed during diagnosis. [%1]</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>2300</td><td>Network Diagnostics Framework stopped because it completed the user initiated diagnostics session. 

Result: Failed during repair. [%1]</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>2400</td><td>Network Diagnostics Framework stopped because it completed the user initiated diagnostics session. 

Result: Cancelled during diagnosis. [%1]</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>2500</td><td>Network Diagnostics Framework stopped because it completed the user initiated diagnostics session. 

Result: Cancelled during repair. [%1]</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>3000</td><td>An error occurred. The Network Diagnostics Framework failed to complete operation. A Windows Error Report was generated. [%1].</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>3100</td><td>An error occurred. The Network Diagnostics Framework failed to complete operation. A Windows Error Report was generated. [%1].</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>4000</td><td>This event is not emitted, it remains manifested for AppCompat</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>4000</td><td>The Network Diagnostics Framework has completed the diagnosis phase of operation. The following repair option was offered: 

Helper Class Name: %7

Root Cause: %1 

Root Cause Guid: %2 

Repair option: %3 

RepairGuid: %4 

Seconds required for repair: %5 

Security context required for repair: %6

Interface: %8 (%9)</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>4100</td><td>The Network Diagnostics Framework has completed the diagnosis phase of operation, but no network problem was identified.</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>4200</td><td>An error occurred. The Network Diagnostics Framework failed to complete the diagnosis phase of operation. A Windows Error Report was generated. [%1]</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>5000</td><td>This event is not emitted, it remains manifested for AppCompat</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>5000</td><td>The Network Diagnostics Framework has completed the repair phase of operation. The following repair option or work-around was executed: 

Helper Class Name: %7 

Repair option: %3 

RepairGuid: %4 

The repair option appears to have successfully fixed the diagnosed problem.</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>5100</td><td>This event is not emitted, it remains manifested for AppCompat</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>5100</td><td>The Network Diagnostics Framework (NDF) has completed the repair phase of operation. The following repair option or work-around was executed: 

Helper Class Name: %7 

Repair option: %3 

RepairGuid: %4 

The repair option appears to have successfully fixed the diagnosed problem. But NDF has detected the existence of other network problems. NDF should be re-run to diagnose these problems.</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>5200</td><td>This event is not emitted, it remains manifested for AppCompat</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>5200</td><td>The Network Diagnostics Framework failed to execute the following repair: 

Repair option: %3 

RepairGuid: %4</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>5300</td><td>An error occurred. The Network Diagnostics Framework failed to complete the repair phase of operation. A Windows Error Report was generated. [%1]</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>6000</td><td>Details about %1 diagnosis: 

%2</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>6100</td><td>Details about %1 diagnosis: 

%2</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>6200</td><td>Details about %1 diagnosis: 

%2</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>7000</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>7010</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>7020</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>7030</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>7040</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>7050</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>7100</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8001</td><td>Start NDF Incident</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8002</td><td>Stop NDF Incident</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8003</td><td>Start NDF Diagnose</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8004</td><td>Stop NDF Diagnose</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8005</td><td>Start NDF Repair</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8006</td><td>Stop NDF Repair</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8007</td><td>Start NDF Validate</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8008</td><td>Stop NDF Validate</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8009</td><td>Start NDF Reproduce Failure</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8010</td><td>Stop NDF Reproduce Failure</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8103</td><td>Start NDF Helper Class &#39;%1&#39; Diagnose</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8104</td><td>Stop NDF Helper Class &#39;%1&#39; Diagnose</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8107</td><td>Start NDF Helper Class &#39;%1&#39; Validate</td></tr>
<tr><td>Microsoft-Windows-Diagnostics-Networking</td><td>8108</td><td>Stop NDF Helper Class &#39;%1&#39; Validate</td></tr>
</table>
