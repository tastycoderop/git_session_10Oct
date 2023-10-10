# GIT Session Readme satyam

Basic and Most Widely used commands:

```
git clone git@github.com:SanketSDeshmukh/git_session_10Oct.git
git checkout branch_name
git pull
git push

```

## Local Setup

```
git config --global user.name "Sanket Deshmukh"
git config --global user.email "sanketdeshmukh12@yahoo.com"
```

### MAC

```
ssh-keygen -t rsa -b 4096 -C "sanketdeshmukh12@yahoo.com"
cat ~/.ssh/id_rsa.pub
```

or

```
ssh-keygen -t ed25519 -C "sanketdeshmukh12@yahoo.com"
cat ~/.ssh/id_ed25519.pub
```

### Windows

open git bash
execute below commands

```
ssh-keygen -o
cat ~/.ssh/id_rsa.pub
```

## Workflow 1:

Working on an existing code repo from github
Say you want to work on a copy of main branch

```
git clone <url>
git checkout main
git checkout -b subbranch_of_main main
git commit -m 'some feature work'

```

## Workflow 2:

I am a Newbie and want to start from scratch

```
echo "# git_session_10Oct" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:SanketSDeshmukh/git_session_10Oct.git
git push -u origin main
```

## Workflow 3:

You have some code and want to start version controlling it.
Create a new repo and push your code there

```
cd your_code_path
git remote add origin git@github.com:SanketSDeshmukh/git_session_10Oct.git
git branch -M main
git push -u origin main
```

# TL;DR (I will do it myself)

https://github.com/skills/introduction-to-github

# Hello World

The seminar was awesome.
