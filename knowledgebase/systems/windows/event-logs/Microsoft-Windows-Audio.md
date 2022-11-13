# Microsoft-Windows-Audio

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Audio</td><td>0</td><td>Windows Audio encountered an error while processing a device event.
                    Event ID     : 0x%1 (%2) 
                    Failure Code : 0x%3</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>1</td><td>Windows Audio encountered an error while processing a device event.
                    DeviceEventType : 0x%1 (%2) 
                    Failure Code    : 0x%3</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>2</td><td>Windows Audio failed during a call to SetServiceStatus.
                    Service Type               : 0x%1 
                    Current State              : 0x%2 
                    Controls Accepted          : 0x%3 
                    Win32 Exit Code            : 0x%4 
                    Service Specific Exit Code : 0x%5 
                    Check Point                : 0x%6 
                    Wait Hint                  : 0x%7</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>3</td><td>Windows Audio failed to start the %1 subsystem.
                    Subsystem Failure Code     : 0x%2 
</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>4</td><td>The Windows Audio Device Graph Isolation process (audiodg.exe) has terminated unexpectedly.
                    Process Exit Code     : 0x%1 
</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>5</td><td>The Windows Audio Device Graph Isolation process (audiodg.exe) could not be started.
                    Error Code     : 0x%1 
</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>10</td><td>The Capture Monitor has failed to restart the capture monitor between %2 and %3  %1 times.  
                 The capture monitor will no longer attempt to start this monitor.
</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>11</td><td>StreamFlags %1</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>12</td><td></td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>13</td><td></td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>14</td><td></td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>15</td><td></td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>16</td><td></td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>17</td><td></td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>18</td><td>Windows Audio Device Graph glitch threshold count exceeded 
                              Count   : 0x%1</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>19</td><td>Windows Audio Device Graph glitch threshold count exceeded 
                              Count   : 0x%1</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>20</td><td>Format: %1
