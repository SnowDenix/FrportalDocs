---
layout: default
title: "Aydınlı Grup Franchise Retail Documentation"
---

# Aydınlı Grup Franchise Retail Documentation

> **Retail Terms, Guidelines & KPI Formulas for Global Franchise Operations**  
> **Version:** 2.0 | **Last Updated:** December 2025

---

## Language Selector / Dil Seçici

<div id="language-selector" style="margin: 20px 0; padding: 15px; background-color: #f5f5f5; border-radius: 5px; text-align: center;">
  <button onclick="showLanguage('all')" id="btn-all" style="margin: 5px; padding: 10px 20px; background-color: #0366d6; color: white; border: none; border-radius: 3px; cursor: pointer;">All / Tümü</button>
  <button onclick="showLanguage('en')" id="btn-en" style="margin: 5px; padding: 10px 20px; background-color: #e1e4e8; color: #24292e; border: none; border-radius: 3px; cursor: pointer;">English</button>
  <button onclick="showLanguage('tr')" id="btn-tr" style="margin: 5px; padding: 10px 20px; background-color: #e1e4e8; color: #24292e; border: none; border-radius: 3px; cursor: pointer;">Türkçe</button>
</div>

<script>
function showLanguage(lang) {
  // Update button styles
  document.getElementById('btn-all').style.backgroundColor = lang === 'all' ? '#0366d6' : '#e1e4e8';
  document.getElementById('btn-all').style.color = lang === 'all' ? 'white' : '#24292e';
  document.getElementById('btn-en').style.backgroundColor = lang === 'en' ? '#0366d6' : '#e1e4e8';
  document.getElementById('btn-en').style.color = lang === 'en' ? 'white' : '#24292e';
  document.getElementById('btn-tr').style.backgroundColor = lang === 'tr' ? '#0366d6' : '#e1e4e8';
  document.getElementById('btn-tr').style.color = lang === 'tr' ? 'white' : '#24292e';
  
  // Show/hide content sections
  const enSections = document.querySelectorAll('.lang-en');
  const trSections = document.querySelectorAll('.lang-tr');
  
  if (lang === 'all') {
    enSections.forEach(el => el.style.display = '');
    trSections.forEach(el => el.style.display = '');
  } else if (lang === 'en') {
    enSections.forEach(el => el.style.display = '');
    trSections.forEach(el => el.style.display = 'none');
  } else if (lang === 'tr') {
    enSections.forEach(el => el.style.display = 'none');
    trSections.forEach(el => el.style.display = '');
  }
  
  // Save preference
  localStorage.setItem('preferredLanguage', lang);
}

// Load saved preference on page load
window.addEventListener('DOMContentLoaded', function() {
  const savedLang = localStorage.getItem('preferredLanguage') || 'all';
  showLanguage(savedLang);
});
</script>

---

<div class="lang-en">

## Overview

This repository contains comprehensive retail documentation for Aydınlı Group's international franchise partners operating **U.S. Polo Assn.**, **Pierre Cardin**, and **Cacharel** brands.

All documents are provided in **bilingual format (Turkish/English)** to support global operations.

---

## Quick Navigation

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin: 30px 0;">

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>📚 Glossary</h3>
<p>Retail terms, finance formulas, and logistics terminology</p>
<a href="#glossary-section">View Documents →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>📋 Guidelines</h3>
<p>Core operational guidelines and protocols</p>
<a href="#guidelines-section">View Documents →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>💼 CRM</h3>
<p>Customer relationship management documentation</p>
<a href="#crm-section">View Documents →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>💙 Marketing</h3>
<p>Marketing operations and brand guidelines</p>
<a href="#marketing-section">View Documents →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>🟦 Visual Merchandising</h3>
<p>VM standards and display guidelines</p>
<a href="#vm-section">View Documents →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>🟩 Store Operations</h3>
<p>Daily store operations and procedures</p>
<a href="#store-operations-section">View Documents →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>🟧 Supply Chain</h3>
<p>Logistics and procurement procedures</p>
<a href="#supply-chain-section">View Documents →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>🎓 Training</h3>
<p>Training materials and guides</p>
<a href="#training-section">View Documents →</a>
</div>

</div>

---

## Complete Document Index

