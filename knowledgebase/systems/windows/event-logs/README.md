# List of all Windows Event Logs

The files in this folder are generated with this command, the rest is some
regex crunching with `sed`.

```ps1
Get-WinEvent -ListProvider * -ErrorAction SilentlyContinue `
| Select-Object Name -ExpandProperty Events `
| Select-Object Name, Id, Description `
| Group-Object -Property Name `
| ForEach-Object {
	$_.Group | ConvertTo-Html | Out-File ".\$($_.Name).html" -Encoding utf8
}
```
