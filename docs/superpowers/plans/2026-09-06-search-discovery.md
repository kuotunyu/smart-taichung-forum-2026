# Search Discovery Implementation Plan

> **For agentic workers:** Execute the approved steps in this session and use the requesting-code-review skill before merging.

**Goal:** Make the forum notes easier to read and retrieve, publish the verified changes, and notify available search services.

**Architecture:** Preserve the existing single HTML document and canonical URL. Use native open details and continuous chapter layout; preserve existing interactions and source content.

**Tech Stack:** Static HTML/CSS/JavaScript, GitHub Pages, PowerShell, Python for static validation, browser UI verification.

## Global Constraints

- Preserve the canonical URL, existing anchor IDs, source distinctions and publication date.
- Do not fabricate facts, source timestamps, author qualifications or ranking results.
- Do not publish social posts or contact third parties without specific authorization.

## Tasks

- [ ] Run the original page in a local browser and record which chapters and primary details are hidden. Acceptance: five visible chapters and all primary details open; expect this to fail before changes.
- [ ] In index.html remove the single-chapter hiding rules and activation, retaining navigation and hash-target expansion. Add open to details[data-session-details] and details.source-group. Update descriptive title/intro and modification dates.
- [ ] In sitemap.xml keep the canonical URL and image; use the actual modification date and remove priority/changefreq. In README.md and llms.txt correct search and IndexNow documentation and describe continuous reading.
- [ ] Verify static document integrity: JSON-LD parsing, internal fragment targets, canonical/sitemap consistency and primary note count. Verify browser chapter visibility, collapse/reopen, deep links, search/reset, EN/ZH, theme, desktop and mobile overflow. Review changes independently.
- [ ] Commit only validated changes; fast-forward main and push. Wait for Pages build and compare deployed HTML with local HTML. Submit IndexNow using the project keyLocation only after deployment.
- [ ] Inspect/submit in Search Console when accessible; otherwise record the exact authentication blocker and owner steps. Save a sharing draft and a short operations record, separating successful actions from pending work.
