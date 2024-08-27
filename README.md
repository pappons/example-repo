# Example Repo

This repository was created as part of a Git tutorial. Below you'll find some basic Git commands that are useful to learn when working with a Git repository.

## Setting up Git

If you don't have Git installed yet, you can install it [here](https://git-scm.com/).

Once you have Git installed, you should configure your name and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Clone this repository
To clone this repository to your local machine, use the following command:

```bash
git clone https://github.com/pappons/example-repo.git
```

## Working with Git
### 1. Check the status of your repository
The git status command shows you the status of your repository, including any changes that have not yet been committed and which branch you are working on.

```bash
git status
```
### 2. Add changes to the staging area
After making changes to your files, you can add them to the staging area with git add. To add all changed files:

```bash
git add .
```
Or to add a specific file:

```bash
 git add filename.txt
```
### 3. Commit your changes
After adding changes to the staging area, you can commit them with a message that describes your changes:

```bash
git commit -m "Your commit message here"
```
### 4. Push changes to GitHub
To push your commits to the remote repository on GitHub, use:

```bash
git push origin master
```
Or if you are working on a different branch:

```bash
git push origin <your-branch>
```
### 5. Pull changes from GitHub
If you want to pull the latest changes from GitHub to your local repository, use:

```bash
git pull origin master
```
Or for a different branch:

```bash
git pull origin <your-branch>
```

## Working with Branches
### Create a new branch
If you want to work on a new feature or change, it's a good idea to create a new branch:

```bash
git checkout -b new-branch
```
### Switch between branches
To switch back to a different branch, use:

```bash
git checkout master
```
### Merge a branch into master
When you are done working on a branch and want to merge the changes into the master branch, use:

```bash
git checkout master
```
### git merge new-branch

## GitHub Workflow
When working with GitHub, it’s often useful to create a pull request to review and merge changes from one branch to another. This can be done via the GitHub web interface.

