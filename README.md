# Luo Mai personal website

This repository contains the Astro/Lumina source for Luo Mai's personal and research-group website, published at <https://luomai.github.io/>.

It was migrated from the earlier Hugo Academic source in `luomai/academic-kickstart`.

## What was migrated

- About/profile content and avatar
- 30 publications converted to BibTeX at `src/content/publications/papers.bib`
- 21 news items converted from old posts
- 8 software/project pages
- Current group members, postdocs, PhD students, and alumni
- Teaching, awards, service, and open-position content
- GitHub Pages Actions workflow at `.github/workflows/deploy.yml`

## Commands

```bash
npm ci
npm run build
npm run dev
```

For the username GitHub Pages repo (`luomai.github.io`), `astro.config.mjs` deploys at the root URL `https://luomai.github.io`.
