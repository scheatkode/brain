# Microsoft-Windows-Windows Defender

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>101</td><td>Microsoft Defender Antivirus state updated to %1.</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1000</td><td>%1 scan has started.
 	Scan ID: %3
 	Scan Type: %5
 	Scan Parameters: %7
 	Scan Resources: %11
 	User: %8\%9</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1001</td><td>%1 scan has finished.
 	Scan ID: %3
 	Scan Type: %5
 	Scan Parameters: %7
 	User: %8\%9
 	Scan Time: %11:%12:%13</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1002</td><td>%1 scan has been stopped before completion.
 	Scan ID: %3
 	Scan Type: %5
 	Scan Parameters: %7
  	User: %8\%9</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1003</td><td>%1 scan has been paused.
 	Scan ID: %3
 	Scan Type: %5
 	Scan Parameters: %7
 	User: %8\%9</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1004</td><td>%1 scan has resumed.
 	Scan ID: %3
  	Scan Type: %5
 	Scan Parameters: %7
 	User: %8\%9</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1005</td><td>%1 scan has encountered an error and terminated.
 	Scan ID: %3
 	Scan Type: %5
 	Scan Parameters: %7
 	User: %8\%9
 	Error Code: %11
 	Error description: %12</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1006</td><td>%1 has detected malware or other potentially unwanted software.
 For more information please see the following:
%15
 	Name: %11
 	ID: %12
 	Severity: %25
 	Category: %26
 	Path Found: %16
 	Detection Type: %22
 	Detection Source: %5
 	Status: %20
 	User: %8\%9
 	Process Name: %7
 	Security intelligence Version: %27
 	Engine Version: %28</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1007</td><td>%1 has taken action to protect this machine from malware or other potentially unwanted software.
 For more information please see the following:
%15
 	User: %8\%9
 	Name: %11
 	ID: %12
 	Severity: %25
 	Category: %26
 	Action: %20
 	Status: %7
 	Security intelligence Version: %27
 	Engine Version: %28</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1008</td><td>%1 has encountered an error when taking action on malware or other potentially unwanted software.
 For more information please see the following:
%15
 	User: %8\%9
 	Name: %11
 	ID: %12
 	Severity: %25
 	Category: %26
 	Path: %16
 	Action: %20
 	Error Code: %21
 	Error description: %22
 	Status: %7
 	Security intelligence Version: %27
 	Engine Version: %28</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1009</td><td>%1 has restored an item from quarantine.
 For more information please see the following:
%15
 	Name: %11
 	ID: %12
 	Severity: %25
 	Category: %26
 	User: %8\%9
 	Security intelligence Version: %27
 	Engine Version: %28</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1010</td><td>%1 has encountered an error trying to restore an item from quarantine.
 For more information please see the following:
%15
 	Name: %11
 	ID: %12
 	Severity: %25
 	Category: %26
 	User: %8\%9
 	Error Code: %3
 	Error description: %4
 	Security intelligence Version: %27
 	Engine Version: %28</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1011</td><td>%1 has deleted an item from quarantine.
 For more information please see the following:
%15
 	Name: %11
 	ID: %12
 	Severity: %25
 	Category: %26
 	User: %8\%9
 	Security intelligence Version: %27
 	Engine Version: %28</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1012</td><td>%1 has encountered an error trying to delete an item from quarantine.
 For more information please see the following:
%15
 	Name: %11
 	ID: %12
 	Severity: %25
 	Category: %26
 	User: %8\%9
 	Error Code: %3
 	Error description: %4
 	Security intelligence Version: %27
 	Engine Version: %28</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1013</td><td>%1 has removed history of malware and other potentially unwanted software.
 	Time: %3
 	User: %8\%9
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1014</td><td>%1 has encountered an error trying to remove history of malware and other potentially unwanted software.
 	Time: %3
 	User: %8\%9
 	Error Code: %4
 	Error description: %5</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1015</td><td>%1 has detected a suspicious behavior.
 	Name: %11
 	ID: %12
 	Severity: %25
 	Category: %26
 	Path Found: %16
 	Detection Origin: %18
 	Detection Type: %22
 	Detection Source: %5
 	Status: %20
 	User: %8\%9
 	Process Name: %7
 	Security intelligence ID: %30
 	Security intelligence Version: %27
 	Engine Version: %28
 	Fidelity Label:  %32
 	Target File Name:  %36
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1116</td><td>%1 has detected malware or other potentially unwanted software.
 For more information please see the following:
