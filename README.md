# HYF Week 8 — Accessibility Testing Corrections

Corrections page for HackYourFuture Denmark QA Team 2026, Week 8 (Accessibility Testing).

Live site: https://aguspe.github.io/hyf-accessibility-corrections/

## Structure

- `index.html` — corrections page (rubric, per-student feedback)
- `submissions/` — student-submitted PDFs, DOCX, and code
- `.github/workflows/pages.yml` — auto-deploys to GitHub Pages on push to `main`

## Updating corrections

Edit the relevant `<div class="student-card">` block in `index.html`. Replace the
`pending` class on the `correction` div with `good` / `improve` / `missing`,
update the status badge, and commit. GitHub Actions will redeploy automatically.
