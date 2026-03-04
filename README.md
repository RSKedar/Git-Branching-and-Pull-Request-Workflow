# Git-Branching-and-Pull-Request-Workflow

Project Overview

This project demonstrates how to manage code using Git branching strategy and GitHub Pull Requests.

The workflow includes creating a GitHub repository, cloning it locally, creating feature and development branches, committing changes, pushing code to GitHub, and merging branches using Pull Requests (PR).

Tools Used

Git

GitHub

Git Bash

Project Architecture:-
Developer
   │
   ▼
Local Git Repository
   │
   ▼
GitHub Remote Repository
   │
   ▼
Branching Strategy
(main, dev, feature branches)


Step 1: Create GitHub Repository

A new repository was created on GitHub.

Repository Name:

student-notes

Settings:

Visibility: Public

Initialized with README


Step 2: Clone Repository

The repository was cloned to the local machine.

git clone https://github.com/<username>/student-notes.git
cd student-notes

Step 3: Create Feature Branch

Created a new feature branch.

git checkout -b feature/add-note

Created file:

echo "My first note" > note1.txt

Add and commit changes:

git add note1.txt
git commit -m "note1 is commited"

Push branch to GitHub:

git push origin feature/add-note


Step 4: Create Dev Branch

Created development branch.

git checkout main
git checkout -b dev

Created file:

echo "Dev branch content" > dev-notes.txt

Add and commit:

git add dev-notes.txt
git commit -m "Added dev-notes.txt"

Push to GitHub:

git push origin dev


Step 5: Create Pull Request

A Pull Request was created on GitHub.

Configuration:

Base Branch: main
Compare Branch: dev


Step 5: Create Pull Request

A Pull Request was created on GitHub.

Configuration:

Base Branch: main
Compare Branch: dev

Description:

Please review my code changes

Step 6: Review and Merge Pull Request

Steps performed:

Reviewed the code changes

Approved the pull request

Merged PR into main branch

Deleted the dev branch

Step 7: Verify Merge

Pulled latest changes:

git checkout main
git pull origin main

Files available:

README.md
dev-notes.txt
note1.txt






















































