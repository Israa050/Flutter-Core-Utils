# 🧩 Flutter Core Modules Repository

A reusable **Flutter Core Modules** repository designed to save time and ensure consistency across all your Flutter projects.  
This repository contains the **core structure, reusable utilities, and base configurations** that are commonly used in your apps — allowing you to kickstart new projects faster and maintain a clean, scalable architecture.

---

## 🚀 Why Use This Repository?

Instead of manually recreating your common setup every time you start a new Flutter project, this repository allows you to:

- ✅ **Save setup time** — Start new projects instantly with pre-built core folders.
- ✅ **Maintain consistency** — Follow the same architecture and best practices across all projects.
- ✅ **Simplify updates** — Update shared logic in one place and pull the changes across all projects.
- ✅ **Encourage modularity** — Keep reusable code isolated and easily maintainable.

---

## 🏗️ Repository Structure

Here’s a general overview of what’s included:


You can customize and extend this structure depending on your project’s requirements.

---

## ⚙️ How to Use This Repository

You can integrate this repository into any Flutter project using **Git Submodules**.

### 1. Add as a Submodule

From your Flutter project root directory, run:

```bash
git submodule add https://github.com/Israa050/Flutter-Core-Utils
```

### 2. Pull Updates from the Core Repository
```bash
git submodule update --remote
```

### 3. Remove the Submodule (if needed)
```bash
git submodule deinit -f core
rm -rf .git/modules/core
git rm -f core
```
---

# 🧭 Example Usage Flow

### 1. Create a new Flutter project:
```bash
flutter create my_new_app
cd my_new_app
```

### 2. Add your core modules:
```bash
git submodule add https://github.com/Israa050/Flutter-Core-Utils
```

### 3.Import and use:
```bash
import 'package:core/core.dart';
```

---

# 🏁 Final Note

This setup makes starting new projects easier and ensures your Flutter apps share the same strong foundation.
Just clone, integrate, and start coding — no more repetitive setup!

## 🤝 Contribution  

Contributions are always welcome! 💡  

1. Fork the repo 🍴  
2. Create a feature branch 🌱  
3. Commit your changes 💬  
4. Push and create a PR 🚀  

Please make sure your code follows the existing **architecture** and **naming conventions**.  

---

## 👨‍💻 Author  

**Israa Essa**  
💼 Flutter Developer

🌐 Portfolio: [https://www.linkedin.com/in/israa-essa-3b5644384] 

💻 GitHub: [Israa050]  

---
