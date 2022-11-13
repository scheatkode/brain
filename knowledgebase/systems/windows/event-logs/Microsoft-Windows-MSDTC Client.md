# Microsoft-Windows-MSDTC Client

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>1073745922</td><td>Unable to translate the MS DTC error code to the appropriate MS DTC error message. The MS DTC error code was: %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>1073745923</td><td>You do not have permissions to manage the MS DTC on this system. MS DTC administrative functionality will be disabled.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229573</td><td>The local MS DTC detected that the MS DTC on %1 has the same unique identity as the local MS DTC. This means that the two MS DTC will not be able to communicate with each other. This problem typically occurs if one of the systems were cloned using unsupported cloning tools. MS DTC requires that the systems be cloned using supported cloning tools such as SYSPREP. Running &#39;msdtc -uninstall&#39; and then &#39;msdtc -install&#39; from the command prompt will fix the problem. Note: Running &#39;msdtc -uninstall&#39; will result in the system losing all MS DTC configuration information.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229585</td><td>MS DTC log path not found.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229609</td><td>Could not force transaction outcome.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229621</td><td>Transaction not found.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229622</td><td>The transaction is not a child transaction.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>2147487799</td><td>The MSDTC TM could not determine if an incoming connection request is from a remote machine. For security reasons, it will treat this connection request as a remote connection request. If the NetworkClients security option is not enabled, this can cause it to reject this connection attempt. This can cause applications to report that the TM is not available. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229623</td><td>The transaction cannot be forced to abort or commit because the transaction&#39;s state is not &quot;In Doubt&quot;.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229624</td><td>Either the transaction is not committed or there are resource managers or subordinate MS DTC Transaction Managers still connected.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229625</td><td>Could not resolve the transaction due to an unknown error.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229627</td><td>MS DTC encountered an internal error and is terminating.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>1073745980</td><td>String message: %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229681</td><td>A critical error occurred in an MS DTC component therefore the process is terminating. The category field identifies the component that encountered the error. Please contact Microsoft Product Support. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229683</td><td>Failed to convert the caller provided TIP Transaction URL into a valid MS DTC Transaction Id. This error is unexpected because the TIP Transaction URL indicates that the transaction originated on this system. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229684</td><td>Unable to get the file name for the OLE Transactions Proxy DLL. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229685</td><td>Failed to dynamically load the OLE Transactions Proxy DLL. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229686</td><td>The &quot;DllGetTransactionManagerCore&quot; function is missing from the OLE Transactions Proxy DLL. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229687</td><td>Failed to connection to the registry on the remote MS DTC Transaction Manager&#39;s system. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229688</td><td>Failed to open the registry key containing the list of transaction managers. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229689</td><td>Failed to read the name of the default transaction manager from the registry. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229696</td><td>Failed to open the registry key containing the name of the OLE Transactions Proxy DLL. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229697</td><td>Failed to read the name of the OLE Transactions Proxy DLL from the registry. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229698</td><td>Failed to start MS DTC via the MS DTC Proxy DLL. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229699</td><td>Unable to start MS DTC because initialization of cluster support failed.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229705</td><td>An MS DTC component was unable to allocate memory for a critical operation. That component is terminating. The category field identifies the component that failed. Please restart MS DTC if it does not restart automatically. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229828</td><td>Failed to initialize the MS DTC Communication Manager.  Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229829</td><td>MS DTC is unable to communicate with MS DTC on a remote system. No common RPC protocol is supported between the two systems. Please ensure that one or more of the following RPC protocols are common to both systems: TCP/IP, SPX, or NetBEUI.  Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229830</td><td>The MS DTC Connection Manager is unable to register with RPC to use one of LRPC, TCP/IP, or UDP/IP. Please ensure that RPC is configured properly. If &quot;ServerTcpPort&quot; registry key is configured(DWORD value under the HKEY_LOCAL_MACHINE\Software\Microsoft\MSDTC for local DTC instance or under cluster hive for clustered DTC instance), please verify if the configured port is valid and the port is not already in use by a different component. Error Specifics:%1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229831</td><td>MS DTC is unable to communicate with MS DTC on a remote system. MS DTC on the primary system established an RPC binding with MS DTC on the secondary system. However, the secondary system did not create the reverse RPC binding to the primary MS DTC system before the timeout period expired. Please ensure that there is network connectivity between the two systems.  Error Specifics:%1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229871</td><td>Could not establish connection to trace transaction.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229872</td><td>No transaction is selected.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229873</td><td>Transaction not found.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229874</td><td>The version of the transaction manager is not compatible for this feature.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229875</td><td>The attempt to dump the transaction to a trace file failed.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229876</td><td>MS DTC Tracing infrastructure : the initialization of the tracing infrastructure failed. Internal Information : %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229877</td><td>MS DTC Tracing infrastructure : the attempt to create a new trace session failed. Internal Information : %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229878</td><td>MS DTC Tracing infrastructure : the attempt to stop the existing trace session failed. Internal Information : %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229879</td><td>MS DTC Tracing infrastructure : the attempt to flush the existing trace data failed. Internal Information : %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229880</td><td>MS DTC Tracing infrastructure : the attempt to update the maximum buffer count of the existing trace session failed. Internal Information : %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229881</td><td>MS DTC Tracing infrastructure : the infrastructure has reported that the number of trace events that have been lost until now is equal to %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229882</td><td>MS DTC Tracing infrastructure : the thread launched to update the trace settings has failed. Any changes to the trace settings made using the &quot;Tracing Options&quot; dialog box might not take the desired effect. Internal Information : %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229883</td><td>MS DTC Tracing infrastructure : the attempt to set the trace specific registry settings failed. Any tracing specific functionality will be disabled. Internal Information : %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229884</td><td>Failed to create a new trace session.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229885</td><td>Failed to stop the existing trace session.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229886</td><td>Failed to flush the existing trace data.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229887</td><td>Failed to update the maximum buffer count of the existing trace session.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229888</td><td>Failed to update all the trace settings in the registry.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229889</td><td>Failed to load all the trace settings from the registry.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229896</td><td>MS DTC Tracing infrastructure : the attempt to create the trace directory failed. Any tracing specific functionality will be disabled. Internal Information : %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229897</td><td>MS DTC Tracing infrastructure : the infrastructure has reported that an attempt to trace an event has failed cause of lack of enough buffer space. The tracing infrastructure will retry tracing this event. The total number of times this has happened so far is equal to %1. Increasing the max number of memory buffers might rectify the situation.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229898</td><td>Failed to read the needed name objects from the registry. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229899</td><td>Failed to initialize the needed name objects. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229900</td><td>Failed to stop MSDTC service or one of its dependent services. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229901</td><td>Failed to set the security attributes on the MS DTC service. Internal Information : %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229903</td><td>Failed to stop the MS DTC service. Internal Information : %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229904</td><td>Failed to restart the MS DTC service. Internal Information : %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229913</td><td>A MS DTC component has encountered an internal error. The process is being terminated. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229914</td><td>MS DTC was unable to start because this version of dtc is less than the least valid version allowable specified in the cluster database. This can happen if a higher incompatible version of MS DTC was installed on another node of the cluster. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229915</td><td>MS DTC was unable to start because this version of dtc is not compatible with the version of MS DTC installed on another node of the cluster. This can happen if an incompatible version of MS DTC was installed on another node of the cluster. Error Specifics: %1</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229926</td><td>Failed to prepare MSDTC for imaging. Sysprep phase: &quot;%1&quot; failed with error: %2</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229927</td><td>Unexpected error (%1) when connecting to the Kernel Transaction Manager.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229928</td><td>Unable to create a communication channel to the Kernel Transaction Manager.  The attempt failed with error: %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229929</td><td>MSDTC was unable to migrate its log during Windows upgrade. The attempt failed with error: %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229930</td><td>MSDTC encountered an error during migration of contact identifiers. The attempt failed with error: %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>3221229931</td><td>MSDTC encountered an error during Windows upgrade. Error specifics: %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>1073795108</td><td>During the MS DTC installation, the attempt to delete the dtclog directory failed. This was done since the location of the log directory has been changed to msdtc. This can happen if the dtclog directory is not empty. Internal Information : %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>2147536968</td><td>During MS DTC installation, the attempt to preserve the old log file failed. The MS DTC installation will continue, however any information present in the old log file will get lost. Internal Information : %1.</td></tr>
<tr><td>Microsoft-Windows-MSDTC Client</td><td>2147536970</td><td>The connection manager in a MS DTC component has received an invalid message. Event specific Information: %1.</td></tr>
</table>
