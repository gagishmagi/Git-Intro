# Introduction to git commands

## what is git

git is a distributed version control system

## how to use git

git init # initialize a git repository

```bash
    git init
```

## why do we use this?

1. to initialize a git repository
2. to create a git repository

## clone a repository
git clone \<url\> \<directory\> 


## why do we use this? 

1. to download a repository
2. to clone a repository
3. to fork a repository

# How to use git

```bash
    git clone https://github.com/username/repo.git
```


# Git commit

```bash
    git commit -m "commit message"
```

# Git status

```bash
    git status
```

# Git add => stage the files to commit

Adding all the files in the current directory

```bash
    git add .
```

Adding a single file in the current directory

```bash
    git add <filename>
```
# Unstage a file

This is how we can unstage a file
accedintly added to the staging area
(This will not remove the file from the working directory)

```bash
    git reset <filename> --cached
```