# Git_all_commands

_1._ Initializing the repository
``` 
$ git init .
```
_2._ To show the status of your repository
``` 
$ git status
```
_3._ To add files for staging before commiting
```
$ git add <filename>
```  
_4._ To commit the changes made 
```
$ git commit -m"<type the message explaining what you have done>"
```
_5._ It will show all the commits and history of the repo
```
$ git log 
```
_6._ It will show all the commit 
``` 
$ git log --oneline ()
```
_7_. It will make a branch of the git repo so that you can work on your own and then merge later on
```
$ git checkout -b <branch name> 
```
_8._ The argument is the branch name you want to merge in your current branch
```
$ git merge <arguement> 
```
_9._ For getting a graphical visualisation of the git tree
```
$ git log --oneline --color --graph --decorate
```
_10._ To sync local repository to your GitHub repository
```
$ git remote add origin <url of the repo> 
```
_11._ All the branches wil get pushed into GitHub repository
``` 
$ git push -all 
```
_12._ It will tell all the fetch and pull history of the repository
```
$ git remote -v
