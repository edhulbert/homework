# Terminal Cheat Sheet

*Ed Hulbert*

### A (hopefully correct &) handy guide to using and navigating the terminal and using git!

## Terminal

| Command | Description | Notes |
| ---------------- | ---------------- | ---------- |
| `cd` | change directory | * `.` refers to current dir<br>* `..` refers to directory above current one|
| `ls` | list  | * shows contents of current directory <br>* `ls -a` shows all, inc. hidden files |
| `rm` | remove | * `-r` argument refers to a directory and everything in it <br> * `-rf` forces as well(?)|
| `mkdir` | make directory | |
| `mv` | move / rename | * `mv <name> <newname>` renames a file <br> * `mv <name> ../<newname>` both moves the file to the directory above, and renames it|
| `touch` | make file | * if file exists, this updates modification time of file |
| `pwd` | print working directory | * this prints the file path of the current directory |

## Git/GitHub

| Command | Description | 
| ------------------- | ---------------- | 
| `git init` | create a new local repository |  
| `git add <file>` | add a file to staging |  
| `gaa` | add all files in current dir (or repo?) to staging | 
| `git commit <filename> -m"<message>"` | commit changes (but not yet to remote repository - github)| 
| `git push` | send changed code to github | 
| `git status` | give info on which files that have been changed and those you need to add/commit | 
| `git log` | gives log of commit, EXIT with q or ctrl+c | 

