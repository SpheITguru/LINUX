### This is file 1 Note
In this book files, is me trying to organise my notes.

This is not a structured book, but for me to keep my notes organised.

Maybe later I will restructure, differently.

##### Some commands:
fg: to bring a command running in the background in the foreground

##### Linux shortcuts
1. Up Arrow key: This will display the most recent command from your shell history. 
2. Ctrl+A: This moves the cursor to the beginning of the command line.
3. etc 

#### Connecting and Expanding Commands
A truly powerful feature of the shell is the capability to redirect the input and output of commands to and from other commands and files.

##### Metacharacter
A metacharacter is a typed character that has special meaning to the shee for connecting commands or requesting expansion.

1. ( | ): pipe
2. ( & ): ampersand
3. ( ; ): semicolon
4. ( () ): left, right parenthesis
5. ( <> ): less, greater than sign

*** 
### Piping 
The pipe ( | ) metacharacter coneects the output from one command to the input of another command.

$ cat /etc/passwd | sort | less

### Sequential commands
Sometimes, you may want a sequence of commands to run, with one command to completing before the next command begins.

$ data ; troff -me verylargedocument | lp ; date

### Background commands
Some commands can take a while to complete. Sometimes, you may not want to tie up your shell waiting for a command to finish. 

In those cases, you can have the commands run in the background by using the ampersand ( & ).

### Expanding commands
With command substitution, you can have the output of a command interpreted by the shell instead of by the command itself.

\$ nano $(find /home | grep xyzzy)

#### Expanding arithmetic expressions
Sometimes, you want to pass arithmetics results to a command using $[expression]

$ echo "I am $[2019 - 1957] years old."

#### Everything that starts with $ : communicate ti the shell
$[Expression]