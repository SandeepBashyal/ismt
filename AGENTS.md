# AGENTS.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository Overview
This is a Git practice repository used for learning version control workflows. The repository contains simple text files used to practice branching, merging, and pull requests.

## Repository Information
- **Remote**: https://github.com/SandeepBashyal/ismt.git
- **Primary Branch**: `main`
- **Active Branches**: Multiple contributor branches (`sagar`, `sandeep`, etc.)

## Git Workflow
This repository follows a feature branch workflow where:
1. Each contributor works on their own named branch
2. Changes are pushed to their respective branches on origin
3. Pull requests are created to merge changes into `main`

### Common Git Commands
```bash
# Check current status and branch
git status

# Create and switch to a new branch
git checkout -b <branch-name>

# Push changes to your branch
git push origin <branch-name>

# Create a pull request (requires GitHub CLI)
gh pr create --base main --head <branch-name> --title "<PR Title>" --body "<Description>

Co-Authored-By: Warp <agent@warp.dev>"

# View all branches
git branch -a

# Sync with main branch
git checkout main
git pull origin main
```

## File Structure
The repository contains simple `.txt` files at the root level. Each file typically represents practice contributions from different team members learning Git workflows.
