# gh-deployment-workflow

A GitHub Actions CI/CD project from [roadmap.sh](https://roadmap.sh/projects/github-actions-deployment-workflow).

## What it does

- Hosts a static `index.html` on **GitHub Pages**
- A GitHub Actions workflow automatically redeploys the site every time `index.html` is pushed to `main`
- Uses path filtering — the workflow only triggers when `index.html` changes

## Live Site

🌐 [https://mythicc123.github.io/gh-deployment-workflow/](https://mythicc123.github.io/gh-deployment-workflow/)

## How to trigger a deployment

Edit `index.html` and push to `main`. The workflow fires automatically.
