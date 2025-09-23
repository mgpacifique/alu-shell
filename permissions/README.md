# Permissions Exercises - ALX Shell

This directory contains scripts for the **Permissions** section of the ALX Shell project.  
These exercises focus on **user management, file ownership, groups, and permission manipulation** in Linux.

## Scripts Overview

| Filename                         | Description |
|----------------------------------|-------------|
| `0-iam_betty`                     | Switches the current user to `betty`. Must use exactly 8 characters for the command. |
| `1-who_am_i`                      | Prints the effective username of the current user. |
| `2-groups`                        | Prints all the groups the current user is part of. |
| `3-new_owner`                     | Changes the owner of the file `hello` to the user `betty`. |
| `4-empty`                         | Creates an empty file called `hello` in the working directory. |
| `5-execute`                       | Adds execute permission to the owner of the file `hello`. |
| `6-multiple_permissions`          | Adds execute permission to owner and group, and read permission to others for `hello`. |
| `7-everybody`                     | Adds execute permission to owner, group, and others for `hello` (no commas allowed). |
| `8-James_Bond`                    | Sets `hello` permissions: owner and group none, others all permissions (no commas). |
| `9-John_Doe`                      | Sets the mode of `hello` to `rwxr-x-wx` (no commas allowed). |
| `10-mirror_permissions`           | Sets `hello` permissions to match the file `olleh`. |
| `11-directories_permissions`      | Adds execute permission to all subdirectories in the current directory for owner, group, and others; files remain unchanged. |
| `12-directory_permissions`        | Creates a directory called `my_dir` with permissions `751`. |
| `13-change_group`                 | Changes the group owner of `hello` to `school`. |
| `14-change_owner_and_group`       | Changes owner to `vincent` and group to `staff` for all files and directories in the current working directory. |
| `15-symbolic_link_permissions`    | Changes owner and group of the symbolic link `_hello` to `vincent` and `staff`. |
| `16-if_only`                       | Changes owner of `hello` to `vincent` only if it is currently owned by `guillaume`. |

## Notes

- All scripts should be **executable**:
```bash
chmod +x <script_name>
