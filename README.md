# winget-updater

winget-updater is a small Windows tray app by ChillCode that keeps your [winget](https://learn.microsoft.com/windows/package-manager/winget/) packages up to date, along with the packages of Scoop, Chocolatey, npm, Bun, pip, Cargo, .NET tools and PowerShell modules.

- Lists every package with an available update, independent of the system language.
- Updates a single app, a selection or everything, or installs updates on a schedule in the background.
- Apps that are running are not killed: they wait until they are closed.
- Desktop shortcuts created by an update can be removed automatically.
- German and English interface.

## Download

Get the latest installer from the **[Releases page](https://github.com/ChillCodeForge/winget-updater/releases/latest)**. Download `winget-updater_<version>_x64-setup.exe` and run it; it installs for all users and asks for admin rights once. Checksums are in `SHA256SUMS.txt` of each release. Installed versions update themselves.

The installer is not code-signed, so Windows SmartScreen and some antivirus programs may warn about a new version. To check that your download is genuine, compare its checksum with `SHA256SUMS.txt` of the same release:

```powershell
Get-FileHash .\winget-updater_<version>_x64-setup.exe
```

## Source code

This repository only publishes release binaries; it contains no source code and does not accept pull requests.

## Reporting problems

Found a bug or have a suggestion? Open an [issue](https://github.com/ChillCodeForge/winget-updater/issues). Please include the winget-updater version (part of the installer file name), your Windows version, and the steps that lead to the problem.
