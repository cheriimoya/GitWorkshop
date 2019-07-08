The power of .gitignore
===

~~~

- is also version controlled
- you can have multiple .gitignores
- either whitelist or blacklist stuff
- keeps your repo nice and small
- please don't upload binary files

~~~

## Example
```
node_modules/
*.class
/**/bin/
/*/lib/
!/bin/important/
```

---

The power of .gitconfig
===

~~~

## Configure your git
git checks
- /etc/gitconfig (global)
- ~/.gitconfig (user level)
- $GIT_DIR/config (repo specific)

~~~

## Example git config
```
[user]
    name = John Doe
    email = J.D@example.com
[alias]
    d = difftool --tool=vimdiff
    graph = log --graph --oneline --decorate=short --branches='*'
[credential]
    helper = cache --timeout=3600000
```
