# Useful Git Commands
## Git
Git is a distributed version control system, very easy to learn and supper fast!

## Install Git
There are a few different ways to install git (from source or for Linux) but the purpose of this page is to focus on git commands, so I am going to assume you are installing git on a your OS.

To view other ways of installing it visit the [Git official site](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git)


## Setting up git
$ git config --global user.name "User Name"

$ git config --global user.email "email"

## Add Existing Project
- create repository name same to your existing project_name
- open your existing project in git bash
- type command: git init 
- type command: git add . (it will add all your project files to your repositories)
- type command: git remote add origin "Your_github_repository_link"
- type cammand: git branch -M main
- type cammand: git push -u origin main
