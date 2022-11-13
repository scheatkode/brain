# Microsoft-AppV-Client

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-AppV-Client</td><td>1</td><td>The Client service started successfully.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>2</td><td>The Client service shut down.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>3</td><td>A required component (%1) cannot be loaded.  Please repair your installation. {error: %2}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>4</td><td>The Client service could not get the list of currently logged-on users.  If users experience any issues running virtual applications, please logoff and logon again, or restart the service. {error: %1}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>5</td><td>The Client could not register a logged-on user.  The user will not be able to access any App-V services, including running virtual applications.  Please have the user logoff and logon again. {error: %1-%2}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6</td><td>The Client could not unregister a user that logged off.  If other users experience any issues logging on, please restart the Client service. {error: %1-%2}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>7</td><td>The Client could not determine the identity of a caller on a public request, and the request was denied. {error: %1}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8</td><td>The Client could not register a caller, or verify the registration status of a caller, on a public request, and the request was denied. {error: %1-%2}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>9</td><td>A public request to the Client was initiated by a caller which granted the Client the authority for %1, whereas the Client requires at a minimum RPC_C_IMP_LEVEL_IMPERSONATE in order to satisfy a request on the caller&#39;s behalf.  The calling application will need to modify its security settings for outbound calls in order to successfully access the Client API.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>10</td><td>The access to the client was denied. The caller didn&#39;t have required permission for this operation.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>11</td><td>The Client failed to register for power notifications.  {error: %1-%2}.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>12</td><td>The Client failed to unregister for power notifications.  {error: %1-%2}.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>13</td><td>SLAPI check failed because of failure to read license info. {error: %1}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14</td><td>The Client service cannot be started due to reboot required.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>15</td><td>The Client service cannot be started due AppV being disabled.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>16</td><td>The Client service cannot be started due to component %1 failing during the global maintenance phase. {error: %2-%3}.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>17</td><td>The maintenance phase has failed for user %1 in component %2. {error: %3-%4}.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>101</td><td>IAppVClient::%1 COM method entered.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>102</td><td>IAppVClient::%1 COM method exited. %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1001</td><td>Active processing could not be shut down, this may lead to delays or hangs for Client shutdown. {error: %1-%2}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1002</td><td>Package %1 version %2 was successfully configured in folder &#39;%3&#39;.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1003</td><td>Package %1 version %2 was successfully published for the user.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1004</td><td>Package %1 version %2 was successfully published for all users.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1005</td><td>Package %1 version %2 was unpublished for the user.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1006</td><td>Package %1 version %2 was unpublished for all users.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1007</td><td>Package %1 version %2 was removed.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1008</td><td>Package %1 version %2 failed configuration in folder &#39;%3&#39; with error %4-%5.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1009</td><td>Virtual application connection group %1 version %2 was successfully configured.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1010</td><td>Virtual application connection group %1 version %2 failed configuration with error %3-%4.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1011</td><td>Virtual application connection group %1 version %2 was successfully published for the user.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1012</td><td>Virtual application connection group %1 version %2 was successfully published for all users.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1013</td><td>Virtual application connection group %1 version %2 was unpublished for the user.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1014</td><td>Virtual application connection group %1 version %2 was unpublished for all users.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1015</td><td>Virtual application connection group %1 version %2 was removed.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1016</td><td>Failed to unpublish package %1 version %2 because the package is published as part of one or more connection groups. Unpublish all connection groups that reference this package and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1017</td><td>Failed to remove package %1 version %2 because the package is configured as part of one or more connection groups. Remove all connection groups that reference this package and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1018</td><td>A package could not be unpublished for the user because it is currently in use by the user.  Shut down all applications in the package, and try again.
Package %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1019</td><td>A package could not be globally unpublished because it is currently in use.  Make sure all users have shut down all applications in the package, and try again.
Package %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1020</td><td>A package could not be removed because it is currently in use.  Make sure all users have shut down all applications in the package, and try again.
Package %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1021</td><td>An app connection group could not be unpublished for the user because it is currently in use by the user.  Shut down all applications in the group, and try again.
Connection Group %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1022</td><td>An app connection group could not be globally unpublished because it is currently in use.  Make sure all users have shut down all applications in the group, and try again.
Connection Group %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1023</td><td>An app connection group could not be removed because it is currently in use.  Make sure all users have shut down all applications in the group, and try again.
Connection Group %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1024</td><td>The package %1 version %2 could not be reconfigured because it is not configured on the system.  Ensure the package ID and version ID are correct and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1025</td><td>The package %1 version %2 could not be configured because it can only be used with 64-bit versions of Windows.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1026</td><td>The package %1 version %2 could not be configured because it is not compatible with this version of Windows.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1027</td><td>The package %1 version %2 could not be configured becaused the Deployment Configuration file &#39;%3&#39; could not be found.  Ensure the path is correct and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1028</td><td>The package %1 version %2 could not be configured because the Deployment Configuration file &#39;%3&#39; is not valid.  Verify that the document is valid and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1029</td><td>The package %1 version %2 could not be configured because the Deployment Configuration file does not match the the specified package.  Ensure the GUIDs in the Deployment Configuration file match those of the package and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1030</td><td>The package %1 version %2 could not be configured because the user account does not have administrative privileges.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1031</td><td>The package %1 version %2 could not be published globally because the user account does not have administrative privileges.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1032</td><td>The package %1 version %2 could not be published because the package has not been configured on the system.  Configure the package and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1033</td><td>The package %1 version %2 could not be published becaused the User Configuration file &#39;%3&#39; could not be found.  Ensure the path is correct and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1034</td><td>The package %1 version %2 could not be published because the User Configuration file &#39;%3&#39; is not valid.  Verify that the document is valid and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1035</td><td>The package %1 version %2 could not be published because the User Configuration file does not match the the specified package.  Ensure the GUIDs in the User Configuration file match those of the package and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1036</td><td>The package %1 version %2 could not be published globally because a User Configuration file was specified.  Either publish the package for the user with the User Configuration file specified or do not supply a User Configuration.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1037</td><td>The package %1 version %2 could not be unpublished globally because the user account does not have administrative privileges.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1038</td><td>The package %1 version %2 could not be unpublished because it is not published to the target of the unpublish operation.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1039</td><td>The package %1 version %2 could not be removed because the package is not configured on the system.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1040</td><td>The package %1 version %2 could not be removed because the user account does not have administrative privileges.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1041</td><td>The package %1 version %2 cannot be repaired because the package is not configured on the system.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1042</td><td>The package %1 version %2 was repaired successfully, but the package is published in one or more Virtual Application Connection Groups.  Settings are associated with the group, so you may need to clear settings for the Virtual Application Connection Groups associated with this package.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1043</td><td>The app connection group %1 version %2 could not be added because the app connection group file &#39;%3&#39; could not be found.  Ensure the path is correct and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1044</td><td>The app connection group %1 version %2 could not be added because the package %3 version %4 is not configured on the system.  Configure the package and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1045</td><td>The app connection group %1 version %2 could not be added because the app connection group file &#39;%3&#39; is not valid.  Verify that the document is valid and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1046</td><td>The app connection group %1 version %2 could not be added because the user account does not have administrative privileges.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1047</td><td>The app connection group %1 version %2 could not be enabled because the app connection group has not been added on the system.  Add the app connection group and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1048</td><td>The app connection group %1 version %2 could not be enabled because the package %3 version %4 is not published to the target of the operation.  Publish the package and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1049</td><td>The app connection group %1 version %2 could not be enabled globally because the user account does not have administrative privileges.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1050</td><td>The app connection group %1 version %2 could not be disabled because it is not enabled for the target of the disable operation.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1051</td><td>The app connection group %1 version %2 could not be disabled globally because the user account does not have administrative privileges.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1052</td><td>The app connection group %1 version %2 could not be removed because the package it has not been added on the system.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1053</td><td>The app connection group %1 version %2 could not be removed because the user account does not have administrative privileges.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1054</td><td>The app connection group %1 version %2 cannot be repaired because the app connection group has not been added on the system.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1055</td><td>A package could not be unpublished for the user because it is currently in use by the user.  The package will be unpublished at a later time.
Package %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1056</td><td>A package could not be globally unpublished because it is currently in use.  The package will be unpublished at a later time.
Package %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1057</td><td>The package %1 version %2 was detected to have a pending global Unpublish task. The App-V Client cannot start the virtual environment. Please close all running applications in the package or stop the package.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1058</td><td>The app connection group %1 version %2 was detected to have a pending global Unpublish task. The App-V Client cannot start the virtual environment. Please close all running applications in the app connection group or stop the app connection group.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1059</td><td>The package %1 version %2 was detected to have a pending user Unpublish task. The App-V Client cannot start the virtual environment. Please close all running applications in the package or stop the package.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1060</td><td>The app connection group %1 version %2 was detected to have a pending user Unpublish task. The App-V Client cannot start the virtual environment. Please close all running applications in the app connection group or stop the app connection group.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1061</td><td>A connection group could not be unpublished for the user because it is currently in use by the user.  The connection group will be unpublished at a later time.
Connection Group %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1062</td><td>A connection group could not be globally unpublished because it is currently in use.  The connection group will be unpublished at a later time.
Connection Group %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1063</td><td>A package could not be published for the user because it is currently in use by the user.  Shut down all applications in the package, and try again.
Package %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1064</td><td>A package could not be globally published because it is currently in use.  Make sure all users have shut down all applications in the package, and try again.
Package %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1065</td><td>An app connection group could not be published for the user because it is currently in use by the user.  Shut down all applications in the group, and try again.
Connection Group %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1066</td><td>An app connection group could not be globally published because it is currently in use.  Make sure all users have shut down all applications in the group, and try again.
Connection Group %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1067</td><td>A package could not be published for the user because it is currently in use by the user.  The package will be published at a later time.
Package %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1068</td><td>A package could not be globally published because it is currently in use.  The package will be published at a later time.
Package %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1069</td><td>A connection group could not be published for the user because it is currently in use by the user.  The connection group will be published at a later time.
Connection Group %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1070</td><td>A connection group could not be globally published because it is currently in use.  The connection group will be published at a later time.
Connection Group %1
Version %2
Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1071</td><td>The package %1 version %2 was detected to have an upgrading task. The App-V Client cannot start the virtual environment. Please try again in several minutes once the update is complete.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1072</td><td>The application connection group %1 version %2 was detected to have an upgrading task. The App-V Client cannot start the virtual environment. Please try again in several minutes once the update is complete.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1073</td><td>The pending publish operation for package %1 version %2 was not performed because network connectivity is not available.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1074</td><td>The package %1 version %2 was detected to have a pending publish or unpublish operation. The App-V Client cannot remove the package. Pending user operations are processed at logon, and pending global operations are processed at startup. Please try again when any related pending operations are complete. Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1075</td><td>The app connection group %1 version %2 was detected to have a pending task. The App-V Client cannot remove the app connection group. Pending user operations are processed at logon, and pending global operations are processed at startup. Please try again when any related pending operations are complete. Activity #%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1076</td><td>The UserSID value %1 is not valid. Please ensure it is a valid SID and that the associated user is logged in when you run the cmdlet. {error: %2-%3}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1077</td><td>While publishing package %1 version %2 an error occurred when obtaining the integration settings for each of the connection groups that the package belongs to {error %3 - %4}.
The package has not been published.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1078</td><td>Package %1 version %2 was user published while belonging to globally published Connection Group %3 version %4.
Therefore, although the package will be published to the user, it will not be assocated with the Connection Group until it is also published globally.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1079</td><td>The App-V driver mappings were not successfully updated when Package %1 version %2 was added (error: %3-%4).
Connection Groups containing this package may not work correctly.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1080</td><td>The App-V driver mappings were not successfully updated when Package %1 version %2 was removed (error: %3-%4).
Connection Groups previously containing this package may not work correctly.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1082</td><td>The App-V driver mappings were not successfully updated when Package %1 version %2 was published (error: %3-%4).
Connection Groups previously containing this package may not work correctly.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>1083</td><td>The App-V driver mappings were not successfully updated when Package %1 version %2 was unpublished (error: %3-%4).
Connection Groups previously containing this package may not work correctly.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>2001</td><td>Failed to move Catalog folder ‘%1’ to new required location ‘%2’. {error: %3}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>2002</td><td>Catalog folder ‘%1’ was migrated to new required location ‘%2’, but the old location could not be removed.  The Catalog will be used from the new location. {error: %3}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>2003</td><td>Catalog folder ‘%1’ was migrated to new required location ‘%2’, but the new location previously existed.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>2004</td><td>Failed due to could not get catalog folder. {error: %1-%2}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>2005</td><td>The package %1 version %2 was detected to be in an irreconcilable state and has been removed. Please manually remove any remaining data (by default under %ProgramData%\App-V\) when re-adding the package.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>2006</td><td>The app connection group %1 version %2 was detected to be in an irreconcilable state and has been removed. Please manually remove any remaining data (by default under %ProgramData%\App-V\) when re-adding the app connection group.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>3001</td><td>The Client service has encountered a critical security issue and must shut down immediately. {error %1-%2}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>3002</td><td>The Client service has encountered a critical security issue and must shut down immediately. {error %1-%2}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>4001</td><td>The App-V client failed to create a process for %1 script event %2 with command line: &#39;%3&#39;. Windows error: %4.  The path must be a Windows application (.exe file).</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>4002</td><td>The App-V client waited for the designated Timeout of %1 seconds for %2 script event %3 with executable: &#39;%4&#39; to complete. Because the Timeout was reached, the script process was terminated. Since RollbackOnError is set to true in script definition, the current AppV Client operation was rolled back due to script timeout.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>4004</td><td>Running %1 script defined in package %2 for event %3. Script execution was initiated by User Account: &#39;%4&#39;; command line: &#39;%5&#39;.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>4005</td><td>A %1 script is defined in package %2 for event %3 but will not be run because embedded scripting is disabled for this client.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>4006</td><td>Parsing of Embedded Script XML in package Manifest failed. Package: %1; event name: %2; XML parsing error: %3-%4. Please ensure that the XML script section in the package manifest for event %2 is well formed.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>4007</td><td>An error was encountered while reading the setting to enable scripts. Error code:  %1-%2.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>4008</td><td>The App-V client waited for the designated Timeout of %1 seconds for %2 script event %3 with executable: &#39;%4&#39; to complete. Because the Timeout was reached, the script process was terminated. Since RollbackOnError is set to false in script definition, the timeout is ignored and current AppV Client operation will continue.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>4009</td><td>%1 script for event %2 with command line: &#39;%3&#39; exited with failure error code: %4. Because Rollback is set to true in the script definition, the current AppV Client operation was rolled back.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>4010</td><td>%1 script for event %2 with command line: &#39;%3&#39; exited with failure error code: %4. Because Rollback is set to false in the script definition, the script process failure is ignored and the current AppV Client operation will continue.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>4011</td><td>Appv Client Scripting Component failed to acquire a proper token before querying Appv Client settings for Scripting, the query of the settings for Scripting may fail.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>5001</td><td>The move/rename of a directory was blocked by the Virtual File System because it represented the merged view of more than one package directory and/or a non-package directory.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>5002</td><td>The delete of a directory was blocked by the Virtual File System because it represented the merged view of more than one package directory and/or a non-package directory.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>5003</td><td>The delete of directory &#39;%1&#39; was blocked by the Virtual File System because it represented the merged view of more than one package directory and/or a non-package directory.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6001</td><td>Failed to get Virtual Service information from manifest.
 Package: %1
 Version: %2
 Error: %3-%4</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6002</td><td>Virtual Service startup type %1 is not supported. The only supported configuration values are Automatic, Manual and Disabled.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6006</td><td>Service %1 failed to start due to error %2.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6007</td><td>DependentService %1 failed to start due to error %2.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6008</td><td>Service %1 failed while handling a control message due to error %2.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6009</td><td>Could not acquire service start lock due to error %1.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6010</td><td>Starting automatic service %1.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6011</td><td>Service %1 could not be stopped.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6012</td><td>Automatic service %1 could not be started.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6013</td><td>Request to change the service configuration is rejected. Currently, changing service configuration during runtime is not supported.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6014</td><td>Request to delete a virtual service is rejected. Currently, deleting a service during runtime is not supported.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6015</td><td>Service %1 is created as a native service instead of a virtual service. Creating virtual service during runtime is not supported.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>6016</td><td>Request to set virtual service security is rejected. Currently, changing service security during runtime is not supported.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>7001</td><td>The client service has encountered an error monitoring settings. Changes to some settings will not take effect until the service is restarted. {error: %1}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8001</td><td>Failed to load provided xml.
