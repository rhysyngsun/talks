## Intermediate Git
sdfsdf

## Adding files

```
git add --all .
git add :/
```



## Working with stash

set aside temporary changes without a branch

```
git stash
git stash list
git stash show
git stash pop
git stash clear
```



## Local branches FTW

```
# in 'development' branch
git checkout -b attempt_fix
# Make a fix
git checkout development
git merge attempt_fix
```



## Rebase pull to reduce merge commits

```
git pull --rebase
```
test
