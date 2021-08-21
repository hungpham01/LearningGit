# Learning Git

## Initialise Git Repository

Intialise the git repository

```
git init .
```

## Cloning Git from github

Cloning git from a remote repository

```
git clone https://github.com/hungpham01/LearningGit.git
```

## git config

Set
```
git config --global user.name "User Name"
git config --global user.email "email@gmail.com"
git config --global --list
git config --local user.name "Local Username"
git config --local user.email "local_email@gmail.com"
git config --local --list
```
## git status

This command show the status of the working files with the last commit and staging area

```
git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   git_command_help.txt

no changes added to commit (use "git add" and/or "git commit -a")
```

## git add

Adding a file into the git repository
```
# adding all file in the current directory
git add .
# adding updated change to staging area
git add -u

```

## git rm

Adding remote Git operation into the staging area for file removal
```
git rm git_command_help.txt
```

