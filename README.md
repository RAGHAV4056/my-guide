
# Git & GitHub Workflow

This is a test file written in `README.md`, which is a markdown file.

Listed below is how Git and GitHub work:

---

### Step-by-step Guide

**Step 0:** Create Repo on Github with the name `my-guide` as example here

**Step 1:** Initialize your repository  
```bash
git init
```
*Initializes a Git repository. After this, code can be pushed to GitHub.*

---

**Step 2:** Create relevant files and add your code  
Example:  
```text
README.md added
```

---

**Step 3:** Check the status of your files  
```bash
git status
```
- If files are **untracked**, you need to **add and commit** them before pushing.  
- If files are in the **staging area**, you need to **commit** them before pushing.  
- If files are already **committed**, you just need to **push** them.

---

**Step 4:** Add untracked files  
```bash
git add [filename]     # Adds a specific file  
git add .              # Adds all files
```

---

**Step 5:** Commit files in the staging area  
```bash
git commit -m "[your commit message]"


---

**Step 6:** Add a remote origin  
```bash
git remote add origin https://github.com/RAGHAV4056/my-guide.git
```

**Step 7:** Branch  
```bash
git branch -M main
```

---

**Step 8:** Push the changes  
```bash
git push -u origin main
```
