# Microsoft-Windows-Eventlog

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>20</td><td>The event logging service encountered an error %1 while obtaining or processing configuration for channel %2.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>21</td><td>The event logging service encountered a configuration-related error (res=%1) for channel %2. The error was encountered while processing the %3 configuration property.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>22</td><td>The event logging service encountered an error while initializing publishing resources for channel %2. If channel type is Analytic or Debug, then this could mean there was an error initializing logging resources as well.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>23</td><td>The event logging service encountered an error (res=%1) while initializing logging resources for channel %2.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>25</td><td>The event logging service encountered a corrupt log file for channel %1. The log was renamed with a .corrupt extension.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>26</td><td>The event logging service encountered a log file for channel %1 which is an unsupported version. The log was renamed with a .UnsupportedVer extension.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>27</td><td>The event logging service encountered an error (res=%1) while opening log file for channel %2. Trying again using default log file path %3.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>27</td><td>The event logging service encountered an error (res=%1) while opening log file for channel %2 at %3. Trying again using default log file path %4.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>28</td><td>The event logging service encountered an error (res=%1) while parsing filter for channel %2. Will continue without filter.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>29</td><td>The event logging service encountered a fatal error (res=%1) when applying settings to the %2 channel. The service is shutting down since this channel is vital to its operation.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>30</td><td>The event logging service encountered an error (%1) while enabling publisher %3 to channel %2. This does not affect channel operation, but does affect the ability of the publisher to raise events to the channel. One common reason for this error is that the Provider is using ETW Provider Security and has not granted enable permissions to the Event Log service identity.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>31</td><td>The event logging service encountered an error (res=%1) while opening configuration for primary channel %2. Trying again using default configuration. This problem usually occurs if registry has been corrupted or explicitly misconfigured.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>40</td><td>The event logging service encountered an error when attempting to apply one or more policy settings.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>100</td><td>The event logging service encountered an error while processing an incoming event published from %3.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>102</td><td>The event logging service encountered an error while processing an incoming event from publisher %3 and trying to process the metadata for it.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>103</td><td>Events have been dropped by the transport.  The session name is %2 and the reason code is %1.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>104</td><td>The %3 log file was cleared.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>105</td><td>Event log automatic backup
	Log:	%1
	File:	%2
</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>106</td><td>Corruption was detected in the log for the %1 channel and some data was erased.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>107</td><td>The event logging service encountered an error %1 while going through publisher configuration. The publisher %2 is already installed with GUID %3.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>108</td><td>The previous system shutdown was unexpected.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>109</td><td>The event logging service encountered an error while processing an incoming event from publisher %3 and trying to process the metadata for it.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>110</td><td>Loading metadata for publisher %2 (%1) and trying to process the metadata for it.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>111</td><td>Finished loading metadata for publisher %2 (%1), with %3 event metadatas processed.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>112</td><td>Failed to load metadata for publisher %2 (%1). The reason code is %3.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>200</td><td>Channel %1 (%2) was enabled (%3) programmatically.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>201</td><td>A push subscription was created for %1.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>202</td><td>A pull subscription was created for %1.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>203</td><td>OpenEventLog legacy API was used to open %2.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>204</td><td>RegisterEventSource legacy API was used to register %2.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>205</td><td>ReportEvent legacy API was used to write an event to %2.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>1100</td><td>The event logging service has shut down.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>1101</td><td>Audit events have been dropped by the transport.  %1</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>1102</td><td>The audit log was cleared.
Subject:
	Security ID:	%1
	Account Name:	%2
	Domain Name:	%3
	Logon ID:	%4</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>1103</td><td>The security log is now %1 percent full.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>1104</td><td>The security log is now full.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>1105</td><td>Event log automatic backup
	Log:	%1
	File:	%2
</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>1106</td><td>Events have been dropped by the event logging service. The reason code is %1.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>1107</td><td>The event logging service encountered an error while processing an incoming event from publisher %3 and trying to process the metadata for it.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>1108</td><td>The event logging service encountered an error while processing an incoming event published from %3.</td></tr>
<tr><td>Microsoft-Windows-Eventlog</td><td>6000</td><td>The %1 log file is full.</td></tr>
</table>
