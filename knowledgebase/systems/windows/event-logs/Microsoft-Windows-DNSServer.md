# Microsoft-Windows-DNSServer

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>256</td><td>QUERY_RECEIVED: TCP=%1; InterfaceIP=%2; Source=%3; RD=%4; QNAME=%5; QTYPE=%6; XID=%7; Port=%8; Flags=%9; PacketData=%11; AdditionalInfo = VirtualizationInstanceOptionValue: %12; GUID=%13</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>257</td><td>RESPONSE_SUCCESS: TCP=%1; InterfaceIP=%2; Destination=%3; AA=%4; AD=%5; QNAME=%6; QTYPE=%7; XID=%8; DNSSEC=%9; RCODE=%10; Port=%11; Flags=%12; Scope=%13; Zone=%14; PolicyName=%15; PacketData=%17; AdditionalInfo= %18; ElapsedTime=%19; GUID=%20</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>258</td><td>RESPONSE_FAILURE: TCP=%1; InterfaceIP=%2; Reason=%3; Destination=%4; QNAME=%5; QTYPE=%6; XID=%7; RCODE=%8; Port=%9; Flags=%10; Zone=%11; PolicyName=%12; PacketData=%14; AdditionalInfo = VirtualizationInstance: %13; ElapsedTime=%16; GUID=%17</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>259</td><td>IGNORED_QUERY: TCP=%1; InterfaceIP=%2; Source=%3; Reason=%4; QNAME=%5; QTYPE=%6; XID=%7; Zone=%8; PolicyName=%9; AdditionalInfo = VirtualizationInstance: %10</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>260</td><td>RECURSE_QUERY_OUT: TCP=%1; Destination=%2; InterfaceIP=%3; RD=%4; QNAME=%5; QTYPE=%6; QXID=%7; XID=%8; Port=%9; Flags=%10; RecursionScope=%11; CacheScope=%12; PolicyName=%13; PacketData=%15; AdditionalInfo = VirtualizationInstance: %16; GUID=%17</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>261</td><td>RECURSE_RESPONSE_IN: TCP=%1; Source=%2; InterfaceIP=%3; AA=%4; AD=%5; QNAME=%6; QTYPE=%7; XID=%8; RemoteQueriesSent=%9; Port=%10; Flags=%11; RecursionScope=%12; CacheScope=%13; PacketData=%15; AdditionalInfo = VirtualizationInstance: %16; GUID=%17; QueriesAttached=%18</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>262</td><td>RECURSE_QUERY_TIMEOUT: TCP=%1; InterfaceIP=%2; Destination=%3; QNAME=%4; QTYPE=%5; QXID=%6; XID=%7; Port=%8; Flags=%9; RecursionScope=%10; CacheScope=%11; AdditionalInfo = VirtualizationInstance: %12; GUID=%13</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>263</td><td>DYN_UPDATE_RECV: TCP=%1; InterfaceIP=%2; Source=%3; QNAME=%4; XID=%5; Port=%6; Flags=%7; SECURE=%8; PacketData=%10</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>264</td><td>DYN_UPDATE_RESPONSE: TCP=%1; InterfaceIP=%2; Destination=%3; QNAME=%4; XID=%5; ZoneScope=%6; Zone=%7; RCODE=%8; PolicyName=%9; PacketData=%11</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>265</td><td>IXFR_REQ_OUT: TCP=%1; InterfaceIP=%2; Source=%3; QNAME=%4; XID=%5; ZoneScope=%6; Zone=%7; PacketData=%9</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>266</td><td>IXFR_REQ_RECV: TCP=%1; InterfaceIP=%2; Source=%3; QNAME=%4; XID=%5; ZoneScope=%6; Zone=%7; PacketData=%9</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>267</td><td>IXFR_RESP_OUT: TCP=%1; InterfaceIP=%2; Destination=%3; QNAME=%4; XID=%5; ZoneScope=%6; Zone=%7; RCODE=%8; PacketData=%10</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>268</td><td>IXFR_RESP_RECV: TCP=%1; InterfaceIP=%2; Destination=%3; QNAME=%4; XID=%5; ZoneScope=%6; Zone=%7; RCODE=%8; PacketData=%10</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>269</td><td>AXFR_REQ_OUT: TCP=%1; Source=%2; InterfaceIP=%3; QNAME=%4; XID=%5; ZoneScope=%6; Zone=%7; PacketData=%9</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>270</td><td>AXFR_REQ_RECV: TCP=%1; Source=%2; InterfaceIP=%3; QNAME=%4; XID=%5; ZoneScope=%6; Zone=%7; PacketData=%9</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>271</td><td>AXFR_RESP_OUT: TCP=%1; InterfaceIP=%2; Destination=%3; QNAME=%4; XID=%5; ZoneScope=%6; Zone=%7; RCODE=%8</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>272</td><td>AXFR_RESP_RECV: TCP=%1; InterfaceIP=%2; Destination=%3; QNAME=%4; XID=%5; ZoneScope=%6; Zone=%7; RCODE=%8</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>273</td><td>XFR_NOTIFY_RECV: Source=%1; InterfaceIP=%2; QNAME=%3; ZoneScope=%4; Zone=%5; PacketData=%7</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>274</td><td>XFR_NOTIFY_OUT: Destination=%1; InterfaceIP=%2; QNAME=%3; ZoneScope=%4; Zone=%5; PacketData=%7</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>275</td><td>XFR_NOTIFY_ACK_IN: Source=%1; InterfaceIP=%2; PacketData=%4</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>276</td><td>XFR_NOTIFY_ACK_OUT: Destination=%1; InterfaceIP=%2; Zone=%3; PacketData=%5</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>277</td><td>DYN_UPDATE_FORWARD: TCP=%1; ForwardInterfaceIP=%2; Destination=%3; QNAME=%4; XID=%5; ZoneScope=%6; Zone=%7; RCODE=%8; PacketData=%10</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>278</td><td>DYN_UPDATE_RESPONSE_IN: TCP=%1; InterfaceIP=%2; Source=%3; QNAME=%4; XID=%5; ZoneScope=%6; Zone=%7; RCODE=%8; PacketData=%10</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>279</td><td>INTERNAL_LOOKUP_CNAME: TCP=%1; InterfaceIP=%2; Source=%3; RD=%4; QNAME=%5; QTYPE=%6; Port=%7; Flags=%8; XID=%9; PacketData=%11</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>280</td><td>INTERNAL_LOOKUP_ADDITIONAL: TCP=%1; InterfaceIP=%2; Source=%3; RD=%4; QNAME=%5; QTYPE=%6; Port=%7; Flags=%8; XID=%9; PacketData=%11</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>281</td><td>RRL_TO_BE_DROPPED_RESPONSE: InterfaceIP=%1; Destination=%2; QNAME=%3; QTYPE=%4; XID=%5; RCODE=%6; Port=%7; PacketData=%9</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>282</td><td>RRL_TO_BE_TRUNCATED_RESPONSE: InterfaceIP=%1; Destination=%2; QNAME=%3; QTYPE=%4; XID=%5; RCODE=%6; Port=%7; PacketData=%9</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>283</td><td>RRL_TO_BE_LEAKED_RESPONSE: InterfaceIP=%1; Destination=%2; QNAME=%3; QTYPE=%4; XID=%5; RCODE=%6; Port=%7; PacketData=%9</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>284</td><td>RESPONSE_SUCCESS: TCP=%1; InterfaceIP=%2; Destination=%3; AA=%4; AD=%5; QNAME=%6; QTYPE=%7; XID=%8; DNSSEC=%9; RCODE=%10; Port=%11; Flags=%12; Scope=%13; Zone=%14; PolicyName=%15; PacketData=%17; AdditionalInfo= %18; DataTag=%19; ElapsedTime=%20; GUID=%21; EDNSCorrelationTag=%22; EDNSScopeName=%23</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>285</td><td>RESPONSE_FAILURE: TCP=%1; InterfaceIP=%2; Reason=%3; Destination=%4; QNAME=%5; QTYPE=%6; XID=%7; RCODE=%8; Port=%9; Flags=%10; Zone=%11; PolicyName=%12; PacketData=%14; AdditionalInfo = VirtualizationInstance: %13; ElapsedTime=%16; GUID=%17; EDNSCorrelationTag=%18; EDNSScopeName=%19</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>286</td><td>QUERY_RECEIVED: TCP=%1; InterfaceIP=%2; Source=%3; RD=%4; QNAME=%5; QTYPE=%6; XID=%7; Port=%8; Flags=%9; PacketData=%11; GUID=%12; EDNSExtendedRCodeBits=%13; EDNSFlags=%14; EDNSUdpPayloadSize=%15; EDNSScopeName=%16; EDNSVirtualizationInstance=%17; EDNSDataTag=%18; EDNSCorrelationTag=%19</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>289</td><td>RECURSE_QUERY_OUT: TCP=%1; Destination=%2; InterfaceIP=%3; RD=%4; QNAME=%5; QTYPE=%6; QXID=%7; XID=%8; Port=%9; Flags=%10; RecursionScope=%11; CacheScope=%12; PolicyName=%13; PacketData=%15; AdditionalInfo = VirtualizationInstance: %16; GUID=%17; EDNSScopeName=%18; EDNSCorrelationTag=%19</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>290</td><td>RECURSE_RESPONSE_IN: TCP=%1; Source=%2; InterfaceIP=%3; AA=%4; AD=%5; QNAME=%6; QTYPE=%7; XID=%8; RemoteQueriesSent=%9; Port=%10; Flags=%11; RecursionScope=%12; CacheScope=%13; PacketData=%15; AdditionalInfo = VirtualizationInstance: %16; GUID=%17; QueriesAttached=%18; EDNSScopeName=%19; EDNSCorrelationTag=%20</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>291</td><td>RECURSE_QUERY_TIMEOUT: TCP=%1; InterfaceIP=%2; Destination=%3; QNAME=%4; QTYPE=%5; QXID=%6; XID=%7; Port=%8; Flags=%9; RecursionScope=%10; CacheScope=%11; AdditionalInfo = VirtualizationInstance: %12; GUID=%13; EDNSScopeName=%14; EDNSCorrelationTag=%15</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>512</td><td>The zone %1 was created with settings: Type=%2; Lookup=%3; ReplicationScope=%4; ZoneFile=%5; [virtualization instance %6].</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>513</td><td>The zone %1 was deleted. [virtualization instance: %2].</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>514</td><td>The zone %1 was updated. The %2 setting has been set to %3. [virtualization instance: %4].</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>515</td><td>A resource record of type %1, name %2, TTL %3 and RDATA %5 was created in scope %7 of zone %6. [virtualization instance: %8].</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>516</td><td>A resource record of type %1, name %2 and RDATA %5 was deleted from scope %7 of zone %6.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>517</td><td>All resource records of type %1, name %2 were deleted from scope %4 of zone %3. [virtualization instance: %5].</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>518</td><td>All resource records at Node name %1 were deleted from scope %3 of zone %2. [virtualization instance: %4].</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>519</td><td>A resource record of type %1, name %2, TTL %3 and RDATA %5 was created in scope %7 of zone %6 via dynamic update from IP Address %8.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>520</td><td>A resource record of type %1, name %2 and RDATA %5 was deleted from scope %7 of zone %6 via dynamic update from IP Address %8.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>521</td><td>A resource record of type %1, name %2, TTL %3 and RDATA %5 was scavenged from scope %7 of zone %6.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>522</td><td>The scope %1 was created in zone %2. [virtualization instance: %3].</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>523</td><td>The scope %1 was deleted in zone %2. [virtualization instance: %3].</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>525</td><td>The zone %1 was signed with following properties: DenialOfExistence=%2; DistributeTrustAnchor=%3; DnsKeyRecordSetTtl=%4; DSRecordGenerationAlgorithm=%5; DSRecordSetTtl=%6; EnableRfc5011KeyRollover=%7; IsKeyMasterServer=%8; KeyMasterServer=%9; NSec3HashAlgorithm=%10; NSec3Iterations=%11; NSec3OptOut=%12; NSec3RandomSaltLength=%13; NSec3UserSalt=%14; ParentHasSecureDelegation=%15; PropagationTime=%16; SecureDelegationPollingPeriod=%17; SignatureInceptionOffset=%18.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>526</td><td>The zone %1 was unsigned.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>527</td><td>The zone %1 was re-signed with following properties: DenialOfExistence=%2; DistributeTrustAnchor=%3; DnsKeyRecordSetTtl=%4; DSRecordGenerationAlgorithm=%5; DSRecordSetTtl=%6; EnableRfc5011KeyRollover=%7; IsKeyMasterServer=%8; KeyMasterServer=%9; NSec3HashAlgorithm=%10; NSec3Iterations=%11; NSec3OptOut=%12; NSec3RandomSaltLength=%13; NSec3UserSalt=%14; ParentHasSecureDelegation=%15; PropagationTime=%16; SecureDelegationPollingPeriod=%17; SignatureInceptionOffset=%18.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>528</td><td>Rollover was started on the type %1 with GUID %2 of zone %3.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>529</td><td>Rollover was completed on the type %1 with GUID %2 of zone %3.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>530</td><td>The type %1 with GUID %2 of zone %3 was marked for retiral. The key will be removed after the rollover completion.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>531</td><td>Manual rollover was triggered on the type %1 with GUID %2 of zone %3.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>533</td><td>The keys signing key with GUID %1 on zone %2 that was waiting for a Delegation Signer(DS) update on the parent has been forced to move to rollover completion.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>534</td><td>DNSSEC setting metadata was exported %1 key signing key metadata from zone %2.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>535</td><td>DNSSEC setting metadata was imported on zone %1.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>536</td><td>A record of type %1, QNAME %2 was purged from scope %3 in cache.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>537</td><td>The forwarder list on scope %2 has been reset to %1.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>540</td><td>The root hints have been modified.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>541</td><td>The setting %1 on scope %2 has been set to %3.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>542</td><td>The scope %1 of DNS server was created.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>543</td><td>The scope %1 of DNS server was deleted.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>544</td><td>The DNSKEY with Key Protocol %2, Base64 Data %4 and Crypto Algorithm %5 has been added at the trust point %1.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>545</td><td>The DS with Key Tag: %2, Digest Type: %3, Digest: %5 and Crypto Algorithm: %6 has been added at the trust point %1.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>546</td><td>The trust point at %1 of type %2 has been removed.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>547</td><td>The trust anchor for the root zone has been added.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>548</td><td>A request to restart the DNS server service has been received.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>549</td><td>The debug logs have been cleared from %1 on DNS server.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>550</td><td>The in-memory contents of all the zones on DNS server have been flushed to their respective files.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>551</td><td>All the statistical data for the DNS server has been cleared.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>552</td><td>A resource record scavenging cycle has been started on the DNS Server.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>553</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>554</td><td>The resource record scavenging cycle has been terminated on the DNS Server.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>555</td><td>The DNS server has been prepared for demotion by removing references to it from all zones stored in the Active Directory.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>556</td><td>The information about the root hints on the DNS server has been written back to the persistent storage.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>557</td><td>The addresses on which DNS server will listen has been changed to %1.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>558</td><td>An immediate RFC 5011 active refresh has been scheduled for all trust points.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>559</td><td>The zone %1 is paused. [virtualization instance: %2].</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>560</td><td>The zone %1 is resumed. [virtualization instance: %2].</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>561</td><td>The data for zone %1 has been reloaded from %2. [virtualization instance: %3].</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>562</td><td>The data for zone %1 has been refreshed from the master server %2.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>563</td><td>The secondary zone %1 has been expired and new data has been requested from the master server %2.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>564</td><td>The zone %1 has been reloaded from the Active Directory.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>565</td><td>The content of the zone %1 has been written to the disk and the notification has been sent to all the notify servers. [virtualization instance: %2].</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>566</td><td>All DNS records at the node %1 in the zone %2 will have their aging time stamp set to the current time.%3</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>567</td><td>The Active Directory-integrated zone %1 has been updated. Only %2 can run scavenging.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>568</td><td>The key master role for zone %1 has been %2.%3</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>569</td><td>A %1 signing key (%2) descriptor has been added on the zone %3 with following properties: KeyId=%4; KeyType=%5; CurrentState=%6; KeyStorageProvider=%7; StoreKeysInAD=%8; CryptoAlgorithm=%9; KeyLength=%10; DnsKeySignatureValidityPeriod=%11; DSSignatureValidityPeriod=%12; ZoneSignatureValidityPeriod=%13; InitialRolloverOffset=%14; RolloverPeriod=%15; RolloverType=%16; NextRolloverAction=%17; LastRolloverTime=%18; NextRolloverTime=%19; CurrentRolloverStatus=%20; ActiveKey=%21; StandbyKey=%22; NextKey=%23. The zone will be resigned with the %2 generated with these properties.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>570</td><td>A %1 signing key (%2) descriptor with GUID %3 has been updated on the zone %4. The properties of this %2 descriptor have been set to: KeyId=%5; KeyType=%6; CurrentState=%7; KeyStorageProvider=%8; StoreKeysInAD=%9; CryptoAlgorithm=%10; KeyLength=%11; DnsKeySignatureValidityPeriod=%12; DSSignatureValidityPeriod=%13; ZoneSignatureValidityPeriod=%14; InitialRolloverOffset=%15; RolloverPeriod=%16; RolloverType=%17; NextRolloverAction=%18; LastRolloverTime=%19; NextRolloverTime=%20; CurrentRolloverStatus=%21; ActiveKey=%22; StandbyKey=%23; NextKey=%24. The zone will be resigned with the %2 generated with these properties.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>571</td><td>A %1 signing key (%2) descriptor %4 has been removed from the zone %3.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>572</td><td>The state of the %1 signing key (%2) %3 has been modified on zone %4. The new active key is %5, standby key is %6 and next key is %7.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>573</td><td>A delegation for %1 in the scope %2 of zone %3 with the name server %4 has been added. [virtualization instance: %5].</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>574</td><td>The client subnet with name %1, and value %2 has been added to the DNS server.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>575</td><td>The client subnet with name %1 has been deleted from the DNS server.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>576</td><td>The client subnet with name %1 has been updated on the DNS server. The new IP subnets that it refers to are %2.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>577</td><td>A server level policy %6 for %1  has been created on server %2 with following properties: Processing order:%3; Criteria:%4; Action:%5; Condition:%7; IsEnabled:%8.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>578</td><td>A zone level policy %8 for %1  has been created on zone %6 on server %2 with following properties: Processing order:%3; Criteria:%4; Action:%5; Scopes:%7; Condition:%9; IsEnabled:%10.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>579</td><td>A policy %6 to control recursion settings has been created on server %2 with following properties: Processing order:%3; Criteria:%4; Action:%5; Scope:%1; Condition:%7; IsEnabled:%8.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>580</td><td>The server level policy %1 has been deleted from server %2.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>581</td><td>The zone level policy %1 has been deleted from zone %3 on server %2.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>582</td><td>The policy %1 to control recursion settings has been deleted from server %2.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>583</td><td>The server level policy %1 has been updated on server %2. The properties %3 have been updated to %4.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>584</td><td>The zone level policy %1 has been updated on zone %3 of server %2. The properties %4 have been updated to %5.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>585</td><td>The server level policy %1 for recursion has been updated on server %2. The properties %3 have been updated to %4.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>586</td><td>The zone level policy %1 has been updated on zone %4 of server %2. The policy does not use scope %3 for query resolution.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>587</td><td>The zone level policy %1 has been updated on zone %5 of server %2. The policy will use scope %3 for query resolution with weight %4.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>588</td><td>The zone level policy %1 has been updated on zone %6 of server %2. The weight assigned to scope %3 has been updated from %5 to %4.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>589</td><td>The server level policy %1 for recursion has been updated on server %2. The policy will use recursion scope %3 instead of %4 for query resolution.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>590</td><td>The Response Rate Limiting is configured on the DNS server  %1. The RRL settings are ResponsesPerSecond: %2, ErrorsPerSecond: %3, LeakRate: %4, TCRate: %5, Window: %6, MaximumResponsesInWindow: %7, IPv4PrefixLength: %8, IPv6PrefixLength: %9, Mode: %10.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>591</td><td>A exceptionlist %1 against response rate limiting has been added on the DNS server %2 with following settings: %3; Condition:%4. The queries that fall under this exceptionlist shall be exempt from response rate limiting.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>592</td><td>A exceptionlist %1 against response rate limiting has been deleted from server %2.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>593</td><td>A exceptionlist %1 against response rate limiting has been updated on server %2. The properties %3 have been updated to %4.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>594</td><td>The virtualization instance %1 with friendly name %2 was created.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>595</td><td>The virtualization instance %1 was removed. The zones hosted in this virtualization instance were automatically removed as a part of this.</td></tr>
<tr><td>Microsoft-Windows-DNSServer</td><td>596</td><td>The virtualization instance %1 was updated. The %2 setting has been set to %3.</td></tr>
</table>
