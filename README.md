# Recon — Laptop Killer OTA Releases

This repository contains **signed OTA release artifacts** for the
Laptop Killer project.

## Structure
releases/ vX.Y.Z/
laptop_killer-X.Y.Z
laptop_killer-X.Y.Z.sha256
laptop_killer-X.Y.Z.sha256.asc

keys/
laptop_killer_ota_pubkey.asc

## Verification

All binaries are verified by:

1. GPG signature on the `.sha256` file
2. SHA-256 checksum of the binary

Field devices must verify both before installation.

## Trust Model

This repository is **public by design**.
Authenticity is guaranteed by the GPG signature, not by repository access.
