# Git Commands for DevOps

## 1. Creating and Navigating Directories
- `mkdir git-for-Devops`  
  Create a directory called `git-for-Devops`.

- `cd git-for-Devops/`  
  Change into the `git-for-Devops` directory.

- `ls`  
  List the files and directories.

- `ls -la`  
  List files and directories in long format with hidden files.

- `pwd`  
  Show the current directory.

## 2. Git Configuration
- `git config --global user.name "ashu-git"`  
  Set the global Git username.

- `git config --global user.email "verma.ashutosh@gamil.com"`  
  Set the global Git email (incorrect email format here).

- `git config --global user.email "verma.ashutosh@gmail.com"`  
  Correct global Git email configuration.

## 3. Git Status and File Operations
- `git status`  
  Show the working directory and staging area status.

- `touch nibba.txt nibbi.txt`  
  Create new empty files: `nibba.txt` and `nibbi.txt`.

- `rm -r nibba.txt nibbi.txt`  
  Remove the files `nibba.txt` and `nibbi.txt`.

## 4. Initializing Git Repository
- `git init`  
  Initialize a new Git repository in the current directory.

## 5. Staging and Committing Files
- `git add nibbi.txt`  
  Add `nibbi.txt` to the staging area.

- `git add nibba.txt`  
  Add `nibba.txt` to the staging area.

- `git rm --cached nibba.txt`  
  Remove `nibba.txt` from the staging area (not from the file system).

- `git commit -m "adding nibba.txt nibbi.txt"`  
  Commit the changes with a message.

- `git restore nibbi.txt`  
  Restore the `nibbi.txt` file from the repository (undo changes).

- `git restore nibba.txt nibbi.txt`  
  Restore both `nibba.txt` and `nibbi.txt` files.

## 6. Branching and Checking Out Branches
- `git branch`  
  List all local branches.

- `git checkout -b dev`  
  Create and switch to a new branch called `dev`.

- `git checkout master`  
  Switch to the `master` branch.

- `git checkout dev`  
  Switch to the `dev` branch.

## 7. Viewing Git History
- `git log`  
  View the commit history.

- `git log --oneline`  
  View the commit history in a condensed format with one commit per line.

## 8. File and Directory Listings
- `ls`  
  List files in the current directory.

- `ls -a`  
  List all files including hidden files.

## 9. Final Cleanup and History
- `history`  
  Show the command history.
