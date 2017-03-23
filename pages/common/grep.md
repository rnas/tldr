# grep

<<<<<<< HEAD
> Matches patterns in input text
> Supports simple patterns and regular expressions

- search for an exact string
 
`grep {{something}} {{file_path}}`

- search recursively in current directory for an exact string

`grep -r {{something}} .`

- use a regex

`grep -e {{^regex$}} {{file_path}}`

- see 3 lines of context

`grep -C 3 {{something}} {{file_path}}`

- print the count of matches instead of the matching text 

`grep -c {{something}} {{file_path}}`

- use the standard input instead of a file

`cat {{file_path}} | grep {{something}}`
=======
> Matches patterns in input text.
> Supports simple patterns and regular expressions.

- Search for an exact string:

`grep {{search_string}} {{path/to/file}}`

- Search in case-insensitive mode:

`grep -i {{search_string}} {{path/to/file}}`

- Search recursively (ignoring non-text files) in current directory for an exact string:

`grep -rI {{search_string}} .`

- Use extended regular expressions (supporting `?`, `+`, `{}`, `()` and `|`):

`grep -E {{^regex$}} {{path/to/file}}`

- Print 3 lines of [C]ontext around, [B]efore, or [A]fter each match:

`grep -{{C|B|A}} 3 {{search_string}} {{path/to/file}}`

- Print the count of matches instead of the matching text:

`grep -c {{search_string}} {{path/to/file}}`

- Print line number for each match:

`grep -n {{search_string}} {{path/to/file}}`

- Print file names with matches:

`grep -l {{search_string}} {{path/to/file}}`

- Use the standard input instead of a file:

`cat {{path/to/file}} | grep {{search_string}}`

- Invert match for excluding specific strings:

`grep -v {{search_string}}`
>>>>>>> upstream/master
