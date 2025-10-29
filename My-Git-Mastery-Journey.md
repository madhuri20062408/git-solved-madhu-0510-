# 🧠 My Git Mastery Challenge Journey

## Student Information
- **Name:** Ch.Madhuri
- **Student ID:** 23A91A0510
- **Repository:** https://github.com/madhuri20062408/git-solved-madhu-0510-
- **Date Started:** Oct 27, 2025
- **Date Completed:** Oct 29, 2025

---

## 🪄 Overview

This challenge helped me learn how to handle branches, merges, and conflicts.  
I practiced creating branches, merging them, resolving merge conflicts, reverting commits, tagging releases, and managing commits using reset and reflog.

---

## ⚔️ Merge 1: main + feature/new-feature (4 files)

### Conflict 1: app/main.js
- **Issue:** One branch used `console.log("Hello")`, the other used `"Hi"`.
- **Resolution:** Kept `"Hello"` and added `"Hi"` as a comment.
- **Strategy:** Manual conflict resolution by combining both.
- **Difficulty:** Easy
- **Time Taken:** 5 minutes

### Conflict 2: config/settings.json
- **Issue:** Different API URLs.
- **Resolution:** Merged both environments by adding `"dev"` and `"prod"` keys.
- **Strategy:** Manual merge of JSON content.
- **Difficulty:** Medium
- **Time Taken:** 10 minutes

### Conflict 3: docs/README.md
- **Issue:** Conflicting instructions for setup.
- **Resolution:** Combined both with clear section titles.
- **Strategy:** Manual text merge.
- **Difficulty:** Easy
- **Time Taken:** 7 minutes

### Conflict 4: scripts/install.sh
- **Issue:** Extra echo commands in one branch.
- **Resolution:** Retained both and cleaned duplicates.
- **Strategy:** Manual cleanup.
- **Difficulty:** Medium
- **Time Taken:** 10 minutes

---

## ⚔️ Merge 2: main + conflict-simulator (6 files)

### Conflict 1: scripts/logger.js
- **Issue:** Different logging formats (plain vs JSON)
- **Resolution:** Standardized to JSON logs for clarity.
- **Strategy:** Combined both log styles using a formatter function.
- **Difficulty:** Medium
- **Time Taken:** 10 minutes

### Conflict 2: scripts/alert.sh
- **Issue:** One used curl, another used mail command.
- **Resolution:** Added a flag to switch between both methods.
- **Strategy:** Conditional logic to support both environments.
- **Difficulty:** Medium
- **Time Taken:** 12 minutes

### Conflict 3: docs/setup.md
- **Issue:** Dev vs Prod instructions conflicted.
- **Resolution:** Split into “For Development” and “For Production”.
- **Strategy:** Manual text merge with clear headings.
- **Difficulty:** Easy
- **Time Taken:** 8 minutes

### Conflict 4: src/utils.js
- **Issue:** Duplicate function names.
- **Resolution:** Renamed one function and documented both.
- **Strategy:** Code rename and documentation.
- **Difficulty:** Medium
- **Time Taken:** 10 minutes

### Conflict 5: index.html
- **Issue:** Different footer credits.
- **Resolution:** Combined both credit lines in one footer.
- **Strategy:** Manual text merge.
- **Difficulty:** Easy
- **Time Taken:** 5 minutes

### Conflict 6: styles/main.css
- **Issue:** Color scheme difference.
- **Resolution:** Created unified color variables.
- **Strategy:** Merged both color sets with comments.
- **Difficulty:** Easy
- **Time Taken:** 10 minutes

---

## 🧩 Reset & Revert Practice

- Made a bad commit (`"Bad commit"`) intentionally.
- Used `git revert HEAD` to undo it safely.
- Practiced `git reset --soft`, `--mixed`, and `--hard` to understand differences.
- Recovered lost commit using `git reflog` and `git cherry-pick`.

---

## 🏷️ Tagging Practice

```bash
git tag -a v1.0.0 -m "Release 1.0.0: Resolved all conflicts"
git tag -a v1.1.0 -m "Release 1.1.0: Added all features"
git push origin --tags
