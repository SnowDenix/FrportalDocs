---
layout: default
title: "Guidelines & Training (EN)"
parent: Consolidated Documentation
nav_order: 9
---

# Guidelines & Training - Complete Documentation (English)

> **Consolidated Document**  
> **Last Updated:** December 8, 2025  
> **Prepared by:** Aydınlı Grup
>
> **Source Files:** 10 files from guidelines, training

---

## SECTION 1: DOCUMENTATION-STYLE-GUIDE-EN


# Documentation Style Guide

> **Purpose:** Ensure every FR Portal document is consistent, scannable, and bilingual-friendly.  
> **Who should use this:** Anyone authoring or updating pages in this repository.


## Standard Page Skeleton

1. Front matter:
```yaml
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


## Bilingual Toggle Pattern (EN/TR)

Use the shared include to present both languages on one page without duplication in navigation.

1) Insert the toggle where the bilingual content begins:
```
```
2) Wrap each language block with `lang-section` and the same `data-group`:
```
<!-- English content -->
</div>

<!-- Türkçe içerik -->
</div>
```
3) Only one group per toggle. Reuse the include with a new `group` value if you need multiple toggled sections on a page.


## Revision History Template

| Date | Version | Editor | Change |
|------|---------|--------|--------|
| 2025-12-08 | 1.0 | Docs Team | Initial publication |


---

## SECTION 2: FRANCHISE-COMMUNICATION-PROTOCOL-EN

﻿---
layout: default
title: "Franchise Communication Protocol"
parent: Guidelines
permalink: /guidelines/franchise-communication-protocol-en/

## Table of Contents

1. [Introduction and Purpose](#introduction-and-purpose)
2. [Organization Structure](#organization-structure)
3. [Communication Channels](#communication-channels)
4. [Reporting Standards](#reporting-standards)
5. [Order and Supply Communication](#order-and-supply-communication)
6. [Escalation Procedures](#escalation-procedures)
7. [Meeting and Conference Protocols](#meeting-and-conference-protocols)
8. [Crisis Communication](#crisis-communication)
9. [Communication Templates](#communication-templates)


## Organization Structure

### Aydınlı Group Headquarters Structure

```
┌─────────────────────────────────────┐
│         GENERAL MANAGER             │
└──────────────┬──────────────────────┘
               │
    ┌──────────┼──────────┐
    │          │          │
┌───▼───┐  ┌───▼───┐  ┌───▼───┐
│Sales  │  │Operations│ │Finance│
│Director│  │Director │ │Director│
└───┬───┘  └───┬───┘  └───┬───┘
    │          │          │
┌───▼───┐  ┌───▼───┐  ┌───▼───┐
│Regional│ │Logistics│ │Accounting│
│Manager│  │Manager  │ │Manager  │
└───────┘  └─────────┘  └─────────┘
```

### Franchise Partner Structure

```
┌─────────────────────────────────────┐
│       FRANCHISE OWNER               │
└──────────────┬──────────────────────┘
               │
    ┌──────────┼──────────┐
    │          │          │
┌───▼───┐  ┌───▼───┐  ┌───▼───┐
│Operations│ │Sales  │  │Finance│
│Manager  │  │Manager │  │Manager│
└───┬───┘  └───────┘  └────────┘
    │
┌───▼───┐
│Store  │
│Manager│
└───────┘
```

### Communication Matrix

| Subject | Franchise Representative | HQ Counterpart |
|---------|-------------------------|----------------|
| Daily Sales | Store Manager | Regional Manager |
| Orders | Operations Manager | Order Tracking |
| Shipment | Operations Manager | Logistics Manager |
| Financial | Finance Manager | Accounting Manager |
| VM/Marketing | Sales Manager | Marketing |
| Strategic | Franchise Owner | General Manager |


## Reporting Standards

### Daily Reports

**Sales Report (Due by 22:00 daily)**

| Metric | Format |
|--------|--------|
| Total Sales | Currency |
| Transaction Count | Units |
| UPT | Decimal |
| ATV | Currency |
| Visitors | Units |
| Conversion | Percentage |

**Report Template:**
```
DAILY SALES REPORT
Date: [DD/MM/YYYY]
Store: [Store Name]

                Today    Target   Achievement
Sales:          _____    _____    ___%
Transactions:   _____    _____    ___%
UPT:            _____    _____    ___%
ATV:            _____    _____    ___%
Visitors:       _____    _____    ___%
Conversion:     _____    _____    ___%

Notes: ________________________
```

### Weekly Reports

**Stock Status Report (Due Monday 12:00)**
- Current stock value
- Stock cover (weeks)
- Critical stock alerts (cover < 4 weeks)
- Transfer requests

**Performance Report (Due Monday 12:00)**
- Weekly sales summary
- LFL comparison
- Top selling products (Top 10)
- Slow moving products (Bottom 10)

### Monthly Reports

**Comprehensive Performance Report (Due by 5th of each month)**
- Monthly sales performance
- KPI analysis
- Stock analysis
- Store operations summary
- Next month targets


## Escalation Procedures

### Escalation Levels

| Level | Definition | Duration | Authority |
|-------|------------|----------|-----------|
| **L1** | Routine matters | 24 hours | Relevant specialist |
| **L2** | Unresolved L1 | 48 hours | Department Manager |
| **L3** | Critical matters | 72 hours | Director |
| **L4** | Crisis situations | Immediate | General Manager |

### Escalation Matrix

| Subject | L1 | L2 | L3 | L4 |
|---------|-----|-----|-----|-----|
| Order delay | Order Specialist | Order Manager | Ops Director | GM |
| Shipment issue | Logistics Specialist | Logistics Manager | Ops Director | GM |
| Quality issue | QC Specialist | QC Manager | Ops Director | GM |
| Payment issue | Accounting | Finance Manager | Finance Director | GM |
| Contract matter | Legal | Legal Manager | General Secretary | GM |

### Escalation Communication Template

```
Subject: [URGENT] - Escalation L[X] - [Subject Summary]

ESCALATION NOTIFICATION

Date/Time: [DD/MM/YYYY HH:MM]
Escalation Level: L[X]
Previous Level Ref: [Ticket no if available]

PROBLEM DESCRIPTION:
[Detailed description]

IMPACT ANALYSIS:
- Financial Impact: [Estimated amount]
- Operational Impact: [Description]
- Customer Impact: [Description]

ACTIONS TAKEN:
1. [Date] - [Action]
2. [Date] - [Action]

REQUESTED ACTION:
[Clear request]

EXPECTED RESOLUTION TIME: [X hours/days]

Contact: [Name, phone, email]
```


## Crisis Communication

### Crisis Types

| Type | Definition | Priority |
|------|------------|----------|
| **Operational Crisis** | Supply disruption, store closure | High |
| **Financial Crisis** | Payment issues, currency crisis | High |
| **Reputation Crisis** | Media, social media issues | Very High |
| **Natural Disaster** | Earthquake, flood, pandemic | Critical |

### Crisis Communication Protocol

```
1. Detect and Assess Crisis
   ↓
2. Activate Crisis Team
   ↓
3. First 1 Hour: Prepare Situation Report
   ↓
4. First 2 Hours: Inform Internal Stakeholders
   ↓
5. First 4 Hours: Create Action Plan
   ↓
6. Ongoing: Status Updates (every 4 hours)
   ↓
7. Post-Crisis: Evaluation and Reporting
```

### Emergency Contact List

```
CRISIS CONTACT LIST


Crisis Hotline (24/7):
Tel: +90 XXX XXX XX XX
WhatsApp: +90 XXX XXX XX XX
```


## Revision History

| Version | Date | Change | Prepared By |
|---------|------|--------|-------------|
| 1.0 | 2025-12-01 | Initial version created | Aydınlı Group |


---

## SECTION 3: STORE-OPERATIONS-GUIDELINE-EN

﻿---
layout: default
title: "Store Operations Guidelines"
parent: Guidelines
permalink: /guidelines/store-operations-guideline-en/

## Table of Contents

1. [Daily Operation Procedures](#daily-operation-procedures)
2. [Store Opening Procedure](#store-opening-procedure)
3. [Store Closing Procedure](#store-closing-procedure)
4. [Return and Exchange Procedures](#return-and-exchange-procedures)
5. [Damage and Rejection Procedures](#damage-and-rejection-procedures)
6. [Price Change Procedures](#price-change-procedures)
7. [Inventory Management Procedures](#inventory-management-procedures)
8. [Cash Management](#cash-management)
9. [Customer Service Standards](#customer-service-standards)
10. [Emergency Procedures](#emergency-procedures)


## Store Opening Procedure

### Opening Checklist (30 mins before opening)

#### 1. Security Checks
- [ ] Disable alarm system
- [ ] Check all entry/exit points
- [ ] Any overnight abnormalities?
- [ ] Check security cameras

#### 2. Physical Preparation
- [ ] Turn on all lights
- [ ] Adjust AC/heating
- [ ] Check floor cleanliness
- [ ] Check windows

#### 3. Store Layout
- [ ] Window display check
- [ ] Fixture arrangement check
- [ ] Mannequin check
- [ ] Signage check
- [ ] Price tag check

#### 4. Cash Register Preparation
- [ ] Opening cash count
- [ ] Turn on and test POS devices
- [ ] Sufficient change available?
- [ ] Receipt roll check

#### 5. Stock Preparation
- [ ] Any overnight deliveries?
- [ ] Replenish missing sizes/colors
- [ ] Check products for return

### Opening Count Form

```
┌─────────────────────────────────────┐
│    OPENING CASH COUNT FORM          │
├─────────────────────────────────────┤
│ Date: ___/___/______                │
│ Staff: _________________            │
├─────────────────────────────────────┤
│ Coins                                │
│   $0.25 × ___ = $_____.___          │
│   $0.50 × ___ = $_____.___          │
│   $1.00 × ___ = $_____.___          │
├─────────────────────────────────────┤
│ Bills                                │
│   $5   × ___ = $_____.___           │
│   $10  × ___ = $_____.___           │
│   $20  × ___ = $_____.___           │
│   $50  × ___ = $_____.___           │
│   $100 × ___ = $_____.___           │
├─────────────────────────────────────┤
│ TOTAL: $____________                │
│ Float: $____________                │
│ Signature: _______________          │
└─────────────────────────────────────┘
```


## Return and Exchange Procedures

### Return Policy

| Condition | Period | Requirement | Action |
|-----------|--------|-------------|--------|
| Tagged, unused | 14 days | With receipt | Full refund |
| Tagged, unused | 14-30 days | With receipt | Store credit |
| Untagged/used | - | - | No return accepted |
| Defective product | 30 days | With receipt | Exchange or refund |

### Return Process Steps

```
1. Greet Customer
   ↓
