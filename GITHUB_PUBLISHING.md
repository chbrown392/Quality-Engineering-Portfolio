# GitHub Publishing — Exact Steps

## Recommended repository
`quality-engineering-portfolio`

## Option A — GitHub web UI
1. Create a new repository named `quality-engineering-portfolio`.
2. Make it public when you are ready for recruiters to see it.
3. Upload the contents of this folder **from inside the folder** so `index.html` is at the repository root.
4. Commit to `main`.
5. Open **Settings → Pages**.
6. Choose **Deploy from a branch**.
7. Select `main` and `/ (root)`.
8. Save.
9. GitHub will provide the Pages URL after deployment.

## Option B — command line
From the portfolio folder:

```bash
git init
git branch -M main
git add .
git commit -m "Launch quality engineering portfolio"
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/quality-engineering-portfolio.git
git push -u origin main
```

Then enable GitHub Pages in repository settings.

## Recommended repository description
`Salesforce QA leadership portfolio: QA operating models, UAT governance, test strategy, sanitized enterprise case studies, and reusable quality templates.`

## Suggested repository topics
`quality-assurance`, `salesforce`, `manual-testing`, `uat`, `qa-leadership`, `jira`, `test-strategy`, `acceptance-criteria`

## Before making public
Run `PRIVACY_SANITIZATION_CHECKLIST.md`.
