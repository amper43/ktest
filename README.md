# ktest

# Dependencies

Required packages:
- socat
- xmlstarlet
- virsh
- qemu

To install on SLES 15 SP1 run following:
```bash
zypper in socat xmlstarlet qemu
zypper addrepo https://download.opensuse.org/repositories/Virtualization/SLE_15_SP1/Virtualization.repo
zypper refresh
zypper install libvirt
```
