---
layout: default
title: "Order Management Guide – EN"
parent: Supply Chain
---

# Order Management Guide – EN

> **Last Updated:** December 01, 2025 | **Version:** 1.0  
> **Prepared by:** Aydınlı Group  
> **Brands:** U.S. Polo Assn., Pierre Cardin, Cacharel

---

## Table of Contents

1. [Purpose](#purpose)
2. [Scope](#scope)
3. [Definitions](#definitions)
4. [Responsibilities](#responsibilities)
5. [Process Steps](#process-steps)
6. [Standards & Rules](#standards--rules)
7. [Checklists](#checklists)
8. [Examples / Scenarios](#examples--scenarios)
9. [KPIs](#kpis)
10. [Common Issues & Solutions](#common-issues--solutions)
11. [Revision History](#revision-history)

---

## Purpose

This document provides comprehensive guidance on order management processes for franchise stores. Effective order management ensures optimal inventory levels, minimizes stock-outs, reduces overstock, and maintains continuous product availability for customers.

### Order Management Mission

"Ensure the right products are available at the right time through accurate and timely ordering."

### Key Objectives

| Objective | Impact |
|-----------|--------|
| **Inventory Optimization** | Balance stock levels |
| **Demand Fulfillment** | Meet customer needs |
| **Cost Control** | Minimize carrying costs |
| **Efficiency** | Streamline processes |
| **Accuracy** | Reduce order errors |

---

## Scope

### Order Types

| Order Type | Description | Timing |
|------------|-------------|--------|
| **Season Order** | Pre-season bulk order | 4-6 months ahead |
| **Replenishment Order** | Regular stock refresh | Weekly/Bi-weekly |
| **Special Order** | Customer-specific requests | As needed |
| **Transfer Order** | Inter-store movements | As needed |
| **Emergency Order** | Urgent stock needs | Same day |

### System Access

| System | Purpose | Access |
|--------|---------|--------|
| **B2B Portal** | Order submission | All stores |
| **ERP System** | Inventory tracking | Manager level |
| **WMS** | Warehouse status | View only |
| **Tracking Portal** | Shipment tracking | All stores |

---

## Definitions

| Term (EN) | Term (TR) | Definition |
|-----------|-----------|------------|
| PO | Satınalma Siparişi | Purchase Order |
| SKU | Stok Kodu | Stock Keeping Unit |
| MOQ | Minimum Sipariş | Minimum Order Quantity |
| Lead Time | Tedarik Süresi | Time from order to delivery |
| Reorder Point | Yeniden Sipariş Noktası | Level triggering reorder |
| Safety Stock | Güvenlik Stoğu | Buffer inventory |
| Open-to-Buy | Satın Alma Bütçesi | Budget for purchasing |
| Allocation | Tahsis | Stock distribution |
| Back Order | Bekleyen Sipariş | Unfulfilled order |
| Fill Rate | Doldurma Oranı | Order completion percentage |

---

## Responsibilities

### Store Staff

| Responsibility | Standard |
|----------------|----------|
| Monitor stock levels | Daily |
| Report low stock items | Immediately |
| Prepare order suggestions | Weekly |
| Verify received orders | Same day |
| Update inventory system | Real-time |

### Store Manager

| Responsibility | Standard |
|----------------|----------|
| Approve order submissions | Before deadline |
| Manage order budget | Within allocation |
| Review order history | Weekly |
| Coordinate with regional | As needed |
| Ensure order accuracy | Per submission |

### Regional Manager

| Responsibility | Standard |
|----------------|----------|
| Oversee regional orders | Weekly review |
| Balance regional inventory | Monthly |
| Approve special orders | Within 48 hours |
| Coordinate transfers | As needed |
| Monitor regional performance | Monthly |

### HQ Supply Chain

| Responsibility | Standard |
|----------------|----------|
| Process orders | 24-hour turnaround |
| Manage allocations | Per policy |
| Coordinate with vendors | Ongoing |
| System maintenance | Continuous |
| Performance reporting | Monthly |

---

## Process Steps

### Regular Replenishment Order Process

```
┌────────────────────────────────────────────────────────────────┐
│              REPLENISHMENT ORDER PROCESS                       │
├────────────────────────────────────────────────────────────────┤
│                                                                │
│   STEP 1: INVENTORY REVIEW                                     │
│   ┌─────────────────────────────────────────────────────────┐  │
│   │ • Run inventory report                                  │  │
│   │ • Identify items below reorder point                    │  │
│   │ • Review sales velocity                                 │  │
│   │ • Check upcoming promotions                             │  │
│   │ • Consider seasonal factors                             │  │
│   └─────────────────────────────────────────────────────────┘  │
│                                                                │
│   STEP 2: ORDER PREPARATION                                    │
│   ┌─────────────────────────────────────────────────────────┐  │
│   │ • Calculate required quantities                         │  │
│   │ • Review size ratios                                    │  │
│   │ • Check minimum order quantities                        │  │
│   │ • Consider lead times                                   │  │
│   │ • Verify budget availability                            │  │
│   └─────────────────────────────────────────────────────────┘  │
│                                                                │
│   STEP 3: ORDER ENTRY                                          │
│   ┌─────────────────────────────────────────────────────────┐  │
│   │ • Log into B2B portal                                   │  │
│   │ • Select items and quantities                           │  │
│   │ • Verify delivery address                               │  │
│   │ • Add special instructions if needed                    │  │
│   │ • Review order summary                                  │  │
│   └─────────────────────────────────────────────────────────┘  │
│                                                                │
│   STEP 4: ORDER SUBMISSION                                     │
│   ┌─────────────────────────────────────────────────────────┐  │
│   │ • Submit order                                          │  │
│   │ • Receive confirmation number                           │  │
│   │ • Save confirmation email                               │  │
│   │ • Note expected delivery date                           │  │
│   └─────────────────────────────────────────────────────────┘  │
│                                                                │
│   STEP 5: ORDER TRACKING                                       │
│   ┌─────────────────────────────────────────────────────────┐  │
│   │ • Monitor order status                                  │  │
│   │ • Track shipment progress                               │  │
│   │ • Prepare for delivery                                  │  │
│   │ • Report any delays                                     │  │
│   └─────────────────────────────────────────────────────────┘  │
│                                                                │
└────────────────────────────────────────────────────────────────┘
```

### Order Calculation Method

```
REORDER QUANTITY CALCULATION

Step 1: Calculate Average Daily Sales
Average Daily Sales = Total Sales (30 days) ÷ 30

Step 2: Calculate Lead Time Demand
Lead Time Demand = Average Daily Sales × Lead Time (days)

Step 3: Calculate Safety Stock
Safety Stock = Average Daily Sales × Safety Days

Step 4: Calculate Reorder Point
Reorder Point = Lead Time Demand + Safety Stock

Step 5: Calculate Order Quantity
Order Quantity = (Target Stock Level) - (Current Stock) + (Expected Sales during Lead Time)

EXAMPLE:
Average Daily Sales: 5 units
Lead Time: 7 days
Safety Days: 3 days
Current Stock: 20 units
Target Stock Level: 50 units

Lead Time Demand = 5 × 7 = 35 units
Safety Stock = 5 × 3 = 15 units
Reorder Point = 35 + 15 = 50 units
Order Quantity = 50 - 20 + 35 = 65 units
```

---

## Standards & Rules

### Order Submission Standards

| Standard | Requirement |
|----------|-------------|
| **Order Deadline** | Tuesday 18:00 for weekly orders |
| **Minimum Order** | Per brand/category MOQ |
| **Order Frequency** | Weekly (standard) |
| **System Access** | Authorized users only |
| **Documentation** | All orders documented |

### Order Accuracy Requirements

| Metric | Target |
|--------|--------|
| Item Selection | 100% correct SKUs |
| Quantity Accuracy | Within 5% of need |
| Size Ratio | Per brand guidelines |
| Address Accuracy | 100% correct |
| Special Instructions | Complete and clear |

### Budget Management

| Rule | Description |
|------|-------------|
| **Open-to-Buy Limit** | Do not exceed allocation |
| **Approval Required** | For orders exceeding budget |
| **Priority Items** | Focus on fast movers |
| **Seasonal Adjustment** | Adjust for peak periods |
| **Clearance Balance** | Include markdown items |

---

## Checklists

### Pre-Order Checklist

```
PRE-ORDER REVIEW CHECKLIST
Date: _____________ Store: _____________

INVENTORY ANALYSIS
□ Current stock levels reviewed
□ Low stock items identified
□ Overstock items identified
□ Sales velocity analyzed
□ Sell-through rates calculated

DEMAND FACTORS
□ Upcoming promotions noted
□ Seasonal considerations reviewed
□ Local events identified
□ Weather factors considered
□ Historical data analyzed

BUDGET REVIEW
□ Open-to-buy checked
□ Remaining budget verified
□ Priority items identified
□ Approval requirements noted

SYSTEM PREPARATION
□ B2B portal access verified
□ Login credentials ready
□ Order template updated
□ Delivery address confirmed

Manager Approval: _____________
Date: _____________
```

### Order Submission Checklist

```
ORDER SUBMISSION CHECKLIST
Date: _____________ Order #: _____________

ORDER ENTRY
□ All items added to order
□ Quantities verified
□ Size ratios correct
□ MOQ requirements met
□ Delivery address confirmed
□ Special instructions added

ORDER REVIEW
□ Total quantity checked
□ Total value reviewed
□ Budget compliance verified
□ Lead time acceptable
□ Expected delivery date noted

SUBMISSION
□ Order submitted successfully
□ Confirmation number received
□ Confirmation saved/printed
□ Calendar reminder set
□ Team notified

ORDER DETAILS
Order Number: _____________
Total Units: _____________
Total Value: _____________
Expected Delivery: _____________
Submitted By: _____________
```

---

## Examples / Scenarios

### Scenario 1: Regular Weekly Order

**Situation:** Tuesday weekly order submission

**Process:**
```
1. Monday: Run inventory report
2. Monday: Analyze sales velocity
3. Monday: Identify reorder needs
4. Monday: Prepare order list
5. Tuesday AM: Manager review and approval
6. Tuesday PM: Submit order before 18:00
7. Tuesday: Save confirmation
8. Wednesday: Verify order confirmation received
```

### Scenario 2: Emergency Stock Request

**Situation:** Key item unexpectedly sold out

**Process:**
```
1. Verify actual stock (physical count)
2. Check regional inventory (other stores)
3. If available: Request store transfer
4. If not: Contact Regional Manager
5. Submit emergency order request
6. Provide justification (sales data)
7. Track approval status
8. Coordinate expedited delivery
```

### Scenario 3: Season Order Planning

**Situation:** Pre-season bulk order

**Process:**
```
1. Review previous season performance
2. Analyze sell-through rates by category
3. Identify best-selling styles/colors
4. Review HQ recommendations
5. Consider local market preferences
6. Calculate size ratios
7. Prepare order within budget
8. Submit by deadline
9. Review HQ allocation
10. Request adjustments if needed
```

---

## KPIs

### Order Management Metrics

| KPI | Formula | Target | Frequency |
|-----|---------|--------|-----------|
| **Order Accuracy** | Correct orders / Total orders | ≥98% | Weekly |
| **Order Timeliness** | On-time submissions / Total | 100% | Weekly |
| **Fill Rate** | Units received / Units ordered | ≥95% | Monthly |
| **Stock-out Rate** | Out of stock days / Total days | <2% | Weekly |
| **Inventory Turnover** | COGS / Average Inventory | 4-6x/year | Quarterly |

### Performance Dashboard

```
┌─────────────────────────────────────────────────────────────┐
│               ORDER MANAGEMENT PERFORMANCE                  │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  Order Accuracy        [████████████████████░░] 98%        │
│  Target: ≥98%          ✓ MEETING                            │
│                                                             │
│  Order Timeliness      [████████████████████████] 100%     │
│  Target: 100%          ✓ MEETING                            │
│                                                             │
│  Fill Rate             [██████████████████░░░░] 94%        │
│  Target: ≥95%          ⚠ BELOW TARGET                       │
│                                                             │
│  Stock-out Rate        [█░░░░░░░░░░░░░░░░░░░░░] 1.5%       │
│  Target: <2%           ✓ WITHIN TARGET                      │
│                                                             │
│  This Week's Orders:                                        │
│  - Regular replenishment: 3 orders                         │
│  - Emergency requests: 1 order                             │
│  - Store transfers: 2 orders                               │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## Common Issues & Solutions

### Issue 1: Missed Order Deadline

**Problem:** Order not submitted by deadline

**Solutions:**
- Set calendar reminders
- Prepare orders in advance
- Delegate backup authority
- Contact HQ immediately if missed
- Request deadline extension (once only)

---

### Issue 2: Order Exceeds Budget

**Problem:** Required order exceeds open-to-buy

**Solutions:**
- Prioritize fast-moving items
- Request budget increase with justification
- Consider store transfers
- Delay non-essential items
- Review allocation with Regional Manager

---

### Issue 3: System Access Issues

**Problem:** Cannot access B2B portal

**Solutions:**
- Check internet connection
- Clear browser cache
- Try different browser
- Reset password if needed
- Contact IT support immediately
- Have backup user submit order

---

### Issue 4: Low Fill Rate

**Problem:** Receiving less than ordered

**Solutions:**
- Review order accuracy
- Check item availability before ordering
- Contact HQ for back-order status
- Request priority allocation
- Consider alternative items

---

## B2B Portal Guide

### Login Process

```
B2B PORTAL ACCESS

1. Navigate to: portal.aydinli.com
2. Enter username (store email)
3. Enter password
4. Complete two-factor authentication
5. Access order dashboard

NAVIGATION
- Dashboard → Order summary
- New Order → Create replenishment order
- Order History → View past orders
- Tracking → Track shipments
- Reports → Download inventory reports
- Support → Contact help desk
```

### Order Entry Steps

```
CREATING A NEW ORDER

1. Click "New Order"
2. Select brand (USPA/PC/Cacharel)
3. Choose category (Men/Women/Kids/Accessories)
4. Browse or search items
5. Enter quantities per size
6. Add to cart
7. Repeat for all items
8. Review cart
9. Verify delivery address
10. Add special instructions
11. Submit order
12. Save confirmation
```

---

## Revision History

| Version | Date | Change | Prepared By |
|---------|------|--------|-------------|
| 1.0 | 2025-12-01 | Initial version created | Aydınlı Group Supply Chain |

---

*This document was prepared by Aydınlı Group.*  
*© 2025 Aydınlı Group - All rights reserved.*


