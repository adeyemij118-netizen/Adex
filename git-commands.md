## GIT COMMANDS

## 1. git init

### What it does

`git init` initializes a new Git repository in the current directory. It creates a hidden `.git` directory where Git stores information about the repository, including its history and configuration.

### Example

```bash
mkdir my-project
cd my-project
git init
```
## 2. git status

## what it does 

git status shows the current state of your Git repository. It tells you which files have been modified, which files are untracked, and which files have been staged for a commit.

### Example 

```bash

git status
```
## 3. git add

## what it does

`git add` adds changes to the staging area.

### Example

To add a specific file:

```bash
git add README.md
```
To add all changed files:
```bash
git add .
```
## 4. git commit

`git commit` saves the staged changes to the Git repository's history.

The -m option allows you to provide a message describing the changes.t it does

### Example

```bash

git commit -m "Add project README"

```

## 5.git push

## what it does

`git push `uploads your local commits to a remote repository such as GitHub.

### Example

```bash

git push origin main

```

## 6.git pull
git pull downloads changes from the remote repository and integrates them into your
local branch.

### Example

```bash

git pull origin main

```
## 7.git clone

## what it does 
`git clone` creates a local copy of an existing remote repository.

### Example

```bash
https://github.com/example/my-project.git

```
### 8.git branch

## what it does
`branch `allows you to work on a separate version of your project.

### Example

```bash
Create a branch:git branch feature-login

Switch to it:git switch feature-login

create and switch at the same time:git switch -c feature-login

```
### 9.git switch

## what it does

`git switch `is used to switch from one branch to another.

### Example

```bash

git switch -c feature-login

```
### 10.git merge

## what it does
`git merge` combines the changes from one branch into another branch.

### Example

```bash

git merge feature-login

```
