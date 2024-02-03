git branch -a all
git branch -r remote
git branch -l local

git fetch --prune // removes deleted branches in local

# Github

master vs origin/master

git remote -v

git checkout origin/master => it gets you to detached head

git add -a -m "foo "

git checkout origin/x => detach HEAD
===> git switch x

## git fetch vs git pull

git pull < remote > // default is origin

git fetch origin master === git fetch master
this Updates origin/master but not master

pull => updates our working directory
git pull = git fetch + git merge

it matters where you pull its where the merge happens

git pull => // git pull origin EXISTING-BRANCH

### github pages

username.github.io/repo-name

work flow

- centeralize
- feature branches
