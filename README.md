# FlexiSAF Internship: Advanced Version Control

## Overview

This repository is a practical demonstration of advanced version control workflows using the command line. It was created as part of the FlexiSAF Internship Program (Advanced Track) to practice essential Git commands, branch management, and safe code-reversion techniques.

## Project Walkthrough & Learning Outcomes

Here is a breakdown of the exact Git workflow practiced in this repository:

### 1. Project Initialization & Best Practices

- **Setup:** Created a new directory (`flexisaf-version-control`) and initialized a local Git repository from scratch.
- **.gitignore:** Created a `.gitignore` file right away to ensure standard environment files and heavy folders (like `.env`, `.DS_Store`, and `node_modules/`) are kept out of version control.
- **First Commit:** Created a starter `app.js` file and made the initial project commit.

### 2. Feature Branching & Renaming

- **Branch Creation:** Instead of working directly on the main branch, I created an isolated feature branch initially named `feature/user-authentication` to build a mock login function.
- **Branch Renaming:** To practice branch management, I used the `git branch -m` command to rename the branch to something more concise: `feature/auth-module`.

### 3. Safely Reverting Commits

- **Making a Mistake:** I intentionally added a temporary debug console log to `app.js` and committed it to the branch.
- **Using Git Revert:** Instead of deleting the code manually, I used the `git revert HEAD` command. This allowed me to safely undo the mistake and record the reversal in the Git history without rewriting past commits.

### 4. Merging and Remote Syncing

- **Merging:** Switched back to the `main` branch and successfully merged the completed `feature/auth-module` into it.
- **Pushing Upstream:** Connected my local repository to GitHub using `git remote add origin` and pushed my finalized, clean `main` branch upstream to share my progress.

## Summary

By following this sequence, I gained hands-on experience with a realistic development workflow. It reinforced how to keep a project clean, how to manage feature branches efficiently, and how to safely correct mistakes using the command line.
