# Here are the Git commands which are being covered:

Так что _main^_ означает "первый родитель ветки main".

_main^^_ означает прародитель (родитель родителя) _main_
Чтобы перейти надо написать : __git checkout main^__


1. **git cofig**
2. **git init**
3. **git clone**
4. **git add**
5. **git commit**
6. **git diff**
7. **git reset**
8. **git status**
9. **git rm**
10. **git log**
11. **git show**
12. **git tag**
13. **git branch**
14. **git checkout**
15. **git merge**
16. **git remote**
17. **git push**
18. **git pull**
19. **git stash**

## Git Commands

### git config

```sh
git config –global user.name “[name]”
```
```sh
git config –global user.email “[email address]”
```

*The git config command is a convenience function that is used to set Git configuration values on a global or local project level. These configuration levels correspond to . gitconfig text files. Executing git config will modify a configuration text file..*

![git-config](git-photo/git-config.png)
### git init
```sh
git init [repository name]
```
*The git init command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository. Most other Git commands are not available outside of an initialized repository, so this is usually the first command you'll run in a new project.*

![git-init](git-photo/git-init.png)
### git clone
```sh
git clone [url]
```
*This command is used to obtain a repository from an existing URL.
The git clone command copies an existing Git repository.*

![git-clone]git-photo/(git-clone.png)
### git add
```sh
git add [file]
```
*his command adds a file to the staging area.
The git add command adds a change in the working directory to the staging area. *

![git-add](git-photo/git-add.png)

```sh
git add *
```
*This command adds one or more to the staging area.*

![git-add-all](git-photo/git-add-all.png)

### git commit
```sh
git commit -m “[ Type in the commit message]”
```
*This command records or snapshots the file permanently in the version history.*

![git-commit](git-photo/git-commit.png)

```sh
 git commit -a
```
*Commits any files you’ve added with the git add command and also commits any files you’ve changed since then.*

![git-commit-all](git-photo/git-commit-all.png)

### git diff
```sh
git diff
```
*This command shows the file differences which are not yet staged.*

![git-diff](git-photo/git-diff.png)

```sh
git diff -staged
```
*This command shows the differences between the files in the staging area and the latest version present.*

![git-diff-staged](git-photo/git-diff-staged.png)

```sh
git diff [first branch] [second branch]
```
*This command shows the differences between the two branches mentioned.*

![git-diff-branches.png](git-photo/git-diff-branches.png)

### git reset
```sh
git reset [file]
```
*This command unstages the file, but it preserves the file contents.*

![git-reset](git-photo/git-reset.png)

```sh
git reset [commit]
```
*This command undoes all the commits after the specified commit and preserves the changes locally.*

![git-reset-commit](git-photo/git-reset-commit.png)

```sh
git reset –hard [commit]
```
*This command discards all history and goes back to the specified commit.*

![git-reset-hard]git-photo/(git-hard-reset.png)

### git status
```sh
git status
```
*This command lists all the files that have to be committed.*

![git-status]git-photo/(git-status.png)

### git rm
```sh
git rm [file]
```
*This command deletes the file from your working directory and stages the deletion.* 

![git-rm](git-photo/git-rm.png)

### git log
```sh
git log
```
*This command is used to list the version history for the current branch.*

![git-log](git-photo/git-log.png)

```sh
git log –follow[file]
```
*This command lists version history for a file, including the renaming of files also.*

![git-log-follow](git-photo/git-log-follow.png)

### git show
```sh
git show [commit]
```
*This command shows the metadata and content changes of the specified commit.*

![git-show](git-photo/git-show.png)

### git tag
```sh
git tag [commitID]
```
*This command is used to give tags to the specified commit.*

![git-tag](git-photo/git-tag.png)

### git branch
```sh
git branch
```
*This command lists all the local branches in the current repository.*

![git-branch](git-photo/git-branch.png)

```sh
git branch [branch name]
```
*This command creates a new branch.*

![git-create-branch](git-photo/git-create-branch.png)

```sh
git branch -d [branch name]
```
*This command deletes the feature branch.*

![git-delete-branch](git-photo/git-delete-branch.png)

### git checkout
```sh
git chekcout [brnach name]
```
*This command is used to switch from one branch to another.*

![git-checkout](git-photo/git-checkout.png)

```sh
git checkout -b [branch name]
```
*This command creates a new branch and also switches to it.*

![git-create-branch-switch](git-photo/git-create-branch-switch.png)

### git merge
```sh
git merge [branch name]
```
*This command merges the specified branch’s history into the current branch.*

![git-merge](git-photo/git-merge.png)

### git remote
```sh
git remote add [variable name] [Remote Server Link]
```
*This command is used to connect your local repository to the remote server.*

![git-remote](git-photo/git-remote.png)

## git push
```sh
git push [variable name] master
```
```sh
git push [variable name] [branch]
```
*This command sends the branch commits to your remote repository.*

![git-push](git-photo/git-push.png)

![git-push-02](git-push-02.png)

```sh
git push –all [variable name]
```
*This command pushes all branches to your remote repository.*

![git-push-all](git-photo/git-push-all.png)

```sh
git push [variable name] :[branch name]
```
*This command deletes a branch on your remote repository.*

![git-push-delete](git-photo/git-push-delete.png)

### git pull
```sh
git pull [Repository Link]
```
*This command fetches and merges changes on the remote server to your 
working directory.*

![git-pull](git-photo/git-pull.png)

### git stash
```sh
git stash save
```
*This command temporarily stores all the modified tracked files.*

![git-stash-save](git-photo/git-stash-save.png)

```sh
git stash pop
```
*This command restores the most recently stashed files.*

![git-stash-pop](git-photo/git-stash-pop.png)

```sh
git stash list
```
*This command lists all stashed changesets.*

![git-stash-list](git-photo/git-stash-list.png)

```sh
git stash drop
```
*This command discards the most recently stashed changeset.*

![git-stash-drop](git-photo/git-stash-drop.png)
