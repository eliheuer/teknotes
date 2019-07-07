# Rebase

Rebasing is taking all your branch's commits and adding them on top of commit 
A instead of commit B. If you consider commit A as the "base" of your branch, 
you're changing that base to the most recent one, commit B. Thus, the name rebasing.

```
git checkout master
git pull
git checkout <branch>
```

Basic structure:
```
git rebase <branch>
git rebase master
git push --force-with-lease
```
