# ls

<<<<<<< HEAD
> List directory contents

- List all files, even hidden

`ls -a`

- Sorting by size

`ls -s`

- List all files with their rights, groups, owner

`ls -ls`

- List all files with a prefix/suffix

`ls {{prefix}}*` or `ls *{{suffix}}`

- Sort files by time

`-t` for last modified
`-U` for date of creation
`-r` reverses the list
`ls -tr`
=======
> List directory contents.

- List files one per line:

`ls -1`

- List all files, including hidden files:

`ls -a`

- Long format list (permissions, ownership, size and modification date) of all files:

`ls -la`

- Long format list with size displayed using human readable units (KB, MB, GB):

`ls -lh`

- Long format list sorted by size (descending):

`ls -lS`

- Long format list of all files, sorted by modification date (oldest first):

`ls -ltr`
>>>>>>> upstream/master
