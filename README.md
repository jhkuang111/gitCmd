some git commands

git add some_file
git commit -m "comments"
git push

git checkout -b branch_name

git branch
git status

git push origin -u remote_branch_name (to set up remote branch tracking)

git push origin --delete branch_name (cmds followed to clean up upstream tracking)
git branch -D branch_name
git branch -d branch_name (if safe)

git reset --hard HEAD~number
git push --force

git pull
git merge master