# Microsoft-Windows-Hyper-V-Shared-VHDX

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>16</td><td>Shared VHDX filter started.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>32</td><td>Shared VHDX filter stopped.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>48</td><td>Successfully attached to volume. Volume: %2.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>64</td><td>Skipped attaching to non-CSV volume. Volume: %2.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>80</td><td>Error attaching to volume. Volume: %2. Error: %3.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>96</td><td>Successfully detached from volume. Volume: %2.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>112</td><td>Error detaching from volume. Volume: %2. Error: %3.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>128</td><td>Error opening handle for initiator. Initiator: %1. Hostname: %3. File: %5. Error: %6.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>129</td><td>A deduplicated file was detected for a Shared VHDX.

File: %2

Guidance:
Using a deduplicated file for a Shared VHDX file is not supported and may result in undefined behavior. Turn off data deduplication for the volume and run the PowerShell commandlet Expand-DedupFile on the file to recover.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>130</td><td>A reparse point was detected for a Shared VHDX file.

File: %2
Reparse Point Tag:%3

Guidance:
Shared VHDX files do not support reparse points, such as those used for symbolic links, hierarchical storage, and other technologies. Opening such a file will result in undefined behavior. The type of reparse point found is identified by the reparse point tag located above. Contact your system vendor to determine how to remove the reparse point. Also see http://technet.microsoft.com/en-us/aa365503(v=vs.71).aspx for more information.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>144</td><td>Error while mounting Shared VHDX file. File: %2. Error: %3.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>256</td><td>Shared VHDX file IO Failure. File: %2. SCSI operation: %3. SRB status: %4. SCSI status: %5. Sense error code: %6. Sense key: %7. Additional sense code: %8. Qualifier: %9. Error: %10.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>272</td><td>Shared VHDX file IO took longer than %1 ms. File %3. SCSI operation: %4. Operation time: %5 ms.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>288</td><td>System out of resources.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>304</td><td>Error reading metadata from the Shared VHDX file. File: %2. Error: %3. This indicates a problem when loading the Persistent Reservation information from the VHDX file. The virtual machine may lose access to the shared VHDX file. The virtual machine might recover automatically, but you may need to perform manual recovery actions inside the virtual machine.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>305</td><td>No metadata found on the Shared VHDX file. File: %2. Error: %3. There is no Persistent Reservation information in the VHDX file being opened. This is expected on the first time the Shared VHDX file is used.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>320</td><td>Error writing metadata to Shared VHDX file. File: %2. Error: %3.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>8208</td><td>Persistent Reservation: REGISTER. File: %2. Initiator %3. Hostname: %5.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>8224</td><td>Persistent Reservation: REGISTER AND IGNORE EXISTING KEY. File: %2. Initiator %3. Hostname: %5.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>8240</td><td>Persistent Reservation: RESERVE. File: %2. Initiator %3. Hostname: %5.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>8256</td><td>Persistent Reservation: RELEASE. File: %2. Initiator %3. Hostname: %5.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>8272</td><td>Persistent Reservation: CLEAR. File: %2. Initiator %3. Hostname: %5.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>8288</td><td>Persistent Reservation: PREEMPT. File: %2. Initiator %3. Hostname: %5.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>8304</td><td>Persistent Reservation: PREEMPT AND ABORT. File: %2. Initiator %3. Hostname: %5.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>8320</td><td>Persistent Reservation: Opening state. File: %2. Holder: %3. Key: %4. Scope: %5. Type: %6. Generation: %7.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>8336</td><td>Persistent Reservation: Opening state. File: %2. Initiator: %3. Registration key: %4.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>16400</td><td>Handle opened by initiator. File: %2. Initiator %3. Hostname: %5.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>16416</td><td>Handle closed by initiator. File: %2. Initiator %3. Hostname: %5.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>16432</td><td>Shared VHDX file was mounted. File: %2. Mount time: %3 ms. Total Size: %4. Log Size: %5.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>16448</td><td>Shared VHDX file was dismounted. File: %2.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>16464</td><td>IO was completed. File: %2. SCSI operation: %3. Operation time: %4 ms.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>16480</td><td>Persistent Reservation start. PR: %1. File: %3. Initiator %4. Hostname: %6.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>16496</td><td>Persistent Reservation end. PR: %1. File: %3. Initiator %4. Hostname: %6. SRB status: %7. SCSI status: %8. Sense error code: %9. Sense key: %10. Additional sense code: %11. Qualifier: %12. Error: %13.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>16512</td><td>Persistent Reservation commit start. PR %1. File: %3. Initiator %4. Hostname: %6.</td></tr>
<tr><td>Microsoft-Windows-Hyper-V-Shared-VHDX</td><td>16528</td><td>Persistent Reservation commit end. PR: %1. File: %3. Initiator %4. Hostname: %6. Status: %7.</td></tr>
</table>
