# PRO_Python
Project resources and guided projects for learning data analysis with Python — from basic exploration to visualization.
# 🧑‍🎓 Student Git Setup Guide for Data Analysis with Python

Welcome! This guide will walk you through setting up Git and GitHub so you can track your progress and submit assignments effectively.

---

## ✅ Step 1: Create a GitHub Account
If you don’t already have one, sign up here:
👉 https://github.com

---

## ✅ Step 2: Fork the Instructor's Repository
1. Visit the instructor's GitHub repo (we will provide the link).
2. Click the **"Fork"** button (top-right) to create your copy of the repository.

---

## ✅ Step 3: Clone Your Fork to Your Computer
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

---

## ✅ Step 4: Add the Instructor’s Repo as Upstream
This allows you to get updates from the instructor.
```bash
git remote add upstream https://github.com/<instructor-username>/<repo-name>.git
```

---

## ✅ Step 5: Create a Branch for Each Task
```bash
git checkout -b assignment-1
```
Replace `assignment-1` with the relevant task name.

---

## ✅ Step 6: Make Changes and Commit
After completing your work:
```bash
git add .
git commit -m "Completed assignment 1"
git push origin assignment-1
```

---

## ✅ Step 7: Pull Updates from Instructor (Optional)
```bash
git pull upstream main
```
This pulls the latest updates from the instructor’s main branch.

---

## ✅ Good Practices
- Commit regularly with clear messages.
- Keep your branches tidy.
- Ask questions by opening an issue in your forked repo (optional).

---

You're all set! 🎉 Now go ahead and start coding!


