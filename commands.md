# Git Commands Guide

## Basic Setup
- **Create a directory**: `mkdir git-for-devops`
- **Change directory**: `cd git-for-devops/`
- **Show current directory**: `pwd`

## Initialize Repository
- **Initialize Git repository**: `git init`

## File Operations
- **Create files**: `touch nibba.txt nibbi.txt`
- **Remove a file**: `rm hello.txt`
- **List files**: `ls`

## Status and Logs
- **Check repository status**: `git status`
- **View commit logs**: `git log`

## Staging and Committing
- **Stage a file**: `git add nibba.txt`
- **Unstage a file**: `git rm --cached nibba.txt`
- **Commit changes**: `git commit -m "commit message"`

## Branching
- **Create a new branch**: `git checkout -b dev`
- **List branches**: `git branch`
- **Switch to a branch**: `git checkout dev`

## Editing Files
- **Edit a file using vim**: `vim nibbi.txt`
- **Restore a deleted file**: `git restore nibbi.txt`

## Remote Operations (SSH)
- **Edit SSH config**: `sudo nano /etc/ssh/sshd_config`
- **Restart SSH service**: `sudo systemctl restart sshd`
- **List SSH units**: `systemctl list-units | grep ssh`

## Miscellaneous
- **Clear terminal**: `clear`
- **View command history**: `history`
