# Uttam Sahani: Portfolio

Single-page portfolio built with HTML5, CSS3 and vanilla JavaScript. No build tools, works on GitHub Pages.

## Structure

```
portfolio/
├── index.html
├── css/style.css
├── js/script.js
├── assets/
│   ├── images/          (put your photo here)
│   └── documents/       (put resume.pdf here)
└── README.md
```

## Before you publish

1. Resume, photo and AI Literacy certificate are already included in `assets/`. To replace the resume, overwrite `assets/documents/resume.pdf`.
2. **Canonical URL:** after deploying, uncomment the canonical line in `<head>` and add your site address.

## Test locally

Option A: double-click `index.html` to open it in your browser.

Option B (recommended): in this folder run
```
python -m http.server 8000
```
then open http://localhost:8000. (Or use the "Live Server" extension in VS Code.)

Check: dark/light toggle, mobile menu (narrow the window), all links, resume download.

## Deploy on GitHub Pages

1. Sign in to https://github.com and click **New repository**.
2. Name it `sahuttam982-dev.github.io` to get the address `https://sahuttam982-dev.github.io/` (or any name, e.g. `portfolio`, to get `https://sahuttam982-dev.github.io/portfolio/`). Set it to **Public** and create it.
3. Click **uploading an existing file**, drag in **everything inside** the `portfolio` folder (so `index.html` is at the top level of the repo), and click **Commit changes**.
4. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then **Save**.
5. Wait 1 to 2 minutes and refresh. Your site address appears at the top of the Pages screen.

To update later: edit or upload the changed file in the repository and commit. The site refreshes automatically.

## Adding more sections later

To add another certificate, copy one `<li>` inside the `certifications` section of `index.html` and edit the text. Languages, memberships and volunteer work can use the same pattern.
