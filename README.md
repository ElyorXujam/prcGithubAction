# Simple GitHub Actions CI/CD Project

A simple HTML website that demonstrates automated deployment to GitHub Pages using GitHub Actions.

## Overview

This project is a minimal example of setting up Continuous Integration and Continuous Deployment (CI/CD) with GitHub Actions. Every time code is pushed to the `main` branch, the workflow automatically deploys the website to GitHub Pages.

## Project Structure

```
.
├── .github/
│   └── workflow/
│       └── deploy.yml    # GitHub Actions workflow file
├── index.html            # Main HTML file
└── README.md             # This file
```

## Features

- 🤖 **Automated Deployment**: Automatic deployment to GitHub Pages on every push to `main`
- 🚀 **Zero Configuration**: Minimal setup required
- 📦 **Simple Structure**: Clean and straightforward project layout

## How It Works

1. When you push code to the `main` branch, GitHub Actions triggers the workflow
2. The workflow checks out your code
3. It automatically deploys the site to GitHub Pages using the `actions/deploy-pages@v2` action

## Customization

You can customize the website by editing `index.html`. The changes will be automatically deployed when you push to the `main` branch.


This project is part of [roadmap.sh](https://roadmap.sh/projects/github-actions-deployment-workflow) DevOps projects.

