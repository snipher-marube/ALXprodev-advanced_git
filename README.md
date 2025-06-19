## Advanced Git Concepts
This document covers advanced concepts in Git, including rebasing, cherry-picking, and resolving merge conflicts.
### Rebasing
Rebasing is a way to integrate changes from one branch into another by moving or combining a
series of commits to a new base commit. This can help maintain a cleaner project history.
To rebase a branch, use the following command:
```bash
git checkout feature-branch
git rebase main
```