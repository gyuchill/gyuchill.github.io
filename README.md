# Donggyu Kim — GitHub Pages

This folder is a complete static site. No build system is required.

## 1. Create the GitHub Pages repository

Create a public repository named:

`YOUR-GITHUB-USERNAME.github.io`

Then upload **all files in this folder** to the repository root.

## 2. Enable GitHub Pages

GitHub:
`Settings → Pages → Build and deployment → Deploy from a branch`

Select:
- Branch: `main`
- Folder: `/ (root)`

Save.

Your site will be available at:

`https://YOUR-GITHUB-USERNAME.github.io/`

## 3. Personalize these items

Open `index.html` and replace:
- `YOUR_EMAIL@example.com`
- Google Scholar URL
- GitHub URL
- `#` paper links
- publication metadata if needed
- employment dates if needed

## 4. Profile photo

The current design uses a generated CSS chip graphic, so no image is required.
If you want a portrait, add `assets/profile.jpg` and replace the `.hero-visual` block with an `<img>` element.

## 5. Important

The website is intentionally framework-free:
- HTML
- CSS
- a tiny vanilla JavaScript smooth-scroll helper

It can be hosted directly by GitHub Pages.
