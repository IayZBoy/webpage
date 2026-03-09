# Webpage

This repo is configured to deploy `index.html` to GitHub Pages automatically from the `main` branch.

## 1) Create a GitHub repository

Create an empty repository on GitHub, for example `webpage`.

## 2) Connect this folder and push

Replace `<your-username>` and `<your-repo>`:

```powershell
git add .
git commit -m "Initial site with GitHub Pages deployment"
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

## 3) Enable Pages (one-time)

In GitHub:

1. Open `Settings` -> `Pages`
2. Under `Build and deployment`, set `Source` to `GitHub Actions`

After the workflow finishes, your live URL will be:

`https://<your-username>.github.io/<your-repo>/`

If the repository is named `<your-username>.github.io`, the URL is:

`https://<your-username>.github.io/`
