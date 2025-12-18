# 🧠 Git + GitHub Master Cheat Sheet

A complete step-by-step guide to Git and GitHub.

<details>
<summary>🚀 Phase 1: New Project – Local to GitHub</summary>

| Command | Description |
|--------|-------------|
| `git init` | Initialize Git repository locally |
| `git add .` | Stage all files for commit |
| `git commit -m "Initial commit"` | Save changes with a message |
| `git branch -M main` | Rename branch to `main` |
| `git remote add origin <URL>` | Connect to remote GitHub repo |
| `git push -u origin main` | Push your code to GitHub |

</details>

<details>
<summary>🔄 Phase 2: Cloning & Daily Work</summary>

| Command | Description |
|--------|-------------|
| `git clone <URL>` | Clone a repo to your computer |
| `git status` | Check which files changed |
| `git pull origin main` | Get latest changes from GitHub |
| `git checkout -b <name>` | Create and switch to a new branch |
| `git push origin <name>` | Push your branch to GitHub |

</details>

<details>
<summary>🤝 Phase 3: Fork & Pull Request (Open Source)</summary>

1. **Fork** the repo on GitHub (Top right button).
2. **Clone** your fork: `git clone <your_fork_url>`
3. **Create Branch**: `git checkout -b feature/my-new-feature`
4. **Code & Commit**: `git commit -m "Added feature"`
5. **Push**: `git push origin feature/my-new-feature`
6. Go to GitHub and click **"Compare & Pull Request"**.

</details>
