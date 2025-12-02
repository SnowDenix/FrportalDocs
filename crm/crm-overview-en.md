---
layout: default
title: "CRM Overview"
parent: CRM
permalink: /crm/crm-overview-en/
---

# CRM Overview

> **Last Updated:** December 01, 2025 | **Version:** 1.0  
> **Prepared by:** Aydınlı Group

---

## Table of Contents

1. [Purpose](#purpose)
2. [Scope](#scope)
3. [Definitions](#definitions)
4. [Responsibilities](#responsibilities)
5. [CRM System Architecture](#crm-system-architecture)
6. [Data Flow](#data-flow)
7. [Screenshots](#screenshots)
8. [Common Issues & Solutions](#common-issues--solutions)
9. [Store Tips](#store-tips)
10. [Revision History](#revision-history)

---

## Purpose

This document defines the overall structure, objectives, and operation of the CRM (Customer Relationship Management) system for U.S. Polo Assn., Pierre Cardin, and Cacharel franchise stores under the Aydınlı Group umbrella.

### CRM Vision

- Deliver a customer-centric retail experience
- Manage customer data securely and efficiently
- Optimize sales and marketing strategies based on customer behavior
- Ensure consistent customer experience across the franchise network

### CRM Objectives

| Objective | Description |
|-----------|-------------|
| Customer Recognition | Uniquely identify each customer and track their purchase history |
| Personalization | Provide customized communications and offers based on customer preferences |
| Loyalty Enhancement | Strengthen customer loyalty through the loyalty program |
| Data Quality | Maintain clean, accurate, and up-to-date customer data |
| Compliance | Ensure full compliance with GDPR and data protection regulations |

---

## Scope

### Who Does This Document Cover?

- **Store Staff:** Sales associates performing daily CRM operations
- **Store Managers:** Managers monitoring CRM performance and guiding the team
- **Regional Managers:** Executives overseeing CRM compliance across the region
- **Franchise Owners:** Business owners tracking CRM investment returns

### Covered Processes

1. Customer registration and profile management
2. Customer matching during sales transactions
3. Loyalty program operations
4. Campaign and coupon management
5. Customer complaint/request management (Ticketing)
6. Data quality control
7. Reporting and analytics

### Covered Brands

| Brand | Segment | CRM Integration |
|-------|---------|-----------------|
| U.S. Polo Assn. | Sportswear / Casual | Full Integration |
| Pierre Cardin | Premium / Business | Full Integration |
| Cacharel | Men's Fashion | Full Integration |

---

## Definitions

### Core CRM Terms

| Term | Definition |
|------|------------|
| **CRM** | Customer Relationship Management - A system for collecting, analyzing customer data, and managing customer relationships. |
| **Customer Profile** | The complete set of demographic information, communication preferences, and purchase history belonging to a customer. |
| **Loyalty Program** | A points/coupon-based reward system designed to increase customer loyalty. |
| **Opt-in** | Customer's consent to receive marketing communications. Requires explicit consent under GDPR. |
| **Opt-out** | Customer's request to unsubscribe from marketing communications. |
| **Ticket** | A work unit where customer complaints, requests, or feedback are recorded in the system. |
| **RFM Segment** | Customer segment created based on Recency, Frequency, Monetary analysis. |
| **GDPR** | General Data Protection Regulation - European Union data protection law. |
| **Duplicate** | Multiple records belonging to the same customer. |
| **Merge** | The process of combining duplicate customer records into a single profile. |
| **POS** | Point of Sale - Sales terminal. |
| **Customer 360** | A screen presenting all customer interactions in a single view. |

### Communication Permission Types

| Permission Type | Description | Default |
|-----------------|-------------|---------|
| SMS Permission | Marketing messages via SMS | Disabled |
| Email Permission | Marketing communications via email | Disabled |
| Call Permission | Marketing calls via phone | Disabled |
| Data Processing Permission | Processing of personal data (mandatory) | Required |

---

## Responsibilities

### Store Staff

| Task | Description | Frequency |
|------|-------------|-----------|
| Customer Registration | Register new customers in the CRM system | Every sale |
| Customer Matching | Link existing customers to sales transactions | Every sale |
| Permission Collection | Obtain GDPR consents and process in the system | At registration |
| Data Update | Update customer information | On request |
| Ticket Creation | Enter customer complaints into the system | As needed |

### Store Manager

| Task | Description | Frequency |
|------|-------------|-----------|
| Performance Monitoring | Track store CRM KPIs | Daily |
| Training | Train staff on CRM usage | Continuous |
| Quality Control | Audit data quality | Weekly |
| Reporting | Present CRM reports to regional management | Monthly |
| Ticket Follow-up | Ensure resolution of open tickets | Daily |

### Regional Manager

| Task | Description | Frequency |
|------|-------------|-----------|
| Compliance Audit | Audit GDPR and CRM policy compliance | Monthly |
| Performance Analysis | Analyze region-wide CRM performance | Weekly |
| Best Practices | Promote successful CRM practices | Continuous |
| Escalation Management | Manage critical customer issues | As needed |

### CRM Headquarters Team

| Task | Description | Frequency |
|------|-------------|-----------|
| System Management | Technical management of the CRM system | Continuous |
| Campaign Management | Creation of central campaigns | Periodic |
| Data Analysis | Customer segmentation and analytics | Continuous |
| Policy Update | Update CRM policies | As needed |
| Training Support | Provide training materials to field teams | Continuous |

---

## CRM System Architecture

### System Components

```
┌─────────────────────────────────────────────────────────────────┐
│                      CRM CENTRAL SYSTEM                         │
├─────────────────────────────────────────────────────────────────┤
│  ┌───────────┐  ┌───────────┐  ┌───────────┐  ┌───────────┐    │
│  │ Customer  │  │ Campaign  │  │ Loyalty   │  │ Ticketing │    │
│  │ Database  │  │  Engine   │  │  Module   │  │  System   │    │
│  └─────┬─────┘  └─────┬─────┘  └─────┬─────┘  └─────┬─────┘    │
│        │              │              │              │           │
│        └──────────────┴──────────────┴──────────────┘           │
│                              │                                   │
│                    ┌─────────┴─────────┐                        │
│                    │   API Gateway     │                        │
│                    └─────────┬─────────┘                        │
└──────────────────────────────┼──────────────────────────────────┘
                               │
            ┌──────────────────┼──────────────────┐
            │                  │                  │
     ┌──────┴──────┐   ┌──────┴──────┐   ┌──────┴──────┐
     │   POS #1    │   │   POS #2    │   │   POS #N    │
     │   (Store)   │   │   (Store)   │   │   (Store)   │
     └─────────────┘   └─────────────┘   └─────────────┘
```

### Integration Points

| System | Integration Type | Data Flow |
|--------|------------------|-----------|
| POS System | Bidirectional | Sales → CRM, Coupon → POS |
| E-commerce | Bidirectional | Online sales → CRM |
| SMS Gateway | Unidirectional | CRM → SMS |
| Email Service | Unidirectional | CRM → Email |
| Inventory Management | Unidirectional | Stock → CRM (product info) |

---

## Data Flow

### Customer Registration Flow

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│  Customer   │────▶│   Store     │────▶│    CRM      │────▶│   Central   │
│    Info     │     │   Entry     │     │ Validation  │     │  Database   │
└─────────────┘     └─────────────┘     └─────────────┘     └─────────────┘
      │                    │                   │                    │
      ▼                    ▼                   ▼                    ▼
  Name, Surname        Phone/             Duplicate            Profile
  Phone                Email              Check                Creation
  Email                Format             GDPR                 Customer ID
  GDPR Consent         Validation         Consent              Assignment
                                          Verification
```

### Sales Transaction Flow

```
1. Start Sale
       │
       ▼
2. Customer Query ───────────────────────┐
       │                                  │
       ▼                                  ▼
3a. Existing Customer            3b. New Customer
    Found                            Registration
       │                                  │
       ▼                                  ▼
4. Customer Matching ◀───────────────────┘
       │
       ▼
5. Complete Sale
       │
       ▼
6. Points/Coupon Processing
       │
       ▼
7. Print Receipt/Invoice
```

---

## Screenshots

### Main CRM Screen

![CRM Main Screen - Placeholder](screenshots/crm-main-screen.png)

*Screenshot to be added.*

### Customer Search Screen

![Customer Search Screen - Placeholder](screenshots/crm-customer-search.png)

*Screenshot to be added.*

### Customer Profile Screen

![Customer Profile Screen - Placeholder](screenshots/crm-customer-profile.png)

*Screenshot to be added.*

---

## Common Issues & Solutions

### Issue 1: Customer Not Found

**Symptom:** A registered customer doesn't appear in search results.

**Possible Causes:**
- Phone number entered in wrong format
- Customer registered with a different number
- Record not yet synchronized

**Solution:**
1. Search phone number without leading zero (5XX XXX XXXX)
2. Ask customer for other registered numbers
3. Wait 5 minutes and try again
4. If problem persists, open IT support ticket

---

### Issue 2: Duplicate Customer Record

**Symptom:** Multiple profiles exist for the same customer.

**Possible Causes:**
- Registered with different phone numbers
- Email registration vs phone registration
- Manual entry errors

**Solution:**
1. Submit duplicate merge request to CRM Headquarters
2. Note the customer's correct information
3. Record new sales to the most recent profile

---

### Issue 3: Cannot Obtain GDPR Consent

**Symptom:** Customer refuses to give GDPR consent.

**Solution:**
1. Explain to customer that data processing is mandatory
2. Registration can only be done with data processing consent
3. Marketing permissions are optional
4. If customer refuses all permissions, proceed with anonymous sale via POS only

---

### Issue 4: Coupon Not Working

**Symptom:** Customer's coupon shows "not valid" error at POS.

**Possible Causes:**
- Coupon has expired
- Minimum cart value not met
- Coupon already used
- Product category outside coupon scope

**Solution:**
1. Check coupon details in CRM
2. Explain conditions to customer
3. Suggest alternative campaign if available

---

## Store Tips

### Daily Routines

1. **Store Opening:** Log into CRM system and check daily targets
2. **Every Sale:** Don't forget to match customers
3. **Store Closing:** Check open tickets

### Customer Registration Best Practices

- Enter phone number after confirming with customer
- Verify email address letter by letter
- Read or summarize the GDPR text to customer
- Don't force marketing permissions, but explain the benefits

### Sales-Boosting CRM Usage

- Suggest cross-sells by reviewing customer's past purchases
- Offer special deals to customers with upcoming birthdays
- Encourage additional sales by reminding loyalty points

### Data Quality Tips

- Verify customer information at every update
- Request corrections when you spot incorrect data
- Report duplicate suspicions immediately

---

## Revision History

| Version | Date | Changes | Prepared by |
|---------|------|---------|-------------|
| 1.0 | Dec 01, 2025 | Initial version created | Aydınlı Group |

---

*This document was prepared by Aydınlı Group.*  
*© 2025 Aydınlı Group - All rights reserved.*