DOM Error: %1
Reason: %2
Line: %3
Column: %4
Offset: %5</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8002</td><td>Failed to validate provided xml.
DOM Error: %1
Reason: %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8003</td><td>Invalid connection group document format. There are no packages specified in the connection group document for connection group %1, version %2.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8004</td><td>Invalid connection group XML document format. There needs to be at least one mandatory package in the connection group XML document for connection group %1, version %2.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8005</td><td>Failed to update the connection groups for user %1. Some virtualized applications may fail to execute properly. Error: %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8006</td><td>All of the package groups associated with the publishing of package %1, version %2 were not successfully refreshed. Error: %3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8007</td><td>All of the package groups associated with the unpublishing of package %1, version %2 were not successfully refreshed. Error: %3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8008</td><td>All of the package groups associated with the adding of package %1, version %2 were not successfully refreshed. Error: %3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8009</td><td>Failed to get the package groups associated with the removal of package %1, version %2. Error: %3.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8010</td><td>All of the package groups associated with the removal of package %1, version %2 were not successfully refreshed. Error: %3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8011</td><td>Package group %1, version %2 was not successfully refreshed. Error: %3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8012</td><td>Mandatory package %3, version %4 specified in connection group %1, version %2 has not been added to the computer or has not been entitled to the user.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8013</td><td>Error %3-%4 occurred while attempting to delete the user publishing data associated with group %1, version %2 for user %5. The publishing data may need to be removed manually.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8014</td><td>Error %3-%4 occurred while attempting to unpublish group %1, version %2 for user %5. This error should correct itself on the next publishing refresh for the user.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8015</td><td>Failed to get the package groups associated with the unpublish of package %1, version %2. Error: %3.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>8016</td><td>Registry path %1 was malformed in dynamic configuration file for package %2, version %3.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>9001</td><td>Error encountered while executing command %1. Error: %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>9002</td><td>Warning raised while executing command %1. Warning: %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>9003</td><td>Error encountered when accessing a property value of an App-V Publishing Server. This Publishing Server has been skipped.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>9004</td><td>Error encountered when accessing a property value of an App-V Client Connection Group. This Connection Group has been skipped.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>9005</td><td>Error encountered when accessing a property value of an App-V Client Package. This Package has been skipped.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>9006</td><td>Error encountered when accessing a property value of an App-V Client Application. This Application has been skipped.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>9007</td><td>Error encountered when attempting to access the packages of an App-V Client Connection Group. This Connection Group will display no Packages.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>9008</td><td>Error encountered when attempting to access the applications of an App-V Client Package. This Package will display no Applications.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>9009</td><td>Error encountered during Powershell process startup or exit while executing command &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>9010</td><td>Error encountered while executing command &#39;%1&#39;. Please refer to the AppV Client log for error details.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>9012</td><td>Error encountered when accessing a property value of an App-V Client Configuration.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>10001</td><td>Process %1 failed to start due to %4 subsystem failure. Package ID %2. Version ID %3. Error: %5-%6</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>10002</td><td>Unable to inject into a non-virtual process with PID %1. This process will not be able to use virtual components.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>11002</td><td>Could not takeover extension points ownership from legacy package %1. Error: %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>11003</td><td>Could not give extension points ownership back to legacy package %1. Error: %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>11004</td><td>MigrationMode is enabled but legacy App-V Client is not installed on the machine. Managing Authority policy will not be applied for the package %1.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>11005</td><td>Taking over extension points ownership using command: %1</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>11006</td><td>Give back extension points ownership using command: %1</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>11007</td><td>Failed reading Managing Authority policy for package %1. Error: %2-%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>11008</td><td>Failed reading old Managing Authority policy for package %1. Error: %2-%3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>11009</td><td>Error &#39;%2&#39; waitig for command: %1</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>11010</td><td>Timed out waitig for command: %1</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>11011</td><td>Error &#39;%2&#39; getting exit code for command: %1</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>11012</td><td>Command &#39;%1&#39; exited with code: %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>12001</td><td>A conflict was detected in the user configuration setting for enabling the virtual registry in virtual application connection group %1 version %2. The virtual application could not be started.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>13001</td><td>User VFS COW state deleted for package ID %1.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>13002</td><td>User VFS COW state deletion failed for package ID %1, error %2-%3.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>13003</td><td>%1 application from package ID %2 failed to launch. process ID %3, error %4-%5.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>13004</td><td>User VFS COW folder validation failed for source: %1, target: %2.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>13005</td><td>Failed to publish roaming packages, error %1-%2.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>13006</td><td>Failed to publish roaming groups, error %1-%2.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>13007</td><td>Security information for VFS directory %1 has changed from its previous value.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>13008</td><td>Error: %1-%2. Process %3 already belongs to a job. It cannot be added to the virtual environment. Package %4, Version %5.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>13009</td><td>Error: %3-%4. Package %1, Version %2 has not been updated to the latest version for this client. The package can be updated by either running a repair operation or by unpublishing and removing              it and then adding and publishing it again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>13010</td><td>Error: %3-%4. Package Group %1, Version %2 has not been updated to the latest version for this client. The package group can be updated by either running a repair operation or by disabling and removing              it and then adding and enabling it again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>13011</td><td>Package %1, Version %2 contained errors in the user state data and has been repaired as part of an upgrade operation. The user-specific application settings have been reset to their original              state when the package was originally added to the system.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>13012</td><td>Package Group %1, Version %2 contained errors in the user state data and has been repaired as part of an upgrade operation. The user-specific application settings have been reset to their original              state when the package group was originally added to the system.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14001</td><td>App-V client is relying on a mobile network connection to stream packages.  Background streaming has been suspended due to the mobile network approaching/exceeding the data limit or roaming.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14002</td><td>App-V client has detected an unrestricted network connection or a mobile connection with sufficient remaining data capacity.  Background streaming has resumed.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14003</td><td>App-V client has detected that you are trying to launch a new application on a mobile network connection.  The launch has been blocked due to the mobile network approaching/exceeding the data limit or roaming.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14004</td><td>Unexepected error.  The App-V client was unable to register for the network cost callback and will be unable to suspend background loads if the network cost increases.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14005</td><td>Unexpected error %1-%2.  The App-V client was unable to start the background load queue.  Packages will not be loaded in the background automatically.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14006</td><td>Unexpected error.  The App-V client was unable to start the background load queue properly.  Package information is not available to determine if background loads are local or remote.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14007</td><td>App-V client has entered connected standby mode.  Background streaming has been suspended.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14008</td><td>App-V client has exited connected standby mode.  Background streaming has resumed.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14009</td><td>App-V client has detected an HTTP error 502 while attempting to stream a package.  This can be the result of a proxy server not being configured to allow a high enough rate of requests from the client to the package server.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14010</td><td>The package %1 version %2 could not be configured because the path %3 could not be reached.  Ensure the path is correct and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14011</td><td>The package %1 version %2 could not be configured because the package is corrupt.  Ensure that the package file is a valid App-V package and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14012</td><td>The package %1 version %2 could not be configured because the package store location is not on a valid NTFS file system.  Ensure that the package store location is a valid NTFS file system and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14013</td><td>The package %1 version %2 could not be configured due to low disk space.  Ensure that there is enough disk space and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14014</td><td>The package %1 version %2 could not be configured because the specified URL is not valid.  Ensure that the URL is valid and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14015</td><td>The package %1 version %2 could not be configured because the target location %3 already exists.  Ensure that this location is removed and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14016</td><td>The package %1 version %2 could not be mounted because the network connection has been lost or is unavailable.  Check your network connection and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14017</td><td>The package %1 version %2 could not be mounted. The operation failed with HRESULT %3, probably due to low disk space.  Ensure that there is enough disk space and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14018</td><td>The package %1 version %2 could not be mounted due to the network connection timing out.  Check your network connection and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14019</td><td>The package %1 version %2 full mount was suspended because the user who initiated the operation has logged off.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14020</td><td>The package %1 version %2 failed to be configured because the package is not valid for the current CPU architecture.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14021</td><td>Content required by an application could not be retrieved from the network. A request for file %2 from package version %1 failed with error %3.  Check your network connection and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14022</td><td>The App-V Client failed to initialize properly.  The Streaming Mini-Filter failed to initialize with error code %1. Please verify that the App-V Client is installed properly.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14023</td><td>A request for the file %1 from process %2 is being processed as SYSTEM since no suitable user token could be found.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14024</td><td>A request for the file %1 from process %2 is being processed as an alternate user %3.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14025</td><td>App-V client has detected that the system has exited idle state. Background streaming has been suspended due to the system coming out of idle state.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14026</td><td>App-V client has detected that the system has entered idle state. Background streaming has resumed.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14027</td><td>App-V client failed to create the idle state detector.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14028</td><td>App-V client failed to register for idle state callback.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>14029</td><td>App-V package root folder ownership has been changed from LocalSystem to %1.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>15001</td><td>The AppVStreamingUX application experienced an AppV error while attempting to connect to the AppVClient service. The AppVStreamingUX process will now exit. AppV Error: %1-%2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>15002</td><td>The AppVStreamingUX application experienced a COM error while attempting to connect to the AppVClient service. The AppVStreamingUX process will now exit. HResult: %1</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>15003</td><td>The AppVStreamingUX application experienced an AppV error while attempting to stop a package or connection group. Running Virtual Environment ID: %1, Version: %2, AppV Error: %3 - %4</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>16001</td><td>A conflict was detected in the configuration settings for Virtual Object exclusions in virtual application connection group %1 version %2. The virtual application could not be started. Verify that the settings are correct and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>16002</td><td>A conflict was detected in the &#39;enabled&#39; setting for Virtual Object subsystem in virtual application connection group %1 version %2. The virtual application could not be started. Verify that the settings are correct and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>16003</td><td>The connection group %1 version %2 could not be published because the virtual objects settings of the individual packages conflict. Verify that the virtual objects settings are the same for all member packages and try again.
Error code: %3 - %4</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>16004</td><td>Failed to publish package %1 version %2 because its virtual objects settings do not match those of other packages in connection group %3 version %4.
Verify that the virtual objects settings are the same for all member packages and try again.
Error code: %5 - %6</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>17001</td><td>Failed to save last report data cache file path %1 to the registry due to error %2.  If there is a Client failure before the next save attempt, and the report data must be loaded from the cache, some records may be missing.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>17002</td><td>Reporting data cache could not be loaded from %1 due to error %2-%3.  A new report data cache file will be generated and saved separately.  Any report data from the previous cache file will be lost.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>17003</td><td>Reporting data manager queue worker thread is exiting on unexpected wait condition %1, error code %2.  No further report records will be processed.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>17004</td><td>Reporting data cache could not be saved to disk after adding new records (rc = %1-%2); those records may be lost if the Client shuts down before the next attempt to save or transmit the cache.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>17005</td><td>Reporting data cache has exceeded the maximum cache size, and older records will be discarded to make room for new records until the cache can be transmitted to a Reporting Server.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>17006</td><td>Reporting data cache could not be sent to Reporting Server. (rc = %1-%2).</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>17007</td><td>Failed to add application launch data to the reporting queue. This application launch will not be reported to the reporting server. (rc = %1-%2).</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>17008</td><td>Failed to add application shutdown data to the reporting queue. This application shutdown will not be reported to the reporting server. (rc = %1-%2).</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>17009</td><td>Failed to add virtual environment created data for the launching application. The application launch will not be reported to the reporting server. (rc = %1-%2).</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>17010</td><td>Failed to add virtual environment terminated data for the terminating application. The application shutdown will not be reported to the reporting server. (rc = %1-%2).</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>17011</td><td>Failed to save updated cached file after upload due to error %1-%2; duplicate records may be sent to the server if the cache must be reloaded before the next save attempt.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>17012</td><td>Failed to add virtual process launch failure information for the terminating process. The application launch failure will not be reported to the reporting server. (rc = %1-%2).</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>18001</td><td>A virtual application could not be launched from package &#39;%1&#39; because the App-V Client Service is not running.  Start the App-V Client Service and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>18002</td><td>The virtual application &#39;%1&#39; could not be launched because the user is not entitled to the package to which it belongs.  Either publish the package to the user or globally and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>18003</td><td>The virtual application &#39;%1&#39; could not be launched because the App-V Client could not determine which environment to use.  Provide a priority to the app connection group for the package and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>18004</td><td>The virtual application &#39;%1&#39; could not be launched because the service &#39;%2&#39; could not be started.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>18005</td><td>The virtual application &#39;%1&#39; could not be started because the App-V Subsystem &#39;%2&#39; could not be initialized. {error: %3-%4}</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>18006</td><td>The virtual environment for connection group %1 version %2 could not be created because the package %3 version %4 is not published.  Publish the package and try again.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19001</td><td>Publishing Refresh started.
 URL: %1
 Global: %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19002</td><td>Publishing Refresh stopped.
 URL: %1
 Global: %2
 Return code: %3 - %4</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19010</td><td>Settings synced.
 Return code: %1 - %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19011</td><td>Settings sync failed.
 Error code: %1 - %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19101</td><td>Getting client information failed.
 Error code: %1 - %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19102</td><td>Getting server publishing data failed.
 URL: %1
 Error code: %2 - %3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19103</td><td>Getting client published data failed.
 Error code: %1 - %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19104</td><td>Part or all packages publish failed.
 published: %1
 failed: %2 
