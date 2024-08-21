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

### git log
```sh
git log
```
*This command is used to list the version history for the current branch.*

```sh
git log –follow[file]
```
*This command lists version history for a file, including the renaming of files also.*

### git show
```sh
git show [commit]
```
*This command shows the metadata and content changes of the specified commit.*

### git tag
```sh
git tag [commitID]
```
*This command is used to give tags to the specified commit.*

### git branch
```sh
git branch
```
*This command lists all the local branches in the current repository.*

```sh
git branch [branch name]
```
*This command creates a new branch.*

```sh
git branch -d [branch name]
```
*This command deletes the feature branch.*

### git checkout
```sh
git chekcout [brnach name]
```
*This command is used to switch from one branch to another.*

```sh
git checkout -b [branch name]
```
*This command creates a new branch and also switches to it.*

### git merge
```sh
git merge [branch name]
```
*This command merges the specified branch’s history into the current branch.*

### git remote
```sh
git remote add [variable name] [Remote Server Link]
```
*This command is used to connect your local repository to the remote server.*

## git push
```sh
git push [variable name] master
```

```sh
git push [variable name] [branch]
```
*This command sends the branch commits to your remote repository.*

```sh
git push –all [variable name]
```
*This command pushes all branches to your remote repository.*

```sh
git push [variable name] :[branch name]
```
*This command deletes a branch on your remote repository.*

### git pull
```sh
git pull [Repository Link]
```
*This command fetches and merges changes on the remote server to your working directory.*

### git stash
```sh
git stash save
```
*This command temporarily stores all the modified tracked files.*

```sh
git stash pop
```
*This command restores the most recently stashed files.*

```sh
git stash list
```
*This command lists all stashed changesets.*

```sh
git stash drop
```
*This command discards the most recently stashed changeset.*