# How to create and use `.gitignore` file
## 1. Create a file and name it `.gitignore`
### This file should be in the directory that the Git tracks it.
```bash
$ touch .gitignore
```
## 2. Open the created file with an editor and add files and directories that you don't want to push them to Git
### You can add vendor directories or log files to `.gitignore` file.
```bash
$ vi .gitignore
```
## 3. Now you use `git status` to verfiy that the Git doesn't track your files in `.gitignore` file

