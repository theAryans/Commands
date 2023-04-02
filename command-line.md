Create a new repository on the command line

echo "# git-bash-command-line-for-github" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Arryan-n/git-bash-command-line-for-github.git
git push -u origin main

push an existing repository from the command line

git remote add origin https://github.com/Arryan-n/git-bash-command-line-for-github.git
git branch -M main
git push -u origin main

How to Uninitialize a Git Repository

rm -rf .git