%13
 	Name: %8
 	ID: %7
 	Severity: %10
 	Category: %12
 	Path: %22
 	Detection Origin: %24
 	Detection Type: %28
 	Detection Source: %18
 	User: %20
 	Process Name: %19
 	Security intelligence Version: %41
 	Engine Version: %42</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1117</td><td>%1 has taken action to protect this machine from malware or other potentially unwanted software.
 For more information please see the following:
%13
 	Name: %8
 	ID: %7
 	Severity: %10
 	Category: %12
 	Path: %22
 	Detection Origin: %24
 	Detection Type: %28
 	Detection Source: %18
 	User: %39
 	Process Name: %19
 	Action: %31
 	Action Status:  %38
 	Error Code: %33
 	Error description: %34
 	Security intelligence Version: %41
 	Engine Version: %42</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1118</td><td>%1 has encountered a non-critical error when taking action on malware or other potentially unwanted software.
 For more information please see the following:
%13
 	Name: %8
 	ID: %7
 	Severity: %10
 	Category: %12
 	Path: %22
 	Detection Origin: %24
 	Detection Type: %28
 	Detection Source: %18
 	User: %39
 	Process Name: %19
 	Action: %31
 	Action Status:  %38
 	Error Code: %33
 	Error description: %34
 	Security intelligence Version: %41
 	Engine Version: %42</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1119</td><td>%1 has encountered a critical error when taking action on malware or other potentially unwanted software.
 For more information please see the following:
%13
 	Name: %8
 	ID: %7
 	Severity: %10
 	Category: %12
 	Path: %22
 	Detection Origin: %24
 	Detection Type: %28
 	Detection Source: %18
 	User: %39
 	Process Name: %19
 	Action: %31
 	Action Status:  %38
 	Error Code: %33
 	Error description: %34
 	Security intelligence Version: %41
 	Engine Version: %42</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1120</td><td>%1 has deduced the hashes for a threat resource.
 	Current Platform Version: %2
 	Threat resource path: %4
 	Hashes: %5</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1121</td><td>Microsoft Defender Exploit Guard has blocked an operation that is not allowed by your IT administrator.
 For more information please contact your IT administrator.
 	ID: %4
 	Detection time: %5
 	User: %6
 	Path: %7
 	Process Name: %8
 	Target Commandline: %12
 	Parent Commandline: %13
 	Involved File: %14
 	Inheritance Flags: %15
 	Security intelligence Version: %9
 	Engine Version: %10
 	Product Version: %2
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1122</td><td>Microsoft Defender Exploit Guard audited an operation that is not allowed by your IT administrator.
 For more information please contact your IT administrator.
 	ID: %4
 	Detection time: %5
 	User: %6
 	Path: %7
 	Process Name: %8
 	Target Commandline: %12
 	Parent Commandline: %13
 	Involved File: %14
 	Inheritance Flags: %15
 	Security intelligence Version: %9
 	Engine Version: %10
 	Product Version: %2
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1123</td><td>%8 has been blocked from modifying %7 by Controlled Folder Access.
 	Detection time: %5
 	User: %6
 	Path: %7
 	Process Name: %8
 	Security intelligence Version: %9
 	Engine Version: %10
 	Product Version: %2
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1124</td><td>%8 would have been blocked from modifying %7 by Controlled Folder Access.
 	Detection time: %5
 	User: %6
 	Path: %7
 	Process Name: %8
 	Security intelligence Version: %9
 	Engine Version: %10
 	Product Version: %2
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1125</td><td>Your IT administrator would have caused Microsoft Defender Exploit Guard to block a potentially dangerous network connection.
 	Detection time: %4
 	User: %5
 	Destination: %6
 	Process Name: %7
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1126</td><td>Your IT administrator has caused Microsoft Defender Exploit Guard to block a potentially dangerous network connection.
 	Detection time: %4
 	User: %5
 	Destination: %6
 	Process Name: %7
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1127</td><td>Controlled Folder Access blocked %8 from making changes to memory.
 	Detection time: %5
 	User: %6
 	Path: %7
 	Process Name: %8
 	Security intelligence Version: %9
 	Engine Version: %10
 	Product Version: %2
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1128</td><td>Controlled Folder Access would have blocked %8 from making changes to memory.
 	Detection time: %5
 	User: %6
 	Path: %7
 	Process Name: %8
 	Security intelligence Version: %9
 	Engine Version: %10
 	Product Version: %2
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1129</td><td>A user has allowed a blocked Microsoft Defender Exploit Guard operation.
 	ID: %4
 	User: %5
 	Path: %6
 	Process Name: %7
 	Involved File: %8
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1131</td><td>%1 has blocked an operation that your administrator doesn&#39;t allow.
 For more information please contact your IT administrator.
 	ID: %4
 	State: %5
 	Timestamp: %6
 	Action: %7
 	Process: %8
 	Source: %9
 	Target: %10
 	User: %11
 	Signature Version: %12
 	Engine Version: %13
 	Product Version: %2
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1132</td><td>%1 has audited an operation.
 For more information please contact your IT administrator.
 	ID: %4
 	State: %5
 	Timestamp: %6
 	Action: %7
 	Process: %8
 	Source: %9
 	Target: %10
 	User: %11
 	Signature Version: %12
 	Engine Version: %13
 	Product Version: %2
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1133</td><td>%1 has blocked an operation that your administrator doesn&#39;t allow.
For more information please contact your IT administrator.
	Policy Version: %4
	Policy Rule ID: %5
	Enforcement Level: %6
	Timestamp: %8
	Action Type: %9
	Process: %10
	Source: %11
	Target: %12
	Session ID: %13
	User SID: %14
	Signature Version: %15
	Engine Version: %16
	Product Version: %2
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1134</td><td>%1 has audited an operation.
For more information please contact your IT administrator.
	Policy Version: %4
	Policy Rule ID: %5
	Enforcement Level: %6
	Audit Reason: %7
	Timestamp: %8
	Action Type: %9
	Process: %10
	Source: %11
	Target: %12
	Session ID: %13
	User SID: %14
	Signature Version: %15
	Engine Version: %16
	Product Version: %2
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1150</td><td>Endpoint Protection client is up and running in a healthy state.
 	Platform version: %2
 	Engine version: %4
 	Security intelligence version: %5
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1151</td><td>Endpoint Protection client health report (time in UTC):
 	Platform version: %2
 	Engine version: %4
 	Network Realtime Inspection engine version: %5
 	Antivirus security intelligence version: %6
 	Antispyware security intelligence version: %7
 	Network Realtime Inspection security intelligence version: %8
 	RTP state: %9
 	OA state: %10
 	IOAV state: %11
 	BM state: %12
 	Antivirus security intelligence age: %13
 	Antispyware security intelligence age: %14
 	Last quick scan age: %15
 	Last full scan age: %16
 	Antivirus security intelligence creation time: %17
 	Antispyware security intelligence creation time: %18
 	Last quick scan start time: %19
 	Last quick scan end time: %20
 	Last quick scan source: %21
 	Last full scan start time: %22
 	Last full scan end time: %23
 	Last full scan source: %24
 	Product status: %25
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>1160</td><td>%1 has detected potentially unwanted application(PUA).
 For more information please see the following:
