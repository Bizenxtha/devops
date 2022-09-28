# devops
learning git from github.

# GIT Commands
git init: to initalize the an empty repo

git clone <url>: to clone the remote repository in to the local machine
after cloning "cd reponame/directory"

git branch: to check which branch we are working on

git branch -a : to display all the branches

git checkout -b <branch name>: to create a new branch and checkout on that branch.

git add . : to add all the file (makes the files in to tracking from untracked mode)

git commit -m "commit message": to create the commit (version)

git push origin <branch name>: to push the local changes to remote repository for the respective branch

git pull origin <branch name>: to pull the branch in to current branch

git diff: to see the difference in local machine (this has to be perfmored before git add)

git status: to check the current status of the files in repo (like, untracked, added, any commites to be made)

git log: to view the commit information

git push --set-upstream origin <branch name>

git push origin :<branch name> : to delete a branch from remote repo (example "git push origin :feature/task-1")
