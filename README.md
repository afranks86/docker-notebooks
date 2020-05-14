# JupyterLabs on Eucalytpus

## Mounting
- Copy everything `/home` to `/mnt`
- Edit `/etc/fstab` to set mount point from `/mnt` to `/home`
- `sudo mount /dev/vdb /home` and `sudo umount /mnt`

## Update ubunutu version
`do-release-upgrade`

## Docker Set Up
- https://docs.docker.com/engine/install/ubuntu/

- https://docs.docker.com/engine/install/linux-postinstall/

- Set install directory at /lib/systemd/system/docker.service to somewhere in `/home`, e.g. `ExecStart=/usr/bin/dockerd -g /home/docker -H fd:// --containerd=/run/containerd/containerd.sock`

- https://docs.docker.com/compose/install/


