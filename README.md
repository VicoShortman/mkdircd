# mkdircd
Linux mkdir and cd commands combined

## Installation
Download *mkdircd* file, make sure it is executable (chmod -x mkdircd) and move it in /usr/bin or where you need it.

## Usage
Unfortunately you can't just use it right away. For the cd command to work, *mkdircd* needs the source of your current terminal.
This can be done by using mkdircd together with the source command:
`source mkdircd mydir`
As alternative you can replace source wit just '.', witch executes the same source command as before:
`. mkdircd mydir`

## Alias
For me, both methods, requiring a prefixed command, are too cluncky. I just want mkdircd like mkdir and cd.
Therefore you can just create an alias:
`alias mkdircd="source mkdircd"`
