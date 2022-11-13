# Microsoft-Windows-Time-Service

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>1</td><td>The time provider &#39;%1&#39; logged the following error: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>2</td><td>The time provider &#39;%1&#39; logged the following warning: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>3</td><td>The time provider &#39;%1&#39; logged the following message: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>4</td><td>The time provider &#39;%1&#39; failed to start due to the following error: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>5</td><td>The time provider &#39;%1&#39; returned the following error during shutdown: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>6</td><td>The time service encountered an error while reading its configuration from the registry, and will continue running with its previous configuration. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>7</td><td>The time provider &#39;%1&#39; returned an error while updating its configuration. The error will be ignored. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>8</td><td>The time provider &#39;%1&#39; returned an error when notified of a polling interval change. The error will be ignored. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>9</td><td>The time provider &#39;%1&#39; returned an error when notified of a time jump. The error will be ignored. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>10</td><td>The time provider &#39;%1&#39; returned an error when asked for time samples. The error will be ignored. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>11</td><td>Time Provider NtpClient: This machine is configured to use the domain hierarchy to determine its time source, but it is not a member of a domain. NtpClient will attempt to use an alternate configured external time source if available. If an external time source is not configured or used for this computer, you may choose to disable the NtpClient.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>12</td><td>Time Provider NtpClient: This machine is configured to use the domain hierarchy to determine its time source, but it is the AD PDC emulator for the domain at the root of the forest, so there is no machine above it in the domain hierarchy to use as a time source. It is recommended that you either configure a reliable time service in the root domain, or manually configure the AD PDC to synchronize with an external time source. Otherwise, this machine will function as the authoritative time source in the domain hierarchy. If an external time source is not configured or used for this computer, you may choose to disable the NtpClient.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>13</td><td>Time Provider NtpClient: This machine is configured to use the domain hierarchy to determine its time source, but the computer is joined to a Windows NT 4.0 domain. Windows NT 4.0 domain controllers do not have a time service and do not support domain hierarchy as a time source. NtpClient will attempt to use an alternate configured external time source if available. If an external time source is not configured or used for this computer, you may choose to disable the NtpClient.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>14</td><td>The time provider NtpClient was unable to find a domain controller to use as a time source. NtpClient will try again in %1 minutes.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>15</td><td>The time provider NtpClient was unable to find a domain controller to use as a time source.  NtpClient will fall back to the remaining configured time sources, if any are available. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>16</td><td>Time Provider NtpClient: An unexpected error occurred during DNS lookup of the manually configured peer &#39;%1&#39;. This peer will not be used as a time source. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>17</td><td>Time Provider NtpClient: An error occurred during DNS lookup of the manually configured peer &#39;%1&#39;. NtpClient will try the DNS lookup again in %3 minutes. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>18</td><td>The time provider NtpClient failed to establish a trust relationship between this computer and the %1 domain in order to securely synchronize time. NtpClient will try again in %3 minutes. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>19</td><td>Logging was requested, but the time service encountered an error while trying to set up the log file: %1. The error was: %2. Please make sure that &#39;Local Service&#39; has permission to write to the file or directory.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>20</td><td>Logging was requested, but the time service encountered an error while trying to write to the log file: %1. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>21</td><td>The time service is configured to use one or more input providers, however, none of the input providers are available. The time service has no source of accurate time.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>22</td><td>The time provider NtpServer encountered an error while digitally signing the NTP response for peer %1. NtpServer cannot provide secure (signed) time to the client and will ignore the request. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>23</td><td>The time provider NtpServer encountered an error while digitally signing the NTP response for symmetric peer %1. NtpServer cannot provide secure (signed) time to the peer and will not send a packet. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>24</td><td>Time Provider NtpClient: No valid response has been received from domain controller %1 after 8 attempts to contact it. This domain controller will be discarded as a time source and NtpClient will attempt to discover a new domain controller from which to synchronize. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>25</td><td>The time provider NtpClient cannot determine whether the response received from %1 has  a valid signature. The response will be ignored. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>26</td><td>Time Provider NtpClient: The response received from domain controller %1 has a bad signature. The response may have been tampered with and will be ignored.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>27</td><td>Time Provider NtpClient: The response received from domain controller %1 is missing the signature. The response may have been tampered with and will be ignored.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>28</td><td>The time provider NtpClient is configured to acquire time from one or more time sources, however none of the sources are accessible. NtpClient has no source of accurate time.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>29</td><td>The time provider NtpClient is configured to acquire time from one or more time sources, however none of the sources are currently accessible. No attempt to contact a source will be made for %1 minutes. NtpClient has no source of accurate time.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>30</td><td>The time service encountered an error while reading its configuration from the registry and cannot start. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>31</td><td>The time service discovered that the system time zone information was corrupted. Because many system components require valid time zone information, the time service has reset the system time zone to GMT. Use the Date/Time control panel to set the correct time zone.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>32</td><td>The time service discovered that the system time zone information was corrupted. The time service tried to reset the system time zone to GMT, but failed. The time service cannot start. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>33</td><td>The time service has jumped the local system clock by %1 seconds. This occurs when the time source and local system time are far enough apart that clock rate adjustments cannot be made to reach the time specified by the time source.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>34</td><td>The time service has detected that the system time needs to be  changed by %1 seconds. The time service will not change the system time by more than %2 seconds. Verify that your time and time zone are correct, and that the time source %3 is working properly.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>35</td><td>The time service is now synchronizing the system time with the time source %1 with reference id %2. Current local stratum number is %3.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>36</td><td>The time service has not synchronized the system time for the last %1 seconds because none of the time service providers provided a usable time stamp. The time service will not update the local system time until it is able to synchronize with a time source. If the local system is configured to act as a time server for clients, it will stop advertising as a time source to clients after %2 seconds. The time service will continue to retry and sync time with its time sources. Check system event log for other W32time events for more details. Run &#39;w32tm /resync&#39; to force an instant time synchronization. You can control the frequency of the time source rediscovery using ClockHoldoverPeriod W32time config setting. Modify the EventLogFlags W32time config setting if you wish to disable this message.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>37</td><td>The time provider NtpClient is currently receiving valid time data from %1.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>38</td><td>The time provider NtpClient has not received response from server %1.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>39</td><td>The time service is unable to register for network configuration change events. This may occur when TCP/IP is not correctly configured. The time service will be unable to sync time from network providers, but will still use locally installed hardware provdiers, if any are available.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>40</td><td>The time provider &#39;%1&#39; was stopped with error %2.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>41</td><td>The time service has been configured to use one or more input providers, however, none of the input providers are still running. The time service has no source of accurate time.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>42</td><td>The time service attempted to create a named event which was already opened. This could be the result of an attempt to compromise your system&#39;s security.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>43</td><td>The time provider &#39;%1&#39; returned an error when notified of a network configuration change. The error will be ignored. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>44</td><td>The time provider NtpClient encountered an error and was forced to shut down. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>45</td><td>The time provider NtpServer encountered an error and was forced to shut down. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>46</td><td>The time service encountered an error and was forced to shut down. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>47</td><td>Time Provider NtpClient: No valid response has been received from manually configured peer %1 after 8 attempts to contact it. This peer will be discarded as a time source and NtpClient will attempt to discover a new peer with this DNS name. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>48</td><td>Time Provider NtpClient: An error occurred during DNS lookup of the manually configured peer &#39;%1&#39;. NtpClient will continue to try the DNS lookup every %3 minutes. This message will not be logged again until a successful lookup of this manually configured peer occurs. The error was: %2</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>49</td><td>The time provider NtpClient was unable to find a domain controller to use as a time source. NtpClient will continue trying to locate an AD DC every %1 minutes. This message will not be logged again until after a domain controller is found.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>50</td><td>The time service detected a time difference of greater than %1 milliseconds for %2 seconds. The time difference might be caused by synchronization with low-accuracy time sources or by suboptimal network conditions. The time service is no longer synchronized and cannot provide the time to other clients or update the system clock. When a valid time stamp is received from a time service provider, the time service will correct itself.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>51</td><td>Time Provider NtpClient: The time sample received from peer %1 differs from the local time by %2 seconds. The observed transmission delay from the server was %3 milliseconds.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>52</td><td>The time service has set the time with offset %1 seconds.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>53</td><td>The time provider NtpClient fails sending request to server %1.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>54</td><td>The time service encountered an error while refreshing its configuration in the registry and cannot start. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>129</td><td>NtpClient was unable to set a domain peer to use as a time source because of discovery error. NtpClient will try again in %2 minutes and double the reattempt interval thereafter. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>130</td><td>NtpClient was unable to set a domain peer to use as a time source because of failure in establishing  a trust relationship between this computer and the &#39;%3&#39; domain in order to securely synchronize time. NtpClient will try again in %2 minutes and double the reattempt interval thereafter. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>131</td><td>NtpClient was unable to set a domain peer to use as a time source because of DNS resolution error on &#39;%3&#39;. NtpClient will try again in %2 minutes and double the reattempt interval thereafter. The error was: %1.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>132</td><td>NtpClient was unable to set a domain peer to use as a time source because of duplicate error on &#39;%3&#39;.  The same time source &#39;%4&#39; has been specified as manual peer in NtpServer. NtpClient will try again in %2 minutes and double the reattempt interval thereafter. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>133</td><td>NtpClient was unable to set a domain peer to use a time source because of an unexpected error.  NtpClient will try again in %2 minutes and double the reattempt interval thereafter. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>134</td><td>NtpClient was unable to set a manual peer to use as a time source because of DNS resolution error on &#39;%3&#39;. NtpClient will try again in %2 minutes and double the reattempt interval thereafter. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>135</td><td>NtpClient was unable to set a manual peer to use as a time source because of duplicate error on &#39;%3&#39;. The same time source &#39;%4&#39; has been either specified as manual peer in NtpServer or selected as domain peer.  NtpClient will try again in %2 minutes and double the reattempt interval thereafter. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>136</td><td>NtpClient was unable to set a manual peer to use as a time source because of an unexpected error. NtpClient will try again in %2 minutes and double the reattempt interval thereafter. The error was: %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>137</td><td>NtpClient succeeds in resolving manual peer %1 after a previous failure.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>138</td><td>NtpClient succeeds in resolving domain peer %1 after a previous failure.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>139</td><td>The time service has started advertising as a time source.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>140</td><td>The time service has stopped advertising as a time source because the local machine is not an Active Directory Domain Controller.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>141</td><td>The time service has stopped advertising as a time source because there are no providers running.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>142</td><td>The time service has stopped advertising as a time source because the local clock is not synchronized.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>143</td><td>The time service has started advertising as a good time source.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>144</td><td>The time service has stopped advertising as a good time source.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>145</td><td>The time service has stopped advertising as a time source.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>146</td><td>The RODC has received %1 requests in the previous %2 minutes. %3 have resulted in success, and %4 have resulted in failure.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>147</td><td>The time sample was rejected because: Duplicate timestamps were received from this peer.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>148</td><td>The time sample was rejected because: Message was received out-of-order.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>149</td><td>The time sample was rejected because: The peer is not synchronized, or reachability has been lost in one, or both, directions. This may also indicate that the peer has incorrectly sent an NTP request instead of an NTP response.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>150</td><td>The time sample was rejected because: Round-trip delay too large.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>151</td><td>The time sample was rejected because: Packet not authenticated.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>152</td><td>The time sample was rejected because: The peer is not synchronized, or it has been too long since the peer&#39;s last synchronization.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>153</td><td>The time sample was rejected because: The peer&#39;s stratum is less than the host&#39;s stratum.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>154</td><td>The time sample was rejected because: Packet contains unreasonable root delay or root dispersion values. This may be caused by poor network conditions.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>156</td><td>The RODC was unable to forward a time sync request from client RID %1 because the client&#39;s RID value is too large and the domain peer (%2) does not support the uplevel timesync authentication format.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>157</td><td>The time provider NtpServer received a request from a client (%1) using a legacy protocol format. The request has been ignored per the RequireSecureTimeSyncRequests policy setting. By default, this message will be logged only once per day per unique client address.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>158</td><td>The time provider &#39;%1&#39; has indicated that the current hardware and operating environment is not supported and has stopped. This behavior is expected for VMICTimeProvider on non-HyperV-guest environments. This may be the expected behavior for the current provider in the current operating environment as well.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>159</td><td>W32time is unable to communicate with Netlogon Service. This failure prevents NTPClient from discovering and using domain peers, besides causing problems with correct W32time service state being advertised by Netlogon. This could be a temporary condition that resolves itself shortly. If this warning repeats over a considerable period of time, ensure the Netlogon service is running and is responsive and restart W32time service to reintiaize the overall state. The error was %1</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>257</td><td>W32time service has started at %1 (UTC), System Tick Count %2.
Configuration:
%3
Time Providers:
%4Clock Rate:%5
For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>258</td><td>W32time service is stopping at %1 (UTC), System Tick Count %2 with return code: %3
For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>259</td><td>NTP Client provider periodic status:
Ntp Client is receiving time data from the following NTP Servers: %1  and the chosen reference time server is %2. System Tick Count %3. IFTSTMP:%4.
For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>260</td><td>W32time Service periodic configuration and status message
Configuration:
%1
Time Providers:
%2
Current Status:
Leap Indicator: %3
Stratum: %4
Precision: %5
RootDelay: %6
RootDispersion: %7
ReferenceId: %8
Last Successful Sync Time: %9 (UTC)
Source: %10
Poll Interval: %11
Phase Offset: %12
Clock Rate: %13
State Machine: %14
Time Source Flags: %15
Server Role: %16
Last Sync Error: %17
Time Since Last Good Sync: %18
System Tick Count: %19
For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>261</td><td>W32time service has set the system time to %1(UTC). Previous system time was %2(UTC). System Tick Count: %3
For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>262</td><td>W32time service has adjusted the system clock rate by %1 PPM and the new nominal clock rate is %2. Previous nominal clock rate was %3. System Tick Count: %4.
Clock adjustments below %5 PPM are not logged. Performance counters are recommended to efficiently track small adjustment values.
For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>263</td><td>W32time Service configuration parameters have been updated. This may impact the fine-grained time synchronization accuracy.
Updated Configuration:
%1
Updated Time Providers:
%2System Tick Count: %3
For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>264</td><td>NTP Client observed a change peer reachability. Ntp Client is now receiving time data from the following NTP Servers: %1. System Tick Count: %2.
For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>265</td><td>The time service is now synchronizing the system time with the reference time source %1 with reference id %2. Current local stratum number is %3, System Tick Count: %4.
For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>266</td><td>W32time Service received notification to rediscover its time sources and/or resynchronize time. Reason Code:%1 System Tick Count: %2
Reason code description:
0 : An explicit time resynchronization request from an administrator
1 : Power state changes on this machine
2 : Changes to the network interface or to the network topology
3 : State changes within W32time that require time synchronization
The actions that follow this notifcation may impact fine-grained time synchronization accuracy.For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>272</td><td>Leap second configuration:
Enabled: %1 (Local)
Count: %2 (Local)
Current Offset from UTC(Seconds): %3 (Local)
Runtime state consistent with settings: %4
Newest Leap Seconds List (Local):
%5
System Tick Count: %6.

