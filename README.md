# prano-updates

Public APK update channel for Prano.

## Post-cutover role
Project Vela Phase 1 cutover is already verified in the unified root repo.

This repo is retained externally on purpose as Prano's public update-distribution surface.
It is **not** the canonical source of truth for Vela runtime architecture or unified-root reconstruction planning.

For canonical Vela runtime/cutover truth, use unified-root `Project Vela/`.
For Prano app implementation truth, use the `Prano/` repo.

Files:
- `latest.json` — app-readable update manifest
- `apk/` — publicly downloadable APK artifacts
