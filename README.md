# Git Command Guide

A quick reference for common Git commands used in personal and collaborative projects.

---

## 🧱 Initialize a Repository

```bash
git init
--Initializes a new Git repository in your current directory. It creates a hidden .git folder to track changes.

📦 Staging and Committing Changes
git add .
--Stages all changes (new, modified, or deleted files) in the current directory.

git commit -m "Add all files"
--Commits the staged changes to the repository with a message.

🌐 Connecting to Remote Repositories
git remote add origin https://github.com/YourUsername/your-repo.git
--Adds a remote repository named origin. Replace the URL with your actual repository URL.

git remote show origin
--Displays detailed information about the origin remote.

git remote rm origin
--Removes the remote named origin.

⬇️ Pulling from Remote
git pull origin main
--Fetches and merges the latest changes from the main branch of the origin remote.

⬆️ Pushing to Remote
git push origin main
--Pushes your committed changes to the main branch of the remote repository.

👤 Git User Configuration
Global Configuration
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
--Applies to all repositories on your system.

Local (Repo-specific) Configuration
git config user.name "Your Repo Name"
git config user.email "you@example.com"
--Applies only to the current Git repository.

Verifying Config
Global:
git config --global user.name
git config --global user.email
Local:
git config user.name
git config user.email

🧽 Remove Git Tracking (Reset git init)
Remove-Item -Recurse -Force .git
--Deletes the Git tracking folder.

🧬 Cloning a Repository
git clone https://github.com/User1/typescript-practice.git
--Clones a remote repository to your local machine.

🌿 Working with Branches
Create a New Branch
git checkout -b feature-branch
--Creates and switches to a new branch.

Switch to Main Branch
git checkout main

Pull the Latest main Changes
git pull origin main

🗑️ Deleting Branches
Delete Local Branch
git branch -d feature-branch
Delete Remote Branch
git push origin --delete feature-branch


📌 Keep this as a reference when working with Git projects to streamline your workflow.

---

