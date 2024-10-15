# holbertonschool-shell
Learning the Shell
In this directory I will be learning many different ways to utilise the shell there will be multiple directories within that will focus different areas of the shell.
The Basics directory looks at commands you can use in scripts to manipulate files and directories within the shell. First each file is edited in vi to have two lines, the first line always displays #!/bin/bash while the second line holds the command that the script will execute.
0-current_working_directory a script that prints the absolute path name of the current working directory
1-listit displays the contents list of the current working directory
2-bring_me_home changes the working directory to the users home directory
3-listfiles displays current directory contents in a long format
4-listmorefiles displays current directory contents, including hidden files, in the long format
5-listfilesdigitonly displays current directories contents in long format, with user and group IDs displayed numerically and hidden files
6-firstdirectory creates a directory named my_first_directory in the /tmp/ directory
7-movethatfile moves the file betty from /tmp/ to /tmp/my_first_directory
8-firstdelete deletes the file betty in /tmp/my_first_directory
9-firstdirdeletion deletes the directory my_first_directory that is in the /tmp directory
10-back changes the working directory to the previous one
11-lists lists all files in the current directory and the parent of the working directory and the /boot directory in long format
12-file_type prints the type of the file named iamafile
13-symbolic_link a symbolic link to /bin/ls, named __ls__
14-copy_html copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory
15-lets_move moves all files beginning with an uppercase letter to the directory /tmp/u
16-clean_emacs deletes all files in the current working directory that end with the character ~
17-tree creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory
