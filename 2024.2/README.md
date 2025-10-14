ironic-fix-2095486.patch        ironic-nfs.patch                ironic-wait-before-insert.patch



## Patches for Ironic release 2024.2

### ironic-nfs.patch
Add support for nfs:// scheme on Redfish virtual media boot

### ironic-wait-before-insert.patch
Check if the virtual media is properly mounted (redfish). Retry on fail.

### ironic-fix-2095486.patch
Do not store `upper_bound` BIOS attributes, fix for https://bugs.launchpad.net/ironic/+bug/2095486

