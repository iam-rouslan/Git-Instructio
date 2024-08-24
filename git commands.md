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

*The git config command is a convenience function that is used to set Git configuration values on a global or local project level. These configuration levels correspond to . gitconfig text files. Executing git config will modify a configuration text file..*

![git-config](git-config.png)
### git init
```sh
git init [repository name]
```
*This command is used to start a new repository.*

![git-init](git-init.png)
### git clone
```sh
git clone [url]
```
*This command is used to obtain a repository from an existing URL.*

![git-clone](git-clone.png)
### git add
```sh
git add [file]
```
*his command adds a file to the staging area.*

![git-add](git-add.png)

```sh
git add *
```
*This command adds one or more to the staging area.*

![git-add-all](git-add-all.png)

### git commit
```sh
git commit -m “[ Type in the commit message]”
```
*This command records or snapshots the file permanently in the version history.*

![git-commit](git-commit.png)

```sh
 git commit -a
```
*This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.*

![git-commit-all](git-commit-all.png)

### git diff
```sh
git diff
```
*This command shows the file differences which are not yet staged.*

![git-diff](git-diff.png)

```sh
git diff -staged
```
*This command shows the differences between the files in the staging area and the latest version present.*

![git-diff-staged](git-diff-staged.png)

```sh
git diff [first branch] [second branch]
```
*This command shows the differences between the two branches mentioned.*

![git-diff-branches](git-diff-branches.png)

### git reset
```sh
git reset [file]
```
*This command unstages the file, but it preserves the file contents.*

![git-reset](git-reset.png)

```sh
git reset [commit]
```
*This command undoes all the commits after the specified commit and preserves the changes locally.*

![git-reset-commit](git-reset-commit.png)

```sh
git reset –hard [commit]
```
*This command discards all history and goes back to the specified commit.*

![git-reset-hard](git-hard-reset.png)

### git status
```sh
git status
```
*This command lists all the files that have to be committed.*

![git-status](git-status.png)

### git rm
```sh
git rm [file]
```
*This command deletes the file from your working directory and stages the deletion.* 

![git-rm](git-rm.png)

### git log
```sh
git log
```
*This command is used to list the version history for the current branch.*

![git-log](git-log.png)

```sh
git log –follow[file]
```
*This command lists version history for a file, including the renaming of files also.*

![git-log-follow](git-log-follow.png)

### git show
```sh
git show [commit]
```
*This command shows the metadata and content changes of the specified commit.*

![git-show](git-show.png)

### git tag
```sh
git tag [commitID]
```
*This command is used to give tags to the specified commit.*

![git-tag](git-tag.png)

### git branch
```sh
git branch
```
*This command lists all the local branches in the current repository.*

![git-branch](git-branch.png)

```sh
git branch [branch name]
```
*This command creates a new branch.*

![git-create-branch](git-create-branch.png)

```sh
git branch -d [branch name]
```
*This command deletes the feature branch.*

![git-delete-branch](git-delete-branch.png)

### git checkout
```sh
git chekcout [brnach name]
```
*This command is used to switch from one branch to another.*

![git-checkout](git-checkout.png)

```sh
git checkout -b [branch name]
```
*This command creates a new branch and also switches to it.*

![git-create-branch-switch](git-create-branch-switch.png)

### git merge
```sh
git merge [branch name]
```
*This command merges the specified branch’s history into the current branch.*

![git-merge](git-merge.png)

### git remote
```sh
git remote add [variable name] [Remote Server Link]
```
*This command is used to connect your local repository to the remote server.*

![git-remote](git-remote.png)

## git push
```sh
git push [variable name] master
```
```sh
git push [variable name] [branch]
```
*This command sends the branch commits to your remote repository.*

![git-push](git-push.png)

![git-push-02](git-push-02.png)

```sh
git push –all [variable name]
```
*This command pushes all branches to your remote repository.*

![git-push-all](git-push-all.png)

```sh
git push [variable name] :[branch name]
```
*This command deletes a branch on your remote repository.*

![git-push-delete](git-push-delete.png)

### git pull
```sh
git pull [Repository Link]
```
*This command fetches and merges changes on the remote server to your 
working directory.*

![git-pull](git-pull.png)

### git stash
```sh
git stash save
```
*This command temporarily stores all the modified tracked files.*

![git-stash-save](git-stash-save.png)

```sh
git stash pop
```
*This command restores the most recently stashed files.*

![git-stash-pop](git-stash-pop.png)

```sh
git stash list
```
*This command lists all stashed changesets.*

![git-stash-list](git-stash-list.png)

```sh
git stash drop
```
*This command discards the most recently stashed changeset.*

![git-stash-drop](git-stash-drop.png)
