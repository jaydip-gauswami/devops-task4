#Devops task 4 - version  Controlled Project with Git

## 📌 Objective
Manage a DevOps project using **Git best practices** including branching, pull requests, tagging, and documentation.

---

## 🛠 Tools Used
- **Git** – Version control
- **GitHub** – Remote repository hosting

---

## 📂 Git Workflow
This project follows a **basic Git workflow**:

1. **Main Branch** – Stable production-ready code (`main`)
2. **Development Branch** – All development work happens here (`dev`)
3. **Feature Branches** – For adding new features before merging to `dev`  
   Example: `feature-add-logging`

---

## 🔄 Workflow Steps

### 1️⃣ Initialize Repo
```bash
git init
git add .
git commit -m "Initial commit: Project setup"
git branch -M main
git remote add origin <repo-urlO>
git push -u origin main
