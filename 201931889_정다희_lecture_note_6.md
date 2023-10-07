# Lecture 6 _ Git

git cinfigureations are stored in three levels
```
(1) system level : --system option. affects on the system
file : /etc/gitconfig
(2) global (user) level : --global option. affects all repositories of current user
file : ~/.config/git/config
(3) local level : --local option. specific to the current repository
file : .git/gitconfig
```
each level overrides values in the previous level : system -> global -> local

---
$ git config --global user.name "dahee Jeong" 

$ git config --global user.email avecamour3717@gmail.com

$ git config --global init.defaltBranch main

checking configration 

=> $ git config --list / $ git config (user.name / user.email)

---
- $ git init ; initializing a repository in an existing directory
- $ git status ; checking repository status
- $ git add[file_name] ; adding a new file to be staged
- $ git add . ; adding all files to be staged
- $ git rm - cached[file_name] ; unstaging a file
- .gitgnore file ; ignoring a file
- $ git commit -m "commit message" ; commit
- $ git branch -m (current name)(change name) ; change branch name
