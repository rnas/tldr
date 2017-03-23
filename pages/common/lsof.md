# lsof

<<<<<<< HEAD
> Lists open files and the corresponding processes

- find the processes that have a given file open

`lsof {{/path/to/file}}`

- find the process that opened a local internet port

`lsof -i :{{8080}}`

- only output the process PID (e.g. to pipe into kill)

`lsof -t {{/path/to/file}} | xargs kill -9`
=======
> Lists open files and the corresponding processes.
> Note: In most cases, you need root privilege (or use sudo) because you want to list files opened by others.

- Find the processes that have a given file open:

`lsof {{/path/to/file}}`

- Find the process that opened a local internet port:

`lsof -i :{{port}}`

- Only output the process PID:

`lsof -t {{/path/to/file}}`

- List files opened by the given user:

`lsof -u {{username}}`

- List files opened by the given command or process:

`lsof -c {{process_or_command_name}}`

- List files opened by the given PID:

`lsof -p {{PID}}`
>>>>>>> upstream/master
