## Table of Content
Directory | Description
------------ | -------------
[`/`](../../README.md#scripts) | entry point
[`configs/`](../../configs/README.md#configs) | configuration of operating systems
[`deploy/`](../../deploy/README.md#deploy) | scripts and files to build firmware binaries
[`deploy/coreboot-rom/`](../../deploy/coreboot-rom/README.md#deploy-coreboot-rom) | (work in progress)
[`deploy/mixed-firmware/`](../../deploy/mixed-firmware/README.md#deploy-mixed-firmware) | disk image solution
[`keys/`](../../keys/README.md#keys) | example certificates and signing keys
[`operating-system/`](../../operating-system/README.md#operating-system) | folders including scripts ans files to build reprodu>
[`operating-system/debian/`](../../operating-system/debian/README.md#operating-system-debian) | reproducible debian buster
[`operating-system/debian/docker/`](../../operating-system/debian/docker/README.md#operating-system-debian-docker) | docker environment
[`stboot/`](../README.md#stboot) | scripts and files to build stboot bootloader from source
[`stboot/include/`](README.md#stboot-include) | fieles to be includes into the bootloader's initramfs
[`stconfig/`](../../stconfig/README.md#stconfig) | scripts and files to build the bootloader's configuration tool from >

## Stboot Include
#### `LetsEncrypt_Authority_X3_signed_by_X1.pem`
Certificate to establish a HTTPS connection to the provisioning server.

#### `netsetup.elv`
Elvish shell script to be used for debugging purposes.
