# srm

<<<<<<< HEAD
> Securely remove files or directories
> Overwrites the existing data one or multiple. Drop in replacement for rm.

- Removes a file after overwriting (single pass, 7 pass, 35 pass)

`srm -s {{/path/to/file}}`
`srm -m {{/path/to/file}}`
`srm {{/path/to/file}}`

- Scurely remove recursively a directory and all it's subdirectories

`srm -r {{/path/to/folder}}`

- Prompt before every removal

`srm -i {{\*}}`
=======
> Securely remove files or directories.
> Overwrites the existing data one or multiple times. Drop in replacement for rm.

- Remove a file after a single-pass overwriting with random data:

`srm -s {{/path/to/file}}`

- Remove a file after seven passes of overwriting with random data:

`srm -m {{/path/to/file}}`

- Recursively remove a directory and its contents overwriting each file with a single-pass of random data:

`srm -r -s {{/path/to/folder}}`

- Prompt before every removal:

`srm -i {{\*}}`
>>>>>>> upstream/master
