# scp

<<<<<<< HEAD
> Copies files between hosts on a network
> Works over a secure connection (SSH)

- upload a file, or upload and rename a file

`scp {{/local/file.txt}} {{10.0.0.1}}:{{/remote/path/}}`
`scp {{/local/file.txt}} {{10.0.0.1}}:{{/remote/path/newname.txt}}`

- download a file

`scp {{10.0.0.1}}:{{/remote/path/file.txt}} {{/local/folder}}`

- upload or download a directory

`scp -r {{/local/folder}} {{10.0.0.1}}:{{/remote/path/}}`
`scp -r {{10.0.0.1}}:{{/remote/path}} {{/local/folder}}`

- specify username on host

`scp {{/local/file.txt}} {{my_user}}@{{10.0.0.1}}:{{/remote/path}}`

- copy a file from one host to another

`scp {{10.0.0.1}}:{{/remote/path/file.txt}} {{20.0.0.2}}:{{/other/remote/path}}`
=======
> Secure copy.
> Copy files between hosts using Secure Copy Protocol over SSH.

- Copy a local file to a remote host:

`scp {{path/to/local_file}} {{remote_host}}:{{path/to/remote_file}}`

- Copy a file from a remote host to a local folder:

`scp {{remote_host}}:{{path/to/remote_file}} {{path/to/local_dir}}`

- Recursively copy the contents of a directory on a remote host to a local directory:

`scp -r {{path/to/local_dir}} {{remote_host}}:{{path/to/remote_dir}}`

- Copy a file between two remote hosts transferring through the local host:

`scp -3 {{host1}}:{{path/to/remote_file}} {{host2}}:{{path/to/remote_dir}}`

- Use a specific username when connecting to the remote host:

`scp {{path/to/local_file}} {{remote_username}}@{{remote_host}}:{{path/to/remote_dir}}`

- Use a specific ssh private key for authentication with the remote host:

`scp -i {{~/.ssh/private_key}} {{local_file}} {{remote_host}}:{{/path/remote_file}}`
>>>>>>> upstream/master
