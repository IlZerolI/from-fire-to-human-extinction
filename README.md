# From Fire to Human Extinction

Premium presentation companion website for a class of 27 students (9 groups of 3).

## Theme
Innovations that built civilisation — and how each could end it.
From mastery of fire to artificial intelligence, every breakthrough carries an extinction risk.

## What's in this folder
- `index.html` — the premium website (animated timeline, interactive groups, QR code)
- `GROUP_ASSIGNMENTS.md` — 9 groups of 3 students, each owning one innovation
- `README.md` — this file
- `From fire to human extinction.pptx` — the slide deck

## Class groups (see GROUP_ASSIGNMENTS.md)

1. Mastery of Fire — Students 1, 2, 3
2. Agriculture — Students 4, 5, 6
3. Printing Press — Students 7, 8, 9
4. Steam Engine — Students 10, 11, 12
5. Nuclear Fission — Students 13, 14, 15
6. The Transistor — Students 16, 17, 18
7. Recombinant DNA — Students 19, 20, 21
8. The World Wide Web — Students 22, 23, 24
9. Artificial Intelligence — Students 25, 26, 27

## Features
- Animated particle background + entrance reveals
- Interactive timeline with detail modals per innovation
- Glassmorphism cards & premium dark theme
- Client-side QR code generator (downloadable PNG)
- Fully responsive, no build step required

## Edit the site
Open `index.html` in any text editor. The `innovations` array at the bottom of the `<script>` drives the timeline and groups — edit titles, eras, descriptions, and student assignments there.

## QR code
Generated client-side from the live page URL. Click "Download QR" to save a PNG. Replace the URL logic in script.js with your GitHub Pages link after deploying.

## Deploy to GitHub Pages

```powershell
git init
git add .
git commit -m "Add premium presentation website"
git branch -M main
git remote add origin https://github.com/<yourusername>/from-fire-to-human-extinction.git
git push -u origin main
```

Then in GitHub **Settings → Pages**: source = `main`, folder = `/ (root)`.
Site goes live at `https://<yourusername>.github.io/from-fire-to-human-extinction/`.

## View locally
Open `index.html` in your browser. No build step or server required.
