# Microsoft-Windows-User Device Registration

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>100</td><td>The discovery request send operation was successful.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>101</td><td>The discovery operation callback was successful. 
Server response was: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>102</td><td>The initialization of the join request was successful. Inputs:
 JoinRequest: %1 (%2)
 Domain: %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>103</td><td>The join request was successfully sent to server. Inputs:
 AuthToken: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>104</td><td>The get join response operation callback was successful. 
Activity Id: %2 
Server response was: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>105</td><td>The complete join response operation was successful.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>106</td><td>The post join tasks for the AAD Authentication Package completed successfully.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>107</td><td>The existing NGC user ID key was successfully deleted. Key name: %1.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>108</td><td>The NGC container was successfully created. 
User SID: %1 
IDP domain: %2 
Tenant domain: %3 
Flags: %4</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>109</td><td>The NGC user ID key was successfully created. 
User SID: %1 
IDP domain: %2 
Tenant domain: %3 
User ID: %4 
Flags: %5</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>110</td><td>The registration status has been successfully cleared from the device. 
Join type: %1 (%2) 
Tenant ID: %3 
UPN: %4</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>111</td><td>The registration status has been successfully flushed to disk. 
Join type: %1 (%2)</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>200</td><td>The discovery request send operation failed with exit code: %1. Inputs:
 Domain: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>201</td><td>The discovery operation callback failed with exit code: %1. The server returned HTTP status: %2. 
Server response was:
%3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>202</td><td>The initialization of the join request failed with exit code: %1. Inputs:
 JoinRequest: %2 (%3)
 Domain: %4</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>203</td><td>The send join request operation failed with exit code: %1. Inputs:
 AuthToken: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>204</td><td>The get join response operation callback failed with exit code: %1. 
