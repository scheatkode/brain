# Microsoft-Windows-BitLocker-API

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>513</td><td>BitLocker Drive Encryption recovery information was backed up successfully to Active Directory Domain Services.
Protector GUID: %1
Volume GUID: %2</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>514</td><td>Failed to backup BitLocker Drive Encryption recovery information to Active Directory Domain Services.
Errorcode: %2
Protector GUID: %1
Volume GUID: %3</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>515</td><td>BitLocker Drive Encryption recovery information for the specified protector is already present in Active Directory Domain Services.
Protector GUID: %1
Volume GUID: %2</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>516</td><td>A BitLocker certificate data recovery agent was created, because it was missing on the volume or added to the list of data recovery agents.
Certificate thumbprint: %2
Protector GUID: %1
Volume GUID: %3</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>517</td><td>A BitLocker certificate data recovery agent was removed, because is no longer in the list of data recovery agents.
Certificate thumbprint: %2
Protector GUID: %1
Volume GUID: %3</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>518</td><td>The attempt to create a data recovery agent protector on the BitLocker volume failed.
Errorcode: %1
Certificate thumbprint: %2
Volume GUID: %3</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>519</td><td>The servicing of the data recovery agents on the volume failed.
Errorcode: %1
Volume GUID: %2</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>520</td><td>The management of the data recovery agents failed on this drive because this feature of BitLocker Drive Encryption is not supported in this edition of the Windows operating system. 
Errorcode: %1
Volume GUID: %2</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>521</td><td>Bootmgr failed to obtain the BitLocker volume master key from the TPM because the PCRs did not match.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>522</td><td>Bootmgr determined that the following boot application has changed: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>523</td><td>Bootmgr determined that the boot configuration data setting %1 has changed for the following boot application: %2</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>524</td><td>Bootmgr determined that the authorization data for the SRK of the TPM is incompatible with BitLocker.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>525</td><td>Bootmgr determined that the TPM is disabled.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>526</td><td>Bootmgr determined that the TPM is not accessible.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>527</td><td>The partition size specified in the partition table is smaller than the size of the file system contained by that partition.  BitLocker TPM based keys cannot be used until the size of the partition calculated from the partition table is consistent with the size of the file system calculated from the bytes per sector and number of sectors fields in the boot sector.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>528</td><td>Boot debugging is enabled on Bootmgr so TPM based keys cannot be obtained.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>529</td><td>Bootmgr determined that driver signature enforcement has been disabled.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>530</td><td>Bootmgr determined that the device was locked out due to too many failed password attempts.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>531</td><td>Bootmgr determined that the device was locked out due to Device Lockout state validation failure.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>768</td><td>BitLocker encryption was started for volume %3 using %4 algorithm.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>769</td><td>BitLocker encryption will occur for volume %3 when the computer is restarted using %4 algorithm.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>770</td><td>BitLocker decryption was started for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>771</td><td>BitLocker encryption was stopped for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>772</td><td>BitLocker encryption was restarted for volume %3 using %4 algorithm.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>773</td><td>BitLocker was suspended for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>774</td><td>BitLocker was resumed for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>775</td><td>A BitLocker key protector was created.
Protector GUID: %4
Identification GUID: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>776</td><td>A BitLocker key protector was removed.
Protector GUID: %4
Identification GUID: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>777</td><td>The PIN was updated for the operating system volume.
Protector GUID: %4
Identification GUID: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>778</td><td>The BitLocker volume %3 was reverted to an unprotected state.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>779</td><td>The BitLocker volume %3 was erased.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>780</td><td>The identification field was changed. 
Identification GUID: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>781</td><td>The BitLocker protected volume %3 was locked. 
Identification GUID: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>782</td><td>The BitLocker protected volume %3 was unlocked.
Protector GUID: %4
Identification GUID: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>783</td><td>BitLocker Drive Encryption recovery information for the specified protector is already present in Active Directory Domain Services.
Protector GUID: %4
Identification GUID: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>784</td><td>BitLocker Drive Encryption recovery information was backed up successfully to Active Directory Domain Services.
Protector GUID: %4
Identification GUID: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>785</td><td>Failed to backup BitLocker Drive Encryption recovery information to Active Directory Domain Services.
Protector GUID: %4
Identification GUID: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>786</td><td>BitLocker free space wiping was started for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>787</td><td>BitLocker free space wiping was stopped for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>788</td><td>BitLocker free space wiping was restarted for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>789</td><td>The PIN was changed.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>790</td><td>A PIN change attempt failed.
Error message: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>791</td><td>The BitLocker Service (BdeSvc) PIN and password change facility is locked out due to too many failed PIN or password change attempts.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>792</td><td>BitLocker encountered a failure to commit metadata changes for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>793</td><td>BitLocker resealed boot settings to the TPM for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>794</td><td>BitLocker failed to reseal boot settings to the TPM.
Error message: %1.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>795</td><td>BitLocker failed to initialize hardware encryption for volume %3 due to group policy.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>796</td><td>BitLocker Drive Encryption is using software-based encryption to protect volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>797</td><td>Group Policy settings prevented BitLocker Drive Encryption from reverting to BitLocker software-based encryption. Volume %3 is not protected by BitLocker.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>798</td><td>BitLocker failed to initialize hardware encryption for volume %3.
Drive is not provisioned for use with BitLocker hardware encryption:
Hardware-based encryption is not activated on this drive.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>799</td><td>BitLocker failed to initialize hardware encryption for volume %3.
Drive is not provisioned for use with BitLocker hardware encryption:
The hardware-based encryption of this drive does not allow BitLocker to cryptographically protect the drive&#39;s media encryption key.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>800</td><td>BitLocker failed to initialize hardware encryption for volume %3.
Drive is not provisioned for use with BitLocker hardware encryption:
Hardware-based encryption is either not configured or has been configured improperly on this volume.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>801</td><td>BitLocker failed to initialize hardware encryption for volume %3.
Drive is not provisioned for use with BitLocker hardware encryption:
Hardware-based encryption cannot be used with this drive because the hardware encryption method used by this drive does not comply with the Group Policy requirement for drive encryption.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>802</td><td>BitLocker failed to initialize hardware encryption for volume %3.
Drive is not provisioned for use with BitLocker hardware encryption:
The key length, %5 bits, required to enable hardware-based encryption is below the minimum key length supported by the drive: %4.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>803</td><td>BitLocker failed to initialize hardware encryption for volume %3.
Drive is not provisioned for use with BitLocker hardware encryption:
The key length, %5 bits, required to enable hardware-based encryption is above the maximum key length supported by the drive: %4.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>804</td><td>The target drive (%3) cannot be managed by BitLocker because the drive&#39;s hardware encryption feature is already in use.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>805</td><td>The BitLocker protected volume was unlocked in the Windows Recovery Environment.
Protector GUID: %2
Identification GUID: %1
Unlock time: %4</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>806</td><td>BitLocker resealed boot settings to the TPM in the Windows Recovery Environment.
Reseal time: %2</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>807</td><td>BitLocker free space wiping was canceled for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>808</td><td>BitLocker failed to initialize hardware encryption for volume %3.
Drive is not provisioned for use with BitLocker hardware encryption:
SID authority is not disabled on this drive.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>809</td><td>BitLocker cannot use Secure Boot for integrity because it is disabled in Group Policy.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>810</td><td>BitLocker cannot use Secure Boot for integrity because it is disabled.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>811</td><td>BitLocker cannot use Secure Boot for integrity because the required UEFI variable &#39;%1&#39; is not present.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>812</td><td>BitLocker cannot use Secure Boot for integrity because the UEFI variable &#39;%1&#39; could not be read.

