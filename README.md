
# 🚀 My First CI/CD Website with GitHub Actions

This project is a **small Python website** that shows how to use **CI/CD (Continuous Integration and Continuous Deployment)** with **GitHub Actions**.

Whenever we **push changes to GitHub**, the website is **automatically built and deployed** online — no need to do it manually! 🌐✨

---

### **What I Did**

1. **Created the Website**

   * Made a simple webpage (`index.html`) and a Python script (`main.py`) to run it locally.
   * Added `requirements.txt` for Python dependencies.

2. **Automated Deployment with GitHub Actions**

   * Created a workflow file that:

     * Checks the code
     * Sets up Python
     * Installs dependencies
     * Deploys the site automatically to GitHub Pages

3. **Configured Permissions**

   * Allowed GitHub Actions to push changes to the `gh-pages` branch automatically.

4. **Enabled GitHub Pages**

   * The website is hosted online using the `gh-pages` branch.
   * Every push to GitHub updates the live site automatically.

---

### **Why This Project is Useful**

* **Learn CI/CD easily:** See how automation works.
* **Automatic Hosting:** No manual uploads.
* **Beginner-friendly:** Perfect for learning DevOps basics.
* **Portfolio-ready:** Shows your skills in automation and deployment.

---

### **How CI/CD Works Here**

**Continuous Integration (CI):**

* Every time you push code, GitHub Actions checks the code and installs dependencies.

**Continuous Deployment (CD):**

* After CI passes, the workflow automatically uploads the website to GitHub Pages.
* The live site is updated immediately.

---

### **Live Demo & Workflow Status**

* **🚀 Live Demo:** [Visit Site](https://srinivasnaren.github.io/my-first-actions-demo/)
* **⚙️ Workflow Status:** ![CI/CD](https://github.com/SrinivasNaren/my-first-actions-demo/actions/workflows/deploy.yml/badge.svg)

---

### **Outcome**

* A fully automated website deployment.
* Live website available online.
* Learned how GitHub Actions can automate CI/CD and hosting.
