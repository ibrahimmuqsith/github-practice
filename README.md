# GIT Practice

## Terminologies
1. dfhgw

--------------------------------------------------------------------------------

## stages

1. untracked
    - new files created
2. modified
    - existing files edited.
3. staging
    - 
4. working area
5. 

--------------------------------------------------------------------------------

## local repo flow

1. git config --list
2. git add
    1. git add .
        - moves all files edited
    2. git add file_name
        - moves only file_name to staging
    3. git restore -- staged file_name
        - moves file from staging area to working directory
3. git status
    - shows the current state of all the files
4. git commit -m "some msg here"
    - commiting the changes to be pushed to repo
5. git log
    - shows the list of history of commits.

--------------------------------------------------------------------------------

## live server commands

1. [git branch](https://github.com/new)
    - creating a repo on github server
2. moving local codebase to above created repo.
    - git remote add origin https://github.com/ibrahimmuqsith/github-practice.git
    - git branch -M main
    - git push -u origin main
3. git push origin - main
    - pushing the local commits to remote repo.

--------------------------------------------------------------------------------

## working with teams
1. git checkout -b 'team1'
    - creating a branch with team1
2. git checkout -b 'team1'
    - creating a branch with team1
