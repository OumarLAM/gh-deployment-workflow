# GitHub Deployment Workflow

This project demonstrates how to use **GitHub Actions** for Continuous Integration (CI) and Continuous Deployment (CD).  
It deploys a simple static website to **GitHub Pages** whenever the `index.html` file is updated on the `main` branch.

---

## Live Website

🌍 The website is available here: [https://oumarlam.github.io/gh-deployment-workflow/](https://oumarlam.github.io/gh-deployment-workflow/)

---

## Project Structure

- `index.html` — A simple static web page that says **"Hello, GitHub Actions!"**
- `README.md` — Documentation explaining the project
- `.github/workflows/deploy.yml` — GitHub Actions workflow for automated deployment

---

## Workflow Behavior

- The workflow runs automatically on every push to the **main** branch.  
- Deployment is triggered **only if the `index.html` file changes**.  
- The updated site is published to **GitHub Pages**.  

---

## How to Reproduce

1. Fork or clone this repository.
2. Ensure GitHub Pages is enabled:
   - Go to **Settings > Pages** in your repository.
   - Set the source to **GitHub Actions**.
3. Review the workflow file: `.github/workflows/deploy.yml`
4. Commit and push changes to `index.html` on the `main` branch.
5. Visit your GitHub Pages URL (e.g., `https://<username>.github.io/gh-deployment-workflow/`) to see the live site.

---

## Learning Objectives

- Understand the basics of **Continuous Integration** (CI) with GitHub Actions.  
- Automate deployment to **GitHub Pages**.  
- Learn how to conditionally run workflows based on file changes.  

---
