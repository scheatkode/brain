# Microsoft-Windows-SMBDirect

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>1</td><td>The network adapter &#39;%1&#39; is incompatible with SMB Direct. Compatible network adapters are required to support at least %2 SGE(s) per receive queue work request. This adapter supports a maximum of %3 SGE(s) per receive queue work request.</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>2</td><td>The network adapter &#39;%1&#39; is incompatible with SMB Direct. Compatible network adapters are required to support at least %2 SGE(s) per send queue work request. This adapter supports a maximum of %3 SGE(s) per send queue work request.</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>3</td><td>The network adapter &#39;%1&#39; is incompatible with SMB Direct. Compatible network adapters are required to support at least %2 SGE(s) per RDMA read request. This adapter supports a maximum of %3 SGE(s) per RDMA read request.</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>4</td><td>Setting %1\%2 is invalid. Verify that %2 is a DWORD (32-bit) value in the range %3 to %4 (inclusive). The default value of %5 will be used for this setting until the error is corrected.</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>5</td><td>The network adapter &#39;%1&#39; does not support a value of %4 for setting %2\%3. The closest adapter supported value of %5 will be used.</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>6</td><td>A connection has been terminated because no pending requests to network adapter &#39;%6&#39; have completed in the last %7 milliseconds. Verify that the network is operational and that the peer is responsive. This event may also indicate that there are insufficient send credits to support the workload. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>7</td><td>Settings BaseAffinityNode and MaxAffinityNode (\Registry\Machine\System\CurrentControlSet\Services\SmbDirect\Parameters) must specify a set of NUMA nodes that contain active processors. All of the system&#39;s processors will be eligible to perform SMB Direct processing until the error is corrected.</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>300</td><td>Starting connect. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>301</td><td>Connect succeeded. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>302</td><td>Connect failed. Socket = %1 Local = %3 Remote = %5 Status = %6</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>303</td><td>Timed out while waiting for connection establishment to complete - cancelling connect. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>304</td><td>NdkConnect failed. Socket = %1 Local = %3 Remote = %5 Status = %6</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>305</td><td>NdkCompleteConnect failed. Socket = %1 Local = %3 Remote = %5 Status = %6</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>306</td><td>Failed to negotiate a common SMB Direct version with the peer. Socket = %1 Local = %3 Remote = %5 MinVersion = %6 MaxVersion = %7 PeerMinVersion = %8 PeerMaxVersion = %9</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>350</td><td>Received connect request. ListenSocket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>351</td><td>Rejected connect request - connect backlog limit exceeded. ListenSocket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>352</td><td>Rejected connect request - not enough memory. ListenSocket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>353</td><td>Timed-out while waiting to receive a negotiate request - cancelling accept. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>354</td><td>NdkAccept failed. Socket = %1 Local = %3 Remote = %5 Status = %6</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>355</td><td>Accept started. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>356</td><td>Accept succeeded. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>357</td><td>Accept failed. Socket = %1 Local = %3 Remote = %5 Status = %6</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>358</td><td>Upper-level driver rejected the connection. Socket = %1 Status = %2</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>400</td><td>NDK disconnect event. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>401</td><td>Disconnect started. Socket = %1 Local = %3 Remote = %5 State = %6</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>402</td><td>Disconnect completed. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>403</td><td>Close started. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>404</td><td>Close completed. Socket = %1</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>450</td><td>Out of send credits - starting credit grant timer. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>451</td><td>Peer used their last send credit. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>452</td><td>Using last send credit. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>453</td><td>Timed-out while waiting to receive send credits. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>454</td><td>Protocol violation - the peer sent a packet but does not have a send credit. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>455</td><td>Protocol violation - the peer used their last send credit but did not grant a send credit. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>456</td><td>Granted the peer %6 additional send credits. Socket %1 Local = %3 Remote = %5 PeerSendCredits = %7</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>457</td><td>Received a grant of %6 credits. Socket = %1 Local = %3 Remote = %5 SendCreditsAccepted = %7 SendCredits = %8</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>500</td><td>Failed to post a %6 SQ work request. Socket = %1 Local = %3 Remote = %5 Status = %7</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>501</td><td>%6 SQ work request failed. Socket = %1 Local = %3 Remote = %5 Status = %7</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>502</td><td>Failed to post a Receive work request. Socket = %1 Local = %3 Remote = %5 Status = %6</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>503</td><td>Receive work request failed. Socket = %1 Local = %3 Remote = %5 Status = %6</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>1000</td><td>Timed-out out while waiting to receive a keepalive response. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>1001</td><td>Protocol violation - received packet is too small or contains at least one invalid value. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>1002</td><td>Protocol violation - total fragmented payload is larger than indicated by first fragment. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>1003</td><td>Protocol violation - total fragmented payload is smaller than indicated by first fragment. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>1004</td><td>Failed to allocate a fragment reassembly buffer. Socket = %1 Local = %3 Remote = %5</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>1005</td><td>%6 operation failed. Socket = %1 Local = %3 Remote = %5 Status = %7</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>1006</td><td>Created socket. Socket = %1</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>1007</td><td>Failed to create socket. Socket = %1 Status = %2</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>1008</td><td>Finished negotiating connection properties. Socket = %1 Local = %3 Remote = %5 ProtocolVersion = %6 MaxReadWriteSize = %7 MaxReceiveSize = %8 MaxFragmentedReceiveSize = %9 MaxSendSize = %10 MaxFragmentedSendSize = %11 IRD = %12 ORD = %13</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>1009</td><td>A completion queue has failed and is no longer indicating completions. Socket = %1 Local = %3 Remote = %5 Status = %6</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>1010</td><td>Updated SCQ interrupt moderation parameters. Socket = %1 Count = %2 IntervalInMicroSeconds = %3</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>1011</td><td>Updated RCQ interrupt moderation parameters. Socket = %1 Count = %2 IntervalInMicroSeconds = %3</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>9500</td><td>Opened network adapter &#39;%1&#39;. NdkMajorVer = %2 NdkMinorVer = %3 VendorId = %4 DeviceId = %5 MaxRegistrationSize = %6 MaxWindowSize = %7 FrmrPageCount = %8 MaxInitiatorRequestSge = %9 MaxReceiveRequestSge = %10 MaxReadRequestSge = %11 MaxTransferLength = %12 MaxInlineDataSize = %13 MaxInboundReadLimit = %14 MaxOutboundReadLimit = %15 MaxReceiveQueueDepth = %16 MaxInitiatorQueueDepth = %17 MaxSrqDepth = %18 MaxCqDepth = %19 LargeRequestThreshold = %20 MaxCallerData = %21 MaxCalleeData = %22 AdapterFlags = %23</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>10000</td><td>Received negotiate request. Socket = %1 Local = %3 Remote = %5 MinVersion = %6 MaxVersion = %7 Reserved = %8 CreditsRequested = %9 PreferredSendSize = %10 MaxReceiveSize = %11 MaxFragmentReassemblyBufferSize = %12</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>10001</td><td>Sending negotiate request. Socket = %1 Local = %3 Remote = %5 MinVersion = %6 MaxVersion = %7 Reserved = %8 CreditsRequested = %9 PreferredSendSize = %10 MaxReceiveSize = %11 MaxFragmentReassemblyBufferSize = %12</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>10002</td><td>Received negotiate response. Socket = %1 Local = %3 Remote = %5 MinVersion = %6 MaxVersion = %7 NegotiatedVersion = %8 Reserved = %9 CreditsRequested = %10 CreditsGranted = %11 Status = %12 MaxReadWriteSize = %13 PreferredSendSize = %14 MaxReceiveSize = %15 MaxFragmentReassemblyBufferSize = %16</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>10003</td><td>Sending negotiate response. Socket = %1 Local = %3 Remote = %5 MinVersion = %6 MaxVersion = %7 NegotiatedVersion = %8 Reserved = %9 CreditsRequested = %10 CreditsGranted = %11 Status = %12 MaxReadWriteSize = %13 PreferredSendSize = %14 MaxReceiveSize = %15 MaxFragmentReassemblyBufferSize = %16</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>10004</td><td>Received data. Socket = %1 Local = %3 Remote = %5 CreditsRequested = %6 CreditsGranted = %7 Flags = %8 Reserved = %9 RemainingDataLength = %10 DataOffset = %11 DataLength = %12</td></tr>
<tr><td>Microsoft-Windows-SMBDirect</td><td>10005</td><td>Sending data. Socket = %1 Local = %3 Remote = %5 CreditsRequested = %6 CreditsGranted = %7 Flags = %8 Reserved = %9 RemainingDataLength = %10 DataOffset = %11 DataLength = %12</td></tr>
</table>
