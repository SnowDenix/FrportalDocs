---
layout: default
title: "About Consolidated Docs"
parent: Consolidated Documentation
nav_order: 13
---

# Consolidated Documentation

This directory contains consolidated documentation files optimized for modern documentation standards and easier reference.

## Purpose

The original documentation was spread across 111+ individual files in multiple directories. This made it difficult to:
- Enable comprehensive analysis and reference
- Quickly reference related information
- Maintain consistency across topics
- Search semantically across a functional area

These consolidated files solve these problems by combining all related documents into single, comprehensive files.

## Structure

### Hierarchical Organization

All consolidated documents follow a **logical hierarchy** where:
1. **Overview sections come first** - providing system-wide context and vision
2. **Conceptual content follows** - explaining methodology and frameworks
3. **Procedural content comes last** - detailing step-by-step processes

This organization ensures readers understand the "why" before the "how."

### Consolidated Files (12 total)

**Customer Management (CRM)**
- `customer-management-en.md` - English version
- `customer-management-tr.md` - Turkish version
- **Source:** 10 CRM documents
- **Sections:** 1. Overview → 2. Segmentation → 3. Loyalty/Campaigns → 4. Dashboard/KPIs → 5. Data Policy → 6. Data Quality → 7. Do's/Don'ts → 8. User Guide → 9. Checklists → 10. Ticketing

**Operations**
- `operations-en.md` - English version
- `operations-tr.md` - Turkish version
- **Source:** 13 documents from Store Operations + Supply Chain
- **Sections:** 1. Store Ops Overview → 2. Supply Chain Overview → 3. Opening/Closing → 4. Cash Management → 5. Customer Service → 6. Inventory Control → 7. Loss Prevention → 8. Returns/Exchanges → 9. Order Management → 10. Delivery/Receiving → 11. Stock Transfers → 12. Shipping/Logistics → 13. Warehouse Coordination

**Marketing**
- `marketing-en.md` - English version
- `marketing-tr.md` - Turkish version
- **Source:** 9 marketing documents
- **Sections:** 1. Overview → 2. Brand Guidelines → 3. Seasonal Calendar → 4. Campaign Execution → 5. POSM Guidelines → 6. In-Store Communication → 7. Digital Assets → 8. Social Media → 9. Approval Process

**Visual Merchandising**
- `visual-merchandising-en.md` - English version
- `visual-merchandising-tr.md` - Turkish version
- **Source:** 5 VM documents
- **Sections:** 1. Overview → 2. In-Store Layout → 3. Window Display → 4. Mannequin Styling → 5. Seasonal Changeover

**Guidelines and Training**
- `guidelines-and-training-en.md` - English version
- `guidelines-and-training-tr.md` - Turkish version
- **Source:** 7-8 documents from Guidelines + Training
- **Sections:** 1. Communication Protocol → 2. Customer Experience → 3. Competency Framework → 4-6. Brand Supplements (USPA, Pierre Cardin, Cacharel) → 7. Customer Interaction Scenarios → 8. Documentation Style Guide

**Glossary**
- `glossary-en.md` - English version
- `glossary-tr.md` - Turkish version
- **Source:** 2 glossary documents
- **Sections:** 1. Retail Terms → 2. Finance KPI Formulas

## Format Changes

The consolidated files have been optimized for modern documentation standards:

### Removed
- Jekyll frontmatter (YAML headers)
- Jekyll includes and liquid tags
- Language toggle HTML components
- Permalink and layout directives

### Retained
- All markdown content
- Tables and formatting
- Code blocks and diagrams
- Hierarchical structure with clear headers

### Enhanced
- Comprehensive table of contents
- Document metadata (source files, last updated, version)
- Clear section markers
- Unified structure across all documents

## File Sizes

| File | Sections | Approx Size | Use Case |
|------|----------|-------------|----------|
| customer-management-*.md | 10 major sections | Large | Complete CRM reference |
| operations-*.md | 13 major sections | Large | Complete operational procedures |
| marketing-*.md | 9 major sections | Medium | Complete marketing guidelines |
| visual-merchandising-*.md | 5 major sections | Medium | Complete VM guidelines |
| guidelines-and-training-*.md | 7-8 major sections | Large | Complete training materials |
| glossary-*.md | 2 major sections | Small | Reference terms and formulas |

## Usage

### For Digital Tools
1. Select the relevant consolidated file(s) for your use case
2. Use with digital reference tools and systems
3. Digital tools will have complete context for that functional area

### For Human Reference
1. Use your text editor's search function (Ctrl+F / Cmd+F)
2. Jump to sections using the table of contents
3. Reference multiple related topics without switching files

### For Semantic Search
The consolidated format makes it easier to:
- Search across an entire functional area
- Find related concepts
- Understand context and relationships

## Original Files

All original files have been preserved in the `/archive` directory with the same structure:
- `/archive/crm/`
- `/archive/store-operations/`
- `/archive/supply-chain/`
- `/archive/marketing/`
- `/archive/vm/`
- `/archive/guidelines/`
- `/archive/training/`
- `/archive/glossary/`

The original Jekyll-based website structure (index.md files, _includes, _sass, etc.) remains in the root directory.

## Maintenance

When updating documentation:

1. **Option A - Update Original + Regenerate**
   - Update original files in `/archive` directories
   - Run `python consolidate_script.py` to regenerate consolidated files

2. **Option B - Update Consolidated Directly**
   - Edit the consolidated files directly
   - Note changes in the document metadata

## Benefits

### For Franchise Stores
- **Faster access:** All related information in one place
- **Better training:** Trainers can reference complete materials
- **Improved consistency:** Easier to see how processes relate

### For Digital Tools Integration
- **Complete context:** Entire functional area in one file
- **Better reference:** More context leads to more accurate information retrieval
- **Efficient processing:** Single file load vs. 10+ files

### For Management
- **Overview capability:** See entire functional area at once
- **Gap analysis:** Easier to spot missing procedures
- **Policy review:** Review all related policies together

## Technical Details

- **Encoding:** UTF-8
- **Line Endings:** LF (Unix-style)
- **Markdown Flavor:** GitHub-flavored Markdown
- **Generated:** December 8, 2025
- **Restructured:** December 9, 2025 (hierarchical ordering applied)
- **Generator:** `consolidate_script.py`

## Questions?

For questions about these consolidated documents, contact:
- Technical: IT/Documentation Team
- Content: CRM Headquarters / Training Team
- Process: Regional Managers

---

**© 2025 Aydınlı Group - All rights reserved.**

This consolidated documentation structure was created to improve accessibility, modern standards compatibility, and operational efficiency across the franchise network.

