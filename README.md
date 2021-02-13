Storage Volume Initialise
=========================

[![Actions Status](https://github.com/ome/ansible-role-storage-volume-initialise/workflows/Molecule/badge.svg)](https://github.com/ome/ansible-role-storage-volume-initialise/actions)
[![Ansible Role](https://img.shields.io/ansible/role/41989.svg)](https://galaxy.ansible.com/ome/storage_volume_initialise/)

Formats and mounts a storage partition.

Note this does not create any partitions or storage devices.


Role Variables
--------------

Required variables:

- `storage_volume_initialise_device`: The storage device, e.g. `/dev/vdb1`
- `storage_volume_initialise_mount`: The mount-point for the storage device


Author Information
------------------

ome-devel@lists.openmicroscopy.org.uk
