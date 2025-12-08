---
layout: default
title: "Documentation Style Guide"
parent: Guidelines
permalink: /guidelines/documentation-style-guide/
---

# Documentation Style Guide

> **Purpose:** Ensure every FR Portal document is consistent, scannable, and bilingual-friendly.  
> **Who should use this:** Anyone authoring or updating pages in this repository.

---

## Quick Rules

- Keep pages concise: lead with the most actionable info first (purpose, scope, who does what, how to execute, KPIs, revision history).
- Use consistent headings and front matter. Every page must declare layout, title, parent, and permalink.
- Prefer tables, checklists, and numbered steps over long prose.
- Keep English and Turkish aligned; use the bilingual toggle pattern for new/updated pages.
- Update the `Revision History` table with every material change.

---

## Standard Page Skeleton

1. Front matter:
```yaml
---
layout: default
title: "Page Title"
parent: Module Name
permalink: /module/page-title/
---
```
2. Title block with metadata (last updated, owner, version).
3. **Summary** (1–2 paragraphs) + quick bullets for objectives and outcomes.
4. **Scope**: who is covered / not covered; regions if relevant.
5. **Roles & Responsibilities**: compact tables grouped by role.
6. **Process / Steps**: numbered steps; add expected inputs/outputs where helpful.
7. **Standards & Rules**: short list or table.
8. **KPIs / Acceptance Criteria**: table with formula/target/owner/frequency.
9. **Common Issues & Fixes**: short table of problems and actions.
10. **Revision History**: date, version, editor, change note.

---

## Writing Checklist

- Use active voice and imperative verbs in steps.
- Keep tables under ~6 columns; wrap text using `<br>` if needed.
- Add `{:.note}` / `{:.warning}` blocks sparingly for critical highlights.
- Provide links to related pages (parent index, sibling docs).
- For numbers and units, be explicit (%, days, USD, pcs).

---

## Bilingual Toggle Pattern (EN/TR)

Use the shared include to present both languages on one page without duplication in navigation.

1) Insert the toggle where the bilingual content begins:
```
{% include lang-toggle.html group="marketing-overview" default="en" %}
```
2) Wrap each language block with `lang-section` and the same `data-group`:
```
<div class="lang-section" data-group="marketing-overview" data-lang="en">
<!-- English content -->
</div>

<div class="lang-section" data-group="marketing-overview" data-lang="tr">
<!-- Türkçe içerik -->
</div>
```
3) Only one group per toggle. Reuse the include with a new `group` value if you need multiple toggled sections on a page.

---

## Tables & Lists

- Prefer compact tables; keep header names short.
- For long lists, split into subheadings; keep bullets to one sentence.
- Use consistent labels across pages (e.g., “Owner”, “Frequency”, “Target”).

---

## Revision History Template

| Date | Version | Editor | Change |
|------|---------|--------|--------|
| 2025-12-08 | 1.0 | Docs Team | Initial publication |

---

## Related Links

- Authoring basics: see `README.md` (Adding New Documentation).
- Example implementation: `marketing/marketing-overview-en.md` (bilingual quick view).

