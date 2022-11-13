# Microsoft-Windows-AppModel-Exec

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>100</td><td>DepMgr: Removed suspension group from the graph, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>101</td><td>Not set app %1 into halted state because it should wait for other apps in the package halted first</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>102</td><td>Not set app %1 into halted state because other app in the package have not finished quiescing</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>103</td><td>Not terminate app %1, because target app %2 state = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>104</td><td>Updated current dependency graph (Removal : %1) with Source %2 and Target %3 for type %4 in return %5</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>105</td><td>Default time for %1 overridden to %2 ms</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>106</td><td>Creating hang report</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>107</td><td>Window %1 is hung in foreground</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>108</td><td>Window %1 is no longer hung in foreground</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>109</td><td>Waiting for WER reporting to finish on app %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>110</td><td>Hang reporting finished on app %1.  App termination status: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>111</td><td>Hung reporting finished on window %1 with result %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>112</td><td>_SubmitActivationHangWerReport(start): Aumid=%1, PIDs=%2 count=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>113</td><td>_SubmitActivationHangWerReport(stop): Aumid=%1, result=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>114</td><td>_UnregisterForStateChanges: fPackageLevel=%1, HRESULT is %2. Cookie is %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>115</td><td>Application %1 has successfully launched. HRESULT %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>116</td><td>Canceled launch grace timer, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>117</td><td>_InitializeLaunchGraceContext: Aumid=%1, fExtendedLaunch=%2, fEventExists=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>118</td><td>App %1 successfully launched and its launch grace period expired: removing suspend exemption</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>119</td><td>Forcefully terminating app, Aumid=%1 flags=%2, reason=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>120</td><td>CheckTerminationBeforeSwitch: Should terminate: %1, Aumid=%2, HRESULT=%3, reason=%4, fIsMisbehaving=%5</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>121</td><td>Termination requested for %1 - flags %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>122</td><td>Failing TerminateApp due to pending task completions: %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>123</td><td>Terminating %1 immediately</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>124</td><td>Uninstalling background work items for %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>125</td><td>Termination of %1 scheduled for %2 ms in future</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>126</td><td>Sent window message to the default immersive browser with HRESULT %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>127</td><td>Attempting to terminate app %1 prior to new app launch due to pending termination</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>128</td><td>EvaluateAndTerminatePid: PID: %1. HRESULT: %2. Package State: %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>129</td><td>Exempting application %1 from suspend while it is being launched</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>130</td><td>Exemption manager %1 is requesting a higher minimum priority %2 for %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>131</td><td>Debug mode is enabled for %1, so it will run at %2 priority</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>132</td><td>Handling logoff, %1 will run at %2 priority</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>133</td><td>Throttling has been disabled, so %1 will run at %2 priority</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>134</td><td>Suspend denied due to new key debounce, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>135</td><td>Suspend denied due to debug mode, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>136</td><td>Not suspending application %1 due to exemption %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>137</td><td>_EvaluateAndSuspendApplication: PsmKey=%1, fIsSuspendAllowed=%2, HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>138</td><td>_ReevaluatePolicy: Ignoring debug mode app, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>139</td><td>ManagePreExistingApps(start)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>140</td><td>ManagePreExistingApps: PsmKey=%1, Aumid=%2, hr=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>141</td><td>ManagePreExistingApps(stop)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>142</td><td>RequestSuspendTimeout called for application %1 and timeout %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>143</td><td>Debug mode enabled, PkgFamilyName=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>144</td><td>Debug mode disabled, PkgFamilyName=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>145</td><td>Set Package %1, Timeout to %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>146</td><td>ResumeDebugModePackage(start): package=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>147</td><td>ResumeDebugModePackage(stop): package=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>148</td><td>SuspendDebugModePackage(start): package=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>149</td><td>SuspendDebugModePackage(stop): package=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>150</td><td>MultiAppSuspendAndTerminateSync(start): cPsmKeys=%1, suspendTrigger=%2, terminateReason=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>151</td><td>MultiAppSuspendAndTerminateSync(stop): cPsmKeys=%1, suspendTrigger=%2, terminateReason=%3, HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>152</td><td>MultiPackageSuspendAndTerminateSync(start): cPsmKeys=%1, suspendTrigger=%2, terminateReason=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>153</td><td>MultiPackageSuspendAndTerminateSync(stop): cPsmKeys=%1, suspendTrigger=%2, terminateReason=%3, HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>154</td><td>MultiPackageSuspendAndPendTerminateSync(start): cPsmKeys=%1, suspendTrigger=%2, terminateReason=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>155</td><td>MultiPackageSuspendAndPendTerminateSync(stop): cPsmKeys=%1, suspendTrigger=%2, terminateReason=%3, HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>156</td><td>TerminateSync(start): PsmKey=%1, type=%2, reason=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>157</td><td>TerminateSync(stop): PsmKey=%1, hrLogReason=%2, hrTermination=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>158</td><td>TerminatePackageSync(start): Package=%1, type=%2, reason=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>159</td><td>TerminatePackageSync(stop): Package=%1, fPlmKnowsPackage=%2, HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>160</td><td>_TerminateAllSuspendedApplications(start)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>161</td><td>_TerminateAllSuspendedApplications(stop): HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>162</td><td>Application %1 is blocking Connected Standby</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>163</td><td>Exiting Connected Standby</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>164</td><td>All packages have been suspended or terminated. Notify PDC. Call to PdcNotificationClientAcknowledge() returned %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>165</td><td>Kernel State Change Callback: There were %1 PIDs present in the callback data</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>166</td><td>Kernel State Change Callback: The state source was %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>167</td><td>PDC_CONTROL_ABORT: PdcNotificationClientAcknowledge(STATUS_SUCCESS) returned %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>168</td><td>Not terminating application %1 in _EvaluateAndTerminateApplication because it contains a running IImmersiveApplication</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>169</td><td>Not terminating application %1 in _EvaluateAndTerminateApplication because it is a long running app</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>170</td><td>Not terminating application %1 in _EvaluateAndTerminateApplication due to pending task completion</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>171</td><td>Not terminating application %1 in _EvaluateAndTerminateApplication due to Launch Grace</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>172</td><td>Not terminating application %1 in _EvaluateAndTerminateApplication due to debug mode</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>173</td><td>Not terminating application %1 in _EvaluateAndTerminateApplication due to application had already been terminated</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>174</td><td>_EvaluateAndTerminateApplication: Skipping child suspension group, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>175</td><td>An empty application was detected. Setting pending termination for application %1, HRESULT %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>176</td><td>Parent allowed suspension for child app, childPsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>177</td><td>GroupChildWithParent: ChildPsmKey=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>178</td><td>Call a command line &#39;%1&#39; to notify default browser with result %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>179</td><td>Read executable path from registry with result %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>180</td><td>Application %1 was added to PLM Data Store and registering for PSM notification</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>181</td><td>Resume the PPLE app %1 when receiving the PSM new key notification</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>182</td><td>An orphaned prereq application was detected. Setting pending termination for application %1, HRESULT %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>183</td><td>Not terminating dependent application %1 in _EvaluateAndTerminateDependentApplication due other dependency applications</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>184</td><td>_EvaluateAndTerminateSourceApplication: Aumid=%1, exemption=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>185</td><td>An force termination exemption Application was detected. Setting pending termination for application %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>186</td><td>StateMgr: State queued, PsmKey=%1, state=%2, HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>187</td><td>StateMgr: OnApplicationStarted set to active, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>188</td><td>StateMgr: OnApplicationStarted finished, PsmKey=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>189</td><td>StateMgr: App&#39;s current state has changed, PsmKey=%1, state=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>190</td><td>StateMgr: OnApplicationTerminated(start), PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>191</td><td>StateMgr: Application terminated signaled, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>192</td><td>StateMgr: OnApplicationTerminated(stop), PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>193</td><td>StateMgr: GetTerminateSyncData, PsmKey=%1, hr=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>194</td><td>StateMgr: _ProcessStateQueue(start): PsmKey=%1, state=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>195</td><td>StateMgr: _ProcessStateQueue(stop): PsmKey=%1, state=%2, HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>196</td><td>StateMgr: Queue&#39;s pause state has changed to %2, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>197</td><td>StateMgr: App&#39;s committed state has changed, PsmKey=%1, state=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>198</td><td>Enabling debug mode on package %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>199</td><td>Disabling debug mode on package %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>200</td><td>Suspending package %1 via debug API. HRESULT: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>201</td><td>Resuming package %1 via debug API. HRESULT: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>202</td><td>Terminating package %1 via debug API. HRESULT: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>203</td><td>Default time for %1 overridden to %2 ms</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>204</td><td>ReportActivationHangSync: Halt application Aumid=%1, result=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>205</td><td>_SubmitActivationHangWerReport(start): Aumid=%1, PIDs=%2 count=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>206</td><td>_SubmitActivationHangWerReport(stop): Aumid=%1 canceled(%2) result=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>207</td><td>PLM doesn&#39;t swap out application %1 due to its swap state %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>208</td><td>PLM termination policy started on background thread because application %1 failed to outswap</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>209</td><td>PLM termination policy finished. Outswapping returned status %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>210</td><td>PLM memory policy will be aggressive because this is a disconnected session</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>211</td><td>PLM termination policy start</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>212</td><td>PLM termination policy stop</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>213</td><td>PLM termination policy triggered by in use memory of %1 MiB</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>214</td><td>PLM termination policy triggered by commit charge of %1 MiB</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>215</td><td>MemoryPolicyWatcherTerminateCommitCharge</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>216</td><td>PLM empty policy triggered by in use memory of %1 MB</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>217</td><td>PLM memory policy does not allow termination of application %1 for reason %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>218</td><td>PLM memory policy allows termination of application %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>219</td><td>Application %1 was hidden %2 seconds ago</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>220</td><td>Application %1 is the clipboard owner</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>221</td><td>PLM empty policy start</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>222</td><td>PLM empty policy ignoring application %1 with error code %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>223</td><td>PLM empty policy finished after emptying %1 MiB</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>224</td><td>PLM termination policy enumerated %1 applications</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>225</td><td>PLM memory policy chose application %1 as its termination candidate, over old candidate application %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>226</td><td>PLM memory policy will terminate application %1 with memory size %2 MiB and score %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>227</td><td>PLM memory policy received MemWatcher event</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>228</td><td>PLM memory policy received MemWatcher event</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>229</td><td>Package exemption manager denied suspend for %1.  Ref counts are LAUNCH=%2, PSMREG=%3, PSMPENDING=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>230</td><td>Package Exemption Manager: ReferenceAdded:%1, %2 ref to application %3. The ref counts are now LAUNCH=%4, PSMREG=%5, and PSMREGPENDING=%6</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>231</td><td>Package %1 added to the package data store</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>232</td><td>Resetting priority to unpause the suspension group, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>233</td><td>Changed the priority of %1 to %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>234</td><td>AllowServiceOfPackages(start): cPackages=%1, fNotifyBi=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>235</td><td>AllowServiceOfPackages(stop): HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>236</td><td>FinishedServiceOfPackages(start): cPackages=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>237</td><td>FinishedServiceOfPackages(stop): HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>238</td><td>AllowUninstallOfPackage(start): package=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>239</td><td>AllowUninstallOfPackage(stop): package=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>240</td><td>Forcefully terminating misbehaving app %1 due to activation failure %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>241</td><td>App %1: Change = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>242</td><td>PsmKey %1 has state %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>243</td><td>Changing app state through BI, PsmKey=%1, state=%2 terminate action=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>244</td><td>Changing the package state of %1 through BI to %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>245</td><td>OnAfterQuiescing: Quiesce began for PsmKey=%1, suspendTrigger=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>246</td><td>_CompleteQuiesceHelper: Queued termination for timed-out PsmKey %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>247</td><td>Quiesce completed for PsmKey=%1, reason=%2, suspendTrigger=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>248</td><td>Suspend trigger updated for PsmKey=%1, suspendTrigger=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>249</td><td>ExtendQuiesceTimeout: PsmKey=%1, request=%2 ms, HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>250</td><td>_CompleteQuiesceHelper: Ignore timed-out PsmKey %1 as is being debugged</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>251</td><td>ResumeHelper: Application resume(start), PsmKey=%1, reason=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>252</td><td>ResumeHelper: Application resume(stop), PsmKey=%1, reason=%2, HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>253</td><td>Resume reason updated for PsmKey=%1, reason=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>254</td><td>RPC 0-&gt;1 transition detected for %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>255</td><td>RPC exemption was granted for application %1. KernelRequest Value: %2. Runaway RPC: %3.  RPC Debounce %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>256</td><td>RPC debounce received for package %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>257</td><td>Application %1 has successfully launched. HRESULT %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>258</td><td>Application %1 termination is blocked. PreserverProcessRequest = %2, TaskCompletionCategory = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>259</td><td>PdcSystem activation (Activate = %1). Result = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>260</td><td>NetworkAudio entries: %1, IsNetworkReferenced: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>261</td><td>App %1 is Sharing</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>262</td><td>Share %1 has started in app %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>263</td><td>Share %1 in app %2 has stopped</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>264</td><td>Queued termination reason updated for PsmKey=%1, reason=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>265</td><td>ClearTerminationTypesForForgottenPackage(start): PkgFamilyName=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>266</td><td>Cleared termination type for forgotten app, Aumid=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>267</td><td>ClearTerminationTypesForForgottenPackage(stop): PkgFamilyName=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>268</td><td>Writing to termination type reg key for Aumid=%1, type=%2, HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>269</td><td>Reading termination type reg key for Aumid=%1, type=%2, HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>270</td><td>_ExtendForResourceStarvation: PsmKey=%1, TimerType=%2, newRelativeExpirationTimeMs=%3, ElapsedMs=%4, CpuRunningMs=%5, CpuReadyMs=%6, IoNormalMs=%7</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>271</td><td>Foreground resume delay %1 milliseconds</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>272</td><td>Suspend allowed for %1 - Session not active</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>273</td><td>Suspend denied due to a visible window or visibility debounce, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>274</td><td>Suspend denied for %1 - UserRequest non-zero</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>275</td><td>Suspend denied for %1- failure %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>276</td><td>OnWindowChanged: Aumid=%1, Hwnd=%2, change=%3, fDeferredVisibility=%4, HRESULT=%5</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>277</td><td>Starting Session Idle Debounce</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>278</td><td>Session is active</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>279</td><td>Session is idle</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>280</td><td>PlmGetPackageFullNameFromAppId, Aumid=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>281</td><td>Session idle state change -- calling _ReevaluatePolicy</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>282</td><td>RegisterForActivationStateChanges: Act:%1 App:%2 HRESULT is %3. Cookie is %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>283</td><td>UnregisterForActivationStateChanges: Cookie is %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>284</td><td>Can Auto Terminate app %1 %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>285</td><td>TerminateApplicationBeforeActivation(start): Aumid=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>286</td><td>TerminateApplicationBeforeActivation: wait for terminate, Aumid=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>287</td><td>TerminateApplicationBeforeActivation(stop): Aumid=%1, reason=%2, HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>288</td><td>s_SuspendPackagesAtLogOff(start)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>289</td><td>s_SuspendPackagesAtLogOff(stop): HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>290</td><td>StateMgr: OnApplicationStarted still halted, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>291</td><td>Added Task Completion under %1 for application %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>292</td><td>Removed Task Completion under %1 for application %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>293</td><td>Illegal state change happened to App: %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>294</td><td>EnableDebugMode failed: %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>295</td><td>DisableDebugMode: RoDisableDebuggingForPackage failed with result %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>296</td><td>DisableDebugMode: OnDebugModeDisabled failed with result %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>297</td><td>DisableDebugMode: Enabling activation timeout failed with result %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>298</td><td>DisableDebugMode failed: %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>299</td><td>Couldn&#39;t open process: %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>300</td><td>PLM failed to process a hang for window %1 with error code %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>301</td><td>PLM outswap application %1 failed to invoke with error code %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>302</td><td>PLM couldn&#39;t find any process for application %1, and handle it as non-large app</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>303</td><td>PLM failed to decide application %1 is large or not with error code %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>304</td><td>PLM empty policy failed to process application %1 with error code %2.  Ignoring the application</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>305</td><td>PLM empty policy failed to empty application %1 with error code %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>306</td><td>PLM failed to terminate application %1 as empty policy with error code %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>307</td><td>PLM empty policy failed to enumerate applications with error code %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>308</td><td>PLM termination policy skipping application %1, which is not registered with PLM</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>309</td><td>PLM memory policy failed to queue work with error code %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>310</td><td>GetPackageData called on a Package %1, which is not in the PLM Package Data Store</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>311</td><td>ERROR: Failed to set priority to %1, PsmKey=%2, NTSTATUS=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>312</td><td>AllowServiceOfPackages: Failed to terminate package=%1, type=%2, HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>313</td><td>_CheckServicingPackages: Failed to enumerate app, PsmKey=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>314</td><td>_CheckServicingPackages: Failed to enumerate package, PkgFullName=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>315</td><td>GetImmersiveApplicationCount failed with error code %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>316</td><td>Background workitems were force terminated, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>317</td><td>ChangeApplicationBiState failed: %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>318</td><td>Background workitems for package %1 were force terminated</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>319</td><td>ChangePackageBiState failed: %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>320</td><td>ApplicationProcesses failed to track process ID %1 with error code %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>321</td><td>OnBeforeQuiescing: Failed to allocate memory for PsmKey=%1, suspendTrigger=%2, HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>322</td><td>OnAfterQuiescing: Quiesce failed for PsmKey=%1, suspendTrigger=%2, HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>323</td><td>ERROR: _CompleteQuiesceHelper: Failed to terminate timed-out PsmKey %1 with result %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>324</td><td>ERROR: QuiesceHelper: App forgotten while still Quiescing, PsmKey=%1, suspendTrigger=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>325</td><td>Failed to query the wake counters associated with application %1. NTSTATUS: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>326</td><td>_AllAppSyncOperationHelper: Failed to allocate memory for PsmKey=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>327</td><td>_MultiAppSyncOperationHelper: Failed to perform operation on PsmKey=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>328</td><td>_MultiAppSyncOperationHelper: Failed in wait, HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>329</td><td>_MultiPackageSyncOperationHelper: Failed to enumerate PsmKey=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>330</td><td>_MultiPackageSyncOperationHelper: Failed to find package in data store, PkgFullName=1%, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>331</td><td>Failed to suspend and terminate apps, cPsmKeys=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>332</td><td>Could not initialize an extended launch grace period for app %1 with HRESULT %2 -- falling back to normal launch grace</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>333</td><td>App %1 failed to show a window after launch. Will attempt to terminate it now</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>334</td><td>Failed to get a window for an app; assuming that the app&#39;s window is not hung, Aumid=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>335</td><td>Failed to query hidden time for visibility debounce for app %1 with error code %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>336</td><td>_StartNewKeyDebounce: Error Result=%2, PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>337</td><td>StartTrackingNewApp failed with %1. The application launch is not protected and the app might potentially get suspended inappropriately</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>338</td><td>ERROR: Failed to enumerate exemption targets starting from PsmKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>339</td><td>Failed to enumerate existing applications from PSM with error code %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>340</td><td>PsmRegisterApplicationNotification failed for application %1 with status %2.  PLM&#39;s cache says that the application&#39;s registration is: %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>341</td><td>ERROR: Failed to enumerate force termination targets starting from PsmKey=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>342</td><td>Application %1 failed to be added in PLM Data Store</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>343</td><td>Failed to initialize string to send app notification %1 state %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>344</td><td>Failed to initialize string to remove app %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>345</td><td>Failed to add %1 for application %2. The application doesn&#39;t have BTC_AUDIO background task capability</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>346</td><td>Failed to initialize CmApi</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>347</td><td>Task completion manager failed to add %1 to its sharing cache with error code %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>348</td><td>ClearTerminationTypesForForgottenPackage: Failed to clear termination type for app, Aumid=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>349</td><td>ERROR: Failed to schedule the visibility debounce, PsmKey=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>350</td><td>OnWindowChanged ERROR: Failed to queue thread for Aumid=%1, Hwnd=%2, change=%3, HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>351</td><td>ERROR: Failed to schedule deferred visibility timer, PsmKey=%1, HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>352</td><td>WaitOnBiNotifyNewSession HRBiNotifyNewSession=%1 HRBiNotifyNewUser=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>353</td><td>RegisterKernelNotifications HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>354</td><td>TCExemptionManager CompleteInitialization HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>355</td><td>PlmActivationManager CompleteInitialization HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>356</td><td>Plm CSDiagnostics CompleteInitialization HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>357</td><td>Plm LogOff/LogOn Registration HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>501</td><td></td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>502</td><td></td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>503</td><td></td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>504</td><td></td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>505</td><td>BM: Queued evaluate WorkItem: %3 EventType: %5 Action: %6 PsmKey: %1 HostJobType: %2 EntryPoint: %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>506</td><td>BM: Evaluate returned WorkItem: %3 EventType: %5 Action: %6 PsmKey: %1 HostJobType: %2 EntryPoint: %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>507</td><td>BM: TaskActivated WorkItem: %1 Instance: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>508</td><td>BM: TaskCompleted WorkItem: %1 Instance: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>509</td><td>BM: TaskCanceled WorkItem: %1 Instance: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>510</td><td>BM: Policy evaluate returned WorkItem: %3 EventType: %4 Action: %5 WallClockLimit: %6 PsmKey: %1 HostJobType: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>511</td><td>BM: TaskActivating WorkItem: %1 Instance: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>512</td><td>BM: Enter %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>513</td><td>BM: Exit %1, HR=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>514</td><td>BM: TerminateHost WorkItem: %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>515</td><td>BM: ResourceSet invalidated for WorkItem: %1 Instance: %2.  This usually means the host has crashed before a ResourceSet could be applied.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>516</td><td>BM: OnAcquired ignoring invalid CallbackId (%1).</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>517</td><td>BM: TryAcquireResourceSet returning HR=&#39;%4&#39; PsmKey=&#39;%1&#39;; WorkItemId=&#39;%2;&#39; CallbackId=&#39;%3&#39;.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>517</td><td>BM: TryAcquireResourceSet returning HR=&#39;%4&#39; PsmKey=&#39;%1&#39; WorkItemId=&#39;%2;&#39; CallbackId=&#39;%3&#39; HostId=&#39;%5&#39; ResourceSetId=&#39;%6&#39;.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>518</td><td>BM: TryAcquireHostResourceSet returning HR=&#39;%2&#39; PsmKey=&#39;%1&#39;.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>518</td><td>BM: TryAcquireHostResourceSet returning HR=&#39;%2&#39; PsmKey=&#39;%1&#39; HostId=&#39;%3&#39; ResourceSetId=&#39;%4&#39;.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>519</td><td>BM: OnApplicationStateChanged returning State=&#39;%2&#39; PsmKey=&#39;%1&#39; HR=&#39;%3&#39;.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>520</td><td>BM: OnAcquired received for CallbackId: %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>521</td><td>BM: OnAcquired request ignored for CallbackId: %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>522</td><td>BM: ActivateDeferredWorkItem WorkItem: %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>523</td><td>BM: ActivateDeferredWorkItem discarded WorkItem: %1 because of Status: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>524</td><td>BM: Enter %1 WorkItem: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>525</td><td>BM: Enter %1 WorkItem: %2 TaskInstanceId: %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>526</td><td>BM: Exit %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>527</td><td>BM: Failed to load settings for event %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>528</td><td>BM: Failed to load settings for event %1 with error %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>529</td><td>BM: Failed to load policy for CLSID: %1, for EventType %2 with error %3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>530</td><td>BM: Failed to load the policies with error %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>531</td><td>BM: Evaluate returned WorkItem: %3 EventType: %5 WallClockLimit: %6 PsmKey: %1 HostJobType: %2 EntryPoint: %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>532</td><td>BM: TaskWallClockActive WorkItem: %1 Instance: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>533</td><td>BM: TaskWallClockExpired WorkItem: %1 Instance: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>534</td><td>BM: Policy returned HRESULT: %3 for WorkItem: %2 PsmKey: %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>535</td><td>BM: Canceling task for high energy usage PsmKey: %1 WorkItem: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>536</td><td>BM: Ignoring cancelation request (whitelisted) for high energy usage PsmKey: %1 WorkItem: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>537</td><td>BM: Session(%1) started, session initialization returned %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>538</td><td>BM: Session(%1) ended.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>539</td><td>BM: Activation ignored due to no Session(%1): PsmKey: %2 WorkItem: %3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>540</td><td>BM: Failed to acquire a ResourceSet for WorkItem: %1 with error %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>541</td><td>BM: WorkItem: %1 is being debugged. Setting wallclock limit to 0.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>542</td><td>BM: EvaluateActivationAction for WorkItem: %1 HRESULT: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>543</td><td>BM: Skipped Buffering Exempted task with SQMId: %1 PsmKey: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>544</td><td>BM: Dropped Exempted task that came before SessionReady with SQMId: %1 PsmKey: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>545</td><td>BM: Activation ignored due to no User(%1): PsmKey: %2 WorkItem: %3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>546</td><td>BM: User Logon Session: %1 User: %2 HRESULT: %3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>547</td><td>BM: User Logoff Session: %1 User: %2 HRESULT: %3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>548</td><td>BM: Pending activation discarded for work item (%1).</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>549</td><td>BM: Flushing ignored EvaluationState: %1 for WorkItem: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>550</td><td>BM: Flushing buffered activations.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>551</td><td>BM: Global Policy evaluate returned WorkItem: %3 EventType: %4 Action: %5 WallClockLimit: %6 PsmKey: %1 HostJobType: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>552</td><td>BM: A Session object for Session(%1) already exists.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>553</td><td>BM: ShellSuspendState changed, oldState: %1 newState: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>554</td><td>BM: DPLKeyState changed, oldState: %1 newState: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>555</td><td>BM: Canceling WorkItem: %1 due to DPL policy.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>556</td><td>BM: Dropping activation for WorkItem: %1 due to DPL policy.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>557</td><td>BM: Buffered activation for WorkItem: %1 due to Shell Ready policy.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>558</td><td>BM: Exempted activation for WorkItem: %1 due to Shell Ready policy.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>559</td><td>BM: Buffered activation for WorkItem: %1 due to Thermal Throttling policy.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>600</td><td>AM: Failed to read activation plugin registry with error code %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>601</td><td>AM: Failed to CoCreate activation plugin with error code %1 and CLSID %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>602</td><td>AM: Successfully created activation plugin with CLSID %1 from the registry.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>603</td><td>AM: Failed to register package if needed with error %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>604</td><td>AM: Failed trying to register package by family name async during activation with error %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>605</td><td>AM: Failed trying to wait for the completion of the register package by family async during activation with error %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>700</td><td>BAM: Added Package: %1 UserSid: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>701</td><td>BAM: Removed Package: %1 UserSid: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>702</td><td>BAM: Added Application: %1 UserSid: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>703</td><td>BAM: Removed Application: %1 UserSid: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>704</td><td>BAM: AccessState Changed for Package: %1 OldState: %2 NewState: %3 UserSid: %4.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>705</td><td>BAM: BackgroundExecutionManager::RequestAccessAsync called for Application: %1 Returned_AccessState: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>706</td><td>BAM: BackgroundExecutionManager::GetStatus called for Application: %1 Returned_AccessState: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>707</td><td>BAM: BackgroundExecutionManager::RemoveAccess called for Application: %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>708</td><td>BAM: Sanitizing data for package: %1 HRESULT: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>709</td><td>BAM: ReregisteredPackage called during _SanitizeStore for package: %1 HRESULT: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>710</td><td>BAM: UnregisterPackage called during _SanitizeStore for package: %1 HRESULT: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>711</td><td>BAM: BackgroundExecutionManager::RequestAccessKindAsync called for Application: %1 Requested_AccessKind: %2 Returned: %3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>750</td><td>FAM: NotifyTaskInstanceCompleted, TaskID:%1, hr:%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>751</td><td>FAM: NotifyTaskInstanceRunning, TaskID:%1 Timer - %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>752</td><td>FAM: RegisterForegroundAgentManagerProxy:PID=%1, ConsumerTaskId=%2, Option=%3, hr=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>753</td><td>FAM: UiForeground:Memory:%1MB, CPU:%2%%</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>754</td><td>FAM: CreateAgentLaunchRequest, TaskID:%1, Queue:%2, hr:%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>755</td><td>FAM: CancelAgentRequest, TaskID:%1, CancelType=%2, hr:%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>756</td><td>FAM: AbortAgentRequestsInternal, hr:%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>757</td><td>FAM: CompleteAgent, TaskID:%1, hr:%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>758</td><td>FAM: PrioritizeAgentRequest, TaskID:%1, hr:%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>759</td><td>FAM: OnForegroundAppChanged()-Abort agents</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>760</td><td>FAM: OnRelease()</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>761</td><td>FAM: NotifyConsumer, Notification:%1, TaskID:%2, hrResult:%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>762</td><td>FAM: AcquireSharedResourceSet, ProductID:%1, ConsumerPid:%2, Pending:%3, hr:%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>763</td><td>FAM: ReleaseResourceSet, #%1, hr:%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>764</td><td>FAM: TimerExpired:TerminateHost[PID=%1]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>765</td><td>FAM: AcquireResourceSet, #%1, Mem:%2MB, CPU:%3%%, hr:%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>766</td><td>FAM: AbortTask: TaskInstanceID = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>801</td><td>OTM: Read settings. First retry timeout = %1 ms, Second retry timeout = %2 ms, Third retry timeout = %3 ms, Maximum Retry Timeout = %4 ms</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>802</td><td>OTM: Task instance %2 of product %1 completed</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>803</td><td>OTM: TaskHost of product %1 has crashed</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>804</td><td>OTM: TaskHost of product %1 has been completed by PacMan</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>805</td><td>OTM: Launching OEM boot agents</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>806</td><td>OTM: Launching boot agents for product %1 failed with error %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>807</td><td>OTM: Launch boot agents for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>808</td><td>OTM: Running OnUpdateStarted for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>809</td><td>OTM: Restarting boot agents for product %1 after update</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>810</td><td>OTM: Start menu is ready.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>811</td><td>OTM: Could not launch OEM boot agents. QueueUserWorkItem failed with error %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>812</td><td>OTM: Could not process update notification for OEM application. QueueUserWorkItem failed with error %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>813</td><td>OTM: Could not process update notification for OEM application. ProcessUpdateNotification failed with error %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>814</td><td>OTM: OemTaskManager::NotifyTaskInstanceCompleted failed with error %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>815</td><td>OTM: OemTaskManager::NotifyTaskHostCompleted failed with error %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>816</td><td>OTM: OemApp::DumpAgents failed with error %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>817</td><td>OTM: An error occurred. Hr = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>818</td><td>OTM: No apps with ServiceAgents were found.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>819</td><td>OTM: No ServiceAgent task found for product %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>820</td><td>OTM: AbortTask: TaskInstanceID = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>851</td><td></td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>852</td><td></td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>853</td><td></td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>854</td><td></td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>861</td><td>PLM: Start tracking new app user %1 app %2, contract %3, hr = %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>862</td><td>PLM: Application launched %1 in app %2, hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>863</td><td>PLM: Application resume %1 in app %2, hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>864</td><td>PLM: Suspend-Terminate(%3) task %1 in app %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>865</td><td>PLM: Suspend-Terminate suspend of task %1 in app %2 exemption %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>866</td><td>PLM: Suspend-Terminate auto terminate(%3) task %1 in app %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>867</td><td>PLM: Suspend-Terminate task %1 in app %2, hr %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>868</td><td>PLM: Halt app %1, hr %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>869</td><td>PLM: Task resume %1 in app %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>870</td><td>PLM: Task cancel %1 in app %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>871</td><td>PLM: Task remove %1 in app %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>872</td><td>PLM: Queue Application State Change Notification for user %1 app %2 state %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>873</td><td>PLM: Queue Activation State Change Notification %1 state %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>874</td><td>PLM: Before Activate task %1 for user %2 in app %3, contract %4, hostid %5, hr = %6</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>875</td><td>PLM: After Activate task %1 with result %2, hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>876</td><td>PLM: ApplicationLayer=%1 Set Foreground new task %2, prev task %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>877</td><td>PLM: Add task %1 to user %2 and app %3, hr = %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>878</td><td>PLM: Create app for user %1, %2, new [app(%3) pkg(%4)], hr = %5</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>879</td><td>PLM: Add task %1 to user %2 and app %3, new [app(%4) pkg(%5)], hr = %6</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>880</td><td>PLM: Remove task %1, was found(%2)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>881</td><td>PLM: Remove app if empty from user %1, %2, hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>882</td><td>PLM: Remove pkg if empty from user %1, %2, hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>883</td><td>PLM: Send Application State Change Notification for user %1 app %2 state %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>884</td><td>PLM: Send Activation State Change Notification %1 state %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>886</td><td>PLM: Timer Started duration %1ms, hr %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>887</td><td>PLM: Timer Expired duration %1ms, hr %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>888</td><td>PLM: Abort task %1 reason %2, dump(%3)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>889</td><td>PLM: Task rehydrate %1 in app %2 contract %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>890</td><td>PLM: Start RPC suspension timer PSMKey=%1 WakeCounters=%2, hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>891</td><td>PLM: Cancel RPC suspension timer PSMKey=%1 app state=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>892</td><td>PLM: Terminate application PSMKey=%1 due to expired RPC suspension timeout</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>893</td><td>PLM: Application %1 cannot be terminated due to %2 exemption</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>894</td><td>PLM: Application %1 can be terminated</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>895</td><td>PLM: EvaluateAndTerminateApplication %1 cannot be terminated due to %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>896</td><td>PLM: EvaluateAndTerminateApplication %1, terminate hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>897</td><td>PLM: Terminate debounce app %1 current state %2 ultimate state %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>898</td><td>PLM: Terminate debounce app %1, hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>899</td><td>PLM: Terminate reason was cleared</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>900</td><td>PLM: Abort app user %1 app %2 reason %3, dump(%4)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>901</td><td>PLM: Watson dump NOT generated for user %1 app %2, process count %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>902</td><td>PLM: Watson dump start for user %1 app %2 reason %3 description %4, process %5 (%6)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>903</td><td>PLM: Watson dump information for user %1 app %2 product Id %3 title %4 version %5</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>904</td><td>PLM: Watson dump end for user %1 app %2, hr %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>905</td><td>PLM: Add Watson dump to user %1 app %2 process %3, hr %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>906</td><td>PLM: Failed to add Watson process info for process %1 user %2 app %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>907</td><td>PLM: Watson dump status changed pids(%1)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>908</td><td>PLM: Watson dump status changed, add process %1 user %2 app %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>909</td><td>PLM: Watson dump status changed, remove process %1 user %2 app %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>910</td><td>PLM: Watson dump status changed, unknown process %1 app %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>911</td><td>PLM: Watson add/remove(%2) error report task completion to process %1 (signaled %4), hr %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>912</td><td>PLM: Watson in progress for PSMKey %1, waiting...</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>913</td><td>PLM: Watson in progress finished for PSMKey %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>914</td><td>PLM: Extending RPC suspension timer PSMKey=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>915</td><td>PLM: Acquire network reference failed CM_RESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>916</td><td>PLM: Release network reference failed CM_RESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>917</td><td>PLM: Suspend-Terminate(%2) app %1 exemption %3, hr %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>918</td><td>PLM: Suspend-Terminate task %1 while dehydrating</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>919</td><td>PLM: Add user %1 sid %2 to data store, hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>920</td><td>PLM: Start launch grace for user %1 app %2, hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>921</td><td>PLM: Set Window Id for user %1 app %2 wnd %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>922</td><td>PLM: EvaluateLaunchGraceCompleted for user %1 app %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>923</td><td>PLM: Terminating reexisting app due to sihost restart with PSMKey %1, status %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>924</td><td>PLM: Terminating preexisting applications on sihost startup</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>925</td><td>PLM: Set Pause On Lock for user %1 app %2 value %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1051</td><td>AAM: Initiate activation for user %1 app %2 contract %3 task %4, hr %5</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1052</td><td>AAM: Initiate activation completed for task %2 (expected %1), hr %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1053</td><td>AAM: Initialize activation for user %1 app %2 contract %3 lightup(%5), hr %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1054</td><td>AAM: Validate activation, hr %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1055</td><td>AAM: Verify license for pkg %1, hr %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1056</td><td>AAM: Activate activation task %1 host %2, hr %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1057</td><td>AAM: Activation shim timer expired %1, hr %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1058</td><td>AAM: Initiate Core UI, hr %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1059</td><td>AAM: Release Core UI</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1060</td><td>AAM: Create Windows AAM, hr %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1061</td><td>AAM: Attempted remediation, hr %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1062</td><td>AAM: Failed while trying to find a remediation handler, hr %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1063</td><td>AAM: Failed while trying to find the package status, hr %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1064</td><td>AAM: Failed while trying to find the package origin, hr %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1065</td><td>AAM: Failed while trying to verify and initialize the activation, hr %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1066</td><td>AAM: Failed while trying to check roaming data, hr %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1071</td><td>AAM: Broker created plugins %1, expected %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1072</td><td>AAM: Broker initialize, hr %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1073</td><td>AAM: Broker start activate application %1 (%3 args) arg[0] %2 type %4 caller PID %5 (initialization count %6)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1074</td><td>AAM: Broker end activate application %1 launched PID %2 task %3, hr %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1075</td><td>AAM: Broker activate task with result for app %1 caller PID %2 caller task %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1076</td><td>AAM: Broker get result for PID %1 task %2 result %3, hr %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1077</td><td>AAM: Broker get task id for process %1 window %2 = task %3, hr %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1078</td><td>AAM: Broker init session manager, hr %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1079</td><td>AAM: Broker release session manager</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1080</td><td>AAM: Broker add task with result for parent %1, hr %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1081</td><td>AAM: Broker get task with result for parent %1, hr %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1082</td><td>AAM: Broker remove task with result for parent %1, hr %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1083</td><td>AAM: Broker create completed event for caller PID %1, hr %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1084</td><td>AAM: Broker get task with result for child %1, hr %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1085</td><td>AAM: Broker parent task completed %1 with child state %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1086</td><td>AAM: Broker child task completed %1 with state %2, hr %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1087</td><td>AAM: Broker task event signaled for parent %1 child %2 previous state %3, hr %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1088</td><td>AAM: Broker close task %1, hr %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1089</td><td>AAM: Broker activate application %1 arg[%3] %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1100</td><td>FM-ARP: ApplyResourceSetType ResourceSetType=%1 User=%2 PSMKey=%3 ResourceSet=%4 HRESULT=%5</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1101</td><td>FM-ARP: ApplyTerminal UserContext=%1 PsmKey=%2 ResourceSet=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1102</td><td>FM-ARP: RemoveInterruptiveUIAccess UserContext=%1 PsmKey=%2 ResourceSet=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1103</td><td>FM-ARP: ResetInterruptiveUIAccess UserContext=%1 PsmKey=%2 ResourceSet=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1104</td><td>FM-ARP: OnRelease UserContext=%1 PsmKey=%2 ReleaseAction=%3 ReleasedCachedResource=%4 ReleaseAppliedResource=%5 HRESULT=%6</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1105</td><td>FM-ARP: OnAcquired UserContext=%1 PsmKey=%2 ResourceSet=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1106</td><td>FM-ARP: OnOutOfMemory UserContext=%1 PsmKey=%2 ResourceSet=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1107</td><td>FM-ARP: ApplyResourceBoost User=%1 PsmKey=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1108</td><td>FM-ARP: AcquireResourceSet ResourceSetType=%1 Usercontext=%2 PsmKey=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1109</td><td>FM-ARP: Apply Cached Resource Set Usercontext=%1 PsmKey=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1110</td><td>FM-ARP: Clear Cached Resource User=%1 PSMKey=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1111</td><td>FM-ARP: Fire Cached ResourceCallback User=%1 PSMKey=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1200</td><td>FM-CAM: OnApplicationStateChangedEx UserContext=%1 PsmKey=%2 state=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1201</td><td>FM-CAM: AcquireForegroundResource UserContext=%1 PsmKey=%2 isPending=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1202</td><td>FM-CAM: OnResourceAcquired UserContext=%1 PsmKey=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1203</td><td>FM-CAM: OnResourceTimerExpired UserContext=%1 PsmKey=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1250</td><td>FM: TaskCompletion New Battery Saver State %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1251</td><td>FM: TaskCompletion Revoke Exemption PID=%1 AUMID=%2 TC=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1252</td><td>FM: TaskCompletion Apply(%3) Exemption PID=%1 TC=%2 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1253</td><td>FM-EEP: CheckProcessBackgroundEligibility ProcessId=%1 TaskCompletionCategory=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1254</td><td>FM-EEP: ApplyTaskCompletion ProcessId=%1 TaskCompletionCategory=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1255</td><td>FM-EEP: RevokeTaskCompletion ProcessId=%1 TaskCompletionCategory=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1256</td><td>FM-EEP: RequestExtendedExecution ProcessId=%1 Reason=%2 DeniedReason=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1257</td><td>FM-EEP: RegisterForExtensionRevokedEvent ProcessId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1258</td><td>FM-EEP: CompleteExtendedExecution ProcessId=%1 fIsResumed=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1259</td><td>FM-EEP: RevokeSuspensionExtension User=%1 PsmKey=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1260</td><td>FM-ARP: NotifyPendingResourceSetTransition ResourceSetType=%1 ResourceSet=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1261</td><td>FM-EEP: ApplyTaskCompletionResourceSet AppUserModelId=%1 fTimerExpiredCallback=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1262</td><td>FM-EEP: IsApplicationStateBackgroundEligibile User=%1 PsmKey=%2 fResult=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1263</td><td>FM-EEP: RevokeTaskCompletionExemption AppUserModelId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1264</td><td>FM-EEP: AllowBackgroundExecution User=%1 AppUserModelId=%2 DeniedReason=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1265</td><td>FM-EEP: OnPackageEnergyStateChange PackageFullName=%1 PackageState=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1266</td><td>FM-EEP: RegisterExtendedExecutionClient ProcessId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1267</td><td>FM-EEP: UnregisterExtendedExecutionClient ProcessId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1268</td><td>FM-EEP: UnregisterForExtensionRevokedEvent ProcessId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1269</td><td>FM-EEP: ApplyTaskCompletionResourceSet AppUserModelId=%1 TC=%2 isResourcePending =%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1270</td><td>FM-EEP: Task Completion Denied By EDP Policy ProcessId=%1 TC=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1271</td><td>FM-EEP: IsForegroundApplication Application=%1 Result=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1400</td><td>FM: Registering callback %1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1401</td><td>FM: Generate ActivationInstanceID Id=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1402</td><td>FM: +ActivationPrerequisitePhase ActivationInstanceId=%1 UserContext=%2 AUMID=%3 ContractId=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1403</td><td>FM: -ActivationPrerequisitePhase HRESULT=%1 fPending=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1404</td><td>FM: +Resume_RehydrationPhase ActivationInstanceId=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1405</td><td>FM: -Resume_RehydrationPhase ActivationInstanceId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1406</td><td>FM: +ResumeActivation ActivationInstanceId=%1 fIsResumed=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1407</td><td>FM: -ResumeActivation ActivationInstanceId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1408</td><td>FM: +Resume_ActivationPhase ActivationInstanceId=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1409</td><td>FM: -Resume_ActivationPhase ActivationInstanceId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1410</td><td>FM: +PauseActivation ActivationInstanceId=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1411</td><td>FM: -PauseActivation HRESULT=%1 PausePending=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1412</td><td>FM: +CancelActivation ActivationInstanceId=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1413</td><td>FM: -CancelActivation ActivationInstanceId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1414</td><td>FM: +AbortActivation ActivationInstanceId=%1 Reason=%2 fGenerateWER=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1415</td><td>FM: -AbortActivation ActivationInstanceId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1416</td><td>FM: +GetActivationProcessId ActivationInstanceId=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1417</td><td>FM: -GetActivationProcessId ActivationInstanceId=%1 PID%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1418</td><td>FM: +SetForegroundActivationInstance ActivationInstanceId=%1 Isforeground=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1419</td><td>FM: -SetForegroundActivationInstance ActivationInstanceId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1420</td><td>FM: SetActivationDehydrationEligibility TaskID=%1 State=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1421</td><td>FM: OnActivationStateChanged ActivationInstanceId=%1 state=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1422</td><td>FM: OnApplicationStateChanged UserContext=%1 PSMKey=%2 state=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1423</td><td>FM: IsValidActivationProcessId ActivationInstanceID=%1 PID=%2 fValid=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1424</td><td>FM: GetForegroundProductId fIgnoreLockScreen=%1 ProductID=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1425</td><td>FM: GetProductIdFromProcessID ProductID=%1 PID=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1426</td><td>FM: Discarding Application Frozen notification because the application isn&#39;t really frozen</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1427</td><td>FM: Dehydrate Application AUMID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1428</td><td>FM: +ResumePrerequisitePhase ActivationInstanceId=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1429</td><td>FM: -ResumePrerequisitePhase HRESULT=%1 fPending=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1430</td><td>FM: GenerateWatsonReport PID=%1 Reason=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1431</td><td>FM: SetContinuation ActivationInstanceID=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1432</td><td>FM: AbandonContinuation ActivationInstanceID=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1433</td><td>FM: PerformContinuation ActivationInstanceID=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1434</td><td>FM: Shutdown HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1435</td><td>FM: +PauseActivation ActivationInstanceId=%1 AUMID=%2 PackageFullName=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1436</td><td>FM: +ActivationBypass ActivationInstanceId=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1437</td><td>FM: -ActivationBypass ActivationInstanceId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1438</td><td>FM: +PostPausePendingResume ActivationInstanceId=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1439</td><td>FM: -PostPausePendingResume ActivationInstanceId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1440</td><td>FM: SetActivationImportanceVector TaskID=%1 Vector=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1441</td><td>FM: NotifyWindowAdded TaskID=%1 WindowInstanceId=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1442</td><td>FM: NotifyWindowRemoved TaskID=%1 WindowInstanceId=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1443</td><td>FTM: Logoff User=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1444</td><td>FM: ActivationTimeoutPolicyChanged  TaskID=%1 WindowInstanceId=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1445</td><td>FM-EEP: OnConnectedStandbyStateChanged  State=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1446</td><td>FM: SendActivationNotification ActivationId=%1 NotificationId=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1447</td><td>FM: OnResourceAcquired Usercontext=%1 PsmKey=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1448</td><td>FM: OnResourceTimerExpired Usercontext=%1 PsmKey=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>1449</td><td>FM: PostPausePendingActivation ActivationId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2000</td><td>VoIPPolicy: Evaluate Activation Action for PsmKey = %2, WorkItemId = %1, Action = %3, HRESULT = %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2001</td><td>VoIPPolicy: Task Activated for PsmKey = %2, WorkItemId = %1, HRESULT = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2002</td><td>VoIPPolicy: Task Completed for PsmKey = %2, WorkItemId = %1, HRESULT = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2003</td><td>VoIPPolicy: Task Canceled for PsmKey = %2, WorkItemId = %1, HRESULT = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2004</td><td>VoIPPolicy: Task Aborted for PsmKey = %2, WorkItemId = %1, HRESULT = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2005</td><td>VoIPPolicy: Determine and Apply Resources PsmKey = %2, WorkItemId = %1, HRESULT = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2006</td><td>VOIP: NotifyVoipActiveCall called for PID:%1 PSMKey:{%2} HRESULT:%3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2007</td><td>VOIP: LaunchVoipRtcTask called for PID:%1 PSMKey:{%2} with TaskEntryPoint:{%3} and WNFStateName:{%4} HRESULT:%5.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2008</td><td>VOIP: NotifyVoipActivityCompleted called for PID:%1 PSMKey:{%2} HRESULT:%3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2009</td><td>VOIP: HoldActiveCall called for PID:%1 PSMKey:{%2} HRESULT:%3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2010</td><td>VOIP: UnholdActiveCall called for PID:%1 PSMKey:{%2} HRESULT:%3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2011</td><td>VOIP: NotifyIncomingCallDialogDisplayed called for PID:%1 PSMKey:{%2} HRESULT:%3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2012</td><td>VOIP: NotifyIncomingCallDialogDismissed called for PID:%1 PSMKey:{%2} HRESULT:%3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2013</td><td>VOIP: CallActive called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3 {InActiveCall:%4, HasRTCTask:%5 OnHold:%6 TaskCompletionApplied:%7 InForeground:%8}.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2014</td><td>VOIP: AppLaunchVoipRtcTask called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3 {InActiveCall:%4, HasRTCTask:%5 OnHold:%6 TaskCompletionApplied:%7 InForeground:%8}.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2015</td><td>VOIP: OnVoipActivityCompleted called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3 {InActiveCall:%4, HasRTCTask:%5 OnHold:%6 TaskCompletionApplied:%7 InForeground:%8}.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2016</td><td>VOIP: AppHoldActiveCall called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3 {InActiveCall:%4, HasRTCTask:%5 OnHold:%6 TaskCompletionApplied:%7 InForeground:%8}.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2017</td><td>VOIP: AppUnholdActiveCall called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3 {InActiveCall:%4, HasRTCTask:%5 OnHold:%6 TaskCompletionApplied:%7 InForeground:%8}.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2018</td><td>VOIP: OnIncomingCallDialogDisplayed called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3 {InActiveCall:%4, HasRTCTask:%5 OnHold:%6 TaskCompletionApplied:%7 InForeground:%8}.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2019</td><td>VOIP: OnIncomingCallDialogDismissed called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3 {InActiveCall:%4, HasRTCTask:%5 OnHold:%6 TaskCompletionApplied:%7 InForeground:%8}.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2020</td><td>VOIP: AppDetermineAndApplyBestResourceSet called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2021</td><td>VOIP: PolicyEvaluateAction called for WorkItemId:{%1} PSMKey:{%2} ActivationAction:%3 HRESULT:%4.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2022</td><td>VOIP: PolicyTaskActivated called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2023</td><td>VOIP: PolicyTaskCompleted called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2024</td><td>VOIP: PolicyTaskCanceled called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2025</td><td>VOIP: PolicyTaskAborted called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2026</td><td>VOIP: OnForegroundApplicationChanged called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3 {InActiveCall:%4, HasRTCTask:%5 OnHold:%6 TaskCompletionApplied:%7 InForeground:%8}.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2027</td><td>VOIP: AppOnTaskActivated called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3 {InActiveCall:%4, HasRTCTask:%5 OnHold:%6 TaskCompletionApplied:%7 InForeground:%8}.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2028</td><td>VOIP: AppOnTaskCompleted called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3 {InActiveCall:%4, HasRTCTask:%5 OnHold:%6 TaskCompletionApplied:%7 InForeground:%8}.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2029</td><td>VOIP: AppCancelVoipRtcTask called for WorkItemId:{%1} PSMKey:{%2} HRESULT:%3 {InActiveCall:%4, HasRTCTask:%5 OnHold:%6 TaskCompletionApplied:%7 InForeground:%8}.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>2030</td><td>VOIP: CancelVoipRtcTask called for PID:%1 PSMKey:{%2} HRESULT:%3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3201</td><td>Task: %1 has started</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3202</td><td>Task: %1 has paused</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3203</td><td>Task: %1 has resumed</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3204</td><td>Task: %1 has completed</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3205</td><td>EM: +GetTaskInfo()</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3206</td><td>EM: -GetTaskInfo(). HRESULT = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3207</td><td>EM: GetAppInfo:%1,%2:%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3208</td><td>EM: ParseBackgroundAbilities - HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3209</td><td>EM: +ExecManServerHost::CreateProcess</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3210</td><td>EM: -ExecManServerHost::CreateProcess. HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3211</td><td>Sqm::AppPlatSqmAppDataUsage: %1/%2 - TaskID = %3, Type = %4, NewState = %5, ReasonForStateChange = %6, Duration (ms) = %7, PeakMemory (kb) = %8</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3215</td><td>Emc::ExecuteCommand: StartTaskCallbackBegin: TaskID = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3216</td><td>Emc::ExecuteCommand: StartTaskCallbackEnd: TaskID = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3217</td><td>Emc::ExecuteCommand: PauseTaskCallbackBegin: TaskID = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3218</td><td>Emc::ExecuteCommand: PauseTaskCallbackEnd: TaskID = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3219</td><td>Emc::ExecuteCommand: ResumeTaskCallbackBegin: TaskID = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3220</td><td>Emc::ExecuteCommand: ResumeTaskCallbackEnd: TaskID = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3221</td><td>Emc::ExecuteCommand: ControlTaskCallbackBegin: TaskID = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3222</td><td>Emc::ExecuteCommand: ControlTaskCallbackEnd: TaskID = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3223</td><td>Emc::ExecuteCommand: CancelTaskCallbackBegin: TaskID = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3224</td><td>Emc::ExecuteCommand: CancelTaskCallbackEnd: TaskID = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3225</td><td>Emc::ExecuteCommand: BackgroundExecutionTaskCallbackBegin: TaskID = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3226</td><td>Emc::ExecuteCommand: BackgroundExecutionTaskCallbackEnd: TaskID = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3230</td><td>Emc::RegisterBackgroundExecutionRequest: TaskID = %1, ExecutionType = %2, HR = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3240</td><td>Emc::DeregisterBackgroundExecutionRequest: TaskID = %1, ExecutionType = %2, Reason = %3, HR = %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3241</td><td>Emc::EnsureXbfForCurrentLocale: EnsureXbfForCurrentLocaleBegin: ProductID = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3242</td><td>Emc::EnsureXbfForCurrentLocale: EnsureXbfForCurrentLocaleEnd: ProductID = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3243</td><td>EM: Skipping terminate process call for %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3244</td><td>EM: Terminating process: PID = %1, ExitCode = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3300</td><td>AimServer::OnAgentRequestInvoked: AgentRequestID %1 was invoked. PID = %2, HR = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3301</td><td>AimServer::ReadSettings: HR = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3302</td><td>AimServer: Detected server for scope %1 terminated (PID = %2)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3304</td><td>AimServer::HandleEvent: ProductID %1 received PM LifecyleEvent %2. HR Notification = %3, HR = %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3305</td><td>BA::NotifyTaskInstanceCompleted: AgentRequestID = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3306</td><td>BA::RegisterServiceRequest: AlreadyReserved = %1, SR = %2, HR = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3307</td><td>BA::UnRegisterServiceRequest: SR = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3308</td><td>BA::CancelAgentRequest: AgentRequestID = %1, CancelType = %2, PID = %3, HR = %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3309</td><td>BA::NotifyTaskInstanceCompleted: Terminating Orphaned Host PID = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3310</td><td>BA::OrphanAgentRequest: AgentRequestID = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3311</td><td>BA::UnRegisterServiceRequest: Terminating host PID %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3312</td><td>BA::UnRegisterServiceRequest: Orphaning host PID %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3313</td><td>BA::UnRegisterServiceRequest: Terminating second old orphaned host PID %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3314</td><td>BTM::RecvCallback: Timer expired for AgentRequestID %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3315</td><td>BTM::LaunchTask: TaskURI = %1 TaskID = %2, PID = %3, HR = %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3316</td><td>GBA::NotifyTaskInstanceCompleted: AgentRequestID = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3317</td><td>GBA::RegisterServiceRequest: SR = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3318</td><td>GBA::UnRegisterServiceRequest: SR = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3319</td><td>GBA::RegisterAgentRequest: AgentRequestID = %1, type = %2, hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3320</td><td>GBA: Cancelling low priority %3 agent because high priority %2 needs to run: Resource was dedicated = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3321</td><td>GBA::CancelAgentRequest: AgentRequestID = %1, CancelType = %2, PID = %3, HR = %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3322</td><td>GBA::TryAcquireResourceSet: pending = %1, type = %2, HR = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3323</td><td>GBA::AbortTask: AgentRequestID = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3324</td><td>BA::AbortTask: AgentRequestID = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3325</td><td>BA::NotifyTaskHostCompleted: ProductID = %1, PID = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3326</td><td>BA::RegisterAgentRequest: ProductID = %1, AgentRequestID = %2, HR = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3327</td><td>BA::PdcActivationFailed: ProductID = %1, Reason = %2, NTSTATUS = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3500</td><td>FTM: AllowBackgroundExecution for ProductID %1. HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3501</td><td>FTM: Process is using too much memory for BG Execution. PID=%1, MemUsage=%2, RequiredMemUsage=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3502</td><td>FTM: Removing BG capability from Task ID %1 due to OOM</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3503</td><td>FTM: Battery Saver State has change. New state = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3504</td><td>FTM: Attempted new BG Execution request due to battery state change. TaskID=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3505</td><td>FTM: NotifyTaskInstanceCompleted TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3506</td><td>FTM: NotifyTaskInstancePaused TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3507</td><td>FTM: NotifyTaskInstanceRunning TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3508</td><td>FTM: SendTaskStatusChange TaskID=%1 Status=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3509</td><td>FTM: NotifyTaskHostCompleted HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3510</td><td>FTM: Discarding NotifyTaskHostFrozen notification because the host isn&#39;t really frozen</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3511</td><td>FTM: NotifyTaskHostFrozen PID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3512</td><td>FTM: NotifyTaskHostDehydrated HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3513</td><td>FTM: Registering callback %1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3514</td><td>FTM: New Task %1 is dehydration-suppressing</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3515</td><td>FTM: Applying Dehydration-Suppressing Policy to Host PID %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3516</td><td>FTM: Revoking Dehydration-Suppressing Policy to Host PID %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3517</td><td>FTM: +LaunchTask TaskURI=%1 LaunchFlags=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3518</td><td>FTM: -LaunchTask TaskURI=%1 TaskID=%2 PID=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3519</td><td>FTM: ResumeTask TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3520</td><td>FTM: Removing Foreground Resources from TaskID=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3521</td><td>FTM: SetForegroundTaskInstanceId TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3522</td><td>FTM: PauseTask TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3523</td><td>FTM: CancelTask TaskID=%1 Frozen=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3524</td><td>FTM: AbortTask being ignored because the task is completed TaskID=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3525</td><td>FTM: AbortTask TaskID=%1 Reason=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3526</td><td>FTM: SetTaskDehydrationEligibility TaskID=%1 State=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3527</td><td>FTM: RequestProcessBackgroundExecution type=%1 Pid=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3528</td><td>FTM: CancelProcessBackgroundExecutionRequest type=%1 Pid=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3529</td><td>FTM: TaskRunningInBackground TaskID=%1 PID=%2  HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3530</td><td>FTM: TaskRunningInForeground TaskID=%1 PID=%2  HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3531</td><td>FTM: Changing activation policy to resume due to BG Execution for ProductID %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3532</td><td>FTM: OnShutdownCompleted</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3533</td><td>FTM: Ignoring expired watchdog for task %1 because it is being debugged.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3534</td><td>FTM: Watchdog fired for task %1 while running in background. Pausing Task.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3535</td><td>FTM: Request BG Execution Denied because it wasn&#39;t running. TaskID=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3536</td><td>FTM: Request BG Execution Denied because product was forbidden. TaskID=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3537</td><td>FTM: Request BG Execution Denied because task didn&#39;t have BG abilities in its manifest. TaskID=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3538</td><td>FTM: Request BG Execution Denied due to lack of resources. TaskID=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3539</td><td>FTM: Request BG Execution Denied because battery policy prevented it. TaskID=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3540</td><td>FTM: RequestBGAccess IsAllowed=%1 TaskID=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3541</td><td>FTM: RemoveBGRequest RequestedRemoval=%1 ActualRemoval=%2 TaskID=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3542</td><td>FTM: ForbidBackgroundExecution for ProductID %1. HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3543</td><td>FTM: IsValidTaskInstancePid TaskID=%1 Pid=%2 fValid=%3 HRESULT=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3544</td><td>FTM: DetermineBestResourceSet for child ProductID=%1 LaunchFlags=%2 ResourceSetType=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3545</td><td>FTM: OnRelease ResourceSet TaskID=%1 ResouceSet=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3546</td><td>FTM:UITask Call to Acquire network reference failed CM_RESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3547</td><td>FTM:UITask Call to Release network reference failed CM_RESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3548</td><td>FTM: SetTaskImportanceVector TaskID=%1 Vector=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3549</td><td>FTM: +RequestProcessBackgroundExecution type=%1 Pid=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3550</td><td>FTM: +RequestBackgroundExecution type=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3551</td><td>FTM: -RequestBackgroundExecution type=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3552</td><td>FTM: +RequestBGAccess TaskInstanceId=%1 type=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3553</td><td>FTM: Request BG Execution Denied because DPL policy prevented it. TaskID=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3554</td><td>FTM: Windows Information Protection keys locked state (%1)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3650</td><td>VoIP: Foreground state for product %1 has changed. Is in foreground = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3651</td><td>VoIP: Canceling communication agent for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3652</td><td>VoIP: Timer expired for keep-alive agent of product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3653</td><td>VoIP: Timer expired for incoming call agent of product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3654</td><td>VoIP: Launched agent instance with id %2 and URI %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3655</td><td>VoIP: Canceled agent instance with id %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3656</td><td>VoIP: Set active call resource set</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3657</td><td>VoIP: Set communication agent resource set</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3658</td><td>VoIP: Set VoIP Worker resource set</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3659</td><td>VoIP: Applied terminal resource set</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3660</td><td>VoIP: Last task instance completed. Releasing the task host ...</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3661</td><td>VoIP: Launching active call agent instance for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3662</td><td>VoIP: Canceling active call agent for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3663</td><td>VoIP: Putting an active call on hold for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3664</td><td>VoIP: Taking an active call off hold for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3665</td><td>VoIP: Incoming call dialog has been displayed for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3666</td><td>VoIP: Incoming call dialog has been dismissed for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3667</td><td>VoIP: Launch communication agent request received from process %1 for product %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3668</td><td>VoIP: Read settings. Keep alive timout = %1 ms, Max agent request queue = %2, Incoming call grace period = %3 ms, Incoming call dismissed grace period = %4 ms</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3669</td><td>VoIP: Received request to launch agent type %2 for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3670</td><td>VoIP: Task instance %2 of product %1 completed</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3671</td><td>VoIP: Processing request to launch agent type %2 for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3672</td><td>VoIP: Added VoIPApp object to map for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3673</td><td>VoIP: Removed VoIPApp object from map for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3674</td><td>VoIP: Getting VoIPApp object from map for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3675</td><td>VoIP: Publishing WNF_DEVP_VOIP_ACTIVE_CALL_STATE_CHANGE failed with status %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3676</td><td>VoIP: Subscribing to the WNF_WIFI_CONNECTION_STATUS event failed with status %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3677</td><td>VoIP: Subscribed to WNF_WIFI_CONNECTION_STATUS? %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3678</td><td>VoIP: WiFi connection status active/dormat? %1 (hConnection = %2)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3679</td><td>VoIP: RtlQueryWnfStateData failed trying to query the value of WNF_WIFI_CONNECTION_STATUS. NTSTATUS = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3680</td><td>VoIP: Could not spin up worker for UpdateWiFiStateHelper. HR =%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3681</td><td>VoIP: In active call? %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3682</td><td>VoIP: CmUtilSetWiFiActive was not successful. This could be because WiFi disconnected by the time we were notified of the connection.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3683</td><td>VoIP: WiFi connection status is %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3684</td><td>VoIP: AbortTask: TaskInstanceID = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3685</td><td>VoIP: PhoneServiceRestart: HR = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3686</td><td>VoIP: PhoneServiceRestart: Product = %1, HR = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3687</td><td>VoIP: Launching call query info agent instance for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3688</td><td>VoIP: Canceling call query info agent instance for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3689</td><td>VoIP: Terminating agents due to low memory for product %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3690</td><td>VoIP: Acquired Pending ResourceSet for product = %1, Resourceset = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3691</td><td>VoIP: Acquired Pending ResourceSet for product = %1, Resourceset = %2, fApplied = %3, HR = %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3692</td><td>VoIP: Set PDC Network Active for product = %1, NTSTATUS = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3693</td><td>VoIP: Set PDC Network Inactive for product = %1, NTSTATUS = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3694</td><td>VoIP: Renew PDC Network activation failed for product = %1, NTSTATUS = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>3699</td><td>VoIP: An error occurred. Hr = %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6100</td><td>%1 - [%2 = %3]\n</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6101</td><td>%1 - Parsing config file [%2] file size = %3.  Parse = %4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6102</td><td>%1 - OnTaskModelMessage: Dispatching EM message</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6103</td><td>%1 - InitializeTaskHost URI=%2, Page=%3, TaskId=%4</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6104</td><td>%1 - Resuming Task from dehydration</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6105</td><td>%1 - TaskHandler::GetTaskHandler hr=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6106</td><td>%1 - TaskHost Init</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6107</td><td>%1 - TaskHost Init hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6108</td><td>%1 - Host Dispatcher Exiting hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6109</td><td>%1 - TaskHandlerReady received</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6110</td><td>%1 - StartTask TaskId=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6111</td><td>%1 - PauseTask TaskId=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6112</td><td>%1 - ResumeTask TaskId=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6113</td><td>%1 - OnTaskHandlerVisible received</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6114</td><td>%1 - OnTaskHandlerHidden received</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6115</td><td>%1 - BackgroundExecutionCallback TaskId[%2] Command[%3]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6116</td><td>%1 - BackgroundExecutionCallback hr=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6117</td><td>%1 - OnHostRunning</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6118</td><td>%1 - OnHostRunning. hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6119</td><td>%1 - Dehydrating. dehydrateGracefully = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6120</td><td>%1 - Gracefully dehydrating TaskHost</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6121</td><td>%1 - TryDehydrateHost. hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6122</td><td>%1 - DehydrateHost event triggered</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6123</td><td>%1 - WaitForUnfreeze hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6124</td><td>%1 - ReduceMemoryHostCallback hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6125</td><td>%1 - Graceful tear-down failed</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6126</td><td>%1 - BeforeHostRunningInBackgroundCallback</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6127</td><td>%1 - BeforeHostRunningInBackgroundCallback. hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6128</td><td>%1 - AfterHostRunningInBackgroundCallback</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6129</td><td>%1 - AfterHostRunningInBackgroundCallback. hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6130</td><td>%1 - Unhandled exception occurred. hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6131</td><td>%1 - State-Transition (%2)-&gt;(%3)</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6132</td><td>%1 - EnableProfiling = [%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6133</td><td>%1 - Profile Dll = [%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6134</td><td>%1 - ProfilerCLSID = [%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6135</td><td>%1 - TaskHostHelper::SetProfilerSettings hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6136</td><td>%1 - File path = %2 : %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6137</td><td>%1 - Parse Element: %2.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6138</td><td>%1 - Parse Element Value = %2 with pwszLocalName = %3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6139</td><td>%1 - Parse HResult = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6140</td><td>%1 - YUTHost: failed to GAC trusted assembly %2\r\n</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6141</td><td>%1 - UITaskHandler::Initialize. hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6142</td><td>%1 - UITaskHandler::Disconnect done</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6143</td><td>%1 - UITaskHandler::GoBackground. hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6144</td><td>%1 - UITaskHandler::GoForeground. hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6145</td><td>%1 - Managed Framework Ready. Handling Pending Event:[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6146</td><td>%1 - HandlePendingEvents Start TaskId=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6147</td><td>%1 - HandlePendingEvents Pause TaskId=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6148</td><td>%1 - HandlePendingEvents Resume TaskId=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6149</td><td>%1 - Waiting for Siblings...</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6150</td><td>%1 - Waiting for Siblings done. hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6151</td><td>%1 - UITaskHandler::OnRuntimeHostReady TaskID:[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6152</td><td>%1 - UITaskHandler::OnRuntimeHostReady. Processed pending SystemKeyPress [%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6153</td><td>%1 - UITaskHandler::OnRuntimeHostReady hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6154</td><td>%1 - UITaskHandler::RegistrationComplete hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6155</td><td>%1 - UITaskHandler::ConnectionComplete received</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6156</td><td>%1 - UITaskHandler::ConnectionComplete hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6157</td><td>%1 - UITaskHandler::ProcessActivationData received, reason=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6158</td><td>%1 - UITaskHandler::ProcessActivationData hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6159</td><td>%1 - UITaskHandler::Show received. Direction:[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6160</td><td>%1 - Navigation in progress. Queuing up the Show</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6161</td><td>%1 - UITaskHandler::Show hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6162</td><td>%1 - UITaskHandler::ShowInternal. Direction:[%2:NavigationDirection:]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6163</td><td>%1 - UITaskHandler::ShowInternal. hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6164</td><td>%1 - UITaskHandler::Hide received. Direction:[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6165</td><td>%1 - Navigation in progress. Cancelling Show and ignoring Hide</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6166</td><td>%1 - UITaskHandler::Hide hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6167</td><td>%1 - UITaskHandler::NavigateTo received TaskID:[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6168</td><td>%1 - UITaskHandler::NavigateTo. hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6169</td><td>%1 - UITaskHandler::NavigationComplete TaskID:[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6170</td><td>%1 - UITaskHandler::NavigationComplete hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6171</td><td>%1 - UITaskHandler::NavigateAway received TaskID:[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6172</td><td>%1 - Navigation interrupted since Task is closing</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6173</td><td>%1 - Navigation in progress. Queuing up the NavigateAway</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6174</td><td>%1 - UITaskHandler::NavigateAway hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6175</td><td>%1 - UITaskHandler::NavigateAwayInternal TaskID:[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6176</td><td>%1 - UITaskHandler::NavigateAwayInternal hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6177</td><td>%1 - UITaskHandler::RequestClose called TaskID:[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6178</td><td>%1 - UITaskHandler::RequestClose hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6179</td><td>%1 - LaunchSession in progress. Cannot add another callback</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6180</td><td>%1 - UITaskHandler::LaunchSession hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6181</td><td>%1 - LaunchChildTask in progress. Cannot add another callback</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6182</td><td>%1 - UITaskHandler::LaunchChildTask hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6183</td><td>%1 - UITaskHandler::SetPauseOnLock[%2] called TaskID:[%3]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6184</td><td>%1 - UITaskHandler::SetPauseOnLock hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6185</td><td>%1 - UITaskHandler::Close received TaskID:[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6186</td><td>%1 - UITaskHandler::Close hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6187</td><td>%1 - UITaskHandler::SystemKeyPressed received: [%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6188</td><td>%1 - UITaskHandler::SystemKeyPressed processed</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6189</td><td>%1 - UITaskHandler::SystemKeyPressed pending. Will be processed on RuntimeHost ready</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6190</td><td>%1 - UITaskHandler::LaunchChildTaskComplete received with result %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6191</td><td>%1 - UITaskHandler::LaunchChildTaskComplete result:%2 hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6192</td><td>%1 - UITaskHandler::LaunchSessionComplete received with result %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6193</td><td>%1 - UITaskHandler::LaunchChildTaskComplete result:%2 hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6194</td><td>%1 - OrientationChanged NewOrientation=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6195</td><td>%1 - OrientationChange received before RuntimeHostTask is set</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6196</td><td>%1 - SetSupportedOrientations. SupportedOrientations:[%2]. hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6197</td><td>%1 - GetSupportedOrientations. SupportedOrientations[%2]. hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6198</td><td>%1 - GetCurrentOrientation. CurrentOrientation[%2]. hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6199</td><td>%1 - UITaskHandler::ReplaceTouchEndpoint hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6200</td><td>%1 - UITaskHandler::ReplaceTextEndpoint hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6201</td><td>%1 - UITaskHandler::Get Task State. StateSize[%2]. hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6202</td><td>%1 - UITaskHandler::Set Task State. StateSize[%2]. hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6203</td><td>%1 - UITaskHandler::OnObscurityChange[%2]. hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6204</td><td>%1 - UITaskHandler::OnLockScreenVisibilityChange[%2]. hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6205</td><td>%1 - UITaskHandler::OnSipVisibilityChange[%2]. hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6206</td><td>%1 - UITaskHandler::OnShowAnimationComplete</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6207</td><td>%1 - UITaskHandler::Window.Visible property changed [%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6208</td><td>%1 - FreezeHost event triggered</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6209</td><td>%1 - FreezeHostCallback failed with hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6210</td><td>%1 - CancelTask TaskId=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6211</td><td>%1 - OnHostPausing</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6212</td><td>%1 - OnHostPausing failed with hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6213</td><td>%1 - OnHostPaused</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6214</td><td>%1 - OnHostPaused failed with hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6215</td><td>%1 - FreezeHost event triggered</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6216</td><td>%1 - FreezeHostCallback failed with hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6217</td><td>%1 - CancelTask received while executing in background</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6218</td><td>%1 - CancelTask received. Ignoring since this is a valid transition only when running in background</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6219</td><td>%1 - CancelTask hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6220</td><td>%1 - TPA entry: %2\\%3%4;</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6221</td><td>%1 - Platform Assemblies List: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6222</td><td>%1 - ParseManifestFile HResult = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6223</td><td>%1 - NotifyError ! Unable to disable NI optimizations</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6224</td><td>%1 - NotifyError ! Unable to set the debugger wait env variable</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6225</td><td>%1 - TestTrustedPath: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6226</td><td>%1 - TestAppPaths: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6227</td><td>%1 - NotifyError ! Failed to set the test settings</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6228</td><td>%1 - GetAppPaths failed with hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6229</td><td>%1 - NotifyError ! message = %2, source = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6230</td><td>%1 - NotifyError ! hr=%2. message = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6231</td><td>%1 - GetIsoStoreAvailableFreeSpace hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6232</td><td>%1 - NotifyEvent XcpHostEvent_ApplicationStarted</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6233</td><td>%1 - NotifyEvent XcpHostEvent_ApplicationStarting</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6234</td><td>%1 - NotifyEvent XcpHostEvent_ApplicationConstructing: Assembly = %2, NotifyEvent Type = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6235</td><td>%1 - NotifyEvent XcpHostEvent_ApplicationConstructed: Assembly = %2, NotifyEvent Type = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6236</td><td>%1 - NotifyEvent XcpHostEvent_AssemblyLoading: Assembly = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6237</td><td>%1 - NotifyEvent XcpHostEvent_AssemblyLoaded: Assembly = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6238</td><td>%1 - NotifyEvent XcpHostEvent_SourceLoading: XAP = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6239</td><td>%1 - NotifyEvent XcpHostEvent_SourceLoaded: XAP = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6240</td><td>%1 - GetQualifiedMutexName returned:[%2]. AllowedMutexCount:[%3]\r\n</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6241</td><td>%1 - XcpHost::Start() failed with hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6242</td><td>%1 - Shutting down the SL runtime...</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6243</td><td>%1 - Calling into XcpHost::Pausing %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6244</td><td>%1 - XcpHost::Pausing %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6245</td><td>%1 - Calling into XcpHost::Pause %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6246</td><td>%1 - XcpHost::Pause %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6247</td><td>%1 - Calling into XcpHost::Resume %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6248</td><td>%1 - XcpHost::Resume %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6249</td><td>%1 - Calling into XcpHost::Resumed %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6250</td><td>%1 - XcpHost::Resumed %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6251</td><td>%1 - XcpHost::CompleteTask called TaskID:[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6252</td><td>%1 - CompleteTask called when XcpTask is null. This likely indicates CompleteTask getting called twice</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6253</td><td>%1 - Error in OnApplicationStarted</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6254</td><td>%1 - Error in OnApplicationConstructing</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6255</td><td>%1 - LaunchSession hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6256</td><td>%1 - LaunchChildTask hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6257</td><td>%1 - Raising Task.OnLaunching</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6258</td><td>%1 - Raised Task.OnLaunching</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6259</td><td>%1 - Raising Task.OnPause. PauseReason[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6260</td><td>%1 - Raised Task.OnPause</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6261</td><td>%1 - Raising Task.OnResume. IsExecutionContextPreserved[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6262</td><td>%1 - Raised Task.OnResume</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6263</td><td>%1 - Raising Task.OnRunningInBackground</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6264</td><td>%1 - Raised Task.OnRunningInBackground</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6265</td><td>%1 - Raising Task.OnCancel</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6266</td><td>%1 - Raised Task.OnCancel</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6267</td><td>%1 - Raising Task.OnHostDehydarting</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6268</td><td>%1 - Raised Task.OnHostDehydarting</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6269</td><td>%1 - Raising Task.OnNavigateTo</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6270</td><td>%1 - Raised Task.OnNavigateTo</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6271</td><td>%1 - Raising Task.OnNavigateAway</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6272</td><td>%1 - Raised Task.OnNavigateAway</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6273</td><td>%1 - Raising Task.OnShow</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6274</td><td>%1 - Raised Task.OnShow</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6275</td><td>%1 - Raising Task.OnHide</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6276</td><td>%1 - Raised Task.OnHide</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6277</td><td>%1 - Raising Task.OnSystemKeyPressed</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6278</td><td>%1 - Raised Task.OnSystemKeyPressed</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6279</td><td>%1 - Raising Task.OnChildTaskReturned</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6280</td><td>%1 - Raised Task.OnChildTaskReturned</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6281</td><td>%1 - Raising Task.OnObscurityChange</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6282</td><td>%1 - Raised Task.OnObscurityChange</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6283</td><td>%1 - Raising Task.OnLockScreenVisibilityChange</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6284</td><td>%1 - Raised Task.OnLockScreenVisibilityChange</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6285</td><td>%1 - Raising Task.OnClosing</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6286</td><td>%1 - Raised Task.OnClosing</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6287</td><td>%1 - RegisterAppCallbacks hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6288</td><td>%1 - RegisterTaskCallbacks hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6289</td><td>%1 - TaskReadyToShow hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6290</td><td>%1 - RequestCloseTask hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6291</td><td>%1 - CompleteTask hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6292</td><td>%1 - DestroyTaskCallbacks hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6293</td><td>%1 - SetHostErrorCode hrHostError = %2, hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6294</td><td>%1 - LaunchSession[%2] hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6295</td><td>%1 - GetTaskState hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6296</td><td>%1 - SetTaskState hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6297</td><td>%1 - LaunchChildTask[%2] hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6298</td><td>%1 - GetTaskAppChromeHandle hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6299</td><td>%1 - SetTaskPauseOnLock hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6300</td><td>%1 - SetHostObscurity[%2] hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6301</td><td>%1 - Entering Modal state</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6302</td><td>%1 - Exiting Modal state hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6303</td><td>%1 - NotifyError: message=%2, source=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6304</td><td>%1 - NotifyEvent XcpHostEvent_ApplicationStarted</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6305</td><td>%1 - NotifyEvent XcpHostEvent_ApplicationStarting</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6306</td><td>%1 - NotifyEvent XcpHostEvent_ApplicationConstructing: Assembly = %2, NotifyEvent Type = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6307</td><td>%1 - NotifyEvent XcpHostEvent_ApplicationConstructed: Assembly = %2, NotifyEvent Type = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6308</td><td>%1 - NotifyEvent XcpHostEvent_AssemblyLoading: Assembly = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6309</td><td>%1 - NotifyEvent XcpHostEvent_AssemblyLoaded: Assembly = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6310</td><td>%1 - NotifyEvent XcpHostEvent_SourceLoading: XAP = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6311</td><td>%1 - NotifyEvent XcpHostEvent_SourceLoaded: XAP = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6312</td><td>%1 - Raising Task.OnRefresh</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6313</td><td>%1 - Raised Task.OnRefresh</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6314</td><td>%1 - UITaskHandler::RequestNavigateBack called TaskID:[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6315</td><td>%1 - UITaskHandler::RequestNavigateBack hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6316</td><td>%1 - RequestNavigateBack hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6317</td><td>%1 - UITaskHandler::SetFullScreen[%2] called TaskID:[%3]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6318</td><td>%1 - UITaskHandler::SetFullScreen hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6319</td><td>%1 - SetTaskFullScreen hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6320</td><td>%1 - Raising Task.OnApplicationLayerChange</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6321</td><td>%1 - Raised Task.OnApplicationLayerChange</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6322</td><td>%1 - Raising Task.OnRequestOverlayStateChange. State=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6323</td><td>%1 - Raised Task.OnRequestOverlayStateChange</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6324</td><td>%1 - ApplicationLayerChanged NewApplicationLayer=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6325</td><td>%1 - ApplicationLayerChange received before RuntimeHostTask is set</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6326</td><td>%1 - AgTaskHandler::LaunchSession hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6327</td><td>%1 - AgTaskHandler::LaunchChildTask hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6328</td><td>%1 - GetSessionDisplayName. DisplayName=%2 hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6329</td><td>%1 - AgTaskHandler::ConnectionComplete received</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6330</td><td>%1 - AgTaskHandler::ConnectionComplete hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6331</td><td>%1 - UITaskHandler::OnNavigationBarVisibilityChange[%2]. hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6332</td><td>%1 - Raising Task.OnModernActivation</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6333</td><td>%1 - Raised Task.OnModernActivation</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6334</td><td>%1 - UITaskHandler::LaunchModernChooser hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6335</td><td>%1 - LaunchChildTask hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6336</td><td>%1 - LaunchModernChooser[%2] hr = %3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6337</td><td>%1 - TaskFirstPresentCompleted = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6338</td><td>%1 - UITaskHandler::FirstPresentCompleted called TaskID:[%2]</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6339</td><td>%1 - UITaskHandler::FirstPresentCompleted hr = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6350</td><td></td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>6351</td><td></td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8100</td><td>AgHost - FrameworkView::Initialize HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8101</td><td>AgHost - FrameworkView::SetWindow HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8102</td><td>AgHost - FrameworkView::Load HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8103</td><td>AgHost - FrameworkView::Run HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8104</td><td>AgHost - FrameworkView::Uninitialize HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8105</td><td>AgHost - FrameworkView::OnActivated PreviousExecutionState=%1 ActivationKind=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8106</td><td>AgHost - FrameworkView::OnExiting HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8107</td><td>AgHost - FrameworkView::OnResuming HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8108</td><td>AgHost - FrameworkView::OnSuspending HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8110</td><td>AgHostSvcs - EmCancelTaskInstance TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8111</td><td>AgHostSvcs - EmCreateTaskInstance TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8112</td><td>AgHostSvcs - EmExitTaskHost HRESULT=%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8113</td><td>AgHostSvcs - EmPauseTaskInstance TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8114</td><td>AgHostSvcs - EmResumeTaskInstance TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8115</td><td>AgHostSvcs - EmSetTaskInstanceApplicationUri TaskID=%1 ApplicationUri=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8116</td><td>AgHostSvcs - EmSetTaskInstanceArguments TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8117</td><td>AgHostSvcs - EmSetTaskInstanceBackgroundTaskId TaskID=%1 BackgroundTaskID=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8118</td><td>AgHostSvcs - EmSetTaskInstanceNavigationPage TaskID=%1 NavigationPage=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8119</td><td>AgHostSvcs - EmStartTaskInstance TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8120</td><td>AgHostSvcs - TaskCompleted TaskID=%1 CompletionCode=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8121</td><td>AgHostSvcs - TaskPaused TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8122</td><td>AgHostSvcs - TaskRunning TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8123</td><td>AgHostSvcs - TaskRunningInBackground TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8124</td><td>AgHostSvcs - TaskRunningInForeground TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8125</td><td>AgHostSvcs - EmWaitForTaskInstanceCompleted TaskID=%1 CompletionCode=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8126</td><td>AgHostSvcs - OnModernContractActivation TaskID=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8200</td><td>EEC: GetExtendedExecutionBroker ProcessId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8201</td><td>EEC: RegisterRevokedHandler ProcessId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8202</td><td>EEC: RequestExtendedExecution ProcessId=%1 Reason=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8203</td><td>EEC: ExtensionRevokedCallback ProcessId=%1 Reason=%2 HRESULT=%3</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8204</td><td>EEC: CompleteExtendedExecution ProcessId=%1 HRESULT=%2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8300</td><td>ODB: LaunchTask - UserSid: %1 SessionId: %2 PackageFullName: %3 EntryPoint: %4 WorkItemId: %5 HRESULT: %6.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8301</td><td>ODB: CancelTask - UserSid: %1 SessionId: %2 WorkItemId: %3 RudeTerminate: %4 CancellationReason: %5 HRESULT: %6.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8302</td><td>ODB: BeforeTaskActivated - WorkItemId: %1 PsmKey: %2 HostJobType: %3 HRESULT: %4.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8303</td><td>ODB: TaskActivated - WorkItemId: %1 TaskInstanceId: %2 PsmKey: %3 HRESULT: %4.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8304</td><td>ODB: TaskCompleted - WorkItemId: %1 TaskInstanceId: %2 HRESULT: %3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8305</td><td>ODB: TaskCanceled - WorkItemId: %1 TaskInstanceId: %2 HRESULT: %3.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8306</td><td>ODB: Timeout in WaitForWnfStateQuiescentTimeout.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>8307</td><td>ODB: CancelBackgroundTaskWithWnf WorkItemId: %1.</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>10000</td><td>%1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>10001</td><td>%1: %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>10002</td><td>*** ExecFailFast ***   %1</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>10010</td><td>PreInstallTaskPolicy: Activate task for User = %1 HRESULT = %2</td></tr>
<tr><td>Microsoft-Windows-AppModel-Exec</td><td>10011</td><td>PreInstallTaskPolicy: BiActivate WorkItemId = %1 for user = %2, PackageFullName = %3, EntryPoint = %4, HRESULT = %5</td></tr>
</table>
