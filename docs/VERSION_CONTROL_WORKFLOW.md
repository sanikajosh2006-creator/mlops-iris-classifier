# Version Control Workflow — MLOps Iris Classifier

## 1. Overview
This document describes the Git-based version control workflow used for this ML project.

- Repository: mlops-iris-classifier
- Primary language: Python
- Maintainer: Your Name

## 2. Branching Strategy
- main: Stable code
- develop: Integration branch
- feature/<name>: Individual features
- conflict-demo-*: Conflict resolution practice

## 3. Commit Convention
- feat: New functionality
- fix: Bug fixes
- docs: Documentation changes
- chore: Configuration changes
- refactor: Code restructuring

## 4. Standard Workflow
1. Switch to develop.
2. Create a feature branch.
3. Make changes.
4. Stage and commit.
5. Push the feature branch.
6. Create a Pull Request.
7. Review and merge.

## 5. Merge Conflict Resolution
1. Identify conflicting files.
2. Open the files.
3. Resolve conflict markers.
4. Run git add.
5. Commit the resolution.
6. Test the project.

## 6. Gitignore Policy
Exclude datasets, model files, virtual environments and notebook checkpoints.

## 7. Pull Request Checklist
- Code runs without errors.
- No large files are staged.
- Commit messages follow conventions.
- Branch is up to date.
- PR explains the changes.

## 8. Verification
- Git version checked.
- Branches created.
- Pull Request merged.
- Training script executed.
- Documentation created.