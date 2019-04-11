# Git Cheat Sheet 

First `init` a new repository to work with:

$ git init REPO Name 
$ cd REPO Name 

**Note** Directories are not tracked, just add a .keep file

To ignore files add them to 'gitignore': 

log/*.log 

To just add part to the indewe can use `git add -p` 

## Disaster Recovery 

In case of deleted commits use 'git reflog' and 'git cherry-pick´ to recover those commits: 

$ git cherry-pick LOST_COMMIT_SHA1


**Note** Will be cleaned uo once 'git gc' ran 