2. Receipt/Invoice Check
   ↓
3. Product Check (tag, condition)
   ↓
4. Determine Return Reason
   ↓
5. System Entry (POS)
   ↓
6. Complete Return Form
   ↓
7. Refund / Exchange
   ↓
8. Customer Signature
```

### Return Reason Codes

| Code | Reason | Description |
|------|--------|-------------|
| R01 | Size mismatch | Customer bought wrong size |
| R02 | Color dissatisfaction | Customer doesn't like color |
| R03 | Gift return | Gift recipient returning |
| R04 | Manufacturing defect | Product is defective |
| R05 | Price difference | Found cheaper elsewhere |
| R06 | Other | Explanation required |

### Return Form

```
┌─────────────────────────────────────┐
│       RETURN / EXCHANGE FORM        │
├─────────────────────────────────────┤
│ Date: ___/___/______                │
│ Receipt No: _________________       │
│ Original Sale Date: ___/___/___     │
├─────────────────────────────────────┤
│ CUSTOMER INFORMATION                │
│ Name: _________________             │
│ Phone: _________________            │
├─────────────────────────────────────┤
│ PRODUCT INFORMATION                 │
│ SKU: _________________              │
│ Product Name: _________________     │
│ Size: ___ Color: ___                │
│ Amount: $_______                    │
├─────────────────────────────────────┤
│ RETURN REASON: [ ] R01 [ ] R02 [ ] R03│
│                [ ] R04 [ ] R05 [ ] R06│
│ Notes: _________________            │
├─────────────────────────────────────┤
│ TRANSACTION TYPE                    │
│ [ ] Cash Refund  [ ] Card Refund    │
│ [ ] Exchange     [ ] Store Credit   │
├─────────────────────────────────────┤
│ Customer Signature: _____________   │
│ Staff: _________________            │
└─────────────────────────────────────┘
```


## Price Change Procedures

### Price Change Types

| Type | Definition | Authority |
|------|------------|-----------|
| **Central Discount** | General campaign | Headquarters |
| **Regional Discount** | Region-based | Regional Manager |
| **Markdown** | End of season | HQ approval |
| **Price Correction** | Error correction | Store Manager |

### Price Update Procedure

```
1. HQ Price Change Notification
   ↓
2. Download Price List
   ↓
3. Update System (POS)
   ↓
4. Physical Tag Change
   ↓
5. Verification (random 10 products)
   ↓
6. Completion Notification
```

### Tag Change Rules

- Old tags must be completely removed
- No overlapping tags
- No handwriting on tags
- All sizes must be updated

### Price Control Form

```
┌─────────────────────────────────────┐
│      PRICE CHANGE CONTROL           │
├─────────────────────────────────────┤
│ Campaign/Period: ________________   │
│ Validity: ___/___ - ___/___         │
├─────────────────────────────────────┤
│ SKU        Old       New      ✓     │
│ ________   $_____    $_____   [ ]   │
│ ________   $_____    $_____   [ ]   │
│ ________   $_____    $_____   [ ]   │
├─────────────────────────────────────┤
│ Checked By: _________________       │
│ Date/Time: _________________        │
└─────────────────────────────────────┘
```


## Cash Management

### Payment Types

| Payment | Process | Points of Attention |
|---------|---------|-------------------|
| Cash | Count, change | Counterfeit check |
| Credit Card | POS transaction | Signature/PIN verification |
| Debit Card | POS transaction | Balance check |
| Gift Card | System entry | Validity check |
| Installment | POS installment | Installment options |

### Cash Shortage/Overage Procedure

**In Case of Shortage:**
1. Recount
2. Check day's transactions
3. Review camera footage
4. Prepare report
5. Notify store manager

**In Case of Overage:**
1. Recount
2. Check return/void transactions
3. Customer change check
4. Prepare report

### Daily Cash Limits

| Amount | Action |
|--------|--------|
| < $1,000 | Normal operation |
| $1,000-$2,500 | Intra-shift bank deposit |
| > $2,500 | Urgent bank transfer |


## Emergency Procedures

### Fire

1. Activate fire alarm
2. Call emergency services
3. Evacuate customers
4. Use fire extinguisher (small fire)
5. Use emergency exits
6. Go to assembly point

### Theft

1. Notify security
2. Don't intervene (if dangerous)
3. Identify the person
4. Secure camera footage
5. Prepare report
6. Call police (if necessary)

### Medical Emergency

1. Call emergency services
2. Apply first aid (if trained)
3. Don't move the person
4. Stay calm
5. Clear the area

### Emergency Contact Numbers

```
Fire Department: ___________
Ambulance: ___________
Police: ___________
Company Security: ___________
Regional Manager: ___________
```


*This document was prepared by Aydınlı Group.*  
*© 2025 Aydınlı Group - All rights reserved.*




---

## SECTION 4: VM-GUIDELINE-EN

﻿---
layout: default
title: "Visual Merchandising Guidelines"
parent: Guidelines
permalink: /guidelines/vm-guideline-en/

## Table of Contents

1. [Introduction and Purpose](#introduction-and-purpose)
2. [Core VM Principles](#core-vm-principles)
3. [Store Zones and Layout](#store-zones-and-layout)
4. [Window Display Standards](#window-display-standards)
5. [Fixture and Product Placement](#fixture-and-product-placement)
6. [Color and Theme Management](#color-and-theme-management)
7. [Signage and POP Materials](#signage-and-pop-materials)
8. [Brand-Specific Standards](#brand-specific-standards)
9. [Seasonal VM Calendar](#seasonal-vm-calendar)
10. [VM Checklist](#vm-checklist)


## Core VM Principles

### 1. Golden Triangle Rule

When viewed from the customer entry point, the most important products should be displayed in the "Golden Triangle" zone.

```
        [WINDOW]
           △
          / \
         /   \
        /     \
       /  ★★★  \    ← Golden Triangle Zone
      /         \
     /           \
    /_____________\
       [ENTRY]
```

### 2. Eye Level Rule

- **Premium Zone (145-170 cm):** Most profitable, new season products
- **Touch Zone (90-145 cm):** Easy access, try-on products
- **Lower Zone (0-90 cm):** Bulky, heavy items
- **Upper Zone (170+ cm):** Stock, visual decor

### 3. Right-Turn Principle

90% of customers turn right when entering a store. Therefore:
- Right side: New season, trend products
- Left side: Basic products, outlet

### 4. Decompression Zone

The first 1-2 meters of the entrance area is where customers adapt to the store. Do not place critical products in this area.


## Window Display Standards

### Window Change Calendar

| Period | Change Frequency |
|--------|-----------------|
| New Season Launch | Immediate |
| Campaign Periods | Campaign start |
| Normal Period | Every 2 weeks |
| Special Occasions | Before event |

### Window Composition Rules

#### Pyramid Arrangement
```
       ▲
      /█\
     / █ \
    / █ █ \
   / █ █ █ \
  ───────────
```
- Center point is highest
- Can be symmetrical or asymmetrical
- Focal point at 145-165 cm

#### Repetition Arrangement
```
  █   █   █   █   █
  ▼   ▼   ▼   ▼   ▼
```
- Same product in different colors
- Strong visual impact

### Window Lighting

- **General Lighting:** 800-1000 lux
- **Spot Lighting:** 2000-3000 lux (for hero products)
- **Color Temperature:** 3000-4000K (warm white)

### Window Mannequin Usage

| Store Size | Mannequin Count |
|------------|-----------------|
| < 80 m² | 2-3 |
| 80-150 m² | 4-6 |
| > 150 m² | 6-8 |


## Color and Theme Management

### Creating Color Blocks

Group products according to color gradients:

```
LIGHT ──────────────────────────────────► DARK

