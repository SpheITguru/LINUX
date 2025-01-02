## Moving Around the Filesystem
### Basic Filesystem Commands

cd : Change to another directory\
pwd : Prints the name of the current (or present) working directory\
mkdir : Create a directory\
chmod : Changes the permission on a file or directory\
ls: Lists the contents of a directory

absolute path always starts at the root level, whereas the reelative path starts on the working directory

cd alon, return to your home directory. tilde(~) also represents your home directory.

### Using Metacharacters and Operators
\* Matches any number of characters.\
? Matches any one character.\
[...] Matches any one of the characters between the brackets, which can include a hyphen-separated range of letters or numbers.

### Using file-redirection metacharacters
 < : Directs the contents of a file to the command. less bigfile is the same as less < bigfile.\
 \> : Directs standard output of a command to a file. If the file exists, the content of that file is overwritten.\
 2> : Directs standard error (error messages) to the file.\
 &> : Directs both standard output and standard error to the file.\
 \>> : Directs the output of a command to a file, adding the output to the end of the existing file.

 ### Using brace expansion character
 \$ touch memo{1,2,3,4,5}\
 \$ touch test-{a,b,c}-{x,y,z}\
 $ touch {a..f}{1..5}