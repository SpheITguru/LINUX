## Working with Text Files

#### Editing Files with Vim and Vi

#### Finding Files
locate (to find commands by name)\
find (to find files based on lots of different attributes)\
grep (to search within text files to find thens in the files that contains search text).

##### Using locate to find files by name
locate "file"

##### Searching for files with find
find command is the best when searching with attributes.\
After files are found, you can act on those files as well (using the -exec or -okay option) by running any commands you want on the them.

-name and -iname options to find files by names.

##### Finding files by size
The -size option enables you to search for files that are exactly, smaller than, or larger than a selected size.

\$ find /usr/share/ -size +10M\
\$ find $HOME/Downloads -size +50M -size -5G -exec du -sh {} \;

##### Finding files by user
\$ find /home -user siphephelo -ls

##### Finding files by permission
-perm option\
\$ find /usr/bin -perm 755 -ls

##### Finding files by date and time
\$ find /etc/ -mmin -60\
see what has changed in the past 60 minutes.

\$ find /bin -ctime -3\
check if there is any change happened in the last 3 days

\$ find /var/ftp -atime +300\
files that have not been accessed in more than 300 days.