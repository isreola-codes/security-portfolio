# Linux basics

Linux is like a house. Folders are rooms and files are things in the rooms.

## Moving around
- `pwd` shows which folder I'm in.
- `ls -la` lists all files, including hidden ones, with details.
- `mkdir`, `cd`, `cd ..` and `touch` make folders, move between them, and create files.

## Permissions
Permissions like `-rwxr-xr--` have three groups: owner, group and others.
- `r` = read, `w` = write, `x` = execute
- `chmod +` adds a permission and `chmod -` removes one.

## Logs and searching
- System logs live in `/var/log`.
- `head` shows the first 10 lines and `tail` shows the last 10 (the latest news).
- `grep` shows the lines that contain a word.
- The pipe `|` takes the output of one command and passes it as the input of the next.

## Users and processes
- `ps aux` lists running processes and `top` shows what is using the most power.
- `root` is the special user with no limits. `sudo` runs one command with root's powers.

## Why this matters for security
A file that everyone can write to is a weak door. Analysts check permissions, logs, users and processes to find these problems.
