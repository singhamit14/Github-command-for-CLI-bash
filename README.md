# Github-command-for-CLI-bash
This GitHub repository provides a comprehensive guide to essential Git commands, covering everything from basic operations like git init, git clone, and git commit to more advanced commands like git merge and git rebase. It includes descriptions, usage examples, and explanations to help users understand each command's purpose and application.

# Git Command List and Usage Guide

Welcome to the Git Command List repository! This repository aims to provide a comprehensive guide to using Git, a distributed version control system that helps developers manage and track changes to their codebase efficiently.

## Table of Contents

1. [Introduction](#introduction)
2. [Basic Git Commands](#basic-git-commands)
3. [Intermediate Git Commands](#intermediate-git-commands)
4. [Advanced Git Commands](#advanced-git-commands)
5. [Common Workflows](#common-workflows)
6. [Additional Resources](#additional-resources)

## Introduction

Git is an essential tool for developers to collaborate on projects and manage their code efficiently. This guide is designed to help both beginners and advanced users understand and use Git commands effectively.

## Basic Git Commands

Here is a list of basic Git commands that every developer should know:

### 1. `git init`

- **Description**: Initializes a new Git repository in the current directory.
- **Usage**: Run this command inside a directory to start tracking its contents with Git.
  
  ```bash
  git init

### 2. `git clone`

- **Description**: Clones a repository into a new directory.
- **Usage**: Use this command to copy an existing repository from GitHub to your local machine.

  ```bash
  git clone <repository-url>


### 3. `git add`

- **Description**: Adds changes in the working directory to the staging area.
- **Usage**: Use this command to stage changes (new files, modifications, deletions) before committing.

  ```bash
   git add <file-name>  # Add a specific file
   git add .            # Add all changes in the current directory

 ### 4. `git commit`

- **Description**: Records changes to the repository.
- **Usage**: Commits staged changes to the local repository with a message describing what was changed.

  ```bash
  git commit -m "Your commit message here"

### 5. `git status`

- **Description**: Displays the state of the working directory and staging area.
- **Usage**: Run this command to view changes that have been staged, unstaged, or untracked.

  ```bash
  git status

### 5. `git push`

- **Description**: Updates the remote repository with commits made locally.
- **Usage**: Use this command to push your local commits to the remote repository on GitHub.

  ```bash
  git push origin main

## Intermediate Git Commands

### 1. `git pull`

- **Description**: Fetches and merges changes from the remote repository to your local repository.
- **Usage**: Use this command to update your local repository with the latest changes from the remote repository.

  ```bash
  git pull origin main

### 2. `git branch`

- **Description**: Lists, creates, or deletes branches.
- **Usage**: To create a new branch, list all branches, or delete a branch.

  ```bash
  git branch          # List all branches
  git branch <name>   # Create a new branch
  git branch -d <name> # Delete a branch

### 3. `git checkout`

- **Description**: Switches branches or restores working tree files.
- **Usage**: Use this command to switch to another branch or restore a file.

  ```bash
  git checkout <branch-name>  # Switch to an existing branch
  git checkout -b <new-branch-name>  # Create and switch to a new branch

## Advanced Git Commands

### 1. `git checkout`

- **Description**: Merges changes from one branch into another.
- **Usage**: Use this command to merge changes from a feature branch into the main branch.
  
  ```bash
  git merge <branch-name>

### 2. `git rebase`

- **Description**: Reapplies commits on top of another base tip.
- **Usage**: Use this command to move or combine a sequence of commits to a new base commit.
  
  ```bash
  git rebase <branch-name>

### 3. `git stash`

- **Description**: Temporarily saves changes that are not ready to be committed.
- **Usage**: Use this command to store uncommitted changes temporarily and clean your working directory.
  
  ```bash
  git stash          # Stash current changes
  git stash pop      # Apply stashed changes

## Common Workflows 

- **Feature Branch Workflow**: A workflow where each feature is developed in a dedicated branch.
- **Forking Workflow**: Used primarily in open source projects, where contributors fork a repository and create pull requests.

## Additional Resources

For more information on Git commands and best practices, visit:

- **Offical Git Documentation**: https://git-scm.com/docs
- **Pro Git Book**: https://git-scm.com/book/en/v2
