# Arman Khachatryan Portfolio

A static portfolio site for Arman Khachatryan: Analytics, Business Intelligence &amp; Applied AI. This is a faithful rebuild of the content from his previous site, hosted here so it lives on his own GitHub Pages account instead of a third-party subdomain.

## Structure

- `index.html` — homepage (hero, selected work, experience, skills, education, services, contact)
- `projects/retail-tableau/` — Retail performance in Tableau
- `projects/santander-classification/` — A fair classification comparison
- `projects/real-estate-ai/` — Real estate listing automation
- `projects/lendingclub-analysis/` — Six years of lending patterns
- `projects/nutrition-regularization/` — Nutrition prediction with regularization
- `assets/style.css` — single shared stylesheet
- `assets/` — project images, hosted locally
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Publish on GitHub Pages

1. On GitHub, signed in as Arman-MSBA, create a new **public** repository named exactly `arman-msba.github.io`.
2. Push these files to the `main` branch of that repository:
   - `git init`
   - `git add .`
   - `git commit -m "Portfolio site"`
   - `git branch -M main`
   - `git remote add origin https://github.com/Arman-MSBA/arman-msba.github.io.git`
   - `git push -u origin main`
3. In the repository, go to Settings, Pages, and confirm the source is "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site will be live at `https://arman-msba.github.io` within a few minutes.

## Notes

- The two Tableau workbook files (retail-performance.twbx and retail-analytics.twbx) return 404 on the old host too, so the download buttons were removed from the retail page. If you still have the .twbx files, drop them into `assets/` and re-add download links pointing at `../../assets/retail-performance.twbx` and `../../assets/retail-analytics.twbx`.
- Copy rule: no em dashes anywhere in the site copy. Use commas, colons, or restructured sentences instead.
- No new facts, projects, or metrics were invented. All words and numbers come from the previous site.
