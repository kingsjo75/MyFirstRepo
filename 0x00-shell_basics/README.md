# 0x00. Shell, basics

## Project Description

This project introduces the basics of Linux file system navigation and fundamental shell commands, designed for those new to programming. Through these tasks, learners will gain hands-on experience in viewing directory contents, understanding file structures, and writing simple shell scripts to perform common operations. The goal is to build a foundational understanding of how to navigate and manage files within the Linux command-line interface.

## Learning Objectives

By completing this project, you will be able to:
- Navigate the Linux file system using basic shell commands
- Understand the current working directory and how to change it
- List and view file and directory contents
- Create and manage files and directories
- Write simple shell scripts with proper syntax and execution permissions
- Understand file permissions and how to modify them

## Files and Scripts

| File | Purpose |
|------|---------|
| 0-current_working_directory | Print the absolute path of the current working directory |
| 1-listit | List all files and directories in the current working directory |
| 2-bring_me_home | Change the current directory to the user's home directory |
| 3-listfiles | List all files and directories in the current directory in a long format |
| 4-listmorefiles | List all files including hidden ones in the current directory |
| 5-listfilesdigitonly | List all files with their numeric user and group IDs instead of names |
| 6-firstdirectory | Create a directory named `my_first_directory` in the `/tmp` directory |
| 7-movethatfile | Move a file from `/tmp` to `/tmp/my_first_directory` |
| 8-firstdelete | Delete a file from `/tmp/my_first_directory` |
| 9-firstdirdeletion | Delete the directory `/tmp/my_first_directory` |
| 10-back | Change the working directory to the previous one |
| 11-lists | List all files in multiple directories |
| 12-file_type | Print the type of a file |
| 13-symbolic_link | Create a symbolic link to a file |
| 14-copy_html | Copy all `.html` files from one directory to another |

## Requirements

- All scripts must start with `#!/bin/bash`
- All scripts must be executable
- Scripts should follow the exact specifications provided in their task descriptions
- No script should use external commands unnecessarily; use shell built-ins when possible

## How to Use

1. Navigate to the `0x00-shell_basics` directory
2. Run any script with `./script_name` or `bash script_name`
3. Example: `./0-current_working_directory`

## Notes

- Ensure all files have the correct permissions to be executable
- Each script should perform only the specified task
- Keep scripts simple and focused on their single responsibility
