# Git

 
To clone the git repo :  git clone <url>
  
Change to the cloned repo : cd \<folder\>
  
check the status : git status 

all changes directly adding to master : git add *

Commit the changes : git commit -m "Starting git notes"

Confirm changes to repo : git push

## Git Branches
create & switch to branch : git checkout -b \<branchname>\else use 2 commands : git branch \<branch name>\git checkout \<branch name>\
#### create a new local branch named after the current story
git checkout -b SS-123
#### create a remote branch which our local one will track
git push -u origin SS-123
... do some work...
#### commit your changes
git commit -m 'SS-123 Fixed bug name field'
#### push to your remote branch
git push origin SS-123
#### update your local repo with changes from the remote
git fetch origin
#### rebase onto master
git rebase origin/master
#### push your rebased branch up to your remote
git push origin SS-123 -f
#### create a new local branch based on an existing remote branch
git checkout -b SS-123 origin/SS-123

Sample git workflow - QA
Most other tasks will be performed directly via the github interface


