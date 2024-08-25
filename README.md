 # GitHub Commits Guide

This guide will help you understand how to make commits on GitHub, including best practices and useful commands. A commit is a record of changes made to a repository, and it's essential to keep track of your project's history.

## Table of Contents
1. [What is a Commit?](#what-is-a-commit)
2. [Why Are Commits Important?](#why-are-commits-important)
3. [How to Make a Commit](#how-to-make-a-commit)
4. [Writing Good Commit Messages](#writing-good-commit-messages)
5. [Viewing Commit History](#viewing-commit-history)
6. [Amending a Commit](#amending-a-commit)
7. [Useful Git Commands](#useful-git-commands)
8. [Resources](#resources)

## What is a Commit?

A commit in Git is like a snapshot of your project at a specific point in time. It records the changes you've made to the files in your repository. Each commit is identified by a unique ID (a SHA-1 hash).

## Why Are Commits Important?

- **Version Control**: Commits allow you to keep a history of changes, making it easy to revert to previous versions of your project if needed.
- **Collaboration**: They help teams work together on the same codebase without overwriting each other's changes.
- **Documentation**: Good commit messages serve as a form of documentation for the project, explaining why certain changes were made.

## How to Make a Commit

Follow these steps to make a commit:

1. **Stage Changes**: Before committing, you need to stage the changes. Staging means selecting the changes you want to include in your commit.

    ```bash
    git add <file_name>         # Adds specific file(s) to the staging area
    git add .                   # Adds all changes in the current directory
    ```

2. **Make a Commit**: Once changes are staged, commit them with a descriptive message.

    ```bash
    git commit -m "Your commit message here"
    ```

3. **Push to GitHub**: After committing, push your changes to GitHub (or any remote repository).

    ```bash
    git push origin main        # Replace 'main' with your branch name if different
    ```

## Writing Good Commit Messages

A good commit message is important for understanding the history of a project. Follow these guidelines:

- **Keep it Short**: Limit the subject line to 50 characters.
- **Use the Imperative Mood**: Write as if you're giving an order (e.g., "Add feature", "Fix bug").
- **Include a Body If Necessary**: If the commit is complex, add a body explaining why the change was made.

### Example of a Good Commit Message

 # Useful Git Commands
 
- Clone a Repository: git clone <repository_url>
-  Check Repository Status: git status
- Compare Changes: git diff
- Create a New Branch: git checkout -b <branch_name>
- Switch Branches: git checkout <branch_name>
- Merge Branches: git merge <branch_name>

