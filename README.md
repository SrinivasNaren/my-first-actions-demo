

```markdown
# 🚀 My First CI/CD Website with GitHub Actions

🎉 Welcome! This is a **beginner-friendly Python project** demonstrating **Continuous Integration (CI) and Continuous Deployment (CD)** using **GitHub Actions**.  

Every push to GitHub automatically **builds, tests, and deploys** your website — no manual uploads needed! 🌐✨

---

## 🌟 What I Did

**1️⃣ Created the Project**
- Simple Python website: `index.html` + Python server `main.py`  
- Added `requirements.txt` for dependencies  

**2️⃣ Setup GitHub Actions Workflow**
- Workflow file: `.github/workflows/deploy.yml`  
- Steps:
  - ✅ Checkout repository  
  - ✅ Setup Python  
  - ✅ Install dependencies  
  - ✅ Deploy to GitHub Pages using `peaceiris/actions-gh-pages@v3`

**3️⃣ Configured CI/CD Permissions**
- Enabled **Read & Write permissions** for Actions  
- Allows workflow to push automatically to `gh-pages` branch  

**4️⃣ Enabled GitHub Pages**
- Source branch: `gh-pages`  
- Site automatically updates on every push  

---

## 💻 How I Did It (Step-by-Step)

**1️⃣ Project Files**
```

index.html
main.py
requirements.txt
.github/workflows/deploy.yml

````

**2️⃣ Initialize Git**
```bash
git init
git add .
git commit -m "Initial commit with project files and workflow"
````

**3️⃣ Connect Local Folder to GitHub**

```bash
git remote add origin https://github.com/<your-username>/my-first-actions-demo.git
git branch -M main
git push -u origin main
```

**4️⃣ Set GitHub Actions Permissions**

* Settings → Actions → General → Workflow permissions → **Read & Write**

**5️⃣ Push Changes to Trigger Workflow**

* Workflow automatically deploys site to `gh-pages` branch

---

## 🔧 Tech Stack

| Feature  | Tech              |
| -------- | ----------------- |
| Language | Python 🐍         |
| CI/CD    | GitHub Actions ⚙️ |
| Hosting  | GitHub Pages 🌐   |

---

## 📂 Project Structure

```
my-first-actions-demo/
├─ index.html       # Main HTML page
├─ main.py          # Python server script
├─ requirements.txt # Python dependencies
├─ .github/
│  └─ workflows/
│     └─ deploy.yml  # GitHub Actions workflow
└─ README.md        # This file
```

---

## 🌐 Live Demo

💻 Check it out:
[![Visit Site](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge)](https://<your-username>.github.io/my-first-actions-demo/)

---

## ✅ Workflow Status

![CI/CD](https://github.com/<your-username>/my-first-actions-demo/actions/workflows/deploy.yml/badge.svg)

---

## 🎯 Why This Project is Useful

* Hands-on **CI/CD experience**
* **Automated hosting** without manual uploads
* **Beginner-friendly** Python project
* Portfolio-ready, shows **DevOps skills**

---

## 🔄 How CI/CD Works

**Continuous Integration (CI)**

* Every push triggers the workflow
* Repository checked out, Python setup, dependencies installed
* Optional: run tests

**Continuous Deployment (CD)**

* Workflow pushes site to `gh-pages`
* GitHub Pages serves latest version automatically

---

### ⚡ Pro Tips

* Update files and push → site updates automatically
* Monitor workflow via **Actions tab**
* Workflow badge shows deployment status ✅

---

