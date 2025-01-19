## My Notes
### This is a digital rough book for my notes: Linux

The shell os a command language interpreter.

The default promt for a regular user is simply a dollar sign:
  $

The default prompt for the root user is a pound sign:
  \#

Note: You can also use sudo in order to run a command as a root user<<

### Choosing Your Shell
To find out your default login shell, enter the following commands:

\$ whoami \
\$ grep siphephelo /etc/passwd
siphephelo:x:1000:1000:Siphephelo,,,:/home/siphephelo:/bin/bash

#### Running Commands
\$ date \
Fri 06 Dec 2024 14:51:52 SAST \
\$ pwd - print working directory \
/home/siphephelo/Downloads

## useful commands:
ls --help \
man --help

The help command, help on getting more information about the command. There is another command that is useful, called man command.

man --help \
man touch \
ls man \
new line
man man

##### Absolute Path
/home/siphephelo/../file.txt 

##### Relative Path
./scriptx.sh

another line