### <span id="glossary-section">📚 Glossary (Sözlükler)</span> - 6 Files

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **Retail Terms** | Inventory, sales, VM, POS terms | [View](glossary/retail-terms-en.md) | [Görüntüle](glossary/retail-terms-tr.md) |
| **Finance KPI Formulas** | EBIT, GMROI, Markup, Margin formulas | [View](glossary/finance-kpi-formulas-en.md) | [Görüntüle](glossary/finance-kpi-formulas-tr.md) |
| **Supply Chain & Logistics Terms** | Incoterms, SAP, logistics terms | [View](glossary/supplychain-logistics-terms-en.md) | [Görüntüle](glossary/supplychain-logistics-terms-tr.md) |

---

### <span id="guidelines-section">📋 Guidelines (Rehberler)</span> - 6 Files

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **VM Guidelines** | Window, fixture, brand standards | [View](guidelines/vm-guideline-en.md) | [Görüntüle](guidelines/vm-guideline-tr.md) |
| **Store Operations Guidelines** | Opening/closing, returns, damage procedures | [View](guidelines/store-operations-guideline-en.md) | [Görüntüle](guidelines/store-operations-guideline-tr.md) |
| **Franchise Communication Protocol** | Reporting, escalation, regional standards | [View](guidelines/franchise-communication-protocol-en.md) | [Görüntüle](guidelines/franchise-communication-protocol-tr.md) |

---

### <span id="crm-section">💼 CRM Module</span> - 20 Files

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **CRM Overview** | CRM operations overview | [View](crm/crm-overview-en.md) | [Görüntüle](crm/crm-overview-tr.md) |
| **Store User Guide** | CRM system user guide for stores | [View](crm/crm-store-user-guide-en.md) | [Görüntüle](crm/crm-store-user-guide-tr.md) |
| **Dashboard KPIs** | CRM dashboard key performance indicators | [View](crm/crm-dashboard-kpi-en.md) | [Görüntüle](crm/crm-dashboard-kpi-tr.md) |
| **Customer Segmentation** | Customer segmentation strategies | [View](crm/crm-customer-segmentation-en.md) | [Görüntüle](crm/crm-customer-segmentation-tr.md) |
| **Loyalty Campaigns** | Loyalty program and campaign management | [View](crm/crm-loyalty-campaigns-en.md) | [Görüntüle](crm/crm-loyalty-campaigns-tr.md) |
| **Ticketing Process** | Customer service ticketing procedures | [View](crm/crm-ticketing-process-en.md) | [Görüntüle](crm/crm-ticketing-process-tr.md) |
| **Data Quality** | CRM data quality standards | [View](crm/crm-data-quality-en.md) | [Görüntüle](crm/crm-data-quality-tr.md) |
| **Customer Data Policy** | Customer data privacy and policy | [View](crm/crm-customer-data-policy-en.md) | [Görüntüle](crm/crm-customer-data-policy-tr.md) |
| **Do's and Don'ts** | CRM best practices and common mistakes | [View](crm/crm-do-and-dont-en.md) | [Görüntüle](crm/crm-do-and-dont-tr.md) |
| **Store CRM Checklist** | Store-level CRM compliance checklist | [View](crm/crm-store-crm-checklist-en.md) | [Görüntüle](crm/crm-store-crm-checklist-tr.md) |

---

### <span id="marketing-section">💙 Marketing Module</span> - 18 Files

#### Overview & Strategy

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **Marketing Overview** | Marketing operations overview | [View](marketing/marketing-overview-en.md) | [Görüntüle](marketing/marketing-overview-tr.md) |
| **Brand Guidelines** | Brand identity and usage guidelines | [View](marketing/brand-guideline-en.md) | [Görüntüle](marketing/brand-guideline-tr.md) |

#### Campaigns & Calendar

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **Seasonal Marketing Calendar** | Annual marketing calendar | [View](marketing/seasonal-marketing-calendar-en.md) | [Görüntüle](marketing/seasonal-marketing-calendar-tr.md) |
| **Campaign Execution Guide** | Campaign implementation procedures | [View](marketing/campaign-execution-guide-en.md) | [Görüntüle](marketing/campaign-execution-guide-tr.md) |

#### Digital & Social

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **Digital Assets Usage** | Digital assets management guide | [View](marketing/digital-assets-usage-en.md) | [Görüntüle](marketing/digital-assets-usage-tr.md) |
| **Social Media Localization** | Social media localization standards | [View](marketing/social-media-localization-guide-en.md) | [Görüntüle](marketing/social-media-localization-guide-tr.md) |

#### In-Store Marketing

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **POSM Guidelines** | POS materials guidelines | [View](marketing/posm-guideline-en.md) | [Görüntüle](marketing/posm-guideline-tr.md) |
| **In-Store Communication** | In-store communication standards | [View](marketing/in-store-communication-guide-en.md) | [Görüntüle](marketing/in-store-communication-guide-tr.md) |

