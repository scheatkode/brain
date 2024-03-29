<h1 align="center">Windows System Repair</h1>

<p align="center">
  <i>Repairing a broken Windows system using SFC and DISM</i>
</p>

This is a quick and dirty way for automated Windows systems repairs. Useful
for common and/or darker issues. Or simply when there isn't enough time to
deal with it.

The following commands need to be run with *administrative privileges*.

## Deployment Image Servicing and Management

On Windows 10, Deployment Image Servicing and Management (DISM) is a tool
designed for network administrators to prepare, modify, and repair system
images, including the Windows Recovery Environment, Windows Setup, and Windows
PE (WinPE). However, anyone can also use the tool to fix common problems with
the hidden recovery image on the computer.

Usually, when the device is experiencing performance issues, doesn't start
correctly, or there are issues troubleshooting errors, the System File Checker
tool can be used to scan, detect, and replace corrupted or missing system
files using the locally available recovery image.

However, if the replacement files inside the Windows 10 image are damaged in
any way, the SFC tool won't work. In this particular situation, the DISM tool
can be used to scan and repair the `install.wim` image, which can then be used
with SFC to repair the installation.

### CheckHealth

The *CheckHealth* option can be used with DISM to quickly determine if there
are any corruptions inside the local image, but the option won't perform any
repairs.

```bat
DISM /Online /Cleanup-Image /CheckHealth
```

The command will run and verify if there is any data corruption that needs
fixing.

### ScanHealth

The **ScanHealth** option performs a more advanced scan to determine if the
Windows 10 image has any problems.

```bat
DISM /Online /Cleanup-Image /ScanHealth
```

The advanced scan will take several minutes to determine if the local image
needs repairing.

### RestoreHealth

DISM, with the **RestoreHealth** option, will run an advanced scan and repair
any problems automatically.

```bat
DISM /Online /Cleanup-Image /RestoreHealth
```

The DISM tool will connect to the Windows Update servers to download and
replace any damaged files in the local image for Windows 10 as necessary.

### Using a local .wim

The DISM tool is unlikely to run into issues, but in the rare case that
Windows Update is causing problems getting the replacement files or there is
no internet connection, an alternative source is needed to repair the files
using another image with the Source option.

Before a different source is specified, an install.wim or install.esd file is
needed from another computer, bootable installation media, or ISO file. Also,
it's important that the source of the known good files matches the same
version, edition, and language of Windows 10 that is used on the problematic
computer.

```bat
DISM /Online /Cleanup-Image /RestoreHealth /Source:<wherever>\install.wim
```

The command will scan and repair any issues using the specified install.wim
image.

## System File Checker

The instructions outlined above to use DISM will repair any issues with the
local hidden image, but they won't fix any problems with the actual
installation of Windows 10. However, now that a healthy image is available,
the System File Checker can be used to repair common issues preventing the
device from running correctly.

```bat
SFC /scannow
```

If errors are found, the command might need to be ran about three times to
make sure that everything is fixed correctly.

The System File Checker will scan the device and repair any system files using
the good files from the local image to restore the health of Windows 10.

### Viewing the logs

To see the details of a System File Checker stored in the CBS.Log file,
a human-readable, filtered copy is needed.

```bat
findstr /c:"[SR]" %windir%\Logs\CBS\CBS.log > "%userprofile%\Desktop\sfc.txt"
```

The resulting file will contain all the details of the scanned system files
and information for files that couldn't be repaired.
