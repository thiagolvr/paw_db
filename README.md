# Paw workspace

This folder is written by Paw, a native macOS API client.

- `collections.json` — workspaces, collections, folders and requests
- `environments.json` — per-collection variables
- `auth-presets.json` — reusable authentication configurations
- `settings.json` — app settings
- `paw-sync.json` — sync manifest (device, timestamp, content hash)

Secrets are never uploaded. They stay in the macOS Keychain on each Mac.
