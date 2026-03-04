# 🚀 Software Developer Collaboration Board

Welcome to the **Software Developer Collaboration Board Activity**.

In this exercise, you will practice a **real-world Git workflow**:

- Forking a repository

- Cloning a project

- Creating branches

- Updating your branch

- Making commits

- Pushing to GitHub

- Opening a Pull Request

---

# 🎯 Objective

Each student must:

- Add their personal developer card to the project

- Follow a professional Git workflow

- Open a Pull Request for review

---

# 📌 Rules

- ❌ Do NOT modify other students' cards

- ❌ Do NOT push directly to `main`

- ✅ Work only in your own branch

- ✅ Follow clean code formatting

- ✅ Use meaningful commit messages

---

# 🛠 Step-by-Step Instructions

---

## 1️⃣ Fork the Repository:

Click the **Fork** button on GitHub to create your own copy of this repository in 
your account.

---

## 2️⃣ Clone Your Fork:

Clone your forked repository to your local machine:

```bash
git clone https://github.com/YOUR-USERNAME/git-and-github-collaboration-board.git
```

Move into the project folder:

```bash
cd git-and-github-collaboration-board
```

---

## 3️⃣ Make Sure Your Repository Is Updated:

Before creating your branch, update your local `main`:

```bash
git checkout main
git pull origin main
```

---

## 4️⃣ Create a New Branch:

Create a branch using your GitHub username:

```bash
git checkout -b feature/YOUR-GITHUB-USERNAME
```

Example:

```bash
git checkout -b feature/janedoe
```

---

## 5️⃣ Add Your Student Card:

Open the index.html file.

Inside the Students section, copy the example student card and:

- Replace with your full name

- Add your country

- Add your role

- Add your tech stack

- Add your learning focus

- Add your goal


Save the file.

---

## 6️⃣ Create a meaningful commit message:

```bash
git commit -am "Add student card - Jane Doe"
```

---

## 7️⃣ Switch to the `main` branch:

```bash
git checkout main
```

---

## 8️⃣ Merge with the `feature branch`:

```bash
git merge feature/janedoe
```

**Delete the `feature branch`**:

```bash
git branch -d feature/janedoe
```

---

## 9️⃣ Push the main branch:

```bash
git push -u origin main
```

---

## 🔟 Open a Pull Request:

1. Go to your fork on GitHub

2. Click Compare & Pull Request

3. Ensure:

    - Base repository: original project

    - Base branch: main

4. Add a clear PR title:

```
Add student card - Your Name
```

5. Submit the Pull Request

---

## 🔎 Before Submitting Your Pull Request

- ✅ Does the HTML structure remain valid?

- ✅ Did you avoid modifying other cards?

- ✅ Is your formatting consistent?

- ✅ Did you use a clean commit message?

- ✅ Did you avoid merge conflicts?

--- 

## 🧠 Professional Workflow Summary

```bash
Fork → Clone → Update → Branch → Code → Commit → Merge → Push → PR
```

This is how real software teams collaborate.

---

## 🏆 Bonus Challenge (Optional)

- Keep students alphabetically ordered

- Add your GitHub profile link inside your card

- Improve semantic HTML

- Fix any layout bug you find

---

## 💬 Final Note

- This activity simulates a real-world development workflow.

- Take it seriously.

- Write clean code.

- Use Git professionally.

- Welcome to real software collaboration 🚀
