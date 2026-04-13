# Git Node.js Project

## 📌 Project Overview

This project demonstrates the use of Git for version control, including repository initialization, staging, committing changes, and using a `.gitignore` file.

A simple Node.js application is included to serve as the sample project.

---

## 🎯 Objectives

* Initialize a Git repository
* Track files using Git
* Make meaningful commits
* Use a `.gitignore` file
* Understand staging and committing

---

## 📂 Project Structure

```
git-node-project/
│
├── src/
│   └── app.js                # Main Node.js application
│
├── screenshots/             # Contains required Git screenshots
│   ├── git-init.png         # Screenshot of git init
│   ├── git-status.png       # Screenshot of git status
│   └── git-log.png          # Screenshot of git log --oneline
│
├── .gitignore               # Files and folders ignored by Git
├── README.md                # Project documentation
├── node.md                  # Answers to Git theory questions
└── package.json             # Node.js configuration file
```

---

## 📸 Screenshots (Required Deliverables)

All screenshots are stored in the **`screenshots/`** folder:

| Screenshot       | Description                                    |
| ---------------- | ---------------------------------------------- |
| `git-init.png`   | Shows Git repository initialization            |
| `git-status.png` | Shows current state of tracked/untracked files |
| `git-log.png`    | Shows commit history using `git log --oneline` |

---

## 🧠 Answers to Questions

All theoretical explanations (including **staging vs committing**) are documented in:

👉 `node.md`

---

## ⚙️ How to Run the Project

### 1. Clone the repository

```
git clone <https://github.com/Adaobilynda1234/SCA-version-control.git>
cd git-node-project
```

### 2. Install dependencies

```
npm install
```

### 3. Run the application

```
node src/app.js
```

### 4. Open in browser

```
http://localhost:3000
```

---

## 🧾 Git Workflow Used

### Step 1: Initialize Repository

```
git init
```

### Step 2: Stage Files

```
git add .
```

### Step 3: Commit Changes

```
git commit -m "Initial commit: add project structure and Node.js app"
```

### Step 4: Additional Commits

* Updated application response
* Added documentation and explanations

### Step 5: View Status

```
git status
```

### Step 6: View Commit History

```
git log --oneline
```

---

## 🚫 .gitignore Explanation

The `.gitignore` file ensures unnecessary files are not tracked by Git, such as:

* `node_modules/`
* `.env`
* log files
* system files (e.g., `.DS_Store`, `Thumbs.db`)
* editor folders like `.vscode/`

---

## 🧪 Sample Application Endpoints

| Route    | Response      |
| -------- | ------------- |
| `/`      | Hello, World! |
| `/about` | About Page    |

---

## ✅ Requirements Checklist

* [x] Git repository initialized
* [x] README.md created
* [x] Source file included (`app.js`)
* [x] Notes file included (`node.md`)
* [x] `.gitignore` file created
* [x] At least 3 commits made
* [x] Screenshots added
* [x] Git concepts explained

---

## 🚀 Conclusion

This project demonstrates a clear understanding of Git fundamentals, including:

* repository setup
* file tracking
* staging and committing
* maintaining a clean project with `.gitignore`
