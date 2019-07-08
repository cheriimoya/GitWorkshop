Merge conflicts
===

~~~

## Why do they exist?
<div class="fragment">![cardib](https://media.giphy.com/media/fGOjgWRzQkC2sHHnq7/giphy.gif)</div>

~~~

- A team is working on different branches
- branching happened from the same ancestor
- Same file gets edited on the same line(s)

~~~

## How to spot them
1) merge conflicts add markers
```
this is the first line
<<<<<<< HEAD
i'm a happy hippo
=======
i'm a unicorn
>>>>>>> bob
3rd line ...
```

~~~

2) Git tells you about them while merging
```
Auto-merging document
CONFLICT (content): Merge conflict in document
Automatic merge failed; fix conflicts and then commit the result.
```

~~~

3) And when using `git status`
```
Git status:
On branch master
You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)

	both modified:   document

no changes added to commit (use "git add" and/or "git commit -a")
```

~~~

## How to resolve them
- git mergetool
- your favourite editor
- saving your code, clone the repo again and apply the changes

~~~

## Live demo

