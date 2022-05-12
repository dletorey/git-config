# Git Config file
## Aliases
Git Aliases are shortcuts for when using git. For example instead of typing:
```txt
git commit -m "this is my commit message"
```
You could instead type:
```txt
git ci "this is my commit message"
```
This is done by setting up an alias:
```txt
git config --global alias.ci 'commit -m'
```
## My Aliases
I have intentionally decided to keep these to a minimum as I am not an *advanced* git user and stick to a few basic commands I am, currently, the only person working on the repositories that I work on.
### status
Check the current status with verbose message
```txt
git config --global alias.st 'status'
```
### add all
```txt
git config --global alias.aa 'add -A'
```
### commit
Commit with the message flag
```txt
git config --global alias.ci 'commit -m'
```
### branch
Switch to another branch
```txt
git config --global alias.br 'branch'
```
### checkout
Switch to a branch or tag
```txt
git config --global alias.co 'checkout'
```
### create branch and checkout
Create a new branch and switch to it
```txt
git config --global alias.cob 'checkout -b'
```
### delete branch locally
Delete a branch on local machine
```txt
git config --global alias.dbl 'branch -d'
```
### delete branch remotely
Delete a branch on local machine
```txt
git config --global alias.dbr 'push origin --delete'
```
## My Shortcuts
### status
```txt
git st
```
### add all
```txt
git aa
```
### commit
```txt
git ci "the commit message"
```
### branch
```txt
git br
```
### checkout
```txt
git co branch-name
```
### create branch and checkout
```txt
git cob new-branch-name
```
### delete branch locally
```txt
git dbl branch-name
```
### delete branch remotely
```txt
git dbr branch-name
```