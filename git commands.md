# Git Commands

## New repository
First you need to move to the place where you want to initialize the repository.

```
$ git init
$ git add <README.md>
$ git remote add origin <Link of the repository>
$ git push -u origin master
```
## New file within an existing repository
```
$ git add filename.md
$ git commit -m "<Short message>"
$ git push --set-upstream origin <branch name>
```

## Branch

### New branch 

```
$ git branch <branch_name>
```
### Move to a branch
```
$ git checkout branch
```
### Check the branches
```
$ git branch
```
### Merge a branch to master branch
```
$ git merge <branch name>
$ git push
```
### Delete a branch
```
# $ git branch -d <branch name>
```
