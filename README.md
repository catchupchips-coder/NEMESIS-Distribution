# NEMESIS Distribution

Public distribution endpoint for the NEMESIS WoW 3.3.5a client suite.

## Download

**[Download NEMESIS Installer — Preview](https://github.com/catchupchips-coder/NEMESIS-Distribution/releases/download/preview-2026.09.15.1/NEMESIS-Installer-PreviewCandidate-win-x64.zip)**

Windows x64. Extract the ZIP and run `NEMESIS-Installer.exe`. The installer handles the NEMESIS client files, verifies downloads, and points the client at the current Preview channel.

> Preview is the current friends/testers channel. Stable is not live yet.

## Distribution

This repository is used for installer/updater channel manifests and release metadata. Versioned binary components are published as GitHub Release assets; the updater verifies component and installed-file SHA-256 hashes before applying changes.

## Channels

- `channels/preview.json` — Preview/testing channel for friends and active client-side retroport validation.
- `channels/stable.json` — Stable channel when a release is explicitly promoted.

Channel manifests are published only when their referenced release assets are actually available. NEMESIS source code is not distributed from this repository.
