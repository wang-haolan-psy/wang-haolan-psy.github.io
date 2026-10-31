# Haolan Wang's Academic Homepage

Personal academic homepage of Haolan Wang (王淏蘭), deployed on GitHub Pages.

**Live site:** https://wang-haolan-psy.github.io/

## Structure

```
├── index.html      # single-page homepage (no build step, no dependencies)
└── assets/
    └── photo.jpg   # portrait photo (resized to 640px)
```

## How to publish

This folder is the git repository for the GitHub Pages user site
(`wang-haolan-psy.github.io`). From this directory:

```bash
git init
git add .
git commit -m "Initial homepage"
git branch -M main
git remote add origin https://github.com/wang-haolan-psy/wang-haolan-psy.github.io.git
git push -u origin main
```

Then on GitHub: **Settings → Pages** → Source: *Deploy from a branch* →
Branch: `main` / `/ (root)` → Save. The site goes live at
`https://wang-haolan-psy.github.io/` within a few minutes.

## How to update

Edit `index.html` and push to `main`. Add news items to the News section,
new papers to the Publications section.

## Privacy note (first version, 2026-10)

By design this site contains **only**: bio, research interests, education,
publications, and selected public honors. It deliberately **excludes**:
phone number, date of birth, hometown, political affiliation, grant/project
details, internship history, and any CV download. Keep it that way unless
you decide otherwise.