White → Cream → Yellow → Orange → Red → Burgundy → Navy → Black
```

### Color Story Telling

Use maximum 3-4 color combinations per fixture:

**Correct:**
```
[Navy] [White] [Red]
```

**Incorrect:**
```
[Green] [Yellow] [Purple] [Orange] [Pink] [Blue]
```

### Seasonal Color Palette

| Season | Main Colors | Accent Colors |
|--------|-------------|---------------|
| SS (Spring/Summer) | White, Blue, Mint | Coral, Yellow |
| FW (Fall/Winter) | Navy, Burgundy, Brown | Mustard, Copper |


## Brand-Specific Standards

### U.S. Polo Assn.

**Concept:** American lifestyle, polo heritage, sporty elegance

**Color Palette:**
- Main: Navy, White, Red
- Accent: Green, Yellow

**Fixture Style:**
- Wood + metal combination
- Classic American style

**Window Themes:**
- Polo field
- Campus life
- Weekend casual


### Cacharel

**Concept:** Modern men's wear, French elegance, sophisticated

**Color Palette:**
- Main: Navy, Grey, Black
- Accent: Dark tones, classic combinations

**Fixture Style:**
- Classic lines
- Modern details

**Window Themes:**
- Business elegance
- Urban sophistication
- French classic style


## VM Checklist

### Daily Check

- [ ] Are all products properly hung/folded?
- [ ] Is size sequencing correct?
- [ ] Are there empty hangers/shelves?
- [ ] Are price tags visible?
- [ ] Is lighting working?
- [ ] Is floor clean?
- [ ] Are mannequins properly dressed?

### Weekly Check

- [ ] Are window products current?
- [ ] Are color blocks organized?
- [ ] Are fixtures clean?
- [ ] Is signage up to date?
- [ ] Is top-bottom ratio balanced?
- [ ] Are campaign materials in place?

### Monthly Check

- [ ] Is window theme seasonally appropriate?
- [ ] Is fixture layout optimized?
- [ ] Is stock distribution balanced?
- [ ] Was lighting maintenance performed?
- [ ] Was VM performance analysis conducted?


## Revision History

| Version | Date | Change | Prepared By |
|---------|------|--------|-------------|
| 1.0 | 2025-12-01 | Initial version created | Aydınlı Group |


---

## SECTION 5: BRAND-SUPPLEMENT-CACHAREL-EN

﻿---
layout: default
title: "Cacharel Brand Training Guide – EN"
parent: Training

## Training Content

### SECTION 1: BRAND STORY

#### 1.1 History

**Cacharel - French Men's Fashion Icon**
- **Founded:** 1962, by Jean Bousquet in Paris
- **First Collection:** Men's shirts and ready-to-wear
- **Perfume:** 1978 - Anaïs Anaïs (important for brand awareness)
- **Today:** French men's fashion - business and casual premium
- **Aydınlı Group:** Turkey license holder

**Key Points:**
- 60+ years of French fashion heritage
- Representative of French elegance in men's wear
- Balance between business and casual
- Modern classic men's fashion
- Positioned as men's fashion brand in Turkey

#### 1.2 Brand Values

| Value | Description |
|-------|-------------|
| **Elegance** | French men's sophistication |
| **Versatility** | Versatility for work and everyday life |
| **Quality** | Premium quality and craftsmanship |
| **Sophistication** | Refined and sophisticated design |
| **Modern Classic** | Modern classic men's fashion |

#### 1.3 Brand Story Narrative (For Customers)

```
"Cacharel has been a pioneer of French men's fashion since 1962. 
Bringing elegance and sophistication from Paris to men's wear. 
The choice of the modern man who wants to look elegant 
both in the business world and in everyday life."
```


### SECTION 3: PRODUCT CATEGORIES

#### 3.1 Men's Collection - Business

| Category | Sub-categories | Key Features |
|----------|---------------|--------------|
| **Suit** | Slim, Regular | Business world elegance |
| **Blazer** | Single Breasted | Smart casual essential |
| **Trousers** | Classic, Slim | Professional look |
| **Shirt** | Business, Non-iron | Office standard |
| **Tie** | Silk, Classic pattern | Elegant accessory |

#### 3.2 Men's Collection - Casual Premium

| Category | Sub-categories | Key Features |
|----------|---------------|--------------|
| **Polo** | Premium Pique | Sophisticated casual |
| **T-shirt** | Basic, Premium | Comfortable elegance |
| **Shirt** | Casual, Denim | Weekend elegance |
| **Knitwear** | V-neck, Crew, Cardigan | Layered outfits |
| **Trousers** | Chino, Premium Denim | Relaxed elegance |
| **Jacket** | Bomber, Denim, Parka | Premium outerwear |

#### 3.3 Accessories

| Category | Products | Feature |
|----------|----------|---------|
| **Tie** | Silk, Classic | Elegant detail |
| **Belt** | Leather, Metal buckle | Premium material |
| **Wallet** | Leather, Card holder | Italian leather |
| **Socks** | Premium cotton | Detail elegance |

#### 3.4 Iconic Products

**1. Business Suit**
- French elegance
- Slim fit modern cut
- Premium fabric
- Business world standard

**2. Premium Polo T-shirt**
- Sophisticated casual
- Premium pique fabric
- Elegant cut
- Business casual essential

**3. Non-iron Shirt**
- Wrinkle-free technology
- 100% cotton
- French cut
- Everyday use


### SECTION 5: SALES TECHNIQUES

#### 5.1 Professional Sales Approach

**Difference:**
```
U.S. Polo = Casual, product-focused
Pierre Cardin = Business, consultancy-focused
Cacharel = Dual approach, style consultancy
```

**Opening:**
```
Staff: "Welcome to Cacharel! Are you looking for work or everyday use today?"
Customer: "Both could work, need something elegant."
Staff: "I understand! Cacharel is perfect for you – we offer French elegance 
for both work and everyday life. What situations are you thinking of?"
```

#### 5.2 Style Consultancy

**Questions:**
```
"What's your work environment like – formal or semi-formal?"
"How do you like to dress on weekends?"
"What basic pieces do you currently have in your wardrobe?"
"What's your color preference – classic or modern?"
```

#### 5.3 Outfit Suggestions

| Situation | Outfit |
|-----------|--------|
| Business meeting | Suit + shirt + tie |
| Daily office | Blazer + chino + polo |
| Weekend | Premium polo + chino + sneakers |
| Dinner | Blazer + shirt + chino |
| Smart casual | Premium t-shirt + chino + blazer |

#### 5.4 Cross-sell and Upsell

**Cross-sell:**
```
Staff: "This blazer is very elegant. I can suggest chino trousers underneath, 
creates a perfect French smart casual outfit."
```

**Upsell:**
```
Staff: "This suit is nice, but I'd also like to show you our premium series. 
Fabric quality is higher level, can be worn for years."
```


### SECTION 7: PRODUCT KNOWLEDGE DETAILS

#### 7.1 Fabric Types

| Fabric | Feature | Usage |
|--------|---------|-------|
| **Wool** | Premium, breathable | Suit |
| **Pique Cotton** | Textured, durable | Polo t-shirt |
| **Poplin** | Smooth, elegant | Shirt |
| **Twill** | Diagonal texture | Chino |
| **Premium Denim** | Quality, long-lasting | Jean, jacket |
| **French Terry** | Soft, comfortable | Sweatshirt |

#### 7.2 Fit Guide

| Fit Type | Feature | Suitable For |
|----------|---------|--------------|
| **Slim Fit** | Narrow cut, modern | Young professional |
| **Regular Fit** | Standard cut | General use |
| **Classic Fit** | Comfortable, traditional | Mature customer |

#### 7.3 Size Chart

| Size | Chest (cm) | Waist (cm) |
|------|------------|------------|
| XS | 88-92 | 72-76 |
| S | 92-96 | 76-80 |
| M | 96-100 | 80-84 |
| L | 100-104 | 84-88 |
| XL | 104-108 | 88-92 |
| XXL | 108-112 | 92-96 |

#### 7.4 Care Instructions

| Product | Wash | Dry | Iron |
|---------|------|-----|------|
| Suit | Dry clean | - | - |
| Polo | 30°C | Hang dry cool | Low |
| Shirt | 40°C | Hang dry cool | Medium |
| Chino | 30°C | Hang dry cool | Low |
| Denim | 30°C inside out | Hang dry cool | Steam |


### SECTION 9: FREQUENTLY ASKED QUESTIONS

| Question | Answer |
|----------|--------|
| "Is Cacharel only business wear?" | "No, we have both business and casual premium collections. We help you look elegant from the business world to weekends." |
| "What's the difference with Pierre Cardin?" | "Cacharel focuses more on casual premium while Pierre Cardin is more business-focused. Both are French elegance but different segments." |
| "Do you do suit alterations?" | "Yes, we offer professional alteration service in our store. Hem and sleeve shortening are free on certain products." |
| "What does French cut mean?" | "French cut is a narrower, body-fitting, modern cut. It looks more elegant and contemporary than classic cut." |


## Tools & Resources

| Resource | Usage |
|----------|-------|
| Fabric Swatch Book | Fabric demonstration to customers |
| Style Guide | Business and casual outfit suggestions |
| Size Measurement Tool | Professional measuring |
| Lookbook | Seasonal style suggestions |
| Lookbook | Seasonal style suggestions |
| Care Cards | Information cards to give customers |


## Assessment Methods

### Brand Knowledge Quiz
- 20 questions
- Brand story, values, product knowledge
- Passing grade: 80%

### Style Consultancy Evaluation
- Customer profile analysis
- Outfit suggestion scenario
- Business/Casual guidance

### Product Knowledge Test
- Fabric recognition
- Fit type determination
- Care instruction knowledge


---

## SECTION 6: BRAND-SUPPLEMENT-PIERRE-CARDIN-EN

﻿---
layout: default
title: "Pierre Cardin Brand Training Guide – EN"
parent: Training

## Training Content

### SECTION 1: BRAND STORY

#### 1.1 History

**Pierre Cardin - Fashion Icon**
- **Birth:** 1922, Italy (San Biagio di Callalta)
- **Career Start:** 1945, Paris - Worked at Christian Dior
- **Own Brand:** 1950, Founded Pierre Cardin house in Paris
- **Revolution:** 1960s - Pioneer of ready-to-wear
- **Legacy:** Passed away in 2020, left lasting mark on fashion world

**Key Points:**
- Pioneer of transition from haute couture to ready-to-wear
- Known for space-age designs
- Inventor of licensing model
- Globally recognized French fashion icon
- Aydınlı Group holds Turkey license

#### 1.2 Brand Values

| Value | Description |
|-------|-------------|
| **Innovation** | Fashion innovation and trend-setting |
| **Elegance** | The essence of French sophistication |
| **Quality** | Premium materials and craftsmanship |
| **Sophistication** | Refined and sophisticated design |
| **Versatility** | Versatility for work and everyday life |

#### 1.3 Brand Story Narrative (For Customers)

```
"Pierre Cardin has been the symbol of French fashion since 1950. Our founder 
changed fashion history as the pioneer of ready-to-wear. Every piece we offer 
you today brings together French elegance with modern living."
```


### SECTION 3: PRODUCT CATEGORIES

#### 3.1 Men's Collection - Business

| Category | Sub-categories | Key Features |
|----------|---------------|--------------|
| **Suit** | Slim, Regular, Classic | Business world standard |
| **Blazer** | Single, Double Breasted | Smart casual |
| **Trousers** | Classic, Slim, Pleated | Professional look |
| **Shirt** | Business, Ceremony | Non-iron technology |
| **Tie** | Silk, Micro pattern | Elegant accessory |

#### 3.2 Men's Collection - Casual Premium

| Category | Sub-categories | Key Features |
|----------|---------------|--------------|
| **Polo** | Premium Pique | Sophisticated casual |
| **Shirt** | Casual, Denim | Weekend elegance |
| **Knitwear** | V-neck, Crew, Cardigan | Layered outfits |
| **Trousers** | Chino, Premium Denim | Relaxed elegance |
| **Jacket** | Leather, Blazer, Parka | Premium outerwear |

#### 3.3 Women's Collection

| Category | Sub-categories | Key Features |
|----------|---------------|--------------|
| **Blazer** | Classic, Oversize | Office elegance |
| **Trousers** | Classic, Wide Leg | Professional cut |
| **Shirt** | Satin, Poplin | Feminine details |
| **Dress** | Business, Cocktail | Versatile |
| **Knitwear** | Fine Knit | Elegant layer |

#### 3.4 Accessories

| Category | Products | Feature |
|----------|----------|---------|
| **Tie** | Silk, Micro pattern | Handmade |
| **Belt** | Leather, Metal buckle | Premium material |
| **Wallet** | Leather, Card holder | Italian leather |
| **Cufflinks** | Metal, Stone | Detail elegance |

#### 3.5 Iconic Products

**1. Business Suit**
- Brand signature
- 100% wool, Italian fabric
- Modern slim fit
- Fully lined

**2. Non-iron Shirt**
- Wrinkle-free technology
- 100% cotton
- Spread collar
- Businessman favorite

**3. Silk Tie**
- 100% pure silk
- Hand-stitched
- Italian design
- Timeless patterns


### SECTION 5: SALES TECHNIQUES

#### 5.1 Consultative Sales

**Approach Difference:**
```
U.S. Polo = Product-focused, quick
Pierre Cardin = Consultancy-focused, detailed
```

**Opening:**
```
Staff: "Welcome to Pierre Cardin. Do you have a specific need today, 
or would you like to browse our collection in general?"
Customer: "I have an important meeting, need something elegant."
Staff: "I understand. What kind of setting is the meeting? 
Formal or semi-formal? I can recommend the most suitable combination for you."
```

#### 5.2 Wardrobe Consultancy

**Questions:**
```
"What basic pieces do you currently have in your wardrobe?"
"Which colors do you prefer more?"
"Are you thinking everyday or special occasion?"
"Your preference for fit – fitted or regular?"
```

#### 5.3 Outfit Sales

| Situation | Outfit Suggestion |
|-----------|------------------|
| Business meeting | Suit + shirt + tie |
| Daily office | Blazer + trousers + polo |
| Dinner | Blazer + shirt + chino |
| Formal event | Dark suit + white shirt + silk tie |

#### 5.4 Premium Sales Techniques

**Value Narration:**
```
Staff: "The fabric used in this suit is from Italy, 100% wool. 
Tailored in Turkey, with handcraft details. You can wear it for years, 
so think of it as an investment piece."
```

**Price Objection Handling:**
```
Customer: "Isn't it a bit expensive?"
Staff: "I understand. However, consider the lifetime value of this piece. 
A quality suit can be worn for 10 years. If you calculate the annual cost, 
it's actually a very reasonable investment."
```


### SECTION 7: PRODUCT KNOWLEDGE DETAILS

#### 7.1 Fabric Types - Suits

| Fabric | Feature | Usage |
|--------|---------|-------|
| **100% Wool** | Premium, breathable | 4-season business |
| **Wool-Silk** | Shiny finish, soft | Special occasions |
| **Wool-Cashmere** | Luxury, warm | Winter business |
| **Stretch Wool** | Flexible, comfortable | Modern business |
| **Tropical Wool** | Light, cool | Summer business |

#### 7.2 Fabric Types - Shirts

| Fabric | Feature | Usage |
|--------|---------|-------|
| **Poplin** | Smooth, elegant | Formal |
| **Twill** | Diagonal texture | Business casual |
| **Oxford** | Textured | Smart casual |
| **Satin** | Shiny | Special occasion |
| **Non-iron** | Wrinkle-free | Daily business |

#### 7.3 Suit Fit Guide

| Fit Type | Feature | Suitable For |
|----------|---------|--------------|
| **Slim Fit** | Narrow cut, modern | Young professional |
| **Regular Fit** | Standard cut | General use |
| **Classic Fit** | Comfortable, traditional | Mature customer |
| **Athletic Fit** | Wide shoulders, narrow waist | Athletic build |

#### 7.4 Shirt Collar Types

| Collar | Feature | Usage |
|--------|---------|-------|
| **Spread** | Wide angle | With tie |
| **Kent** | Medium angle | Any situation |
| **Button-down** | Buttoned | Casual |
| **Cutaway** | Very wide | Thick tie |

#### 7.5 Care Instructions - Premium Products

| Product | Care | Storage |
|---------|------|---------|
| Suit | Dry clean | Garment bag, wooden hanger |
| Silk Tie | Dry clean | Lay flat |
| Leather Belt | Moisturizer | Flat, no buckle |
| Non-iron Shirt | 40°C wash | Hanging |


### SECTION 9: FREQUENTLY ASKED QUESTIONS

| Question | Answer |
|----------|--------|
| "Is Pierre Cardin still managed by the designer himself?" | "Unfortunately Pierre Cardin passed away in 2020, but his legacy and design philosophy continue to live in our brand." |
| "Do you do suit alterations?" | "Yes, we offer professional alteration service in our store. Hem and sleeve shortening are free on certain products." |
| "Can silk tie be washed?" | "Silk tie should be dry cleaned. We don't recommend washing at home, professional cleaning is essential for stains." |
| "How to choose suit size?" | "Jacket size is determined by your chest measurement, trousers by your waist measurement. I recommend we take professional measurements for you." |


## Tools & Resources

| Resource | Usage |
|----------|-------|
| Fabric Swatch Book | Fabric demonstration to customers |
| Style Guide | Business dress code information |
| Size Measurement Tool | Professional measuring |
| Lookbook | Seasonal style suggestions |
| Care Cards | Information cards to give customers |


## Assessment Methods

### Premium Sales Quiz
- 20 questions
- Fabric knowledge, fit, style recommendations
- Passing grade: 85%

### Style Consultancy Evaluation
- Customer profile analysis
- Outfit recommendation scenario
- Wardrobe consultancy role-play

### Product Knowledge Test
- Fabric recognition (by touch)
- Fit type determination
- Care instruction knowledge


---

## SECTION 7: BRAND-SUPPLEMENT-USPA-EN

﻿---
layout: default
title: "U.S. Polo Assn. Brand Training Guide – EN"
parent: Training

## Training Content

### SECTION 1: BRAND STORY

#### 1.1 History

**United States Polo Association (USPA)**
- **Founded:** 1890, USA
- **Mission:** To promote and expand polo sport in America
- **Status:** Official governing body of polo sport in the USA
- **License:** U.S. Polo Assn. clothing brand is USPA's official licensed product

**Key Points:**
- 130+ years of polo heritage
- Official brand of a real sports organization
- Sales in 180+ countries worldwide
- Aydınlı Group holds Turkey license

#### 1.2 Brand Values

| Value | Description |
|-------|-------------|
| **Authenticity** | Originality based on real polo heritage |
| **Quality** | Premium quality, affordable price |
| **Heritage** | American sports tradition |
| **Lifestyle** | Active, dynamic lifestyle |
| **Accessibility** | Accessible luxury for everyone |

#### 1.3 Brand Story Narrative (For Customers)

```
"U.S. Polo Assn. has been the official polo sport institution in America since 1890. 
This brand brings the elegance of polo sport and American lifestyle to everyday life. 
With over 130 years of heritage, we offer quality and authentic pieces."
```


### SECTION 3: PRODUCT CATEGORIES

#### 3.1 Men's Collection

| Category | Sub-categories | Key Features |
|----------|---------------|--------------|
| **Polo T-shirt** | Classic, Slim Fit, Big Horse | Iconic product, brand DNA |
| **T-shirt** | Basic, Graphic, V-neck | Everyday use, comfortable cut |
| **Shirt** | Oxford, Casual, Denim | Smart casual style |
| **Pants** | Chino, Denim, Jogger | Stylish and comfortable |
| **Sweatshirt** | Hoodie, Crew neck, Zip-up | Sporty elegance |
| **Coat/Jacket** | Bomber, Denim, Parka | Seasonal outerwear |
| **Accessories** | Hat, Belt, Socks, Bag | Outfit complementers |

#### 3.2 Women's Collection

| Category | Sub-categories | Key Features |
|----------|---------------|--------------|
| **Polo T-shirt** | Classic, Fitted | Feminine cuts |
| **T-shirt** | Basic, Crop, Oversized | Trendy models |
| **Shirt** | Oxford, Casual | Smart casual |
| **Pants** | Chino, Denim | Slim and regular fit |
| **Dress** | Polo Dress, Casual | Sport chic |
| **Knitwear** | V-neck, Crew | Layered dressing |
| **Accessories** | Bag, Scarf | Style completers |

#### 3.3 Kids Collection

| Category | Age Group | Features |
|----------|-----------|----------|
| **Boys** | 4-14 years | Mini men's collection |
| **Girls** | 4-14 years | Mini women's collection |
| **Baby** | 0-3 years | Baby sets |

#### 3.4 Iconic Products

**1. Classic Polo T-shirt**
- Brand signature product
- 100% cotton pique fabric
- Embroidered logo
- Contrast collar detail

**2. Big Horse Polo**
- Large logo version
- Statement piece
- Young target group favorite

**3. Oxford Shirt**
- Smart casual essential
- Button-down collar
- Matches any outfit


### SECTION 5: SALES TECHNIQUES

#### 5.1 Brand Story Selling

**Opening:**
```
Staff: "U.S. Polo Assn. is the official polo sport brand in America, 
did you know? With 130 years of heritage, we offer authentic American style."
```

**Product Narration:**
```
Staff: "This polo t-shirt is our brand's iconic product. Real polo players 
wear this logo. The fabric is pique cotton, breathable and shape-retaining."
```

#### 5.2 Cross-sell Recommendations

| Main Product | Cross-sell Suggestion |
|--------------|----------------------|
| Polo T-shirt | Chino pants, belt |
| Oxford Shirt | Chino, denim jacket |
| Jogger | Sweatshirt, sneaker |
| Denim | Basic t-shirt, polo |

#### 5.3 Upsell Opportunities

| Basic Product | Premium Alternative |
|---------------|---------------------|
| Basic Polo | Big Horse Polo |
| Regular T-shirt | Premium Cotton T-shirt |
| Basic Chino | Stretch Chino |

#### 5.4 Seasonal Sales Highlights

| Season | Featured Products | Key Message |
|--------|------------------|-------------|
| Spring | Polo, Oxford, Chino | "New season, new beginning" |
| Summer | Polo, T-shirt, Shorts | "Summer energy" |
| Fall | Sweatshirt, Denim | "Layered dressing" |
| Winter | Coat, Knitwear, Scarf | "Warm and stylish" |


### SECTION 7: PRODUCT KNOWLEDGE DETAILS

#### 7.1 Fabric Types

| Fabric | Usage | Feature |
|--------|-------|---------|
| **Pique Cotton** | Polo t-shirt | Breathable, durable |
| **Jersey** | T-shirt | Soft, flexible |
| **Oxford** | Shirt | Textured, elegant |
| **Twill** | Chino | Durable, structured |
| **French Terry** | Sweatshirt | Keeps warm, comfortable |
| **Denim** | Jean, jacket | Classic, long-lasting |

#### 7.2 Fit Guide

| Fit Type | Feature | Suitable For |
|----------|---------|--------------|
| **Slim Fit** | Body-hugging | Athletic build |
| **Regular Fit** | Standard cut | Everyone |
| **Relaxed Fit** | Loose cut | Comfort seekers |
| **Classic Fit** | Traditional | Mature customer |

#### 7.3 Size Chart

| Size | Chest (cm) | Waist (cm) |
|------|------------|------------|
| XS | 88-92 | 72-76 |
| S | 92-96 | 76-80 |
| M | 96-100 | 80-84 |
| L | 100-104 | 84-88 |
| XL | 104-108 | 88-92 |
| XXL | 108-112 | 92-96 |

#### 7.4 Care Instructions

| Product | Wash | Dry | Iron |
|---------|------|-----|------|
| Polo | 30°C | Hang dry cool | Low heat |
| T-shirt | 30°C | Hang dry cool | Low if needed |
| Shirt | 40°C | Hang dry cool | Medium heat |
| Denim | 30°C inside out | Hang dry cool | Steam |
| Knitwear | Hand wash or 30°C | Flat dry | Steam |


### SECTION 9: FREQUENTLY ASKED QUESTIONS

| Question | Answer |
|----------|--------|
| "Is this brand the same as Polo Ralph Lauren?" | "No, U.S. Polo Assn. is the official brand of the US Polo Association, while Polo RL is a designer brand. They are different companies." |
| "Why is there a two-horse logo?" | "The two-horse logo is the polo match symbol, representing the game. The single-horse logo only shows the player." |
| "Is it made in Turkey?" | "Production is done in various countries including Turkey. Quality standards are global." |
| "Does it go on sale?" | "We have end-of-season sales and special campaigns. With CRM membership, you'll be the first to know about campaigns." |


## Tools & Resources

| Resource | Usage |
|----------|-------|
| Brand Booklet | Brand story and values |
| Product Catalog | Seasonal product information |
| Fit Guide Poster | In-store size guide |
| Training Video | Brand introduction video |
| Fabric Samples | Tactile training set |


## Assessment Methods

### Brand Knowledge Quiz
- 20 questions, multiple choice
- Brand story, values, product knowledge
- Passing grade: 80%

### Product Recognition Test
- 10 product images
- Fabric, fit, feature identification
- Practical evaluation

### Role-Play
- Customer scenario
- Brand story narration
- Cross-sell/Upsell application


---

## SECTION 8: COMPETENCY-FRAMEWORK-EN

﻿---
layout: default
title: "Competency Framework"
parent: Training

## Table of Contents

1. [Purpose](#purpose)
2. [Scope](#scope)
3. [Learning Objectives](#learning-objectives)
4. [Competency Levels](#competency-levels)
5. [Competency Areas](#competency-areas)
6. [Skills Matrix](#skills-matrix)
7. [Level Progression Criteria](#level-progression-criteria)
8. [Assessment Process](#assessment-process)
9. [Career Path](#career-path)
10. [Role Responsibilities](#role-responsibilities)
11. [KPIs and Performance Indicators](#kpis-and-performance-indicators)
12. [Common Mistakes and Coaching Notes](#common-mistakes-and-coaching-notes)
13. [Revision History](#revision-history)


## Scope

### Target Audience

| Role | Starting Level | Target Level |
|------|----------------|--------------|
| **Sales Associate** | Level 1 | Level 3-5 |
| **Assistant Store Manager** | Level 3 | Level 4-5 |
| **Store Manager** | Level 4 | Level 5 |

### Competency System Overview

```
┌─────────────────────────────────────────────────────────────────┐
│              5-LEVEL COMPETENCY SYSTEM                          │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  LEVEL 5: EXPERT (12+ months)                                  │
│     ████████████████████████████████████████  100%             │
│     Trainer, leader, excellence model                          │
│                                                                 │
│  LEVEL 4: SENIOR (6-12 months)                                 │
│     ██████████████████████████████  80%                        │
│     Mentor, difficult scenarios, autonomous                    │
│                                                                 │
│  LEVEL 3: PROFICIENT (3-6 months)                              │
│     ████████████████████████  60%                              │
│     Independent, cross-selling, CRM                            │
│                                                                 │
│  LEVEL 2: JUNIOR (1-3 months)                                  │
│     ████████████████  40%                                      │
│     Basic sales, product knowledge                             │
│                                                                 │
│  LEVEL 1: TRAINEE (0-30 days)                                  │
│     ████████  20%                                              │
│     Orientation, observation, learning                         │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```


## Competency Levels

### Level 1: Trainee

```
┌─────────────────────────────────────────────────────────────────┐
│              LEVEL 1: TRAINEE                                   │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  DURATION: 0-30 days                                           │
│                                                                 │
│  DEFINITION:                                                   │
│  Newly hired personnel in orientation process.                 │
│  In observation and learning phase.                            │
│                                                                 │
│  EXPECTATIONS:                                                 │
│  ✓ Learn store rules                                           │
│  ✓ Recognize product categories                                │
│  ✓ Understand POS system basics                                │
│  ✓ Know customer greeting standard                             │
│  ✓ Work under Buddy guidance                                   │
│                                                                 │
│  LIMITATIONS:                                                  │
│  ✗ Cannot make independent sales                               │
│  ✗ Cannot do register operations (without supervision)         │
│  ✗ Cannot resolve complaints                                   │
│                                                                 │
│  COMPLETION CRITERIA:                                          │
│  • Complete 30-day orientation                                 │
│  • Certification exam 70%+                                     │
│  • Store Manager approval                                      │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Level 2: Junior

