
```markdown
# 🚀 My First CI/CD Website with GitHub Actions

🎉 Welcome! This is a **beginner-friendly Python project** demonstrating **Continuous Integration (CI) and Continuous Deployment (CD)** using **GitHub Actions**.  

Every push to GitHub automatically **builds, tests, and deploys** your website — no manual uploads needed! 🌐✨

---

## 🌟 Project Highlights

- **Simple Python Website**: `index.html` + `main.py`  
- **Automated CI/CD Pipeline**: GitHub Actions handles everything  
- **Live Hosting**: GitHub Pages 🚀  
- **Beginner-Friendly**: Perfect for learning DevOps basics  

---

## 🛠 Features Implemented

**1️⃣ Project Setup**
- Created project files locally:
```

index.html
main.py
requirements.txt
.github/workflows/deploy.yml

````

**2️⃣ CI/CD Workflow**
- `.github/workflows/deploy.yml` automates:
  - ✅ Checkout repository  
  - ✅ Setup Python  
  - ✅ Install dependencies  
  - ✅ Deploy site to GitHub Pages using `peaceiris/actions-gh-pages@v3`

**3️⃣ Permissions & Deployment**
- Enabled **Read & Write permissions** in GitHub Actions  
- Workflow pushes automatically to `gh-pages` branch  
- GitHub Pages renders the site live  

---

## 💻 Step-by-Step Implementation

1. **Initialize Git**
```bash
git init
git add .
git commit -m "Initial commit with project files and workflow"
````

2. **Connect to GitHub**

```bash
git remote add origin https://github.com/SrinivasNaren/my-first-actions-demo.git
git branch -M main
git push -u origin main
```

3. **Set Workflow Permissions**

* Go to **Settings → Actions → General → Workflow permissions → Read & Write**

4. **Push Changes**

* Workflow automatically deploys to `gh-pages`
* Site becomes live in a few minutes

---

## 🌐 Live Demo & Workflow Status

| Feature         | Link                                                                                                                                     |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| 🚀 Live Demo    | [![Visit Site](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge)](https://srinivasnaren.github.io/my-first-actions-demo/) |
| ⚙️ CI/CD Status | ![CI/CD](https://github.com/SrinivasNaren/my-first-actions-demo/actions/workflows/deploy.yml/badge.svg)                                  |

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

## 🎯 Why This Project is Useful

* Hands-on **CI/CD experience**
* Fully **automated hosting**
* Beginner-friendly introduction to **DevOps**
* **Portfolio-ready** to showcase GitHub Actions skills

---

## 🔄 How CI/CD Works

**Continuous Integration (CI)**

* Runs automatically on every push
* Repository checked out, Python setup, dependencies installed
* Optional tests can be added

**Continuous Deployment (CD)**

* Workflow pushes the site to `gh-pages`
* GitHub Pages hosts the live version automatically

---

### ⚡ Pro Tips & Notes

> 💡 Update your `index.html` or other files and push → site updates automatically
> 💡 Monitor workflow logs via **Actions tab**
> 💡 Workflow badge shows real-time deployment status

