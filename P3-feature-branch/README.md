# P3 — Feature-branch Git workflow

```bash
git switch -c feature/about-section
# Make and save your changes
git add .
git commit -m "Add about section"
git push -u origin feature/about-section
````

Create a Pull Request on GitHub, review it, and merge into `main`. Then:
```bash
git switch main
git pull origin main
git branch -d feature/about-section
```