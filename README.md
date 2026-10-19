# Atom Code releases

Downloads for Atom Code: the desktop app and the CLI.
Every file is checked against `SHA256SUMS` in its release.

## Desktop app

```
# Windows (PowerShell)
irm https://github.com/THCO-Labs/atomcode-releases/releases/latest/download/install-desktop.ps1 | iex

# macOS / Linux
curl -fsSL https://github.com/THCO-Labs/atomcode-releases/releases/latest/download/install-desktop.sh | sh
```

Or download the installer from the [latest release](https://github.com/THCO-Labs/atomcode-releases/releases/latest).

## CLI

```
# Windows (PowerShell)
irm https://github.com/THCO-Labs/atomcode-releases/releases/latest/download/install.ps1 | iex

# macOS / Linux
curl -fsSL https://github.com/THCO-Labs/atomcode-releases/releases/latest/download/install.sh | sh

# Python
pipx install atomcode-cli
```

Then sign in once with `atomcode access login`; the desktop app and the VS Code extension share that sign-in.

Desktop releases are tagged `v<version>`; CLI and engine releases `engine-v<version>` (pre-releases).
This repository holds release files only.
