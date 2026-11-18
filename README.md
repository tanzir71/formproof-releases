# FormProof releases

Public installer downloads and checksums for the FormProof desktop app.

This repository is a distribution channel only. It contains no application source code; the FormProof source remains private.

## Download

- Download page: https://www.trips.quest/formproof
- Latest release: [FormProof 0.1.0 Preview](https://github.com/tanzir71/formproof-releases/releases/tag/formproof-v0.1.0-preview) (pre-release)

Installers and their SHA-256 checksums are attached to each release on the [Releases page](https://github.com/tanzir71/formproof-releases/releases).

## Verify before installing

Preview builds are not backed by a commercial Windows code-signing certificate or Apple notarization, so your operating system may warn you when you open them. Compare the installer's SHA-256 checksum with the one published alongside the release first:

```bash
# macOS / Linux
shasum -a 256 <installer-file>
```

```powershell
# Windows
Get-FileHash <installer-file> -Algorithm SHA256
```
