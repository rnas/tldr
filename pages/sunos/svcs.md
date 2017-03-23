# svcs

<<<<<<< HEAD
> List information about running services

- list all running services

`svcs`

- list services that are not running

`svcs -vx`

- list information about a service

`svcs apache`

- show location of service log file

`svcs -L apache`

- display end of a service log file
=======
> List information about running services.

- List all running services:

`svcs`

- List services that are not running:

`svcs -vx`

- List information about a service:

`svcs apache`

- Show location of service log file:

`svcs -L apache`

- Display end of a service log file:
>>>>>>> upstream/master

`tail $(svcs -L apache)`
