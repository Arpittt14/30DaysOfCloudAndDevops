# Day 01 - Git & GitHub Fundamentals

## Objective

Learn the fundamentals of Git and GitHub, understand version control, and perform basic repository operations.

---

## What is Git?

Git is a distributed version control system used to track changes in source code and files over time. It helps developers collaborate, manage project history, and revert changes when needed.

### Benefits of Git

* Tracks changes in files
* Maintains project history
* Supports team collaboration
* Enables branching and merging
* Helps recover previous versions

---

## What is GitHub?

GitHub is a cloud-based platform that hosts Git repositories online.

### Git vs GitHub

| Git                    | GitHub                 |
| ---------------------- | ---------------------- |
| Version Control System | Cloud Hosting Platform |
| Works locally          | Works online           |
| Tracks changes         | Stores repositories    |
| Command-line tool      | Collaboration platform |

---

## Git Configuration

Configure Git identity before using it.

### Set Username

```bash
git config --global user.name "Your Name"
```

### Set Email

```bash
git config --global user.email "your@email.com"
```

### Verify Configuration

```bash
git config --list
```

---

## Creating and Cloning Repositories

### Initialize a New Repository

```bash
git init
```

Creates a new Git repository in the current folder.

### Clone an Existing Repository

```bash
git clone <repository-url>
```

Downloads a remote repository to the local machine.

---

## Understanding the Git Workflow

Working Directory → Staging Area → Repository

### Check Repository Status

```bash
git status
```

Displays modified, staged, and untracked files.

### Add Files to Staging Area

```bash
git add file-name
```

Add all files:

```bash
git add .
```

### Remove Files from Staging Area

```bash
git reset
```

---

## Viewing Changes

### Show Unstaged Changes

```bash
git diff
```

### Show Staged Changes

```bash
git diff --staged
```

---

## Creating Snapshots (Commits)

### Commit Changes

```bash
git commit -m "Commit Message"
```

A commit creates a permanent snapshot of the project at a specific point in time.

Example:

```bash
git commit -m "Added login page"
```

---

## Branching and Merging

Branches allow developers to work on features independently without affecting the main codebase.

### View Branches

```bash
git branch
```

### Switch Branch

```bash
git checkout branch-name
```

### Merge Branches

```bash
git merge branch-name
```

### View Commit History

```bash
git log
```

---

## Key Takeaway

The Git Staging Area acts as a checkpoint before creating a commit. It allows developers to carefully select and review changes before they become part of the project history.

---

## Hands-On Practice Completed

* Installed Git
* Configured username and email
* Created a local repository
* Checked repository status
* Added files to the staging area
* Created commits
* Viewed differences using Git Diff
* Practiced branching and merging basics
* Viewed commit history

---

## Commands Learned Today

```bash
git config --global user.name
git config --global user.email
git config --list
git init
git clone
git status
git add
git reset
git diff
git diff --staged
git commit -m
git branch
git checkout
git merge
git log
```

---

## Day 01 Summary

Today I learned the foundations of Git and GitHub, including repository creation, version control concepts, staging changes, committing code, and basic branching operations. These concepts form the backbone of modern software development, Cloud Engineering, and DevOps workflows.

**Status:** ✅ Day 01 Completed
