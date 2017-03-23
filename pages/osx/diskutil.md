# diskutil

<<<<<<< HEAD
> Utility to manage local disks and volumes

- List all currently available disks, partitions and mounted volumes.

`diskutil list`

- Repair permissions on a volume

`diskutil repairPermissions {{/Volumes/Name}}`

- Repair the file system data structures of a volume

`diskutil repairVolume {{/dev/diskX}}`

- Unmount a volume

`diskutil unmountDisk {{/dev/diskX}}`

- Eject a CD/DVD (unmount first)
=======
> Utility to manage local disks and volumes.

- List all currently available disks, partitions and mounted volumes:

`diskutil list`

- Repair the file system data structures of a volume:

`diskutil repairVolume {{/dev/diskX}}`

- Unmount a volume:

`diskutil unmountDisk {{/dev/diskX}}`

- Eject a CD/DVD (unmount first):
>>>>>>> upstream/master

`diskutil eject {{/dev/disk1}}`
