# Migration notes

## Recommended source-of-truth layout

Use `luomai.github.io` as the source repo, not only as a generated static-output repo. GitHub Actions builds Astro and deploys the `dist/` artifact to Pages.

## Manual review needed before publishing

- Check all publication links in `papers.bib`; the converter preserved top-level `url_pdf`, `url_code`, `url_project`, etc. when present.
- Decide whether `News` should stay as short announcements or become a full blog.
- Add photos for group members if desired; current prototype falls back to initials.
- The template has low GitHub adoption compared with HugoBlox/Academic Pages, so review maintainability before making it canonical.
- `npm audit` on the upstream template currently reports vulnerabilities in transitive dependencies; review before publishing.
