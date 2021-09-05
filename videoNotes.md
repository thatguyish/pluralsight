# Plural Sight Notes on Git

> git config --list
- Will display all available options to modify git
  
> man [git]
- gives you a list of options for any command (In this instance git)

> git status --s 
- displays a smaller version of git status

> git log -[1]
- limits the amount of commits displayed by git log (In this instance 1)

> git rm [name of file]
- deletes file from git and local storage
  
> git rm --cached [name of file]
- removes file from being tracked but doesnt delete the file

> git stash 
- record a current state of a working directory.

> git stash list
- displays what saved states are in the stash 

> git stash pop
> removes saved state from stash 