Please check the error events of &#39;Configure/Publish Package&#39; before this message for the details of the failure.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19105</td><td>Part or all packages un-publish failed.
 un-published: %1
 failed: %2 
Please check the error events of &#39;Unpublish Package&#39; before this message for the details of the failure.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19106</td><td>Part or all groups publish failed.
 published: %1
 failed: %2 
Please check the error events of &#39;Configure/Publish Virtual Application Connection Group&#39; before this message for the details of the failure.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19107</td><td>Part or all groups un-publish failed.
 un-published: %1
 failed: %2 
Please check the error events of &#39;Unpublish Virtual Application Connection Group&#39; before this message for the details of the failure.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19108</td><td>Failed to publish group due to the failure of the package.
 Group GUID: %1
 Group Version GUID: %2
 Package GUID: %3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19201</td><td>Unknown protocol for package URI.
 input: %1</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19202</td><td>HttpRequest initialize failed.
 URL: %1
 Error code: %2 - %3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19203</td><td>HttpRequest sendRequest failed.
 URL: %1
 Error code: %2 - %3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19204</td><td>The content could not be coverted to unicode.
 URL: %1</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19205</td><td>The content from server is not valid XML for publishing.
 URL: %1
 Error code: %2 - %3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19301</td><td>Failed to create default machine policy document.
 Package: %1, %2
 Error code: %3 - %4</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19302</td><td>Failed to create machine policy document from string.
 Package: %1, %2
 Error code: %3 - %4</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19303</td><td>Failed to create user policy document from string.
 Package: %1, %2
 Error code: %3 - %4</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19304</td><td>Failed to create package group descriptor document from string.
 Group: %1, %2
 Error code: %3 - %4</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19401</td><td>Failed to get publishing server record from registry.
 Server ID: %1
 Error code: %2 - %3</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19402</td><td>The URL has already been used by other publishing server.
 Server ID: %1
 URL: %2</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19403</td><td>No URL was supplied for the publishing server.
 Server ID: %1</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19404</td><td>The ID for the publishing server is out of the range.
 Server ID: %1
 Valid Range: [1~5]</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19405</td><td>The interval of hours for the publishing server is out of the range.
 Server ID: %1
 Interval: %2
 Valid Range: [0~23]</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19406</td><td>The interval of days for the publishing server is out of the range.
 Server ID: %1
 Interval: %2
 Valid Range: [0~365]</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19407</td><td>The interval unint for the publishing server is not valid.
 Server ID: %1
 Interval Unit: %2
 Valid Values: 0/Hour, 1/Day</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19408</td><td>The stored URL %1 for the server %2 is incorrectly formatted.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19501</td><td>SyncAppvPublishingServer completed successfully: &#39;%1&#39;.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19502</td><td>SyncAppvPublishingServer failed due to a PowerShell error.
