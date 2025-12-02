# Aydınlı Grup Franchise Retail Documentation

> **Retail Terms, Guidelines & KPI Formulas for Global Franchise Operations**  
> **Version:** 2.0 | **Last Updated:** December 2025

---

## Overview

This repository contains comprehensive retail documentation for Aydınlı Group's international franchise partners operating **U.S. Polo Assn.**, **Pierre Cardin**, and **Cacharel** brands.

All documents are provided in **bilingual format (Turkish/English)** to support global operations.

**📖 View Documentation Site:** [https://snowdenix.github.io/FrportalDocs/](https://snowdenix.github.io/FrportalDocs/)

---

## Documentation Structure

```
/
├── glossary/           # Retail terms, finance formulas, logistics terminology
├── guidelines/         # Core operational guidelines and protocols
├── crm/                # Customer relationship management (20 files)
├── marketing/          # Marketing operations and brand guidelines (18 files)
├── vm/                 # Visual merchandising standards (12 files)
├── store-operations/   # Daily store operations (16 files)
├── supply-chain/       # Logistics and procurement (12 files)
├── training/           # Training materials and guides (24 files)
├── _config.yml         # Jekyll configuration
├── index.md            # Homepage
└── Gemfile             # Ruby dependencies for local development
```

---

## Document Summary

| Module | Document Pairs | Languages | Total Files |
|--------|---------------|-----------|-------------|
| Glossary | 3 | TR/EN | 6 |
| Guidelines | 3 | TR/EN | 6 |
| CRM | 10 | TR/EN | 20 |
| Marketing | 9 | TR/EN | 18 |
| Visual Merchandising | 6 | TR/EN | 12 |
| Store Operations | 8 | TR/EN | 16 |
| Supply Chain | 6 | TR/EN | 12 |
| Training | 12 | TR/EN | 24 |
| **Total** | **57** | **TR/EN** | **114** |

---

## Key Topics Covered

- **Retail Terms & Concepts:** Stock Cover, SKU, Sell-Through Rate, etc.
- **Finance KPIs & Formulas:** EBIT, GMROI, Markup, Margin, etc.
- **Supply Chain & Logistics:** Incoterms 2020, SAP Transaction Codes
- **Visual Merchandising:** Golden Triangle, A-B-C Zone System
- **Store Operations:** Opening/Closing, Returns, Cash Management
- **Marketing Operations:** Brand Identity, Campaign Execution, POSM
- **CRM:** Customer Segmentation, Loyalty Campaigns, Data Quality
- **Training:** Onboarding, Sales Techniques, Brand Training

---

## Local Development

To run the documentation site locally:

```bash
# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve

# Visit http://localhost:4000/FrportalDocs/
```

---

## Adding New Documentation

### 1. New Section (top-level folder)

1. Create a new folder at the project root, for example `new-section/`.
2. Inside it, create an `index.md` with front matter similar to:

```markdown
---
layout: default
title: New Section
nav_order: 10
has_children: true
permalink: /new-section/
---

# New Section

Short description of what this module covers.
```

3. Add a `## Documents` table in that `index.md` that links to child pages using relative links like `child-doc-en` (no `.md` extension).

### 2. New Child Document within a Section

1. In the relevant section folder (for example `crm/`), add a new file such as `crm-new-topic-en.md`.
2. Use front matter like:

```markdown
---
layout: default
title: "CRM New Topic – EN"
parent: CRM
---
```

3. Link this new document from the section’s `index.md` table using a relative link (for example `[CRM New Topic](crm-new-topic-en)`).

### 3. Navigation Rules

- Section navigation is driven primarily by each section’s `index.md` page and its documents table.
- The `parent:` metadata on child pages (for example `parent: CRM`) is used to group items in the Just the Docs sidebar, but the site will still be usable even if the sidebar nesting is imperfect.
- Do **not** add arbitrary `parent:` values like `parent: info`; always match the section `title` (for example `CRM`, `Glossary`, `Marketing`, `Visual Merchandising`, etc.) or omit `parent:` entirely if you don’t need sidebar nesting.

---

## License

© 2025 Aydınlı Grup - All rights reserved.

This documentation is proprietary and confidential. Distribution is limited to authorized Aydınlı Group franchise partners only.

---

*Prepared by Aydınlı Grup Franchise Operations Team*

