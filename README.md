## Git Workflow

# git add

# git commit 

# git branch

# git checkout

change to the read me

local changes that i havent commited

new change to main

another change to main


# Merging Notes

- to merge changes from main to feature branch call : "git merge main" from feature branch
- make sure to pull all changes beforehand
- This will be merged over to merging branch from main to keep merging up to date
- to merge changes from feature branch to main branch, instead of merging the files locally we want to create a pull request to pull these changes from the feature branch to the main branch (merging feature to main)
- to create this, we can call "git push -u origin merging"
- -u command will set up upstreaming so that time we call a git push it will push this branch to our origin repository
- We call origin as the remote repository to push the merging branch to the remote repository 

# Rebase Notes

- When calling a rebase, we will set the new head of the feature branch to be the lastest commit from main
- to call a rebase, we want to call : "git rebase main" from our feature branch
- this will allow us to update our feature branch with the latest changes to main
- CHANGE TO MAIN - this is a commited change to main that we will use to update in our rebase
- To complete our rebase, we call "git rebase --continue" to accept the changes or updates in conflicts if necessary
- This is the final change to our feature branch, feature branch is complete and will be pushed origin for pull request
