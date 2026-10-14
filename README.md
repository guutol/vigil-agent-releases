# Vigil Agent downloads

[Português](README.pt-BR.md) · **English**

Official public binary downloads for [Vigil Trophies](https://vigiltrophies.com), an achievement tracker for PC ports and emulators.

**Current beta:** [v0.1.0-beta.5](https://github.com/guutol/vigil-agent-releases/releases/tag/v0.1.0-beta.5). Downloads do not require a GitHub account.

- Windows tray app: `vigil-agent-tray.exe`.
- Windows CLI: `vigil-agent-windows-amd64.exe`.
- Linux / Steam Deck CLI: `vigil-agent-linux-amd64`.
- Linux ARM64 CLI: `vigil-agent-linux-arm64`.

Download `SHA256SUMS.txt` alongside the executable and compare its SHA-256 before running it. Windows PowerShell: `Get-FileHash .\vigil-agent-tray.exe -Algorithm SHA256`. Linux: `sha256sum --ignore-missing -c SHA256SUMS.txt`.

Create an account at https://vigiltrophies.com. On Windows, open the tray app and choose **Link this PC**, then approve the code in your browser. Choose which game folders to watch. The agent reads achievements and queues them when offline. Installation details: https://vigiltrophies.com/download.

This repository contains distribution documentation and release files, not the application source. Source remains in a separate private repository. The binaries are licensed under MIT; see [LICENSE](LICENSE).

The beta is unsigned, has no automatic updates, and its original build has no GitHub provenance attestation. Publishing a copy here does not create a build attestation. These are byte-for-byte copies of the original GitHub Actions release, not new builds. See each release's notes for the original source commit and checksum verification.

To update, exit the running agent, replace its executable, then reopen it. Keep its path unchanged if it starts with Windows. Your local account link, preferences, sources and queued achievements remain in the agent's configuration directory.
