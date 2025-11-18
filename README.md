Hello World!!!
## Creating a new repo
1. `git init` <- initializing a git repository
2. Create repo on github
3. `git remote add origin <github http url>`
4. to test run `git remote -v` - shows if remote repository is connected

## HOW to create / push commits
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

## Git Merging
-  Merging is the process of combining a secondary branch with the master branch
1. Switch to branch you want to merge into (usually main branch)
2. `git merge <name of branch to merge>` - comebines secondary branch into main