```
┌─────────────────────────────────────────────────────────────────┐
│              LEVEL 2: JUNIOR                                    │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  DURATION: 1-3 months                                          │
│                                                                 │
│  DEFINITION:                                                   │
│  Personnel who gained basic competencies and can make          │
│  independent sales. Still needs support.                       │
│                                                                 │
│  EXPECTATIONS:                                                 │
│  ✓ Independent customer greeting                               │
│  ✓ Basic sales conversation                                    │
│  ✓ Product knowledge presentation                              │
│  ✓ Fitting room service                                        │
│  ✓ POS operations (sales, returns)                            │
│  ✓ Stock checking                                              │
│                                                                 │
│  DEVELOPMENT AREAS:                                            │
│  → Objection handling                                          │
│  → Add-on sales techniques                                     │
│  → Difficult customer management                               │
│                                                                 │
│  COMPLETION CRITERIA:                                          │
│  • Minimum 3 months experience                                 │
│  • Achieving 80% of monthly targets                            │
│  • Practical assessment "Good" or above                        │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Level 3: Proficient

```
┌─────────────────────────────────────────────────────────────────┐
│              LEVEL 3: PROFICIENT                                │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  DURATION: 3-6 months                                          │
│                                                                 │
│  DEFINITION:                                                   │
│  Personnel who can work fully independently, achieve targets,  │
│  and perform cross-selling.                                    │
│                                                                 │
│  EXPECTATIONS:                                                 │
│  ✓ Fully independent sales                                     │
│  ✓ Objection handling                                          │
│  ✓ Cross-selling and add-on sales                             │
│  ✓ CRM data collection and usage                              │
│  ✓ Complaint resolution (basic level)                         │
│  ✓ VM support                                                  │
│  ✓ Stock management participation                              │
│                                                                 │
│  DEVELOPMENT AREAS:                                            │
│  → Mentoring skills                                            │
│  → Leadership fundamentals                                     │
│  → Advanced sales techniques                                   │
│                                                                 │
│  COMPLETION CRITERIA:                                          │
│  • Minimum 6 months experience                                 │
│  • Achieving 100% of monthly targets                           │
│  • Success in UPT and ATV targets                             │
│  • 360° assessment "Good" or above                            │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Level 4: Senior

