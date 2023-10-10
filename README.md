# Önemli Linux Komutları

### File Commands
#### File Administration
| Command | Description |
| ------- | ----------- |
| `ls` | Program will list the contents of the current directory in short form |
| `ls -l` | Detailed List |
| `ls -a` | Displays Hidden Files |
| `ls -lart` | Lists directory contents in long list mode, showing hidden files and reverse sorted by last modified date |
| `cp` | Copies sourcefile to targetfile |
| `cp -i` | Waits for confirmation, if necessary, before an existing targetfile is overwritten |
| `cp -r` | Copies recursively (includes subdirectories) |
| `mv` | Copies sourcefile to targetfile then deletes the original sourcefile |
| `mv -b` | Creates a backup copy of the sourcefile before moving |
| `mv -i` | Waits for confirmation, if necessary, before an existing targetfile is overwritten |
| `rm` | Removes the specified files from the system. Directories are not removed by rm unless the option -r is used |
| `rm -r` | Deletes any existing subdirectories |
| `rm -rf` | It is used to permanently delete files and directories without confirmation |
| `rm -i` | Waits for confirmation before deleting each file |
| `ln` | Creates an internal link from the sourcefile to the targetfile, under a different name |
| `ln -s` | Creates a symbolic link |
| `cd` | Changes the current directory. cd without any parameters changes to the user's home directory |
| `cd..` | It is used to move from one directory to a higher directory |
| `mkdir` | Creates a new directory |
| `rmdir` | Deletes the specified directory, provided it is already empty |
| `chown` | Transfers the ownership of a file to the user with the specified user name |
| `chown -R` | Changes files and directories in all subdirectories |
| `chgrp ` | Transfers the group ownership of a given file to the group with the specified group name. The file owner can only change group ownership if a member of both the existing and the new group |
| `chmod` | Changes the access permissions |

#### Commands to Access File Contents
| Command | Description |
| ------- | ----------- |
| `cat` | The cat command displays the contents of a file, printing the entire contents to the screen without interruption |
| `cat -n` | Numbers the output on the left margin |
| `grep` | | The grep command finds a specific searchstring in specified file(s). If the search string is found, the command display the line in which the searchstring was found along with the file name |
| `grep -i` | Ignore case |
| `grep -l` | Only displays the names of the respected files, but not the text lines |
| `grep -irl` | Used to search for text within files |

#### Processes
| Command | Description |
| ------- | ----------- |
| `top` | top provides a quick overview of the currently running processes. Press H to access a page that briefly explains the main options to customize the program |
| `ps` | This command displays a table of all your own programs or processes - those you started |
| `ps aux` | Displays a detailed list of all processes, independent of the owner |
| `ps -ef` | Lists all running processes with their details |
| `kill` | Sends a TERM signal that instructs the program to shut itself down |
| `kill -9` | Sends a KILL signal instead of a TERM signal, with which the process really is annihilated by the operating system. This brings the specific processes to an end in almost all cases |
| `kill -f` | It is used to terminate processes matched by a specific command or command line |
| `killall` | Similar to kill, but uses the process name (instead of the process ID) as an argument, causing all processes with that name to be killed |

#### `ps -ef | grep ` A combination of these commands is commonly used to filter processes that contain a specific process or group of processes, username, or other attribute


