## Practicising Git commands
all comands in terminal
1. ## git init
-> makes a existing folder as git repo it create a hidden folder called .git all information stored in it code changes branch.....
# U symbol untracked 
-> add this file in repo(git add filename) for tracking -> A
# A symbol
-> file added to track
# M

2. ## git add README.md
    Adds readme file to track changes

3. ## git commit -m "this is my first commit"
files goes in stagging area
changes commit ho gya hai

# M-> modified 
modification done in your file and recorded in .git

## git branch
show all branches  change it to main to push in main

## git branch -M main
master by default ko main bana diya

## git remote add origin (url)
git remote add origin git@github.com:shubhkr72/repo_name.git
// url should be https not ssh**
add origin of of repo
is git ko url repo  se connect

## git remote -v
to get push and fetch url

## git push origin main
pushes your code to main branch of repo
but if you are pushinng it first time it will give error
{Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.}

to resolve this you must have to set up your github profile


## SETUP

means add your account to this remote url so that it can track who is pushing
1. ## git config --global user.name "firstName,lastName"

provide email
2. ## git confing --global user.email "email"

to find you in global list
{C:\Users\shubh\Desktop\AMLZ\Git Commands>git config --global --list
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
user.email=youremail@gmail.com
user.name=your name}


all set go for other concepts 

created a new file in github but it is not is in local how to do that
pull request
1. ## git pull origin main
pull newly added file to local

Branching strategy
1. ## git branch branchname(dev1)
created branch beanchname(dev1)
it is exact replica of main branch

2. ## git checkout branchname(dev1)
switch to branchname(dev1)

## git branch 
for checking which branch are you in

