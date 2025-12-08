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
├── crm/                # Customer relationship management (20 files)
├── glossary/           # Retail terms, finance formulas, logistics terminology
├── guidelines/         # Core operational guidelines and protocols
├── marketing/          # Marketing operations and brand guidelines (18 files)
├── store-operations/   # Daily store operations (16 files)
├── supply-chain/       # Logistics and procurement (12 files)
├── training/           # Training materials and guides (24 files)
├── vm/                 # Visual merchandising standards (12 files)
├── _sass/custom/       # Custom dark theme styles
├── .github/workflows/  # GitHub Actions deployment
├── _config.yml         # Jekyll configuration
├── index.md            # Homepage
├── Gemfile             # Ruby dependencies
└── README.md           # This file
```

---

## Document Summary

| Module               | Document Pairs | Languages | Total Files |
| -------------------- | -------------- | --------- | ----------- |
| CRM                  | 10             | TR/EN     | 20          |
| Glossary             | 3              | TR/EN     | 6           |
| Guidelines           | 3              | TR/EN     | 6           |
| Marketing            | 9              | TR/EN     | 18          |
| Visual Merchandising | 6              | TR/EN     | 12          |
| Store Operations     | 8              | TR/EN     | 16          |
| Supply Chain         | 6              | TR/EN     | 12          |
| Training             | 12             | TR/EN     | 24          |
| **Total**            | **57**         | **TR/EN** | **114**     |

---

## Key Topics Covered

- **CRM:** Customer Segmentation, Loyalty Campaigns, Data Quality, GDPR Compliance
- **Retail Terms & Concepts:** Stock Cover, SKU, Sell-Through Rate, Conversion Rate
- **Finance KPIs & Formulas:** EBIT, GMROI, Markup, Margin, ROI
- **Supply Chain & Logistics:** Incoterms 2020, Order Management, Warehouse Coordination
- **Visual Merchandising:** Golden Triangle, A-B-C Zone System, Window Display Standards
- **Store Operations:** Opening/Closing, Returns, Cash Management, Loss Prevention
- **Marketing Operations:** Brand Identity, Campaign Execution, POSM, Digital Assets
- **Training:** Onboarding, Sales Techniques, Brand Knowledge, Customer Experience

---

## Theme Features

This documentation site uses **Just the Docs** theme with:

- 🌙 **Dark Theme** - Professional dark mode for comfortable reading
- 🔍 **Full-text Search** - Quick document search with keyboard shortcut (Cmd/Ctrl + K)
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile
- 🎨 **Brand Colors** - Aydınlı red accent colors
- 📖 **Bilingual Support** - Turkish and English documents

---

## Local Development

To run the documentation site locally:

```bash
# Install Ruby dependencies
bundle install

# Serve locally with live reload
bundle exec jekyll serve --livereload

# Visit http://localhost:4000/FrportalDocs/
```

### Requirements

- Ruby 3.0+
- Bundler gem
- Jekyll 4.x

---

## Adding New Documentation

### New Section (top-level folder)

1. Create a new folder at the project root, e.g., `new-section/`
2. Create an `index.md` with front matter:

```yaml
---
layout: default
title: New Section
nav_order: 10
has_children: true
permalink: /new-section/
---
```

### New Document within a Section

1. Add a new file in the section folder, e.g., `crm/crm-new-topic-en.md`
2. Use front matter:

```yaml
---
layout: default
title: "CRM New Topic"
parent: CRM
permalink: /crm/crm-new-topic-en/
---
```

3. Link from the section's `index.md` table

---

## Authoring Standards

- Follow the shared structure and checklist in `[Documentation Style Guide](guidelines/documentation-style-guide)`.
- For bilingual pages, use the `{% include lang-toggle.html %}` pattern (see the style guide) and wrap English/Turkish blocks in `lang-section` containers with matching `data-group`.
- Example implementation: `marketing/marketing-overview-en.md` includes a bilingual quick view using this pattern.

### Converting Existing Modules to the Bilingual Pattern

When converting a section pair (EN/TR):
- Keep front matter aligned (layout/title/parent/permalink).
- Add a “Quick Reference (EN/TR Toggle)” section near the top with `{% include lang-toggle.html group="unique-name" %}` and paired `lang-section` blocks.
- Update the table of contents to include the quick reference entry.
- Keep English and Turkish content scoped to the same page to avoid duplicate nav entries.
- Re-run a quick visual check: toggle buttons active state, spacing, and lists render correctly.

---

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch via GitHub Actions.

**Workflow:** `.github/workflows/pages.yml`

---

## License

© 2025 Aydınlı Grup - All rights reserved.

This documentation is proprietary and confidential. Distribution is limited to authorized Aydınlı Group franchise partners only.

---

*Prepared by Aydınlı Grup Franchise Operations Team*  
📧 **Contact:** franchise@aydinli.com.tr

