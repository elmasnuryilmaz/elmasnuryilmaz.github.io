# elmasnuryilmaz.github.io

Personal website for Elmasnur Yılmaz — RNA biologist & computational genomicist.
Single self-contained `index.html` (no build step, no dependencies).

## Files
- `index.html` — the whole site (HTML + CSS + JS inline)
- `Elmasnur_Yilmaz_CV.pdf` — linked by the "Download CV" buttons

## Deploy to GitHub Pages
From this folder:

```bash
git init
git add .
git commit -m "New personal website"
git branch -M main
git remote add origin https://github.com/elmasnuryilmaz/elmasnuryilmaz.github.io.git
git push -u origin main
```

If the repo already exists, **clone it** rather than starting a fresh history:

```bash
git clone https://github.com/elmasnuryilmaz/elmasnuryilmaz.github.io.git
# edit, then
git add -A && git commit -m "Update the site" && git push
```

Do not `git init` in a folder of loose files and force-push it. Whatever the
folder is missing gets deleted from the live site without a word — and this repo
holds files that are easy to forget: `google83c6d5b98e51769c.html` is the Google
Search Console verification, and removing it unverifies the site.

GitHub Pages serves `<username>.github.io` repos automatically from the `main`
branch root. The site is live at https://elmasnuryilmaz.github.io within a minute.

## Updating the CV
Replace `Elmasnur_Yilmaz_CV.pdf` (keep the same filename), then commit & push.
