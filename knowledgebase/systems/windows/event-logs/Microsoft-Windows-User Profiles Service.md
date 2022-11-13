# Microsoft-Windows-User Profiles Service

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1</td><td>Recieved user logon notification on session %1.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>2</td><td>Finished processing user logon notification on session %1.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>3</td><td>Recieved user logoff notification on session %1.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>4</td><td>Finished processing user logoff notification on session %1.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>5</td><td>Registry file %1 is loaded at HKU\%2.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>6</td><td>Starting synchronize profile from %1 to %2.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>7</td><td>Finished synchronize profile from %1 to %2. 

Result: %3</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>50</td><td>Background hive upload for user %1 started.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>51</td><td>Background hive upload for user %1 succeeded.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>52</td><td>Background hive upload for user %1 failed.

 Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>53</td><td>Cannot delete file %1.

 Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>54</td><td>Open user regisry root key for %1 failed.

 Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>55</td><td>Save user hive to file %1 failed.

 Error: %2</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>56</td><td>Save user hive to file %1 succeeded.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>57</td><td>Enable background user hive upload task succeeded.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>58</td><td>Failed to enable background user hive upload task.

 Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>59</td><td>Disable background user hive upload task succeeded.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>60</td><td>Failed to disable background user hive upload task.

 Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>61</td><td>Slow network connection detected, abort background user hive upload task.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>62</td><td>Windows was unable to successfully evaluate whether this computer is a primary computer for this user. This may be due to failing to access the Active Directory server at this time. The user&#39;s roaming profile will be applied as configured. Contact the Administrator for more assistance. Error: %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>63</td><td>This computer %1 a primary computer for this user.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>64</td><td>The primary computer relationship for this computer and this user was not evaluated due to %1.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>65</td><td>The attempt to create or open the profile key for the user failed with error %1.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>66</td><td>Creating the local profile for the user failed with error %1.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>67</td><td>Logon type: %1 
Local profile location: %2 
Profile type: %3</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>68</td><td>LastDownloadTime: %1 
LastUploadTime: %2</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>70</td><td>Waiting on network arrivals. Max wait time %1 ms.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>71</td><td>After waiting %1 ms, a network with the necessary capabilities was not ready for use. Allowing profile load to proceed.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>72</td><td>Terminating wait due to unexpected failure %1.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>73</td><td>Wait complete due to connectivity event but network not ready.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>74</td><td>Wait completed due to network connectivity or determination that no viable network connection is likely to become available. Allowing profile load to proceed.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>75</td><td>Roaming Profiles configuration is being controlled by Group Policy.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>76</td><td>Roaming Profiles configuration is being controlled by WMI configuration classes Win32_RoamingProfileUserConfiguration and Win32_RoamingProfileMachineConfiguration.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1001</td><td>Begin new user profile creation.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1002</td><td>New user profile creation complete.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1003</td><td>A network latency of %1 milliseconds has been detected.  Maximum latency to synchronize a roaming profile is set at %2 milliseconds.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1004</td><td>A network bandwidth of %1 kilobits per second has been detected.  Minimum bandwidth to synchronize a roaming profile is set at %2 kilobits per second.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1005</td><td>Delete cached profile %1 since it is older than %2 days.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1500</td><td>Windows cannot log you on because your profile cannot be loaded. Check that you are connected to the network, and that your network is functioning correctly. 

 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1501</td><td>Windows cannot create a temporary profile directory. This problem may be caused by insufficient security rights. 

 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1502</td><td>Windows cannot load the locally stored profile. Possible causes of this error include insufficient security rights or a corrupt local profile. 

 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1503</td><td>Windows cannot set security on your registry. 

 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1504</td><td>Windows cannot update your roaming profile completely. Check previous events for more details. 

