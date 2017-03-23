# zpool

<<<<<<< HEAD
> Manage ZFS pools

- Show the configuration and status of all ZFS zpools

`zpool status [{{poolname}}]`

- Check a ZFS pool for errors (verifies the checksum of EVERY block). Very CPU and disk intensive.

`zpool scrub {{poolname}}`

- List zpools available for import

`zpool import`

- Import a zpool, optionally specifying a new name

`zpool import {{poolname}}`
`zpool import {{poolname}} {{newpoolname}}`

- Export a zpool (unmount all filesystems)

`zpool export {{poolname}}`

- Show the history of all pool operations

`zpool histrory {{poolname}}`

- Create a mirrored pool. 

`zpool create {{poolname}} mirror {{disk1}} {{disk2}}`
`zpool create {{poolname}} mirror {{disk1}} {{disk2}} mirror {{disk3}} {{disk4}}`
=======
> Manage ZFS pools.

- Show the configuration and status of all ZFS zpools:

`zpool status`

- Check a ZFS pool for errors (verifies the checksum of EVERY block). Very CPU and disk intensive:

`zpool scrub {{pool_name}}`

- List zpools available for import:

`zpool import`

- Import a zpool:

`zpool import {{pool_name}}`

- Export a zpool (unmount all filesystems):

`zpool export {{pool_name}}`

- Show the history of all pool operations:

`zpool histrory {{pool_name}}`

- Create a mirrored pool:

`zpool create {{pool_name}} mirror {{disk1}} {{disk2}} mirror {{disk3}} {{disk4}}`
>>>>>>> upstream/master
