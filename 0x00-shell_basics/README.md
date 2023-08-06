
0;276;0c# Shell Basics Scripts

This directory contains shell scripts for various basic tasks.

## Script 0-current_working_directory

This script prints the absolute path name of the current working directory.

## Script 1-listit

This script displays the contents list of the current directory.

## Script 2-bring_me_home

This script changes the working directory to the user's home directory.

## Script 3-listfiles

This script displays the contents of the current directory in a long format.

## Script 4-listmorefiles

This script displays the contents of the current directory, including hidden files, in a long format.

## Script 5-listfilesdigitonly

This script displays the contents of the current directory in a long format, with user and group IDs displayed numerically, including hidden files.

## Script 6-firstdirectory

This script creates a directory named `my_first_directory` in the `/tmp/` directory.

## Script 7-movethatfile

This script moves the file named `betty` from `/tmp/` to `/tmp/my_first_directory/`.

## Script 8-firstdelete

This script deletes the file named `betty` from `/tmp/my_first_directory`.

## Script 9-firstdirdeletion

This script deletes the directory named `my_first_directory` from the `/tmp` directory.

## Script 10-back

This script changes the working directory to the previous one.

## Script 11-lists

This script lists all files in the current directory, the parent of the working directory, and the /boot directory in long format.

## Script 12-file_type

This script prints the type of the file named `iamafile` in the `/tmp` directory.

## Script 13-symbolic_link

This script creates a symbolic link named `__ls__` to `/bin/ls` in the current directory.

## Script 14-copy_html

This script copies HTML files from the current working directory to the parent directory, only if they are newer or do not exist in the parent directory.

## Script 100-lets_move

This script moves files beginning with an uppercase letter to the directory /tmp/u.

## Script 101-clean_emacs

This script deletes files in the current directory that end with the character ~.

## Script 102-tree

This script creates the directories welcome/, welcome/to/, and welcome/to/school/ in the current directory.

## Magic File school.mgc

This magic file `school.mgc` can be used with the `file` command to detect School data files containing the string "SCHOOL" at offset 0.
