# Git_all_commands

_1._ Initializing the repository
``` 
$ git init .
```
_2._ retrieve an entire repository from a hosted location via URL
``` 
$ git clone [url]
```
_3._ show modified files in working directory, staged for your next commit
``` 
$ git status
```
_4._ add a file as it looks now to your next commit (stage)
``` 
$ git add [file]
```
_5._ unstage a file while retaining the changes in working directory
``` 
$ git reset [file]
```
_6._ diff of what is changed but not staged
``` 
$ git diff
```
_6._ diff of what is staged but not yet commited
``` 
$ git diff --staged
```
_7._ commit your staged content as a new commit snapshot
``` 
$ git commit -m “[descriptive message]”
```
_8._ ist your branches. a * will appear next to the currently active branch
``` 
$ git branch
```
_9._ create a new branch at the current commit
``` 
$ git branch [branch-name]
```
_10._ switch to another branch and check it out into your working directory
``` 
$ git checkout [branch name]
```
_11._ create a new branch at the current commit
``` 
$ git branch [branch-name]
```
_12._ merge the specified branch’s history into the current one
``` 
$ git merge [branch]
```
_13._ show all commits in the current branch’s history
``` 
$ git log
```
_14._ show the commits on branchA that are not on branchB
``` 
$ git log branchB..branchA
```
_15._ show the commits that changed file, even across renames
``` 
$ git log --follow [file]
```
_16._ show the diff of what is in branchA that is not in branchB
``` 
$ git diff branchB...branchA
```
_17._ show any object in Git in human-readable format
``` 
$ git show [SHA]
```
_18._ add a git URL as an alias
``` 
$ git remote add [alias] [url]
```
_19._ fetch down all the branches from that Git remote
``` 
$ git fetch [alias]
```
_20._ merge a remote branch into your current branch to bring it up to date
``` 
$ git merge [alias]/[branch]
```
_21._ Transmit local branch commits to the remote repository branch
``` 
$ git push [alias] [branch]
```
_22._ fetch and merge any commits from the tracking remote branch
``` 
$ git pull
```
_23._ delete the file from project and stage the removal for commit
``` 
$ git rm [file]
```
_24._ change an existing file path and stage the move
``` 
$ git mv [existing-path] [new-path]
```
_25._ show all commit logs with indication of any paths that moved
``` 
$ git log --stat -M
```
_26._ apply any commits of current branch ahead of specified one
``` 
$ git rebase [branch]
```
_27._ clear staging area, rewrite working tree from specified commit
``` 
$ git reset --hard [commit]
```
_28._ Save modified and staged changes
``` 
$ git stash
```
_29._ list stack-order of stashed file changes
``` 
$ git stash list
```
_30._ write working from top of stash stack
``` 
$ git stash pop
```
_31._ discard the changes from top of stash stack
``` 
$ git stash drop
