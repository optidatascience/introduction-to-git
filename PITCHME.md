# Git and GitHub

a free and open source distributed version control system

---
### Git vs GitHub

- *Git*: the tool to create/manage repository. like SVN
- *GitHub*: repository hosting. http://www.github.com (free) http://github.optum.com (enterprise)

---
### How Git works

![Git Command Flow](https://kevintshoemaker.github.io/StatsChats/GIT2.png)

---
### How to Collabrate

![Collabration](https://kevintshoemaker.github.io/StatsChats/GIT1.png)

---
### Get Started

- Setup
 - Install Git from Appstore
 - Request Github access from Secure
 
- Git Config (do it once and done)
 ```
  git config --global user.name "Liang Zhou"
  git config --global user.email "liang.zhou@optum.com"
 ```
 
---
### Step 1. Create a repo
 - initiate
 ```
  git init
 ```
 
 - clone an existing repo
 ```
  git clone git@github.optum.com:lzhou10/introduction-to-git.git
 ```
 
---
### Step 2. Stage files
 ```
  git add filenames.txt filesnames.sas filesnames.R
 ```
 
 - Check status
 ```
  git status
 ```
 
---
### Step 3. Commit
 - Write commit messages (very important)
 ```
  git commit -m "messages here"
 ```
 
 
 
 
 