#### Approval Process

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **Marketing Approval Process** | Marketing approval workflow | [View](marketing/marketing-approval-process-en.md) | [Görüntüle](marketing/marketing-approval-process-tr.md) |

---

### <span id="vm-section">🟦 Visual Merchandising Module</span> - 12 Files

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **VM Overview** | VM operations overview | [View](vm/vm-overview-en.md) | [Görüntüle](vm/vm-overview-tr.md) |
| **VM General Guidelines** | General visual merchandising standards | [View](vm/vm-guideline-general-en.md) | [Görüntüle](vm/vm-guideline-general-tr.md) |
| **Window Display Guidelines** | Window display standards | [View](vm/window-display-guideline-en.md) | [Görüntüle](vm/window-display-guideline-tr.md) |
| **In-Store Layout Guidelines** | Store layout principles | [View](vm/in-store-layout-guideline-en.md) | [Görüntüle](vm/in-store-layout-guideline-tr.md) |
| **Mannequin Styling Guidelines** | Mannequin styling standards | [View](vm/mannequin-styling-guideline-en.md) | [Görüntüle](vm/mannequin-styling-guideline-tr.md) |
| **Seasonal VM Changeover** | Seasonal VM transition guide | [View](vm/seasonal-vm-changeover-en.md) | [Görüntüle](vm/seasonal-vm-changeover-tr.md) |

---

### <span id="store-operations-section">🟩 Store Operations Module</span> - 16 Files

#### Overview & Daily Operations

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **Store Operations Overview** | Store operations overview | [View](store-operations/store-operations-overview-en.md) | [Görüntüle](store-operations/store-operations-overview-tr.md) |
| **Opening/Closing Procedures** | Store opening/closing procedures | [View](store-operations/opening-closing-procedures-en.md) | [Görüntüle](store-operations/opening-closing-procedures-tr.md) |

#### Cash & Customer Service

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **Cash Management Guide** | Cash handling procedures | [View](store-operations/cash-management-guide-en.md) | [Görüntüle](store-operations/cash-management-guide-tr.md) |
| **Customer Service Standards** | Customer service excellence | [View](store-operations/customer-service-standards-en.md) | [Görüntüle](store-operations/customer-service-standards-tr.md) |

#### Returns & Inventory

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **Return & Exchange Procedures** | Return and exchange policies | [View](store-operations/return-exchange-procedures-en.md) | [Görüntüle](store-operations/return-exchange-procedures-tr.md) |
| **Inventory Control Guide** | Inventory management procedures | [View](store-operations/inventory-control-guide-en.md) | [Görüntüle](store-operations/inventory-control-guide-tr.md) |

#### Loss Prevention & Safety

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **Loss Prevention Guide** | Loss prevention procedures | [View](store-operations/loss-prevention-guide-en.md) | [Görüntüle](store-operations/loss-prevention-guide-tr.md) |

---

### <span id="supply-chain-section">🟧 Supply Chain & Logistics Module</span> - 12 Files

#### Overview & Orders

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **Supply Chain Overview** | Supply chain operations overview | [View](supply-chain/supply-chain-overview-en.md) | [Görüntüle](supply-chain/supply-chain-overview-tr.md) |
| **Order Management Guide** | Order management procedures | [View](supply-chain/order-management-guide-en.md) | [Görüntüle](supply-chain/order-management-guide-tr.md) |

#### Delivery & Receiving

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **Delivery & Receiving Procedures** | Delivery receiving standards | [View](supply-chain/delivery-receiving-procedures-en.md) | [Görüntüle](supply-chain/delivery-receiving-procedures-tr.md) |
| **Stock Transfer Procedures** | Stock transfer processes | [View](supply-chain/stock-transfer-procedures-en.md) | [Görüntüle](supply-chain/stock-transfer-procedures-tr.md) |

#### Warehouse & Shipping

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **Warehouse Coordination Guide** | Warehouse coordination procedures | [View](supply-chain/warehouse-coordination-guide-en.md) | [Görüntüle](supply-chain/warehouse-coordination-guide-tr.md) |
| **Shipping & Logistics Guide** | Shipping and logistics guide | [View](supply-chain/shipping-logistics-guide-en.md) | [Görüntüle](supply-chain/shipping-logistics-guide-tr.md) |

---

### <span id="training-section">🎓 Training Module</span> - 24 Files

