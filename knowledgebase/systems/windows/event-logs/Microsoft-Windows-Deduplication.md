# Microsoft-Windows-Deduplication

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4096</td><td>Volume &quot;%1&quot; appears as disconnected and it is ignored by the service.  You may want to rescan disks.   Error: %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4097</td><td>The COM Server with CLSID %1 and name &quot;%2&quot; cannot be started on machine &quot;%3&quot;. Most likely the CPU is under heavy load.  Error: %4.
%5</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4098</td><td>The COM Server with CLSID %1 and name &quot;%2&quot; cannot be started on machine &quot;%3&quot;.  Error: %4.
%5</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4099</td><td>The COM Server with CLSID %1 and name &quot;%2&quot; cannot be started on machine &quot;%3&quot; during Safe Mode. The Data Deduplication service cannot start while in safe mode.  Error: %4.
%5</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4100</td><td>A critical component required by Data Deduplication is not registered. This might happen if an error occurred during Windows setup, or if the computer does not have the Windows Server 2012 or later version of Deduplication service installed. The error returned from CoCreateInstance on class with CLSID %1 and Name &quot;%2&quot; on machine &quot;%3&quot; is %4.
%5</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4101</td><td>Data Deduplication service is shutting down due to idle timeout.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4102</td><td>Data Deduplication service is shutting down due to shutdown event from the Service Control Manager.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4103</td><td>Data Deduplication job of type &quot;%1&quot; on volume &quot;%2&quot; has completed with return code: %3
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4104</td><td>Data Deduplication error: Unexpected error calling routine %1.  hr = %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4105</td><td>Data Deduplication error: Unexpected error.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4106</td><td>Data Deduplication warning: %1
Error: %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4107</td><td>Data Deduplication error: Unexpected COM error %1: %2.  Error code: %3.
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4108</td><td>Data Deduplication was unable to access the following file or volume: &quot;%1&quot;.  This file or volume might be locked by another application right now, or you might need to give Local System access to it.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4109</td><td>Data Deduplication encountered an unexpected error during volume scan of volumes mounted at &quot;%1&quot; (&quot;%2&quot;). To find out more information about the root cause for this error please consult the Application/System event log for other Deduplication service, VSS or VOLSNAP errors related with these volumes. Also, you might want to make sure that you can create shadow copies on these volumes by using the VSSADMIN command like this: VSSADMIN CREATE SHADOW /For=C:
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4110</td><td>Data Deduplication was unable to create or access the shadow copy for volumes mounted at &quot;%1&quot; (&quot;%2&quot;). Possible causes include an improper Shadow Copy configuration, insufficient disk space, or extreme memory, I/O or CPU load of the system. To find out more information about the root cause for this error please consult the Application/System event log for other Deduplication service, VSS or VOLSNAP errors related with these volumes. Also, you might want to make sure that you can create shadow copies on these volumes by using the VSSADMIN command like this: VSSADMIN CREATE SHADOW /For=C:
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4111</td><td>Data Deduplication was unable to access volumes mounted at &quot;%1&quot; (&quot;%2&quot;). Make sure that dismount or format operations do not happen while running deduplication.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4112</td><td>Data Deduplication was unable to access a file or volume. Details:

