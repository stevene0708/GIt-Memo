# Git-Memo

## Git Usual Commands
 - Make new git-dir
 ```
    mkdir git-Memo
    cd git-Memo
    git init
 ```
 - Add new files under the git controll
```
    git add . # All file
    git add filename # Specfic file
    git add directory # Specfic directory
```
 - Commit change
```
    git commit
    git commit -m "TEXT" # Add the memo and commit.
```
 - Check the log
```
    git log
    git log -10 # Show the most 10 log
```
 - Remove the files
```
    git rm 'filename' # remove the git cache and instance
```
 - Rename the files
```
    git mv "filenamev1" "filenamev2"
```
 - Show the status
```
    git status
    git status -s # show the simple version
```
 - Reset the directory
```
    git reset --hard # Restore the newest commit version
```
 - Restore one of the files
```
    git checkout master filename
```