| Document | Description | English | Turkish |
|----------|-------------|---------|---------|
| **Training Overview** | Training program overview | [View](training/training-overview-en.md) | [Görüntüle](training/training-overview-tr.md) |
| **Onboarding Guide** | New employee onboarding procedures | [View](training/onboarding-guide-en.md) | [Görüntüle](training/onboarding-guide-tr.md) |
| **Product Knowledge Basics** | Fundamental product knowledge | [View](training/product-knowledge-basics-en.md) | [Görüntüle](training/product-knowledge-basics-tr.md) |
| **Sales Techniques** | Sales techniques and best practices | [View](training/sales-techniques-en.md) | [Görüntüle](training/sales-techniques-tr.md) |
| **Customer Experience Standards** | Customer experience excellence standards | [View](training/customer-experience-standards-en.md) | [Görüntüle](training/customer-experience-standards-tr.md) |
| **Customer Interaction Scenarios** | Common customer interaction scenarios | [View](training/customer-interaction-scenarios-en.md) | [Görüntüle](training/customer-interaction-scenarios-tr.md) |
| **Competency Framework** | Employee competency framework | [View](training/competency-framework-en.md) | [Görüntüle](training/competency-framework-tr.md) |
| **Seasonal Training Pack** | Seasonal training materials | [View](training/seasonal-training-pack-en.md) | [Görüntüle](training/seasonal-training-pack-tr.md) |
| **Training Assessment** | Training evaluation and assessment | [View](training/training-assessment-en.md) | [Görüntüle](training/training-assessment-tr.md) |
| **Brand Supplement - USPA** | U.S. Polo Assn. brand training | [View](training/brand-supplement-uspa-en.md) | [Görüntüle](training/brand-supplement-uspa-tr.md) |
| **Brand Supplement - Pierre Cardin** | Pierre Cardin brand training | [View](training/brand-supplement-pierre-cardin-en.md) | [Görüntüle](training/brand-supplement-pierre-cardin-tr.md) |
| **Brand Supplement - Cacharel** | Cacharel brand training | [View](training/brand-supplement-cacharel-en.md) | [Görüntüle](training/brand-supplement-cacharel-tr.md) |

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

## How to Use

### For Store Managers
1. Start with [Store Operations Overview](store-operations/store-operations-overview-en.md)
2. Reference [Opening/Closing Procedures](store-operations/opening-closing-procedures-en.md) for daily routines
3. Follow [VM Overview](vm/vm-overview-en.md) for display standards
4. Review [Customer Service Standards](store-operations/customer-service-standards-en.md) for service excellence

### For Operations Teams
1. Review [Supply Chain Overview](supply-chain/supply-chain-overview-en.md) for logistics
2. Use [Finance KPI Formulas](glossary/finance-kpi-formulas-en.md) for performance metrics
3. Follow [Inventory Control Guide](store-operations/inventory-control-guide-en.md) for stock management

### For Marketing Teams
1. Start with [Marketing Overview](marketing/marketing-overview-en.md)
2. Follow [Brand Guidelines](marketing/brand-guideline-en.md) for brand consistency
3. Review [Campaign Execution Guide](marketing/campaign-execution-guide-en.md) for campaigns
4. Use [Seasonal Marketing Calendar](marketing/seasonal-marketing-calendar-en.md) for planning

### For Franchise Owners
1. Understand all KPIs in [Finance Formulas](glossary/finance-kpi-formulas-en.md)
2. Review [Communication Protocol](guidelines/franchise-communication-protocol-en.md)
3. Ensure teams follow all operational guidelines
4. Monitor performance with documented KPIs

---

## Contact

**Aydınlı Grup Franchise Operations**

- Email: franchise@aydinli-franchise.com
- Support: support@aydinli-franchise.com

---

## License

© 2025 Aydınlı Grup - All rights reserved.

This documentation is proprietary and confidential. Distribution is limited to authorized Aydınlı Group franchise partners only.

---

*Prepared by Aydınlı Grup Franchise Operations Team*

</div>

<div class="lang-tr">

## Genel Bakış

Bu depo, **U.S. Polo Assn.**, **Pierre Cardin** ve **Cacharel** markalarını işleten Aydınlı Grup'un uluslararası franchise ortakları için kapsamlı perakende dokümantasyonunu içermektedir.

Tüm belgeler küresel operasyonları desteklemek için **iki dilli format (Türkçe/İngilizce)** olarak sağlanmaktadır.

---

