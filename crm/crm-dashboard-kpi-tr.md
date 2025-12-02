---
layout: default
title: "CRM Dashboard ve KPI Rehberi"
---

# CRM Dashboard ve KPI Rehberi

> **Son Güncelleme:** 01 Aralık 2025 | **Versiyon:** 1.0  
> **Hazırlayan:** Aydınlı Grup

---

## İçindekiler

1. [Amaç](#amaç)
2. [Kapsam](#kapsam)
3. [Tanımlar](#tanımlar)
4. [Sorumluluklar](#sorumluluklar)
5. [CRM KPI'ları](#crm-kpıları)
6. [Dashboard Kullanımı](#dashboard-kullanımı)
7. [Raporlama Periyotları](#raporlama-periyotları)
8. [Ekran Görüntüleri](#ekran-görüntüleri)
9. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
10. [Mağaza İpuçları](#mağaza-ipuçları)
11. [Revizyon Geçmişi](#revizyon-geçmişi)

---

## Amaç

Bu doküman, Aydınlı Grup franchise mağazalarında (U.S. Polo Assn., Pierre Cardin, Cacharel) CRM performansının takip edilmesi için kullanılan KPI'ları ve dashboard kullanımını açıklar.

### Dashboard'un Amacı

- CRM performansını anlık olarak izlemek
- Hedeflerle karşılaştırma yapmak
- Aksiyon gerektiren alanları tespit etmek
- Performans trendlerini analiz etmek
- Mağazalar arası karşılaştırma yapmak

---

## Kapsam

### Bu Doküman Kimleri Kapsar?

| Rol | Kullanım Amacı |
|-----|----------------|
| Mağaza Müdürü | Günlük performans takibi |
| Bölge Müdürü | Bölgesel performans analizi |
| CRM Merkez | Global performans ve trend analizi |
| Franchise Sahibi | İş sonuçları takibi |

### Dashboard Türleri

| Dashboard | Kullanıcı | İçerik |
|-----------|-----------|--------|
| Mağaza Dashboard | Mağaza Müdürü | Mağaza KPI'ları |
| Bölge Dashboard | Bölge Müdürü | Bölge özeti |
| Global Dashboard | CRM Merkez | Tüm mağazalar |
| Executive Dashboard | Üst Yönetim | Özet metrikler |

---

## Tanımlar

### KPI Terimleri

| Terim | Tanım |
|-------|-------|
| **KPI** | Key Performance Indicator - Temel Performans Göstergesi |
| **Target** | Hedef değer |
| **Actual** | Gerçekleşen değer |
| **Variance** | Hedef ile gerçekleşen arasındaki fark |
| **YoY** | Year over Year - Yıllık karşılaştırma |
| **MoM** | Month over Month - Aylık karşılaştırma |
| **WoW** | Week over Week - Haftalık karşılaştırma |
| **Benchmark** | Referans değer |
| **Trend** | Zaman içindeki değişim yönü |

### Renk Kodları

| Renk | Anlam | Aksiyon |
|------|-------|---------|
| 🟢 Yeşil | Hedefin üzerinde (>100%) | Devam et |
| 🟡 Sarı | Hedefe yakın (85-100%) | İzle |
| 🔴 Kırmızı | Hedefin altında (<85%) | Aksiyon al |

---

## Sorumluluklar

### Mağaza Müdürü

| Görev | Sıklık |
|-------|--------|
| Günlük KPI kontrolü | Her gün |
| Haftalık performans değerlendirmesi | Her Pazartesi |
| Düşük performans aksiyon planı | Anında |
| Ekiple KPI paylaşımı | Günlük |

### Bölge Müdürü

| Görev | Sıklık |
|-------|--------|
| Bölge performans analizi | Haftalık |
| Mağaza karşılaştırması | Haftalık |
| En iyi uygulama paylaşımı | Sürekli |
| Merkeze raporlama | Aylık |

---

## CRM KPI'ları

### 1. Müşteri Eşleştirme KPI'ları

#### Loyalty Penetration Rate

**Tanım:** Toplam satış işlemlerinin ne kadarının loyalty üyesi ile eşleştirildiği

**Formül:**
```
Loyalty Penetration % = (Üyeli Satış Adedi / Toplam Satış Adedi) × 100
```

**Örnek Hesaplama:**
- Toplam satış adedi: 1.000
- Üyeli satış adedi: 720
- Loyalty Penetration = (720 / 1.000) × 100 = **%72**

**Hedef:** %70 ve üzeri

**Franchise Etkisi:** Yüksek penetration = daha fazla müşteri verisi = daha iyi hedefleme

---

#### Customer Match Rate

**Tanım:** CRM'deki kayıtlı müşterilere eşleştirilen satış oranı

**Formül:**
```
Customer Match Rate % = (Eşleştirilmiş Satış / Toplam Satış) × 100
```

**Hedef:** %75 ve üzeri

---

### 2. Müşteri Tabanı KPI'ları

#### Active Customer Rate

**Tanım:** Son 12 ayda alışveriş yapmış müşterilerin toplam üye tabanına oranı

**Formül:**
```
Active Customer Rate % = (Son 12 Ay Aktif Müşteri / Toplam Üye) × 100
```

**Örnek Hesaplama:**
- Toplam üye: 50.000
- Son 12 ayda alışveriş yapan: 20.000
- Active Customer Rate = (20.000 / 50.000) × 100 = **%40**

**Hedef:** %35 ve üzeri

**Franchise Etkisi:** Aktif müşteri oranı, loyalty programının etkinliğini gösterir

---

#### New Customer Acquisition

**Tanım:** Dönem içinde kazanılan yeni müşteri sayısı

**Formül:**
```
New Customer Rate % = (Yeni Müşteri / Toplam Satış Yapılan Müşteri) × 100
```

**Hedef:** %20-30 arası (sektör ve lokasyona göre değişir)

---

#### Customer Retention Rate

**Tanım:** Bir önceki dönemde alışveriş yapan müşterilerin bu dönemde tekrar alışveriş yapma oranı

**Formül:**
```
Retention Rate % = ((Dönem Sonu Aktif - Yeni Kazanılan) / Dönem Başı Aktif) × 100
```

**Örnek Hesaplama:**
- Dönem başı aktif: 10.000
- Dönem sonu aktif: 11.000
- Yeni kazanılan: 3.000
- Retention = ((11.000 - 3.000) / 10.000) × 100 = **%80**

**Hedef:** %70 ve üzeri

---

### 3. Müşteri Değeri KPI'ları

#### Average Transaction Value (ATV)

**Tanım:** Ortalama sepet tutarı

**Formül:**
```
ATV = Toplam Satış Tutarı / Toplam İşlem Adedi
```

**Örnek Hesaplama:**
- Toplam satış: 500.000 TL
- Toplam işlem: 1.000
- ATV = 500.000 / 1.000 = **500 TL**

---

#### Units Per Transaction (UPT)

**Tanım:** İşlem başına satılan ürün adedi

**Formül:**
```
UPT = Toplam Satılan Adet / Toplam İşlem Adedi
```

**Örnek Hesaplama:**
- Satılan adet: 2.500
- İşlem adedi: 1.000
- UPT = 2.500 / 1.000 = **2.5 adet**

**Hedef:** 2.0 ve üzeri

---

#### Customer Lifetime Value (CLV)

**Tanım:** Bir müşterinin yaşam boyu getirisi tahmini

**Formül:**
```
CLV = Ortalama Sipariş Değeri × Yıllık Alışveriş Sıklığı × Müşteri Ömrü (yıl)
```

**Örnek Hesaplama:**
- Ortalama sipariş: 500 TL
- Yıllık sıklık: 4 kez
- Müşteri ömrü: 5 yıl
- CLV = 500 × 4 × 5 = **10.000 TL**

---

### 4. Loyalty Program KPI'ları

#### Points Redemption Rate

**Tanım:** Kazanılan puanların kullanılma oranı

**Formül:**
```
Redemption Rate % = (Kullanılan Puan / Kazanılan Puan) × 100
```

**Örnek Hesaplama:**
- Kazanılan puan: 1.000.000
- Kullanılan puan: 350.000
- Redemption Rate = (350.000 / 1.000.000) × 100 = **%35**

**Hedef:** %25-40 arası (çok düşük = program bilinmiyor, çok yüksek = maliyet)

---

#### Coupon Redemption Rate

**Tanım:** Dağıtılan kuponların kullanılma oranı

**Formül:**
```
Coupon Redemption % = (Kullanılan Kupon / Dağıtılan Kupon) × 100
```

**Hedef:** %15-25 arası

---

#### Enrollment Rate

**Tanım:** Yeni müşterilerin loyalty programına kayıt oranı

**Formül:**
```
Enrollment Rate % = (Yeni Üye / Yeni Müşteri) × 100
```

**Hedef:** %50 ve üzeri

---

### 5. Kampanya KPI'ları

#### Campaign Response Rate

**Tanım:** Kampanya hedef kitlesinin kampanyaya katılım oranı

**Formül:**
```
Response Rate % = (Kampanyaya Katılan / Hedef Kitle) × 100
```

**Hedef:** %10-20 arası

---

#### Campaign ROI

**Tanım:** Kampanya yatırım getirisi

**Formül:**
```
ROI = ((Kampanya Geliri - Kampanya Maliyeti) / Kampanya Maliyeti) × 100
```

**Örnek Hesaplama:**
- Kampanya geliri: 100.000 TL
- Kampanya maliyeti: 20.000 TL
- ROI = ((100.000 - 20.000) / 20.000) × 100 = **%400**

**Hedef:** %200 ve üzeri

---

### 6. Müşteri Edinme KPI'ları

#### Customer Acquisition Cost (CAC)

**Tanım:** Yeni müşteri kazanma maliyeti

**Formül:**
```
CAC = Toplam Pazarlama Gideri / Kazanılan Yeni Müşteri Sayısı
```

**Örnek Hesaplama:**
- Pazarlama gideri: 50.000 TL
- Yeni müşteri: 500
- CAC = 50.000 / 500 = **100 TL/müşteri**

**Hedef:** CLV'nin %10-20'si kadar

---

### 7. Ticketing KPI'ları

#### SLA Compliance Rate

**Tanım:** SLA süresinde kapatılan ticket oranı

**Formül:**
```
SLA Compliance % = (SLA İçinde Kapatılan / Toplam Kapatılan) × 100
```

**Hedef:** %95 ve üzeri

---

#### First Contact Resolution (FCR)

**Tanım:** İlk temasta çözülen ticket oranı

**Formül:**
```
FCR % = (İlk Temasta Çözülen / Toplam Ticket) × 100
```

**Hedef:** %60 ve üzeri

---

## KPI Özet Tablosu

| KPI | Formül | Hedef | Sıklık |
|-----|--------|-------|--------|
| Loyalty Penetration | Üyeli Satış / Toplam Satış × 100 | >70% | Günlük |
| Active Customer Rate | 12 Ay Aktif / Toplam Üye × 100 | >35% | Aylık |
| Retention Rate | Kalan Müşteri / Dönem Başı × 100 | >70% | Aylık |
| ATV | Toplam Satış / İşlem Adedi | Artan | Günlük |
| UPT | Satılan Adet / İşlem Adedi | >2.0 | Günlük |
| Redemption Rate | Kullanılan Puan / Kazanılan Puan × 100 | 25-40% | Aylık |
| Enrollment Rate | Yeni Üye / Yeni Müşteri × 100 | >50% | Haftalık |
| SLA Compliance | SLA İçinde / Toplam Ticket × 100 | >95% | Günlük |

---

## Dashboard Kullanımı

### Ana Dashboard Bileşenleri

```
┌─────────────────────────────────────────────────────────────────┐
│                    CRM MAĞAZA DASHBOARD                          │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐             │
│  │  LOYALTY    │  │   ACTIVE    │  │    ATV      │             │
│  │  PENETR.    │  │  CUSTOMERS  │  │             │             │
│  │    72%      │  │   12.450    │  │   485 TL    │             │
│  │   🟢 +2%    │  │   🟡 -1%    │  │   🟢 +5%    │             │
│  └─────────────┘  └─────────────┘  └─────────────┘             │
│                                                                 │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │  Haftalık Trend Grafiği                                 │   │
│  │  ▄▄▄▅▅▅▆▆▇▇█                                            │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                                 │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │  Açık Ticketlar: 3    |    Bekleyen Kuponlar: 45        │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Dashboard Filtreleri

| Filtre | Seçenekler |
|--------|------------|
| Dönem | Bugün, Bu Hafta, Bu Ay, Bu Yıl, Özel Tarih |
| Marka | U.S. Polo Assn., Pierre Cardin, Cacharel, Tümü |
| Mağaza | Tekli mağaza, Bölge, Tüm mağazalar |
| Segment | Tüm müşteriler, RFM segmentleri |

### Dashboard Okuma Rehberi

**Kart Yapısı:**
- **Başlık:** KPI adı
- **Ana Değer:** Güncel performans
- **Renk:** Performans durumu
- **Değişim:** Önceki döneme göre fark

**Trend Okuma:**
- ↑ Yukarı ok: İyileşme
- ↓ Aşağı ok: Kötüleşme
- → Yatay ok: Stabil

---

## Raporlama Periyotları

### Günlük Raporlar

| Rapor | İçerik | Alıcı |
|-------|--------|-------|
| Günlük Özet | Satış, penetration, ticket | Mağaza Müdürü |
| Flash Report | Kritik KPI'lar | Bölge Müdürü |

### Haftalık Raporlar

| Rapor | İçerik | Alıcı |
|-------|--------|-------|
| Haftalık Performans | Tüm mağaza KPI'ları | Mağaza Müdürü |
| Bölge Özeti | Bölge performansı | Bölge Müdürü |
| Kampanya Raporu | Aktif kampanya sonuçları | CRM Merkez |

### Aylık Raporlar

| Rapor | İçerik | Alıcı |
|-------|--------|-------|
| Aylık Dashboard | Detaylı performans analizi | Tüm yöneticiler |
| Müşteri Analizi | Segment, CLV, churn | CRM Merkez |
| Ticket Analizi | Şikayet trendleri | Kalite Ekibi |

---

## Ekran Görüntüleri

### Mağaza Dashboard

![Mağaza Dashboard - Placeholder](screenshots/crm-store-dashboard.png)

*Ekran görüntüsü eklenecektir.*

### KPI Detay Ekranı

![KPI Detay - Placeholder](screenshots/crm-kpi-detail.png)

*Ekran görüntüsü eklenecektir.*

---

## Sık Karşılaşılan Sorunlar ve Çözümler

### Sorun 1: KPI Verileri Güncel Değil

**Durum:** Dashboard'daki veriler güncellenmemiş görünüyor.

**Çözüm:**
1. Sayfayı yenileyin
2. Cache'i temizleyin
3. 15-30 dakika bekleyin (veri senkronizasyonu)
4. Sorun devam ederse IT'ye bildirin

---

### Sorun 2: Loyalty Penetration Düşük

**Durum:** Hedefin altında penetration oranı.

**Olası Nedenler:**
- Personel müşteri eşleştirmesi yapmıyor
- Yeni kayıt teşviki yetersiz
- Sistem kullanım zorluğu

**Çözüm:**
1. Günlük penetration hedefi belirleyin
2. Personele eşleştirme önemini anlatın
3. Her satışta müşteri sorgusu yapılmasını sağlayın

---

### Sorun 3: Redemption Rate Çok Düşük

**Durum:** Müşteriler puanlarını kullanmıyor.

**Olası Nedenler:**
- Müşteri puan bakiyesinden habersiz
- Kullanım koşulları zor
- Personel hatırlatmıyor

**Çözüm:**
1. Her satışta puan bakiyesini hatırlatın
2. Puan kullanımını teşvik edin
3. SMS ile puan hatırlatması gönderin

---

## Mağaza İpuçları

### Günlük KPI Takibi

1. **Sabah:** Dashboard'u kontrol edin, günlük hedefinizi bilin
2. **Gün içi:** Penetration oranını izleyin
3. **Akşam:** Günü değerlendirin, ertesi gün için plan yapın

### KPI İyileştirme Taktikleri

| KPI | İyileştirme Taktiği |
|-----|---------------------|
| Penetration | Her satışta "Üye misiniz?" sorun |
| UPT | Tamamlayıcı ürün önerin |
| ATV | Üst segment ürün önerin |
| Enrollment | Avantajları vurgulayın |
| Redemption | Puan bakiyesini hatırlatın |

### Ekip Motivasyonu

- Günlük hedefleri ekiple paylaşın
- İyi performansı kutlayın
- Düşük performans için destek sağlayın
- Haftalık performans değerlendirmesi yapın

---

## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 01.12.2025 | İlk sürüm oluşturuldu | Aydınlı Grup |

---

*Bu doküman Aydınlı Grup CRM Operasyonları tarafından hazırlanmıştır.*  
*© 2025 Aydınlı Grup - Tüm hakları saklıdır.*


