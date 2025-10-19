TASK_4: CI-CD Pipeline

Overview

GitHub Actions workflow to build the Java API (`TASK_1`) on each push/PR to `main`/`master`.

How to run this pipeline

1. Ensure your full project (including `TASK_1`) is committed to a Git repository.
2. Copy the `.github/workflows/ci.yml` from this folder to the repository root (or move the entire `.github` folder to the root).
3. Push to GitHub:
   - git init (if new)
   - git add .
   - git commit -m "Add CI"
   - git branch -M main
   - git remote add origin <your_repo_url>
   - git push -u origin main
4. Open the GitHub repo → Actions tab to watch the workflow build `TASK_1` with Maven.

What it does

- Checks out code
- Sets up JDK 17 (Temurin)
- Runs `mvn -B -q -e -DskipTests package` in `TASK_1`


