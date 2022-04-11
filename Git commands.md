# Git commands
* Use GitBash in Windows
* Configuration
```
git config --global user.name ""
git config --global user.email ""
```
* Getting started with a project. Create a repository in Github for the project before starting.
```
git init
git add .
git commit -m "Commit"
git remote add origin "https"
git push -u origin main
```
* Create a personal access token in github account to enable push (if link is https, SSH link needs SSH keys added to the account)
settings ->developer settings->Generate new token

Push asks for password and give the access token in place of password

* Forking
fork -- creates a copy in our github, clone it, change it, push back and make a pull request
```
git clone "https"
git add .
git commit -m ""
git push -u origin
```
* Branching (See that the folder containing project changes with branching)
Create branch
```
git branch mybranch
```
Change to branch
```
git checkout mybranch
```
Merge when work is finished (merge from main branch)
```
git checkout main
git merge mybranch -m ""
```

* Pulling to update local repository with changes in the remote (important when another contributor made a relevant change that gets merged)
```
git pull
```
Might open editor
Press ESC and type :q to quit the editor
Always makes sure to pull after committing changes in the local repo
