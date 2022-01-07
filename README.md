<!-- # git-github-cheatsheat -->
# **Git CheatSheet**

## Initialization
```
git init
```
`:- Initialize the existing directory as a git repo`
___

## Status
```
git status
```
`:- Give the current status of the repo`
___

## Stage and Commit 
```
git add <file name >
git commit -m "commit message"
```
`:-Stage the changes and then commit`<br>
`:-This is very common workflow` <br>
```
git commit --amend
```
`:- Redu the last commit`
___

## Info about Commits 
```
git log
<or>
git log --oneline
```
`:- Give us information about the commits`
___

## Branching
```
git branch
```
`:- show list of all branches`
```
git branch <branch name>
```
`:- Create the new branch with that particular branch name`
```
git switch <branch name>
```
`:- To switch on that particular branch`
```
git merge <branch name>
```
`:- To merge the branch`
```
git branch -m <branch name>
```
`:- to raname that particular branch`
```
git branch -D <branch name>
```
`:- to delete that particular branch`

---
## Comperision
```
git diff
```
`:- show changes since last stage`
```
git diff HEAD
```
`:- Show the changes since last commit`
```
git diff --staged
```
`:- show changes between last commit and last stage`
```
git diff <commit1> <commit2>
```
`:- show the changes between these commits`
```
git diff <branch1> <branch2>
```
`:- show the changes between the branches`

---
## Stashing
```
git stash 
```
`:- stash the changes that are not ready to commit`
```
git stash pop
```
`:- to bring back the recent stash`
```
git stash list
```
`:- show the list of all stash`
```
git stash apply <stash refer>
```
`:- to bring back the particular stash`
```
git stash clear
```
`:- to clear of stash`

---
## Time travelling
```
git checkout <commit>
```
`:- to time travell at that particular commit `

---
## Undoing
```
git restore <file name>
```
`:- undo the changes in that file since last commit `
```
git restore --staged <file name>
```
`:- unstage the last stage in that file`

---

## Reset 
```
git reset <commit>
```
`:- reset the repe back to that particular commit but our changes will be their in our working directory`
```
git reset --hard <commit>
```
`:- reset the repo back to that particular commit as well as associated changes`

---
---
---
---
---

# **Github CheatSheet**

## Cloning

```
git clone <url>
```
`:-  clone a repo`

---
## Remote

```
git remote -v
```
`:- show the list of all remotes`
```
git remote add <remote label> <url>
```
`:- add a remote `

```
git remote remove <remote label>
```
`:- to remove a remote`

---
## Pushing

```
git push <remote> <branch>
```
`:- to push that particular branch on remote repo`

---

## fetching

``` 
git fetch <remote>
```
`:- download all changes from our remote repo to our local repo but these changes will not intergrate with our working directory`

---

## Pulling 

``` 
git pull <remote> <branch>
```
`:- download all the changes form the particular branch of remote repo to local repo and merge with the current standing branch`








