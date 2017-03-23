# pacman

<<<<<<< HEAD
> Arch Linux package manager utility

- synchronize and update all packages
 
`pacman -Syyu`

- install a new package

`pacman -S package-name`

- remove a package and its dependencies
 
`pacman -Rs package-name`

- search the package database for a keyword

`pacman -Ss icon theme`

- list installed packages and versions

`pacman -Q`
=======
> Arch Linux package manager utility.

- Synchronize and update all packages:

`pacman -Syu`

- Install a new package:

`pacman -S {{package_name}}`

- Remove a package and its dependencies:

`pacman -Rs {{package_name}}`

- Search the package database for a regular expression or keyword:

`pacman -Ss "{{search_pattern}}"`

- List installed packages and versions:

`pacman -Q`

- List only the explicitly installed packages and versions:

`pacman -Qe`

- Find which package owns a certain file:

`pacman -Qo {{filename}}`

- Empty package cache to free up space:

`pacman -Scc`
>>>>>>> upstream/master
