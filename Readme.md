# This is my notes & commands about git

`git add filename`
`git commit -am " message nam "`
`git checkout commit_sha`
`git checkout main`

`git log --oneline --decorate --graph --all`
### To merge 
- switch to master (or any other branch )
- merge the desigred branch with it` git merge hotfix `
- to delete  use `git branch -d hotfix`
-----
###  Merging 
- switch to the banch you wanna merge into, then do the command `git merge remote-feature-branch`
- to abort the meging when conflicts happen use `git merge --abort`
