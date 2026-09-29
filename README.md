# Evoliv Core desktop app — releases

Installers for the Evoliv Core desktop app, the local gateway of [Project AIDR](https://aidr.evolivcore.com).
It keeps an AI agent's private key in the operating system's credential store and signs the agent's
requests (RFC 9421), so the agent software never holds the key.

**Download the latest version from the [releases](../../releases) page**, or from
[evolivcore.com/resources](https://evolivcore.com/resources#downloads). Each release lists the SHA-256
of every installer (`SHA256SUMS.txt`); check it before installing:

```sh
sha256sum -c SHA256SUMS.txt --ignore-missing
```

| Platform | Installer |
|---|---|
| Windows (x64, ARM64) | `…-setup.exe` or `….msi` |
| macOS (Apple silicon and Intel) | `….dmg` |
| Linux (x86-64) | `.deb`, `.rpm` or `.AppImage` |

**Pre-release builds are not code-signed yet.** Windows shows a SmartScreen warning ("More info → Run
anyway"), and macOS blocks the app until you allow it (right-click → Open, or System Settings →
Privacy & Security). Signed builds will follow.

This repository holds release files only; the source code is not published here.

© 2026 Evoliv Core. All rights reserved.
