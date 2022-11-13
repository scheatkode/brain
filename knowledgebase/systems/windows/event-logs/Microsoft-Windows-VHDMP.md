# Microsoft-Windows-VHDMP

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>1</td><td>The VHD %1 has come online (surfaced) as disk number %2.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>2</td><td>The VHD %1 has been removed (unsurfaced) as disk number %2.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>3</td><td>Failed to surface VHD %1. Error status %2.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>4</td><td>Failed to surface VHD %1. Surface attempt was cancelled.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>5</td><td>Failed to %1 VHD %2. Error status %3.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>6</td><td>Operation failed on VHD %2. Operation type %1. Error status %3.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>7</td><td>The Vhd Chain for VHD %4 is corrupted. The expected LastWriteGUID %2 (%3) did not match the parent&#39;s actual LastWriteGUID (%1).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>8</td><td>The change tracking file for VHD %1 is corrupted and cannot be read. No change tracking information will be available for this VHD, and change tracking will need to be enabled again before changed are tracked.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>9</td><td>The VHD file %1 has been modified without updating its associated change tracking file. Because the consistency of the change tracking information cannot be ensured, the change tracking data has been reset. No change tracking information will be available for this VHD, and change tracking will need to be enabled again before changed are tracked.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>10</td><td>Error %2 occured when attempting to update the change tracking file for VHD %1. This will invalidate the file&#39;s change tracking information. Change tracking will not be available for this VHD until change tracking is enabled again.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>11</td><td>Surface for VHD %2 is invalidated and will be removed (unsurfaced) because of a %1 operation failure with status %3.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>50</td><td>Performing %1 VHD for %2 (target &#39;%3&#39;).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>51</td><td>Successfully performed %1 VHD %2.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>100</td><td>Vhd resiliency initiated for %1 (VM ID: %2). A %3 IO failed with error %4.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>101</td><td>Vhd resiliency successfully recovered %1 (VM ID: %2).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>102</td><td>Vhd resiliency failed to recover %1 (VM ID: %2) with error %3.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>110</td><td>Recovery initiated for %1 (VM ID: %2) due to an IO failure with error %3.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>111</td><td>Recovery succeeded for %1 (VM ID: %2).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>112</td><td>Recovery failed for %1 (VM ID: %2) with error %3.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>113</td><td>File %1 is invalidated (VM ID: %2) from current mode %3 with error %4. Any recovery in process will be failed and the virtual disk will be invalidated as well.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>114</td><td>Waiting on file (%4) recovery for %1 (VM ID: %2) due to an IO failure with error %3.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>115</td><td>Waiting on file (%4) recovery for %1 (VM ID: %2) completed with status %3.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>116</td><td>File (%3) recovery succeeded for %1 (VM ID: %2).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>117</td><td>File (%4) recovery failed for %1 (VM ID: %2) with error %3.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>118</td><td>Failed to open file %1 with error %3. The file handle was previously invalidated due to a critical error. This operation will be retried periodically. (VM ID: %2).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>119</td><td>File %1 has been closed before initiating a recovery attempt. The file was open in mode %3. (VM ID: %2).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>120</td><td>Recovery attempt initiated for virtual disk %1 (VM ID: %2).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>121</td><td>Recovery attempt completed successfully for virtual disk %1 (VM ID: %2).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>122</td><td>Recovery attempt for virtual disk %1 failed with status %3 (VM ID: %2).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>123</td><td>Reopening handles to file %1 (VM ID: %2).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>124</td><td>Waiting for handles to file %1 to be reactivated (VM ID: %2).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>125</td><td>Recovery attempt completed for file %1 with status %3 (VM ID: %2).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>126</td><td>I/O failed with status %3 on file %1 (VM ID: %2).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>208</td><td>Change Tracking has been enabled for the VHD %1 (%2) with log file %3.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>209</td><td>Change Tracking has been disabled for the VHD %1 (%2).</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>210</td><td>Change Tracking for the VHD %1 to the log file %2 has been stopped due to the error %3.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>211</td><td>Flushing of the header of the log file %1 has failed due to error %2.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>212</td><td>Flushing of the buffers to the log file %1 has failed due to error %2.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>213</td><td>Opening the log file %1 for tracking has failed due to error %2.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>214</td><td>Offline changes are detected for VHD %2. Log file: %1, VHD time: %4, Log file time: %5</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>1001</td><td>Starting an IO.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>1002</td><td>Completing an IO.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>1010</td><td>A %4 %3 IO to %1 (VM ID: %2) failed with error %7. Recovery of this virtual disk has been initiated. If this IO was initiated by a VM then it will be internally retried later when the virtual disk has successfully recovered.</td></tr>
<tr><td>Microsoft-Windows-VHDMP</td><td>1011</td><td>A %4 %3 IO to %1 (VM ID: %2) failed with error %7. Recovery for this virtual disk could not be initiated either because this is not a recoverable failure or recovery has failed or the virtual disk is in an invalid state.</td></tr>
</table>
