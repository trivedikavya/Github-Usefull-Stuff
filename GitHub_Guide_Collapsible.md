
# 🧠 Git + GitHub Master Cheat Sheet for Beginners

A complete step-by-step guide to Git and GitHub – ideal for:

- 💻 Starting new projects  
- 🔄 Cloning existing repos  
- 🌍 Contributing to open-source  
- 🌿 Working with branches  
- ✍️ Editing code like a pro

---

<details>
<summary>🚀 Phase 1: New Project – Local to GitHub</summary>

| Command | Description |
|--------|-------------|
| `mkdir my-project && cd my-project` | Create and enter a new folder |
| `git init` | Initialize Git repository locally |
| `git add .` | Stage all files for commit |
| `git commit -m "Initial commit"` | Save changes with a message |
| `git branch -M main` | Rename branch to `main` (recommended) |
| `git remote add origin <repo_URL>` | Connect to remote GitHub repo |
| `git push -u origin main` | Push your code to GitHub |

</details>

---

<details>
<summary>🔄 Phase 2: Clone a Repo and Work on It</summary>

| Command | Description |
|--------|-------------|
| `git clone <repo_URL>` | Clone an existing GitHub repo |
| `cd <repo_folder>` | Navigate into the folder |
| `git checkout -b <feature_branch>` | Create and switch to new branch |
| `git add .` | Stage changes |
| `git commit -m "Your message"` | Commit changes |
| `git push origin <feature_branch>` | Push new branch to GitHub |

</details>

---

<details>
<summary>🤝 Phase 3: Contribute to Open Source (Fork + PR)</summary>

| Step | Description |
|------|-------------|
| 🔗 Fork the repo | On GitHub, click `Fork` to create your copy |
| 🖥️ `git clone <your_fork_URL>` | Clone fork to your PC |
| 🛠️ `cd <repo_folder>` | Go into the folder |
| 📡 `git remote add upstream <original_repo_URL>` | Track original repo |
| 🌿 `git checkout -b feature/my-feature` | Create a new branch |
| ✍️ Make your changes | Add your code |
| 📦 `git add .` | Stage files |
| 📝 `git commit -m "Add feature"` | Save changes |
| 🚀 `git push origin feature/my-feature` | Push branch |
| 📥 Create Pull Request | Go to GitHub → Compare & Pull Request |
| ✅ Submit | Add title, description and submit PR |

</details>

---

<details>
<summary>✍️ Editing or Updating Code</summary>

| Command | Description |
|--------|-------------|
| `git status` | See modified/untracked files |
| `git diff` | See what changed |
| `git add <file>` | Stage specific file |
| `git commit -m "Update file"` | Commit update |
| `git pull origin <branch>` | Get latest changes before pushing |
| `git push origin <branch>` | Push changes |

</details>

---

<details>
<summary>🌿 Branching & Merging</summary>

| Command | Description |
|--------|-------------|
| `git branch` | List all branches |
| `git branch <name>` | Create new branch |
| `git checkout <name>` | Switch branch |
| `git checkout -b <name>` | Create + switch |
| `git merge <branch>` | Merge into current |
| `git branch -d <name>` | Delete local branch |

</details>

---

<details>
<summary>🌍 Working with Remotes</summary>

| Command | Description |
|--------|-------------|
| `git remote -v` | View remotes |
| `git remote add origin <url>` | Add origin |
| `git remote add upstream <url>` | Add upstream |
| `git fetch upstream` | Get changes from original repo |
| `git merge upstream/main` | Merge updates |
| `git push origin main` | Push to GitHub |

</details>

---

<details>
<summary>💣 Undo / Fix Mistakes</summary>

| Command | Description |
|--------|-------------|
| `git checkout -- <file>` | Revert file changes |
| `git reset HEAD~1` | Undo last commit (soft) |
| `git revert <commit_id>` | Revert a commit (safe) |
| `git stash` | Save work temporarily |
| `git stash pop` | Restore stashed work |

</details>

---

<details>
<summary>🧽 Clean Git Setup Tips</summary>

| Tip | Reason |
|-----|--------|
| Use `.gitignore` | Avoid uploading unwanted files |
| Use `README.md` | Document your project |
| Use branches | Avoid editing main directly |
| Write clear commits | Helps understand history |
| Pull before push | Avoid conflicts |
| Commit often | Small changes = better tracking |

</details>

---

<details>
<summary>🔥 Open Source Contribution Tips</summary>

| Step | Why |
|------|-----|
| 🔀 Fork instead of clone | You can't push directly to the main repo |
| 🌱 Create a feature branch | Clean and isolated work |
| 💬 Describe your PR properly | Easier to review |
| 📖 Read `CONTRIBUTING.md` | Follow guidelines |
| 🔧 Solve issues or add features | Meaningful contributions |
| 📜 Add yourself to contributors if allowed | Recognition 💯 |

</details>

---

## ✅ TL;DR – Quick Git Commands

```bash
git init
git clone <url>
git add .
git commit -m "msg"
git push origin main
git pull origin main
git branch <branch>
git checkout <branch>
git merge <branch>
git remote add origin <url>
```

---

> 💡 **Pro Tip:** Always create a new branch for each new feature or fix. Never work directly on `main`.

---

### 📥 Like this README?

You can fork and use it for your own repo or dev notes.  
Feel free to Fork this And Try on this REPO ( Task to Commit (N.O - Myname Commited ) eg :- 1 kavya trivedi commited 
