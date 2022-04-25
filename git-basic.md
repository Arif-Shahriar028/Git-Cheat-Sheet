## Basic Git Command

Topic Covered: 

*  <a href = "https://github.com/Arif-Shahriar028/Git-Cheat-Sheet/blob/main/git-basic.md#configuaration-git"> Configuaration git </a>
*  <a href = "https://github.com/Arif-Shahriar028/Git-Cheat-Sheet/blob/main/git-basic.md#initialize-git"> Initialize git </a>
*  <a href = "https://github.com/Arif-Shahriar028/Git-Cheat-Sheet/blob/main/git-basic.md#git-branch"> Git Branch </a>
*  <a href = "https://github.com/Arif-Shahriar028/Git-Cheat-Sheet/blob/main/git-basic.md#check-status"> Check Status </a>
*  <a href = "https://github.com/Arif-Shahriar028/Git-Cheat-Sheet/blob/main/git-basic.md#add-and-commit"> add and commit </a>
*  <a href = "https://github.com/Arif-Shahriar028/Git-Cheat-Sheet/blob/main/git-basic.md#git-remote"> Git remote </a>



###  Configuaration git
---

```
$ git config --global user.name "King Kong"
$ git config --global user.email "king-kong@gmail.com"
```

### Initialize git
---

To initialize a git:
```
$git init
```

### Git Branch
---

* Change default branch master to main:
```
$ git branch -m master main
```

*  Creat new branch:
```
$ git branch branch_name
```

* Switch to another existed branch :
```
$ git checkout branch_name
```

* Create a branch and instanly enter on it (by default you are in master branch and if you want to work with other branch):
```
$ git checkout -b branch_name
```

* Change current branch name :
```
$ git branch -m <newname>
```

* change any branch name:
```
$ git branch -m <oldname> <newname> 
```

* push the local branch and reset the upstream branch:
```
$ git push origin -u <newname> 
```

* if you want to Delete the remote branch:
```
$ git push origin --delete <oldname>
```

### Check Status
---

* To check the status about your local repo:
```
$ git status
```

### 'add' and 'commit'
---

* Add specific item:
```
$ git add file_name
```

* To add all item in git:    
```
$ git add .
```

* commit the files:

```
$ git commit -m "commit message"
```

* commit file on previous message

```
$ git commit --amend --no-edit
```

### Git Remote
---

* To connect with remote git
```
$ git remote add origin repo_link
```

* Push commits to remote:
```
$ git push -u origin branch_name
```

* To up-to-date local git:
```
$ git pull
```

* To up-to-date local git from any branch
```
$ git pull origin branch_name
```

* To remove remote:
```
$ git remote remove origin
```

* To replace remote: 
```
$ git remote set-url origin git://new.url.here
```


