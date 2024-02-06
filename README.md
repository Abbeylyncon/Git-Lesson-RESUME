# Git-Lesson-Resume  
## This is an introductory class into Git and Github, the objective was to push an index.html file from Git to Github  
- Download Gitbash https://git-scm.com/downloads
## Configure Gitbash  
- Configure username git config --global user.name "Username"
- Configure email git config --global email "Email"
## Prepare the working environment  
- Create a directory -mkdir"directory name"
- Enter the directory -cd "directory name"
- Create an index.html using touch index.html
- Initialize the working environment using Git init
## Clone remote Repo  
- Create a repo for the project
- Git remote add origin url "https://github.com/Abbeylyncon/Git-Lesson-RESUME.git"
## Work with the project file  
- Edit the index.html file using vim index.html
- Check the status with regards to the statging area using git status
- Add the file to the staging area using git add "filename"
- Add a commit message using the command git commit -m "file name"
## Push to the remote repo  
- To push to the remote repo we use git push origin master  
