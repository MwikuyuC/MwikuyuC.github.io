---
layout: post
title: "Week in Review: March 15-21, 2026"
date: 2026-03-21
categories: [personal, weekly]
---

## 🚀 What I Accomplished This Week

### Technical Achievements
- **Git Configuration:** Set up GPG signing for commits and SSH keys for GitHub authentication
- **Repository Management:** Created and configured git-extended repository using Git-flow
- **Release Management:** Successfully created releases v1.0.0 and v1.2.3 with automatic changelogs
- **Personal Website:** Started building this Jekyll site for GitHub Pages

### 📚 Key Learnings

#### Git & Version Control
- Mastered Git-flow branching strategy (master, develop, feature branches)
- Learned to sign commits with GPG keys
- Understood Semantic Versioning (MAJOR.MINOR.PATCH)
- Practiced Conventional Commits (feat, fix, chore, etc.)

#### Tools & Automation
- Installed and configured commitizen for conventional commits
- Used standard-changelog for automatic CHANGELOG generation
- Created GitHub releases with CLI tool

### 🛠️ Commands I Used
```bash
# Git-flow release process
git flow release start 1.2.3
standard-changelog
git flow release finish 1.2.3 -m "Release 1.2.3"
git push --all && git push --tags
gh release create v1.2.3 -F CHANGELOG.md

Next Week's Goals
Customize this website with a better theme

Learn GitHub Actions for CI/CD

Write more technical blog posts

Explore Docker basics

Thanks for reading! Follow my journey as I continue learning.
