# 📘 Git Practice Repository

This repository contains hands-on exercises to learn and practice essential Git workflows.  
The goal is to help beginners and intermediate users understand how Git works internally and how to use it effectively in real development environments.

## 🚀 Purpose

This project provides practical examples of:

- Initializing a Git repository  
- Adding and removing files from staging  
- Creating commits  
- Working with branches  
- Merging changes  
- Navigating commit history  
- Reverting and resetting states  
- Understanding Git workflows used in DevOps teams  

Each exercise is designed to be simple, repeatable, and focused on a single Git concept.

## 📂 Repository Structure
  upractice-repos/ │ ├── exercises/ │   ├── 01-init/ │   ├── 02-staging/ │   ├── 03-branches/ │   ├── 04-merges/ │   ├── 05-history/ │   └── 06-reset-revert/ │ └── README.md
  
Each folder contains a short scenario and step-by-step tasks.

## 🛠️ Prerequisites

Before starting, make sure you have:

- Git installed (any recent version)
- A terminal (PowerShell, Bash, Zsh, etc.)
- Basic understanding of command-line navigation

# 🧪 Exercises Overview

Below is a summary of the Git concepts covered in this repository.

## 1. 🟦 Initialize a Git Repository

Learn how to create a new Git repository from scratch.

**Key commands:**
  git init git status


## 2. 🟩 Add & Remove Files from Staging

Understand the difference between working directory, staging area, and repository.

**Key commands:**
git add <file> git add . git reset <file> git rm --cached <file


## 3. 🌿 Branching

Create and switch between branches to isolate work.

**Key commands:**
  git branch git branch feature-xyz git switch feature-xyz git checkout feature-xyz

## 4. 🔀 Merging Branches

Learn how to merge changes and resolve conflicts.

**Key commands:**
git merge <branch> git merge --abort


## 5. 🕒 Viewing History

Explore commit logs and understand how Git tracks changes.

**Key commands:**
  git log git log --oneline --graph --decorate git show <commit>


## 6. ⏪ Resetting & Reverting

Practice going back to previous states safely.

**Key commands:**
  git reset --soft <commit> git reset --hard <commit> git revert <commit>

# 📚 Recommended Workflow

1. Clone this repository  
  git clone https://github.com/AldoSan666/upractice-repos.git
2. Navigate into any exercise folder  
3. Follow the instructions inside  
4. Experiment freely — break things, fix them, repeat  
5. Commit your progress as you learn  

# 🤝 Contributing

This repository is meant for learning, but contributions are welcome:

- Add new exercises  
- Improve explanations  
- Add diagrams or examples  
- Fix typos or structure  

Please follow a simple workflow:

1. Create a new branch  
2. Make your changes  
3. Open a Pull Request  

# 📄 License

This project is open-source under the MIT License.
