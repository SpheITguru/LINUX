## Writing Simple Shell Scripts
A shell scripts is a group of commands, functions, variables, or just about anything else you can use from a shell.

you can write a script in two ways: 
plaintext and run it by using bash.

bash myscript

secondly, you can write it using the interpreter placed in the first line of the script preceded by #! (as in #!/bin/bash)

(#) The pound sign prefaces comments that can take up an entire line.

You can use set -x near the beginning of the script to display each command that is executed or launch your scripts using.\
$ bash -x myscript

#### Understanding shell variables
Variable names within shell scripts are case sensitive and can be defined in the following manner:\
NAME=value

The first part of a variable is the variable name, and the second part is the value set for that name. Make sure that the NAME and value touch the qual sign, without any spaces.

Variables can also contain the output of a command or command sequence.

continuing with the script
adding new line