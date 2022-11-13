# Microsoft-Windows-Kernel-Tm

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Kernel-Tm</td><td>1</td><td>The Transaction (UOW=%1, Description=&#39;%3&#39;) was unable to be committed, and instead rolled back; this was due to an error message returned by CLFS while attempting to write a Prepare or Commit record for the Transaction.  The CLFS error returned was: %4.</td></tr>
<tr><td>Microsoft-Windows-Kernel-Tm</td><td>2</td><td>The Transaction (UOW=%1, Description=&#39;%3&#39;) blocked a Freeze from completing.  Freeze is necessary to ensure that a VSS snapshot is transactionally consistent.  The ResourceManager (RmId=%4, Description=&#39;%6&#39;) may not be functioning correctly, since it did not allow the transaction to drain in the allotted time.  Contact the vendor for that ResourceManager for assistance.</td></tr>
<tr><td>Microsoft-Windows-Kernel-Tm</td><td>3</td><td>The transaction (UOW=%1, Description=&#39;%3&#39;) was heuristically aborted and forgotten from the TransactionManager (TmId=%4, LogPath=%6) so that the TransactionManager can continue to make forward progress.  This may cause data corruption in any subordinate ResourceManagers or Transactionmanager.</td></tr>
<tr><td>Microsoft-Windows-Kernel-Tm</td><td>4</td><td>The TransactionManager (TmId=%1, LogPath=%3) has failed to advance its log tail, due to the transaction (UOW=%4, Description=&#39;%6&#39;) being unresolved for some time.  The transaction must be forced to resolve in order for the TransactionManager to continue to provide transactional services.  Forcing the incorrect outcome may cause data corruption in any subordinate ResourceManagers or Transactionmanagers.</td></tr>
</table>
