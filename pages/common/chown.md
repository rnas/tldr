# chown

<<<<<<< HEAD
> Change the owning user/group of the specified files

- change the user of a file

`chown {{user}} {{path/to/file}}`

- change the user and group of a file
 
`chown {{user}}:{{group}} {{path/to/file}}`

- recursively change the owner of an entire folder

`chown -R {{user}} {{path/to/folder}}`

- change the owner of a symbolic link
 
`chown -h {{user}} {{path/to/symlink}}`
=======
> Change user and group ownership of files and folders.

- Change the owner user of a file/folder:

`chown {{user}} {{path/to/file}}`

- Change the owner user and group of a file/folder:

`chown {{user}}:{{group}} {{path/to/file}}`

- Recursively change the owner of a folder and its contents:

`chown -R {{user}} {{path/to/folder}}`

- Change the owner of a symbolic link:

`chown -h {{user}} {{path/to/symlink}}`

- Change the owner of a file/folder to match a reference file:

`chown --reference={{path/to/reference_file}} {{path/to/file}}`
>>>>>>> upstream/master
