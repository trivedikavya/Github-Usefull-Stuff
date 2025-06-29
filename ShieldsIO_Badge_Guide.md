## 6. 🛡️ Shields.io Badge Master Guide (All Badge Types + Usage)

> A full collection of Shields.io badge styles grouped by topic. Each section includes a usage snippet and how to edit it.

---

### 🟢 Core  
**Basic Flat Badge**  
```md
![Badge](https://img.shields.io/badge/Hello-World-blue)
```
**Edit**: Replace `Hello`, `World`, `blue`.

---

### 🌀 Activity  
**Commit Activity**  
```md
![Commit Activity](https://img.shields.io/github/commit-activity/m/username/repo)
```
**Edit**: Use your GitHub `username/repo`.

---

### 📊 Analysis  
**Code Frequency**  
```md
![Code Frequency](https://img.shields.io/github/commit-activity/y/username/repo)
```

---

### ⚙️ Build  
**GitHub Workflow Status**  
```md
![Build Status](https://img.shields.io/github/actions/workflow/status/username/repo/workflow.yml)
```
**Edit**: Replace `username`, `repo`, `workflow.yml`.

---

### 💬 Chat  
**Discord Server Invite**  
```md
![Discord](https://img.shields.io/discord/123456789012345678)
```
**Edit**: Use your Discord server ID.

---

### 📦 Code Coverage  
**Codecov Coverage**  
```md
![Codecov](https://img.shields.io/codecov/c/github/username/repo)
```

---

### 📦 Dependencies  
**Depfu**  
```md
![Depfu](https://img.shields.io/depfu/username/repo)
```

---

### 📥 Downloads  
**npm Downloads**  
```md
![npm](https://img.shields.io/npm/dt/package-name)
```
**Edit**: Use your actual npm package name.

---

### 💸 Funding  
**GitHub Sponsors**  
```md
![Sponsors](https://img.shields.io/github/sponsors/username)
```

---

### 🐞 Issue Tracking  
**Open Issues**  
```md
![Issues](https://img.shields.io/github/issues/username/repo)
```

---

### 📄 License  
**MIT License**  
```md
![License](https://img.shields.io/github/license/username/repo)
```

---

### 🔍 Monitoring  
**Uptime Robot**  
```md
![Uptime Robot](https://img.shields.io/uptimerobot/status/m786460784-8a0b43b1db9c1c9a91f7e276)
```
**Edit**: Replace with your monitor ID.

---

### 🧪 Custom Endpoint  
**Custom JSON Badge**  
```md
![Custom](https://img.shields.io/endpoint?url=https://your.api/endpoint.json)
```
**Your JSON:**
```json
{
  "schemaVersion": 1,
  "label": "hello",
  "message": "sweet world",
  "color": "orange"
}
```

---

### 💻 Platform & Version  
**Node Version**  
```md
![Node](https://img.shields.io/node/v/package-name)
```

---

### ⭐ Rating  
**GitHub Stars**  
```md
![Stars](https://img.shields.io/github/stars/username/repo?style=social)
```

---

### 📦 Size  
**Bundle Size (min+gzip)**  
```md
![Size](https://img.shields.io/bundlephobia/minzip/package-name)
```

---

### 🌐 Social  
**Twitter (X) Follow**  
```md
![Twitter](https://img.shields.io/twitter/follow/username?style=social)
```

---

### ✅ Test Results  
**Travis CI**  
```md
![Travis](https://img.shields.io/travis/com/username/repo)
```

---

### 🧪 Version  
**PyPI Version**  
```md
![PyPI](https://img.shields.io/pypi/v/package-name)
```

---

### 🎨 Style Tips (Optional)  
Add styles to any badge:  
```md
?style=for-the-badge
?style=flat-square
?style=social
```

**Example with style:**  
```md
![Stars](https://img.shields.io/github/stars/username/repo?style=for-the-badge)
```