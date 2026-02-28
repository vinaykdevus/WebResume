# Web Resume

This repository contains a small static web resume generated from a LinkedIn link. The site reads its content from `data/resume.json` so you can easily edit your details without changing the page code.

How to use
- Edit `data/resume.json` with your real contact info, summary, experience, education and skills.
- Commit and push to GitHub on the `main` branch. A GitHub Actions workflow (added in `.github/workflows/deploy.yml`) will publish the site to GitHub Pages automatically.

Styling
- The site uses Bootstrap 4.1 (via CDN) for a clean responsive layout. Custom tweaks live in `styles.css`.

Notes and next steps
- LinkedIn pages may require sign-in to view full content, so I populated `data/resume.json` with inferred/public bits and placeholders — please update it.
- If you'd like, I can help extract the exact experience/education entries once you provide the LinkedIn content or copy/paste the relevant sections.

Want the site on a custom domain? I can add `CNAME` and update the workflow.
