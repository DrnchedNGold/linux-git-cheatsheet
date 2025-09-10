# Linux & Git Commands Cheat Sheet

This cheat sheet covers essential Linux and Git commands, along with common and useful flags.

---

## Linux Commands

### 1. `ls` – List files and directories
- `ls` -> list files in the current directory
- `ls -l` -> detailed (long) listing (permissions, size, date, owner)
- `ls -a` -> include hidden files (`.` and `..`)
- `ls -lh` -> human-readable sizes (KB, MB, GB)

### 2. `cd` – Change directory
- `cd /path/to/dir` -> move into directory
- `cd ..` -> go up one level (go to parent directory)
- `cd ~` -> go to home directory
- `cd /` -> go to root directory
- `cd -` -> go to previous directory

### 3. `pwd` – Print working directory
- `pwd` -> show absolute path of current location

### 4. `cp` – Copy files/directories
- `cp file1 file2` -> copy `file1` to `file2`
- `cp -r dir1 dir2` -> copy a directory recursively

### 5. `mv` – Move or rename files
- `mv file1 dir/` -> move file into directory
- `mv old.txt new.txt` -> rename file

### 6. `rm` – Remove files/directories
- *** CAUTION: THIS IS IRREVERSIBLE ***
- `rm file.txt` -> delete file
- `rm -r dir/` -> delete directory recursively
- `rm -rf dir/` -> force delete (skip prompts)

### 7. `mkdir` – Create directories
- `mkdir mydir` -> create new directory
- `mkdir -p a/b/c` -> create parent directories if not existing

### 8. `touch` – Create empty files / update timestamp
- `touch file.txt` -> create empty file if it doesn’t exist

### 9. `cat` – View contents of files
- `cat file.txt` -> display contents
- `cat file1 file2 > combined.txt` -> merge files

### 10. `grep` – Search text patterns
- `grep "pattern" file.txt` -> search for "pattern"
- `grep -i "pattern" file.txt` -> case-insensitive
- `grep -r "pattern" dir/` -> recursive search in directory

---

## Git Commands  

### 1. `git init` – Initialize repository
- `git init` -> create new local repo

### 2. `git clone` – Clone a repository
- `git clone git@github.com:user/repo.git` -> clone via SSH

### 3. `git status` – Check repo status
- `git status` -> see staged, unstaged, and untracked files

### 4. `git add` – Stage files
- `git add file.txt` -> stage specific file
- `git add .` -> stage all changes

### 5. `git commit` – Save snapshot
- `git commit -m "message"` --> commit staged changes with message
- `git commit -am "message"` -> add + commit tracked files in one step
