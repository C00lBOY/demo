## This is the Git tutorial by Darshan Patil
## 1st thing you have to do is setting global variables by using following command.
git config --global user.email "your_email_id"
git config --global user.name "your_user_name"

## 2nd thing you can change your master branch to main.
git branch  ---> to check your branch name
git branch -M main ---> chanage your master branch to main

## 3rd thing you can do is to add 
git remote add origin "URL" ---> this URL is the place where we will be doing commits.
git remote -v  ---> it will show us the fetch and push branch. & This has been set because of above command.


## 1. git init  ---> initializing new empty repository
## 2. git status ---> it show tracked and untracked files
## 3. git add .           ---> for tracking the files
## 4. git commit -m "Commit massage"  ----> after commit all file goes to staging environment
## 5. git push -u origin main  ----> pushing the file to the production environment (pushing the file from origin to main OR These all files will go to the github repository)

## Lets work on branch
1. git branch  ---> shows all available branches
2. git branch "branch_name"  ---> this will create new branch with "branch_name" which is replica of main branch.
3. git checkout "branch_name" ---> now i am working on developer branch ie."branch_name"
4. NOTE: if you commit in developer branch the changes you do will not be visible in main branch, if you want to see all the changes you need to merge the developer branch to main branch using below commad.
 first come to main branch then 
 5. git merge Developer_branch  
   now the changes are visible from main branch
6. git log ---> record of commits OR History of everything that happens to the repository
   git log -p ---> detailed history of commits
   press q for quit if you are stuck.
7. git branch -d Developer1  ---> this will delete the Developer1 branch

Now,
Go the demo repository -- setting -- collaborator --add email
1. after adding email that new developer can get invite , after accepting invite he/she can fork the repository and can able to make the commit and push the changes by creating pull request.
2. This pull request will get to the base user after verifying the changes made by the developer the base user can merge that pull request.
3. This is how team work is done swiftly.
4. pull request ---> pull request is to get the latest version and merge into main repository(Production Environment)