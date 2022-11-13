# Microsoft-Windows-WebAuthN

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1000</td><td>WebAuthN Ctap MakeCredential started.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1001</td><td>WebAuthN Ctap MakeCredential completed.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1002</td><td>WebAuthN Ctap MakeCredential completed.

TransactionId: %1
Error: %2. %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1003</td><td>WebAuthN Ctap GetAssertion started.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1004</td><td>WebAuthN Ctap GetAssertion completed.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1005</td><td>WebAuthN Ctap GetAssertion completed.

TransactionId: %1
Error: %2. %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1006</td><td>WebAuthN Ctap SendCommand started.

TransactionId: %1
Ticket: %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1007</td><td>WebAuthN Ctap SendCommand completed.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1008</td><td>WebAuthN Ctap SendCommand completed.

TransactionId: %1
Error: %2. %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1020</td><td>WebAuthN Ngc MakeCredential started.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1021</td><td>WebAuthN Ngc MakeCredential completed.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1022</td><td>WebAuthN Ngc MakeCredential completed.

TransactionId: %1
Error: %2. %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1023</td><td>WebAuthN Ngc GetAssertion started.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1024</td><td>WebAuthN Ngc GetAssertion completed.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1025</td><td>WebAuthN Ngc GetAssertion completed.

TransactionId: %1
Error: %2. %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1040</td><td>Ngc MakeCredential request.

TransactionId: %1
RpId: %2
AccountId: %3
ClientDataHashAlgId: %4 ClientDataLength: %5 ClientDataHash: %7
ExcludeCredentialCount: %8
CredentialParameterCount: %9</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1041</td><td>Ngc MakeCredential response.

TransactionId: %1
AttestationFormatType: %2
RpIdHash: %4
Flags: %5
SignCount: %6
AAGuid: %7
CredentialId: %9
U2fPublicKey: %10
PublicKey: %12
Response: %14</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1042</td><td>Ngc GetAssertion request.

TransactionId: %1
RpId: %2
ClientDataHashAlgId: %3 ClientDataLength: %4 ClientDataHash: %6
AllowCredentialCount: %7</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1043</td><td>Ngc GetAssertion response.

TransactionId: %1
RpIdHash: %3
Flags: %4
SignCount: %5
CredentialId: %7%</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1060</td><td>WebAuthN error at: %2

TransactionId: %1
Error: %3. %4</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1100</td><td>Cbor decode error.

TransactionId: %1
Function: %2
CborError: %3 %4
ErrorOffset: %5 LineNumber: %6
Encoded: %8</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1101</td><td>Cbor encode MakeCredential request.

TransactionId: %1
RpId: %2
UserId: %4
ClientDataHashAlgId: %5 ClientDataLength: %6 ClientDataHash: %8
RequireResidentKey: %9
ExcludeCredentialCount: %10
CredentialParameterCount: %11
Request: %13</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1102</td><td>Cbor decode MakeCredential response.

TransactionId: %1
AttestationFormatType: %2
RpIdHash: %4
Flags: %5
SignCount: %6
AAGuid: %7
CredentialId: %9
U2fPublicKey: %10
PublicKey: %12
Response: %14</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1103</td><td>Cbor encode GetAssertion request.

TransactionId: %1
RpId: %2
ClientDataHashAlgId: %3 ClientDataLength: %4 ClientDataHash: %6
AllowCredentialCount: %7
Request: %9</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>1104</td><td>Cbor decode GetAssertion response.

TransactionId: %1
RpIdHash: %3
Flags: %4
SignCount: %5
CredentialId: %7
Response: %9</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2000</td><td>Ctap service started successfully.</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2001</td><td>Ctap service stopped successfully.</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2100</td><td>Ctap %1 started.

TransactionId: %2
Flags: %3
TimeoutMilliseconds: %4
Ticket: %6
Request: %8</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2101</td><td>Ctap command started.

Request: %2</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2102</td><td>Ctap %1 completed.

TransactionId: %2
Response: %4</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2103</td><td>Ctap %1 completed.

TransactionId: %2
Error: %3. %4</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2104</td><td>Ctap device info.

TransactionId: %1
ProviderName: %2
DevicePath: %3
Manufacturer: %4
Product: %5
AAGuid: %6
U2fProtocol: %7</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2110</td><td>Ctap device device state info.

Transport Type: %1
WnfState: %2
Error: %3. %4
</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2111</td><td>Ctap device change notify info.

Transport Type: %1
</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2200</td><td>Ctap Usb provider thread started.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2201</td><td>Ctap Usb provider thread completed.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2202</td><td>Ctap Usb provider thread completed.

TransactionId: %1
Error: %2. %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2203</td><td>Ctap Usb provider thread completed.

TransactionId: %1
Error: %2. %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2210</td><td>Ctap Usb device thread started.

TransactionId: %1
DevicePath: %2
Manufacturer: %3
Product: %4</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2211</td><td>Ctap Usb device thread completed.

TransactionId: %1
DevicePath: %2
Manufacturer: %3
Product: %4
AAGuid: %5
U2fProtocol: %6</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2212</td><td>Ctap Usb device thread completed.

TransactionId: %1
DevicePath: %2
Manufacturer: %3
Product: %4
AAGuid: %5
U2fProtocol: %6
State: %7
Status: %8
Error: %9. %10</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2213</td><td>Ctap Usb device thread completed.

TransactionId: %1
DevicePath: %2
Manufacturer: %3
Product: %4
AAGuid: %5
U2fProtocol: %6
State: %7
Status: %8
Error: %9. %10</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2220</td><td>Ctap Usb add device.