%13
 	Name: %8
 	ID: %7
 	Severity: %10
 	Category: %12
 	Path: %22
 	Detection Origin: %24
 	Detection Type: %28
 	Detection Source: %18
 	User: %20
 	Process Name: %19
 	Security intelligence Version: %41
 	Engine Version: %42</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2000</td><td>%1 Security intelligence version has been updated.
 	Current security intelligence Version: %3
 	Previous security intelligence Version: %4
 	Security intelligence Type: %12
 	Update Type: %14
 	User: %8\%9
 	Current Engine Version: %15
 	Previous Engine Version: %16</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2001</td><td>%1 has encountered an error trying to update security intelligence.
 	New security intelligence Version: %3
 	Previous security intelligence Version: %4
 	Update Source: %6
 	Security intelligence Type: %12
 	Update Type: %14
 	User: %8\%9
 	Current Engine Version: %15
 	Previous Engine Version: %16
 	Error code: %17
 	Error description: %18</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2002</td><td>%1 engine version has been updated.
 	Current Engine Version: %3
 	Previous Engine Version: %4
 	User: %8\%9</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2003</td><td>%1 has encountered an error trying to update the engine.
 	New Engine Version: %3
 	Previous Engine Version: %4
 	User: %8\%9
 	Error Code: %11
 	Error description: %12</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2004</td><td>%1 has encountered an error trying to load security intelligence and will attempt reverting back to a known-good version.
 	Security intelligence Attempted: %4
 	Error Code: %5
 	Error description: %6
 	Security intelligence version: %9
 	Engine version: %10</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2005</td><td>%1 could not load antimalware engine because current platform version is not supported. %1 will revert back to the last known-good engine and a platform update will be attempted.
 	Current Platform Version: %2</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2006</td><td>%1 has encountered an error trying to update the platform.
 	Current Platform Version: %2
 	Error code: %4
 	Error description: %5</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2007</td><td>%1 will soon require a newer platform version to support future versions of the antimalware engine. Download the latest %1 platform to maintain the best level of protection available.
 	Current Platform Version: %2</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2008</td><td>%1 platform update update to %4 is paused due to system activity. For more details see the latest MpLog*.log entry under ProgramData.
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2009</td><td>%1 platform update to %4 has resumed.
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2010</td><td>%1 used Dynamic security intelligence Service to retrieve additional security intelligence to help protect your machine.
 	Current security intelligence Version: %3
 	Security intelligence Type: %12
 	User: %8\%9
 	Current Engine Version: %15
 	Dynamic security intelligence Type: %23
 	Persistence Path: %24
 	Dynamic security intelligence Version: %25
 	Dynamic security intelligence Compilation Timestamp: %26
 	Persistence Limit Type: %28
 	Persistence Limit: %29</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2011</td><td>%1 used Dynamic security intelligence Service to discard obsolete security intelligence updates.
 	Current security intelligence Version: %3
 	Security intelligence Type: %12
 	Current Engine Version: %15
 	Dynamic security intelligence Type: %23
 	Persistence Path: %24
 	Dynamic security intelligence Version: %25
 	Dynamic security intelligence Compilation Timestamp: %26
 	Removal Reason: %31
 	Persistence Limit Type: %28
 	Persistence Limit: %29</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2012</td><td>%1 has encountered an error trying to use Dynamic security intelligence Service.
 	Current security intelligence Version: %3
 	Security intelligence Type: %12
 	User: %8\%9
 	Current Engine Version: %15
 	Error code: %17
 	Error description: %18 	Dynamic security intelligence Type: %23
 	Persistence Path: %24
 	Dynamic security intelligence Version: %25
 	Dynamic security intelligence Compilation Timestamp: %26
 	Persistence Limit Type: %28
 	Persistence Limit: %29</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2013</td><td>%1 discarded all Dynamic security intelligence.
 	User: %8\%9
 	Current Engine Version: %15</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2014</td><td>%1 platform update to %2 has succeeded.
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2030</td><td>%1 downloaded and configured Microsoft Defender Offline to run on the next reboot.</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2031</td><td>%1 has encountered an error trying to download and configure Microsoft Defender Offline.
	Error code: %4
	Error description: %5</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2040</td><td>The support for your operating system will expire shortly. Running %1 on an out of support operating system is not an adequate solution to protect against threats.
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2041</td><td>The support for your operating system has expired. Running %1 on an out of support operating system is not an adequate solution to protect against threats.
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2042</td><td>The support for your operating system has expired. %1 is no longer supported on your operating system, has stopped functioning, and is not protecting against malware threats.
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2050</td><td>%1 has uploaded a file for further analysis.
 	Filename: %3
 	Sha256: %4
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>2051</td><td>%1 has encountered an error trying to upload a suspicious file for further analysis.
 	Filename: %3
 	Sha256: %4
 	Current security intelligence Version: %5
 	Current Engine Version: %6
 	Error code: %7
