#Create a new repository on the command line

- 1-echo "# git-bash-command-line-for-github" >> README.md
- 2-git init
- 3-git add README.md
- 4-git commit -m "first commit"
- 5-git branch -M main
- 6-git remote add origin https://github.com/Arryan-n/git-bash-command-line-for-github.git
- 7-git push -u origin main

##push an existing repository from the command line

- 1-git remote add origin https://github.com/Arryan-n/git-bash-command-line-for-github.git
- 2-git branch -M main
- 3-git push -u origin main

###How to Uninitialize a Git Repository

- 1-rm -rf .git

#### How to create a branch in git repo

- git checkout -b development

#### How to make a clone of repo in your local pc

- git clone (add here the HTTPS link from the repo of github)
- then a folder of the default name same as your repo will be created in desktop
- open in your vs code make some changes
- track those changes through (git status)

* git add (file name) Commandline.md or git add .

- git commit -m 'adding comment here it will be shown'
- git push origin master
