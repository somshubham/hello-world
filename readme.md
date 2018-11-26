# Git Commands -- version control. 

### Get the git version.
* `git --version`

### Get the default user name and email.
* `git config user.name`
* `git config user.email`

### Set the default user name and email.
* `git config --global user.name "Som Shubham Sahoo"`
* `git config --global user.email "somshubhams@gmail.com"`

### Some folder cmd option
* `mkdir "folder name"`
* `rmdir "folder name"`
* `ls`

### Initialize The Git
* `git init`

### Check Git repository
* `git status`

### Git add files and folder
* `git add filename/foldername`
* `git add .`  will add all the changes 

### View changes mnade in git repo
* `git diff filename`

### Git commit files
* `git commit -m "Your commit msg"`

### To add a remote named 'origin' to your repository:
* `git remote add origin <URLFROMGITHUB>`
* `git remote set-url origin <URLFROMGITHUB>`

### To push the changes to a branch
* `git push origin branchname`