# Git Version Control DevOps Project

## 1. Project Overview

This project demonstrates how Git and GitHub are used in a DevOps workflow to manage source code, maintain different branches, track changes, and collaborate through Pull Requests.

The project was performed using an AWS EC2 Linux instance.

## 2. Objective

- Understand Git version control.
- Create and manage multiple Git branches.
- Develop features using a separate feature branch.
- Use Pull Requests to review and merge changes.
- Maintain project files using Git.
- Use `.gitignore` to exclude unnecessary files.
- Create version tags.
- Document the complete workflow using Markdown.

## 3. Tools and Technologies

- AWS EC2
- Amazon Linux
- Git
- GitHub
- Markdown
- Linux Terminal

## 4. Project Structure

```text
git-devops-project/
│
├── index.html
├── README.md
├── .gitignore
│
└── docs/
    └── git-workflow.md
```

## 5. Git Repository Initialization

Initialized a local Git repository and connected it to a remote GitHub repository.

Commands used:

```bash
git init
git remote add origin <GitHub-repository-URL>
git add .
git commit -m "Initial commit"
git push -u origin main
```

## 6. Branch Management

Created three branches to organize development:

- **main** – Main project branch.
- **dev** – Development branch.
- **feature** – Branch used to develop new features.

Commands used:

```bash
git branch
git checkout -b dev
git push -u origin dev

git checkout -b feature
git push -u origin feature
```

## 7. Feature Development

Modified `index.html` in the feature branch by adding a new feature section.

Changes were committed and pushed to GitHub.

```bash
git add index.html
git commit -m "Add feature branch update to homepage"
git push -u origin feature
```

## 8. Pull Requests and Merging

Used GitHub Pull Requests to merge code changes between branches.

The workflow involved:
- Creating a Pull Request.
- Selecting the base and compare branches.
- Reviewing the changes.
- Merging and closing the Pull Request.

## 9. Git Ignore

Created a `.gitignore` file to prevent unnecessary files and sensitive environment configuration files from being tracked.

Entries included:

```text
*.log
.env
node_modules/
.DS_Store
```

## 10. Git Version Tagging

Created a version tag to identify the first project version.

```bash
git tag -a v1.0 -m "First version of Git DevOps project"
git push origin v1.0
```

## 11. Project Documentation

Created `docs/git-workflow.md` to document the project objective, tools, branching, feature development, Pull Requests, Git ignore, tagging, and outcome.

## 12. Important Git Commands Learned

| Command | Purpose |
|---|---|
| `git status` | Check repository status |
| `git branch` | List branches |
| `git checkout` | Switch branches |
| `git add .` | Stage changes |
| `git commit` | Save changes |
| `git push` | Upload changes to GitHub |
| `git pull` | Download remote changes |
| `git fetch` | Fetch remote updates |
| `git merge` | Merge branches |
| `git log` | View commit history |
| `git tag` | Manage version tags |
| `git remote -v` | View remote repository |

## 13. Outcome

Successfully practised Git and GitHub version control using an AWS EC2 Linux environment.

Learned repository initialization, branch management, feature development, commits, pushing and pulling changes, Pull Requests, `.gitignore`, version tagging, and Markdown documentation.

## 14. GitHub Repository

GitHub Repository: https://github.com/Mithula7777/git-devops-project
