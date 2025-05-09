
# 🚀 Git for Beginners: A Step-by-Step Guide to Version Control

Whether you're a developer, DevOps engineer, or tech enthusiast, **Git** is an essential tool to manage your code efficiently. In this blog, you'll learn Git step by step—from setting it up to managing branches and collaborating with teams.

---

## 🧠 What is Git?

**Git** is a distributed version control system that tracks changes in your code. It allows multiple people to work on a project without overwriting each other’s work.

---

## 🛠️ Step 1: Install Git

### For Ubuntu/Linux:
```bash
sudo apt update
sudo apt install git
```

### For Windows/Mac:
Download from the official site: [https://git-scm.com/](https://git-scm.com/)

---

## ⚙️ Step 2: Configure Git

Set your name and email:
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

Check config:
```bash
git config --list
```

---

## 📁 Step 3: Initialize a Git Repository

Navigate to your project directory:
```bash
cd my-project
git init
```

You’ve now created a local Git repository!

---

## 📄 Step 4: Track Your First File

Create a file:
```bash
echo "Hello Git!" > hello.txt
```

Check status:
```bash
git status
```

Stage the file:
```bash
git add hello.txt
```

Commit it:
```bash
git commit -m "Initial commit"
```

---

## 🔍 Step 5: View Commit History

```bash
git log
```

Want a simplified view?
```bash
git log --oneline
```

---

## 🌿 Step 6: Branching

Create a new branch:
```bash
git branch feature-x
```

Switch to it:
```bash
git switch feature-x
```

Make changes, then:
```bash
git add .
git commit -m "Added feature X"
```

---

## 🔀 Step 7: Merging Branches

Switch to main branch:
```bash
git switch main
```

Merge changes:
```bash
git merge feature-x
```

---

## 💥 Step 8: Resolve Merge Conflicts

If conflicts occur, Git will highlight them in the files. Manually edit and fix them.

Then:
```bash
git add .
git commit -m "Resolved merge conflicts"
```

---

## 🌐 Step 9: Connect to Remote (GitHub)

Create a repo on GitHub.

Link it:
```bash
git remote add origin https://github.com/yourusername/yourrepo.git
```

Push code:
```bash
git push -u origin main
```

---

## 🔄 Step 10: Pull Updates from Remote

```bash
git pull origin main
```

---

## 🧰 Bonus Commands

- Ignore files: Add patterns to `.gitignore`
- Stash temporary changes:
  ```bash
  git stash
  git stash pop
  ```
- Undo last commit (keep changes):
  ```bash
  git reset --soft HEAD~1
  ```

---

## ✅ Conclusion

Git is a powerful tool that simplifies version control, promotes collaboration, and improves your workflow. With these basics, you’re well on your way to mastering Git. Keep practicing!

---

### 💡 What's Next?

- Learn about **rebasing** vs **merging**
- Explore **GitHub Actions** for automation
- Use **Git hooks** for pre-commit checks

---

If you found this helpful, follow me for more DevOps, Git, and cloud tutorials! ✨
