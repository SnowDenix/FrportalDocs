---
layout: default
title: "CRM Ticketing and Customer Complaint Management"
---

# CRM Ticketing and Customer Complaint Management

> **Last Updated:** December 01, 2025 | **Version:** 1.0  
> **Prepared by:** Aydınlı Grup

---

## Table of Contents

1. [Purpose](#purpose)
2. [Scope](#scope)
3. [Definitions](#definitions)
4. [Responsibilities](#responsibilities)
5. [Process Steps](#process-steps)
6. [SLA Times](#sla-times)
7. [Screenshots](#screenshots)
8. [KPIs](#kpis)
9. [Common Issues & Solutions](#common-issues--solutions)
10. [Store Tips](#store-tips)
11. [Revision History](#revision-history)

---

## Purpose

This document defines the processes for managing customer complaints, requests, and feedback through the CRM Ticketing system at Aydınlı Grup franchise stores (U.S. Polo Assn., Pierre Cardin, Cacharel).

### Ticketing System Objectives

- Resolve customer issues quickly and effectively
- Record all customer interactions
- Standardize complaint resolution processes
- Increase customer satisfaction
- Analyze recurring issues to eliminate root causes

---

## Scope

### Who Does This Document Cover?

| Role | Responsibility |
|------|----------------|
| Store Staff | Ticket creation and first response |
| Store Manager | Ticket follow-up and escalation |
| Regional Manager | Critical ticket management |
| CRM Headquarters | Central resolution and closure approval |
| Quality Team | Product quality-related tickets |

### Covered Processes

1. Ticket creation
2. Ticket categorization
3. Ticket assignment and routing
4. Evidence/document attachment
5. Ticket update
6. Ticket resolution
7. Ticket closure
8. Customer notification

---

## Definitions

### Core Ticketing Terms

| Term | Definition |
|------|------------|
| **Ticket** | A work unit where customer complaints, requests, or feedback are recorded in the system |
| **Ticket ID** | Unique tracking number assigned to each ticket |
| **SLA** | Service Level Agreement - Maximum time set for resolution |
| **Escalation** | Elevation of ticket to a higher authority level |
| **First Contact Resolution (FCR)** | Percentage of tickets resolved on first contact |
| **Ticket Owner** | Person responsible for ticket resolution |
| **Ticket Status** | Current state of the ticket (Open, In Progress, On Hold, Resolved, Closed) |
| **Root Cause** | Underlying cause of the issue |
| **Resolution** | Applied solution |

### Ticket Statuses

| Status | Description | Color Code |
|--------|-------------|------------|
| **Open** | Newly created, processing not started | 🔴 Red |
| **In Progress** | Being worked on | 🟡 Yellow |
| **On Hold** | Waiting for customer/supplier response | 🟠 Orange |
| **Resolved** | Solution applied, awaiting customer approval | 🔵 Blue |
| **Closed** | Process completed | 🟢 Green |
| **Cancelled** | Invalid or duplicate ticket | ⚫ Gray |

---

## Responsibilities

### Store Staff

| Task | Detail |
|------|--------|
| Ticket creation | Enter customer complaint into system |
| Information gathering | Collect all details about the issue |
| Evidence attachment | Upload photos, receipts, etc. |
| First response | Resolve issues that can be handled at store level |
| Customer notification | Keep customer updated about the process |

### Store Manager

| Task | Detail |
|------|--------|
| Ticket approval | Verify opened tickets |
| Prioritization | Rank tickets by importance |
| Escalation | Forward unresolved tickets to higher level |
| Performance tracking | Monitor store ticket KPIs |
| Closure approval | Close resolved tickets |

### CRM Headquarters Team

| Task | Detail |
|------|--------|
| Central resolution | Resolve tickets that cannot be solved at store level |
| Coordination | Communicate with relevant departments |
| SLA tracking | Ensure all tickets stay within SLA |
| Trend analysis | Report recurring issues |
| Policy update | Improve processes |

---

## Process Steps

### 1. Ticket Creation

#### Step 1: Verify Customer Information

**Action:** Search for customer in CRM and open their profile

**Checklist:**
- [ ] Is customer registered in system?
- [ ] Is contact information up to date?
- [ ] Was purchase history reviewed?

#### Step 2: Open Ticket

**Action:** Click "New Ticket" button

**Fields to Complete:**

| Field | Description | Required |
|-------|-------------|----------|
| Customer | Auto-selected | ✓ |
| Category | Main complaint category | ✓ |
| Sub-Category | Detailed category | ✓ |
| Priority | Critical/High/Normal/Low | ✓ |
| Subject | Brief title | ✓ |
| Description | Detailed issue description | ✓ |
| Related Sale | Sales transaction if applicable | - |
| Related Product | Product SKU if applicable | - |

#### Step 3: Category Selection

**Main Categories:**

| Category | Sub-Categories | Example |
|----------|----------------|---------|
| **Product Quality** | Stitching defect, Fabric issue, Color bleeding, Size mismatch | Shirt stitching came undone |
| **Product Exchange** | Size exchange, Model exchange, Color exchange | Wants L size instead of M |
| **Return Request** | Product return, Refund | Wants to return product |
| **Missing/Wrong Delivery** | Missing item, Wrong item, Damaged package | 1 of 2 items missing from order |
| **Price/Campaign** | Wrong pricing, Campaign issue, Coupon issue | Discount not applied |
| **Store Service** | Staff behavior, Wait time, Cleanliness | Long queue complaint |
| **Loyalty/Points** | Points issue, Card issue, Membership | Points not reflected |
| **Other** | General feedback, Suggestion, Thank you | Product suggestion |

#### Step 4: Priority Setting

| Priority | Criteria | SLA |
|----------|----------|-----|
| **Critical** | Health/safety risk, media threat, VIP customer | 4 hours |
| **High** | Financial loss, recurring issue, social media complaint | 24 hours |
| **Normal** | Standard complaint, exchange/return request | 48 hours |
| **Low** | Suggestion, general feedback, information request | 72 hours |

#### Step 5: Evidence Attachment

**Uploadable Documents:**
- Product photo (showing damage/defect)
- Sales receipt/invoice copy
- Customer ID document (if required)
- Video recording (maximum 30 seconds)
- Email/SMS correspondence

**Photo Taking Rules:**
1. Take in well-lit environment
2. Show problematic area in close-up
3. Capture label and barcode visibly
4. Add minimum 3 photos from different angles

---

### 2. Ticket Processing Flow

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   Ticket    │────▶│   Store     │────▶│    CRM      │────▶│  Relevant   │
│   Created   │     │   Review    │     │    HQ       │     │  Department │
└─────────────┘     └─────────────┘     └─────────────┘     └─────────────┘
       │                   │                   │                   │
       ▼                   ▼                   ▼                   ▼
    Open              Resolved at         Escalation         Department
    Status            Store?              to HQ              Response
                         │                   │                   │
                    Yes / No           Assign/Route           Solution
                         │                   │                   │
                         ▼                   ▼                   ▼
                  ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
                  │  Resolved   │     │ In Progress │     │  Resolved   │
                  │   Status    │     │   Status    │     │   Status    │
                  └─────────────┘     └─────────────┘     └─────────────┘
                         │                                       │
                         └───────────────────────────────────────┘
                                           │
                                           ▼
                                   ┌─────────────┐
                                   │  Customer   │
                                   │  Approval   │
                                   └─────────────┘
                                           │
                                           ▼
                                   ┌─────────────┐
                                   │   Ticket    │
                                   │   Closed    │
                                   └─────────────┘
```

---

### 3. Escalation Matrix

| Level | Authority | Time Exceeded | Action |
|-------|-----------|---------------|--------|
| Level 1 | Store Staff | - | First response |
| Level 2 | Store Manager | 24 hours | In-store resolution |
| Level 3 | Regional Manager | 48 hours | Regional coordination |
| Level 4 | CRM Headquarters | 72 hours | Central intervention |
| Level 5 | Senior Management | 96 hours | Management decision |

**Automatic Escalation Rules:**
- Warning email sent when SLA reaches 80%
- Automatic escalation to higher level when SLA exceeded
- Critical tickets start directly from Level 3

---

### 4. Ticket Update

**Record at each update:**
- Action taken
- Communication details (who, when, how)
- Next step
- Estimated resolution time

**Update Format:**
```
[Date - Time] [User]
Action: [Description of action taken]
Result: [Outcome of action]
Next Step: [Planned action]
```

---

### 5. Ticket Closure

#### Pre-Closure Checklist

- [ ] Was customer issue resolved?
- [ ] Was customer notified?
- [ ] Did customer approve the resolution?
- [ ] Were all documents attached?
- [ ] Was root cause identified?
- [ ] Were resolution notes written?

#### Closure Categories

| Category | Description |
|----------|-------------|
| Resolved - Customer Satisfied | Issue fixed, customer satisfied |
| Resolved - Partial Satisfaction | Issue fixed, customer partially satisfied |
| Unresolved - Customer Accepted | No solution found, customer accepted situation |
| Unresolved - Customer Dissatisfied | No solution found, customer not satisfied |
| Cancelled - Duplicate | Another ticket exists for same issue |
| Cancelled - Invalid | Ticket subject invalid or incorrectly opened |

---

## SLA Times

### Category-Based SLA

| Category | Priority | First Response | Resolution |
|----------|----------|----------------|------------|
| Product Quality | Normal | 4 hours | 48 hours |
| Product Exchange | Normal | 2 hours | 24 hours |
| Return Request | Normal | 2 hours | 48 hours |
| Price/Campaign | High | 1 hour | 24 hours |
| Store Service | Normal | 4 hours | 48 hours |
| Loyalty/Points | Normal | 2 hours | 24 hours |

### VIP Customer SLA

All SLA times are reduced by 50% for VIP customers.

| Normal SLA | VIP SLA |
|------------|---------|
| 48 hours | 24 hours |
| 24 hours | 12 hours |
| 4 hours | 2 hours |

---

## Screenshots

### Ticket List

![Ticket List - Placeholder](screenshots/crm-ticket-list.png)

*Screenshot to be added.*

### New Ticket Form

![New Ticket - Placeholder](screenshots/crm-ticket-new.png)

*Screenshot to be added.*

### Ticket Detail

![Ticket Detail - Placeholder](screenshots/crm-ticket-detail.png)

*Screenshot to be added.*

---

## KPIs

### Ticket Performance KPIs

| KPI | Definition | Formula | Target |
|-----|------------|---------|--------|
| **First Contact Resolution (FCR)** | Percentage of tickets resolved on first contact | (Resolved on First Contact / Total Tickets) × 100 | >60% |
| **SLA Compliance** | Percentage of tickets closed within SLA | (Closed Within SLA / Total Closed) × 100 | >95% |
| **Average Resolution Time** | Average time to resolution | Total Resolution Time / Closed Tickets | <36 hours |
| **Customer Satisfaction (CSAT)** | Customer satisfaction score | Satisfied Customers / Survey Responses × 100 | >85% |
| **Reopened Ticket Rate** | Percentage of reopened tickets | (Reopened / Total Closed) × 100 | <5% |
| **Ticket per Transaction** | Ticket rate per transaction | Total Tickets / Total Sales × 1000 | <2‰ |

### Calculation Examples

**FCR Calculation:**
```
Tickets resolved on first contact: 150
Total tickets: 250
FCR = (150 / 250) × 100 = 60%
```

**SLA Compliance Calculation:**
```
Closed within SLA: 190
Total closed: 200
SLA Compliance = (190 / 200) × 100 = 95%
```

---

## Common Issues & Solutions

### Issue 1: Ticket Category Unclear

**Situation:** Customer complaint fits multiple categories.

**Solution:**
1. Identify the main issue (what customer complains about most)
2. Open ticket under that category
3. Note other issues in description field
4. Create related ticket if necessary

---

### Issue 2: Customer Cannot Provide Evidence

**Situation:** Customer lost receipt or didn't bring product.

**Solution:**
1. Check sales history in CRM
2. Request bank statement based on payment method
3. Check store security camera footage
4. Record situation in ticket notes
5. Proceed with store manager approval

---

### Issue 3: Customer Being Aggressive

**Situation:** Customer is yelling, threatening.

**Solution:**
1. Stay calm, don't take it personally
2. Listen to customer, don't interrupt
3. Show empathy: "I understand..."
4. Offer concrete solution
5. Call store manager
6. Open ticket with "Critical" priority
7. Document situation in detail

---

### Issue 4: SLA About to Expire

**Situation:** Ticket not resolved, SLA expiring.

**Solution:**
1. Escalate immediately
2. Notify customer: "Your issue has been escalated to management"
3. Write delay reason in ticket notes
4. State estimated new timeline
5. Raise priority level

---

## Store Tips

### Effective Ticket Opening

1. **Write in detail:** Instead of "Customer unhappy", write "Customer reported that blue polo shirt purchased on 15.11.2025 had stitching come undone after 3rd wash"
2. **Select correct category:** Wrong category routes to wrong team
3. **Add evidence:** Ticket without photo delays resolution
4. **Note customer expectation:** "Customer wants refund" or "Customer will accept exchange"

### Customer Communication

1. **First response is critical:** Give customer immediate feedback
2. **Share tracking number:** "Your ticket number is 12345, you can track with this number"
3. **Give timeline:** "We will respond within 24 hours"
4. **Be proactive:** Give updates without customer asking

### Solution-Oriented Approach

| Customer Expectation | Recommended Approach |
|---------------------|----------------------|
| Just wants to be heard | Show empathy, apologize |
| Wants product exchange | Check stock, offer alternatives |
| Wants refund | Offer solution within policy |
| Wants compensation | Direct to store manager approval |

### Do's

- ✅ Take every complaint seriously
- ✅ Give customer a response timeline
- ✅ Respond within promised time
- ✅ Follow up on resolution
- ✅ Ask for satisfaction after closure

### Don'ts

- ❌ Don't argue with customer
- ❌ Don't blame other departments
- ❌ Don't make unrealistic promises
- ❌ Don't leave ticket unanswered
- ❌ Don't close ticket with incomplete information

---

## Revision History

| Version | Date | Changes | Prepared by |
|---------|------|---------|-------------|
| 1.0 | Dec 01, 2025 | Initial version created | Aydınlı Grup |

---

*This document was prepared by Aydınlı Grup.*  
*© 2025 Aydınlı Group - All rights reserved.*


