# This is my notes & commands about git
```
git add filename
git commit -am " message nam "
git checkout commit_sha
git checkout main
git log --oneline 
```
git log --oneline --decorate

git log --oneline --decorate --graph --all
### to merge 
- switch to master (or any other branch )
- merge the desigred branch with it
``` git merge hotfix ```
### to delete 
git branch -d hotfix
-----
### git merging 
- switch to the banch you wanna merge into, then do the command `git merge remote-feature-branch`
- to abort the meging when conflicts happen use `git merge --abort`
- this is his branch change
