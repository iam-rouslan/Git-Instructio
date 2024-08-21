# Here are the Git commands which are being covered:

- **git cofig**
- **git init**
- **git clone**
- **git add**
- **git commit**
- **git diff**
- **git reset**
- **git status**
- **git rm**
- **git log**
- **git show**
- **git tag**
- **git branch**
- **git checkout**
- **git merge**
- **git remote**
- **git push**
- **git pull**
- **git stash**

## Git Commands

### git config

```sh
git config –global user.name “[name]”
```
```sh
git config –global user.email “[email address]”
```
*This command sets the author name and email address respectively to be used with your commits.*

### git init
```sh
git init [repository name]
```
*This command is used to start a new repository.*

### git clone
```sh
git clone [url]
```
_This command is used to obtain a repository from an existing URL._

### git add
```sh
git add [file]
```
_his command adds a file to the staging area._

```sh
git add *
```
_This command adds one or more to the staging area._

### git commit
```sh
git commit -m “[ Type in the commit message]”
```
_This command records or snapshots the file permanently in the version history._

```sh
 git commit -a
```
*This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.*

### git diff
```sh
git diff
```
*This command shows the file differences which are not yet staged.*

```sh
git diff -staged
```
*This command shows the differences between the files in the staging area and the latest version present.*

```sh
git diff [first branch] [second branch]
```
*This command shows the differences between the two branches mentioned.*

### git reset
```sh
git reset [file]
```
*This command unstages the file, but it preserves the file contents.*

```sh
git reset [commit]
```
*This command undoes all the commits after the specified commit and preserves the changes locally.*

```sh
git reset –hard [commit]
```
*This command discards all history and goes back to the specified commit.*

### git status
```sh
git status
```
*This command lists all the files that have to be committed.*

### git rm
```sh
git rm [file]
```
*This command deletes the file from your working directory and stages the deletion.*