```
┌─────────────────────────────────────────────────────────────────┐
│              LEVEL 4: SENIOR                                    │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  DURATION: 6-12 months                                         │
│                                                                 │
│  DEFINITION:                                                   │
│  Personnel showing excellent performance, taking mentor role,  │
│  capable of managing difficult situations.                     │
│                                                                 │
│  EXPECTATIONS:                                                 │
│  ✓ Excellent sales performance                                 │
│  ✓ Mentoring new staff                                         │
│  ✓ Difficult customer/scenario management                      │
│  ✓ Shift responsibility                                        │
│  ✓ Complaint management (advanced level)                       │
│  ✓ VM implementation                                           │
│  ✓ Opening/closing responsibility                              │
│                                                                 │
│  ADDITIONAL RESPONSIBILITIES:                                  │
│  → Coaching Level 1-2 staff                                    │
│  → Daily operations support                                    │
│  → Represent in manager's absence                             │
│                                                                 │
│  COMPLETION CRITERIA:                                          │
│  • Minimum 12 months experience                                │
│  • Achieving 110%+ of targets (consistently)                   │
│  • Mentored at least 2 personnel                              │
│  • Leadership assessment "Good" or above                       │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Level 5: Expert

```
┌─────────────────────────────────────────────────────────────────┐
│              LEVEL 5: EXPERT                                    │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  DURATION: 12+ months                                          │
│                                                                 │
│  DEFINITION:                                                   │
│  Excellence model, trainer level, capable of                   │
│  store leadership.                                             │
│                                                                 │
│  EXPECTATIONS:                                                 │
│  ✓ Consistently superior performance                           │
│  ✓ Official trainer role                                       │
│  ✓ Store leadership capacity                                   │
│  ✓ Strategic thinking                                          │
│  ✓ Problem-solving expertise                                   │
│  ✓ Best practice development                                   │
│  ✓ Regional level contribution                                 │
│                                                                 │
│  LEADERSHIP AREAS:                                             │
│  → In-store training leadership                                │
│  → New store opening support                                   │
│  → Pilot program participation                                 │
│  → HQ coordination                                             │
│                                                                 │
│  CAREER OPTIONS:                                               │
│  → Assistant Store Manager                                     │
│  → Store Manager                                               │
│  → Regional Trainer                                            │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```


## Skills Matrix

### Sales Skills Matrix

| Skill | Level 1 | Level 2 | Level 3 | Level 4 | Level 5 |
|-------|---------|---------|---------|---------|---------|
| **Greeting** | Learning | Can do | Mastered | Excellent | Can train |
| **Needs Analysis** | Observing | Basic questions | In-depth | Expert | Can train |
| **Product Presentation** | Learning | Basic | Storytelling | Excellent | Can train |
| **Objection Handling** | - | Learning | Can do | Mastered | Can train |
| **Closing** | - | Basic | Advanced | Excellent | Can train |
| **Add-on Sales** | - | Learning | Can do | Mastered | Can train |

### Customer Service Matrix

| Skill | Level 1 | Level 2 | Level 3 | Level 4 | Level 5 |
|-------|---------|---------|---------|---------|---------|
| **Fitting Room** | Observing | Can do | Excellent | Excellent | Can train |
| **Complaints** | - | Observing | Basic | Advanced | Expert |
| **CRM** | Learning | Basic | Full usage | Analysis | Strategy |
| **Problem Solving** | - | Basic | Intermediate | Advanced | Expert |

### Operational Skills Matrix

| Skill | Level 1 | Level 2 | Level 3 | Level 4 | Level 5 |
|-------|---------|---------|---------|---------|---------|
| **POS Usage** | Learning | Can do | Full | Full | Can train |
| **Cash Management** | - | Supervised | Independent | Responsibility | Can train |
| **Stock Operations** | Basic | Can do | Full | Management | Can train |
| **Opening/Closing** | Observing | Participation | Can do | Responsibility | Can train |
| **VM** | Observing | Support | Implementation | Management | Can train |


## Assessment Process

### Assessment Calendar

| Assessment | Frequency | Responsible | Purpose |
|------------|-----------|-------------|---------|
| **Daily Observation** | Daily | Shift Lead | Instant feedback |
| **Weekly Check-in** | Weekly | Store Manager | Progress tracking |
| **Monthly Performance** | Monthly | Store Manager | KPI assessment |
| **Quarterly 360°** | Every 3 months | Regional Manager | Comprehensive assessment |
| **Level Assessment** | As needed | Relevant manager | Level transition |

### Competency Assessment Form

```
┌─────────────────────────────────────────────────────────────────┐
│              COMPETENCY ASSESSMENT FORM                         │
├─────────────────────────────────────────────────────────────────┤
│ Staff: _________________  Current Level: ___                   │
│ Assessor: _____________  Date: ___/___/______                  │
│ Assessment Type: [ ] Routine [ ] Level Transition             │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│ SALES SKILLS                        1  2  3  4  5              │
│ Customer greeting                  [ ][ ][ ][ ][ ]             │
│ Needs analysis                     [ ][ ][ ][ ][ ]             │
│ Product presentation               [ ][ ][ ][ ][ ]             │
│ Objection handling                 [ ][ ][ ][ ][ ]             │
│ Closing sales                      [ ][ ][ ][ ][ ]             │
│ Add-on sales                       [ ][ ][ ][ ][ ]             │
│                                                                 │
│ PRODUCT KNOWLEDGE                   1  2  3  4  5              │
│ Fabric knowledge                   [ ][ ][ ][ ][ ]             │
│ Fit knowledge                      [ ][ ][ ][ ][ ]             │
│ Brand knowledge                    [ ][ ][ ][ ][ ]             │
│                                                                 │
│ CUSTOMER SERVICE                    1  2  3  4  5              │
│ Fitting room service               [ ][ ][ ][ ][ ]             │
│ Complaint management               [ ][ ][ ][ ][ ]             │
│ CRM management                     [ ][ ][ ][ ][ ]             │
│                                                                 │
│ OPERATIONS                          1  2  3  4  5              │
│ POS usage                          [ ][ ][ ][ ][ ]             │
│ Stock operations                   [ ][ ][ ][ ][ ]             │
│ VM implementation                  [ ][ ][ ][ ][ ]             │
│                                                                 │
│ TEAMWORK                            1  2  3  4  5              │
│ Collaboration                      [ ][ ][ ][ ][ ]             │
│ Communication                      [ ][ ][ ][ ][ ]             │
│                                                                 │
│ LEADERSHIP (Level 4-5)              1  2  3  4  5              │
│ Mentoring                          [ ][ ][ ][ ][ ]             │
│ Coaching                           [ ][ ][ ][ ][ ]             │
│                                                                 │
│ OVERALL SCORE: _____/100                                       │
│                                                                 │
│ STRENGTHS:                                                     │
│ ______________________________________________________________ │
│                                                                 │
│ DEVELOPMENT AREAS:                                             │
│ ______________________________________________________________ │
│                                                                 │
│ LEVEL TRANSITION RECOMMENDATION: [ ] Yes [ ] No               │
│ Justification: _______________________________________________ │
│                                                                 │
│ Assessor Sign: _____________                                   │
│ Staff Sign: _____________                                      │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```


## Role Responsibilities

### Staff

| Responsibility | Detail |
|----------------|--------|
| Self-assessment | Know own level |
| Development plan | Identify development areas |
| Training participation | Complete required training |
| Performance | Achieve targets |

### Store Manager

| Responsibility | Detail |
|----------------|--------|
| Assessment | Regular competency assessment |
| Coaching | Provide development support |
| Recommendation | Level transition recommendation |
| Tracking | Monitor progress |

### Regional Manager

| Responsibility | Detail |
|----------------|--------|
| Approval | Level 4-5 transition approval |
| Audit | Monitor assessment quality |
| Standard | Consistency across region |


## Common Mistakes and Coaching Notes

### Common Mistakes in Competency Development

| Mistake | Result | Correction |
|---------|--------|------------|
| Trying to skip levels | Failure | Step-by-step progression |
| Not getting feedback | Development slows | Request regular feedback |
| Focusing only on sales | One-dimensional | Develop all competencies |
| Refusing mentorship | Missing opportunity | Be open to learning |

### Coaching Tips

```
FOR LEVEL 1-2:
• Focus on basic skills
• Be patient, turn mistakes into learning
• Celebrate small wins
• Give regular feedback

