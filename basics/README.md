# 0x00. Shell, basics

This project introduces the basics of the Linux shell.  
Each script is exactly two lines: the first line starts with `#!/bin/bash` and the second line contains the command.

## Scripts

- **0-current_working_directory**: Prints the absolute path name of the current working directory.
- **1-listit**: Displays the contents of the current directory.
- **2-bring_me_home**: Changes the working directory to the user's home directory.
- **3-listfiles**: Displays current directory contents in long format.
- **4-listmorefiles**: Displays current directory contents, including hidden files (`.` files), in long format.
- **5-listfilesdigitonly**: Displays current directory contents with numeric user/group IDs, long format, including hidden files.
- **6-firstdirectory**: Creates a directory named `my_first_directory` inside `/tmp`.
- **7-movethatfile**: Moves the file `betty` from `/tmp` to `/tmp/my_first_directory`.
- **8-firstdelete**: Deletes the file `betty` in `/tmp/my_first_directory`.
- **9-firstdirdeletion**: Deletes the directory `my_first_directory` inside `/tmp`.
- **10-back**: Changes the working directory to the previous one.
- **11-lists**: Lists all files (including hidden ones) in the current directory, the parent directory, and `/boot` in long format.
- **12-file_type**: Prints the type of the file named `iamafile`.
- **13-symbolic_link**: Creates a symbolic link to `/bin/ls` named `__ls__` in the current directory.
- **14-copy_html**: Copies all `.html` files from the current directory to the parent directory, only if the parent’s copy is missing or older.
- **15-lets_move**: Moves all files beginning with an uppercase letter to the directory `/tmp/u`.
- **16-clean_emacs**: Deletes all files in the current directory ending with `~`.
- **17-tree**: Creates the directories `welcome/`, `welcome/to/`, and `welcome/to/school/` in the current directory in one command.
- ---

## How to Use
1. Clone this repo and navigate into the project directory.
2. Make each script executable:
   ```bash
   chmod u+x <script_name>
