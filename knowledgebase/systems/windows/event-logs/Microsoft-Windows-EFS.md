# Microsoft-Windows-EFS

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1</td><td>An API call failed at %1.%2.  Error code: %3</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>2</td><td>An API call failed at %1.%2.  Error code: %3, Data: %4</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>3</td><td>An API call failed at %1.%2.  Error code: %3, Data: %4, %5</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4</td><td>%1.%2: Failed to allocate %3 bytes.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>256</td><td>EFS key promoted from current key.  CertValidated: %1, cbHash: %2, pbHash: %3, ContainerName: %4, ProviderName: %5, DisplayInformation: %6, dwCapabilities: %7, bIsCurrentKey: %8, eKeyType: %9</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>257</td><td>EFS key demoted from current key.  CertValidated: %1, cbHash: %2, pbHash: %3, ContainerName: %4, ProviderName: %5, DisplayInformation: %6, dwCapabilities: %7, bIsCurrentKey: %8, eKeyType: %9</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>258</td><td>EFS key flushed from cache.  CertValidated: %1, cbHash: %2, pbHash: %3, ContainerName: %4, ProviderName: %5, DisplayInformation: %6, dwCapabilities: %7, bIsCurrentKey: %8, eKeyType: %9</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>259</td><td>%1.%2: The specified key is not valid for EFS</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>260</td><td>%1.%2: Attempt to create a new EFS key</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>261</td><td>%1.%2: A new EFS key was successfully created</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>262</td><td>%1.%2: Begin searching the MY store for a valid EFS key</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>263</td><td>%1.%2: Begin searching the MY store for a valid EFS key</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>264</td><td>%1.%2: Deleting currentkey from registry</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>265</td><td>%1.%2: The EFS cert is self-signed, but self-signed certs are disabled by policy</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>272</td><td>%1.%2: RSA is required by policy, but the key does not support RSA encryption</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>273</td><td>%1.%2: MASTERKEY is required by policy, but the key does not support MASTERKEY encryption</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>274</td><td>%1.%2: SMARTCARDS are required by policy, but the key is not SMARTCARD-based</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>275</td><td>%1.%2: key is expired</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>276</td><td>%1.%2: key is valid</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>277</td><td>%1.%2: try and locate the matching key based on cert hash</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>278</td><td>%1.%2: key successfully loaded from registry</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>279</td><td>%1.%2: try and locate the matching key in cache</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>280</td><td>%1.%2: trying to load the masterkey history</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>281</td><td>%1.%2: masterkey history loaded</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>288</td><td>%1.%2: failed to encrypt: SIS or HSM file</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>289</td><td>%1.%2: Suite B is disabled by policy, but the key is a Suite B key</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>290</td><td>%1.%2: Suite B is required by policy, but the key is not a Suite B key</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>512</td><td>%1.%2: releasing user cache object.  Refcount: %3</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>513</td><td>%1.%2: trying to stop cache polling thread</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>514</td><td>%1.%2: no decryption status in cache</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>515</td><td>%1.%2: found matching decryption status in cache</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>516</td><td>%1.%2: attempting to add key to user cache</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>517</td><td>EFS key added to user cache.  CertValidated: %1, cbHash: %2, pbHash: %3, ContainerName: %4, ProviderName: %5, DisplayInformation: %6, dwCapabilities: %7, bIsCurrentKey: %8, eKeyType: %9</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>518</td><td>%1.%2: ensuring user has cache node</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>519</td><td>%1.%2: found cache node in user info</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>520</td><td>%1.%2: found cache node in global cache</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>521</td><td>%1.%2: creating new cache node for user</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>768</td><td>%1.%2: Policy settings specified flush on card removal.  Starting the polling thread...</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>769</td><td>%1.%2: Policy settings specified NO flush on timeout.  Stopping the polling thread...</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>770</td><td>%1.%2: Policy settings specified flush on timeout.  Starting the polling thread...</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>771</td><td>%1.%2: Policy settings specified new cache flush interval: %3.  Stop polling (will restart if there are active user caches)</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>772</td><td>%1.%2: Polling thread stopped</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>773</td><td>%1.%2: Flush cache specified by policy, and we have active user caches.  Start polling.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>774</td><td>%1.%2: Polling thread started</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>775</td><td>%1.%2: User logon detected.  Beginning SSO processing.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>776</td><td>%1.%2: User logon detected, but is not smartcard-based.  No SSO processing required.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>777</td><td>%1.%2: Smartcard notification detected.  Beginning SSO processing.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>784</td><td>%1.%2: Smartcard notification detected, but the logon cert is already cached.  No processing required.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>785</td><td>%1.%2: Current key matches the logon cert.  Setting up the PIN cache.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>786</td><td>%1.%2: User does not yet have a current key.  If smartcard is required by policy, the logon cert and PIN will be cached.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>787</td><td>%1.%2: Logon notification detected on DC.  Beginning DRA install.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>788</td><td>%1.%2: user does not already have a cache: generating one now</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>789</td><td>%1.%2: generating pre-cache for PIN and logon cert</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>790</td><td>%1.%2: tried to install logon cert, but it&#39;s not available (not a smartcard logon, or the smartcard was removed)</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>791</td><td>%1.%2: logon cert successfully installed</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>792</td><td>%1.%2: trying to install logon cert</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>793</td><td>%1.%2: User lock detected.  Beginning SSO processing.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>800</td><td>%1.%2: User logoff detected.  Beginning SSO processing.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>801</td><td>%1.%2: Flushing the user cache</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>802</td><td>%1.%2: User has locked workstation, but policy says not to flush cache</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>803</td><td>%1.%2: Checking for expired cache entries</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>804</td><td>%1.%2: Expired certificate in recovery policy</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>805</td><td>%1.%2: Certificate in recovery policy is not yet valid</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1024</td><td>%1.%2: SL policy successfully updated</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1040</td><td>%1.%2: EFS is disabled by SL policy</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1041</td><td>%1.%2: EFS is not yet initialized</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1042</td><td>%1.%2: EFS is disabled</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1280</td><td>%1.%2: the data received by the API was too large.  Expected: %3, Actual: %4</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1281</td><td>%1.%2: the data received by the API was too small.  Expected: %3, Actual: %4</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1282</td><td>%1.%2: POSSIBLE EFS ATTACK DETECTED: %3, %4, %5</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1283</td><td>%1.%2: attempting to validate EFS stream</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1284</td><td>%1.%2: EFS stream validated</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1536</td><td>PIN prompt dialog has closed</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1537</td><td>Prompt the user to select a smartcard-based EFS cert</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1538</td><td>Smartcard-based EFS cert successfully selected by the user</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1539</td><td>Prompt the user for PIN</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1540</td><td>PIN successfully acquired from the user</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1541</td><td>Perfect match found in cache.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1542</td><td>Masterkey history already loaded</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1543</td><td>Current key loaded from cache</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1544</td><td>Current key loaded from registry</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>1545</td><td>%1.%2: Masterkey history: failed size consistency check.  %3, %4, %5</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4096</td><td>%1.%2: Encrypted keys not equal</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4097</td><td>%1.%2: doing a REKEY, but the DDF entry already exists</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4098</td><td>%1.%2: replace operation added a DDF (unexpected)</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4099</td><td>%1.%2: user is modifying a DDF entry not matching the PoP entry.  Require WRITE_ATTRIBUTES</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4100</td><td>%1.%2: user is modifying a DDF matching the PoP entry, or the DRF.  Don&#39;t require WRITE_ATTRIBUTES</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4101</td><td>%1.%2: UNEXPECTED condition: no ENCRYPTED_KEY for SC failure</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4102</td><td>%1.%2: Plug-n-Play service not ready. EFS server will not try to detect interrupted encryption/decryption operation(s).</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4353</td><td>%1.%2: Cannot open log file. Encryption/decryption operation(s) cannot be recovered.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4354</td><td>%1.%2: Cannot read log file. Encryption/decryption operation(s) cannot be recovered.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4355</td><td>%1.%2: A corrupted or different format log file has been found. No action was taken.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4356</td><td>%1.%2: The log file cannot be opened as non-cached IO. No action was taken.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4357</td><td>%1.%2: Interrupted encryption/decryption operation(s) found on a volume. Recovery procedure started.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4358</td><td>%1.%2: EFS recovery service cannot open the file %3. The interrupted encryption/decryption operation cannot be recovered.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4359</td><td>%1.%2: EFS service recovered %3 successfully.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4360</td><td>%1.%2: EFS service could not open all the streams on file %3  The file was not recovered.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4361</td><td>%1.%2: %3 could not be recovered Completely.  EFS driver may be missing.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4368</td><td>%1.%2: IO Error occurred during stream recovery.  %3 was not recovered.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4369</td><td>%1.%2: EFS recovery service cannot open the backup file %3 by name. The interrupted encryption/decryption operation (on file %4) may be recovered.  The backup file will not be deleted. User should delete the backup file if the recovery operation is done successfully.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4370</td><td>%1.%2: %3 was opened by File ID successfully the first time but not the second time. No recovery operation was tried on file %4. This is an internal error.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4371</td><td>%1.%2: EFS recovery service cannot get the backup file name. The interrupted encryption/decryption operation (on file %3) may be recovered.  The temporary backup file %4 is not deleted.  User should delete the backup file if the recovery operation is done successfully.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4372</td><td>%1.%2: %3 could not be opened. %4 was not recovered.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4373</td><td>%1.%2: Stream Information could not be got from %3. %4 was not recovered.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4374</td><td>%1.%2: EFS service could not open all the streams on file %3.  %4 was not recovered.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4375</td><td>%1.%2: EFS Service received logon notification.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4376</td><td>EFS Service failed to start. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4377</td><td>%1.%2: User cache entry purged. Reference count: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4378</td><td>%1.%2: All user cache entries purged. Reference count: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4379</td><td>EFS service was unable to populate SID information. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4380</td><td>EFS service was unable to determine the computer name. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4381</td><td>EFS service was unable to initialize cache lock. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4382</td><td>EFS service was unable to initialize the BCrypt Algorithm Provider. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4383</td><td>EFS service was unable to query Software Licensing for the cache size. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4384</td><td>EFS service was unable to open handle to the MS_DEF_PROV provider. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4385</td><td>EFS service was unable to setup notifications from LSA. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4386</td><td>EFS service was unable to initialize the recovery policy resource. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4387</td><td>EFS service was unable process the recovery policy. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4388</td><td>EFS service was unable to notify NTFS of its state. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4389</td><td>EFS service was unable to setup group policy change notifications. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4390</td><td>EFS service was unable to process active user sessions. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4391</td><td>Encrypting File System server ready to accept calls.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4392</td><td>%1.%2: EFS service failed to subscribe for updates to an MDM policy. Index: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4393</td><td>%1.%2: Failed to initialize one or more synchronization objects. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4400</td><td>%1.%2: EFS service failed to process MDM policy updates. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4401</td><td>%1.%2: EFS service failed to provision a user for Windows Information Protection. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4402</td><td>%1.%2: EFS service failed to provision a user for DPL. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4403</td><td>%1.%2: EFS service failed to initialize file encryption queues. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4404</td><td>%1.%2: Recovery policy data is in an invalid format. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4405</td><td>%1.%2: Start: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4406</td><td>%1.%2: Complete: %3. Code: %4.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4407</td><td>%1.%2: Error Code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4408</td><td>%1.%2: Status Code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4409</td><td>%1.%2: Enter: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4410</td><td>%1.%2: Leave: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4411</td><td>%1.%2: Leave: %3. Code: %4.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4412</td><td>%1.%2: Error: %3. Code: %4.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4413</td><td>%1.%2: Warning: %3. Code: %4.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4414</td><td>%1.%2: %3. Code: %4.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4415</td><td>%1.%2: %3. Value: %4.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4416</td><td>%1.%2: Complete: %3. Code: %4.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4417</td><td>%1.%2: Leave: %3. Code: %4.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4418</td><td>%1.%2: EFS service failed to provision RMS for Windows Information Protection. Error code: %3.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4419</td><td>Thread %1: %2, Line %3, HRESULT %4, Message: &#39;%5&#39;</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>4420</td><td>A client attempted to call an EFS service API without privacy level authentication. Error code: %3. See https://go.microsoft.com/fwlink/?linkid=2181030.</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>7000</td><td>Machine role cannot be determined. %1</td></tr>
<tr><td>Microsoft-Windows-EFS</td><td>7002</td><td>Default group policy object cannot be created. %1</td></tr>
</table>
