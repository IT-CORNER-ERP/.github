
## 🛠️ **Git Collaboration Guide for ERP Corner**  
This document is designed to streamline collaboration for the ERP Corner development team, ensuring efficient Git practices for optimal project management.

### 🔀 **Branching Strategy**  
At ERP Corner, we use a structured Git branching system to maintain code quality and enable seamless teamwork.

- **Main Branch**  
  Holds the production-ready version of the application. Changes here are tested and approved for end-users.  

- **Dev Branch**  
  A staging area where features are tested by the team. It’s one step before reaching the main branch.

- **Dev Authors Branch**  
  Used by individual developers or teams working on specific features. This branch is where active development occurs.

---

### 📜 **Common Git Commands**

#### **Staging Changes**  
Prepare changes for the next commit:
```bash
git add .
```

#### **Committing Changes**  
Save your staged changes with a descriptive message:
```bash
git commit -m "commit message"
```

#### **Pushing Updates**  
Upload changes to the remote repository:
```bash
git push
```

#### **Pulling Updates**  
Download changes from the remote repository:
```bash
git pull
```

#### **Pulling a Specific Branch**  
Sync your local branch with updates from a specific branch:
```bash
git pull origin branch
```

#### **Merging Branches**  
Combine changes from another branch:
```bash
git merge branch_name
```

---

### 🌿 **Branch Management**

#### **Listing Branches**  
See all branches in your repository:
```bash
git branch
```

#### **Switching Branches**  
Move between branches:
```bash
git checkout branch_name
```

#### **Creating a New Branch**  
Start a new branch for development:
```bash
git checkout -b new_branch_name
```

---

### ✍️ **Rewriting History**

#### **Rebasing Branch**  
Rebase your branch with the latest changes from another branch:
```bash
git rebase branch_name
```

#### **Resetting to a Commit**  
Undo changes back to a specific commit:
```bash
git reset commit_hash
```

---

### 📘 **Naming Conventions**

To keep our Git history clear and organized, we follow these guidelines:

#### **Branch Names**  
- **Base Branches**: `main`, `dev`  
- **Sub Branches**: `dev_authors`

#### **Commit Messages**

Use the following structure for commit messages:
```
<type>(<module>): <description>
```
- **Type**: Describes the type of change.  
  - `feat`: New feature or enhancement.  
  - `fix`: Bug fixes or corrections.
  
- **Module**: The module affected by the changes (e.g., `sales`, `warehouse`, `master`).

- **Description**: A brief summary of the change made.

**Example**:
- `feat(sales): create CRUD menu interface`  
- `fix(master): update serializer to match model`

---

We hope these guidelines enhance collaboration and make using Git more efficient for everyone. Let's continue building amazing ERP solutions together! 🚀✨

---
