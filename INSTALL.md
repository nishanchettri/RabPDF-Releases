# Install or run RabPDF on Windows

Download only from this repository's Releases page.

## Portable EXE

Download RabPDF-Windows-1.5.7.exe and double-click it. There is no installation
wizard and no need to install Python or supporting packages.

## FastStart ZIP

Download RabPDF-Windows-1.5.7-FastStart.zip. Right-click and select Extract All.
Open the extracted folder and run RabPDF.exe. Keep _internal alongside the EXE.
Do not run directly inside the ZIP or copy only the EXE out of this edition.

Close any older RabPDF window before opening the new version. The app's
single-instance protection otherwise brings the already-running app forward.
If updating FastStart, extract into a new folder instead of mixing versions.

## Security and checksums

These builds are unsigned and Windows may show a SmartScreen warning. Do not
disable antivirus or security protection. If unsure, stop and contact support.
Checksums verify bytes; they do not authenticate the publisher or prove safety.

In PowerShell, compare the hash against SHA256SUMS.txt:

```powershell
Get-FileHash .\RabPDF-Windows-1.5.7.exe -Algorithm SHA256
```

Test with disposable copies before processing important documents. Compression
estimates vary; AI upscaling estimates missing detail rather than recovering
guaranteed original information.

To remove a portable edition, close it and delete its downloaded/extracted
files. Local language settings may remain in %LOCALAPPDATA%\RabPDF\settings.json.
Do not delete your own exported documents.

Support: ciao@monkeywithbrain.in
