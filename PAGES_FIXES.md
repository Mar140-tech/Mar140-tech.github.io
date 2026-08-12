# Removed failing Pages workflow

This branch removes the redundant and failing workflow `.github/workflows/deploy-pages.yml`.

Rationale:
- The built-in GitHub Pages "pages build and deployment" process is already successfully deploying the site on pushes to main.
- The custom workflow was failing and created noisy failed runs. Removing it keeps the repository deploying correctly via Pages without extra failures.

If you prefer a custom workflow, I can add a corrected deploy workflow in a follow-up PR.
