# Basics

**Show status -> list files (changed, not already added to index), shows branch**
```
git status
```

**Show changes in file**
```
git diff <file>
```

**Add all files to index**
```
git add <file>
```

**Commit changes**
```
git commit -m <message>
```

# Branching

**Create branch**
```
git branch <branch>
````

**Switch to branch**
```
git checkout <branch>
```

**Merge to master**
```
git checkout master
git merge <branch>
````

**Delete branch**
```
git branch -D <branch>
```

# Remote Repositories

**Push branch to remote repository**
```
git push origin <branch>
```

**Pull changes from branch**
```
git pull orign <branch>
```

**Clone branch**
```
git clone --single-branch --branch <branch> <repository>
```