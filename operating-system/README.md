## Table of Content
Directory | Description
------------ | -------------
[`/`](../README.md#scripts) | entry point
[`configs/`](../configs/README.md#configs) | configuration of operating systems
[`deploy/`](../deploy/README.md#deploy) | scripts and files to build firmware binaries
[`deploy/coreboot-rom/`](../deploy/coreboot-rom/README.md#deploy-coreboot-rom) | (work in progress)
[`deploy/mixed-firmware/`](../deploy/mixed-firmware/README.md#deploy-mixed-firmware) | disk image solution
[`keys/`](../keys/README.md#keys) | example certificates and signing keys
[`operating-system/`](README.md#operating-system) | folders including scripts ans files to build reprodu>
[`operating-system/debian/`](debian/README.md#operating-system-debian) | reproducible debian buster
[`operating-system/debian/docker/`](debian/docker/README.md#operating-system-debian-docker) | docker environment
[`stboot/`](../stboot/README.md#stboot) | scripts and files to build stboot bootloader from source
[`stboot/include/`](../stboot/include/README.md#stboot-include) | fieles to be includes into the bootloader's initramfs
[`stconfig/`](../stconfig/README.md#stconfig) | scripts and files to build the bootloader's configuration tool from >

## Operating-System
The operating systems to be used with *System Transparency* need to be build reproducible. See http://docs.system-transparency.org for further information. 

Currently, a reproducible *Debian* system is supported.

### Scripts
#### `create_stconfig.sh`
This script is invoked by `run.sh`. It creates a configuration directory for the *debian* system in `configs/` including a `stconfig.json` configuration file. This can also serve as template for custom configuration directories.

See https://docs.system-transparency.org for further information about `stconfig.json`
