# P3 — Feature-Branch Git Workflow

**Name:** Devansh Bansal | **Course:** B.Tech CSE (AI & ML)

## Aim
To implement a feature using a separate Git branch and merge it through a Pull Request.

## Procedure
1. Create and switch to a feature branch.
2. Make changes and commit them.
3. Push the branch to GitHub.
4. Open a Pull Request, review it, and merge it into main.
5. Update main and remove the feature branch.

## Commands
```bash
git switch -c feature/about-section
git add .
git commit -m "Add about section"
git push -u origin feature/about-section
# Create and merge a Pull Request on GitHub
git switch main
git pull origin main
git branch -d feature/about-section
```

## Output
The feature changes are merged into the main branch on GitHub.

## Result
Successfully followed a feature-branch workflow using Git and GitHub.