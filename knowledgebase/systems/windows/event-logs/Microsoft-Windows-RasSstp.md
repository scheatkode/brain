# Microsoft-Windows-RasSstp

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>1</td><td>CoId=%1:The initial Secure Socket Tunneling Protocol request could not be successfully sent to the server. This can be due to network connectivity issues or certificate (trust) issues. The detailed error message is provided below. Correct the problem and try again.

%2</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>2</td><td>CoId=%1:The initial Secure Socket Tunneling Protocol (SSTP) response could not be received. There might be intermittent network connectivity issues or the server might not be accepting SSTP connections. The detailed error message is provided below. Correct the problem and try again. 

%2</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>3</td><td>CoId=%1:The HTTP response received from the server-side Secure Socket Tunneling Protocol (SSTP) either does not have the version information or the version is not supported. The HTTP version information received is logged in the data section below. The HTTP response from the SSTP server must contain the version header and the version must be 1.1.</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>4</td><td>CoId=%1:The server has refused the Secure Socket Tunneling Protocol (SSTP) request. Either a failure response code or no response code was received. The data portion below contains the response code that was received from the server. This is the HTTP status code present in the response. It can be because the web proxy or the SSTP server might be rejecting the connection, the server might not be configured for SSTP or the server might not have a port available for connection.</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>5</td><td>CoId=%1:The Secure Socket Tunneling Protocol (SSTP) negotiation has failed. The failure code is stored in the Data section of this message. Correct the problem and try again.</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>6</td><td>CoId=%1:The SSTP-based VPN connection to the remote access server was terminated because of a security check failure. Security settings on the remote access server do not match settings on this computer. Contact the system administrator of the remote access server and relay the following information:

SHA1 Certificate Hash: %2
SHA256 Certificate Hash: %3</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>7</td><td>The Secure Socket Tunneling Protocol service could not open the ConfigStore that is used for storing service-specific information. This can lead to incorrect service configuration or a leak of system resources.</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>8</td><td>The Secure Socket Tunneling Protocol (SSTP) service could not initialize the HTTP layer for setting up the configuration. Any configuration changes applied by the administrator might not be applied by SSTP.</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>9</td><td>The Secure Socket Tunneling Protocol service could not secure the URL with the new service configuration. Other applications or services can override the URL reservation. Use &#39;netsh.exe http add urlacl&#39; command to secure the access control list (ACL) manually. The detailed error message is given at the end of this message. 

URL: %1 

%2</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>10</td><td>The Secure Socket Tunneling Protocol service could not secure the default URL. This can prevent the servicing of the SSTP modules. Use &#39;netsh.exe http add urlacl&#39; command to secure the ACL manually. The detailed error message is given at the end of this message. 

URL: %1

%2</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>11</td><td>The Secure Socket Tunneling Protocol (SSTP) service could not find either a Server Authentication certificate or an Any Purpose certificate to be used for HTTPS. Check to see the availability of either a Server Authentication certificate or an Any Purpose certificate which also has a private key. SSTP sessions may not get established. Use ‘netsh.exe http add sslcert’ command to configure the certificate manually or install the appropriate certificate for SSTP use and restart RemoteAccess service.</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>12</td><td>The Secure Socket Tunneling Protocol service could not configure the following certificate for use with Internet Protocol version 4 (IPv4). This might prevent SSTP connections from being established successfully. Correct the problem and try again.

Certificate Name - %2

%1</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>13</td><td>The Secure Socket Tunneling Protocol service could not configure the following certificate for use with Internet Protocol version 6 (IPv6). This might prevent SSTP connections from being established successfully. Correct the problem and try again.

Certificate Name - %2

%1</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>14</td><td>The Secure Socket Tunneling Protocol service could not configure the route to the VPN server, which is required for the proper functioning of the VPN connection. The detailed error message is given below. Correct the problem and try again. %1</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>15</td><td>The Secure Socket Tunneling Protocol service could not get the network address of the remote server. This address is required for establishing the route for redirecting the traffic over the VPN interface. The detailed error message is provided below. Correct the problem and try again. %1</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>16</td><td>CoId=%1:The Secure Socket Tunneling Protocol server has provided a certificate with an Enhanced Key Usage that is neither Server Authentication nor Any Purpose. This client will not accept the certificate. The connection will be canceled. Contact the server administrator to correct the issue and try again.</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>17</td><td>The Secure Socket Tunneling Protocol service could not open the Parameters section of the registry to read the configuration values, so SSTP cannot be initialized. The detailed error message is provided below. Correct the problem and try again. 

%1</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>18</td><td>The Secure Socket Tunneling Protocol service either could not read the SHA256 certificate hash from the registry or the data is invalid. To be valid, the SHA256 certificate hash must be of type REG_BINARY and 32 bytes in length. SSTP might not be able to retrieve the value from the registry due to some other system failure. The detailed error message is provided below. SSTP connections will not be accepted on this server. Correct the problem and try again. 

%1</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>19</td><td>The Secure Socket Tunneling Protocol service either could not read the SHA1 certificate hash from the registry or the data is invalid. To be valid, the SHA1 certificate hash must be of type REG_BINARY and 20 bytes in length. SSTP might not be able to retrieve the value from the registry due to some other system failure. The detailed error message is provided below. SSTP connections will not be accepted on this server. Correct the problem and try again. 

%1</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>20</td><td>The Secure Socket Tunneling Protocol service was not able to allocate memory for setting up the configuration for accepting connections. The system might be low on memory. Correct the problem and restart the service.</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>21</td><td>The Secure Socket Tunneling Protocol service was not able to get the hash for the certificate configured with HTTP. The detailed error message is provided below. Correct the problem and try again. 

%1</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>22</td><td>The Secure Socket Tunneling Protocol service could not be configured to accept incoming connections. The detailed error message is provided below. Correct the problem and restart the SSTP service. 

%1</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>23</td><td>CoId=%1:The initial Secure Socket Tunneling Protocol request could not be successfully sent to the server. This can be due to the presence of a web proxy between the client and the server requiring authentication. Proxy authentication is not supported by this version of SSTP.</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>24</td><td>The certificates bound to the HTTPS listener for IPv4 and IPv6 do not match. For SSTP connections, certificates should be configured for 0.0.0.0:Port for IPv4, and [::]:Port for IPv6. The port is the listener port configured to be used with SSTP. The default listener port is 443.</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>25</td><td>The certificate used for Secure Socket Tunnelling Protocol (SSTP) is missing. You should configure a new certificate for SSTP or use default configuration</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>32</td><td>The thumbprint (cert hash) of the certificate used for Secure Socket Tunnelling Protocol (SSTP) %1 is different than the certificate bound %2 to the Web listener (HTTP.sys). Configure SSTP to use the default certificate or the certificate bound to SSL. You can configure web server applications to use the same certificate used by SSTP</td></tr>
<tr><td>Microsoft-Windows-RasSstp</td><td>33</td><td>CoId=%1: “Secure Socket Tunnelling Protocol (SSTP)” service could not configure the VPN server specific cookies. The detailed information on the error is given below.

%%2</td></tr>
</table>