## Hızlı Navigasyon

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin: 30px 0;">

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>📚 Sözlük</h3>
<p>Perakende terimleri, finans formülleri ve lojistik terminolojisi</p>
<a href="#glossary-section-tr">Belgeleri Görüntüle →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>📋 Rehberler</h3>
<p>Temel operasyonel rehberler ve protokoller</p>
<a href="#guidelines-section-tr">Belgeleri Görüntüle →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>💼 CRM</h3>
<p>Müşteri ilişkileri yönetimi dokümantasyonu</p>
<a href="#crm-section-tr">Belgeleri Görüntüle →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>💙 Pazarlama</h3>
<p>Pazarlama operasyonları ve marka rehberleri</p>
<a href="#marketing-section-tr">Belgeleri Görüntüle →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>🟦 Görsel Mağazacılık</h3>
<p>VM standartları ve vitrin rehberleri</p>
<a href="#vm-section-tr">Belgeleri Görüntüle →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>🟩 Mağaza Operasyonları</h3>
<p>Günlük mağaza operasyonları ve prosedürler</p>
<a href="#store-operations-section-tr">Belgeleri Görüntüle →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>🟧 Tedarik Zinciri</h3>
<p>Lojistik ve tedarik prosedürleri</p>
<a href="#supply-chain-section-tr">Belgeleri Görüntüle →</a>
</div>

<div style="border: 1px solid #e1e4e8; border-radius: 5px; padding: 20px;">
<h3>🎓 Eğitim</h3>
<p>Eğitim materyalleri ve rehberler</p>
<a href="#training-section-tr">Belgeleri Görüntüle →</a>
</div>

</div>

---

## Tam Belge İndeksi

### <span id="glossary-section-tr">📚 Sözlük</span> - 6 Dosya

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **Perakende Terimleri** | Stok yönetimi, satış, VM, POS terimleri | [View](glossary/retail-terms-en.md) | [Görüntüle](glossary/retail-terms-tr.md) |
| **Finans KPI Formülleri** | EBIT, GMROI, Markup, Margin formülleri | [View](glossary/finance-kpi-formulas-en.md) | [Görüntüle](glossary/finance-kpi-formulas-tr.md) |
| **Tedarik Zinciri & Lojistik Terimleri** | Incoterms, SAP, lojistik terimleri | [View](glossary/supplychain-logistics-terms-en.md) | [Görüntüle](glossary/supplychain-logistics-terms-tr.md) |

---

### <span id="guidelines-section-tr">📋 Rehberler</span> - 6 Dosya

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **VM Rehberi** | Vitrin, fixture, marka standartları | [View](guidelines/vm-guideline-en.md) | [Görüntüle](guidelines/vm-guideline-tr.md) |
| **Mağaza Operasyonları Rehberi** | Açılış/kapanış, iade, hasar prosedürleri | [View](guidelines/store-operations-guideline-en.md) | [Görüntüle](guidelines/store-operations-guideline-tr.md) |
| **Franchise İletişim Protokolü** | Raporlama, escalation, bölge standartları | [View](guidelines/franchise-communication-protocol-en.md) | [Görüntüle](guidelines/franchise-communication-protocol-tr.md) |

---

### <span id="crm-section-tr">💼 CRM Modülü</span> - 20 Dosya

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **CRM Genel Bakış** | CRM operasyonları genel bakış | [View](crm/crm-overview-en.md) | [Görüntüle](crm/crm-overview-tr.md) |
| **Mağaza Kullanıcı Rehberi** | Mağazalar için CRM sistem kullanıcı rehberi | [View](crm/crm-store-user-guide-en.md) | [Görüntüle](crm/crm-store-user-guide-tr.md) |
| **Dashboard KPI'ları** | CRM dashboard temel performans göstergeleri | [View](crm/crm-dashboard-kpi-en.md) | [Görüntüle](crm/crm-dashboard-kpi-tr.md) |
| **Müşteri Segmentasyonu** | Müşteri segmentasyon stratejileri | [View](crm/crm-customer-segmentation-en.md) | [Görüntüle](crm/crm-customer-segmentation-tr.md) |
| **Sadakat Kampanyaları** | Sadakat programı ve kampanya yönetimi | [View](crm/crm-loyalty-campaigns-en.md) | [Görüntüle](crm/crm-loyalty-campaigns-tr.md) |
| **Biletleme Süreci** | Müşteri hizmetleri biletleme prosedürleri | [View](crm/crm-ticketing-process-en.md) | [Görüntüle](crm/crm-ticketing-process-tr.md) |
| **Veri Kalitesi** | CRM veri kalitesi standartları | [View](crm/crm-data-quality-en.md) | [Görüntüle](crm/crm-data-quality-tr.md) |
| **Müşteri Veri Politikası** | Müşteri veri gizliliği ve politikası | [View](crm/crm-customer-data-policy-en.md) | [Görüntüle](crm/crm-customer-data-policy-tr.md) |
| **Yapılacaklar ve Yapılmayacaklar** | CRM en iyi uygulamaları ve yaygın hatalar | [View](crm/crm-do-and-dont-en.md) | [Görüntüle](crm/crm-do-and-dont-tr.md) |
| **Mağaza CRM Kontrol Listesi** | Mağaza seviyesi CRM uyumluluk kontrol listesi | [View](crm/crm-store-crm-checklist-en.md) | [Görüntüle](crm/crm-store-crm-checklist-tr.md) |

