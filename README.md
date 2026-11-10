# Version-Controlled DevOps Project Using Git

## Project Overview
This project demonstrates the use of Git for version control and GitHub for remote repository management. The project was created on an AWS EC2 instance running Amazon Linux 2023.

## Technologies Used
- AWS EC2
- Amazon Linux 2023
- Git
- GitHub
- HTML

## Project Architecture

AWS EC2 (Amazon Linux 2023)
       |
       v
   Git Repository
       |
       v
   Git Add
       |
       v
   Git Commit
       |
       v
   GitHub Remote Repository
       |
       v
   Git Push

## Implementation Steps

1. Created an AWS EC2 instance using Amazon Linux 2023.
2. Connected to the EC2 instance.
3. Updated Linux packages.
4. Installed Git.
5. Configured Git username and email.
6. Created a project directory.
7. Created an HTML file named `index.html`.
8. Initialized a local Git repository using `git init`.
9. Added files to the staging area using `git add`.
10. Committed changes using `git commit`.
11. Created a remote repository on GitHub.
12. Connected the local repository to GitHub using `git remote add origin`.
13. Uploaded the project using `git push`.

## Git Commands Used

```bash
git init
git config --global user.name "Mithula"
git config --global user.email "YOUR_GITHUB_EMAIL"
git add index.html
git status
git commit -m "Add index.html"
git branch
git remote add origin REPOSITORY_URL
git remote -v
git push -u origin master
```

## Project File Structure

```text
git-devops-project/
│
├── index.html
└── README.md
```

## Learning Outcomes

- Understanding Git version control.
- Managing local and remote repositories.
- Understanding Git staging and commits.
- Working with Git branches.
- Connecting AWS EC2 with GitHub.
- Uploading project files to GitHub using Git.

## Author
Mithula

## GitHub Repository
https://github.com/Mithula7777/git-devops-project-
