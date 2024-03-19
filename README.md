## Verify local installation
`git --version`  

## Setup local git profile
`git config --global user.name "<name>"`  
`git config --global user.email "<github email>"`

## Clone from github
`git clone <github-url>`  
`cd <repository>`  
Note: remote origin is added by default after clone


## Optional - manually add remote repo 
`git init` Creates .git  
`git remote add <origin> <REMOTE_URL>`  
`git remote -v`  
`git fetch <remote repo name>`  *Download objects and refs from another repository*

or
`git pull` (note: if already tracking remote) *Fetch from and integrate with another repository or a local branch*    

https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes  


## Resources
https://training.github.com/downloads/github-git-cheat-sheet/  


## Commit
`git status`  
`git add <file>`  
`git restore –unstage <file>`  
`git commit -m “Hello, 50 chars summary”`  
`git push`  

### Commit message best practices
https://gist.github.com/luismts/495d982e8c5b1a0ced4a57cf3d93cf60  
https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html  

## New Branch
`git checkout -b <name>`  
creates a branch and switches to it. same as `git branch <name>; git checkout <name>`   
https://missing.csail.mit.edu/2020/version-control/ 


## Merge Branch
`git checkout main`  
`git merge <branch>`  
`git push`  
`git branch -d <branch>`  


## Common .gitignore configurations
https://gist.github.com/octocat/9257657

## Github actions  
https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions

## Markdown syntax  
https://www.markdownguide.org/basic-syntax/#overview
