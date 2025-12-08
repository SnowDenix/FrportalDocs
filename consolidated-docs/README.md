---
layout: default
title: "About Consolidated Docs"
parent: Consolidated Documentation
nav_order: 13
---

# Consolidated Documentation

This directory contains consolidated documentation files optimized for LLM (Large Language Model) processing and easier reference.

## Purpose

The original documentation was spread across 111+ individual files in multiple directories. This made it difficult to:
- Feed complete context to LLMs for analysis and querying
- Quickly reference related information
- Maintain consistency across topics
- Search semantically across a functional area

These consolidated files solve these problems by combining all related documents into single, comprehensive files.

## Structure

### Consolidated Files (12 total)

**Customer Management (CRM)**
- `customer-management-en.md` - English version
- `customer-management-tr.md` - Turkish version
- **Source:** 10 CRM documents
- **Content:** Overview, segmentation, KPIs, data quality, GDPR, loyalty, do's/don'ts, user guide, checklists, ticketing

**Operations**
- `operations-en.md` - English version
- `operations-tr.md` - Turkish version
- **Source:** 13 documents from Store Operations + Supply Chain
- **Content:** Store operations overview, opening/closing procedures, cash management, inventory control, customer service, loss prevention, returns/exchanges, order management, delivery/receiving, shipping/logistics, stock transfers, warehouse coordination

**Marketing**
- `marketing-en.md` - English version
- `marketing-tr.md` - Turkish version
- **Source:** 9 marketing documents
- **Content:** Marketing overview, brand guidelines, campaign execution, digital assets, in-store communication, approval processes, POSM guidelines, seasonal calendar, social media localization

**Visual Merchandising**
- `visual-merchandising-en.md` - English version
- `visual-merchandising-tr.md` - Turkish version
- **Source:** 6 VM documents
- **Content:** VM overview, general guidelines, window displays, in-store layouts, mannequin styling, seasonal changeovers

**Guidelines and Training**
- `guidelines-and-training-en.md` - English version
- `guidelines-and-training-tr.md` - Turkish version
- **Source:** 10 documents from Guidelines + Training
- **Content:** Documentation style guide, franchise communication protocols, store operations guidelines, VM guidelines, brand supplements (USPA, Pierre Cardin, Cacharel), competency framework, customer experience standards, interaction scenarios

**Glossary**
- `glossary-en.md` - English version
- `glossary-tr.md` - Turkish version
- **Source:** 3 glossary documents
- **Content:** Retail terms, finance KPI formulas, supply chain/logistics terms

## Format Changes

The consolidated files have been optimized for LLM processing:

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
| visual-merchandising-*.md | 6 major sections | Medium | Complete VM guidelines |
| guidelines-and-training-*.md | 10 major sections | Large | Complete training materials |
| glossary-*.md | 3 major sections | Small | Reference terms and formulas |

## Usage

### For LLM Processing
1. Select the relevant consolidated file(s) for your use case
2. Feed the entire file or specific sections to your LLM
3. The LLM will have complete context for that functional area

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

### For LLMs/AI Tools
- **Complete context:** Entire functional area in one file
- **Better answers:** More context leads to more accurate responses
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
- **Generator:** `consolidate_script.py`

## Questions?

For questions about these consolidated documents, contact:
- Technical: IT/Documentation Team
- Content: CRM Headquarters / Training Team
- Process: Regional Managers

---

**© 2025 Aydınlı Group - All rights reserved.**

This consolidated documentation structure was created to improve accessibility, LLM compatibility, and operational efficiency across the franchise network.

