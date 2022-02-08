# Learning Git

Useful commands that I used when I was learning Git & GitHub. I hope they are also useful to you!

### Working in the staging area (local)

**Add files**
```
git add file_name
git add .
git add -A
```

**Delete files**
```
git rm --cached file
git rm -r --cached .
```

**View status**
```
git status
```

### Working in the commit history area (local)

**Add files**
```
git commit -m "Message"
```

**View state**
```
git log
```

**View details of one commit**
```
git show commit_id
```

**View differences**
```
git diff
```

**Restore file from the last commit**
```
git restore file_name
```

**Change the message of the last commit**
```
git commit --amend -m "Correct message"
```

