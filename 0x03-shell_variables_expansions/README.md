# Shell, init files, variables and expansions
## Scripts and their command


0.  A script that creates an alias. =  with value `ls` and name `rm *`
##  `alias ls="rm *" `
_
1. A script that prints hello user where user is the current Linux user
## `export PATH=$PATH:/action `

2. Add `/action` to the `PATH` `/action` should be the last directory the shell looks into when looking for a program.
## `export PATH=$PATH:/action`

3.  A script that counts the number of directories in the `PATH`
## `echo $PATH | tr ':' '\n' | wc -w`
_
4.  A script that lists environment variables.
## ` printenv | less`
_
5. A script that lists all local variables and environment variables, and functions.
## `set`
_
6. A script that creates a new local variable.

- Name: `BEST`
- Value: `School`
