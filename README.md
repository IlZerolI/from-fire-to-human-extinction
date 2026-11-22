# From Fire to Human Extinction

Presentation companion website. Built as a static site for GitHub Pages alongside the group presentation.

## What's in this folder
- `index.html` — the website (edit text, colors, or timeline here)
- `From fire to human extinction.pptx` — the slide deck

## Edit the site
Open `index.html` in any text editor and change:
- Titles, subtitle, and card text in `<body>`
- The QR code target URL (see below)

## QR code
The QR code is generated client-side from `window.location.origin + window.location.pathname` in the `<script>` at the bottom of `index.html`. Once you publish to GitHub Pages, it will point to your live site automatically. To hard-code a specific URL, replace `pageUrl` with your `https://<user>.github.io/<repo>/` string.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `from-fire-to-human-extinction`). Do NOT initialize with a README.
2. In this folder, run:
   ```powershell
   git init
   git add .
   git commit -m "Add presentation companion website"
   git branch -M main
   git remote add origin https://github.com/<yourusername>/<your-repo>.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, select **Deploy from a branch**.
5. Branch: `main`, folder: `/ (root)`. Click **Save**.
6. Your site will be live at `https://<yourusername>.github.io/<your-repo>/` (usually within a minute).

## View locally
Just open `index.html` in your browser. No build step or server required.
