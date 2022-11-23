# This is the Git tutorial by Darshan Patil
# 1st thing you have to do is setting global variables by using following command.
git config --global user.email "your_email_id"
git config --global user.name "your_user_name"

# 2nd thing you can change your master branch to main.
git branch  ---> to check your branch name
git branch -M main ---> chanage your master branch to main

# 3rd thing you can do is to add 
git remote add origin "URL" ---> this URL is the place where we will be doing commits.
git remote -v  ---> it will show us the fetch and push branch. & This has been set because of above command.


# 1. git init  ---> initializing new empty repository
# 2. git status ---> it show tracked and untracked files
# 3. git add .           ---> for tracking the files
# 4. git commit -m "Commit massage"  ----> after commit all file goes to staging environment
# 5. git push -u origin main  ----> pushing the file to the production environment (pushing the file from origin to main OR These all files will go to the github repository)