Activity Id: %2 
The server returned HTTP status: %3 
Server response was: %4</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>205</td><td>The complete join response operation failed with exit code: %1. </td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>206</td><td>The post join tasks for the AAD Authentication Package failed with exit code: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>207</td><td>The parameter value should not be NULL or empty. Function: %1; Parameter: %2.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>208</td><td>Unable to remove account %2 from group %1. Error: %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>209</td><td>Unable to convert the string-format security identifier (SID) %1 to a functional SID. Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>210</td><td>Unable to retrieve account information for security identifier (SID) %1. Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>211</td><td>Unable to add account %2 to group %1. Error: %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>212</td><td>Error happened while accessing registry: %1. Operation: %2. Path: %3.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>213</td><td>Unable to connect to Local Security Authority (LSA) server. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>214</td><td>Unable to lookup Local Security Authority (LSA) authentication package. Package name: %1. Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>215</td><td>Local Security Authority (LSA) authentication failed. 
Authentication package identifier: %1. 
Authentication package name: %2. 
Error: %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>216</td><td>The security identifier (SID) is invalid. Function name: %1. Parameter name: %2.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>217</td><td>Unable to copy security identifier (SID) %1. Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>218</td><td>The string %1 is not a valid email address.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>219</td><td>Unable to retrieve the Active Directory domain join status information of the computer. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>220</td><td>Unable to retrieve the local computer&#39;s name in the specified format %1. Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>221</td><td>Unable to connect to the LDAP server %1:%2 using authentication method %3. Error: %4</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>222</td><td>Unable to convert the SID structure to its string-format. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>223</td><td>Unable to set WinHTTP option %1. Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>224</td><td>Unable to query WinHTTP option %1. Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>225</td><td>Unable to initialize WinHTTP. 
User agent: %1 
Access type: %2 
Proxy name: %3 
Proxy bypass address list: %4 
Flags: %5 
Error: %6</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>226</td><td>Unable to connect to server %1:%2 through WinHTTP. Error: %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>227</td><td>Unable to open WinHTTP %1 request. Flags: %2. Error: %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>228</td><td>Unable to set WinHTTP call back function. Notification flags: %1. Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>229</td><td>Unable to retrieve WinHTTP header information. Flags: %1. Name: %2. Error: %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>230</td><td>Unable to send WinHTTP request. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>231</td><td>One or more errors were encountered while retrieving a Secure Sockets Layer (SSL) certificate from the server.  
Error code: %1 
WinHTTP status: %2 (%3)</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>232</td><td>The WinHTTP callback function was cancelled. WINHTTP_STATUS_CALLBACK status code: %1 (%2)</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>233</td><td>The WinHTTP callback function failed. WINHTTP_STATUS_CALLBACK status code: %1 (%3). Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>234</td><td>Unalbed to query the amount of data available to read through WinHTTP. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>235</td><td>WinHTTP read data failure. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>236</td><td>WinHTTP write data failure. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>237</td><td>Unable to setup a certificate from the given encoded string. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>238</td><td>Unable to save the certificate. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>239</td><td>Unable to clear the registration status from the device. 
Exit code: %1 
Join type: %2 (%3) 
Tenant ID: %4 
UPN: %5</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>240</td><td>Unable to flush the registration status to disk. 
Exit code: %1 
Join type: %2 (%3)</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>241</td><td>KSP session ID: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>242</td><td>Account %2 was added to group %1.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>243</td><td>Account %2 was removed from group %1.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>244</td><td>Unable to sign authentication data for managed automatic registration. Exit code: %1.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>245</td><td>Unable to verify or update the signing certificate for automatic registration. Exit code: %1.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>246</td><td>Unable to get persisted state location. 
Exit code: %1 
Resource ID: %2 
Default location: %3 
Location type: %4 (%5)</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>247</td><td>Unable to remove Microsoft Passport key registration for all local Active Directory and Azure Active Directory users. 
Exit code: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>257</td><td>The task %1\%2 was successfully enabled.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>258</td><td>Failed to enable task %2\%3. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>259</td><td>The task %1\%2 was successfully enabled.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>260</td><td>Failed to enable task %2\%3. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>300</td><td>The Microsoft Passport key was successfully registered with Azure AD. 
Key ID: %1 
UPN: %2 
Attestation: %3 
Client request ID: %4 
Server request ID: %5 
Server response: %6</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>301</td><td>NGC key registration failed. 
Exit code: %1 
Client request ID: %2 
Server request ID: %3 
Error code: %4 
Server error message: %5 
Recommended client response: %6 
Server response: %7</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>302</td><td>The NGC key registration request was successfully sent. User email: %1.
Auth token: %2.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>303</td><td>The NGC key registration initialization operation failed. Exit code: %1. User email: %2.
Auth token: %3.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>304</td><td>Automatic registration failed at join phase. 
Exit code: %1 
Server error: %2 
Tenant type: %3 
Registration type: %4 
Debug Output: 
%5</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>305</td><td>Automatic registration failed at authentication phase. Unable to acquire access token. 
Exit code: %1 
Tenant Name: %4 
Tenant Type: %3 
Server error: 
%2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>306</td><td>Automatic registration Succeeded.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>307</td><td>Automatic registration failed. Failed to lookup the registration service information from Active Directory. Exit code: %1. See http://go.microsoft.com/fwlink/?LinkId=623042</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>308</td><td>This Device is joined to Azure AD, however, the user did not sign-in with an Azure AD account. Microsoft Passport provisioning will not be enabled. User: %1.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>309</td><td>Failed to discover the Azure AD DRS service. Exit code: %1.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>310</td><td>Unable to retrieve the NGC user ID key with name %1. Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>311</td><td>The NGC create container operation failed. 
User SID: %1 
IDP domain: %2 
Tenant domain: %3 
Flags: %4 
Error: %5</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>312</td><td>The existing NGC container was successfully deleted. 
User SID: %1 
IDP domain: %2 
Tenant domain: %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>314</td><td>Unable to delete NGC container. 
User SID: %1 
IDP domain: %2 
Tenant domain: %3 
Error: %4</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>315</td><td>Unable to create NGC user ID key. 
User SID: %1 
IDP domain: %2 
Tenant domain: %3 
User ID: %4 
Flags: %5 
Error: %6</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>316</td><td>Unable to retrieve the specified NGC user ID key. 
User SID: %1 
IDP domain: %2 
Tenant domain: %3 
User ID: %4 
Error: %5</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>317</td><td>Unable to delete NGC user ID key. Key name: %1. Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>318</td><td>Unable to create NGC transport key. 
User SID: %1 
IDP domain: %2 
Tenant domain: %3 
User ID: %4 
Key type: %5 
Flags: %6 
Error: %7</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>319</td><td>Unable to delete NGC transport key. 
User SID: %1 
IDP domain: %2 
Tenant domain: %3 
User ID: %4 
Error: %5</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>320</td><td>Unable to parse the NGC registration server response. 
HTTP status: %1 
Server response body: %2 
Error: %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>321</td><td>Failed to enable the device lock PIN. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>322</td><td>The application does not have the permission to perform this operation. Application SID: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>323</td><td>Preparing to send a request to the Web Account Manager. 
Account provider ID: %1 
Scope: %2 
Client ID: %3 
Authority: %4 
Resource: %5 
CorrelationId: %6</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>324</td><td>Unable to get a token using the Web Account Manager. Error: %5 
Request status code: %1 (%2) 
Token provider error code: %3 
Token provider error message: %4 
CorrelationId: %6</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>325</td><td>Successfully obtained a token for the current user via token broker. 
CorrelationId: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>326</td><td>Unable to get the application&#39;s core window. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>327</td><td>Unable to remove the PIN that has been created to use in place of the current user&#39;s logon password. 
User SID: %1 
Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>328</td><td>Unable to check whether a PIN has been created to use in place of the current user&#39;s logon password. 
User SID: %1 
Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>329</td><td>Preparing to send a request to the Web Account Manager silently (no UI mode). 
Account provider ID: %1 
Scope: %2 
Client ID: %3 
Authority: %4 
Resource: %5 
CorrelationId: %6</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>330</td><td>Azure DRS and Enterprise DRS are configured for this device. Only one DRS instance can be configured for an environment. AzureADTenantName:%1 EnterpriseDrsName:%2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>331</td><td>Automatic device join pre-check tasks completed. Debug output:\r\n %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>332</td><td>Automatic device join pre-check tasks found that this device is joined, however, it is missing some required state. The device will be removed and then joined again.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>333</td><td>Automatic device join pre-check tasks completed. The device can NOT be joined. The process MUST run as NT AUTHORITY\SYSTEM.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>334</td><td>Automatic device join pre-check tasks completed. The device can NOT be joined because a domain controller could not be located. The device must be connected to a network with connectivity to an Active Directory domain controller.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>335</td><td>Automatic device join pre-check tasks completed. The device is already joined.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>336</td><td>The Web Proxy Autodiscovery Protocol (WPAD) did NOT locate the URL of a configuration file using DHCP and/or DNS discovery methods. The request will be sent directly to the server. 
WINHTTP_STATUS_CALLBACK dwInternetStatus is %1 (%4) 
WINHTTP_ASYNC_RESULT dwResult is %2 (%5) 
WINHTTP_ASYNC_RESULT dwError is %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>337</td><td>The request was sent to the server through the out-bound proxy and failed with the following information. A fail-over proxy server will be used if available. 
WINHTTP_STATUS_CALLBACK dwInternetStatus is %1 (%4) 
WINHTTP_ASYNC_RESULT dwResult is %2 (%5) 
WINHTTP_ASYNC_RESULT dwError is %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>338</td><td>The Web Proxy Autodiscovery Protocol (WPAD) located the URL of a configuration file using DHCP and/or DNS discovery methods. %1 configuration entries were found in the configuration file.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>339</td><td>The following out-bound proxy information was set for this request. 
WINHTTP_PROXY_RESULT_ENTRY fProxy is: %1 
WINHTTP_PROXY_RESULT_ENTRY fBypass is: %2 
WINHTTP_PROXY_RESULT_ENTRY INTERNET_SCHEME is: %3 
WINHTTP_PROXY_RESULT_ENTRY pwszProxy is: %4 
WINHTTP_PROXY_RESULT_ENTRY ProxyPort is: %5</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>340</td><td>The Web Proxy Autodiscovery Protocol (WPAD) encountered an unexpected error. The request may not have been sent to the server. 
WINHTTP_STATUS_CALLBACK dwInternetStatus is %1 (%4) 
WINHTTP_ASYNC_RESULT dwResult is %2 (%5) 
WINHTTP_ASYNC_RESULT dwError is %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>341</td><td>This request will NOT fail over to a proxy server. The end of the proxy configuration discovered by Web Proxy Autodiscovery Protocol (WPAD) has been reached. Error %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>342</td><td>Unable to query Passport for Work policies. 
User SID: %1 
IDP domain: %2 
Tenant domain: %3 
Error: %4</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>343</td><td>Unable to enumerate Passport for Work containers. 
User SID: %1 
Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>344</td><td>Failed to access the device key. If you have a TPM, it might be locked out or in an unknown state. 
Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>345</td><td>Failed to access the device key. The device key has likely been removed. 
Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>346</td><td>The Microsoft Passport key was successfully removed from Azure AD. 
Key ID (encoded): %1 
UPN: %2 
Client request ID: %3 
Server request ID: %4 
Server response: %5</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>347</td><td>Failed to remove the Microsoft Passport key from Azure AD. 
Error: %2 
Key ID (encoded): %1 
Client request ID: %3 
Server request ID: %4 
Server error code: %5 
Server error message: %6 
Recommended client response: %7 
Server response: %8</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>348</td><td>The Microsoft Passport delete key registration request was successfully sent. User email: %1. Tenant ID: %2. Auth token: %3.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>349</td><td>Failed to initialize the Microsoft Passport delete key registration request. Exit code: %1. User email: %2. Tenant ID: %3. Auth token: %4.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>350</td><td>The Microsoft Passport key information was successfully saved. 
Key ID: %1 
Attestation level: %2 
AIK status: %3 
Key type: %4 
Key name: %5 
IDP domain: %6 
Tenant ID: %7 
User email: %8</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>351</td><td>Failed to save the Microsoft Passport key information. 
Error: %1 
Key ID: %2 
Attestation level: %3 
AIK status: %4 
Key type: %5 
Key name: %6 
IDP domain: %7 
Tenant ID: %8 
User email: %9</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>352</td><td>The Microsoft Passport key information was successfully deleted. 
Key ID: %1 
User SID: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>353</td><td>Failed to delete the Microsoft Passport key information. 
Error: %1 
Key ID: %2 
User SID: %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>354</td><td>Json Request Failed. Exit code: %1. httpStatus: %2 Server response: %3.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>355</td><td>Successfully enrolled for a logon certificate using a Registration Authority. 
Upn: %1 
TenantId: %2 
Authority: %3 
Resource: %4 
ExitCode: %5</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>356</td><td>Failed to enroll for a logon certificate using a Registration Authority. 
UPN: %1 
TenantId: %2 
ExitCode: %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>357</td><td>Group Policy indicates the user must enroll for a logon certificate along with their work PIN. 
Sid: %1 
TenantId: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>358</td><td>%1 
Device is AAD joined ( AADJ or DJ++ ): %2 
User has logged on with AAD credentials: %3 
Windows Hello for Business policy is enabled: %4 
Windows Hello for Business post-logon provisioning is enabled: %5 
Local computer meets Windows hello for business hardware requirements: %6 
User is not connected to the machine via Remote Desktop: %7 
User certificate for on premise auth policy is enabled: %8 
Machine is governed by %9 policy. 
See https://go.microsoft.com/fwlink/?linkid=832647 for more details.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>359</td><td>Windows Hello for Business provisioning has encountered an error during policy evaluation. 
ExitCode: %1 
Method: %2 
See https://go.microsoft.com/fwlink/?linkid=832647 for more details</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>360</td><td>%1 
Device is AAD joined ( AADJ or DJ++ ): %2 
User has logged on with AAD credentials: %3 
Windows Hello for Business policy is enabled: %4 
Windows Hello for Business post-logon provisioning is enabled: %5 
Local computer meets Windows hello for business hardware requirements: %6 
User is not connected to the machine via Remote Desktop: %7 
User certificate for on premise auth policy is enabled: %8 
Machine is governed by %9 policy. 
See https://go.microsoft.com/fwlink/?linkid=832647 for more details.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>361</td><td>%1 
Device is AAD joined ( AADJ or DJ++ ): %2 
User has logged on with AAD credentials: %3 
Windows Hello for Business policy is enabled: %4 
Windows Hello for Business post-logon provisioning is enabled: %5 
Local computer meets Windows hello for business hardware requirements: %6 
User is not connected to the machine via Remote Desktop: %7 
User certificate for on premise auth policy is enabled: %8 
MDM user certificate enrollment is ready: %9 
Certificate enrollment method: %10 
See https://go.microsoft.com/fwlink/?linkid=832647 for more details</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>362</td><td>%1 
Device is AAD joined ( AADJ or DJ++ ): %2 
User has logged on with AAD credentials: %3 
Windows Hello for Business policy is enabled: %4 
Windows Hello for Business post-logon provisioning is enabled: %5 
Local computer meets Windows hello for business hardware requirements: %6 
User is not connected to the machine via Remote Desktop: %7 
User certificate for on premise auth policy is enabled: %8 
Enterprise user logon certificate enrollment endpoint is ready: %9 
Enterprise user logon certificate template is : %10 
User has successfully authenticated to the enterprise STS: %11 
Certificate enrollment method: %12 
See https://go.microsoft.com/fwlink/?linkid=832647 for more details.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>363</td><td>The Microsoft Passport key is missing. 
Key ID: %1 
Attestation level: %2 
AIK status: %3 
Key type: %4 
Key name: %5 
IDP domain: %6 
Tenant ID: %7 
User email: %8</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>364</td><td>The saved Microsoft Passport information does not match the key. 
Saved information: 
  Key ID: %1 
  Key name: %2 
  IDP domain: %3 
  Tenant ID: %4 
  User email: %5 
