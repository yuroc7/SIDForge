# Verify an official SID Forge download

Download SID Forge only from:

`https://sidforge.pp.ua/download/sid-forge/stable`

The official release record publishes the file name, version, size, and SHA-256 checksum. Compare that checksum with the downloaded file before running it.

On Windows PowerShell:

```powershell
Get-FileHash "$env:USERPROFILE\Downloads\SIDForge.exe" -Algorithm SHA256
```

The displayed hash must match the SHA-256 value shown by the official SID Forge release page. If the file name, size, or hash differs, delete the file and download it again from the official website.

Do not download SID Forge from file-sharing mirrors, shortened links, chat attachments, or unofficial software bundles.
