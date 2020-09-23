# freeCodeCamp

This repository will contain all my projects made at freeCodeCamp.

# Github

## Git clone

Use "git clone" when you want to clone a github repository into a folder on alexanderfluna.

## Git status

Make sure to be in the directory and to save your files first.

Use "git status" to check if there have been any changes to files that were not added, committed, then pushed to the origin yet.

## Git add .

First step:
Use "git add ." to add all of the changes made to any files. Only do this for files that you just created, not modified.

## Git commit -m " " -m " "

Second step:
Use git commit -m " " -m " " to commit the add you did in step one.

If you already created the file then you can type git commit -am " " to do step 1 and step 2 together.

## Git push

Third step:
Use "git push" to push the commits to the origin.

Press "cancel" then sign in to github with your username and password.

## Git pull

Use "git pull" to pull any changes made in the origin to your local files.

## Git branching

Branching is good to learn when working with others. It creates temporary repositorites to do some code in that will eventually be merged it into the main repository.

Type "git branch" to list all branches

Type "git checkout <branch>" to change between branches. For the <branch>, you can just type the first letters and TAB to finish.

To create a new branch, type "git checkout -b <name>"

"git diff" shows you what has been changed

"git merge <branch>" merges the branches and pushes the changes

"git branch -d <branch>" deletes the branch

## Undoing git

"git reset" will undo any adds that you have.

"git reset <file>" will undo any changes from the file you just made changes to.

"git reset HEAD~1"  will undo the last commit

"git log" gives a list of all previous commits. You can find the hash of a commit to paste into "git reset <hash>", which undos a specific commit.

"git reset --hard <hash>" will completely remove all the changes in this specific commit.

## Forking

Fork means a complete copy of a  repository.
___________________________________________________________
# Visual Studio

## Workspace

You have one workspace in alexanderfluna that should include all other folders so you can see multiple at once.

'M' next to files means "modified"
