## Project Purpose

This repository is a public release-only distribution space for ZCode installers.

## Directory Rules

- Installer binaries are kept locally for publishing, but must not be committed to Git.
- GitHub Releases are the only supported distribution channel for installer binaries.
- Release assets must use stable names, for example `ZCode-3.2.2-win-x64.exe`.
- Release notes must include version, platform, SHA256, and download links.

## Git Rules

- Do not commit `.exe`, archive files, build outputs, secrets, tokens, or credentials.
- Keep commits limited to release metadata, documentation, and operational scripts.
- Use GitHub CLI for release creation and asset uploads.

## Verification

- Before publishing, calculate SHA256 for each release asset.
- After publishing, verify both latest and fixed-version download URLs.
