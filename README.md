# GitHub Simple Command II

## Git Clone
`git clone` is used for just downloading exactly what is currently working on the remote server repository and saving it in your machine's folder where that project is placed. (Only one time)
do add the full address of the repo after clone.

## Git Fetch
`git fetch` just "downloads" the changes from the remote to your local repository. 

## Git Pull
`git pull` is a (clone(download) + merge) operation and mostly used when you are working as teamwork. (Can be multiple time if there is new changes on the repo). git pull downloads the changes and merges them into your current branch. 

## Git Add
`git add` is used to stage the all the file for commit to your local repository by the following command.

## Git Branch
`git branch` is used to see list of available branch on local repository

## Git reset
`git reset` --hard origin/master
is used when you want to ignore all locat stuff and get exact remote copy without error issues.

## Git remote
to change the remote to SSH instead of HTTPS etc
`git remote set-url origin` SSH repo address pasted here(from git) 