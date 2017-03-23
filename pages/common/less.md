# less

<<<<<<< HEAD
> Opens a file for reading
> Allows movement and search
> Doesn't read the entire file (suitable for logs)

- open a file

`less {{source_file}}`

- page up / down

`d (next), D (previous)`

- go to start / end of file

`g (start), G (end)`

- search for a string

`/{{something}}   then   n (next), N (previous)`

- exit
=======
> Open a file for interactive reading, allowing scrolling and search.

- Open a file:

`less {{source_file}}`

- Page down / up:

`<Space> (down), b (up)`

- Go to end / start of file:

`G (end), g (start)`

- Forward search for a string (press `n`/`N` to go to next/previous match):

`/{{something}}`

- Backward search for a string (press `n`/`N` to go to next/previous match):

`?{{something}}`

- Open the current file in an editor:

`v`

- Exit:
>>>>>>> upstream/master

`q`