Error Message: %2</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>813</td><td>BitLocker cannot use Secure Boot for integrity because the expected TCG Log entry for variable &#39;%1&#39; is missing or invalid.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>814</td><td>BitLocker cannot use Secure Boot for integrity because the expected TCG Log entry for the OS Loader Authority is missing or invalid.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>815</td><td>BitLocker cannot use Secure Boot for integrity because the expected TCG Log separator entry is missing or invalid.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>816</td><td>BitLocker cannot use Secure Boot for integrity because the TCG Log for PCR [7] contains invalid entries.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>817</td><td>BitLocker successfully sealed a key to the TPM.

PCRs measured include [%1].

The source for these PCRs was: %2.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>818</td><td>BitLocker encountered a failure attempting to configure network unlock for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>819</td><td>The BitLocker service could not resume protection on the OS volume %3, due to the following error: Bootable media in the drive.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>820</td><td>The BitLocker service could not resume protection on the OS volume %3, due to the following error: TPM is locked out.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>821</td><td>The BitLocker service could not resume protection on the OS volume %3, due to the following error: Group policy conflict.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>822</td><td>The BitLocker service could not resume protection on the OS volume %3, due to the following error code: %4.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>823</td><td>Bootmgr failed to obtain the BitLocker volume master key from the TPM because Secure Boot was disabled.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>824</td><td>Bootmgr failed to obtain the BitLocker volume master key from the TPM because Secure Boot configuration changed unexpectedly.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>825</td><td>BitLocker failed to initialize hardware encryption for volume %3.
This PC&#39;s firmware is not capable of supporting hardware encryption.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>826</td><td>The password was changed.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>827</td><td>A password change attempt failed.
Error message: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>828</td><td>BitLocker Drive Encryption recovery information for volume %3 was backed up successfully to your Microsoft account.
Protector GUID: %4</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>829</td><td>Failed to backup BitLocker Drive Encryption recovery information for volume %3 to your Microsoft account.

