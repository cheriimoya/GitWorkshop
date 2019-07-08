Advanced usage of git
===

~~~

## git diff
- see all kinds of different changes
- I use it a LOT!
- better use `git difftool`

~~~

## git log
- get insight into the commit history
- go pro with the `--graph` and `all` option

~~~

## git stash
- 'stash' away changes made to tracked files
- a stash can have a name
- a stash can be worked with like a commit
- a stash is kept on a stack

~~~

## git stash
- use `git stash --all` to also stash untracked files
- you can show differences and changes with git diff
- `git stash apply` to keep stash on the stack
- `git stash pop` to remove stash from the stack

~~~

## git rebase
- to change the origin of a branch
```
      A---B---C topic *
     /
D---E---F---G master
=====git rebase master========
              A'--B'--C' topic *
             /
D---E---F---G master
```

~~~

## git cherry-pick
- apply specific commit
- apply this commit patch like