%1
 The volume may be inaccessible for I/O operations or marked read-only. In case of a cluster volume, this may be a transient failure during failover.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4113</td><td>Data Deduplication was unable to scan volume &quot;%1&quot; (&quot;%2&quot;).
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4114</td><td>Data Deduplication detected a corruption on file &quot;%1&quot; at offset (&quot;%2&quot;).  If this condition persists then please restore the data from a previous backup.  Corruption details: Structure=%3, Corruption type = %4, Additional data = %5
%6</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4115</td><td>Data Deduplication encountered failure while reconciling chunk store on volume &quot;%1&quot;. The error code was %2. Reconciliation is disabled for the current optimization job.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4118</td><td>Data Deduplication encountered corrupted chunk container %1 while performing full garbage collection. The corrupted chunk container is skipped.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4119</td><td>Data Deduplication could not initialize change log under %1. The error code was %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4120</td><td>Data Deduplication service could not mark chunk container %1 as reconciled. The error code was %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4121</td><td>A Data Deduplication configuration file is corrupted. The system or volume may need to be restored from backup.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4122</td><td>Data Deduplication was unable to save one of the configuration stores on volume &quot;%1&quot; due to a disk-full error: If the disk is full, please clean it up (extend the volume or delete some files). If the disk is not full, but there is a hard quota on the volume root, please delete, disable or increase this quota.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4123</td><td>Data Deduplication could not access global configuration since the cluster service is not running. Please start the cluster service and retry the operation.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4124</td><td>Shadow copy &quot;%1&quot; was deleted during storage report generation.  Volume &quot;%2&quot; might be configured with inadequate shadow copy storage area. Data Deduplication could not process this volume.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4125</td><td>Shadow copy creation failed for volume &quot;%1&quot; after retrying for %2 minutes because other shadow copies were being created.  Reschedule the Data Deduplication for a less busy time.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4126</td><td>Volume &quot;%1&quot; is not supported for shadow copy.  It is possible that the volume was removed from the system.  Data Deduplication service could not process this volume.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4127</td><td>The volume &quot;%1&quot; has been deleted or removed from the system.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4128</td><td>Shadow copy creation failed for volume &quot;%1&quot; with error %2.  The volume might be configured with inadequate shadow copy storage area.  File Serve Deduplication service could not process this volume.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4129</td><td>The file system on volume &quot;%1&quot; is potentially corrupted.  Please run the CHKDSK utility to verify and fix the file system.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4130</td><td>Data Deduplication detected an insecure internal folder. To secure the folder, reinstall deduplication on the volume again.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4131</td><td>Data Deduplication could not find a chunk store on the volume.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4132</td><td>Data Deduplication detected multiple chunk store folders. To recover, reinstall deduplication on the volume.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4133</td><td>Data Deduplication detected conflicting chunk store folders: &quot;%1&quot; and &quot;%2&quot;.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4134</td><td>The data is invalid.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4135</td><td>Data Deduplication scheduler failed to initialize with error &quot;%1&quot;.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4136</td><td>Data Deduplication failed to validate job type &quot;%1&quot; on volume &quot;%2&quot; with error &quot;%3&quot;.
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4137</td><td>Data Deduplication failed to start job type &quot;%1&quot; on volume &quot;%2&quot; with error &quot;%3&quot;.
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4140</td><td>Data Deduplication detected job type &quot;%1&quot; on volume &quot;%2&quot; uses too much memory. %3 MB is assigned. %4 MB is used.
%5</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4141</td><td>Data Deduplication detected job type &quot;%1&quot; on volume &quot;%2&quot; memory usage has dropped to desirable level.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4142</td><td>Data Deduplication cancelled job type &quot;%1&quot; on volume &quot;%2&quot;. It uses too much memory than the amount assigned to it.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4143</td><td>Data Deduplication cancelled job type &quot;%1&quot; on volume &quot;%2&quot;. Memory resource is running low on the machine or in the job.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4144</td><td>Data Deduplication job type &quot;%1&quot; on volume &quot;%2&quot; failed to report completion to the service with error: %3.
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4145</td><td>Data Deduplication detected a container cannot be compacted or updated because it has reached the maximum generation.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4146</td><td>Data Deduplication corruption log &quot;%1&quot; is corrupted.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4147</td><td>Data Deduplication corruption log &quot;%1&quot; has reached maximum allowed size &quot;%2&quot;. Please run scrubbing job to process corruption log. No more corruptions will be reported until the log is processed.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4148</td><td>Data Deduplication corruption log &quot;%1&quot; has reached maximum allowed size &quot;%2&quot;. No more corruptions will be reported until the log is processed.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4149</td><td>Data Deduplication scheduler failed to uninitialize with error &quot;%1&quot;.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4150</td><td>Data Deduplication detected a new container could not be created in a chunk store because it ran out of available container Id.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4151</td><td>Data Deduplication full garbage collection phase 1 (cleaning file related metadata) on volume &quot;%1&quot; failed with error: %2.  The job will continue with phase 2 execution (data chunk cleanup).
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4153</td><td>Data Deduplication full garbage collection could not achieve maximum space reclamation because delete logs for data container %1 could not be cleaned up.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4154</td><td>Some files could not be deduplicated because of FSRM Quota violations on volume %1. Files skipped are likely compressed or sparse files in folders which are at quota or close to their quota limit. Please consider increasing the quota limit for folders that are at their quota limit or close to it.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4155</td><td>Data Deduplication failed to dedup file %1 &quot;%2&quot; due to fatal error %3
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4156</td><td>Data Deduplication encountered corruption while accessing a file in chunk store.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4157</td><td>Data Deduplication encountered corruption while accessing a file in chunk store. Please run scrubbing job for diagnosis and repair.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4158</td><td>Data Deduplication encountered checksum (CRC) mismatch error while accessing a file in chunk store. Please run scrubbing job for diagnosis and repair.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4159</td><td>Data Deduplication is unable to access file %1 because the file is in use.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4160</td><td>Data Deduplication encountered checksum (CRC) mismatch error while accessing a file in chunk store.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4161</td><td>Data Deduplication cannot run the job on volume %1 because the dedup store version compatiblity check failed with error %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4162</td><td>Data Deduplication has disabled the volume %1 because it has discovered too many corruptions. Please run deep scrubbing on the volume.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4163</td><td>Data Deduplication has detected a corrupt corruption metadata file on the store at %1. Please run deep scrubbing on the volume.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4164</td><td>Volume &quot;%1&quot; cannot be enabled for Data Deduplication. Data Deduplication does not support volumes larger than 64TB. Error: %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4165</td><td>Data Deduplication cannot be enabled on SIS volume &quot;%1&quot;. Error: %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4166</td><td>File-system is configured for case-sensitive file/folder names. Data Deduplication does not support case-sensitive file-system mode.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4169</td><td>Data Deduplication changed scrubbing job to read-only due to insufficient disk space.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4171</td><td>Data Deduplication has disabled the volume %1 because there are missing or corrupt containers. Please run deep scrubbing on the volume.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4173</td><td>Data Deduplication encountered a disk-full error.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4174</td><td>Data Deduplication job cannot run on volume &quot;%1&quot; due to insufficient disk space.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4175</td><td>Data Deduplication job cannot run on offline volume &quot;%1&quot;.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4176</td><td>Data Deduplication recovered a corrupt or missing file.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4177</td><td>Data Deduplication encountered a corrupted metadata file. To correct the problem, schedule or manually run a Garbage Collection job on the affected volume with the -Full option.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4178</td><td>Data Deduplication encountered chunk %1 with corrupted header while updating container. The corrupted chunk is replicated to the new container %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4179</td><td>Data Deduplication encountered chunk %1 with transient header corruption while updating container. The corrupted chunk is NOT replicated to the new container %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4180</td><td>Data Deduplication failed to read chunk container redirection table from file %1 with error %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4181</td><td>Data Deduplication failed to initialize reparse point index table for deep scrubbing from file %1 with error %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4182</td><td>Data Deduplication failed to deep scrub container file %1 on volume %2 with error %3.
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4183</td><td>Data Deduplication failed to load stream map log for deep scrubbing from file %1 with error %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4184</td><td>Data Deduplication found a duplicate local chunk id %1 in container file %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4185</td><td>Data Deduplication job type &quot;%1&quot; on volume &quot;%2&quot; was cancelled manually.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4186</td><td>Scheduled data Deduplication job type &quot;%1&quot; on volume &quot;%2&quot; was cancelled.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4189</td><td>The Data Deduplication chunk store statistics file on volume &quot;%1&quot; is corrupted and will be reset. Statistics will be updated by a subsequent job and can be updated manually by running the Update-DedupStatus cmdlet.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4190</td><td>The Data Deduplication volume statistics file on volume &quot;%1&quot; is corrupted and will be reset. Statistics will be updated by a subsequent job and can be updated manually by running the Update-DedupStatus cmdlet.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4191</td><td>Data Deduplication failed to append to deep scrubbing log file %1 with error %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4192</td><td>Data Deduplication encountered a failure during deep scrubbing on store %1 with error %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4193</td><td>Data Deduplication cancelled job type &quot;%1&quot; on volume &quot;%2&quot;. The job violated Csv dedup job placement policy.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4194</td><td>Data Deduplication cancelled job type &quot;%1&quot; on volume &quot;%2&quot;. The csv job monitor has been uninitialized.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4195</td><td>Data Deduplication encountered a IO device error while accessing a file on the volume. This is likely a hardware fault in the storage subsystem.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4196</td><td>Data Deduplication encountered an unexpected error. If this is a cluster, verify Data Deduplication is enabled on all nodes of the cluster.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>4197</td><td>Attempted to disable data access for data deduplicated CSV volume &quot;%1&quot; without maintenance mode. Data access can only be disabled for a CSV volume when in maintenance mode. Place volume into maintenance mode and retry.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6144</td><td>Data Deduplication service could not unoptimize file &quot;%5%6%7&quot;. Error %8, &quot;%9&quot;.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6145</td><td>Data Deduplication service failed to unoptimize too many files %3. Some files are not reported.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6146</td><td>Data Deduplication service has finished unoptimization on volume %3 with no errors.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6147</td><td>Data Deduplication service has finished unoptimization on volume %3 with %4 errors.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6148</td><td>%1 job has started.

