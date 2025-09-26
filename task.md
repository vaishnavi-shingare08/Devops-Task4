# Task Commands

## 1. Initialize Git
git init
git branch -M main
git remote add origin https://github.com/vaishnavi-shingare08/Devops-Task4.git

## 2. First Commit
git add .
git commit -m "Initial commit with project.html, README.md, .gitignore, task.md"
git push -u origin main

## 3. Branching
git checkout -b dev
git push -u origin dev

git checkout -b feature
git push -u origin feature

## 4. Make Changes
echo "<p>New feature added</p>" >> project.html
git add .
git commit -m "Add new feature content"
git push origin feature

## 5. Pull Request & Merge
# Go to GitHub → Compare & Pull Request → Merge into dev
# Then create another PR to merge dev → main

## 6. Tagging
git tag v1.0
git push origin v1.0

## 7. Useful Checks
git log --oneline --graph --all
git branch -a
git tag

## GitHub Repository
All changes are stored at:
➡️ https://github.com/vaishnavi-shingare08/Devops-Task4.git
