```
* git add `some_file`
* git commit -m "comments"
* git push
```

```
* git checkout -b `new_branch_name`
```

```
* git branch
* git status
```

```
* git push origin -u remote_branch_name (to set up remote branch tracking)
```

```
* git push origin --delete branch_name (cmds followed to clean up upstream tracking)
* git status
* git branch --unset-upstream
```

```
* git remote update origin --prune (update list of remote tracking branches)
```

```
* git push origin localBranchBeingWorkedOn:mainline (push changes on local working branch to destination branch)
```

```
* git branch -D branch_name (locally)
* git branch -d branch_name (if safe)
```

```
* git branch -u origin/mainline (set up to track origin master)
* git branch --unset-upstream (to untrack)
* git branch -vvv (to see latest commits of each branch)
* git push origin BranchName:masterBranch
```

```
* git fetch origin
* git checkout branch-name (fix-resource-leak)
```

```
* git rebase -i HEAD~number

* git reset --hard HEAD~number 
* git push --force
```

```
* git pull 
* git merge master
* git rebase master (on top of git pull from master and add new stuff from this branch to it)
```

---

***Starting new repo***
```
1. Create new repo from the command line
   
echo "# NameOfRepo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/jhkuang111/NameOfRepo.git
git push -u origin main
```

```
2. Push an existing repository from the command line

git remote add origin https://github.com/jhkuang111/NameOfRepo.git
git branch -M main
git push -u origin main
```