The Microsoft Passport key: 
  Key name: %6 
  IDP domain: %7 
  Tenant ID: %8 
  User email: %9</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>365</td><td>Unable to enroll for a logon certificate using a Registration Authority. Automatic certificate enrollment will retry at regular intervals. 
UPN: %1 
TenantId: %2 
ExitCode: %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>366</td><td>Unable to enroll for a logon certificate using a Registration Authority. 
Resource: %1 
ExitCode: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>367</td><td>Added following properties to the Web Account Manager access token request. 
Properties: 
%1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>368</td><td>The following token properties were recieved from the Web Account Manager: 
Properties: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>369</td><td>The Workstation Service logged a device registration message. 
Message: %1 </td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>370</td><td>The automatic device registration task failed to unregister device. 
Exit code: %1 
Server error: %2 
Tenant type: %3 
Registration type: %4 
Debug Output: 
%5</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>371</td><td>The automatic device registration task successfully unregistered device.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>372</td><td>The FIDO credential was successfully registered with Azure AD. 
Credential ID: %1 
UPN: %2 
Request ID: %3 
Time: %4 
Server response: %5</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>373</td><td>FIDO credential registration failed. 
Exit code: %1 
Request ID: %2 
Time: %3 
HTTP status: %4 
Error code: %5 
Error subcode: %6 
Server error message: %7 
Server response: %8</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>374</td><td>The FIDO credential registration request was successfully sent. 
RPID: %1 
UPN: %2 
Credential display name: %3 
User display name: %4 
User image URL: %5 
Key algorithm: %6 
Auth token: %7 
Request ID: %8 
Flags: %9</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>375</td><td>The FIDO credential registration initialization operation failed. 
Exit code: %1 
RPID: %2 
UPN: %3 
Credential display name: %4 
User display name: %5 
User image URL: %6 
Key algorithm: %7 
Auth token: %8 
Request ID: %9 
Flags: %10</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>376</td><td>The FIDO credential was successfully created. 
UPN: %1 
Credential display name: %2 
User display name: %3 
User image URL: %4 
Key algorithm: %5 
Auth token: %6 
Request ID: %7 
Flags: %8</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>377</td><td>Unable to create FIDO credential. 
Exit code: %1 
UPN: %2 
Credential display name: %3 
User display name: %4 
User image URL: %5 
Key algorithm: %6 
Auth token: %7 
Request ID: %8 
Flags: %9</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>378</td><td>The FIDO credentials were successfully deleted from Azure AD. 
Number of credentials: %1 
UPN: %3 
Request ID: %4 
Time: %5 
Server response: %6</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>379</td><td>FIDO credential deletion failed. 
Exit code: %1 
Request ID: %2 
Time: %3 
HTTP status: %4 
Error code: %5 
Error subcode: %6 
Server error message: %7 
Server response: %8</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>380</td><td>The FIDO credential deletion request was successfully sent. 
UPN: %1 
Credential ID: %2 
Auth token: %3 
Request ID: %4</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>381</td><td>The FIDO credential deletion initialization operation failed. 
Exit code: %1 
UPN: %2 
Credential ID: %3 
Auth token: %4 
Request ID: %5</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>382</td><td>Unable to parse the FIDO registration server response. 
HTTP status: %1 
Server response body: %2 
Error: %3</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>383</td><td>The PIN has been successfully recovered.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>384</td><td>The PIN recover operation failed with exit code: %1.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>385</td><td>Unable to get attestation statement for Microsoft Passport key. Key name: %1,  KeyStatus: %2 (%3), Error: %4.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>386</td><td>Successfully got attestation statement for Microsoft Passport key. Key name: %1, KeyStatus: %2 (%3). </td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>387</td><td>Unable to reset registry recovery flag. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>388</td><td>Recovery API %1 called. Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>389</td><td>Automatic Azure SecureVM Join Succeeded.</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>500</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>501</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>502</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>503</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>504</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-User Device Registration</td><td>4096</td><td>The automatic device registration task will be triggered.</td></tr>
</table>
