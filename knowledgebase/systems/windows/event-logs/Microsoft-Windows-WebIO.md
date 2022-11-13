# Microsoft-Windows-WebIO

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>1</td><td>%1: WebInitialize completed successfully (ApiVersion %3) (Flags %4) -&gt; (API Handle = %2).</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2</td><td>WebInitialize failed with an error = %5 (ApiVersion %3) (Flags %4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>3</td><td>%1 WebTerminate completed successfully. (Handle %2) (Flags %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>4</td><td>%1 WebTerminate failed with an error = %4. (Handle %2) (Flags %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>5</td><td>%3: WebCreateSession completed successfully. (ApiHandle %1[%2]) (Flags: %5) -&gt; (Session Handle: %4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>6</td><td>%1: WebCreateSession failed with an error = %6. (ApiHandle %1[%2]) (Flags: %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>7</td><td>%1: WebCloseSession called (Handle %2) (Flags %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>8</td><td>%1: WebCloseSession failed with an error = %4. (Handle %2) (Flags %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>9</td><td>%2(%1) API called.</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>10</td><td>%2(%1) API returned successfully.</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>11</td><td>%2(%1) API failed with an error = %3.</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>12</td><td>%2(%1) API pending completion.</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>13</td><td>%2(%1) API completed.</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>14</td><td>%2(%1) API completed with an error = %3.</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>15</td><td>%1: Set Request Option %3 (Handle %2) (Error %6) (Length %4) (Value %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>17</td><td>%1: WebCreateHttpRequest completed successfully. (Session %3[%4]) (Method %5) (URI %6) (Version %7.%8) -&gt; (Request Handle %2)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>18</td><td>%3: WebCreateHttpRequest failed with error: %9. (Session %3[%4]) (Method %5) (URI %6) (Version %7.%8)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>19</td><td>%1: WebCloseHttpRequest called (Handle %2) (Flags %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>20</td><td>%1 WebCloseHttpRequest failed with an error = %4. (Handle %2) (Flags %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>21</td><td>Synchronous API Event Handle Signall (Event %2) (Error %3) (Information %4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>22</td><td>Synchronous API Event Handle Wait Completed (Handle %1) (Event %2) (Error %3) (Information %4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>23</td><td>%1: WebSetHttpRequestInformationRoutine completed successfully. (Handle %2) (Flags %3) (InformationRoutine %4) (InformationContext %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>24</td><td>%1: WebSetHttpRequestInformationRoutine failed with an error = %6. (Handle %2) (Flags %3) (InformationRoutine %4) (InformationContext %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>25</td><td>%1: WebRemoveHttpRequestInformationRoutine completed successfully. (Handle %2) (Flags %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>26</td><td>%1: WebRemoveHttpRequestInformationRoutine failed with an error = %6. (Handle %2) (Flags %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>27</td><td>%1: Indicating informational callback to request. (PendingCount %2) (InformationRoutine %3) (InformationContext %4) (Type %5) (Information %6) (InformationLength %7</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>28</td><td>%1: Informational callback to request complete. (PendingCount %2) (InformationRoutine %3) (InformationContext %4) (Type %5) (Information %6) (InformationLength %7</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>29</td><td>%1: WebCloseSession completed successfully. (Handle %2) (Flags %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>30</td><td>%1: WebCloseHttpRequest completed sucessfully error = %4. (Handle %2) (Flags %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>100</td><td>%1: Sending Headers: %3</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>101</td><td>%1: Received Headers: %3</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>102</td><td>%1: Starting Proxy Resolution</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>103</td><td>%1: Completed Proxy Resolution</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>104</td><td>%1: Acquired a connection slot (ConnMgr: %2), (Connection: %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>105</td><td>%1: Request on Endpoint (Server Endpoint: %2) (Proxy Endpoint: %3) (Connection Manager: %4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>106</td><td>%1: Request Message Generated (DataChunk %2[%3])</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>107</td><td>%1: WebSendHttpRequestEntity (Handle: %2) (Flags: %3) (DataChunks %4 [%5]) CompletionContext (%6)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>108</td><td>%1: WebSendHttpRequestEntity Inline Completion (Handle: %2) (Error: %7) (Flags: %3) (DataChunks %4 [%5]) CompletionContext (%6)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>109</td><td>%1: HTTP Queuing Entity for Sending (DataChunks %2) (ChunkLength %3) (IsEntity %4) (All Entity Posted? %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>110</td><td>%1: HTTP Sending Entity (Connection: %2) (DataChunks %3) (PendingSendCount %4) (LastSend? %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>111</td><td>%1: HTTP Send Entity Details (Connection: %2) (DataChunks %3) (Index %4) (Buffer %5 [%6]) Data: %7</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>112</td><td>%1: HTTP Sending Entity Complete (Error %6) (Connection: %2) (DataChunks %3) (PendingSendCount %4) (LastSend? %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>113</td><td>%1: Completing WebSendHttpRequest(Entity) (DataChunks %2) (Error %3) (CompletionContext %4) (CompletionInformation %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>114</td><td>%1: Completing WebSendHttpRequest(Entity) Complete (DataChunks %2)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>115</td><td>%1: WebHttpReceiveEntityBody (Handle: %2) (Flags: %3) (DataChunks %4 [%5]) CompletionContext (%6)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>116</td><td>%1: WebHttpReceiveEntityBody Inline Completion (Handle: %2) (Error: %7) (Flags: %3) (DataChunks %4 [%5]) CompletionContext (%6)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>117</td><td>%1: Completing WebHttpReceiveEntityBody (DataChunks %2) (Error %3) (CompletionContext %4) (CompletionInformation %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>118</td><td>%1: Completing WebHttpReceiveEntityBody Complete (DataChunks %2)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>119</td><td>%1: HTTP Connection changing Buffer (OldBuffer %2 [%3]) (NewBuffer %5 [%6]) (Carryover %4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>120</td><td>%1: HTTP Connection Buffer Posting Receive (DataChunks %2) (Buffer: %3 [%4/%5/%6])</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>121</td><td>%1: HTTP Connection Buffer Completing Receive (DataChunks %2) (Buffer: %3 [%4/%5/%6]) (Error %7)  (CompletionInformation %8)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>122</td><td>%1: HTTP Connection Buffer Receive Details (DataChunks %2) (Length %3) Data: %4</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>123</td><td>%1: HTTP Parser (Connection %2) (Buffer: %3 [%4/%5/%6]) (ParserChunk %7 [%8])</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>124</td><td>%1: HTTP Parser Complete (Connection %2) (Error %9) (Buffer: %3 [%4/%5/%6]) (ParserChunk %7 [%8])</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>125</td><td>%1: HTTP Parser Reset (Buffer %2) (HttpResponseCode %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>126</td><td>%1: HTTP Receive From Parser (DataChunk %2) (ParserChunk %3 [%4]) (Error %5) (Context %6) (Information %7)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>127</td><td>%1: HTTP Receive (DataChunk %2) (BytesToRecv %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>128</td><td>%1: HTTP Receive Complete (DataChunk %2) (BytesToRecv %3) (Error %4) (Context %5) (Information %6)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>129</td><td>%1: HTTP Receive Entity Details (DataChunk %2) (Index %3) (Length %4) Data %5</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>130</td><td>%1: WebSendHttpRequest (Handle: %2) (Flags: %3) (DataChunks %4 [%5]) CompletionContext (%6)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>131</td><td>%1: WebSendHttpRequest Inline Completion (Handle: %2) (Error: %7) (Flags: %3) (DataChunks %4 [%5]) CompletionContext (%6)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>132</td><td>%1: WebHttpReceiveResponse (Handle: %2) (Flags %3) (ResponseFlags %4) CompletionContext (%5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>133</td><td>%1: WebHttpReceiveEntityBody Inline Completion (Handle: %2) (Error: %6) (Flags: %3) (ResponseFlags %4) CompletionContext (%5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>134</td><td>%1: Completing WebHttpReceiveEntityBody (Error %3) (ResponseFlags %2) (CompletionInformation %4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>135</td><td>%1: Completing WebHttpReceiveEntityBody Complete</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>136</td><td>%1: WebCancelHttpRequest (Handle: %2) (Flags %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>137</td><td>%1: WebCancelHttpRequest Complete (Error: %4) (Handle: %2) (Flags %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>200</td><td>%1: Connecting (Socket %2) (Context %5) (RemaingAddress %6) Address: %4.</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>201</td><td>%1: Connection established (Socket %2) (Context %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>202</td><td>%1: Connect failed with error %7 (Socket %2) (Context %5) (RemaingAddress %6)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>203</td><td>Socket %2 created on Endpoint %1.</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>204</td><td>%1: Socket %2 Closed (Reason = %3, Status = %4).</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>205</td><td>%1: Name Resolution Request (Name %2) (Timeout %3) (CompletionContext: %4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>206</td><td>%1: Name Resolution Request Completed (FQDN %2) (Canonical %3) (AddressCount: %4) AddressData: %6</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>207</td><td>%1: Name Resolution Request Failed (Error %2)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>208</td><td>%1: Name Resolution Request queued to %2</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>209</td><td>%1: Name Resolution Request is cancelled</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>210</td><td>%1: Name Resolution Request Timed-out</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>211</td><td>%1: Resolving addresses (Host %2) (Flags: %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>212</td><td>%1: Address resolution completed (Error = %4) (Host %2) (Flags: %3).(AddressCount %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>213</td><td>%1: Winsock Send Entity Start(DataChunks %2) (Socket %3) (Buffers %4) (Context %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>214</td><td>%1: Winsock Send Entity Complete (Error %6) (Information %7) (Socket %3) (Buffers %4) (Context %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>215</td><td>%1: Winsock Recv Entity Start (DataChunks %2) (Socket %3) (Buffers %4) (Context %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>216</td><td>%1: Winsock Recv Entity Complete(Error %6) (Information %7) (Socket %3) (Buffers %4) (Context %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>700</td><td>%1: InitializeSecurityContext - Credential Handle(%2:%3) Context Handle (%4:%5) (Hostname %6) (InputFlags %7) (Buffer %8 [%9/%10])</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>703</td><td>%1: InitializeSecurityContext returned - (%14) Credential Handle(%2:%3) Context Handle (%4:%5) (OutputFlags %11) (Buffer %8 [%9/%10]) (DataChunk %12 [%13])</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>704</td><td>%1: InitializeSecurityContext Details (Pre) - Credential Handle(%2:%3) (Buffer %4 [%5/%6]) Data: %7</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>705</td><td>%1: InitializeSecurityContext Details (Post) - Credential Handle(%2:%3) (DataChunk %4 [%5]) Data: %6</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>706</td><td>%1: SSL Encryption (SSLIOContext %2) Context Handle(%3:%4) (DataChunks: %5) (Index: %6) (OutBuffer: %7[%8]) (Flags %9)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>707</td><td>%1: SSL Encryption Complete (SSLIOContext %2) (ErrorCode: %10) Context Handle(%3:%4) (DataChunks: %5) (Index: %6) (InBuffer: %7[%8]) (Flags %9)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>708</td><td>%1: SSL Encryption Failed (SSLIOContext %2) (ErrorCode: %10) Context Handle(%3:%4) (DataChunks: %5) (Index: %6) (Flags %9) </td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>709</td><td>%1: SSL Encryption Details (SSLIOContext %2) Context Handle(%3:%4) (DataChunks: %5) (Index: %6) (OutBuffer: %7[%8]) (Flags %9) Data:%10</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>710</td><td>%1: SSL Queue Send Entity (SSLIOContext %2) (DataChunks: %3) (RequestDisconnect? %4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>711</td><td>%1: SSL Send Entity Complete (SSLIOContext: %2) (Error: %5) (DataChunks: %3) (RequestDisconnect? %4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>712</td><td>%1: SSL Cert Validation - (Error: %6) Context Handle(%2:%3) (IgnoredServerCertErrors %4) (CertErrors %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>713</td><td>%1: SSL Cert Validation Failure - %7 (Error: %6) Context Handle(%2:%3) (IgnoredServerCertErrors %4) (CertErrors %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>720</td><td>%1: SSL Queue Recv Entity Data Chunk (SSLIOContext %2) (DataChunks: %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>721</td><td>%1: SSL Filling Up Recv Entity Data Chunk (SSLIOContext: %2) (DataChunks: %3) (PlainData %4[%5]) (Information: %6)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>722</td><td>%1: SSL Decryption - Context Handle(%2:%3) (Buffer %4[%5/%6]) (PlainData %7[%8])</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>723</td><td>%1: SSL Decryption Complete (SecStatus %9) (Error %10) Context Handle(%2:%3) (Buffer %4[%5/%6]) (PlainData %7[%8])</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>724</td><td>%1: SSL Receive Buffer Posting Receive (DataChunk %2) (Buffer %3[%4/%5])</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>725</td><td>%1: SSL Receive Buffer Receive Complete (DataChunk %2) (Error %7) (Information %6) (Buffer %3[%4/%5])</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>726</td><td>%1: SSL Receive Buffer Details: (Buffer %2[%3/%4]) Data: %5</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>727</td><td>%1: SSL Receive Buffer Posting Receive (Buffer %2) (NewBuffer: %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>728</td><td>%1: SSL AcquireCredentialsHandle - (EnabledProtocols %2) (ClientCert %3) (EnableRevertToSelfClientCertificate %4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>728</td><td>%1: SSL AcquireCredentialsHandle - (EnabledProtocols %2) (ClientCert %3) (EnableRevertToSelfClientCertificate %4) (CipherConfig %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>729</td><td>%1: SSL AcquireCredentialsHandle returned - (%7) Credential Handle(%5:%6) (EnabledProtocols %2) (ClientCert %3) (EnableRevertToSelfClientCertificate %4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>729</td><td>%1: SSL AcquireCredentialsHandle returned - (%8) Credential Handle(%6:%7) (EnabledProtocols %2) (ClientCert %3) (EnableRevertToSelfClientCertificate %4) (CipherConfig %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>730</td><td>%1: SSL AcquireCredentialsHandle failed - (%7) (EnabledProtocols %2) (ClientCert %3) (EnableRevertToSelfClientCertificate %4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>730</td><td>%1: SSL AcquireCredentialsHandle failed - (%8) (EnabledProtocols %2) (ClientCert %3) (EnableRevertToSelfClientCertificate %4) (CipherConfig %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>900</td><td>%1: WebCompleteProtocolUpgrade completed successfully. (Handle %2) (Request %3[%4]) (Session %5[%6])</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>901</td><td>%1: WebCompleteProtocolUpgrade failed with error: %7. (Handle %2) (Request %3[%4]) (Session %5[%6])</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>902</td><td>%1: WebProtocolCancelHandle (Handle: %2)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>903</td><td>%1: WebProtocolCancelHandle Complete (Error: %3) (Handle: %2)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>904</td><td>%1: WebCloseProtocolHandle called (Handle %2)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>905</td><td>%1: WebCloseProtocolHandle completed (Error %4) (Handle %2)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>906</td><td>%1: Set Protocol Option %3 (Handle %2) (Error %6) (Length %4) (Value %5)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>907</td><td>%1: WebProtocolSendData (Handle: %2) (Flags: %3) (DataChunks %4 [%5]) CompletionContext (%6)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>908</td><td>%1: WebProtocolSendData Inline Completion (Handle: %2) (Error: %7) (Flags: %3) (DataChunks %4 [%5]) CompletionContext (%6)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>909</td><td>%1: Completing WebProtocolSendData (Handle: %2) (Error: %3) CompletionContext (%4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>910</td><td>%1: Completing WebProtocolSendData Complete (Handle: %2) (Error: %3) CompletionContext (%4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>911</td><td>%1: WebProtocolReceiveData (Handle: %2) (Flags: %3) (DataChunks %4 [%5]) CompletionContext (%6)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>912</td><td>%1: WebProtocolReceiveData Inline Completion (Handle: %2) (Error: %7) (Flags: %3) (DataChunks %4 [%5]) CompletionContext (%6)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>913</td><td>%1: Completing WebProtocolReceiveData (Handle: %2) (Error: %3) CompletionContext (%4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>914</td><td>%1: Completing WebProtocolReceiveData Complete (Handle: %2) (Error: %3) CompletionContext (%4)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2100</td><td>%1: =====Request Initialize===================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2101</td><td>%1: =====Query Endpoints======================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2102</td><td>%1: =====Waiting For Available Connection=====</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2111</td><td>%1: =====Request Connect======================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2112</td><td>%1: =====Name Resolution======================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2113</td><td>%1: =====TCP Connect==========================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2114</td><td>%1: =====SSL Negotiation======================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2120</td><td>%1: =====Generate Headers=====================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2121</td><td>%1: =====Send Headers=========================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2122</td><td>%1: =====Send Entity==========================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2123</td><td>%1: =====Send Complete========================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2130</td><td>%1: =====Receive Headers======================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2131</td><td>%1: =====Receive Entity=======================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2132</td><td>%1: =====Receive Complete=====================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2140</td><td>%1: =====Request Restart======================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>2141</td><td>%1: =====Request Done=========================</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>59992</td><td>Restore Thread Token %1 (Error: %2)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>59993</td><td>Set Thread Token %1 (OldToken %2) (Error: %3)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>59994</td><td>Get Thread Token %1 (Error: %3) (SID: %2)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>59995</td><td>Canceling %2 Thread Action (Context: %1)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>59996</td><td>Queue %2 Thread Action (Context: %1)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>59997</td><td>Stopping %2 Thread Action (Context: %1)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>59998</td><td>Starting %2 Thread Action (Context: %1)</td></tr>
<tr><td>Microsoft-Windows-WebIO</td><td>59999</td><td>%2</td></tr>
</table>
