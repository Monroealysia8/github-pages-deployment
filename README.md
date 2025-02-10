# COMMANDS

## BASH COMMANDS

### CREATE FILE

- `touch {filename}     # Create an empty file or update its timestamp`
- `echo "some text" > textfile.txt  #Create a file with content`

### CREATE FOLDER

- `mkdir {folderName} # Create a new directory`

### Navigate Directories

- `cd {directoryName}   # Change directory`
- `cd ..    # Move up one directory level`
- `cd../..  # Move up two directory(no effect)`
- `cd .     # Stay in the current directory(no effect)`
- `pwd  # Print working directory`
- `ls   # List files and folders`
- `ls -la   # List all files including hidden ones`

### FILE OPERATIONS

- `cp {source} {destination}    # Copy file or folder`
- `cp -r {sourceFolder} {destination}   # Copy folder and contents to destination`
- `mv {source} {destination}    # Move or rename file or folder`
- `rm {filename}    # Remove file`
- `rm -r {folderName}   #Remove folder and contents`

## GIT COMMANDS

### INITIALIZE REPOSITORY

- `git init # Initialize a new Git repository`

### ACP (Add, Commit, Push)

- `git add .    # Stage all changes`
- `git commit -m "commit message"   # Commit changes`
- `git push origin {branchName}     # Push changes to remote repository`

### CLONE REPO

- `git clone {repoURL}`

### CREATE BRANCH

- `git branch {branchName}  # Create new branch`
- `git checkout {branchName}    # Switch to branch`
- `git checkout -b {brancName}  # Create and switch to a new branch`
- `git switch -c {branchName}   # Create and switch to a new branch(alternative to checkout)`

### SWITCH BRANCH

- `git checkout {branchName}    #Switch to branch`
- `git switch {branchName}  #Alternative to checkout(NEWER VERSION)`

### MERGE BRANCH 
- `git merge {branchName}   # Merge branch into current branch`

### REBASE
- `git rebase {branchName}  # Reapply commits from another branch on top of the current branch`

- `git rebase -i {branchName} # Interactive rebase to modify commit history`

- `git rebase --abort   # Abort a rebase in progress`
- `git rebase --continue    # Continue rebase after resolving conflicts`

### PULL CHANGES

- `git pull origin {branchName}     # Fetch and merge changes from remote`

### CHECK STATUS

- `git status   # Show status of working directory`
- `git help     # Help with more commands`

### VIEW LOGS

- `git log --oneline -- graph --all # Compact commit history with branches`