Error: %4</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>830</td><td>The BitLocker Drive Encryption recovery information already exists in your Microsoft account.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>831</td><td>Failed to save BitLocker Drive Encryption recovery information to your Microsoft account due to an error.

Error Code: %1
Localized Error Message: %2</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>832</td><td>TCG Log parsing failure.

Error: %1.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>833</td><td>BitLocker detected that custom Secure Boot policy is installed, and will seal to this configuration. Sealing to a custom policy may reduce the integrity provided by Secure Boot.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>834</td><td>BitLocker determined that the TCG log is invalid for use of Secure Boot. The filtered TCG log for PCR[7] is included in this event.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>835</td><td>BitLocker cannot use Secure Boot for integrity because the expected TCG Log entry for the OS Loader Authority has invalid structure.

The event is expected to be an EV_EFI_VARIABLE_AUTHORITY event. The event data must be formatted as an EFI_VARIABLE_DATA structure with VariableName set to EFI_IMAGE_SECURITY_DATABASEGUID and UnicodeName set to &#39;db&#39;.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>836</td><td>BitLocker cannot use Secure Boot for integrity because the expected TCG Log entry for the OS Loader Authority is invalid.

The contents of the EFI_VARIABLE_DATA.VariableData field should be an EFI_SIGNATURE_DATA structure with SignatureOwner set to the GUID {77fa9abd-0359-4d32-bd60-28f4e78f784b} (Microsoft).</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>837</td><td>BitLocker cannot use Secure Boot for integrity because the expected TCG Log entry for the OS Loader Authority is invalid.

The EFI_SIGNATURE_DATA structure contained in the OS authority event could not be found in the Secure Boot &#39;db&#39; signature database.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>838</td><td>BitLocker cannot use Secure Boot for integrity because the signature of the boot loader could not be validated as a Windows signature chained to a trusted Microsoft root certificate.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>839</td><td>BitLocker cannot use Secure Boot for integrity because the TCG Log entry for the OS Loader Authority is invalid.

The signature contained in the EFI_SIGNATURE_DATA structure from the OS authority event could not be found in the verified certificate chain for the boot loader.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>840</td><td>A trusted WIM file has been added for volume %3.
The SHA-256 hash of the WIM file is: %5</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>841</td><td>BitLocker was unable to update a key for volume %3 due to the following error: %4</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>842</td><td>BitLocker was unable to reseal boot settings to the TPM in the Windows Recovery Environment.

