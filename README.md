Hello World!!!
## Basic Termainal code:
1. `touch <filename.type>` create a file
2. `mkdir <foldername>` create a folder
3. `pwd` your current location
4. `ls` where you can go
5. `cd <file name>` go to the file in terminal add a `.` for going backwards and a `..` for the home folder

## Creating a new repo:
1. `git init` <- initializing a git repository
2. Create repo on github
3. `git remote add origin <github http url>`
4. to test run `git remote -v` - shows if remote repository is connected

## HOW to create / push commits:
1. `git add .` - means git add everything, all saved changes
2. `git commit -m "Commit message here"`
3. `git push origin master` or `git push origin master -u`


*** If you use `-u` upstream flag, all subsequent /further commits you use `git push` instead of `git push origin master` ***


# Branching your repo:
1. `git branch <name of new branch>` - create a new branch
2. `git checkout` to see what branch we are on
3. `git checkout <name of branch>` - to swtich to different branch
    -   when in alternative branch all changes are saved/commited only to that branch

*** DO NOT MAKE CHANGES TO BOTH BRANCHES ***

## Git Merging:
-  Merging is the process of combining a secondary branch with the master branch
1. Switch to branch you want to merge into (usually main branch)
2. `git merge <name of branch to merge>` - comebines secondary branch into main

# Git clone:
1.  In terminal, navigate to folder you want to clone code in to.
2. Run command, `git clone <Https url from git hub> opt_new_name _for_folder`

# Git Pull: 
1. In terminal, directory should be the repo you want to update
2. Run command, `git pull`

