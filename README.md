# NEMESIS Distribution

Public distribution endpoint for the NEMESIS WoW 3.3.5a client suite.

This repository is used for installer/updater channel manifests and release metadata. Versioned binary components are published as GitHub Release assets; the updater verifies component and installed-file SHA-256 hashes before applying changes.

## Channels

- `channels/preview.json` — Preview/testing channel for friends and active client-side retroport validation.
- `channels/stable.json` — Stable channel when a release is explicitly promoted.

Channel manifests are published only when their referenced release assets are actually available. NEMESIS source code is not distributed from this repository.
