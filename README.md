# Pulse — Windows releases

Download **Pulse.exe** from [the latest release](https://github.com/feudracode/r/releases/latest).

The launcher checks for updates at startup. Update metadata is signed with ECDSA P-256; the launcher checks the signature, version, file size and SHA-256 before installation. If the update check fails, the installed version remains available.

Each release contains `Pulse.exe`, `update.txt`, and `update.sig`. These update signatures are separate from Windows Authenticode code signing.