---

### <span id="marketing-section-tr">💙 Pazarlama Modülü</span> - 18 Dosya

#### Genel Bakış & Strateji

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **Pazarlama Genel Bakış** | Pazarlama operasyonları genel bakış | [View](marketing/marketing-overview-en.md) | [Görüntüle](marketing/marketing-overview-tr.md) |
| **Marka Rehberi** | Marka kimliği ve kullanım rehberi | [View](marketing/brand-guideline-en.md) | [Görüntüle](marketing/brand-guideline-tr.md) |

#### Kampanyalar & Takvim

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **Sezonluk Pazarlama Takvimi** | Yıllık pazarlama takvimi | [View](marketing/seasonal-marketing-calendar-en.md) | [Görüntüle](marketing/seasonal-marketing-calendar-tr.md) |
| **Kampanya Uygulama Rehberi** | Kampanya uygulama prosedürleri | [View](marketing/campaign-execution-guide-en.md) | [Görüntüle](marketing/campaign-execution-guide-tr.md) |

#### Dijital & Sosyal

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **Dijital Varlık Kullanımı** | Dijital varlık yönetimi rehberi | [View](marketing/digital-assets-usage-en.md) | [Görüntüle](marketing/digital-assets-usage-tr.md) |
| **Sosyal Medya Lokalizasyonu** | Sosyal medya lokalizasyon standartları | [View](marketing/social-media-localization-guide-en.md) | [Görüntüle](marketing/social-media-localization-guide-tr.md) |

#### Mağaza İçi Pazarlama

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **POSM Rehberi** | Satış noktası malzemeleri rehberi | [View](marketing/posm-guideline-en.md) | [Görüntüle](marketing/posm-guideline-tr.md) |
| **Mağaza İçi İletişim** | Mağaza içi iletişim standartları | [View](marketing/in-store-communication-guide-en.md) | [Görüntüle](marketing/in-store-communication-guide-tr.md) |

#### Onay Süreci

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **Pazarlama Onay Süreci** | Pazarlama onay iş akışı | [View](marketing/marketing-approval-process-en.md) | [Görüntüle](marketing/marketing-approval-process-tr.md) |

---

### <span id="vm-section-tr">🟦 Görsel Mağazacılık Modülü</span> - 12 Dosya

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **VM Genel Bakış** | VM operasyonları genel bakış | [View](vm/vm-overview-en.md) | [Görüntüle](vm/vm-overview-tr.md) |
| **VM Genel Rehberi** | Genel görsel mağazacılık standartları | [View](vm/vm-guideline-general-en.md) | [Görüntüle](vm/vm-guideline-general-tr.md) |
| **Vitrin Standartları** | Vitrin standartları | [View](vm/window-display-guideline-en.md) | [Görüntüle](vm/window-display-guideline-tr.md) |
| **Mağaza Yerleşim Rehberi** | Mağaza yerleşim prensipleri | [View](vm/in-store-layout-guideline-en.md) | [Görüntüle](vm/in-store-layout-guideline-tr.md) |
| **Manken Stillendirme Rehberi** | Manken stillendirme standartları | [View](vm/mannequin-styling-guideline-en.md) | [Görüntüle](vm/mannequin-styling-guideline-tr.md) |
| **Sezonluk VM Geçişi** | Sezonluk VM geçiş rehberi | [View](vm/seasonal-vm-changeover-en.md) | [Görüntüle](vm/seasonal-vm-changeover-tr.md) |

---

### <span id="store-operations-section-tr">🟩 Mağaza Operasyonları Modülü</span> - 16 Dosya

