<p align="center">
  <img src="https://glub-corporation.github.io/glub-browser-docs/favicon.png" width="112" alt="Glub Browser icon">
</p>

<h1 align="center">Glub Browser</h1>

<p align="center">
  <strong>Keep the page. Keep the path.</strong><br>
  Official Windows preview downloads for the keyboard-first spatial browser.
</p>

<p align="center">
  <a href="https://github.com/Glub-Corporation/glub-browser-releases/releases">Download Glub</a>
  &nbsp;&middot;&nbsp;
  <a href="https://glub-corporation.github.io/glub-browser-docs/">Read the documentation</a>
</p>

> [!WARNING]
> Glub Browser is an early Windows x64 preview. The installer is not yet
> code-signed, so Windows SmartScreen may identify the publisher as unknown.
> Download Glub only from this repository and verify the checksum before running
> it.

## Install

1. Open the [Releases page](https://github.com/Glub-Corporation/glub-browser-releases/releases).
2. Choose the newest preview.
3. Download `Glub-Browser-Setup-<version>-x64.exe` and `SHA256SUMS.txt`.
4. Verify the installer in PowerShell:

```powershell
Get-FileHash .\Glub-Browser-Setup-<version>-x64.exe -Algorithm SHA256
```

Compare the reported hash with the installer entry in `SHA256SUMS.txt`. If the
values differ, do not run the file.

After verification, run the installer. If SmartScreen appears, confirm the
download source and checksum before choosing **More info** and **Run anyway**.

## Learn Glub

The [Glub Browser documentation](https://glub-corporation.github.io/glub-browser-docs/)
explains:

- spatial page tiles and directional browsing;
- Workspaces and Stash;
- Open Page Control and the transit-style History Map;
- downloads, site controls, passwords, privacy, and updates; and
- the complete keyboard command reference.

## Repository purpose

This public repository distributes installers, updater metadata, checksums, and
release notes. The Glub Browser application source is maintained in a separate
private repository. The documentation source is public at
[`Glub-Corporation/glub-browser-docs`](https://github.com/Glub-Corporation/glub-browser-docs).
