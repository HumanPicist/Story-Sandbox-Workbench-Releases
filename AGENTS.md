# Distribution repository rules

This repository is the public binary distribution channel for Story Sandbox Workbench.

- Never commit or publish application source code here.
- Only commit release notes, checksums, download instructions, and other distribution metadata.
- Upload DMG files as GitHub Release assets; do not commit them to Git.
- Verify version, architecture, signing/notarization status, file size, and SHA-256 before every upload.
- Keep the private source repository and this public download repository as separate Git histories and separate remotes.
- Never configure this repository as a push remote of the private source working tree.

