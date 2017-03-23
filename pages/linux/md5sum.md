# md5sum

<<<<<<< HEAD
> Calculate MD5 cryptographic checksums

- Calculate the MD5 checksum for file(s) or files in a directory, one checksum per file

`md5sum {{filename1}}`
`md5sum {{filename1}} {{filename2}}`
`md5sum {{directory/\*}}`

- Read a file of MD5SUMs and verify all files have matching checksums
=======
> Calculate MD5 cryptographic checksums.

- Calculate the MD5 checksum for a file:

`md5sum {{filename1}}`

- Calculate MD5 checksums for multiple files:

`md5sum {{filename1}} {{filename2}}`

- Read a file of MD5SUMs and verify all files have matching checksums:
>>>>>>> upstream/master

`md5sum -c {{filename.md5}}`
