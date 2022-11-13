# Schannel

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Schannel</td><td>36864</td><td>The schannel security package has loaded successfully.</td></tr>
<tr><td>Schannel</td><td>36865</td><td>A fatal error occurred while opening the system %1 cryptographic module. Operations that require the SSL or TLS cryptographic protocols will not work correctly. The error code is %2.</td></tr>
<tr><td>Schannel</td><td>36867</td><td>Creating a TLS %1 credential.</td></tr>
<tr><td>Schannel</td><td>36868</td><td>The TLS %1 credential&#39;s private key has the following properties:

   CSP name: %2
   CSP type: %3
   Key name: %4
   Key Type: %5
   Key Flags: %6

 The attached data contains the certificate.</td></tr>
<tr><td>Schannel</td><td>36869</td><td>The TLS %1 credential&#39;s certificate does not have a private key information property attached to it. This most often occurs when a certificate is backed up incorrectly and then later restored. This message can also indicate a certificate enrollment failure.</td></tr>
<tr><td>Schannel</td><td>36870</td><td>A fatal error occurred when attempting to access the TLS %1 credential private key. The error code returned from the cryptographic module is %2. The internal error state is %3.</td></tr>
<tr><td>Schannel</td><td>36871</td><td>A fatal error occurred while creating a TLS %1 credential. The internal error state is %2.</td></tr>
<tr><td>Schannel</td><td>36872</td><td>The TLS %1 specified certificate&#39;s chain could not be retrieved:

   Failure Status: %2
   Flags: %3

 The attached data contains the certificate.</td></tr>
<tr><td>Schannel</td><td>36873</td><td>No supported cipher suites were found when initiating a TLS connection. This indicates a configuration problem with the client application and/or the installed cryptographic modules. The TLS connection request has failed.</td></tr>
<tr><td>Schannel</td><td>36874</td><td>An %1 connection request was received from a remote client application, but none of the cipher suites supported by the client application are supported by the server. The TLS connection request has failed.</td></tr>
<tr><td>Schannel</td><td>36875</td><td>The remote server has requested TLS client authentication, but no suitable client certificate could be found. An anonymous connection will be attempted. This TLS connection request may succeed or fail, depending on the server&#39;s policy settings.</td></tr>
<tr><td>Schannel</td><td>36876</td><td>The certificate received from the remote server has not validated correctly. The error code is %1. The TLS connection request has failed. The attached data contains the server certificate.</td></tr>
<tr><td>Schannel</td><td>36877</td><td>The certificate received from the remote client application has not validated correctly. The error code is %1. The attached data contains the client certificate.</td></tr>
<tr><td>Schannel</td><td>36878</td><td>The certificate received from the remote client application is not suitable for direct mapping to a client system account, possibly because the authority that issuing the certificate is not sufficiently trusted. The error code is %1. The attached data contains the client certificate.</td></tr>
<tr><td>Schannel</td><td>36879</td><td>The certificate received from the remote client application was not successfully mapped to a client system account. The error code is %1. This is not necessarily a fatal error, as the server application may still find the certificate acceptable.</td></tr>
<tr><td>Schannel</td><td>36880</td><td>A TLS %1 handshake completed successfully. The negotiated cryptographic parameters are as follows.

   Protocol version: %2
   CipherSuite: %3
   Exchange strength: %4 bits
   Context handle: %5
   Target name: %6
   Local certificate subject name: %7
   Remote certificate subject name: %8</td></tr>
<tr><td>Schannel</td><td>36881</td><td>The certificate received from the remote server has either expired or is not yet valid. The TLS connection request has failed. The attached data contains the server certificate.</td></tr>
<tr><td>Schannel</td><td>36882</td><td>The certificate received from the remote server was issued by an untrusted certificate authority. Because of this, none of the data contained in the certificate can be validated. The TLS connection request has failed. The attached data contains the server certificate.</td></tr>
<tr><td>Schannel</td><td>36883</td><td>The certificate received from the remote server has been revoked. This means that the certificate authority that issued the certificate has invalidated it. The TLS connection request has failed. The attached data contains the server certificate.</td></tr>
<tr><td>Schannel</td><td>36884</td><td>The certificate received from the remote server does not contain the expected name. It is therefore not possible to determine whether we are connecting to the correct server. The server name we were expecting is %1. The TLS connection request has failed. The attached data contains the server certificate.</td></tr>
<tr><td>Schannel</td><td>36885</td><td>When asking for client authentication, this server sends a list of trusted certificate authorities to the client. The client uses this list to choose a client certificate that is trusted by the server. Currently, this server trusts so many certificate authorities that the list has grown too long. This list has thus been truncated. The administrator of this machine should review the certificate authorities trusted for client authentication and remove those that do not really need to be trusted.</td></tr>
<tr><td>Schannel</td><td>36886</td><td>No suitable default server credential exists on this system. This will prevent server applications that expect to make use of the system default credentials from accepting SSL connections. An example of such an application is the directory server. Applications that manage their own credentials, such as the internet information server, are not affected by this.</td></tr>
<tr><td>Schannel</td><td>36887</td><td>A fatal alert was received from the remote endpoint. The TLS protocol defined fatal alert code is %1.</td></tr>
<tr><td>Schannel</td><td>36888</td><td>A fatal alert was generated and sent to the remote endpoint. This may result in termination of the connection. The TLS protocol defined fatal alert code is %1.

   Target name: %3

The TLS alert registry can be found at http://www.iana.org/assignments/tls-parameters/tls-parameters.xhtml#tls-parameters-6</td></tr>
<tr><td>Schannel</td><td>36889</td><td>The TLS %1 specified certificate&#39;s chain is incomplete:

   Failure Status: %2

 This can cause trust validation failures or interoperability problems. For more information see KB 954755
 The attached data contains the certificate.</td></tr>
<tr><td>Schannel</td><td>36896</td><td>Verification of the DTLS connection request failed.</td></tr>
<tr><td>Schannel</td><td>36897</td><td>DTLS record was rejected because it is outside of current receive window.</td></tr>
<tr><td>Schannel</td><td>36898</td><td>A DTLS record was rejected because it is a duplicate of a previously received record.</td></tr>
<tr><td>Schannel</td><td>36899</td><td>The retransmission of DTLS handshake messages has been requested.</td></tr>
<tr><td>Schannel</td><td>36912</td><td>The key material used to protect TLS Session Tickets was not found at %1.</td></tr>
</table>
