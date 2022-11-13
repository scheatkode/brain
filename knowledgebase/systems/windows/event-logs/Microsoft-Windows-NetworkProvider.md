# Microsoft-Windows-NetworkProvider

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>Microsoft-Windows-NetworkProvider</td><td>1000</td><td>Ignoring UNC Hardening Configuration Entry: Unsupported registry value type.

Registry Value Path: %2@%4

Registry Value Type: %5

Guidance:
UNC Hardening configuration only supports registry values of types REG_SZ and REG_MULTI_SZ.

For details on configuring Windows computers to require additional security when accessing specific UNC paths, visit http://support.microsoft.com/kb/3000483.</td></tr>
<tr><td>Microsoft-Windows-NetworkProvider</td><td>1001</td><td>Ignoring UNC Hardening Configuration Entry: Unable to parse UNC Path.

UNC Path: %2

UNC Hardening Configuration: %4

Guidance:
The registry value name is not a valid UNC path.

For details on configuring Windows computers to require additional security when accessing specific UNC paths, visit http://support.microsoft.com/kb/3000483.</td></tr>
<tr><td>Microsoft-Windows-NetworkProvider</td><td>1002</td><td>Ignoring UNC Hardening Configuration Entry: Unsupported UNC Path.

UNC Path: %2

UNC Hardening Configuration: %4

Guidance:
UNC Hardening is only supported at server or share granularity. If only a fraction of the resources available on a share require additional security, consider relocating contents that require additional security to a different share.

For details on configuring Windows computers to require additional security when accessing specific UNC paths, visit http://support.microsoft.com/kb/3000483.</td></tr>
<tr><td>Microsoft-Windows-NetworkProvider</td><td>1003</td><td>Ignoring UNC Hardening Configuration Property: Unsupported property name.

UNC Path: %2

UNC Hardening Configuration: %4

Property Name: %6

Property Value: %7

Guidance:
The specified property name does not match a UNC Hardening property supported on the current version of Windows and will be ignored.

For details on configuring Windows computers to require additional security when accessing specific UNC paths, visit http://support.microsoft.com/kb/3000483.</td></tr>
<tr><td>Microsoft-Windows-NetworkProvider</td><td>1004</td><td>Ignoring UNC Hardening Configuration Property: Unsupported property name.

UNC Path: %2

UNC Hardening Configuration: %4

Property Name: %6

Property Value: &#39;%8&#39;

Guidance:
The specified property name does not match a UNC Hardening property supported on the current version of Windows and will be ignored.

For details on configuring Windows computers to require additional security when accessing specific UNC paths, visit http://support.microsoft.com/kb/3000483.</td></tr>
<tr><td>Microsoft-Windows-NetworkProvider</td><td>1005</td><td>Ignoring UNC Hardening Configuration Property: Unsupported property value.

UNC Path: %2

UNC Hardening Configuration: %4

Property Name: %6

Property Value: &#39;%8&#39;

Guidance:
The specified property name expects a boolean value should be assigned a value of 0 (disabled) or 1 (enabled).

For details on configuring Windows computers to require additional security when accessing specific UNC paths, visit http://support.microsoft.com/kb/3000483.</td></tr>
<tr><td>Microsoft-Windows-NetworkProvider</td><td>1006</td><td>Unable to parse UNC Hardening Configuration Entry: Unknown Error.

UNC Path: %2

UNC Hardening Configuration: %4

Guidance:
The UNC Hardening configuration for the path contains invalid syntax and may be ignored.

For details on configuring Windows computers to require additional security when accessing specific UNC paths, visit http://support.microsoft.com/kb/3000483.</td></tr>
<tr><td>Microsoft-Windows-NetworkProvider</td><td>1007</td><td>Unable to parse UNC Hardening Configuration Entry: Unexpected token.

UNC Path: %2

UNC Hardening Configuration: %4

Expected Token: %5

Found Token: %7

Guidance: The UNC Hardening configuration for the path contains invalid syntax and may be ignored.

For details on configuring Windows computers to require additional security when accessing specific UNC paths, visit http://support.microsoft.com/kb/3000483.</td></tr>
<tr><td>Microsoft-Windows-NetworkProvider</td><td>1008</td><td>Unable to parse UNC Hardening Configuration Entry: Unable to parse integer.

UNC Path: %2

UNC Hardening Configuration: %4

Expected Token: %5

Found Token: %7

Guidance: The UNC Hardening configuration for the path contains invalid syntax and may be ignored. The value found token was parsed as an integer, but was found to contain illegal digits.

For details on configuring Windows computers to require additional security when accessing specific UNC paths, visit http://support.microsoft.com/kb/3000483.</td></tr>
<tr><td>Microsoft-Windows-NetworkProvider</td><td>1009</td><td>Unable to parse UNC Hardening Configuration Entry: Unable to parse string.

UNC Path: %2

UNC Hardening Configuration: %4

Expected Token: %5

Found Token: %7

Guidance: The UNC Hardening configuration for the path contains invalid syntax and may be ignored. The value found token was parsed as an string, but was not terminated or exceeded the maximum allowable string length.

For details on configuring Windows computers to require additional security when accessing specific UNC paths, visit http://support.microsoft.com/kb/3000483.</td></tr>
</table>
