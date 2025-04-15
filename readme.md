## hello here is the code for readme file

# first we need to initialize the git

git init

git status

git add readme.md

## it will send the file at the staging env that come before github repo

git commit -m "this is my first commit "

git branch --> output : master

# rename the master

git branch -M main

# restore the file form the stagging state

git restore readme.md

# for add 1 or more files we can use git add .

# undo the stagging

git restore --staged "stagging.md"

git diff --staged

# tell about the commit that we do with the file updated

git commit + stagging part --> move toward the github repo

# create a new branch

git branch branch-name

## there are three to - 4 branches as we go a head

# so for switch the branch we can use

git checkout newly-created-branch

# meage two branch

git mearge otherbranch-name