FOR LEVEL 3-4:
• Set advanced goals
• Create mentorship opportunities
• Develop leadership skills
• Give challenging tasks

FOR LEVEL 5:
• Encourage strategic thinking
• Offer training opportunities
• Do career planning
• Assign regional level projects
```


*This document was prepared by Aydınlı Group Franchise Operations.*  
*© 2025 Aydınlı Group - All rights reserved.*




---

## SECTION 9: CUSTOMER-EXPERIENCE-STANDARDS-EN

﻿---
layout: default
title: "Customer Experience Standards"
parent: Training

## Table of Contents

1. [Purpose](#purpose)
2. [Scope](#scope)
3. [Learning Objectives](#learning-objectives)
4. [Key Concepts](#key-concepts)
5. [Aydınlı Customer Experience Model](#aydınlı-customer-experience-model)
6. [Greeting Standards](#greeting-standards)
7. [Fitting Room Service](#fitting-room-service)
8. [Problem Solving and Complaint Management](#problem-solving-and-complaint-management)
9. [CRM Actions](#crm-actions)
10. [Role Responsibilities](#role-responsibilities)
11. [KPIs and Performance Indicators](#kpis-and-performance-indicators)
12. [Scenarios](#scenarios)
13. [Common Mistakes and Coaching Notes](#common-mistakes-and-coaching-notes)
14. [Assessment Methods](#assessment-methods)
15. [Revision History](#revision-history)


## Scope

### Target Audience

| Role | Training Content |
|------|------------------|
| **Sales Associate** | All customer experience standards |
| **Cashier** | Payment experience, farewell |
| **Store Manager** | Complaint management, CRM, team coaching |
| **Regional Manager** | Experience auditing, best practice sharing |

### Customer Journey Map

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    CUSTOMER JOURNEY MAP                                     │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   1.DISCOVERY    2.ENTRY      3.BROWSING     4.FITTING     5.PURCHASE     │
│      │             │              │              │              │           │
│      ▼             ▼              ▼              ▼              ▼           │
│  ┌───────┐    ┌─────────┐    ┌─────────┐    ┌─────────┐    ┌─────────┐    │
│  │Window │    │Greeting │    │ Help    │    │ Fitting │    │Register │    │
│  │Online │    │First    │    │ Present │    │  Room   │    │ Payment │    │
│  │Advert │    │Impression│   │ Suggest │    │ Service │    │ Package │    │
│  └───────┘    └─────────┘    └─────────┘    └─────────┘    └─────────┘    │
│                                                                             │
│   6.FAREWELL     7.AFTERCARE                                               │
│      │               │                                                      │
│      ▼               ▼                                                      │
│  ┌─────────┐    ┌─────────┐                                                │
│  │Thank You│    │  CRM    │                                                │
│  │Send Off │    │Contact  │                                                │
│  │         │    │Loyalty  │                                                │
│  └─────────┘    └─────────┘                                                │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```


