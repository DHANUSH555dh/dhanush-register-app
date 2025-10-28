# How to publish this project on GitHub (for beginners)

1. Create a GitHub account at https://github.com if you don't have one.
2. On GitHub, click "New" to create a new repository.
   - Name it: `dhanush-register-app`
   - Optionally add a description.
   - **Do NOT** initialize with README or license if you're going to push an existing local repo.
3. Locally, open a terminal in the project folder and run:
```bash
git init
git add .
git commit -m "Initial commit - personalized fork by Dhanush Guntumadugu"
git branch -M main
git remote add origin https://github.com/<your-username>/dhanush-register-app.git
git push -u origin main
```
4. If the repo already has history and you want to keep it, consider forking the original repo on GitHub and then pushing your changes to your fork.
5. After pushing, open your GitHub repo page and add topics, a nice README, and screenshots.

**Important:** If the original project license requires attribution or other constraints, include that in your README before publishing.
