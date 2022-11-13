# Microsoft-Windows-HttpService

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>1</td><td>Request received (request ID %1) on connection (connection ID %2) from remote address %4.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>2</td><td>Parsed request (request pointer %1, method %2) with URI %3.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>3</td><td>Delivered request to server application (request pointer %1, request ID %2, site ID %3) from request queue %4 for URI %5 with status %6.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>4</td><td>Server application passed response (request ID %1, connection ID %2, method %4, header length %5, number of entity chunks %6, cache policy %7) with status code %3.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>5</td><td>Server application passed the last response (corresponding to request ID %1).</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>6</td><td>Server application passed entity body for request ID %1 (connection ID %2).</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>7</td><td>Server application passed the last entity body for request ID %1.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>8</td><td>Server application passed response (request ID %1, connection ID %2, method %4, header length %5, number of entity chunks %6, cache policy %7) with status code %3.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>9</td><td>Server application passed the last response (corresponding to request ID %1).</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>10</td><td>Response ready for send (corresponding to request ID %1) with status code %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>11</td><td>Cached the response (corresponding to request ID %1) with status code %2. Response to be sent.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>12</td><td>Queued last response (corresponding to request ID %1) for sending. Status code is %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>13</td><td>Response sent (corresponding to request ID %1) with status code %2. If disconnect is required, a TCP FIN has been sent.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>14</td><td>Error occurred while sending the last response (corresponding to request ID %1) with status code %2. A TCP Reset has been sent.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>15</td><td>Error %3 occurred while sending (corresponding to request ID %1). A TCP Reset will be sent.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>16</td><td>Response (request pointer %1, site ID %2, number of bytes %3) queued for sending from the cache.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>16</td><td>Response (request pointer %1, corresponding to request ID %4, site ID %2, number of bytes %3, encoding %5) queued for sending from the cache.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>17</td><td>Response (request pointer %1, site ID %2, number of bytes %3) queued for sending with status code 304 (cache not modified).</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>17</td><td>Response (request pointer %1, site ID %2, number of bytes %3, encoding %5) queued for sending with status code 304 (cache not modified).</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>18</td><td>Attempted to reserve URL (%1). Status %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>19</td><td>Successfully read the IP listen list for IP address %1.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>20</td><td>SSL credentials for IP address and port %3 successfully created.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>20</td><td>SSL credentials for endpoint %2 successfully created.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>21</td><td>New connection created (local IP address %3 and remote address %5).</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>22</td><td>Connection ID (%2) assigned to connection and request (request ID %1) will be parsed.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>23</td><td>Client closed the connection (connection pointer %1). Status of whether closed by TCP Reset: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>24</td><td>Connection (connection pointer %1) cleanup started due to either the sending of a TCP Reset, receiving of a TCP Reset, or after the mutual exchange of TCP Fins.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>25</td><td>Successfully added entry (URI %1) to cache.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>25</td><td>Successfully added entry (URI %1) to cache (Encoding %7).</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>26</td><td>Failed to add an entry (URI %1) to the cache. Status: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>26</td><td>Failed to add an entry (URI %1) to the cache. Status: %2. Encoding: %3.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>27</td><td>Flushed entry (URI %1) from the cache.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>28</td><td>Attempted to set URL group property: %1. Status: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>29</td><td>Attempted to set server session property: %1. Status: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>30</td><td>Attempted to set request queue property: %1. Status: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>31</td><td>Attempted to add URL (%2) to URL group (%1). Status: %3.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>32</td><td>Removed URL (%2) from URL group (%1).</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>33</td><td>Removed all URLs from URL group %1.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>34</td><td>Initiating SSL connection.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>35</td><td>Initiating SSL handshake.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>36</td><td>SSL handshake completed with status: %1.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>37</td><td>Server application is attempting to receive the SSL client certificate, which will be provided if available. If the client certificate is not available, a renegotiation will be initiated.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>38</td><td>Attempt by server application to receive client certificate failed with status: %1.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>39</td><td>Raw SSL data is available for processing.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>40</td><td>Decrypted SSL data is available for processing.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>41</td><td>Passed plaintext data for encryption.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>43</td><td>Attempt (on connection ID %1) to authenticate client completed. Authentication type %2. Security status: %3.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>43</td><td>Attempt (on connection ID %1) to authenticate client completed. Authentication type %2. Security status: %3.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>44</td><td>Attempted to add entry to the %2 authentication cache. Status: %4.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>45</td><td>Entry successfully removed from the authentication cache.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>46</td><td>Successfully associated QoS flow with connection (connection ID %1). Bandwidth throttled to: %2 Bytes per second.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>47</td><td>Failed to configure the %2 logging (directory %4), Status: %1.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>48</td><td>Successfully configured %2 logging (directory %5).</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>49</td><td>Failed to create %2 log file %5. Status: %1.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>50</td><td>Successfully created new %2 log file %5.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>51</td><td>Entry has been written to %3 log file.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>52</td><td>Parsing of request (request ID %2) failed due to reason: %3. Request may not be compliant with HTTP/1.1.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>53</td><td>HTTP timer %3 expired. The connection will be reset.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>56</td><td>Failed to acquire handle for SSL credentials. Failure will be event logged. Security status: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>57</td><td>SSL connection will be disconnected as initiated by the client.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>58</td><td>SSL connection will be disconnected as initiated by the server application. Status: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>59</td><td>Attempt to decrypt SSL data failed. Security status: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>60</td><td>Query for SSL connection parameters failed. Security status: %2. Connection will be reset.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>61</td><td>Cannot find SSL endpoint for inbound connection for local IP address and port %3.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>62</td><td>Attempt to perform SSL handshake failed. Security status: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>63</td><td>Attempt to encrypt SSL data failed. Security status: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>64</td><td>Request (request ID %1) rejected due to reason: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>65</td><td>Server application canceled the processing of its request (request ID %1).</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>66</td><td>Http.sys failed to process CPU hot-add. Processor number: %1, reason: %2, status: %3.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>67</td><td>Hot-add information: Current UxNumberOfProcessors: %1, comment: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>68</td><td>Initialized QoS flow: FlowHandle %1, bandwidth %2, peak bandwidth %3, burst size %4</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>69</td><td>Initialized QoS flow: FlowHandle %1, bandwidth %2, peak bandwidth %3, burst size %4</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>70</td><td>QoS flow initialization failed: bandwidth %1, peak bandwidth %2, burst size %3, status %4</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>71</td><td>Setting flow: Connection %1, FlowHandle %2</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>72</td><td>Assign to Configuration QoS Flow: FlowHandle %1</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>73</td><td>[re]Setting QoS Flow failed: Connection %1, FlowHandle %2, status %3</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>74</td><td>Response range processing done. Req. %1, response content size %2, ranges %3 (%4-%5, %6-%7,...)</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>75</td><td>Begin building slices. Req. %1, slices %2 (%3,%4,...), ranges %5 (%6-%7, %8-%9,...)</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>76</td><td>Send cached slices. Req. %1, CacheEntry %2, slices %3 (%4,%5,...), ranges %6 (%7-%8, %9-%10,...)</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>77</td><td>Cached slices match content. Req. %1, CacheEntry %2, slices %3 (%4,%5,...), ranges %6 (%7-%8, %9-%10,...)</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>78</td><td>Merge slices to cache. CacheEntry %1, slices to merge %2, slices to cache %3</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>79</td><td>Sending range from flat cache entry. CacheEntry %1, range %2-%3</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>80</td><td>Channel bind ASC parameters: connection %1, buffers %2, flags %3</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>81</td><td>Service bind check done. Connection %1, Context %2-%3, status %4, target %5</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>82</td><td>Captured channel bind config. Hardening %1, flags %2, service count %3</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>83</td><td>Channel bind response config overwrites %1</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>84</td><td>Policy-Based QoS: Connection %1, FlowHandle %2</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>85</td><td>Thread pool extension. Pool type: %1, active pools: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>86</td><td>Thread ready. Pool type: %1, active pools: %2, thread count: %3</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>87</td><td>Thread pool trim. Pool type: %1, active pools: %2.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>88</td><td>Thread gone. Pool type: %1, active pools: %2, thread count: %3</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>89</td><td>SNI parsed for connection: %1 with status: %2</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>90</td><td>Request %1 has initated opaque mode</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>91</td><td>Endpoint auto-generated for %2</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>92</td><td>Deleted auto-generated endpoint for %2</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>93</td><td>Inbound connection for IP: %3, SNI: %4. SSL endpoint found: %5</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>94</td><td>SSL connection with local IP address and port %2 rejected due to configuration policy.</td></tr>
<tr><td>Microsoft-Windows-HttpService</td><td>95</td><td>Parsing of response (response ID %2) failed due to reason: %3. Request may not be compliant with HTTP/1.1.</td></tr>
</table>
