# Git Commands :

checking the status -

`git status`

initializing git repository (only one time using its enough):

`git init`

ls -a → all files, minimal info -

`ls -a`

ls -la → all files, detailed info -

`ls -la`

Add to tracking via git to get into staging area -

`git add <filename>`

commit the file about it -

`git commit -m 'add file details'`

Give you full detailed status of commited files -

`git log`

This syntax givne you relavant instead of long format(similar to git log):
`git log --oneline`

Git needs to know who made each commit -

```
git config --global user.name 'username'

git config --global user.email 'useremail'

```

Sets VS Code as Git’s default editor for commit messages and waits until you close it before continuing -

`git config --global core.editor "code --wait"`

To check where our username and user email stored

used this command:

(make sure to use this command you should come to Users/saichaitanya) -

`cat .gitconfig`

## Git Branches :

Default you will get into th master branch:

`git branch`

And more thing lets say if you of team member is working on the navbar or anything if he want pushed the code to with another branch then we use

`git branch nav-bar`

for checking the branch

(Will show you how many branches are there which current working branch)

`git branch`

To switch one branch to another

old version:

`git checkout <branchname>`

lastest version:

`git switch <branchname>` # to change branches

create an branch and move you there

old version:

`git checkout -b <branch name>`

latest version:

`git switch -c <branch name>`

## Merging of the branches :

To merge branch use :

`git merge day2 -m 'merging the day2 with master'`

- If you want to merge footer into master, you need to be on master first(but in conflicts it will me some what different).

- commit message is required or you will enter into separate code editor to commit the message

To delete the branch

`git branch -d day2`

- Make sure about conflicts ,updating and merging

# Stashing

Its an showing the changes before staging and after

`git diff`

- (git diff is not for comparing two random files like a regular file comparison tool.)
