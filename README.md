# git and github

## 1 init the first commit
1. `git init`
2. `git add .`
3. `git commit -m 'first'`

## 2 add some commit
1. `git add .`
2. `git commit -m 'first'`

## 3 push to github
1. `git remote add origin git@github.com:isKage/git_tutorial.git`
2. `git push -u origin main`
3. enter your key
> note: ssh key

## 4 change and push to github
1. `git push (or: git push --all)`
2. enter your key

## 5 change and pull from github
1. `git pull --ff-only`
2. enter your key

## 6 git pull = git fetch + git merge
1. `git fetch`
2. enter your key
3. `git checkout main`
4. `git merge origin/main --ff-only`
