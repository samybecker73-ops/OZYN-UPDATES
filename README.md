# OZYN Updates

Public distribution repository for official OZYN releases.

## Purpose

This repository hosts public release notes and downloadable installers for OZYN.
The application source code remains in the private repository: `samybecker73-ops/OZYN`.

## Release conventions

- Use semantic version tags: `vMAJOR.MINOR.PATCH`.
- Publish stable releases through GitHub Releases.
- Windows installer asset naming: `OZYN-Setup-X.Y.Z.exe`.
- Attach a SHA-256 checksum file named `OZYN-Setup-X.Y.Z.exe.sha256`.
- Include release notes describing changes, fixes, known issues, and minimum requirements.
- Do not publish a release until the installer has been tested and its checksum verified.

## Important

The initial repository setup does not contain an installer yet. The first downloadable release will be published only after a working OZYN build exists and has been tested.

OZYN runs its language model locally on the user's computer. This repository distributes application updates; it is not an AI inference service.

## Related project

- Private source repository: https://github.com/samybecker73-ops/OZYN
- KAVIO website: https://kavio.pages.dev/
