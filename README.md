# blog

[![Deploy Hugo site to Pages](https://github.com/mirmousaviii/blog/actions/workflows/hugo.yml/badge.svg)](https://github.com/mirmousaviii/blog/actions/workflows/hugo.yml)

Personal website/blog built with [Hugo](https://gohugo.io/) and [Mostafa hugo theme](https://github.com/mirmousaviii/mostafa-hugo-theme).

This website is built with **Hugo** and is automatically deployed to **GitHub Pages** using **GitHub Actions**. The deployment process ensures that the site always stays up-to-date with the latest changes from both the content and the theme.

## 📌 How Deployment Works

- **GitHub Actions** is configured to build and deploy the site whenever:
  - New changes are pushed to the `main` branch.
  - A webhook triggers an update when the theme repository is updated.

- **Webhooks Integration:**  
  - The site follows the latest changes from the `mostafa-hugo-theme` repository.
  - When the theme is updated, a webhook sends a request to this repository, triggering a GitHub Actions workflow to rebuild and deploy the site.

## 🚀 Automated Workflow

1. **Push Content Updates:**  
   - Any changes to the `main` branch trigger a new deployment.

2. **Theme Updates via Webhooks:**  
   - When the `mostafa-hugo-theme` repository gets updated, a webhook notifies this repository.
   - GitHub Actions then pulls the latest theme version, rebuilds the site, and deploys it.

3. **Deployment to GitHub Pages:**  
   - The final build is published on **GitHub Pages**, ensuring the site remains live and updated.

## 🛠 Running Locally

To test the site locally, clone the repository and run:

```bash
hugo server
```

Then, open `http://localhost:1313` to preview your site.
