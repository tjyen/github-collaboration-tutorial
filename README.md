# 🚀 Git × GitHub Collaboration Tutorial: Beginner-Friendly Interactive Course

Welcome! This tutorial guides you through a hands-on Git and GitHub collaboration workflow — all within the **GitHub web interface**. You’ll practice version control, branching, pull requests, code reviews, and merge workflows, just like contributing to a real open-source project.

---

## 📚 Course Overview

**Objective**: Simulate a real-world GitHub collaboration workflow.

### 🔁 Workflow Steps

1. **You open an issue** to request adding your profile.
2. **Fork** this repository.
3. **Create a new branch** in your fork.
4. **Add your profile** and link it in the main file.
5. **Commit your changes** with clear, meaningful messages.
6. **Open a Pull Request (PR)** to the main repository.
7. The maintainer **reviews your PR** and may request changes.
8. You **revise and update your PR** accordingly.
9. The maintainer **approves and merges** your contribution.

---

## 🛠️ Your Task

### ✅ Step 1. Open an Issue

- Go to the [Issues tab](../../issues).
- Click **New Issue** and title it:  
  `Add profile for your-github-username`
- Briefly describe your intent to contribute a profile.

### ✅ Step 2. Fork & Branch

- Click **Fork** (top right) to create a copy of this repo under your account.
- In your fork, create a new branch:  
  `your-github-username/feature-profile`

### ✅ Step 3. Make Two Edits

- In `profiles/your-github-username.md`, add:

  ```markdown
  # your-github-username
  ```

- In `hello.md`, add a link to your profile with a short message:

  ```markdown
  - [your-github-username](profiles/your-github-username.md): Your message here.
  ```

### ✅ Step 4. Commit

- Write a clear commit message:
  
  ```markdown
  [feat] Add profile, link, and message to hello.md
  ```

### ✅ Step 5. Open Pull Request

- Submit a PR to the `main` branch of this repository.
- Mention your issue number, e.g., "Closes #12"

### ✅ Step 6. Respond to Review

- The maintainer may request changes:
  > Please add a self-introduction in your profile file.
- Edit the file and commit again:

  ```markdown
  [fix] Add self-introduction to profile
  ```

### ✅ Step 7. Merge

- After approval, the maintainer will **squash-and-merge** your PR.
- Your contribution will be added, and the issue closed 🎉

---

## 💬 Need Help?

Open an [issue](../../issues) if you have questions.

Happy contributing 🎉