Volume: %4 (%3)
Available memory: %5 MB
Available cores: %6
Instances: %7
Readers per instance: %8
Priority: %9
IoThrottle: %10</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6149</td><td>%1 job has started.

Volume: %4 (%3)
Available memory: %5 MB
Available cores: %6
Priority: %7
Full: %8
Volume free space (MB): %9</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6150</td><td>%1 job has started.

Volume: %4 (%3)
Available memory: %5 MB
Priority: %6
Full: %7
Read-only: %8</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6151</td><td>%1 job has started.

Volume: %4 (%3)
Available memory: %5 MB
Priority: %6</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6152</td><td>%1 job has started.

Volume: %4 (%3)
Available memory: %5 MB
Priority: %6</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6153</td><td>%1 job has completed.

Volume: %4 (%3)
Error code: %5
Error message: %6
Savings rate (percent): %7
Saved space (MB): %8
Volume used space (MB): %9
Volume free space (MB): %10
Optimized file count: %11
In-policy file count: %12
Job processed space (MB): %13
Job elapsed time (seconds): %18
Job throughput (MB/second): %19
Churn processing throughput (MB/second): %20</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6154</td><td>%1 job has completed.

Full: %2
Volume: %5 (%4)
Error code: %6
Error message: %7
Freed up space (MB): %8
Volume free space (MB): %9
Job elapsed time (seconds): %10
Job throughput (MB/second): %11</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6155</td><td>%1 job has completed.

Volume: %4 (%3)
Error code: %5
Error message: %6</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6156</td><td>%1 job has completed.

Full: %2
Read-only: %3
Volume: %6 (%5)
Error code: %7
Error message: %8
Total corruption count: %9
Fixable corruption count: %10

When corruptions are found, check more details in Scrubbing event channel.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6157</td><td>%1 job has completed.

Volume: %4 (%3)
Error code: %5
Error message: %6
Unoptimized file count: %7
Job processed space (MB): %8
Job elapsed time (seconds): %9
Job throughput (MB/second): %10</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6158</td><td>%1 job has been queued.

Volume: %4 (%3)
System memory percent: %5 
Priority: %6
Schedule mode: %7</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6159</td><td>%1 job has been queued.

Volume: %4 (%3)
System memory percent: %5 
Priority: %6
Schedule mode: %7</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6160</td><td>%1 job has been queued.