</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>3002</td><td>%1 Real-Time Protection feature has encountered an error and failed.
 	Feature: %3
 	Error Code: %5
 	Error description: %6
 	Reason: %4</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>3007</td><td>%1 Real-time Protection feature has restarted. It is recommended that you run a full system scan to detect any items that may have been missed while this agent was down.
 	Feature: %3
 	Reason: %4</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>5000</td><td>%1 Real-time Protection scanning for malware and other potentially unwanted software was enabled.</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>5001</td><td>%1 Real-time Protection scanning for malware and other potentially unwanted software was disabled.</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>5004</td><td>%1 Real-time Protection feature configuration has changed.
 	Feature: %3
 	Configuration: %4</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>5007</td><td>%1 Configuration has changed. If this is an unexpected event you should review the settings as this may be the result of malware.
 	Old value: %3
 	New value: %4</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>5008</td><td>%1 engine has been terminated due to an unexpected error.
 	Failure Type: %5
 	Exception code: %6
 	Resource: %3</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>5009</td><td>%1 scanning for spyware and other potentially unwanted software has been enabled.</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>5010</td><td>%1 scanning for spyware and other potentially unwanted software is disabled.</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>5011</td><td>%1 scanning for viruses has been enabled.</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>5012</td><td>%1 scanning for viruses is disabled.</td></tr>
<tr><td>Microsoft-Windows-Windows Defender</td><td>5013</td><td>Tamper Protection %3 a change to %1.
 	Value: %4</td></tr>
</table>
