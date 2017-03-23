# alias

<<<<<<< HEAD
> Creates an alias for a word when used 
> as the first word of a command

- creating a generic alias

`alias {{word}}="{{command}}"`

- remove an aliased command

`unalias {{word}}`

- full list of aliased words

`alias -p`

- turning rm an interative command

`alias {{rm}}="{{rm -i}}"`

- overriding la as ls -a

`alias {{la}}="{{ls -a}}"`
=======
> Creates aliases -- words that are replaced by a command string.
> Aliases expire with the current shell session, unless they're defined in the shell's configuration file, e.g. `~/.bashrc`.

- Create a generic alias:

`alias {{word}}="{{command}}"`

- View the command associated to a given alias:

`alias {{word}}`

- Remove an aliased command:

`unalias {{word}}`

- List all aliased words:

`alias -p`

- Turn rm into an interactive command:

`alias {{rm}}="{{rm -i}}"`

- Create `la` as a shortcut for `ls -a`:

`alias {{la}}="{{ls -a}}"`
>>>>>>> upstream/master
