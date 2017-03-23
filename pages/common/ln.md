# ln

<<<<<<< HEAD
> Creates links to files and folders

- create a symbolic link to a file or folder

`ln -s {{path/to/original/file}} {{path/to/link}}`

- create a hard link to a file or folder

`ln {{path/to/original/file}} {{path/to/link}}`
=======
> Creates links to files and folders.

- Create a symbolic link to a file (or folder):

`ln -s {{path/to/file}} {{path/to/symlink}}`

- Overwrite an existing symbolic to point to a different file:

`ln -sf {{path/to/new_file}} {{path/to/symlink}}`

- Create a hard link to a file:

`ln {{path/to/file}} {{path/to/hardlink}}`
>>>>>>> upstream/master