Error: %1

Protection has been temporarily suspended.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>843</td><td>BitLocker was suspended from within the Windows Recovery Environment.
Suspend time: %2</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>844</td><td>BitLocker was unable to recover from device lock in the Windows Recovery Environment.

Error: %1

Protection has been temporarily suspended.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>845</td><td>BitLocker Drive Encryption recovery information for volume %1 was backed up successfully to your Azure AD.
Protector GUID: %2.
TraceId: %3</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>846</td><td>Failed to backup BitLocker Drive Encryption recovery information for volume %1 to your Azure AD.
TraceId: %2

Error: %3</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>847</td><td>Failed to save BitLocker Drive Encryption recovery information to your Azure AD due to an error.

Error Code: %1
Localized Error Message: %2</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>848</td><td>Failed to update BCD store with the Recovery URL for OS volume.

Error: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>849</td><td>Failed to set the TPM dictionary attack parameters to the legacy behavior.

Error: %1.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>850</td><td>Successfully set the TPM dictionary attack parameters to the legacy behavior.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>851</td><td>Failed to enable Silent Encryption. 

Error: %1.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>852</td><td>Failed to enable Silent Encryption. Device is not AAD joined. 

Error: %1.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>853</td><td>Failed to enable Silent Encryption. TPM is not available. 

Error: %1.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>854</td><td>Failed to enable Silent Encryption. WinRe is not configured. 

Error: %1.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4096</td><td>Device Encryption could not be initialized.

Error: %1.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4097</td><td>Device Encryption initialization start.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4098</td><td>Device Encryption initialization stop.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4099</td><td>Device Encryption failed to process user logon event.

Error: %1.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4100</td><td>Beginning Device Encryption user logon processing.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4101</td><td>Ending Device Encryption user logon processing.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4102</td><td>BitLocker failed to recover after Device Lock.
Error message: %1.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4103</td><td>Failed to automatically enable Device Encryption.

Error Message: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4104</td><td>Begin Enable Protection.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4105</td><td>End Enable Protection.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4106</td><td>Failed to automatically back up recovery password to your Microsoft account.

Error Message: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4107</td><td>Begin Recovery Password Backup.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4108</td><td>End Recovery Password Backup.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4109</td><td>Begin Query Protection Status.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4110</td><td>End Query Protection Status.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4111</td><td>Device Lock recovery event initiated for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4112</td><td>MaxPasswordRetry policy enforced with TPM-based hardening for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4113</td><td>MaxPasswordRetry policy enforced without hardware based hardening for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4114</td><td>Device Lock recovery event initiated due to protected state mismatch for volume %3.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4116</td><td>Device Encryption initialization for volume %3 start.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4117</td><td>Device Encryption initialization for volume %3 stop.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4118</td><td>Volume %3 could not be initialized for Device Encryption.

Error: %4.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4119</td><td>Windows RE is not correctly configured for device encryption. Make sure that Windows RE is enabled and is not installed on the OS drive.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4120</td><td>The TPM is not provisioned for device encryption. To set up the TPM use the TPM management console (Start-&gt;tpm.msc) and use the action to make the TPM ready.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4121</td><td>Sign in with a Microsoft account to finish provisioning device encryption.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4138</td><td>Successfully setup TPM API callback.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4139</td><td>Failed to setup TPM API callback. Error Code: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4140</td><td>Successfully added predicted TPM protector.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4141</td><td>Failed to add predicted TPM protector. Error Code: %4.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4142</td><td>Predicted PCR4 value for TPM info based protector. Predicted Value: %5.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4143</td><td>Failed to evaluate PCR4 predicted value from TPM info. Error Code: %1</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4144</td><td>Predicted PCR7 value for TPM info based protector. Predicted Value: %5.</td></tr>
<tr><td>Microsoft-Windows-BitLocker-API</td><td>4145</td><td>Failed to evaluate PCR7 predicted value from TPM info. Error Code: %1</td></tr>
</table>
