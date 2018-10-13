# Ansible Playbooks to Build Linux From Scratch
Tested on Xubuntu 18.04 LTS.

# Instructions
Run `main.yml` on the build host.

# Version
This script builds the [8.3-systemd](http://www.linuxfromscratch.org/lfs/view/8.3-systemd/) version of LFS.

# Progress
- [x] Configure host build system, including installing dependencies and patching host system quirks
- [x] Partition, format, and mount the future LFS disk
- [x] Download and verify the LFS packages and patches
- [x] Create the LFS user
- [ ] Build the temporary root
- [ ] Install the base system
- [ ] Configure the system
- [ ] Make the system bootable