Volume: %4 (%3)
System memory percent: %5 
Priority: %6
Schedule mode: %7</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6170</td><td>%1 job has been queued.

Volume: %4 (%3)
System memory percent: %5 
Priority: %6
Schedule mode: %7</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6171</td><td>%1 job has been queued.

Volume: %4 (%3)
System memory percent: %5 
Priority: %6
Schedule mode: %7</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6172</td><td>Restore of deduplicated file &quot;%1&quot; failed with the following error: %2, &quot;%3&quot;.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6173</td><td>Priority %1 job has started.

Volume: %4 (%3)
File ID: %11
Available memory: %5 MB
Available cores: %6
Instances: %7
Readers per instance: %8
Priority: %9
IoThrottle: %10</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6174</td><td>%1 job has started.

Volume: %4 (%3)
Available memory: %5 MB
Available threads: %6
Priority: %7</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6175</td><td>%1 job has completed.

Volume: %4 (%3)
Error code: %5
Error message: %6
Savings rate (percent): %7
Saved space (MB): %8
Volume used space (MB): %9
Volume free space (MB): %10
Optimized file count: %11
Chunk lookup count: %12
Inserted chunk count: %13
Inserted chunks logical data (MB): %14
Inserted chunks physical data (MB): %15
Committed stream count: %16
Committed stream entry count: %17
Committed stream logical data (MB): %18
Retrieved chunks physical data (MB): %19
Retrieved stream logical data (MB): %20
DataPort time (seconds): %21
Job elapsed time (seconds): %22
Ingress throughput (MB/second): %23
Egress throughput (MB/second): %24</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6176</td><td>%1 job has been queued.

Volume: %4 (%3)
System memory percent: %5 
Priority: %6
Schedule mode: %7</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6177</td><td>Data Deduplication detected a non-clustered volume specified for the chunk index cache volume in a clustered deployment. The configuration is not recommended because it may result in job failures after failover.

