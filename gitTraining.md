#########This is a file with git commands#########

#########Create a branch and push changes 

git checkout -b <branch-name>

#########To check the repo status 

git status

#########To stage the changes 

git add -A --> will stage all the changes 

git add your-file-name-with-extension --> will add that specific file

#########To commit your changes 

git commit -m "your commit message"

#########To push the code to your remote branch

git push 

#########To force push your commt 

git push -f

#########To push a commit while creating a new branch  

git push --set-upstream origin your-branch-name