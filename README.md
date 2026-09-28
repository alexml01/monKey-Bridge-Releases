# MONKey Bridge Releases

Public release repository for **MONKey Bridge** by MEDialogic.

This repository is the distribution endpoint for signed MONKey Bridge software releases. Raspberry Pi installations and other MONKey Bridge systems use it to check for approved updates and download the corresponding release artifacts.

## Purpose

The MONKey Bridge source code and development history are maintained separately. This repository contains only the files and metadata required for software distribution and field updates.

MONKey Bridge installations can use this repository without GitHub credentials. Before an update is installed, the downloaded release is validated using the MONKey Bridge signing and trust mechanism. Public availability of a file alone does not make it a trusted update.

## Release channels

The update architecture supports separate release channels so development, pilot deployments and stable field installations can be updated independently. The currently active development channel is `development`.

## Repository structure

Release metadata is published through the MONKey release catalog. Signed manifests reference the platform-specific artifacts required by each installation, including Raspberry Pi / ARM64 and development systems where applicable.

This repository is intended for automated release distribution. Files should normally be generated and published through the MONKey release process rather than edited manually.

---

MONKey Bridge · MEDialogic