# Parva Luminance Studios

Portfolio website for Parva Luminance Studios — photography, videography, and brand campaign work.

## What's included

- `index.html` — single-page site (HTML, CSS, and JavaScript)
- `assets/` — project photos, portfolio images, and videos
- `logo-color.png`, `logo-mono.png`, `grain.jpg` — branding assets

## Preview locally

Open `index.html` in your browser, or run a local server:

```bash
npx serve .
```

## Deploy to GitHub Pages

1. Create a new repository on GitHub (for example `parva-luminance-studios`).
2. Upload this entire folder, or push with git:

```bash
git init
git add .
git commit -m "Initial site export with assets"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/parva-luminance-studios.git
git push -u origin main
```

3. In the repo **Settings → Pages**, set source to **Deploy from branch** and choose `main` / `/ (root)`.
4. Your site will be live at `https://YOUR_USERNAME.github.io/parva-luminance-studios/`.

## Large file note

One video is about **105 MB** (`assets/portfolio/videography/copy_382B476E-1C52-49DE-81F1-A9A37AE564C4.mov`), which is above GitHub's 100 MB per-file limit. Options:

- Use [Git LFS](https://git-lfs.com/) for large videos, or
- Compress/replace that file before pushing, or
- Host large videos externally and update the paths in `index.html`.

## Structure

```
parva-luminance-studios/
├── index.html
├── logo-color.png
├── logo-mono.png
├── grain.jpg
└── assets/
    ├── creators/
    ├── portfolio/
    │   ├── photography/
    │   └── videography/
    └── projects/
        ├── buoy/
        ├── fiber-and-ore/
        ├── heirloom/
        └── lune/
```
