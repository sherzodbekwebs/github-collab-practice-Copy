# Git Workflow Guide

## 1. Create a Branch

```bash
git switch main
git pull origin main
git switch -c feature/my-feature
```

## 2. Make Changes

Keep each branch focused on one improvement.

## 3. Commit Changes

```bash
git add .
git commit -m "feat: add new feature"
```

## 4. Push Branch

```bash
git push -u origin feature/my-feature
```

## 5. Create Pull Request

Open a Pull Request from the feature branch into `main`. Describe the changes and test results.

## 6. Review and Merge

Review the diff, resolve feedback, and merge when ready.

## 7. Clean Up

After merging, update your local `main` branch and delete the old feature branch if no longer needed.