Error: &#39;%1&#39;</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19801</td><td>Deimpersonation failed.
 Error: %1 - %2.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19802</td><td>Read policy identities failed.
 URL: %1
 Global: %2
 For deployment configuration: %3
 Error: %4 - %5.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19803</td><td>Write policy identities failed.
 URL: %1
 Global: %2
 For deployment configuration: %3
 Error: %4 - %5.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19804</td><td>File type associations, shell extensions, and shortcuts updated.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>19805</td><td>Failed to update file type associations, shell extensions, and shortcuts.
 Error: %1 - %2.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>20001</td><td>The connection group %1 version %2 could not be published because the virtual COM settings of the individual packages conflict.  Verify that the virtual COM settings are the same for all member packages and try again.
Error code: %3 - %4</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>20002</td><td>Package %1 version %2 could not be published because its virtual COM settings conflict with those of other packages in connection group %3-%4.  Verify that the virtual COM settings are the same for all member packages and try again.
Error code: %5 - %6</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>20101</td><td>Package %1 version %2 could not be published because its virtual file system settings conflict with other packages in connection group %3-%4.  Verify that the virtual COM settings are the same for all member packages and try again.
Error code: %5 - %6</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>21001</td><td>An error was encountered while reading the setting to enable or disable Dynamic Virtualization. Dynamic Virtualization is enabled by default and can be modified using the Set-AppvClientConfiguration Powershell cmdlet. Error code:  %1-%2.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>21002</td><td>Dynamic Virtualization is currently disabled. Publishing will not take effect for shell extensions, browser plugins, or ActiveX controls. To modify this setting, use the Set-AppVClientConfiguration Powershell cmdlet.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>22001</td><td>The SxS assembly &#39;%1&#39; could not be installed because its payload file &#39;%2&#39; is not part of the package. Please ensure this assembly is installed natively to ensure package functionality.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>23001</td><td>A timeout occurred while streaming an application, which may have prevented the application from running. The application should start successfully the next time it is launched.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>24001</td><td>Enable Appv failed with error %1.</td></tr>
<tr><td>Microsoft-AppV-Client</td><td>24002</td><td>Disable Appv failed with error %1.</td></tr>
</table>
