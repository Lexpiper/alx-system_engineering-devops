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
## `BEST="School"`
_
7. A script that creates a new global variable.
## `export BEST="School"`
_
8.  A script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE followed by a new line.
## `echo $((TRUEKNOWLEDGE + 128))`
_
9. A script that prints the result of **POWER** divided by **DIVIDE**, followed by a new line.
## `echo $((POWER / DIVIDE))`
_
10. A script that displays the result of **BREATH** to the power **LOVE**
	- `BREATH` and `LOVE` are environment variables
	- The script should display the result, followed by a new line
## `echo $((BREATH ** LOVE))`
_
11. a script that converts a number from base 2 to base 10..
	- The number in base 2 is stored in the environment variable `BINARY`
	- The script should display the number in base 10, followed by a new line
## `echo $((2#$BINARY))`
