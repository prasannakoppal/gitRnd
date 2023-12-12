# gitRnd
This is an testing GIT Repository

## * Clone **************************
```bash
git clone gitRepoURL
```

## Clone Specific Branch
```bash
git clone -b branchName origin/gitRnd.git
```
#### Eg
```bash
git clone -b branchName https://github.com/prasannakoppal/gitRnd.git
```

## Pull
```bash
git pull
```

## Status
```bash
git status
```

## Commit
### Add
```bash
git add fileName 
```

```bash
git add *
```

### Commit
```bash
git commit -m "informative message about the commit"
```

## Revert back in commits

## Hard Reset: Reset all changes
```bash
git reset --hard
```

# Branch

## Branch List
```bash
git branch
```

## Checkout Branch (Create New Branch)
```bash
git checkout -b childBranchName ParentBranchName
```
###Eg
```bash
git checkout -b feature/123/issue-show-2-proponent dev
git checkout -b issue/256/issue-bug dev
```

## Switch Branch 
```bash
git checkout branchName
```
## Rebase Branch 
```bash
git rebase parentBranch
```

## Merge Branch 
```bash
git merge childBranchName
```
#### Eg
```bash
git merge feature/123/issue-show-2-proponent
```

## Delete Branch
```bash
git branch -d source-branch
```

## Push Branch to Remote (Cloud)
```bash
git push origin featureBranchName:featureBranchName
```

## Checkout File 
```bash
git checkout HEAD -- fileName
```


## Switch
```bash
git fromMaster
```

```bash
git remote -v
```