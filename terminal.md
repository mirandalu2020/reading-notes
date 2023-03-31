# Terminal Notes

## The Command Line[^1]

**What is it, how does it work and how do I get to one**.

- The terminal is the text-based interface to the system. It works by presenting the user with a prompt, and the results will be displayed after typing to the prompt.
- In order to open a terminal, a Mac user can find it under Applications --> Utilities; a Linux user can find it in Applications --> System (or Utilities); a Windows user will need to log into another machine then an SSH client is needed (such as Putty)

**Basic Navigation**.

- To get around a linux system, the following commands can be used:

1. `pwd` - Print Working Directory, outputs where the user is current at
2. `ls` - outputs what's in our current location;
3. A path can be specified by starting with `/`, that can be used to specify an absolute path; whereas a relative path specifies a location in relation to where we currently are in the system so `/` is not needed
4. `~` - shortcut to home directory
5. `.` - reference to your current directory
6. `..` reference to the parent directory, ancestories can be tracked using `../../`etc.
7. `cd` - change directory

**More about Files**.

- In the linux system, everything is a file, which includes a text file, a directory, the keyboard, etc. 
- Linux is also extensionless, which means the system does not use the extension to determine what's inside the file, instead it determines the file type by looking inside the files
- If there are spaces in names, the name needs to be encased in quotes, `' '`, or escape characters `xx\ xx`

**Manual Pages**.

- Manual pages are a set of pages that explain every command available on your system including what they do, how to run them, and what arguments they accept.
- The command can be used to search for specific items on the manual pages: keyword search: `man -k <search term>`; look up a specific command `man <command>`, perform a serach for 'term' within the manual page `/<term>`, and after performing a search within a manual page, the select the next found item `n`

**File Manipulation**.
*How to make, remove, rename, copy and move files and directories*

- `mkdir` - to make a directory
- `mkdir -p` - make parent directory as needed
- `mkdir -pv` - make the directory and tell us what it's doing

- `rmdir` - remove a directory, which also supports -v and -p options similarly to mkdir. Also the directory must be empty before it can be removed
- `rm` - remove a file
- `rm -r` - remove a non-empty directory

- `touch` - creating a blank file
- `cp [options] <source> <destination>` - copying a file or directory
- `mv [options] <source> <destination>` - moving a file or directory
- `mkdir --> mv` - effectively rename a file or directory

**Cheatsheet**[^2]

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://ryanstutorials.net/linuxtutorial/commandline.php
[^2]:https://ryanstutorials.net/linuxtutorial/cheatsheet.php