TransactionId: %1
DevicePath: %2
Manufacturer: %3
Product: %4</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2221</td><td>Ctap Usb remove device.

TransactionId: %1
DevicePath: %2
Manufacturer: %3
Product: %4</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2222</td><td>Ctap Usb device changes.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2223</td><td>Ctap Usb U2F device.

TransactionId: %1
DevicePath: %2
Manufacturer: %3
Product: %4</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2224</td><td>Ctap Usb connect to device.

TransactionId: %1
DevicePath: %2
Manufacturer: %3
Product: %4
DeviceErr: %5
Status: %6
Error: %7. %8</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2225</td><td>Ctap Usb Send Receive:

TransactionId: %1
Request Command: %2 Response Command: %5
Request: %4
Response: %7</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2226</td><td>Ctap Usb Send Receive:

TransactionId: %1
Request Command: %2 Response Command: %5
Request: %4
Response: %7
Error: %8. %9</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2250</td><td>Ctap Ble provider thread started.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2251</td><td>Ctap Ble provider thread completed.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2252</td><td>Ctap Ble provider thread completed.

TransactionId: %1
Error: %2. %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2253</td><td>Ctap Ble provider thread completed.

TransactionId: %1
Error: %2. %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2260</td><td>Ctap Ble device thread started.

TransactionId: %1
DevicePath: %2
PairedName: %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2261</td><td>Ctap Ble device thread completed.

TransactionId: %1
DevicePath: %2
PairedName: %3
AAGuid: %4
U2fProtocol: %5</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2262</td><td>Ctap Ble device thread completed.

TransactionId: %1
DevicePath: %2
PairedName: %3
AAGuid: %4
U2fProtocol: %5
State: %6
Status: %7
Error: %8. %9</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2263</td><td>Ctap Ble device thread completed.

TransactionId: %1
DevicePath: %2
PairedName: %3
AAGuid: %4
U2fProtocol: %5
State: %6
Status: %7
Error: %8. %9</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2270</td><td>Ctap Ble Function: %1 Location: %2

Error: %3. %4</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2271</td><td>Ctap Ble U2F device.

TransactionId: %1
DevicePath: %2
PairedName: %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2272</td><td>Ctap Ble Send Receive:

TransactionId: %1
Request Command: %2 Response Command: %5
Request: %4
Response: %7</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2273</td><td>Ctap Ble Send Receive:

TransactionId: %1
Request Command: %2 Response Command: %5
Request: %4
Response: %7
Location: %8
Error: %9. %10</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2300</td><td>Ctap Nfc provider thread started.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2301</td><td>Ctap Nfc provider thread completed.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2302</td><td>Ctap Nfc provider thread completed.

TransactionId: %1
Error: %2. %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2303</td><td>Ctap Nfc provider thread completed.

TransactionId: %1
Error: %2. %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2310</td><td>Ctap Nfc reader thread started.

TransactionId: %1
Reader: %2</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2311</td><td>Ctap Nfc reader thread completed.

TransactionId: %1
Reader: %2
AAGuid: %3
U2fProtocol: %4</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2312</td><td>Ctap Nfc reader thread completed.

TransactionId: %1
Reader: %2
AAGuid: %3
U2fProtocol: %4
State: %5
Status: %6
Error: %7. %8</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2313</td><td>Ctap Nfc reader thread completed.

TransactionId: %1
Reader: %2
AAGuid: %3
U2fProtocol: %4
State: %5
Status: %6
Error: %7. %8</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2314</td><td>Ctap Nfc reader manager thread started.

TransactionId: %1
</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2315</td><td>Ctap Nfc reader manager thread completed.

TransactionId: %1
NumberOfTimesScardCancelCommandsSent: %2
</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2316</td><td>Cancelling Reader Threads.

TransactionId: %1
</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2320</td><td>Ctap Nfc add reader.

TransactionId: %1
Reader: %2</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2321</td><td>Ctap Nfc skip reader for: %2.

TransactionId: %1
Reader: %3
DeviceInstanceId: %4</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2322</td><td>Ctap Nfc transition reader for: %2.

TransactionId: %1
Reader: %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2323</td><td>Ctap Nfc send message warning for: %2.

TransactionId: %1
Reader: %3
ApduStatus: %4
DeviceStatus: %5
SmartCardError: %6. %7</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2324</td><td>Ctap Nfc send request error for: %2.

TransactionId: %1
Reader: %3
ApduStatus: %4
DeviceStatus: %5
Error: %6. %7</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2325</td><td>Ctap Nfc U2F device.

TransactionId: %1
Reader: %2</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2326</td><td>Ctap Nfc send message at: %2.

TransactionId: %1
Reader: %3</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2327</td><td>Ctap Nfc SCardTransmit Request:

TransactionId: %1
Reader: %2

Request: %3 bytes
%4

Response data: %5 bytes
%6

Apdu Status: %7
</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2328</td><td>Ctap Nfc SCardTransmit Request:

TransactionId: %1
Reader: %2

Request: %3 bytes
%4

Response data: %5 bytes
%6

Apdu Status: %7

Error: %8. %9</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2400</td><td>Ctap Test provider thread started.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2401</td><td>Ctap Test provider thread completed.

TransactionId: %1</td></tr>
<tr><td>Microsoft-Windows-WebAuthN</td><td>2402</td><td>Ctap Test provider thread completed.

TransactionId: %1
Error: %2. %3</td></tr>
</table>