Volume: %3 (%2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>6178</td><td>DataPort status update.  

Volume: %2
Savings rate (percent): %3
Saved space (MB): %4
Volume used space (MB): %5
Volume free space (MB): %6
Optimized file count: %7
Chunk lookup count: %8
Inserted chunk count: %9
Inserted chunks logical data (MB): %10
Inserted chunks physical data (MB): %11
Committed stream count: %12
Committed stream entry count: %13
Committed stream logical data (MB): %14
Retrieved chunks physical data (MB): %15
Retrieved stream logical data (MB): %16
DataPort time (seconds): %17
Job elapsed time (seconds): %18
Ingress throughput (MB/second): %19
Egress throughput (MB/second): %20</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8192</td><td>Data Deduplication detected job type &quot;%1&quot; on volume &quot;%2&quot; working set is low. Ratio to commit size is %3.
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8193</td><td>Data Deduplication detected job type &quot;%1&quot; on volume &quot;%2&quot; working set has recovered to desirable level.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8194</td><td>Data Deduplication detected job type &quot;%1&quot; on volume &quot;%2&quot; page fault rate is high. The rate is %3 page faults per second.
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8195</td><td>Data Deduplication detected job type &quot;%1&quot; on volume &quot;%2&quot; page fault rate has lowered to desirable level. The rate is %3 page faults per second.
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8196</td><td>Data Deduplication failed to dedup file &quot;%1&quot; with file ID %2 due to non-fatal error %3
%4.

Note: You can retrieve the file name by running the command FSUTIL FILE QUERYFILENAMEBYID on the file in question.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8197</td><td>Data Deduplication was unable to access a file or volume. Details:

%1
 The volume may be inaccessible for I/O operations or marked read-only. In case of a cluster volume, this may be a transient failure during failover.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8198</td><td>Data Deduplication could not find a chunk store on the volume.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8199</td><td>Data Deduplication detected multiple chunk store folders. To recover, reinstall deduplication on the volume.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8200</td><td>The data is invalid.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8201</td><td>Data Deduplication detected a container cannot be compacted or updated because it has reached the maximum generation.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8202</td><td>Data Deduplication detected a new container could not be created in a chunk store because it ran out of available container Id.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8203</td><td>Data Deduplication error: Unexpected error.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8204</td><td>Data Deduplication has aborted a group commit session.

File count: %1
Error: %2
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8205</td><td>Data Deduplication encountered corruption while accessing a file in chunk store. Please run scrubbing job for diagnosis and repair.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8206</td><td>Data Deduplication encountered checksum (CRC) mismatch error while accessing a file in chunk store. Please run scrubbing job for diagnosis and repair.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8207</td><td>Data Deduplication detected an insecure internal folder. To secure the folder, reinstall deduplication on the volume again.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8208</td><td>A Data Deduplication configuration file is corrupted. The system or volume may need to be restored from backup.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8209</td><td>Data Deduplication could not access global configuration since the cluster service is not running. Please start the cluster service and retry the operation.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8210</td><td>Data Deduplication error: Unexpected error calling routine %1.  hr = %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8211</td><td>Data Deduplication error: Unexpected COM error %1: %2.  Error code: %3.
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8212</td><td>Data Deduplication warning: %1
Error: %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8213</td><td>The COM Server with CLSID %1 and name &quot;%2&quot; cannot be started on machine &quot;%3&quot;. Most likely the CPU is under heavy load.  Error: %4.
%5</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8214</td><td>The COM Server with CLSID %1 and name &quot;%2&quot; cannot be started on machine &quot;%3&quot;.  Error: %4.
%5</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8215</td><td>The COM Server with CLSID %1 and name &quot;%2&quot; cannot be started on machine &quot;%3&quot; during Safe Mode. The Data Deduplication service cannot start while in safe mode.  Error: %4.
%5</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8216</td><td>A critical component required by Data Deduplication is not registered. This might happen if an error occurred during Windows setup, or if the computer does not have the Windows Server 2012 or later version of Deduplication service installed. The error returned from CoCreateInstance on class with CLSID %1 and Name &quot;%2&quot; on machine &quot;%3&quot; is %4.
%5</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8217</td><td>Data Deduplication is unable to access file %1 because the file is in use.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8218</td><td>Data Deduplication encountered checksum (CRC) mismatch error while accessing a file in chunk store.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8219</td><td>Data Deduplication encountered corruption while accessing a file in chunk store.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8220</td><td>Fail to open dedup setting registry key</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8221</td><td>Data Deduplication failed to dedup file &quot;%1&quot; with file ID %2 due to oplock break
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8222</td><td>Data Deduplication failed to load hotspot table from file %1 due to error %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8223</td><td>Data Deduplication failed to initialize oplock.

File ID: %1
File name: &quot;%2&quot;
Error: %3
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8224</td><td>Data Deduplication while running job on volume %1 detected invalid physical sector size %2. Using default value %3.
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8225</td><td>Data Deduplication detected an unsupported chunk store container.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8226</td><td>Data Deduplication could not create window to receive task scheduler stop message due to error %1. Task(s) may not stop after duration limit.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8227</td><td>Data Deduplication could not create thread to poll for task scheduler stop message due to error %1. Task(s) may not stop after duration limit.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8228</td><td>An attempt was made to perform an initialization operation when initialization has already been completed.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8230</td><td>Data Deduplication detected a corruption on file &quot;%1&quot; at offset (&quot;%2&quot;).  If this condition persists then please restore the data from a previous backup.  Corruption details: Structure=%3, Corruption type = %4, Additional data = %5
%6</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8231</td><td>Data Deduplication encountered a disk-full error.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8232</td><td>Data Deduplication created emergency file %1.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8233</td><td>Data Deduplication failed to create emergency file %1 with error %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8234</td><td>Data Deduplication deleted emergency file %1.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8235</td><td>Data Deduplication failed to delete emergency file %1 with error %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8236</td><td>Data Deduplication detected a chunk store container with misaligned valid data length.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8237</td><td>Data Deduplication Garbage Collection encountered a delete log entry with an invalid stream map signature for stream map Id %1.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8238</td><td>Data Deduplication failed to initialize oplock as the file appears to be missing.

File ID: %1
File name: &quot;%2&quot;
Error: %3
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8239</td><td>Data Deduplication skipped too many file-level errors. We will not log more than %1 file-level errors per job.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8240</td><td>Data Deduplication diagnostic warning.

%1
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8241</td><td>Data Deduplication diagnostic information.

%1
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8242</td><td>Data Deduplication found file %1 with a stream map id %2 in container file %3 marked for deletion.
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8243</td><td>Failed to enqueue job of type &quot;%1&quot; on volume &quot;%2&quot;.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8244</td><td>Error terminating job host process for job type &quot;%1&quot; on volume &quot;%2&quot; (process id: %3).
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8245</td><td>Data Deduplication encountered corrupted chunk %1 while updating container. Corrupted data that cannot be repaired will be copied as-is to the new container %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8246</td><td>Data Deduplication job type &quot;%1&quot; on volume &quot;%2&quot; failed to exit gracefully.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8247</td><td>Data Deduplication job host for job type &quot;%1&quot; on volume &quot;%2&quot; exited unexpectedly.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8248</td><td>Data Deduplication has failed to load corruption metadata file on the store at %1 due to error %2. Please run deep scrubbing on the volume.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8249</td><td>Data Deduplication full garbage collection phase 1 on volume &quot;%1&quot; encountered an error %2 while processing file %3. Phase 1 will need to be aborted since garbage collection of file-related metadata is unsafe to continue on file errors.
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8250</td><td>Data Deduplication has failed to process corruption metadata file %1 due to error %2. Please run deep scrubbing on the volume.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8251</td><td>Data Deduplication has failed to load a corrupted metadata file %1 due to error %2. Deleting the file and continuing.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8252</td><td>Data Deduplication has failed to set NTFS allocation size for container file %1 due to error %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8253</td><td>Data Deduplication configured to use BCrypt provider &#39;%1&#39; for hash algorithm %2.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8254</td><td>Data Deduplication could not use BCrypt provider &#39;%1&#39; for hash algorithm %2 due to an error in operation %3. Reverting to the Microsoft primitive CNG provider.
%4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8255</td><td>Data Deduplication failed to include file &quot;%1&quot; in file metadata analysis calculations.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8256</td><td>Data Deduplication failed to include stream map %1 in file metadata analysis calculations.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8257</td><td>Data Deduplication encountered an error for file &quot;%1&quot; while scanning files and folders.
%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8258</td><td>Data Deduplication encountered an error while attempting to resume processing. Please consult the event log parameters for more details about the current file being processed.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8259</td><td>Data Deduplication encountered an error %1 whle scanning usn journal on volume %2 for updating hot range tracking.
%3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8260</td><td>Data Deduplication could not truncate the stream of an optimized file. No action is required. Error: %1

%2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>8261</td><td>Data Deduplication encountered a IO device error while accessing a file on the volume. This is likely a hardware fault in the storage subsystem.
%1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10240</td><td>%1 job memory requirements.

Volume: %4 (%3)
Minimum memory: %5 MB
Maximum memory: %6 MB
Minimum disk: %7 MB
Maximum cores: %8</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10241</td><td>%1 reconciliation has started.

Volume: %4 (%3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10242</td><td>%1 reconciliation has completed.

Guidance: This event is expected when Reconciliation has completed, there is no recommended or required action. Reconciliation is an internal process that allows Optimization and DataPort jobs to run when the entire Deduplication chunk index cannot be loaded into memory. 

Volume: %4 (%3)
Reconciled containers: %5
Unreconciled containers: %6
Catchup references: %7
Catchup containers: %8
Reconciled references: %9
Reconciled containers: %10
Cross-reconciled references: %11
Cross-reconciled containers: %12
Error code: %13
Error message: %14</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10243</td><td>%1 job on volume %4 (%3) was configured with insufficient memory.

System memory percentage: %5
Available memory: %8 MB
Minimum required memory: %6 MB</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10244</td><td>Optimization memory details for %1 job on volume %3 (%2).</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10245</td><td>An open file was skipped during optimization. No action is required.

FileId: %2
Skip Reason: %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10246</td><td>An operation succeeded after one or more retries. Operation: %1; FileId: %3; Number of retries: %2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10247</td><td>Data Deduplication aborted the optimization pipeline.
VolumePath: %1
ErrorCode: %2
ErrorMessage: %3Details: %4</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10248</td><td>Data Deduplication aborted a file.
FileId: %1
FilePath: %2
FileSize: %3
Flags: %4
TotalRanges: %5
SkippedRanges: %6
AbortedRanges: %7
CommittedRanges: %8
ErrorCode: %9
ErrorMessage: %10Details: %11</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10249</td><td>Data Deduplication aborted a file range.
FileId: %1
FilePath: %2
RangeOffset: %3
RangeLength: %4
ErrorCode: %5
ErrorMessage: %6Details: %7</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10250</td><td>Data Deduplication aborted a session.
MaxSize: %1
CurrentSize: %2
RemainingRanges: %3
ErrorCode: %4
ErrorMessage: %5Details: %6</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10251</td><td>USN journal created.

Volume: %2 (%1)
Maximum size %3 MB
Allocation size %4 MB</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10252</td><td>DataPort memory details for %1 job on volume %3 (%2).</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10253</td><td>Data deduplication detected a file with an ID that is not supported.  Files with identifiers unpackable into 64-bits will be skipped. FileId: %1 FileName: %2</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10254</td><td>Reconciliation should be run to ensure optimal savings.

Guidance: This event is expected when Reconciliation is turned off for the DataPort job. Reconciliation is an internal process that allows Optimization and DataPort jobs to run when the entire Deduplication chunk index cannot be loaded into memory. When Reconciliation would require 50% or more of the memory on the system, it is recommended that you (temporarily) cease running a DataPort job against this volume, and run an Optimization job. If Reconciliation is not run through an Optimization job before Reconciliation would require more than 100% of system memory, Reconciliation will not be able to be run again (unless more memory is added). This would result in permanent decreased space efficiency on this volume.

Volume: %2 (%1)
Memory percentage required: %3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>10255</td><td>Data Deduplication optimization job will not run the reconciliation step due to inadequate memory.

Guidance: Deduplication savings will be suboptimal until the optimization job is provided more memory, or more more memory is added to the system.

Volume: %2 (%1)
Memory percentage required: %3</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12800</td><td>Data Deduplication service detected corruption in &quot;%5%6%7&quot;. The corruption cannot be repaired.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12801</td><td>Data Deduplication service detected corruption (%7) in &quot;%6&quot;. See the event details for more information.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12802</td><td>Data Deduplication service detected a corrupted item (%11 - %13, %8, %9, %10, %12) in Deduplication Chunk Store on volume %4. See the event details for more information.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12803</td><td>Data Deduplication service has finished scrubbing on volume %3. It did not find any corruption since the last scrubbing.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12804</td><td>Data Deduplication service found %4 corruption(s) on volume %3. All corruptions are fixed.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12805</td><td>Data Deduplication service found %4 corruption(s) on volume %3. %5 corruption(s) are fixed. %6 user file(s) are corrupted. %7 user file(s) are fixed. For the corrupted file list, see the Microsoft/Windows/Deduplication/Scrubbing events.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12806</td><td>Data Deduplication service found too many corruptions on volume %3. Some corruptions are not reported.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12810</td><td>Data Deduplication service has finished scrubbing on volume %3. It did not find any corruption since the last scrubbing.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12817</td><td>Data Deduplication service has finished scrubbing on volume %3. See the event details for more information.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12818</td><td>Data Deduplication service encountered error while processing file &quot;%5%6%7&quot;. The error was %8.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12819</td><td>Data Deduplication service encountered too many errors while processing file on volume %3. The threshold was %4. Some user file corruptions may not be reported.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12820</td><td>Data Deduplication service encountered error while detecting corruptions in chunk store on volume %3. The error was %4. The job is aborted.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12822</td><td>Data Deduplication service encountered error while loading corruption logs on volume %3. The error was %4. The job continues. Some corruptions may not be detected.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12823</td><td>Data Deduplication service encountered error while cleaning up corruption logs on volume %3. The error was %4. Some corruptions may be reported again next time.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12824</td><td>Data Deduplication service encountered error while loading hotspots mapping from chunk store on volume %3. The error was %4. Some corruptions may not be repaired.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12825</td><td>Data Deduplication service encountered error while determining corrupted user files on volume %3. The error was %4. Some user file corruptions may not be reported.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12826</td><td>Data Deduplication service found %4 corruption(s) on volume %3. %6 user file(s) are corrupted. %7 user file(s) are fixable. Please run scrubbing job in read-write mode to attempt fixing reported corruptions.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12827</td><td>Data Deduplication service fixed corruption in &quot;%5%6%7&quot;.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12828</td><td>Data Deduplication service detected fixable corruption in &quot;%5%6%7&quot;. Please run scrubbing job in read-write mode to fix this corruption.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12829</td><td>Data Deduplication service has finished scrubbing on volume %3. See the event details for more information.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12830</td><td>Data Deduplication service encountered error while repairing corruptions on volume %3. The error was %4. The repair is unsuccessful.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12831</td><td>Data Deduplication service detected a corrupted item (%6, %7, %8, %9) in Deduplication Chunk Store on volume %4. See the event details for more information.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12832</td><td>Container (%8,%9) with user data is missing from the chunk store. Missing container may result from incomplete restore, incomplete migration or file-system corruption. Volume is disabled from further optimization. It is recommended to restore the volume prior to enabling the volume for further optimization.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12833</td><td>Data Deduplication service encountered error while scaning dedup user files on volume %3. The error was %4. Some user file corruptions may not be reported.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12834</td><td>Data Deduplication service encountered error while processing file &quot;%5%6%7&quot;. The error was %8.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12835</td><td>Data Deduplication service encountered too many errors while processing file on volume %3. The threshold was %4. Some user file corruptions may not be reported.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12836</td><td>Data Deduplication service detected potential data loss (%9) in &quot;%6&quot; due to sharing reparse data with file &quot;%8&quot;. See the event details for more information.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>12837</td><td>Container (%8,%9) with user data is corrupt in the chunk store. It is recommended to restore the volume prior to enabling the volume for further optimization.</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20480</td><td>Open stream store stream (StartingChunkId %1, FileId %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20481</td><td>Open stream store stream completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20482</td><td>Prepare for paging IO (Stream %1, FileId %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20483</td><td>Prepare for paging IO completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20484</td><td>Read stream map (Stream %1, FileId %2, StartIndex %3, EntryCount %4)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20485</td><td>Read stream map completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20486</td><td>Read chunks (Stream %1, FileId %2, IoType %3, FirstRequestChunkId %4, NextRequest %5)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20487</td><td>Read chunks completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20488</td><td>Compute checksum (ItemType %1, DataSize %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20489</td><td>Compute checksum completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20490</td><td>Get container entry (ContainerId %1, Generation %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20491</td><td>Get container entry completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20492</td><td>Get maximum generation for container (ContainerId %1, Generation %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20493</td><td>Get maximum generation for container completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20494</td><td>Open chunk container (ContainerId %1, Generation %2, RootPath %4)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20495</td><td>Open chunk container completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20496</td><td>Initialize chunk container redirection table (ContainerId %1, Generation %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20497</td><td>Initialize chunk container redirection table completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20498</td><td>Validate chunk container redirection table (ContainerId %1, Generation %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20499</td><td>Validate chunk container redirection table completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20500</td><td>Get chunk container valid data length (ContainerId %1, Generation %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20501</td><td>Get chunk container valid data length completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20502</td><td>Get offset from chunk container redirection table (ContainerId %1, Generation %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20503</td><td>Get offset from chunk container redirection table completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20504</td><td>Read chunk container block (ContainerId %1, Generation %2, Buffer %3, Offset %4, Length %5, IoType %6, Synchronous %7)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20505</td><td>Read chunk container block completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20506</td><td>Clear chunk container block (Buffer %1, Size %2, BufferType %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20507</td><td>Clear chunk container block completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20508</td><td>Copy chunk (Buffer %1, Size %2, BufferType %3, BufferOffset %4, OutputCapacity %5)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20509</td><td>Copy chunk completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20510</td><td>Initialize file cache (UnderlyingFileObject %1, CacheFileSize %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20511</td><td>Initialize file cache completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20512</td><td>Map file cache data (CacheFileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20513</td><td>Map file cache data completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20514</td><td>Unpin file cache data(Bcb %1)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20515</td><td>Unpin file cache data completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20516</td><td>Copy file cache data (CacheFileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20517</td><td>Copy file cache data completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20518</td><td>Read underlying file cache data (CacheFileObject %1, UnderlyingFileObject %2, Offset %3, Length %4)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20519</td><td>Read underlying file cache data completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20520</td><td>Get chunk container file size (ContainerId %1, Generation %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20521</td><td>Get chunk container file size completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20522</td><td>Pin stream map (Stream %1, FileId %2, StartIndex %3, EntryCount %4)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20523</td><td>Pin stream map completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20524</td><td>Pin chunk container (ContainerId %1, Generation %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20525</td><td>Pin chunk container completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20526</td><td>Pin chunk (ContainerId %1, Generation %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20527</td><td>Pin chunk completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20528</td><td>Allocate pool buffer (ReadLength %1, PagingIo %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20529</td><td>Allocate pool buffer completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20530</td><td>Unpin chunk container (ContainerId %1, Generation %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20531</td><td>Unpin chunk container completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20532</td><td>Unpin chunk (ContainerId %1, Generation %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>20533</td><td>Unpin chunk completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24616</td><td>Dedup read processing (FileObject %1, Offset %2, Length %3, IoType %4)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24617</td><td>Dedup read processing completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24618</td><td>Get first stream map entry (TlCache %1, Stream %2, RequestStartOffset %3, RequestEndOffset %4)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24619</td><td>Get first stream map entry completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24620</td><td>Read chunk metadata (Stream %1, CurrentOffset %2, AdjustedFinalOffset %3, FirstChunkByteOffset %4, ChunkRequestsEndOffset %5, TlCache %6)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24621</td><td>Read chunk metadata completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24622</td><td>Read chunk data (TlCache %1, Stream %2, RequestStartOffset %3, RequestEndOffset %4)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24623</td><td>Read chunk data completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24624</td><td>Reference TlCache data (TlCache %1, Stream %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24625</td><td>Reference TlCache data completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24626</td><td>Read chunk data from stream store (Stream %1)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24627</td><td>Read chunk data from stream store completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24628</td><td>Assemble chunk data</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24629</td><td>Assemble chunk data completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24630</td><td>Decompress chunk data</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24631</td><td>Decompress chunk data completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24632</td><td>Copy chunk data in to user buffer (BytesCopied %1)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24633</td><td>Copy chunk data in to user buffer completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24634</td><td>Insert chunk data in to tlcache</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24635</td><td>Insert chunk data in to tlcache completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24636</td><td>Read data from dedup reparse point file (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24637</td><td>Read underlying file cache data completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24638</td><td>Prepare stream map (StreamContext %1)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24639</td><td>Prepare stream map completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24640</td><td>Patch clean ranges (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24641</td><td>Patch clean ranges completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24642</td><td>Writing data to dedup file (FileObject %1, Offset %2, Length %3, IoType %4)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24643</td><td>Writing data to dedup file completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24644</td><td>Queue write request on dedup file (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24645</td><td>Queue write request on dedup file completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24646</td><td>Do copy on write work on dedup file (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24647</td><td>Do copy on write work on dedup file completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24648</td><td>Do full recall on dedup file (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24649</td><td>Do full recall on dedup file completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24650</td><td>Do partial recall on dedup file (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24651</td><td>Do partial recall on dedup file completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24652</td><td>Do dummy paging read on dedup file (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24653</td><td>Do dummy paging read on dedup file completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24654</td><td>Read clean data for recalling file (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24655</td><td>Read clean data for recalling file completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24656</td><td>Write clean data to dedup file normally (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24657</td><td>Write clean data to dedup file completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24658</td><td>Write clean data to dedup file paged (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24659</td><td>Write clean data to dedup file paged completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24660</td><td>Recall dedup file using paging Io (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24661</td><td>Recall dedup file using paging Io completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24662</td><td>Flush dedup file after recall (FileObject %1)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24663</td><td>Flush dedup file after recall completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24664</td><td>Update bitmap after recall on dedup file (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24665</td><td>Update bitmap after recall on dedup file completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24666</td><td>Delete dedup reparse point (FileObject %1)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24667</td><td>Delete dedup reparse point completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24668</td><td>Open dedup file (FilePath %1)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24669</td><td>Open dedup file completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24670</td><td>Locking user buffer for read</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24671</td><td>Locking user buffer for read completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24672</td><td>Get system address for MDL</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24673</td><td>Get system address for MDL completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24674</td><td>Read clean dedup file (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24675</td><td>Read clean dedup file completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24676</td><td>Get range state (Offset %1, Length %2)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24677</td><td>Get range state completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24678</td><td>Get chunk body</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24679</td><td>Get chunk body completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24680</td><td>Release chunk</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24681</td><td>Release chunk completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24682</td><td>Release decompress chunk context (BufferSize %1)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24683</td><td>Release decompress chunk context completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24684</td><td>Prepare decompress chunk context (BufferSize %1)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24685</td><td>Prepare decompress chunk context completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24686</td><td>Copy data to compressed buffer (BufferSize %1)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24687</td><td>Copy data to compressed buffer completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24688</td><td>Release data from TL Cache</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24689</td><td>Release data from TL Cache completed %1</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24690</td><td>Queue async read request (FileObject %1, Offset %2, Length %3)</td></tr>
<tr><td>Microsoft-Windows-Deduplication</td><td>24691</td><td>Queue async read request complete %1</td></tr>
</table>
