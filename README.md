# Git flow

## New Project

### Create develop branch and switch to it
```
git checkout -b develop
```
### Push all of develop commits into develop branch
```
git push -u origin develop
```

### Create feature branch and switch to it
```
git checkout develop
```
```
git checkout -b feature
```

### Work on feature ...

### Merge feature branch with develop branch
```
git checkout develop
```
```
git merge feature
```

### Delete feature branch
```
git branch -D feature
```

### Create release branch and switch to it
```
git checkout develop
```
```
git checkout -b release/0.1.0
```

### Merge release branch with master branch
```
git checkout master
```
```
git merge release/0.1.0
```

### Create hot-fix branch to fix any issues in master branch
```
git checkout master
```
```
git checkout -b hot-fix
```

### Work on fix master branch issues ...

### Merge hot-fix branch with master branch
```
git checkout master
```
```
git merge hot-fix
```

### Merge hot-fix branch with develop branch
```
git checkout develop
```
```
git merge hot-fix
```

### Delete hot-fix branch
```
git branch -D hot-fix
```