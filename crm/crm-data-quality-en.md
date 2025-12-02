# CRM Data Quality Management

> **Last Updated:** December 01, 2025 | **Version:** 1.0  
> **Prepared by:** Aydınlı Grup

---

## Table of Contents

1. [Purpose](#purpose)
2. [Scope](#scope)
3. [Definitions](#definitions)
4. [Responsibilities](#responsibilities)
5. [Data Quality Principles](#data-quality-principles)
6. [Data Validation Rules](#data-validation-rules)
7. [Common Data Errors](#common-data-errors)
8. [Correction Processes](#correction-processes)
9. [Duplicate Management](#duplicate-management)
10. [Screenshots](#screenshots)
11. [KPIs](#kpis)
12. [Common Issues & Solutions](#common-issues--solutions)
13. [Store Tips](#store-tips)
14. [Revision History](#revision-history)

---

## Purpose

This document defines the standards and processes required to ensure and maintain the quality of customer data in the CRM system at Aydınlı Grup franchise stores (U.S. Polo Assn., Pierre Cardin, Cacharel).

### Importance of Data Quality

- **Customer experience:** Accurate data means personalized service
- **Marketing effectiveness:** Quality data means targeted campaigns
- **Operational efficiency:** Clean data means faster processing
- **Cost savings:** Incorrect data creates extra costs
- **Legal compliance:** GDPR requires accurate and up-to-date data

---

## Scope

### Who Does This Document Cover?

| Role | Responsibility |
|------|----------------|
| Store Staff | Enter data correctly |
| Store Manager | Monitor data quality |
| Regional Manager | Track regional data quality |
| CRM Headquarters | Data cleansing and standardization |
| IT Team | System validation rules |

### Covered Data

| Data Field | Criticality | Validation Level |
|------------|-------------|------------------|
| Mobile Phone | High | Automatic + Manual |
| Email | High | Automatic |
| First/Last Name | High | Manual |
| Date of Birth | Medium | Automatic |
| Address | Low | Manual |
| Gender | Low | Manual |

---

## Definitions

### Data Quality Terms

| Term | Definition |
|------|------------|
| **Data Quality** | The state of data being accurate, complete, consistent, and current |
| **Duplicate** | Multiple records belonging to the same customer |
| **Merge** | Combining duplicate records |
| **Data Cleansing** | Correcting/cleaning erroneous data |
| **Validation** | Format/content verification during data entry |
| **Standardization** | Converting data to a single format |
| **Enrichment** | Enhancing existing data |
| **Decay** | Data becoming outdated/invalid over time |

### Data Quality Dimensions

| Dimension | Description | Example |
|-----------|-------------|---------|
| **Accuracy** | Data reflects reality | Does phone number really belong to customer? |
| **Completeness** | All required fields filled | Is email field empty? |
| **Consistency** | Same data consistent across systems | Same name in POS and CRM? |
| **Timeliness** | Data is current | Is address still valid? |
| **Uniqueness** | Each customer has single record | Are there duplicates? |
| **Validity** | Data conforms to rules | Is phone 10 digits? |

---

## Responsibilities

### Store Staff

| Task | Detail | Frequency |
|------|--------|-----------|
| Correct entry | Enter customer information correctly | Every transaction |
| Verification | Confirm entered data with customer | Every transaction |
| Update | Update changed information | On request |
| Reporting | Report incorrect data | Upon detection |

### Store Manager

| Task | Detail | Frequency |
|------|--------|-----------|
| Audit | Check data entries | Weekly |
| Training | Train staff on data quality | Continuous |
| Correction | Correct detected errors | Immediately |
| Reporting | Monitor data quality KPIs | Monthly |

### CRM Headquarters

| Task | Detail | Frequency |
|------|--------|-----------|
| Bulk cleansing | Systematic data cleaning | Monthly |
| Duplicate management | Merge duplicate records | Continuous |
| Rule update | Update validation rules | As needed |
| Analysis | Analyze data quality trends | Monthly |

---

## Data Quality Principles

### Core Principles

1. **Right First Time:** Getting data right at first entry is easier than correcting later
2. **Source Verification:** Enter data after confirming with customer
3. **Standardization:** Follow defined formats
4. **Minimum Data:** Only collect necessary data
5. **Regular Update:** Verify information at every customer contact

### Golden Record Rule

Each customer should have a single "Golden Record" (master record) in the system:

```
┌─────────────────────────────────────────────────────────────────┐
│                     GOLDEN RECORD                                │
├─────────────────────────────────────────────────────────────────┤
│  Customer ID: 1000045678                                        │
│  Name: JOHN SMITH                                               │
│  Phone: 532 123 4567                                            │
│  Email: john.smith@email.com                                    │
│  ─────────────────────────────────────────────────────────────  │
│  All sales, points, coupons should be linked to this record    │
│  Duplicate records should be merged with this record            │
└─────────────────────────────────────────────────────────────────┘
```

---

## Data Validation Rules

### Phone Number

| Rule | Valid | Invalid |
|------|-------|---------|
| Format | 5XX XXX XXXX | 0532 123 4567 |
| Length | 10 digits | 9 or 11 digits |
| Start | Must start with 5 | Must not start with 0 |
| Uniqueness | Must be unique | Must not be in another customer |

**System Validation:**
```
✓ 5321234567 → Valid
✗ 05321234567 → Invalid (11 digits)
✗ 4321234567 → Invalid (doesn't start with 5)
✗ 532123456 → Invalid (9 digits)
```

### Email Address

| Rule | Valid | Invalid |
|------|-------|---------|
| Format | user@domain.com | user@domain |
| @ symbol | Required | Cannot be missing |
| Domain | Valid domain | test, asdf |
| Uniqueness | Must be unique | Must not be in another customer |

**Common Email Errors:**

| Error | Example | Possible Correct |
|-------|---------|------------------|
| Special characters | john.smïth@email.com | john.smith@email.com |
| Space | john smith@email.com | john.smith@email.com |
| Missing domain | john@gmail | john@gmail.com |
| Wrong domain | john@gmial.com | john@gmail.com |

### First/Last Name

| Rule | Correct | Wrong |
|------|---------|-------|
| Capitalization | John Smith | john smith |
| Full name | John | J. |
| No special chars | John Smith | John Smith!!! |
| No numbers | John Smith | John123 |

**Standard Format:**
- First name: First letter uppercase, rest lowercase
- Last name: First letter uppercase, rest lowercase
- Multiple names: Each word's first letter uppercase

### Date of Birth

| Rule | Valid | Invalid |
|------|-------|---------|
| Format | DD/MM/YYYY | YYYY-MM-DD |
| Age | Between 16-100 | 5 years or 120 years |
| Future date | Not allowed | Future date |
| Logical | Realistic | 01/01/1900 |

---

## Common Data Errors

### Error Categories

| Category | Description | Impact |
|----------|-------------|--------|
| Format Error | Data in wrong format | System rejection |
| Typo | Typing error, missing character | Communication failure |
| Missing Data | Required field empty | Incomplete profile |
| Duplicate | Multiple records | Split data |
| Outdated | Old information | Unreachable |
| Fake Data | Made-up information | Unusable data |

### Most Frequently Encountered Errors

| Error | Example | Cause |
|-------|---------|-------|
| Wrong phone | 532 123 456 (9 digits) | Rushed entry |
| Email typo | john@gmial.com | Lack of attention |
| Fake email | aaa@aaa.com | Customer didn't want to provide |
| Wrong birth date | 01/01/2000 (for everyone) | Information not collected |
| Abbreviation instead of full name | J. Smith | Rush |
| Duplicate record | Same customer with 2 phones | Check not performed |

### Error Impacts

| Error | Business Impact |
|-------|-----------------|
| Wrong phone | SMS doesn't arrive, customer unreachable |
| Wrong email | Campaign emails don't arrive |
| Duplicate | Points split, customer disadvantaged |
| Missing data | Personalization not possible |
| Fake data | Marketing budget wasted |

---

## Correction Processes

### 1. Store Level Correction

**If customer requests:**

**Step 1:** Verify customer identity

**Step 2:** Find customer in CRM

**Step 3:** Click "Edit" button

**Step 4:** Correct the erroneous field

**Step 5:** Save the change

**Step 6:** Inform the customer

### 2. Bulk Correction (CRM Headquarters)

Bulk correction can be done for certain patterns:

| Pattern | Correction |
|---------|------------|
| 05XXXXXXXXX | Remove leading 0 |
| email@gmial.com | Correct to @gmail.com |
| JOHN SMITH | Format to John Smith |

### 3. Correction Request Process

**If store cannot correct:**

**Step 1:** Open ticket (Category: Data Correction)

**Step 2:** Specify customer information
- Customer ID
- Incorrect field
- Correct value
- Evidence (if available)

**Step 3:** CRM Headquarters reviews and corrects

**Step 4:** Correction information sent to store

---

## Duplicate Management

### Causes of Duplicates

| Cause | Description |
|-------|-------------|
| Different phone | Customer gave different number |
| Different email | Records made with different emails |
| Spelling difference | "John" vs "Jon" |
| New record | New record opened without searching existing |
| Different store | Registered at different stores |

### Duplicate Detection

**Symptoms:**
- Customer says "Where are my points?" but balance is zero
- Multiple records appear with same name
- Different profile opens when customer gives different number

**Detection Screen:**
```
┌─────────────────────────────────────────────────────────────────┐
│  POSSIBLE DUPLICATE DETECTION                                   │
├─────────────────────────────────────────────────────────────────┤
│  Record 1                   │  Record 2                         │
│  ─────────────────────────  │  ─────────────────────────────── │
│  ID: 1000045678             │  ID: 1000098765                   │
│  Name: John Smith           │  Name: John Smyth                 │
│  Phone: 532 123 4567        │  Phone: 533 987 6543              │
│  Email: john@email.com      │  Email: john@email.com            │
│  Points: 2,500              │  Points: 1,000                    │
│  ─────────────────────────────────────────────────────────────  │
│  Email is same → High probability same customer                 │
└─────────────────────────────────────────────────────────────────┘
```

### Merge Process

**Step 1:** Detect duplicate

**Step 2:** Compare both records

**Step 3:** Submit merge request to CRM Headquarters:
- Both Customer IDs
- Which record will be "Golden Record"
- Correct information obtained from customer

**Step 4:** CRM Headquarters performs merge:
- Points are combined
- Sales history is combined
- Coupons are transferred
- Second record is deactivated

**Step 5:** Customer is informed

### Merge Rules

| Rule | Description |
|------|-------------|
| Oldest record becomes master | Has more history |
| Points are summed | No loss |
| Most current info used | Phone, address, etc. |
| Sales history preserved | All transactions visible |

---

## Screenshots

### Data Quality Dashboard

![Data Quality Dashboard - Placeholder](screenshots/crm-data-quality-dashboard.png)

*Screenshot to be added.*

### Duplicate Management

![Duplicate Management - Placeholder](screenshots/crm-duplicate-management.png)

*Screenshot to be added.*

---

## KPIs

### Data Quality KPIs

| KPI | Definition | Formula | Target |
|-----|------------|---------|--------|
| **Data Completeness** | Profile completion rate | (Filled Fields / Total Fields) × 100 | >80% |
| **Phone Validity** | Valid phone rate | (Valid Phones / Total Records) × 100 | >95% |
| **Email Validity** | Valid email rate | (Valid Emails / Emails Entered) × 100 | >90% |
| **Duplicate Rate** | Duplicate record rate | (Duplicate Records / Total Records) × 100 | <2% |
| **Bounce Rate** | Unreachable communication rate | (Bounces / Sent) × 100 | <5% |
| **Data Decay Rate** | Data obsolescence rate | (Outdated / Total) × 100 | <10% |

### Calculation Examples

**Data Completeness:**
```
Total required fields: 6 (First Name, Last Name, Phone, Email, Gender, DOB)
Average filled fields: 5
Completeness = (5 / 6) × 100 = 83%
```

**Duplicate Rate:**
```
Detected duplicates: 150
Total customers: 10,000
Duplicate Rate = (150 / 10,000) × 100 = 1.5%
```

---

## Common Issues & Solutions

### Issue 1: Customer Changed Phone Number

**Situation:** Registered with old number, searching with new number.

**Solution:**
1. Find record with old number
2. Verify customer identity
3. Update phone number
4. Give customer confirmation

---

### Issue 2: Email Bouncing

**Situation:** Sent emails are bouncing back.

**Solution:**
1. Check email address
2. Check common typos (gmial, hotnail, etc.)
3. Get correct email from customer
4. Update in CRM

---

### Issue 3: Suspected Duplicate Record

**Situation:** Same customer coming with different numbers.

**Solution:**
1. Compare both records
2. Get confirmation from customer
3. Open merge request to CRM Headquarters
4. Inform customer about the process

---

### Issue 4: Fake Data Entry

**Situation:** Fake information like aaa@aaa.com.

**Solution:**
1. Detect such records
2. Get correct information from customer if possible
3. If not possible, leave field empty
4. Never accept fake data

---

## Store Tips

### For Correct Data Entry

| Do | Don't |
|----|-------|
| ✅ Confirm phone from customer | ❌ Don't guess |
| ✅ Verify email letter by letter | ❌ Don't rush |
| ✅ Search existing customer before registration | ❌ Don't directly create new record |
| ✅ Leave empty instead of fake info | ❌ Don't accept aaa@aaa.com |
| ✅ Report suspected duplicates | ❌ Don't ignore |

### Data Quality Checklist

**At Every Customer Registration:**
- [ ] Is phone 10 digits and starts with 5?
- [ ] Does email contain @ and .?
- [ ] Is first/last name in correct format?
- [ ] Is customer not already registered?
- [ ] Were GDPR consents obtained?

### Customer Approach

**To get correct information:**
> "We'll have a special surprise for you on your birthday, so it's important for me to get your date of birth correctly."

> "I need to record your email address correctly so we can inform you about campaigns. Can you spell it out?"

**If they don't want to provide:**
> "Of course, that's entirely your choice. I'll leave that field empty."

---

## Revision History

| Version | Date | Changes | Prepared by |
|---------|------|---------|-------------|
| 1.0 | Dec 01, 2025 | Initial version created | Aydınlı Grup |

---

*This document was prepared by Aydınlı Grup.*  
*© 2025 Aydınlı Group - All rights reserved.*

