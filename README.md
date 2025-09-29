# GitHub Deployment Workflow

This project demonstrates how to use **GitHub Actions** for Continuous Integration (CI) and Continuous Deployment (CD).  
It deploys a simple static website to **GitHub Pages** whenever the `index.html` file is updated.

---

## Project Structure

- `index.html` — A simple static web page that says **"Hello, GitHub Actions!"**
- `README.md` — Documentation explaining the project
- `.github/workflows/deploy.yml` — GitHub Actions workflow for automated deployment (to be created)

---

## Workflow Behavior

- The workflow runs automatically when changes are pushed to the repository.  
- Deployment is triggered **only if the `index.html` file changes**.  
- The updated site is published to **GitHub Pages**.

---

## How to Reproduce

1. Fork or clone this repository.
2. Ensure GitHub Pages is enabled:
   - Go to **Settings > Pages** in your repository.
   - Set the source to **GitHub Actions**.
3. Create a workflow file at `.github/workflows/deploy.yml` with the deployment configuration.
4. Commit and push changes to `index.html`.
5. Visit your GitHub Pages URL (e.g., `https://<username>.github.io/gh-deployment-workflow/`) to see the live site.

---

## Learning Objectives

- Understand the basics of **Continuous Integration** (CI) with GitHub Actions.
- Automate deployment to **GitHub Pages**.
- Learn how to conditionally run workflows based on file changes.

---