</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1505</td><td>Windows cannot load the user&#39;s profile but has logged you on with the default profile for the system. 

 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1506</td><td>Your roaming profile is not available. You are logged on with the locally stored profile. Changes to the profile will not be copied to the server. Possible causes of this error include network problems or insufficient security rights.  

 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1508</td><td>Windows was unable to load the registry. This problem is often caused by insufficient memory or insufficient security rights. 

 DETAIL - %1 for %2</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1509</td><td>Windows was unable to load %1.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1510</td><td>Windows cannot load your profile because it appears to be corrupted.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1511</td><td>Windows cannot find the local profile and is logging you on with a temporary profile. Changes you make to this profile will be lost when you log off.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1512</td><td>Windows cannot unload your registry file. The memory used by the registry has not been freed. This problem is often caused by services running as a user account. Try configuring services to run in either the LocalService or NetworkService account. 

 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1513</td><td>Windows cannot copy your profile because it contains encrypted files or directories. The keys to decrypt the files or directories are also stored in the profile and are not available now. Decrypt the files and try again.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1514</td><td>The roaming profile path %1 is too long. Windows is logging you on with a default profile.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1515</td><td>Windows has backed up this user profile. Windows will automatically try to use the backup profile the next time this user logs on.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1517</td><td>Windows saved user %1 registry while an application or service was still using the registry when the user logged off. The memory used by the user registry has not been freed. The registry will be unloaded when it is no longer in use. 

 This error may be caused by services running as a user account. Try configuring services to run in either the LocalService or NetworkService account.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1518</td><td>Windows cannot create a local profile and is logging you on with a temporary profile. This profile will be deleted when you log off. This problem may be caused by incorrect file system permissions or network problems.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1519</td><td>Windows cannot locate your roaming mandatory profile and is attempting to log you on with your local profile. This error may be caused by incorrect file system permissions or network problems. 

 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1520</td><td>Windows cannot log you on because your roaming mandatory profile is not available. This error may be caused by incorrect file system permissions or network problems. 

 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1521</td><td>Windows cannot locate the server copy of your roaming profile and is attempting to log you on with your local profile. Changes to the profile will not be copied to the server when you log off. This error may be caused by network problems or insufficient security rights. 

 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1522</td><td>Windows cannot locate your roaming profile (read only) and is attempting to log you on with your local profile. This error may be caused by network problems or insufficient security rights. 

 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1523</td><td>Your roaming profile (read only) is not available. You are logged on with the locally stored profile. This error may be caused by incorrect file system permissions or network problems.  

 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1524</td><td>Windows cannot unload your classes registry file - it is still in use by other applications or services. The file will be unloaded when it is no longer in use.  

</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1525</td><td>Windows has detected that Automatic Offline Caching is enabled on the Roaming Profile share - to avoid potential profile corruption, Offline Caching must be set to manual or disabled on shares where roaming user profiles are stored. 

</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1526</td><td>Windows could not load your roaming profile and is attempting to log you on with your local profile. Changes to the profile will not be copied to the server when you log off. Windows could not load your profile because a server copy of the profile folder already exists that does not have the correct security. Either the current user or the Administrators group must be the owner of the folder. 

</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1527</td><td>Windows failed to initialize user profiles. Non-console users will be unable to log on.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1529</td><td>Roaming user profiles across forests are disabled. Windows did not load your roaming profile and is logging you on with a local profile. Changes to the profile will not be copied to the server when you log off.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1530</td><td>Windows detected your registry file is still in use by other applications or services. The file will be unloaded now. The applications or services that hold your registry file may not function properly afterwards. No user action is required.  

 DETAIL - 
 %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1531</td><td>The User Profile Service has started successfully.  

</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1532</td><td>The User Profile Service has stopped.  

</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1533</td><td>Windows cannot delete the profile directory %1. This error may be caused by files in this directory being used by another program. 

 DETAIL - %2</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1534</td><td>Profile notification of event %1 for component %2 failed, error code is %3. 

</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1535</td><td>Successfully suspended folder &quot;%1&quot;</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1536</td><td>Successfully unsuspended folder &quot;%1&quot;</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1537</td><td>Failed to suspend folder &quot;%1&quot;
 DETAIL - %2</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1538</td><td>Failed to unsuspend folder &quot;%1&quot;
 DETAIL - %2</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1539</td><td>Failed to sync folder &quot;%1&quot;
 DETAIL - %2</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1540</td><td>Your roaming profile is not synchronized correctly with the server. Windows will load your previously-saved local profile instead. See the previous events for details.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1541</td><td>Failed to apply CSC suspend policy. Cannot connect to CSC service.
 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1542</td><td>Windows cannot load classes registry file.
 DETAIL - %1</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1543</td><td>A slow network connection is detected for the roaming profile %1. It will not be synchronized with the profile on this computer.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1544</td><td>Windows cannot back up a ProfileList entry because one already exists for this user. Only the existing backup entry will be kept in the ProfileList. Future logons will restore the ProfileList entry from the existing backup entry.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1545</td><td>User hive is loaded by another process (File Lock). Process name: %1, PID: %2, ProfSvc PID: %3.</td></tr>
<tr><td>Microsoft-Windows-User Profiles Service</td><td>1552</td><td>User hive is loaded by another process (Registry Lock) Process name: %1, PID: %2, ProfSvc PID: %3.</td></tr>
</table>
