# apt-get

<<<<<<< HEAD
> Debian and Ubuntu package management utility

- Synchronize list of packages and versions available. This should be run first, before running subsequent apt-get commands.
 
`apt-get update`

- install a new package

`apt-get install {{package}}`


- remove a package
 
`apt-get remove {{package}}`

- Upgrade installed packages to newest available versions

`apt-get upgrade`

- Upgrade installed packages (like `apt-get upgrade`) including removing obsolete packages and installing additional packages to meet new package dependencies. 
=======
> Debian and Ubuntu package management utility.

- Synchronize list of packages and versions available. This should be run first, before running subsequent apt-get commands:

`apt-get update`

- Install a new package:

`apt-get install {{package}}`

- Remove a package:

`apt-get remove {{package}}`

- Upgrade installed packages to newest available versions:

`apt-get upgrade`

- Remove no longer needed packages:

`apt-get autoremove`

- Upgrade installed packages (like "upgrade"), but remove obsolete packages and install additional packages to meet new dependencies:
>>>>>>> upstream/master

`apt-get dist-upgrade`
