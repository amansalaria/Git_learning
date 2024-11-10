# Git: Version Control System

Git is a powerful version control system developed to coordinate work among developers. It helps manage changes to source code over time, ensuring collaboration and efficiency.

## Features of Git

- **Open Source**: Git is distributed under the GPL license, making it free to use and modify.
- **Scalable**: Git can handle a large number of users and repositories efficiently.
- **Distributed**: Users can clone repositories to their local machines, allowing for offline work and redundancy.
- **Security**: Git uses SHA1 (Secure Hash Algorithm 1) to name and identify objects, ensuring data integrity.
- **Speed**: Most operations are performed locally, making Git very fast.
- **Branching and Merging**: Git supports multiple branches, allowing developers to work on different features simultaneously and merge changes seamlessly.
- **Staging Area**: Provides a preview of the next commit, allowing for better control over changes.

## Benefits of Using Git

- **Collaboration**: Facilitates teamwork by allowing multiple developers to work on the same project.
- **Version History**: Keeps a detailed history of changes, making it easy to revert to previous versions.
- **Backup**: Distributed nature ensures that each clone is a full backup of the repository.
- **Flexibility**: Supports various workflows and branching strategies.

## Installing Git on Windows

1. Visit Git Downloads.
2. Download and install Git from the website.

## Basic Git Commands

### Check Git Version
```bash
$ git --version

**Register User with Git**
$ git config --global user.name "Aman"
$ git config --global user.email "amansalaria11@gmail.com"

**Verify the configuration:**
$ git config --list

**Important Terminology**
**Branch**: A separate line of development in a repository.
**Checkout**: Switching between different versions or branches.
**Clone**: Creating a copy of a repository from a server.
**Merge**: Combining changes from different branches.
**Origin**: The default name for a remote repository.
**Pull**: Fetching and integrating changes from a remote repository.
**Push**: Uploading local changes to a remote repository.
.**gitignore**: A file specifying which files and directories to ignore.
**git** diff: Shows changes between commits, working directory, etc.
**git** rm: Removes files from the working directory and staging area.

**Getting Started with Git**
**Create a Local Repository**
$ git init

**Clone a Repository**
$ git clone <repository_url>

**Adding Files to Staging Area**
$ git add <file>  # Single file
$ git add -A      # All files

**Check the Status of Files**
$ git status

**Committing Changes**
$ git commit -m "commit message"

**Tracking Changes**
Changes not staged:
$ git diff

**Changes staged but not committed**
$ git diff --staged

**Changes after committing:**
$ git diff HEAD

**Show Objects**
$ git show
**Show Objects**
$ git show

**Commit History
Display recent commits:**
$ git log

**Show changes introduced in each commit:**
$ git log -p -2

**Output one commit per line:**
$ git log --oneline

**Display files modified in each commit:**
$ git log --stat

**Show modifications on each line of a file:**
$ git blame <file>

**Ignoring Files**
Create a .gitignore file to specify files and directories to ignore.

**Branching
List branches:**
$ git branch --list

**Create a new branch:**
$ git branch <name>

**Delete a branch:**
$ git branch -d <name>

**Rename a branch:**
$ git branch -m <old_name> <new_name>

**Switching Branches
Switch to a branch:**
$ git checkout <branch_name>

**Create and switch to a new branch:**
$ git checkout -b <branch_name>

**Merging Branches
Merge a branch into the current branch:**
$ git merge <branch_name>

**Working with Remote Repositories
View remote repositories:**
$ git remote -v

**Add a remote repository:**
$ git remote add <name> <remote_url>

**Removing Files
Delete a file from the working directory and staging area:**
$ git rm <file>

**Remove a file only from the staging area:**
$ git rm --cached <file>

**GitHub: Repository Hosting Service
Working with Remote Repositories**
**Add a remote repository:**
$ git remote add origin <url>

**Verify remote repositories:**
$ git remote -v

**Push changes to the remote repository:**
$ git push -u origin master

**Change the URL of a remote repository:**
$ git remote set-url origin <new_url>

