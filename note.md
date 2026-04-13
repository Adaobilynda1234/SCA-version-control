# Git Concepts Explanation

## What is Staging?

Staging is the process of selecting which changes you want to include in the next commit.

When you run:
git add .

You are moving files into the staging area. This means Git is preparing those changes to be saved.

---

## What is Committing?

Committing is the process of saving the staged changes into the Git repository.

When you run:
git commit -m "message"

Git takes a snapshot of the staged files and saves it permanently in the project history.

---

## Difference Between Staging and Committing

- Staging allows you to choose what changes to include
- Committing permanently saves those selected changes