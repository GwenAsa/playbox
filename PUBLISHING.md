# Publishing this repository on GitHub

This package contains the repository presentation, documentation, SVG identity assets, and the screenshots supplied for PlayBox. It does not contain the application's source code or executable packages.

## 1. Create the GitHub repository

On GitHub, create a new repository named `playbox` under the account that owns the project. For a clean first push, leave **Add a README**, **Add .gitignore**, and **Choose a license** unchecked; this package already contains its README files, and the license should be selected deliberately.

## 2. Push the files

Open a terminal inside the extracted `PlayBox-Repository-Kit` directory and run:

```bash
git init -b main
git add .
git commit -m "docs: publish PlayBox project page"
git remote add origin https://github.com/GwenAsa/playbox.git
git push -u origin main
```

If you create the repository under a different account or name, replace the remote URL before running the commands.

## 3. Finish the repository settings

Use the description and topic suggestions in [`docs/REPOSITORY-SETUP.md`](docs/REPOSITORY-SETUP.md). Add the application source, release packages, installation instructions, and a chosen license when they are ready.
