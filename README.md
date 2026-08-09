# Open Shelf

A small static e-book library, built in deliberate phases. This version is fully static: it has a first book card and five empty e-book slots, with no S3 or backend dependency.

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. In **Settings → Pages**, choose **Deploy from a branch**, select `main`, and choose the `/website` folder.

After GitHub Pages finishes deploying, the site will be available at:
`https://YOUR-GITHUB-USER.github.io/REPOSITORY-NAME/`

## Local preview

Open `website/index.html` in a browser.

## Planned structure

```
website/       Static GitHub Pages site
terraform/     Infrastructure as code (Phase 4)
.github/       CI/CD workflows (Phase 3)
```
