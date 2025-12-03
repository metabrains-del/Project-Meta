# Contributing to This Project

Thank you for your interest in contributing! Please follow the guidelines below to ensure smooth collaboration and consistent quality throughout the project.

---

## 🐛 How to Open Issues

Before creating an issue:
- Search existing issues to check if your topic already exists.
- Provide a clear title that summarizes the problem or suggestion.
- Include detailed steps to reproduce the issue (if reporting a bug).
- Add relevant screenshots, logs, or code snippets.
- Label the issue correctly (bug, feature, enhancement, documentation).

**Issue Format Example:**
```
Title: Login page throws 500 error on submit

Description:
- Expected behavior
- Actual behavior
- Steps to reproduce
- Environment info (OS, Browser, Version)
- Additional context
```

---

## 🌿 Branch Naming Rules

Create a new branch for every feature, bug fix, or update.  
Use this naming structure:

```
feature/<short-description>
bugfix/<short-description>
hotfix/<short-description>
docs/<short-description>
refactor/<short-description>
```

**Examples:**
```
feature/add-user-auth
bugfix/fix-navbar-overflow
docs/update-readme
```

Branch naming should always use lowercase and hyphens.

---

## 🔀 Pull Request Process

Follow these steps when submitting a Pull Request:

1. Ensure your branch is updated with the latest `main`.
2. Run all tests and ensure the build passes.
3. Write clear, descriptive commit messages.
4. Include screenshots or GIFs if the change affects UI.
5. Reference related issues using:
   ```
   Closes #123
   ```
6. Request review from at least one maintainer.
7. PR titles must follow this format:
   ```
   [Feature] Add user authentication
   [Fix] Correct API URL in config
   [Docs] Update contributing guide
   ```

**Your PR will be merged only if:**
- Code follows standards  
- CI checks pass  
- Reviews are approved  

---

## 🧩 Coding Style Guidelines

Please follow these conventions:

### **General**
- Keep code clean, readable, and modular.
- Use meaningful variable and function names.
- Remove unused imports, console logs, and commented code.
- Follow the existing project structure.

### **JavaScript/React**
- Use ES6+ features.
- Use functional components.
- Prefer hooks over class components.
- Use consistent indenting (2 spaces).
- Always format code with Prettier (if available).

### **Python/Django**
- Follow PEP8 standards.
- Use snake_case for variables and functions.
- Keep views small and focused.
- Avoid repeating code (follow DRY principles).

---

## 📝 Commit Message Format

Use structured, clear commit messages.  
Format:

```
<type>: <short description>

[optional body with more detail]
```

### **Allowed Types**
```
feat     → new feature
fix      → bug fix
docs     → documentation change
style    → formatting only
refactor → code restructure
test     → adding or updating tests
chore    → maintenance tasks
```

### **Examples**
```
feat: add login API endpoint
fix: resolve crash on empty input
docs: update environment setup instructions
refactor: optimize dashboard rendering logic
```

Commit messages should be brief, meaningful, and written in present tense.

---

Thank you for helping improve this project! 🚀
