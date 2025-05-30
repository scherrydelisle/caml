# 211-distress-centre-datathon

# Datathon Project Repository

Welcome to our datathon team repository! This is where we’ll collaborate, share code, and build our project together. Don’t worry if you’re new to Git or GitHub — this README will guide you through how we work together in this repo.

# 📊 Datathon Team Repository

Welcome to our datathon project! This repo will house all code, data, and documentation related to our team's work. This README will guide you through how we use GitHub, what our branching structure looks like, and how to contribute effectively—even if you've never used Git or GitHub before.

---

## 🔧 Tech Stack

- **Python** (Jupyter Notebooks and scripts)
- **SQL** (likely via SQLite, PostgreSQL, or BigQuery)
- **Jupyter Notebooks**
- **GitHub Desktop** for version control (Windows)

---

## 🌿 Branching Structure

To keep things simple, each team member will start off with their **own branch** to work on. This avoids conflicts and gives everyone their own space to experiment and commit code.

- **`main`**: Clean, stable, production-ready code. Avoid committing directly here.
- **`dev`**: Our team’s shared development branch. This is where all individual branches will eventually merge.
- **`your-name`**: Your personal working branch. Do all your work here.

---

## 🔁 Git Workflow (via GitHub Desktop)

### 1. **Clone the repository**
- Open GitHub Desktop
- Go to `File` > `Clone Repository`
- Paste the repo URL and choose a folder on your computer

### 2. **Create your personal branch**
- In GitHub Desktop, switch to the `dev` branch
- Click `Branch` > `New Branch`
- Name it with **your name or username**, all lowercase
- Make sure the base branch is `dev`, then click `Create Branch`

> You only need to do this once!

### 3. **Work on your tasks**
- Use Jupyter, Python, SQL, etc.
- Save your work in the appropriate folders (`/notebooks`, `/scripts`, etc.)
- Try to commit frequently with small, meaningful messages

### 4. **Commit your changes**
- In GitHub Desktop:
  - Write a brief commit message (e.g. `cleaned up null values in dataset`)
  - Click `Commit to your-name`

### 5. **Push your branch**
- Click `Push origin` to upload your changes to GitHub

### 6. **Create a Pull Request (PR)**
- Go to the GitHub repo in your browser
- Click `Compare & pull request`
- Set the base branch to `dev`, and compare with your branch
- Add a short title and description
- Click `Create pull request`

### 7. **Review & Merge**
- We’ll review your PR together as a team
- Once approved, your code will be merged into `dev`

---

## 📁 Folder Structure (recommended)

```
/data          # Raw and processed datasets (avoid uploading large files)
/notebooks     # Jupyter notebooks (each team member can have a subfolder)
/scripts       # Python scripts and functions
/sql           # SQL queries or templates
/docs          # Notes, screenshots, design drafts, etc.
```

---

## ✅ Git Tips & Etiquette

- **Always pull before pushing**: Before starting your work for the day, switch to your branch and pull latest changes.
- **Keep your work in your own branch**: This avoids conflicts and helps isolate issues.
- **Use clear commit messages**.
- **Don’t worry if you mess up**—we can always fix it together.

---

## 💬 Communication

We'll use Discord for discussion and GitHub comments for pull request reviews.

---

