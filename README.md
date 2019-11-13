## Git Branching Practice

### Basic `git` commands

* `git init` - create local repo
* `git add .` - add current working directory to git index
* `git commit -m "message"` - commits changes to local rep

### Basic Branching
* `git branch branchName` - Crete local branch `branchName`
* `git checkout branchName` - Move to branch `branchName`
* `git branch` - Display local branch which we are on
* `git checkout -b newBranch` - Create and check out branch `newBranch`
* `git status` - display status of local repo

### Merging
* Add and commit local brach.
* Push local branch to remote.
* Pull `master` from remote into local branches
```bash
git checkout newBranch
git pull origin master
```
* Resolve merge conflicts
* Commit and push local branch
``` bash
git add .
git commit -m 'Merging master with newBranch'
git push origin newBranch
```
* On Github , create Pull Request
* Teammates merge Pull Request into master.
