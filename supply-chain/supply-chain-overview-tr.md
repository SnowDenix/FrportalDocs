---
layout: default
title: "Tedarik Zinciri ve Lojistik Genel Bakış – TR"
parent: Supply Chain
---

# Tedarik Zinciri ve Lojistik Genel Bakış – TR

> **Son Güncelleme:** 01 Aralık 2025 | **Versiyon:** 1.0  
> **Hazırlayan:** Aydınlı Grup  
> **Markalar:** U.S. Polo Assn., Pierre Cardin, Cacharel

---

## İçindekiler

1. [Hızlı Bakış (EN/TR Toggle)](#hızlı-bakış-entr-toggle)
2. [Amaç](#amaç)
3. [Kapsam](#kapsam)
4. [Tanımlar](#tanımlar)
5. [Sorumluluklar](#sorumluluklar)
6. [Süreç Adımları](#süreç-adımları)
7. [Standartlar ve Kurallar](#standartlar-ve-kurallar)
8. [Kontrol Listeleri](#kontrol-listeleri)
9. [Örnekler / Senaryolar](#örnekler--senaryolar)
10. [KPI'lar](#kpilar)
11. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
12. [Revizyon Geçmişi](#revizyon-geçmişi)

---

## Hızlı Bakış (EN/TR Toggle)

{% include lang-toggle.html group="supply-chain-overview" default="tr" %}

<div class="lang-section" data-group="supply-chain-overview" data-lang="tr">

**Amaç**
- Uçtan uca tedarik zinciri görünümü: tedarik, depolama, dağıtım, mağazalar

**Kapsam ve roller**
- Roller: Mağaza Ekibi, Bölge Müdürü, Merkez Tedarik Zinciri
- Kapsam: sipariş, teslim alma, transfer, yenileme, lojistik

**Hizmet hedefleri**
- Stok doğruluğu ≥%98; zamanında teslimat; hasar raporu <24s; dengeli tahsis

**Döngü bazlı olmazsa olmazlar**
- Siparişler zamanında; ASN/BOL kaydı; kabul kontrolleri; transfer takibi
</div>

<div class="lang-section is-hidden" data-group="supply-chain-overview" data-lang="en">

**Purpose**
- End-to-end supply chain view: sourcing, warehousing, distribution, stores

**Scope & roles**
- Roles: Store Team, Regional Manager, HQ Supply Chain
- Coverage: orders, receiving, transfers, replenishment, logistics

**Service targets**
- Stock accuracy ≥98%; on-time delivery; damage reports <24h; balanced allocations

**Per-cycle must-haves**
- Orders on schedule; ASN/BOL captured; receiving checks done; transfers tracked
</div>

---
## Amaç

Bu doküman, Aydınlı Grup franchise ortakları için tedarik zinciri ve lojistik operasyonlarına kapsamlı bir genel bakış sunmaktadır. Verimli tedarik zinciri yönetimi, tüm perakende lokasyonlarında ürün bulunabilirliği, envanter optimizasyonu ve müşteri memnuniyetini sağlar.

### Tedarik Zinciri Misyonu

"Doğru ürünü, doğru yere, doğru zamanda, doğru miktarda, doğru maliyetle teslim etmek."

### Temel Hedefler

| Hedef | Etki |
|-------|------|
| **Ürün Bulunabilirliği** | Stoksuzluğu minimize et |
| **Envanter Optimizasyonu** | Fazla stoğu azalt |
| **Pazara Hız** | Hızlı yenileme |
| **Maliyet Verimliliği** | Lojistik maliyetleri minimize et |
| **Doğruluk** | Hatasız teslimatlar |

---

## Kapsam

### Tedarik Zinciri Bileşenleri

```
TEDARİK ZİNCİRİ AKIŞI

TEDARİK
├── Üreticiler
│   (Türkiye + Uzak Doğu)
│
DEPOLAMA
├── Ana DC
│   (İstanbul)
│
DAĞITIM
├── TR Mağazalar
├── EU Hub → Yerel Mağazalar
├── ME Hub → Yerel Mağazalar
└── Diğer Hublar → Yerel Mağazalar
```

---

## Tanımlar

| Terim (EN) | Terim (TR) | Tanım |
|------------|------------|-------|
| DC | Dağıtım Merkezi | Distribution Center |
| Lead Time | Tedarik Süresi | Siparişten teslimata süre |
| SKU | Stok Kodu | Stok Tutma Birimi |
| MOQ | Minimum Sipariş | Minimum Sipariş Miktarı |
| PO | Satınalma Siparişi | Purchase Order |
| ASN | Ön Sevk Bildirimi | Önceden Sevkiyat Bildirimi |
| BOL | Konşimento | Bill of Lading |
| FIFO | İlk Giren İlk Çıkar | İlk Giren, İlk Çıkar |
| Safety Stock | Güvenlik Stoğu | Tampon envanter |
| Reorder Point | Yeniden Sipariş Noktası | Yeniden siparişi tetikleyen envanter seviyesi |

---

## Sorumluluklar

### Mağaza Ekibi

| Sorumluluk | Standart |
|------------|----------|
| Sipariş gönderimi | Programa göre |
| Teslimat kabulü | Prosedüre göre |
| Envanter doğruluğu | ≥%98 |
| Hasar raporlama | 24 saat içinde |
| Transfer talepleri | Gerektiğinde |

### Bölge Müdürü

| Sorumluluk | Standart |
|------------|----------|
| Bölgesel tahsis | Stoğu dengele |
| Transfer koordinasyonu | Bölge içinde |
| Teslimat planlaması | Rotaları optimize et |
| Performans izleme | Haftalık inceleme |

### Merkez Tedarik Zinciri Ekibi

| Sorumluluk | Standart |
|------------|----------|
| Envanter planlaması | Sezonluk tahmin |
| Sipariş işleme | 24 saat dönüş |
| Lojistik koordinasyonu | Taşıyıcı yönetimi |
| Performans analizi | Aylık raporlama |

---

## Süreç Adımları

### Sipariş Döngüsü

```
GÜN 1: SİPARİŞ GÖNDERİMİ
├── Mağaza envanteri inceler
├── Yenileme ihtiyaçlarını belirler
├── B2B portalı üzerinden sipariş gönderir
└── Sipariş son tarihi: 18:00 yerel saat

GÜN 2: SİPARİŞ İŞLEME
├── HQ siparişi inceler
├── Envanter durumunu kontrol eder
├── Siparişi onaylar veya düzeltir
└── Sipariş onayı gönderir

GÜN 3-4: TOPLAMA VE PAKETLEME
├── Depo siparişi toplar
├── Kalite kontrolü
├── Standartlara göre paketleme
└── Sevkiyat belgelerini oluşturur

GÜN 4-5: SEVKİYAT
├── Taşıyıcı teslim alımı
├── Transit takibi
└── Mağazaya ETA bildirimi

GÜN 5-7: TESLİMAT VE KABUL
├── Mağazaya teslimat
├── Mağaza kabul süreci
├── Envanter güncelleme
└── Tutarsızlık raporlama
```

### Sezonluk Planlama Döngüsü

| Aşama | Zamanlama | Aktiviteler |
|-------|-----------|-------------|
| **Planlama** | T-6 ay | Tahmin, bütçeleme |
| **Sipariş** | T-4 ay | Üretim siparişleri |
| **Üretim** | T-3 ay | İmalat |
| **Sevkiyat** | T-2 ay | DC'ye lojistik |
| **Dağıtım** | T-1 ay | Mağaza tahsisleri |
| **Lansman** | T-Günü | Sezon başlar |

---

## Standartlar ve Kurallar

### Sipariş Standartları

| Standart | Gereksinim |
|----------|------------|
| **Sipariş Penceresi** | Bölgesel programa göre |
| **Minimum Sipariş** | Anlaşmaya göre |
| **Tedarik Süresi** | 5-7 iş günü (Türkiye) |
| **Sipariş Doğruluğu** | Tam siparişler gönder |
| **Ödeme Şartları** | Sözleşmeye göre |

### Teslimat Standartları

| Standart | Hedef |
|----------|-------|
| **Zamanında Teslimat** | ≥%95 |
| **Tam Siparişler** | ≥%98 |
| **Hasarsız** | ≥%99 |
| **Belge Doğruluğu** | %100 |

### Kabul Standartları

| Standart | Gereksinim |
|----------|------------|
| **Kabul Penceresi** | 24 saat içinde |
| **Doğrulama** | Ürünlerin %100'ü |
| **Tutarsızlık Raporlama** | Aynı gün |
| **Envanter Güncelleme** | Aynı gün |

---

## Kontrol Listeleri

### Haftalık Sipariş Kontrol Listesi

```
HAFTALIK SİPARİŞ HAZIRLIĞI
Tarih: _____________ Mağaza: _____________

ENVANTER İNCELEME
□ Mevcut stok seviyeleri kontrol edildi
□ Satış hızı analiz edildi
□ Düşük stok ürünleri belirlendi
□ Fazla stok ürünleri not edildi

SİPARİŞ PLANLAMA
□ Gerekli miktarlar hesaplandı
□ Beden oranları değerlendirildi
□ Kampanya ihtiyaçları dahil edildi
□ Yaklaşan etkinlikler değerlendirildi

SİPARİŞ GÖNDERİMİ
□ Sipariş B2B portalına girildi
□ Miktarlar doğrulandı
□ Teslimat adresi onaylandı
□ Sipariş son tarihine kadar gönderildi

ONAY
□ Sipariş onayı alındı
□ Onaylanan miktarlar eşleşiyor
□ Beklenen teslimat tarihi not edildi
□ Düzeltmeler kabul edildi

Sipariş Numarası: _____________
Beklenen Teslimat: _____________
```

### Teslimat Kabul Kontrol Listesi

```
TESLİMAT KABUL KONTROL LİSTESİ
Tarih: _____________ Teslimat #: _____________

TESLİMAT ÖNCESİ
□ Kabul alanı hazırlandı
□ Personel atandı
□ Beklenen ürün listesi hazır
□ Tarayıcı/ekipman hazır

VARIŞ KONTROLÜ
□ Taşıyıcı ve araç doğrulandı
□ Mühür numarası ASN ile eşleşiyor
□ Dış hasar kontrolü
□ Kutu sayısı eşleşiyor

KABUL SÜRECİ
□ Her kutu açıldı ve kontrol edildi
□ Ürünler sisteme tarandı
□ Miktarlar doğrulandı
□ Hasarlı ürünler ayrıldı
□ Eksik ürünler belgelendi
□ Fazla ürünler belgelendi

TAMAMLAMA
□ Teslimat notlarla imzalandı
□ Tutarsızlık raporu dosyalandı (varsa)
□ Ürünler stoğa taşındı
□ Envanter sistemi güncellendi
□ Evraklar dosyalandı

Beklenen Toplam Adet: _____
Alınan Toplam Adet: _____
Hasarlı Adet: _____
Fark: _____

Kabul Eden: _____________
Müdür: _____________
```

---

## Örnekler / Senaryolar

### Senaryo 1: Acil Stok Talebi

**Durum:** Hafta sonu öncesi kilit ürünler azalıyor

**Süreç:**
```
1. Bölgesel envanteri kontrol et (diğer mağazalar)
2. Mevcutsa: Mağazalar arası transfer talep et
3. Mevcut değilse: Bölge Müdürüyle iletişime geç
4. DC'den hızlandırılmış sevkiyat talep et
5. Mevcudiyet ve ETA'yı onayla
6. Kritikse ekspres teslimat ayarla
7. Envanter planlamasını güncelle
```

### Senaryo 2: Eksik Teslimat

**Durum:** 100 beklenen, 80 adet alındı

**Süreç:**
```
1. Eksikliği teslimat makbuzunda belgele
2. Tüm belgelerin fotoğrafını çek
3. Tutarsızlık formunu tamamla
4. 24 saat içinde HQ'ya gönder
5. Eksik ürünler için envanteri düzeltME
6. HQ'dan çözüm bekle
7. 48 saat içinde yanıt gelmezse takip et
```

### Senaryo 3: Sevkiyatta Hasarlı Ürün

**Durum:** 5 ürün sevkiyat sırasında hasar görmüş

**Süreç:**
```
1. Hasarlı ürünleri fotoğrafla
2. Kabul raporunda belgele
3. İyi envanterden ayır
4. Hasar talep formunu tamamla
5. HQ ve taşıyıcıya gönder
6. Hasarlı ürünleri inceleme için tut
7. Değiştirme veya kredi bekle
```

---

## KPI'lar

### Tedarik Zinciri Metrikleri

| KPI | Formül | Hedef | Sıklık |
|-----|--------|-------|--------|
| **Sipariş Doğruluğu** | Doğru ürün / Toplam ürün | ≥%99 | Teslimat başına |
| **Zamanında Teslimat** | Zamanında teslimat / Toplam | ≥%95 | Aylık |
| **Doldurma Oranı** | Sevk edilen / Sipariş edilen | ≥%97 | Aylık |
| **Envanter Devir Hızı** | SMM / Ort envanter | Yılda 4-6x | Üç aylık |
| **Stoksuzluk Oranı** | Stoksuz SKU / Toplam | <%3 | Haftalık |
| **Kabul Doğruluğu** | Doğru kabuller / Toplam | %100 | Teslimat başına |

### Tedarik Zinciri Panosu

```
┌─────────────────────────────────────────────────────────────┐
│              AYLIK TEDARİK ZİNCİRİ PERFORMANSI              │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  Zamanında Teslimat    [████████████████████░░] %96        │
│  Hedef: ≥%95           ✓ KARŞILIYOR                         │
│                                                             │
│  Sipariş Doldurma Oranı[████████████████████░░] %98        │
│  Hedef: ≥%97           ✓ AŞIYOR                             │
│                                                             │
│  Kabul Doğruluğu       [████████████████████████] %100     │
│  Hedef: %100           ✓ KARŞILIYOR                         │
│                                                             │
│  Stoksuzluk Oranı      [██░░░░░░░░░░░░░░░░░░░░] %2.1       │
│  Hedef: <%3            ✓ HEDEF İÇİNDE                       │
│                                                             │
│  Bu Ay En Çok Sorunlar:                                     │
│  1. Taşıyıcı gecikmesi (2 sevkiyat)                        │
│  2. DC stok eksikliği (3 SKU)                              │
│  3. Adres hatası (1 teslimat)                              │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## Sık Karşılaşılan Sorunlar ve Çözümler

### Sorun 1: Sık Stoksuzluk

**Problem:** Kilit ürünler düzenli olarak stoksuz kalıyor

**Çözümler:**
- Yeniden sipariş noktalarını incele
- Güvenlik stoğu seviyelerini artır
- Talep tahminini iyileştir
- Öncelikli tahsis talep et
- Mağaza transferlerini düşün

---

### Sorun 2: Teslimat Gecikmeleri

**Problem:** Sevkiyatlar geç varıyor

**Çözümler:**
- Sevkiyatları proaktif izle
- Taşıyıcıyla iletişim kur
- Tampon süre planla
- Alternatif taşıyıcıları düşün
- Tekrarlayan sorunları eskalasyon yap

---

### Sorun 3: Sipariş Hataları

**Problem:** Yanlış ürün/miktar alınıyor

**Çözümler:**
- Göndermeden önce siparişleri doğrula
- Kabulü iki kez kontrol et
- Tutarsızlıkları hemen raporla
- Araştırma talep et
- Sipariş sürecini incele

---

## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 2025-12-01 | İlk versiyon oluşturuldu | Aydınlı Grup Tedarik Zinciri |

---

*Bu doküman Aydınlı Grup Tedarik Zinciri Ekibi tarafından hazırlanmıştır.*  
*© 2025 Aydınlı Grup - Tüm hakları saklıdır.*