Sampling rate: %2Hz
Offloaded: %3</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>21</td><td>Sound level for application [%1] changed to [%2]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>22</td><td>Suspended: %1</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>23</td><td>Released exclusive mode resource %1
Released offload mode resource %2</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>24</td><td>Stream started.
App Id: %1
PID: %2
Audio Stream Category: %3</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>25</td><td>Stream stopped.
App Id: %1
PID: %2
Audio Stream Category: %3</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>26</td><td>Capture Monitor Render Glitch: pCMonitor=[%1], DevicePosition=[%2], QPCPosition=[%3]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>27</td><td>Capture Monitor Capture Glitch: pCMonitor=[%1], DevicePosition=[%2], QPCPosition=[%3]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>28</td><td>APO Glitch: Format Converter INF detected: pCAudioFormatConvert=[%1], [%2]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>29</td><td>Engine Glitch: CP Client Input Endpoint - pCCrossProcessClientInputEndpoint=[%1] No Messages in queue</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>30</td><td>Engine Glitch: CP Client Input Endpoint - pCCrossProcessClientInputEndpoint=[%1] Queue item does not match requested size</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>31</td><td>Engine Glitch: CP Client Output Endpoint - Server Overread: pCCrossProcessClientOutputEndpoint=[%1] WritePos=[%2] ReadPos=[%3] BytesToWrite=[%4]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>32</td><td>Engine Glitch: CP Client Output Endpoint - Read Pointer Overwrite: pCCrossProcessClientOutputEndpoint=[%1] WriteOffset=[%2] ReadOffset=[%3] BytesToWrite=[%4] EndOfDataOffset=[%5]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>33</td><td>Engine Glitch: CP Server Input Endpoint - Starvation: pCCrossProcessServerInputEndpoint=[%1] WriteOffset=[%2] ReadOffset=[%3] BufferSize=[%4] BytesAvail=[%5]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>34</td><td>Engine Glitch: CP Server Output Endpoint - Queue Full Packet Drop: pCCrossProcessServerOutputEndpoint=[%1] WritePos=[%2] DroppedBytes=[%3] ReadPos=[%4] BytesToWrite=[%5]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>35</td><td>Engine Glitch: CP Server Output Endpoint - Read Pointer Overwrite: pCCrossProcessServerOutputEndpoint=[%1] WriteOffset=[%2] ReadOffset=[%3] BytesToWrite=[%4]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>36</td><td>KS Endpoint Glitch: IOMGR No Outstanding Packets: pOwner=[%1] NextStreamingPacketToComplete=[%2] MaxPacketCount=[%3]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>37</td><td>KS Endpoint Glitch: IOMGR Ioctl Time Limit Exceeded: pOwner=[%1] DeltaHNS=[%2]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>38</td><td>KS Endpoint Glitch: BASE Output Unexpected Buffer Completed: pCAudioBasePin=[%1] LockedDataPointer=[%2] bLockedEqualsUnrolled=[%3]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>39</td><td>KS Endpoint Glitch: BASE Input Null Last Buffer with LockedData != LoopedBuffer: pCAudioBasePin=[%1] LockedDataPointer=[%2]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>40</td><td>KS Endpoint Glitch: BASE Input Buffer Index Mismatch: pCAudioBasePin=[%1] LockedDataPointer=[%2]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>41</td><td>KS Endpoint Glitch: BASE End Glitch: pCAudioBasePin=[%1] StreamPosition=[%2] GlitchDuration=[%3]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>42</td><td>KS Endpoint Glitch: RTCAP StreamPos Ahead of HW Pos: pCAudioCapturePinRealtimeStreaming=[%1] WritePos=[%2] PlayPos=[%3] StreamPos=[%4] StreamPosMinusReadPos=[%5]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>43</td><td>KS Endpoint Glitch: RTCAP StreamPos Too Far Behind: pCAudioCapturePinRealtimeStreaming=[%1] WritePos=[%2] PlayPos=[%3] StreamPos=[%4] ReadPosMinusStreamPos=[%5]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>44</td><td>KS Endpoint Glitch: RTREN WritePos Exceeds TotalPos: pCAudioRenderPinRealtimeStreaming=[%1] WritePos=[%2] PlayPos=[%3] TotalPos=[%4] WritePosMinusTotalPos=[%5]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>45</td><td>KS Endpoint Glitch: STCAP Capture Ahead: pCAudioCapturePinStandardStreaming=[%1] ValidPosEnd=[%2] ValidPosStart=[%3] StreamPos=[%4] StreamPosMinusValidPosEnd=[%5]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>46</td><td>KS Endpoint Glitch: STCAP Capture Behind: pCAudioCapturePinStandardStreaming=[%1] ValidPosEnd=[%2] ValidPosStart=[%3] StreamPos=[%4] ValidPosStartMinusStreamPos=[%5]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>47</td><td>KS Endpoint Glitch: STCAP Device Starved: pCAudioCapturePinStandardStreaming=[%1] StreamPos=[%2] FrameCount=[%3]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>48</td><td>KS Endpoint Glitch: STREN Device Starved: pCAudioRenderPinStandardStreaming=[%1] DevicePos=[%2] StreamPos=[%3] AvailFrames=[%4]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>49</td><td>KS Endpoint Glitch: STREN EXCL PULL Invalid Buffer Count: pCAudioRenderPinStandardStreaming=[%1] DevicePos=[%2] StreamPos=[%3] AvailFrames=[%4]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>50</td><td>System effect initialized: CLSID=[%1] AudioSignalProcessingMode=[%2] InitializeForDiscoveryOnly=[%3]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>51</td><td>Volume limit event signalled to audiosrv enter</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>52</td><td>Volume limit event signalled to audiosrv exit</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>53</td><td>AudioSrv published AVLC state</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>58</td><td>MMDevAPI: Default device changed triggered</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>59</td><td>MMDevAPI: OnMediaNotification Enter</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>60</td><td>MMDevAPI: OnMediaNotification Exit</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>61</td><td>MMDevAPI: DeviceStateChanged callback</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>62</td><td>MMDevAPI: DeviceAdded callback</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>63</td><td>MMDevAPI: DeviceRemoved callback</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>64</td><td>MMDevAPI: DefaultDeviceChanged callback</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>65</td><td>MMDevAPI: Audio device state changed</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>101</td><td>MidiRT: Application Suspension Handler</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>102</td><td>MidiRT: Application Resume Handler</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>103</td><td>MidiRT: Application Entering CS Handler</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>104</td><td>MidiRT: Application Resuming from CS Handler</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>105</td><td>MidiRT: Device Removal Handler</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>106</td><td>MidiRT: Cleanup and release device handle</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>107</td><td>MidiRT: Close handle to MIDI Device</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>108</td><td>MidiRT: Begin binding to DeviceId: %1</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>109</td><td>MidiRT: Done binding to device interface</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>110</td><td>MidiRT: Create new MidiPortDeviceIoControl</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>111</td><td>MidiRT: Beginning Synchronous I/O</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>112</td><td>MidiRT: Done with synchronous I/O</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>113</td><td>MidiRT: Beginning Asynchronous I/O</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>114</td><td>MidiRT: Done with Asynchronous I/O</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>115</td><td>CrossProcess packet added</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>116</td><td>Pump: setting deadline</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>117</td><td>Pump: cancelling deadline</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>118</td><td>Pump: missed deadline!</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>119</td><td>Pump: Start - setting MultimediMode to AVRT_MULTIMEDIA_MODE_BUFFERING</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>120</td><td>Pump: Stop - setting MultimediMode to AVRT_MULTIMEDIA_MODE_IDLE</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>121</td><td>Discovering EndpointCharacteristics for [%1]</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>122</td><td>Discovered EndpointCharacteristics for [%1] (hr = %2)</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>123</td><td>GetMixFormat starting on endpoint [%1] (category=%2, raw=%3, matchformat=%4, connector=%5)</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>124</td><td>GetMixFormat ended</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>125</td><td>IsFormatSupported starting on endpoint [%1] (category=%2, raw=%3, matchformat=%4, connector=%5)</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>126</td><td>IsFormatSupported ended</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>127</td><td>Vadserver_CreateStream starting on endpoint [%1] (category=%2, raw=%3, matchformat=%4, connector=%5)</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>128</td><td>Vadserver_CreateStream ended</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>129</td><td>Derived stream settings for stream</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>130</td><td>Created StreamGroup and stream</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>131</td><td>Created SaDevice</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>132</td><td>Connected StreamGroup to SaDevice</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>133</td><td>CreateDeviceEndpointInstance starting on endpoint [%1] (connector=%2)</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>134</td><td>CreateDeviceEndpointInstance ended</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>135</td><td>Pump: Correct Position</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>136</td><td>Pump: Start - Yield start</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>137</td><td>Pump: Stop - Yield stop</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>138</td><td>Pump: Start - Process start</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>139</td><td>Pump: Stop - Process stop</td></tr>
<tr><td>Microsoft-Windows-Audio</td><td>140</td><td>Pump: ProcPassDuration</td></tr>
</table>
