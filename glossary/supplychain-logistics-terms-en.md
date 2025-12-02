---
layout: default
title: "Supply Chain and Logistics Terms Glossary"
parent: Glossary
permalink: /glossary/supplychain-logistics-terms-en/
---

# Supply Chain and Logistics Terms Glossary

> **Last Updated:** December 01, 2025 | **Version:** 1.0  
> **Prepared by:** Aydınlı Grup

---

## Table of Contents

1. [Incoterms (International Commercial Terms)](#incoterms-international-commercial-terms)
2. [Shipping and Delivery Terms](#shipping-and-delivery-terms)
3. [SAP and ERP Terms](#sap-and-erp-terms)
4. [Warehouse and Inventory Management Terms](#warehouse-and-inventory-management-terms)
5. [Customs and Import Terms](#customs-and-import-terms)
6. [Documentation Terms](#documentation-terms)

---

## Incoterms (International Commercial Terms)

> **Note:** Incoterms 2020 rules are established by the International Chamber of Commerce (ICC).

### EXW (Ex Works)

**Definition:** The seller makes goods available at their premises; buyer bears all transportation and insurance costs.

**Responsibility Allocation:**
- **Seller:** Packages goods and delivers at factory
- **Buyer:** Loading, transportation, insurance, customs, all costs

**Use Case:** Frequently used in Aydınlı Group domestic shipments.

**Example:** EXW delivery from Istanbul production facility to franchise

---

### FOB (Free On Board)

**Definition:** The seller loads goods onto the vessel at the named port of shipment; risk and cost transfer to buyer at that point.

**Responsibility Allocation:**
- **Seller:** Clears goods for export and loads onto vessel
- **Buyer:** Ocean freight, insurance, import customs, destination costs

**Use Case:** International shipments via sea transportation

**Example:** FOB Istanbul Port - franchise shipment

---

### CIF (Cost, Insurance, Freight)

**Definition:** The seller covers all costs including freight and insurance to the destination port.

**Responsibility Allocation:**
- **Seller:** Goods cost + insurance + freight (to destination port)
- **Buyer:** All costs after destination port, import customs

**Example:** CIF Port - franchise shipment

---

### CPT (Carriage Paid To)

**Definition:** The seller pays freight to named destination, but risk transfers when goods are handed to first carrier.

**Responsibility Allocation:**
- **Seller:** Freight to destination, export customs
- **Buyer:** Insurance (optional), import customs, destination costs

**Use Case:** Road transportation or multimodal transport

**Example:** CPT - franchise shipment

---

### CIP (Carriage and Insurance Paid To)

**Definition:** CPT + insurance. Seller bears transportation and insurance costs.

**Responsibility Allocation:**
- **Seller:** Transportation + insurance to destination
- **Buyer:** Import customs, destination costs

---

### DAP (Delivered At Place)

**Definition:** Seller delivers goods ready for unloading at the named place of destination.

**Responsibility Allocation:**
- **Seller:** All transportation costs and risks to destination
- **Buyer:** Unloading, import customs

---

### DDP (Delivered Duty Paid)

**Definition:** Seller bears all costs including import duties; delivery to buyer's door.

**Responsibility Allocation:**
- **Seller:** All costs and risks (including import duties)
- **Buyer:** Only unloading

**Use Case:** Turnkey franchise store openings

**Example:** DDP Store - franchise store opening shipment

---

### FCA (Free Carrier)

**Definition:** Seller delivers goods to the carrier at the named place.

**Responsibility Allocation:**
- **Seller:** Export customs, delivery to carrier
- **Buyer:** Main carriage, insurance, import

---

## Shipping and Delivery Terms

### Lead Time

**Definition:** Total time from order placement to product receipt.

**Components:**
- Production Lead Time
- Transportation Lead Time
- Customs Clearance Time

**Example:** Total lead time: 15-20 days

---

### Initial Shipment

**Definition:** The first shipment of a product to a store. Applied for new seasons or new store openings.

---

### RPT Shipment (Repeat Shipment)

**Definition:** Re-shipment of a previously shipped product to the same store.

---

### Consolidation

**Definition:** Combining multiple small shipments into one larger shipment.

**Benefits:**
- Freight cost savings
- Fewer customs procedures
- Efficient capacity utilization

---

### Cross-Docking

**Definition:** Products transferred directly from incoming vehicles to outgoing vehicles without warehouse storage.

**Use Case:** Fast-moving products, RPT shipments

---

### Drop Shipping

**Definition:** Products shipped directly from supplier to customer without passing through seller's warehouse.

---

### Bill of Lading (B/L)

**Definition:** Document in sea transport that confirms goods are loaded onto vessel and serves as title document.

**Types:**
- **Original B/L:** Original, negotiable
- **Telex Release:** Electronic release confirmation
- **Sea Waybill:** Non-negotiable sea transport document

---

### AWB (Air Waybill)

**Definition:** Transport document used in air freight.

---

### CMR (Road Consignment Note)

**Definition:** Transport document used in international road transportation.

---

## SAP and ERP Terms

### Purchase Order (PO)

**Definition:** Official purchasing order issued to supplier.

**SAP Transaction Code:** ME21N (Create), ME22N (Change), ME23N (Display)

**Contains:**
- Product code and description
- Quantity and unit price
- Delivery date and location
- Payment terms

---

### Sales Order (SO)

**Definition:** Sales order received from customer.

**SAP Transaction Code:** VA01 (Create), VA02 (Change), VA03 (Display)

---

### Delivery Note

**Definition:** Document sent with shipment listing products in the consignment.

**SAP Transaction Code:** VL01N (Create), VL02N (Change)

---

### Invoice

**Definition:** Financial document for the sales transaction.

**Types:**
- **Proforma Invoice:** Preliminary invoice for customs
- **Commercial Invoice:** Commercial invoice for payment
- **Tax Invoice:** Tax document

**SAP Transaction Code:** VF01 (Create), VF02 (Change)

---

### Goods Receipt (GR)

**Definition:** System recording of product entry to warehouse or store.

**SAP Transaction Code:** MIGO

---

### Goods Issue (GI)

**Definition:** System recording of product exit from warehouse or store.

**SAP Transaction Code:** MIGO

---

### Stock Transfer Order (STO)

**Definition:** Order for stock transfer between warehouses or stores.

---

### Material Master

**Definition:** Master data record in SAP containing all product information.

**Contains:**
- Basic data (description, unit)
- Sales data
- Purchasing data
- Warehouse data
- Accounting data

---

### Vendor Master

**Definition:** Master data record containing supplier information.

---

### Customer Master

**Definition:** Master data record containing customer (franchise dealer) information.

---

## Warehouse and Inventory Management Terms

### WMS (Warehouse Management System)

**Definition:** Warehouse management system. Manages product receipt/dispatch, location, picking operations.

---

### FIFO (First In, First Out)

**Definition:** First items received are first to be dispatched.

**Use Case:** Seasonal products, products with shelf life

---

### LIFO (Last In, First Out)

**Definition:** Last items received are first to be dispatched.

---

### Pick & Pack

**Definition:** Collecting products from warehouse according to order and packaging for shipment.

---

### Bin Location

**Definition:** Physical location address where products are stored in warehouse.

**Format:** Warehouse-Aisle-Rack-Level-Position (e.g., A-01-03-2-05)

---

### Cycle Counting

**Definition:** Regular periodic counts for continuous inventory verification.

---

### Safety Stock

**Definition:** Minimum inventory level maintained against demand fluctuations or supply delays.

**Formula:**
```
Safety Stock = (Max Daily Sales × Max Lead Time) - (Avg Daily Sales × Avg Lead Time)
```

---

### Reorder Point

**Definition:** Inventory level at which a new order should be placed.

**Formula:**
```
Reorder Point = (Avg Daily Sales × Lead Time) + Safety Stock
```

---

### EOQ (Economic Order Quantity)

**Definition:** Optimal order quantity that minimizes total inventory cost.

---

## Customs and Import Terms

### HS Code (Harmonized System Code)

**Definition:** International standard product classification code. Used for customs duty determination.

**Example:** 6105.10 - Men's/boys' knitted cotton shirts

---

### Customs Duty

**Definition:** Tax levied on the value of imported goods.

---

### VAT (Value Added Tax)

**Definition:** Value added tax. Calculated on goods value + customs duty at import.

---

### Certificate of Origin

**Definition:** Document certifying the country where goods were manufactured. Required for preferential tariff application.

---

### Letter of Credit (L/C)

**Definition:** Bank-guaranteed payment method. Provides secure payment in international trade.

**Types:**
- Sight L/C (Payment on presentation)
- Deferred L/C (Term payment)
- Confirmed L/C (Bank confirmed)

---

### Bill of Entry (Customs Declaration)

**Definition:** Official declaration submitted to customs for import or export operations.

---

### Bonded Warehouse

**Definition:** Customs-controlled warehouse where goods are temporarily stored without paying customs duties.

---

## Documentation Terms

### Packing List

**Definition:** Detailed list of products in the shipment.

**Contains:**
- Carton numbers
- Contents of each carton
- Gross and net weights
- Dimensions

---

### Commercial Invoice

**Definition:** Invoice used in international trade showing goods value.

---

### Proforma Invoice

**Definition:** Preliminary invoice used for order confirmation and customs procedures.

---

### Insurance Certificate

**Definition:** Document certifying that transported goods are insured.

---

### Phytosanitary Certificate

**Definition:** Certificate proving plant and plant products have passed health inspection.

---

## Incoterms Summary Table

| Term | Risk Transfer | Cost Coverage | Transport Mode |
|------|---------------|---------------|----------------|
| EXW | Seller's premises | Goods only | All |
| FCA | Delivery to carrier | Incl. export customs | All |
| FOB | Ship's rail | Incl. export + loading | Sea |
| CFR | Ship's rail | Incl. freight | Sea |
| CIF | Ship's rail | Incl. freight + insurance | Sea |
| CPT | First carrier | Incl. transportation | All |
| CIP | First carrier | Incl. transport + insurance | All |
| DAP | Destination | All excl. unloading | All |
| DDP | Destination | All (incl. duties) | All |

---

## Revision History

| Version | Date | Change | Prepared By |
|---------|------|--------|-------------|
| 1.0 | 2025-12-01 | Initial version created | Aydınlı Grup |

---

*This document was prepared by Aydınlı Grup.*  
*© 2025 Aydınlı Group - All rights reserved.*


