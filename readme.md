## to initialize git repo in a folder
```
git init 
```

## to clone a git repo to your system
```
git clone username@host:/path/to/repo
```

## to check if a directory is a git repo
git rev-parse --is-inside-tree

## to add changes to the git repo
git add filename 
or
git add *

## to commit these changes to your git repo
git commit -m "commit message"

## to push these changes to the local repo
git push origin master
-- "if do not want to add changes to master branch then add changes to any other branch instead of master"
-->>> if there is an issue while doing commit of username then do 
git config credential.username your_username

## to see the git log tree
git log --graph --oneline --all

## to go to a new branch
git checkout -b branch_name

## to go to an already existing branch
git checkout branch_name

## to delete a branch
git branch -d branch_name

## to merge different branches together
git merge branch_name

## to set global username and email
git config --global user.name "user_name"
git config --global user.email "mail id"

## to set repository specific username and email
git config user.name "user_name"
git config user.email "mail id"

## This command shows the file differences which are not yet staged.
git diff
git diff -staged

## This command unstages the file, but it preserves the file contents.
git reset [filename]

## This command undoes all the commits after the specified commit and preserves the changes locally.
git reset [commit]

## This command discards all history and goes back to the specified commit.
git reset –hard [commit]
