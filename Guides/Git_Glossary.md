# 📖 Git & GitHub Glossary

Confused by the jargon? Here is a plain-english translation.

## 🌳 Core Concepts

### **Repository (Repo)**
The folder where your project and its history live. Think of it as the "Project Folder."

### **Commit**
A save point. Unlike "saving" a file (Ctrl+S), a commit saves the state of the *entire* project and includes a message explaining what changed.

### **Branch**
A parallel version of your code.
* **Main/Master:** The "official" working version.
* **Feature Branch:** A sandbox where you experiment without breaking the main version.

### **Merge**
Taking the changes from one branch (e.g., your experiment) and combining them into another (e.g., the main version).

---

## 🤝 Collaboration Terms

### **Fork**
A personal copy of someone else's repository. It lives on *your* GitHub account. You can do whatever you want with it without affecting the original.

### **Clone**
Downloading a repository from the cloud (GitHub) to your local computer so you can work on it.

### **Remote**
The link between your computer and GitHub.
* **Origin:** The link to *your* fork.
* **Upstream:** The link to the *original* creator's repository.

### **Pull Request (PR)**
A request to merge your changes into someone else's code. You are saying, *"Hey, I fixed this on my copy (Fork), please pull it into your original version."*

### **Merge Conflict**
When two people try to change the exact same line of code at the same time. Git gets confused and asks you to pick which version is correct.

### **CI/CD (Continuous Integration/Deployment)**
Robots that run tests automatically every time you push code. If the tests pass, the robots might even deploy your website for you.
