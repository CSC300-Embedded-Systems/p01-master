# How to use git

## How to get started

1. Install git
2. Open Git Bash
3. Clone the repo:
   1. ```git clone \<repo_URL\>```
   2. cd \<repo_dir\>

## Start coding

1. git branch \<branchname\>
2. git checkout \<branchname\>
3. \<write code\>
4. git add -A or git add \<filename\>
5. git commit -m "\<witty message\>"
6. git push 

Your files are now in Github.

## Collaborating

Always work from your own branch, then merge:
1. Add, commit, and push to your branch
2. Pull in all changes from master:
    1. git checkout master
    2. git pull origin master
    3. git checkout \<branch_name\>
    4. git merge master
    
    NOTE: You may get conflicts here. Review each file, fix the conflicts, then commit

3. Add, commit, and push to your branch
4. Go to Github, and issue a pull request from your branch to master



