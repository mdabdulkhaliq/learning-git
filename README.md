# learning-git

git clone ...
git status
git add .
git commit -m "..."
git push origin master (works when we have cloned since origin is set here)

git init
git remote add origin ... (point to a git repo)
git push -u origin master (use to set upstream, next time we dont need to type 
origin master and just use git push)

git branch
git checkout -b "featurebranchname" - To create a new branch
git checkout featurebranchname - To switch between branches

Make necessary changes on branches, add, commit. 
Go back to master

git diff featurebranchname - to view differences between current branch(master) and given branch

In order to push a branch to git we need to set origin because git needs to know origin
git push --set-upstream origin featurebranchname

If we goto git hub can can create a pull request to merge the branch to master
Once PR is created and merged, we need to update our local machine code using pull

git pull origin master or git pull

git branch -d featurebranchname

for a modified file (not newly added) we can add and commit at same time
git commit -am "..."

get all latest from master , goto featurebranch
git diff master
git merge master

git reset - to remove staged changed (via git add)
git reset HEAD~1 (uncommit and unstage to one version back done via git commit)

git log
git reset commitno (will have changes done but not staged or commit)

git reset --hard commitno (hard reset to previous version)
