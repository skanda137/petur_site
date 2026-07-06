# ग्रामपंचायत पेटुर — Static Website

Static HTML/CSS site (no backend) for Gram Panchayat Petur, Taluka Wani, District Yavatmal (PIN 445304).

## Contents
- 32 HTML pages (index.html is the homepage)
- styles.css — shared stylesheet
- assets/ — local fonts (Marathi) + emblem SVGs (no external CDN)
- images/ — all photos

## Host free on GitHub Pages
1. Create a new GitHub repository (e.g. `petur-gp`).
2. Upload **all** files and folders in this directory to the repo root
   (index.html must be at the top level, not inside a subfolder).
   - CLI: `git init && git add . && git commit -m "site" && git branch -M main && git remote add origin <repo-url> && git push -u origin main`
3. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main` → `/ (root)` → Save.
4. Wait ~1 minute. Your link: `https://<username>.github.io/<repo>/`

Note: GitHub Pages URLs are case-sensitive. All files here are lowercase.

## Notes
- No backend: forms show a confirmation message only; "प्रमाणपत्र स्थिती", "तक्रार स्थिती", "कर भरणा" are informational.
- "नकाशावर पहा" buttons open Google Maps at each location.
- Placeholder fields (phone, email, member names, announcements) are intentionally empty pending official data.