## Key Concepts

### Customer Experience Terminology

| Term | Definition | Importance |
|------|------------|------------|
| **CX (Customer Experience)** | Customer experience | Sum of all touchpoints |
| **NPS (Net Promoter Score)** | Recommendation score | Customer loyalty measurement |
| **CSAT (Customer Satisfaction)** | Customer satisfaction | Instant satisfaction measurement |
| **Touchpoint** | Contact point | Moment of customer interaction |
| **Customer Journey** | Customer journey | End-to-end experience |
| **Service Recovery** | Service recovery | Turning complaint into opportunity |

### Customer Expectations

```
┌─────────────────────────────────────────────────────────────────┐
│               CUSTOMER EXPECTATION PYRAMID                      │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│                        ▲ SURPRISING                             │
│                       ▲▲▲ (WOW Moments)                         │
│                      ▲▲▲▲▲                                      │
│                     ▲▲▲▲▲▲▲ DESIRED                             │
│                    ▲▲▲▲▲▲▲▲▲ (Above expectation)               │
│                   ▲▲▲▲▲▲▲▲▲▲▲                                   │
│                  ▲▲▲▲▲▲▲▲▲▲▲▲▲ EXPECTED                         │
│                 ▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲ (Standard service)             │
│                ▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲                                │
│               ▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲ BASIC                        │
│              ▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲▲ (Minimum requirements)      │
│                                                                 │
│  💡 Goal: Meet Expected, Create Surprising moments             │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```


## Greeting Standards

### First 10 Seconds Rule

```
┌─────────────────────────────────────────────────────────────────┐
│              FIRST 10 SECONDS STANDARD                          │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  SECONDS 1-3: EYE CONTACT                                      │
│  • Notice the customer                                         │
│  • Make eye contact                                            │
│  • Smile                                                       │
│                                                                 │
│  SECONDS 4-7: GREETING                                         │
│  • Say "Welcome"                                               │
│  • Use sincere tone                                            │
│  • Display open body language                                  │
│                                                                 │
│  SECONDS 8-10: INVITATION                                      │
│  • Say "Please come in, we're here to help"                   │
│  • Create space (don't follow)                                 │
│  • Stay available (don't go too far)                          │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Greeting Phrases

**Standard Greeting:**
```
✅ "Welcome!"
✅ "Hello, welcome!"
✅ "Good morning/afternoon, welcome!"
✅ "Welcome, may I help you?"
```

**Situation-Specific Greeting:**
```
Rainy day: "Welcome, hope you didn't get too wet!"
Cold day: "Welcome, it's warm inside, please come in!"
Busy day: "Welcome, we're a bit busy but I'll be with you shortly."
Regular customer: "Welcome Sir/Madam, lovely to see you again!"
```

### Body Language Standards

| Correct | Incorrect |
|---------|-----------|
| Standing, upright posture | Sitting, leaning |
| Eye contact | On phone |
| Open arms | Crossed arms |
| Genuine smile | Forced expression |
| 1.5-2m distance | Too close/too far |
| Facing customer | Back turned |


## Problem Solving and Complaint Management

### LEARN Model

```
┌─────────────────────────────────────────────────────────────────┐
│                    LEARN MODEL                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  L - Listen                                                    │
│      • Don't interrupt                                         │
│      • Listen actively                                         │
│      • Take notes                                              │
│                                                                 │
│  E - Empathize                                                 │
│      • "I understand, that must be very frustrating"          │
│      • "You're right, this is unacceptable"                   │
│                                                                 │
│  A - Apologize                                                 │
│      • Sincere apology                                         │
│      • Take personal responsibility                            │
│      • Don't blame                                             │
│                                                                 │
│  R - Resolve                                                   │
│      • Offer solution                                          │
│      • Present alternatives                                    │
│      • Take quick action                                       │
│                                                                 │
│  N - Notify                                                    │
│      • Explain the process                                     │
│      • Promise follow-up                                       │
│      • Thank them                                              │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Common Complaints and Solutions

| Complaint | First Response | Solution |
|-----------|----------------|----------|
| **Defective product** | "I'm so sorry, let's exchange right away" | Immediate exchange/refund |
| **Wrong size** | "Let's find the right size immediately" | Size exchange |
| **Price difference** | "Let me check right away" | Price correction/discount |
| **Long wait** | "I apologize for keeping you waiting" | Priority service |
| **Staff behavior** | "I'm so sorry, this is unacceptable" | Apology + Manager handover |

### Complaint Management Dialogue

```
┌─────────────────────────────────────────────────────────────────┐
│              COMPLAINT MANAGEMENT DIALOGUE                      │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│ CUSTOMER: "I bought this shirt last week and the color        │
│            ran in the first wash. This is unacceptable!"       │
│                                                                 │
│ STAFF: [LISTEN - Don't interrupt]                              │
│                                                                 │
│ STAFF: "I completely understand, that's a really frustrating  │
│         situation. Having this happen with a new product       │
│         is very disappointing."                                │
│         [EMPATHIZE]                                            │
│                                                                 │
│ STAFF: "I'm very sorry about this. This is unacceptable       │
│         for us as well."                                       │
│         [APOLOGIZE]                                            │
│                                                                 │
│ STAFF: "Let's resolve this right away. I can offer you        │
│         two options: We can exchange it for a new product      │
│         or give you a full refund. Which would you prefer?"   │
│         [RESOLVE]                                              │
│                                                                 │
│ CUSTOMER: "I'll take the exchange."                            │
│                                                                 │
│ STAFF: "I'll take care of it immediately. I'm also noting     │
│         what happened and will report to headquarters.         │
│         Thank you for letting us know."                        │
│         [NOTIFY]                                               │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Escalation Procedure

```
LEVEL 1: SALES ASSOCIATE
├── Simple complaints
├── Size/color exchange
├── Minor price differences
└── Wait time complaints

        │ If unresolved
        ▼

LEVEL 2: STORE MANAGER
├── Complex return requests
├── High-value complaints
├── Staff complaints
└── Recurring issues

        │ If unresolved
        ▼

LEVEL 3: REGIONAL MANAGER / HQ
├── Legal matters
├── Media threats
├── Serious product defects
└── Systemic issues
```


## Role Responsibilities

### Sales Associate

| Responsibility | Detail |
|----------------|--------|
| Greeting | Standard greeting for every customer |
| Fitting room service | Professional fitting service |
| Problem solving | First level complaint resolution |
| CRM | Collecting customer information |
| Farewell | Standard and warm send-off |

### Store Manager

| Responsibility | Detail |
|----------------|--------|
| Standards audit | Daily CX standards check |
| Complaint management | Level 2 complaint resolution |
| CRM management | Data quality tracking |
| Coaching | Team performance coaching |
| Reporting | Weekly CX report |

### Regional Manager

| Responsibility | Detail |
|----------------|--------|
| Mystery shopping | Secret shopper coordination |
| Best practice | Sharing successful examples |
| Escalation | Level 3 complaint resolution |
| Analysis | Regional CX analysis |


## Scenarios

### Scenario 1: Creating a WOW Moment

```
SITUATION: Regular customer visiting near their birthday.

STEPS:
1. Recognize customer: Check birthday info from CRM
2. Special greeting: "Welcome [Name], your birthday is 
   coming up, how nice!"
3. Surprise offer: "You have a special 15% birthday discount code"
4. Extra attention: "Shall I show you our new season pieces 
   specially for you?"
5. Gift: Small birthday gift (accessory, perfume sample)

RESULT: Customer satisfaction, loyalty increase, social media share
```

### Scenario 2: Difficult Customer Management

```
SITUATION: Customer loudly claiming a 1-month-old product is defective.

STEPS:
1. Stay calm, don't get defensive
2. Invite customer to quiet area: "Let's step over here, 
   we can talk more comfortably"
3. Apply LEARN model:
   - LISTEN: Listen to complaint completely
   - EMPATHIZE: "I completely understand, this is very frustrating"
   - APOLOGIZE: "I'm very sorry about this"
   - RESOLVE: "Let's give you a new product or full refund"
   - NOTIFY: "I'll report this to the quality team"
4. Offer compensation: "Use 10% off your next purchase 
   for what you've experienced"

RESULT: Angry customer transforms into loyal customer
```

### Scenario 3: Proactive Service

```
SITUATION: Customer has been browsing the store for a while, 
           not asking for help but looking lost.

STEPS:
1. Observe: Watch for 3-4 minutes
2. Natural approach: Make eye contact while passing by
3. Soft offer: "If you're looking for something and can't 
   find it, I can help"
4. Needs analysis: "What kind of product are you thinking about?"
5. Guide: Take to relevant section, suggest products

