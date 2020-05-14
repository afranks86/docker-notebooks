# JupyterLabs on Eucalytpus

## Mounting
- Copy everything `/home` to `/mnt`
- Edit `/etc/fstab` to set mount point from `/mnt` to `/home`
- `sudo mount /dev/vdb /home` and `sudo umount /mnt`

## Update ubunutu version

## Docker Set Up
- https://docs.docker.com/engine/install/ubuntu/

- https://docs.docker.com/engine/install/linux-postinstall/

- https://docs.docker.com/compose/install/


- Set install directory at /lib/systemd/system/docker.service to somewhere in `/home`
