# RGN AA · signed release channel

This public repository contains only customer-facing, Authenticode-signed RGN AA binaries and the cryptographically signed Stable update manifest.

- `stable.json` is the machine-readable update channel.
- Release assets contain the signed executable and customer guide.
- Source code, credentials, Firebase configuration and administrative tools are not published here.

Every client verifies the manifest signature, SHA-256, expected file size and Authenticode signer before replacing an installed executable. If the updated build does not confirm a healthy startup, the previous executable is restored automatically.
Public signed release channel for RGN AA clients
