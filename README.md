# GENERAL INSTRUCTIONS
- [AWESOME GIT GUIDE!](http://rogerdudler.github.io/git-guide/)
- [AWESOME GIT TUTORIAL (gitimmersion)](http://gitimmersion.com/index.html)
- [GitLab Collaboration](http://rkd.zgib.net/scicomp/git-collaboration/gitlab-and-collaboration.html)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


# CREATING A NEW REPO

- First manually create a repo "NewRepsitory" on github.com/new. 
- UNCHECK "Initialize this repository with a README".
- Create a new folder "NewRepsitory" on your local machine.
- Go to this folder, right click and select git bash. 
- Then follow the codes below 

```
touch README.md
git init
git add README.md
git status
git commit -m "first commit"
git remote add origin https://github.com/isnehil/NewRepsitory.git
git push -u origin master
```
To add more files:

```
git add newFile.py
git status
git commit -m "file added"
git push -u origin master
```

# CLONING A GITHUB REPO TO LOCAL MACHINE 

- Go to the folder on your local machine where you want to clone the online repo.
- right click and select git bash. Then type:

```
git clone https://github.com/schacon/simplegit.git
```

# UPDATING EXISTING LOCAL MACHINE REPO  AFTER MAKING CHANGES TO GITHUB REPO ONLINE 

- Go to  existing folder on your local machine where your repo exists.
- right click and select git bash. Then type:

```
git pull
```
