# Git Cheat Sheet

## [Managing multiple GitHub account using git in same pc](https://dev.to/raven404/managing-multiple-github-account-using-git-in-windows-2m0h)

### Configure/Reconfigure Globle user
    git config user.name "Name Here"
    git config user.email "youremail@gmail.com"

### View Git all Configuration
    git config --list

### View Git all Configuration and Where they are comming from
    git config --list --show-origin

### Stage Specific File
    git add path/filename

### Stage All unstage file use one of below
    git add --a
    git add .

### Direct Commit with message Without open editor
    git commit -m "message"

### Clone Repo using http url
    git clone http_url

### Show All Git Commit in pretty format
    git log --pretty=oneline

### Show all branch (Local, Remote)
    git branch -a

### Merge branch to current branch
    git merge branch_name

### Create a new branch from specific commit
    git branch branch_name commit_hash

### Delete branch (Local)
    git branch -D branch_name

### Delete branch (Remote)
    git push origin --delete branch_name

### Move/Rename a branch
    git branch -M new_branch_name

### Rename the remote named "old name" to "new name".
    git remote rename origin new_name

### Remove the remote name
     git remote remove origin

### Change the Most Recent Commit Message

     git commit --amend -m "New commit message."