RESULT: Lost sale recovered, customer leaves satisfied
```


## Assessment Methods

### Mystery Shopping Form

```
┌─────────────────────────────────────────────────────────────────┐
│              MYSTERY SHOPPER EVALUATION FORM                    │
├─────────────────────────────────────────────────────────────────┤
│ Store: _________________  Date: ___/___/______                 │
│ Visit Time: _____  Evaluator: _________________                │
├─────────────────────────────────────────────────────────────────┤
│                                           Yes   No    N/A      │
│ GREETING                                                        │
│ Eye contact within 10 seconds           [ ]   [ ]    [ ]       │
│ Warm greeting given                     [ ]   [ ]    [ ]       │
│ Smile was present                       [ ]   [ ]    [ ]       │
│                                                                 │
│ SERVICE QUALITY                                                 │
│ Needs analysis performed                [ ]   [ ]    [ ]       │
│ Product knowledge adequate              [ ]   [ ]    [ ]       │
│ Fitting service professional            [ ]   [ ]    [ ]       │
│ Add-on suggestion made                  [ ]   [ ]    [ ]       │
│                                                                 │
│ CHECKOUT EXPERIENCE                                            │
│ Quick transaction                       [ ]   [ ]    [ ]       │
│ CRM registration offered                [ ]   [ ]    [ ]       │
│ Thank you given                         [ ]   [ ]    [ ]       │
│                                                                 │
│ FAREWELL                                                        │
│ Warm send-off given                     [ ]   [ ]    [ ]       │
│ Invited to return                       [ ]   [ ]    [ ]       │
│                                                                 │
│ OVERALL SCORE: _____/100                                       │
│                                                                 │
│ NOTES:                                                          │
│ ______________________________________________________________ │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### NPS Survey

```
┌─────────────────────────────────────────────────────────────────┐
│              NPS SURVEY                                         │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│ "How likely are you to recommend this store                   │
│  to a friend or family member?"                                │
│                                                                 │
│  0   1   2   3   4   5   6   7   8   9   10                    │
│  │   │   │   │   │   │   │   │   │   │   │                     │
│  ▼───▼───▼───▼───▼───▼───▼───▼───▼───▼───▼                     │
│  │      DETRACTORS     │ PASSIVES │ PROMOTERS │               │
│  │      (0-6)          │  (7-8)   │   (9-10)  │               │
│                                                                 │
│  NPS = % Promoters - % Detractors                              │
│                                                                 │
│  Target: NPS 50+                                               │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```


*This document was prepared by Aydınlı Group Franchise Operations.*  
*© 2025 Aydınlı Group - All rights reserved.*




---

## SECTION 10: CUSTOMER-INTERACTION-SCENARIOS-EN

﻿---
layout: default
title: "Customer Interaction Scenarios – EN"
parent: Training

## Training Content

### SECTION 1: GREETING SCENARIOS


#### Scenario 1.2: Customer in a Hurry

**Situation:** Customer enters quickly, checking their watch, appears to be looking for a specific item.

**✅ Correct Approach:**
```
Staff: "Welcome! Are you looking for something quickly? I can help."
Customer: "Yes, I need a white shirt, I have 15 minutes."
Staff: "Got it! What's your size? Let me bring you the options right away."
Customer: "Size M."
Staff: (Brings products quickly) "Here are 3 different models. This is slim fit, this is regular. 
Would you like to try? I can prepare the fitting room."
```

**🎯 Coaching Note:**
- Don't move slowly with customers in a hurry
- Get straight to the point, no long explanations
- Offer maximum 3 options
- Speed up the fitting room and payment process


### SECTION 2: NEEDS ASSESSMENT SCENARIOS


#### Scenario 2.2: Customer Looking for a Gift

**Situation:** Customer says "looking for a gift."

**✅ Correct Approach:**
```
Staff: "Great! Buying gifts is always nice. Who is it for?"
Customer: "For my father."
Staff: "How old is your father? What type of clothes does he usually prefer?"
Customer: "He's 55, closer to classic style."
Staff: "I see! Our Pierre Cardin collection is perfect for him. 
Would you consider a shirt or a sweater? Both are very popular this season."
Customer: "A shirt would work."
Staff: "Then please come this way. Do you know his size? 
Even if you don't, we do gift wrapping and have 30-day exchange policy."
```

**🎯 Coaching Note:**
- Ask questions about the gift recipient
- Learn age, style, usage area
- Emphasize exchange guarantee
- Suggest gift wrapping


### SECTION 3: SALES TECHNIQUE SCENARIOS


#### Scenario 3.2: Upsell

**Situation:** Customer has selected a basic t-shirt, seems to have budget.

**✅ Correct Approach:**
```
Staff: "This t-shirt is a nice choice. However, I'd like to show you our premium series."
Customer: "What's the difference?"
Staff: "This is organic cotton, softer and longer-lasting. 
It doesn't lose shape even after 10 washes. The price difference is only 150 TL 
but quality-wise it's a much higher segment."
Customer: "How much is it?"
Staff: "This is 799 TL, the other is 649 TL. But if you think of it as an investment, 
this product can be worn much longer."
```

**🎯 Coaching Note:**
- Explain upsell through value
- Say "higher quality" instead of "more expensive"
- Minimize price difference: "Only X TL difference"
- Emphasize long-term benefit


### SECTION 4: OBJECTION HANDLING SCENARIOS


#### Scenario 4.2: "It's Cheaper Elsewhere" Objection

**Situation:** Customer brings up competitor's price.

**✅ Correct Approach:**
```
Customer: "A similar shirt at X store was 500 TL."
Staff: "I understand, comparing prices makes sense. 
However, comparing product quality is also important. 
Our product is [brand], fabric quality and stitching are different. 
Also, our exchange and return policy is very flexible – hassle-free exchange within 30 days."
Customer: "But still..."
Staff: "Let me suggest this: Try this product, feel the fabric. 
If you compare it with the other product and still think that one is better, 
you can always exchange it."
```

**🎯 Coaching Note:**
- Don't badmouth competitors, praise your own product
- Explain quality difference concretely
- Provide try-and-return assurance
- Respect the customer's decision


### SECTION 5: COMPLAINT MANAGEMENT SCENARIOS


#### Scenario 5.2: Wrong Product/Size Complaint

**Situation:** Customer realized it was the wrong size when they opened it at home.

**✅ Correct Approach:**
```
Customer: "The pants I bought yesterday were supposed to be M but S came out!"
Staff: "I'm very sorry, this is our mistake. Let's fix it right away."
(Checks stock)
Staff: "Size M is available in our stock. Let's exchange it immediately. 
I'm really sorry for this inconvenience, I'd also like to give you a discount coupon."
(Makes exchange, gives 10% coupon)
Staff: "You can use this coupon on your next purchase. 
We apologize again and thank you for choosing us."
```

**🎯 Coaching Note:**
- Admit the mistake, don't make excuses
- Offer quick solution
- Make a compensatory gesture (coupon, gift)
- Guarantee customer satisfaction


### SECTION 6: FITTING ROOM SERVICE SCENARIOS


#### Scenario 6.2: Size Issue Resolution

**Situation:** Customer is in the fitting room, size didn't fit.

**✅ Correct Approach:**
```
Customer: (From fitting room) "This one is a bit tight!"
Staff: "I'll bring one size up right away. Would you also like another color?"
Customer: "Sure, if you have blue too."
Staff: (Brings within 30 seconds) "Here you go, L instead of M and the blue version."
(Hands products through the door)
Staff: "By the way, this model is regular fit. If you want something more comfortable, 
we also have a relaxed fit model, shall I bring that too?"
```

**🎯 Coaching Note:**
- Size change should happen within 1 minute
- Suggest alternative color/model
- Make fit type suggestions
- Don't keep customer waiting in the fitting room


#### Scenario 7.1: CRM Registration

**Situation:** New customer, not yet registered in the system.

**✅ Correct Approach:**
```
Staff: (During payment) "Do you have a membership with us?"
Customer: "No, I don't."
Staff: "Let's create one right away! If you give your phone number, 
you'll be informed about campaigns and special discounts. 
Also, your purchases accumulate as points."
Customer: "Sure."
Staff: "Super! Your phone number? ... Thank you! 
I've just added 100 welcome points, you can use them on your next purchase."
```

**🎯 Coaching Note:**
- Suggest CRM registration naturally
- Briefly explain benefits (points, campaigns, discounts)
- Welcome points/gift provides motivation
- Don't forget data protection consent


### SECTION 8: BRAND-SPECIFIC SCENARIOS


#### Scenario 8.2: Pierre Cardin – Business Professional

**Situation:** Professional-looking customer looking for formal wear.

**✅ Correct Approach:**
```
Staff: "Welcome! Are you looking for work?"
Customer: "Yes, I need something elegant for meetings."
Staff: "Our Pierre Cardin Business series is perfect for you. 
French elegance with modern cuts combined. This suit is slim fit, 
but also has stretch, providing all-day comfort. 
I can also suggest a shirt from the Executive series."
```


## Process / Application Steps

### Daily Scenario Practice

| Step | Application | Duration |
|------|-------------|----------|
| 1 | Select the scenario of the day | 2 min |
| 2 | Role-play (2 people) | 10 min |
| 3 | Give/receive feedback | 5 min |
| 4 | Apply with real customer | All day |
| 5 | Evening evaluation | 5 min |

### Weekly Scenario Rotation

| Week | Focus |
|------|-------|
| Week 1 | Greeting & Needs Assessment |
| Week 2 | Sales Techniques |
| Week 3 | Objection Handling |
| Week 4 | Complaint Management |
| (Repeat) | Cycle continues |


## Tools & Resources

| Resource | Usage |
|----------|-------|
| Scenario Cards | Printed card set for each scenario |
| Role-Play Videos | Correct/wrong approach videos |
| Observation Form | In-store application evaluation |
| Quiz Questions | Scenario knowledge test |
| Mobile App | Scenario practice game |


## Assessment Methods

### 1. Role-Play Evaluation
- Store manager acts out the scenario
- Staff demonstrates correct approach
- Rating on 1-5 point scale

### 2. Mystery Shopper
- Secret shopper visit
- Specific scenarios are tested
- Detailed feedback report

### 3. Video Recording Analysis
- Real customer interaction is recorded (with permission)
- Watched and evaluated together with the team

### 4. Scenario Quiz
- Written or digital test
- Correct answers selected for each scenario


## Revision History

| Date | Version | Editor | Change |
|------|---------|--------|--------|
| 01.12.2025 | 1.0 | Aydınlı Group Training HQ | Initial version created |




---
