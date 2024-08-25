# This is my notes & commands about git


- add files `git add filename`
- commit changes `git commit -am " message nam "`
- switch to another branch `git checkout branch-name` like `git checkout main`

- show info `git log --oneline --decorate --graph --all`
-----
###  Merging 
- switch to the banch you wanna merge into, then do the command `git merge remote-feature-branch`
- to abort the meging when conflicts happen use `git merge --abort`
- to delete a branch use `git branch -d branch-name`


### How to Remove a Git User from the Terminal?
Git user can be set using the following commands:

```
git config --global user.name [username]
git config --global user.email [user email]
```
Username and email can be checked using the following commands

```
git config --global user.name
git config --global user.email
```
Now to remove user details we use the unset commands as given below:
```
git config --global --unset user.name
git config --global --unset user.email
OR
git config --global --replace-all user.name "Your New Name"
git config --global --replace-all user.email "Your new email"
```
Adding new remote
```
git remote -v # list current remotes
git remote add target https://<token>@github.com/<nuame>/<reponame>.git
```
#### Stash
it is about saving your current changes without doning un-nedded commits
https://www.youtube.com/watch?v=lH3ZkwbVp5E

```
git stash # save yr changes
# do checkout another branch and go back
git stash pop
git stash apply # do the same but also don't remove anything from the stash queue.
```
# Conan
 ```
conan profile new mynewprofile --detect
conan profile list
 conan profile show myprofile1
```