For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>273</td><td>A leap second will be %1 at %2 UTC (%3 local time). The local system data on this leap second matches with the data from the time provider %4.
System Tick Count: %5.

For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>274</td><td>The time provider %4 has signaled a leap second should be %1 at %2 UTC (%3 local time). However, there is no matching local system data. Please make sure you are synchronizing time from a time source that supports leap seconds and apply the latest Windows patches to avoid seeing this message.
System Tick Count: %5.

For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>275</td><td>Per configuration, W32time service attempted to add a leap second %1 UTC to local settings. Result: %2. System Tick Count: %3.

For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>276</td><td>The local system data indicates that a leap second will be %1 at %2 UTC (%3 local time). This information is not corroborated by the current chosen time provider %4. W32time service will update the system data to excude this leap second. Please make sure you are synchronizing time from a time source that supports leap seconds and ensure you have applied the latest Windows patches. System Tick Count: %5.

For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>279</td><td>W32time could not update the local system time data on leap seconds. Please make sure you are synchronizing time from a time source that supports leap seconds and ensure you have applied the latest Windows patches. System Tick Count: %1.

For more information, see https://go.microsoft.com/fwlink/?linkid=845961.</td></tr>
<tr><td>Microsoft-Windows-Time-Service</td><td>280</td><td>Error %1 registering an RPC endpoint.  Please restart the Windows Time Service for it to become fully functional.</td></tr>
</table>
