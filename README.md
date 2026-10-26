# DineTime POS — download

Restaurant billing and KOT software for Windows 10 / 11 (64-bit).

## Download the latest version

**[Download DineTime POS for Windows](https://github.com/gauravgofficial54-dot/dinetime-pos-download/releases/latest/download/DineTime-POS-Setup.exe)**

This link always gives the newest version. The release page lists what is
new, the install guide and the checksum:
[Latest release](https://github.com/gauravgofficial54-dot/dinetime-pos-download/releases/latest).

## Installing

1. Run `DineTime-POS-Setup.exe`.
2. Windows may show **"Windows protected your PC"** — the installer is not
   code-signed yet. Click **More info**, then **Run anyway**.
3. Activate with the licence key you received from DineTime. The software
   does not work without a licence key.

Full steps (updating, backups, the menu from Excel): `INSTALL.md` on the
release page.

## Checking the file

In PowerShell, in the folder you downloaded to:

```
Get-FileHash .\DineTime-POS-Setup.exe -Algorithm SHA256
```

The value must match `SHA256SUMS.txt` on the release page.