#### Genel Bakış & Günlük Operasyonlar

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **Mağaza Operasyonları Genel Bakış** | Mağaza operasyonları genel bakış | [View](store-operations/store-operations-overview-en.md) | [Görüntüle](store-operations/store-operations-overview-tr.md) |
| **Açılış/Kapanış Prosedürleri** | Mağaza açılış/kapanış prosedürleri | [View](store-operations/opening-closing-procedures-en.md) | [Görüntüle](store-operations/opening-closing-procedures-tr.md) |

#### Nakit & Müşteri Hizmetleri

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **Nakit Yönetimi Rehberi** | Nakit işlem prosedürleri | [View](store-operations/cash-management-guide-en.md) | [Görüntüle](store-operations/cash-management-guide-tr.md) |
| **Müşteri Hizmetleri Standartları** | Müşteri hizmetleri mükemmelliği | [View](store-operations/customer-service-standards-en.md) | [Görüntüle](store-operations/customer-service-standards-tr.md) |

#### İadeler & Envanter

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **İade & Değişim Prosedürleri** | İade ve değişim politikaları | [View](store-operations/return-exchange-procedures-en.md) | [Görüntüle](store-operations/return-exchange-procedures-tr.md) |
| **Envanter Kontrol Rehberi** | Envanter yönetimi prosedürleri | [View](store-operations/inventory-control-guide-en.md) | [Görüntüle](store-operations/inventory-control-guide-tr.md) |

#### Kayıp Önleme & Güvenlik

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **Kayıp Önleme Rehberi** | Kayıp önleme prosedürleri | [View](store-operations/loss-prevention-guide-en.md) | [Görüntüle](store-operations/loss-prevention-guide-tr.md) |

---

### <span id="supply-chain-section-tr">🟧 Tedarik Zinciri & Lojistik Modülü</span> - 12 Dosya

#### Genel Bakış & Siparişler

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **Tedarik Zinciri Genel Bakış** | Tedarik zinciri operasyonları genel bakış | [View](supply-chain/supply-chain-overview-en.md) | [Görüntüle](supply-chain/supply-chain-overview-tr.md) |
| **Sipariş Yönetimi Rehberi** | Sipariş yönetimi prosedürleri | [View](supply-chain/order-management-guide-en.md) | [Görüntüle](supply-chain/order-management-guide-tr.md) |

#### Teslimat & Kabul

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **Teslimat & Kabul Prosedürleri** | Teslimat kabul standartları | [View](supply-chain/delivery-receiving-procedures-en.md) | [Görüntüle](supply-chain/delivery-receiving-procedures-tr.md) |
| **Stok Transfer Prosedürleri** | Stok transfer süreçleri | [View](supply-chain/stock-transfer-procedures-en.md) | [Görüntüle](supply-chain/stock-transfer-procedures-tr.md) |

#### Depo & Sevkiyat

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **Depo Koordinasyon Rehberi** | Depo koordinasyon prosedürleri | [View](supply-chain/warehouse-coordination-guide-en.md) | [Görüntüle](supply-chain/warehouse-coordination-guide-tr.md) |
| **Sevkiyat & Lojistik Rehberi** | Sevkiyat ve lojistik rehberi | [View](supply-chain/shipping-logistics-guide-en.md) | [Görüntüle](supply-chain/shipping-logistics-guide-tr.md) |

---

### <span id="training-section-tr">🎓 Eğitim Modülü</span> - 24 Dosya

