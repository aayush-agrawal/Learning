
# Git Commands

#### _How to check your git configuration:_
```git config --list```

#### _How to setup your git username and email:_
```git config --global user.name "Aayush Agrawal"```
```git config --global user.email "agrawal.aayushn91@gmail.com"```

#### _How to initialize a git repo:_
```git init```

#### _How to add a file to the staging area:_
``` git add filename```

#### _How to add all file to the staging area:_
``` git add .```

#### _How to see the changes_
```git add -p```

#### _How to add only certain  files to the staging area:_
```git add filena*```

#### _How to commit changes:_
```git commit -m "message"```

#### _How to add track files to staging area and commit changes:_
```get commit -am "message"```

#### _How to see the commit history:_
```git log --oneline --graph```

#### _How to see a specific commit:_
```git show commit_id```

#### _How to see changes made before committing them:_
```git diff```
```git diff filename```
```git diff --staged```




git stash
git stash pop
git stash save "message"
git stash list
git stash apply 0


git status
git add .
git commit -m "message"
git commit -am "message"
git add file
git add -p

git push
git push remote branch
git push remote branch --set-upstream

git resest --soft HEAD~1
git commit --amend -m "message"
git revert hash

git log --graph --oneline