# md5

<<<<<<< HEAD
> Calculate MD5 cryptographic checksums

- Calculate the MD5 checksum for file(s) or files in a directory, one checksum per file

`md5 {{filename1}}`
`md5 {{filename1}} {{filename2}}`
`md5 {{directory/\*}}`

- Output only the md5 checksum (no filename)

`md5 -q {{filename}}`
=======
> Calculate MD5 cryptographic checksums.

- Calculate the MD5 checksum for a file:

`md5 {{filename}}`

- Calculate MD5 checksums for multiple files:

`md5 {{filename1}} {{filename2}}`

- Output only the md5 checksum (no filename):

`md5 -q {{filename}}`

- Print a checksum of the given string:

`md5 -s {{string}}`
>>>>>>> upstream/master
