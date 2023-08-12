# Steps to upload any project on githun for the first time
- Step 1  Go to github.com and create a repository by clicking on plus icon, in the name of repository use the same name of the local folder on your computer.
- Step 2  After creating the repository you will see the below commands
```
echo "# Learning-Documentation" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/isr-project-one/Learning-Documentation.git
git push -u origin main
```

- Step 3 open git scm on the folder which you want to upload on git.
- Step 4 use **git  init** command
- Step 5 use **git add .**
- Step 6 use **git commit -m "first commit"**
- Stpe 7 use below command to set  your email and authenticate yourself. Note: this step is use only once
```
- git config --global user.email "you@example.com"
- git config --global user.name "Your Name"
```
- Step 8 use **git remote add origin https://github.com/isr-project-one/Learning-Documentation.git** to locate your remote repository
- Step 9 **git push -u origin master**
