## The basic git commands (and what they do)

~~~

## git clone
- used to clone (copy) a repository
- use `git clone <directory>` to change target dir

~~~

## git checkout
- `git checkout <branchname>` to switch branches
- `git checkout -b <branchname>` to create new (local) branch from HEAD

~~~

## git pull
- pushes local commits to the remote
- `git push origin master` push directly to master
- dont push to master!
- use `--force` or `-f` if you really want to
~~~

## git add
- used to push local changes to the index
- `git add .` is not good
- use `git add <filename>` or `git add -p`
- or use your favourite IDE ;)

~~~

## git commit
- to commit changes from the index
- `git commit -m <message>`
- even better, use `git commit -v`

~~~

## git push
- pushes local commits to the remote
- `git push origin master` push directly to master
- dont push to master!
- use `--force` or `-f` if you really want to
