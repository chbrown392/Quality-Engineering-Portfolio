# Framer Execution — Exact Steps

Framer now supports external agents such as Claude Code and Codex. Use the native Framer Agent connection rather than trying to import this static site as editable Framer source.

## One-time agent setup
1. Create or open the Framer project that will become the portfolio.
2. On your computer, open a terminal.
3. Run:

```bash
npx @framer/agent setup
```

4. Follow Framer's authorization flow. The first connection can open a browser and request permission/API-key authorization.
5. Open Claude Code in the same local environment.
6. Give Claude the contents of `CLAUDE_FRAMER_AGENT_PROMPT.md` and access to this portfolio folder/repository.
7. Tell Claude to implement the build directly in the authorized Framer project.

## What the agent should create
- Responsive home page
- QA operating-model section
- Case Studies CMS collection
- Five case-study detail pages
- Frameworks section
- Leadership/About section
- Contact section
- Navigation and mobile menu
- SEO title/description
- 404 page

## Important limitation
Framer's external agents can make content/design and CMS changes, but some project settings such as project names and domains still require the Framer UI. Publishing and custom-domain configuration therefore remain explicit account-level steps.

## Final manual Framer checks
- Add your actual LinkedIn URL.
- Add your resume URL/file.
- Add your professional contact email.
- Set the final project name.
- Publish.
- Connect the chosen custom domain.
- QA desktop/tablet/mobile after publishing.