| Belge | Açıklama | İngilizce | Türkçe |
|-------|----------|-----------|---------|
| **Eğitim Genel Bakış** | Eğitim programı genel bakış | [View](training/training-overview-en.md) | [Görüntüle](training/training-overview-tr.md) |
| **Yeni İşe Alım Rehberi** | Yeni çalışan işe alım prosedürleri | [View](training/onboarding-guide-en.md) | [Görüntüle](training/onboarding-guide-tr.md) |
| **Ürün Bilgisi Temelleri** | Temel ürün bilgisi | [View](training/product-knowledge-basics-en.md) | [Görüntüle](training/product-knowledge-basics-tr.md) |
| **Satış Teknikleri** | Satış teknikleri ve en iyi uygulamalar | [View](training/sales-techniques-en.md) | [Görüntüle](training/sales-techniques-tr.md) |
| **Müşteri Deneyimi Standartları** | Müşteri deneyimi mükemmellik standartları | [View](training/customer-experience-standards-en.md) | [Görüntüle](training/customer-experience-standards-tr.md) |
| **Müşteri Etkileşim Senaryoları** | Yaygın müşteri etkileşim senaryoları | [View](training/customer-interaction-scenarios-en.md) | [Görüntüle](training/customer-interaction-scenarios-tr.md) |
| **Yeterlilik Çerçevesi** | Çalışan yeterlilik çerçevesi | [View](training/competency-framework-en.md) | [Görüntüle](training/competency-framework-tr.md) |
| **Sezonluk Eğitim Paketi** | Sezonluk eğitim materyalleri | [View](training/seasonal-training-pack-en.md) | [Görüntüle](training/seasonal-training-pack-tr.md) |
| **Eğitim Değerlendirmesi** | Eğitim değerlendirme ve ölçümü | [View](training/training-assessment-en.md) | [Görüntüle](training/training-assessment-tr.md) |
| **Marka Ekleri - USPA** | U.S. Polo Assn. marka eğitimi | [View](training/brand-supplement-uspa-en.md) | [Görüntüle](training/brand-supplement-uspa-tr.md) |
| **Marka Ekleri - Pierre Cardin** | Pierre Cardin marka eğitimi | [View](training/brand-supplement-pierre-cardin-en.md) | [Görüntüle](training/brand-supplement-pierre-cardin-tr.md) |
| **Marka Ekleri - Cacharel** | Cacharel marka eğitimi | [View](training/brand-supplement-cacharel-en.md) | [Görüntüle](training/brand-supplement-cacharel-tr.md) |

---

## Belge Özeti

| Modül | Belge Çiftleri | Diller | Toplam Dosya |
|-------|----------------|--------|--------------|
| Sözlük | 3 | TR/EN | 6 |
| Rehberler | 3 | TR/EN | 6 |
| CRM | 10 | TR/EN | 20 |
| Pazarlama | 9 | TR/EN | 18 |
| Görsel Mağazacılık | 6 | TR/EN | 12 |
| Mağaza Operasyonları | 8 | TR/EN | 16 |
| Tedarik Zinciri | 6 | TR/EN | 12 |
| Eğitim | 12 | TR/EN | 24 |
| **Toplam** | **57** | **TR/EN** | **114** |

---

## Nasıl Kullanılır

### Mağaza Müdürleri İçin
1. [Mağaza Operasyonları Genel Bakış](store-operations/store-operations-overview-tr.md) ile başlayın
2. Günlük rutinler için [Açılış/Kapanış Prosedürleri](store-operations/opening-closing-procedures-tr.md) referans alın
3. Vitrin standartları için [VM Genel Bakış](vm/vm-overview-tr.md) takip edin
4. Hizmet mükemmelliği için [Müşteri Hizmetleri Standartları](store-operations/customer-service-standards-tr.md) gözden geçirin

### Operasyon Ekipleri İçin
1. Lojistik için [Tedarik Zinciri Genel Bakış](supply-chain/supply-chain-overview-tr.md) gözden geçirin
2. Performans metrikleri için [Finans KPI Formülleri](glossary/finance-kpi-formulas-tr.md) kullanın
3. Stok yönetimi için [Envanter Kontrol Rehberi](store-operations/inventory-control-guide-tr.md) takip edin

### Pazarlama Ekipleri İçin
1. [Pazarlama Genel Bakış](marketing/marketing-overview-tr.md) ile başlayın
2. Marka tutarlılığı için [Marka Rehberi](marketing/brand-guideline-tr.md) takip edin
3. Kampanyalar için [Kampanya Uygulama Rehberi](marketing/campaign-execution-guide-tr.md) gözden geçirin
4. Planlama için [Sezonluk Pazarlama Takvimi](marketing/seasonal-marketing-calendar-tr.md) kullanın

### Franchise Sahipleri İçin
1. [Finans Formülleri](glossary/finance-kpi-formulas-tr.md) içindeki tüm KPI'ları anlayın
2. [İletişim Protokolü](guidelines/franchise-communication-protocol-tr.md) gözden geçirin
3. Ekiplerin tüm operasyonel rehberleri takip ettiğinden emin olun
4. Dokümante edilmiş KPI'larla performansı izleyin

---

## İletişim

**Aydınlı Grup Franchise Operasyonları**

- E-posta: franchise@aydinli-franchise.com
- Destek: support@aydinli-franchise.com

---

## Lisans

© 2025 Aydınlı Grup - Tüm hakları saklıdır.

Bu dokümantasyon mülkiyet ve gizlidir. Dağıtım yalnızca yetkili Aydınlı Grup franchise ortaklarıyla sınırlıdır.

---

*Aydınlı Grup Franchise Operasyonları Ekibi tarafından hazırlanmıştır*

</div>

