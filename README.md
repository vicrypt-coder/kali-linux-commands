# Kali Linux Basic Commands

Hands-on practice with the basic Linux commands used to navigate and manage files in Kali Linux, completed while learning cybersecurity (started September 2026).

**Environment:** Kali Linux (terminal)

## Commands practised

| Command | What it does |
|---|---|
| `pwd` | Shows the directory I'm currently in |
| `ls` | Lists the files and folders in the current directory |
| `cd <folder>` | Moves into a folder |
| `mkdir <name>` | Creates a new folder |
| `touch <file>` | Creates a new empty file |
| `cat <file>` | Displays the contents of a file |
| `cp`, `mv`, `rm` | Copies, moves/renames and deletes files |

## 01. Navigating the file system

Used `pwd` to confirm my location, `ls` to list files, and `cd` to move into a folder.

![pwd, ls and cd](screenshots/01-pwd-ls-cd.png)

## 02. Creating folders and files

Created a folder with `mkdir`, an empty file with `touch`, and displayed it with `cat`. The `cat` command printed nothing because the file was empty, which confirmed that `touch` creates a blank file.

![mkdir, touch and cat](screenshots/02-mkdir-touch-cat.png)

## 03. Writing, copying, moving and deleting files

Wrote text into a file with `echo`, copied it with `cp`, renamed it with `mv`, and removed it with `rm`.

![echo, cp, mv and rm](screenshots/03-echo-cp-mv-rm.png)

## What I learned

- Almost everything in Linux is a file or a folder, and the terminal can manage all of it.
- `rm` deletes permanently, with no recycle bin, so I should double-check before running it.
- File names are case-sensitive on Linux, so `Notes.txt` and `notes.txt` are different files.
- These commands are the base for the next labs on file permissions and checking logs.

## Next steps
File permissions with `ls -l`, `chmod` and `chown`, and checking system logs.
