## Git and Git Branching Cheat stylesheet

### Basic commands
* `git init` - initialize current directory with repository
* `git add .` - add all new or changed files in current directory git index, staging them for commit
* `git commit -m "some message"` = commit staged changes to local repository


### Info commands

* `git status` - show status of current working directory
* `git log` - list commit history
* `git log --oneline` - list commit history


## Branch commands
* `git branch` -list local branches, highlights branch you are working on
* `git branch newBranch` - create new branch
* `git checkout newBranch` - switching your working branch
* `git checkout -b otherBranch` -switches to otherBranch and create if it doesn't already exist
* `git branch -M newBranch` - to rename your branch

###Remote subcommands
* `git remote add origin someUrl` - connect local repo to remote repo url as `origin`
* `git push origin branchName` - push local commits to remote repo into branch `branchName` 
##Other commands
* `git help` -List git subcommands and options
* `git config --help` -show options for `git config`
