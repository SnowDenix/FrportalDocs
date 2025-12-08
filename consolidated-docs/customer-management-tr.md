---
layout: default
title: "Müşteri Yönetimi (TR)"
parent: Consolidated Documentation
nav_order: 2
---

# Müşteri Yönetimi - Tam Dokümantasyon (Türkçe)

> **Konsolide Doküman**  
> **Son Güncelleme:** 8 Aralık 2025  
> **Hazırlayan:** Aydınlı Grup
>
> **Kaynak Dosyalar:** crm klasöründen 10 dosya

---

## Doküman Genel Bakış

Bu kapsamlı CRM dokümantasyonu, Aydınlı Grup franchise mağazaları için müşteri ilişkileri yönetiminin tüm yönlerini kapsamaktadır. Doküman 10 ana bölümden oluşmaktadır:

**Bölüm 1: CRM Müşteri Verileri Politikası** - KVKK uyumlu veri koruma politikalarını belirler, müşteri bilgilerinin nasıl toplanması, saklanması ve yönetilmesi gerektiğini tanımlar. Yasal gereklilikleri, izin yönetimini, veri saklama sürelerini ve silme talepleri dahil müşteri haklarını kapsar.

**Bölüm 2: Müşteri Segmentasyonu** - RFM (Yenilik, Sıklık, Parasal) segmentasyon metodolojisini ve müşteri yaşam döngüsü aşamalarını açıklar. Yeni müşterilerden VIP üyelere, riskli ve kayıp müşteri geri kazanım yaklaşımları dahil farklı müşteri segmentlerini hedefleme stratejileri sunar.

**Bölüm 3: Dashboard ve KPI Kılavuzu** - Sadakat penetrasyonu, müşteri eşleştirme oranı, ortalama işlem değeri ve müşteri yaşam boyu değeri dahil tüm CRM temel performans göstergelerini detaylandırır. Mağaza performansını takip etmek için formüller, hedefler ve dashboard kullanım talimatlarını içerir.

**Bölüm 4: Veri Kalitesi Yönetimi** - Telefon numaraları, e-postalar, isimler ve tarihler için doğrulama kuralları ile yüksek kaliteli müşteri verilerini koruma standartlarını belirler. Düzeltme süreçlerini, duplicate yönetimini ve veri kalitesi KPI'larını kapsar.

**Bölüm 5: Yapılması ve Yapılmaması Gerekenler** - Kayıt, veri güvenliği, müşteri iletişimi, sadakat operasyonları ve sistem kullanımını kapsayan izin verilen ve yasaklanan CRM uygulamaları hakkında net yönergeler sunar. İhlal sonuçlarını ve uyum gerekliliklerini içerir.

**Bölüm 6: Sadakat Programı ve Kampanyalar** - Puan sistemi yapısını, kazanma ve kullanma kurallarını, kupon yönetimini ve kampanya yürütmesini açıklar. Müşteri katılımı için üyelik kademelerini, puan geçerlilik sürelerini ve çeşitli kampanya türlerini detaylandırır.

**Bölüm 7: CRM Genel Bakış** - Sistem mimarisini, entegrasyon noktalarını ve genel CRM vizyonunu sunar. Temel terminolojiyi, iletişim izin türlerini ve POS sistemleri ile merkezi CRM platformu arasındaki veri akışını tanımlar.

**Bölüm 8: Mağaza CRM Kontrol Listesi** - Mağaza personeli ve müdürleri için günlük, haftalık ve aylık kontrol listeleri sunar. Uyum ve tutarlılığı sağlamak için satış süreçleri, müşteri kaydı ve ticket yönetimi için sistematik görev listeleri sağlar.

**Bölüm 9: Mağaza Kullanıcı Kılavuzu** - Giriş, müşteri arama, yeni kayıt, bilgi güncellemeleri, kupon uygulama ve puan işlemleri dahil CRM sistemini kullanmak için adım adım operasyonel talimatlar. Satış görevlileri ve kasiyerler için tasarlanmıştır.

**Bölüm 10: Ticketing Süreci** - Kategorizasyon, öncelik seviyeleri, SLA süreleri, yükseltme prosedürleri ve çözüm takibi dahil tam müşteri şikayeti ve ticketing iş akışını açıklar. Ticket performans KPI'larını ve yanıt süresi gerekliliklerini içerir.

---

## SECTION 1: CRM-CUSTOMER-DATA-POLICY-TR

﻿---
layout: default
title: "CRM Müşteri Verileri Politikası (KVKK Uyumlu)"
parent: CRM

## İçindekiler

1. [Amaç](#amaç)
2. [Kapsam](#kapsam)
3. [Tanımlar](#tanımlar)
4. [Yasal Dayanak](#yasal-dayanak)
5. [Sorumluluklar](#sorumluluklar)
6. [Veri Toplama İlkeleri](#veri-toplama-ilkeleri)
7. [İzin Yönetimi](#izin-yönetimi)
8. [Veri Saklama ve İmha](#veri-saklama-ve-imha)
9. [Müşteri Hakları](#müşteri-hakları)
10. [Süreç Adımları](#süreç-adımları)
11. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
12. [Mağaza İpuçları](#mağaza-ipuçları)
13. [Revizyon Geçmişi](#revizyon-geçmişi)


## Kapsam

### Bu Politika Kimleri Kapsar?

| Rol | Sorumluluk |
|-----|------------|
| Tüm Mağaza Personeli | Veri toplama ve işleme kurallarına uymak |
| Mağaza Müdürü | Politika uyumunu denetlemek |
| Bölge Müdürü | Bölge genelinde uyumu sağlamak |
| CRM Merkez | Veri yönetimi ve güvenliği |
| Veri Koruma Sorumlusu (DPO) | KVKK uyumluluk denetimi |

### Kapsanan Veriler

| Veri Kategorisi | Örnekler | Hassasiyet |
|-----------------|----------|------------|
| **Kimlik Bilgileri** | Ad, soyad, T.C. kimlik no | Yüksek |
| **İletişim Bilgileri** | Telefon, e-posta, adres | Orta |
| **Satın Alma Verileri** | Satış geçmişi, tercihler | Düşük |
| **Finansal Veriler** | Ödeme yöntemi (maskelenmiş) | Yüksek |
| **Demografik Veriler** | Doğum tarihi, cinsiyet | Orta |
| **İletişim Tercihleri** | SMS/E-posta izinleri | Düşük |


## Yasal Dayanak

### İlgili Mevzuat

| Mevzuat | Konu |
|---------|------|
| 6698 sayılı KVKK | Kişisel verilerin korunması |
| 6563 sayılı Kanun | Elektronik ticaret ve ticari iletişim |
| KVKK Yönetmelikleri | Uygulama detayları |
| Kişisel Verileri Koruma Kurulu Kararları | Emsal kararlar |

### Temel İlkeler (KVKK m.4)

1. **Hukuka ve dürüstlük kurallarına uygun olma**
2. **Doğru ve gerektiğinde güncel olma**
3. **Belirli, açık ve meşru amaçlar için işlenme**
4. **İşlendikleri amaçla bağlantılı, sınırlı ve ölçülü olma**
5. **İlgili mevzuatta öngörülen veya işlendikleri amaç için gerekli olan süre kadar muhafaza edilme**


## Veri Toplama İlkeleri

### Toplanabilecek Veriler

| Veri | Amaç | Zorunluluk |
|------|------|------------|
| Ad, Soyad | Müşteri tanımlama | Zorunlu |
| Cep Telefonu | İletişim, müşteri doğrulama | Zorunlu |
| E-posta | İletişim, dijital hizmetler | Önerilen |
| Doğum Tarihi | Doğum günü kampanyaları | İsteğe bağlı |
| Cinsiyet | Kişiselleştirilmiş hizmet | İsteğe bağlı |
| Adres | Teslimat hizmetleri | İsteğe bağlı |

### Toplanamayacak Veriler

Aşağıdaki veriler **kesinlikle toplanamaz**:

| Veri Türü | Açıklama |
|-----------|----------|
| Sağlık bilgileri | Hastalık, ilaç kullanımı vb. |
| Dini inanç | Din, mezhep bilgisi |
| Siyasi görüş | Parti üyeliği vb. |
| Irk/Etnik köken | Etnik köken bilgisi |
| Biyometrik veri | Parmak izi, yüz tanıma |
| Ceza mahkumiyeti | Sabıka kaydı |
| Cinsel hayat | Cinsel tercih bilgisi |

> ⚠️ **UYARI:** Bu verileri sormak, kaydetmek veya işlemek yasaktır ve ciddi yaptırımlara tabidir.

### Veri Toplama Kuralları

1. **Sadece gerekli verileri toplayın:** Amaç dışı veri toplamayın
2. **Aydınlatma yapın:** Verinin neden toplandığını açıklayın
3. **İzin alın:** Açık rızayı belgeleyin
4. **Doğrulayın:** Girilen verilerin doğruluğunu teyit edin
5. **Güvende tutun:** Verileri yetkisiz erişimden koruyun


## Veri Saklama ve İmha

### Saklama Süreleri

| Veri Kategorisi | Saklama Süresi | Dayanak |
|-----------------|----------------|---------|
| Müşteri kimlik bilgileri | Müşteri ilişkisi + 10 yıl | Ticaret Kanunu |
| Satın alma geçmişi | 10 yıl | Vergi mevzuatı |
| İletişim izinleri | İzin iptali + 10 yıl | KVKK |
| Şikayet kayıtları | Çözüm + 10 yıl | TTK |
| Loyalty işlemleri | Son işlem + 5 yıl | İç politika |

### İmha Yöntemleri

| Yöntem | Açıklama | Kullanım Alanı |
|--------|----------|----------------|
| **Silme** | Verinin geri getirilemeyecek şekilde silinmesi | Dijital kayıtlar |
| **Yok Etme** | Fiziksel imha (öğütme, yakma) | Basılı belgeler |
| **Anonimleştirme** | Verinin kişiyle ilişkilendirilemez hale getirilmesi | Analitik amaçlı |

### Periyodik İmha

- **Sıklık:** Her 6 ayda bir
- **Sorumlu:** CRM Merkez
- **Raporlama:** İmha tutanağı düzenlenir


## Süreç Adımları

### 1. Yeni Müşteri Kaydında Veri Toplama

**Adım 1:** Müşteriye aydınlatma metnini sunun

**Adım 2:** Metnin okunduğunu/anlaşıldığını teyit alın

**Adım 3:** Veri işleme iznini alın (zorunlu)

**Adım 4:** Ticari iletişim izinlerini sorun (isteğe bağlı)

**Adım 5:** İzinleri CRM'e kaydedin

**Adım 6:** Fiziksel form varsa imzalatın ve arşivleyin

**Adım 7:** Müşteriye bilgilendirme yapın

> ✅ **Doğru:** "KVKK kapsamında verilerinizi işleyebilmemiz için onayınıza ihtiyacımız var. İsterseniz kampanyalardan haberdar olmak için SMS/E-posta izni de verebilirsiniz."

> ❌ **Yanlış:** "Şuraya imza atın" (açıklama yapmadan)


### 3. Silme/Unutulma Hakkı Talebi

**Adım 1:** Müşteriden yazılı başvuru alın

**Adım 2:** Ticket açın (Kategori: KVKK Talebi)

**Adım 3:** Müşteri kimliğini doğrulayın

**Adım 4:** CRM Merkez'e yönlendirin

**Adım 5:** Yasal saklama yükümlülüklerini kontrol edin

**Adım 6:** Silinebilecek verileri silin

**Adım 7:** 30 gün içinde müşteriye yazılı yanıt verin

> ⚠️ **Dikkat:** Bazı veriler yasal zorunluluk nedeniyle silinemez (örn: fatura bilgileri 10 yıl saklanmalı).


### Sorun 2: Müşteri Verilerini Sorgulamak İstiyor

**Çözüm:**
1. Müşteri kimliğini doğrulayın
2. CRM'den müşteri verilerini çıkarın
3. Yazılı olarak müşteriye teslim edin
4. Teslim tutanağı alın


### Sorun 4: Veri İhlali Şüphesi

**Çözüm:**
1. Panik yapmayın ama hızlı hareket edin
2. Yetkisiz erişimi engelleyin
3. Mağaza müdürünü bilgilendirin
4. CRM Merkez'i arayın
5. Hiçbir şeyi silmeyin/değiştirmeyin (delil)


## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 01.12.2025 | İlk sürüm oluşturuldu | Aydınlı Grup |


---

## SECTION 2: CRM-CUSTOMER-SEGMENTATION-TR

﻿---
layout: default
title: "CRM Müşteri Segmentasyonu"
parent: CRM

## İçindekiler

1. [Amaç](#amaç)
2. [Kapsam](#kapsam)
3. [Tanımlar](#tanımlar)
4. [Sorumluluklar](#sorumluluklar)
5. [RFM Segmentasyonu](#rfm-segmentasyonu)
6. [Müşteri Yaşam Döngüsü](#müşteri-yaşam-döngüsü)
7. [Segment Bazlı Stratejiler](#segment-bazlı-stratejiler)
8. [KPI'lar](#kpılar)
9. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
10. [Mağaza İpuçları](#mağaza-ipuçları)
11. [Revizyon Geçmişi](#revizyon-geçmişi)


## Kapsam

### Bu Doküman Kimleri Kapsar?

| Rol | Kullanım Amacı |
|-----|----------------|
| Mağaza Müdürü | Segment dağılımını anlamak |
| Bölge Müdürü | Bölgesel segment analizi |
| CRM Merkez | Segment stratejileri oluşturmak |
| Pazarlama Ekibi | Hedefli kampanyalar planlamak |

### Segmentasyon Türleri

| Tür | Açıklama |
|-----|----------|
| RFM Segmentasyonu | Davranışsal segmentasyon (Recency, Frequency, Monetary) |
| Yaşam Döngüsü | Müşteri aşaması bazlı segmentasyon |
| Demografik | Yaş, cinsiyet, lokasyon bazlı |
| Değer Bazlı | Müşteri değerine göre |


## Sorumluluklar

### CRM Merkez

| Görev | Detay |
|-------|-------|
| Segment tanımı | RFM ve yaşam döngüsü segmentlerini tanımlamak |
| Analiz | Segment performansını analiz etmek |
| Strateji | Her segment için strateji belirlemek |
| Kampanya | Segment bazlı kampanyalar oluşturmak |

### Mağaza Müdürü

| Görev | Detay |
|-------|-------|
| Segment anlama | Mağaza müşteri dağılımını bilmek |
| Strateji uygulama | Segment stratejilerini uygulamak |
| Geri bildirim | Segment performansını raporlamak |


## Müşteri Yaşam Döngüsü

### Yaşam Döngüsü Aşamaları

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│    ┌─────────┐    ┌─────────┐    ┌─────────┐    ┌─────────┐   │
│    │  YENİ   │───▶│  AKTİF  │───▶│ SADIK   │───▶│   VIP   │   │
│    │ MÜŞTERİ │    │ MÜŞTERİ │    │ MÜŞTERİ │    │ MÜŞTERİ │   │
│    └─────────┘    └────┬────┘    └─────────┘    └─────────┘   │
│                        │                                        │
│                        ▼                                        │
│                   ┌─────────┐    ┌─────────┐    ┌─────────┐   │
│                   │ RİSKLİ  │───▶│ UYUYAN  │───▶│  KAYIP  │   │
│                   │ MÜŞTERİ │    │ MÜŞTERİ │    │ MÜŞTERİ │   │
│                   └─────────┘    └─────────┘    └─────────┘   │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Yaşam Döngüsü Segment Tanımları

| Aşama | Tanım | Kriter |
|-------|-------|--------|
| **Yeni Müşteri** | İlk alışverişini yapmış | Son 90 gün içinde ilk alışveriş |
| **Aktif Müşteri** | Düzenli alışveriş yapan | Son 180 günde alışveriş var |
| **Sadık Müşteri** | Uzun süredir düzenli | 12+ ay üyelik, 4+ alışveriş |
| **VIP Müşteri** | En değerli müşteriler | Top %10 CLV |
| **Riskli Müşteri** | Aktivitesi azalan | Son alışveriş 180-270 gün önce |
| **Uyuyan Müşteri** | Uzun süredir alışveriş yok | Son alışveriş 270-365 gün önce |
| **Kayıp Müşteri** | Tamamen kaybedilmiş | Son alışveriş >365 gün önce |


### Loyal Customers (Sadık Müşteriler)

**Profil:** Düzenli alışveriş yapan, marka bağlılığı yüksek

**Strateji:**
- Sadakati ödüllendir
- Çapraz satış yap
- Üst segment ürünler öner
- Marka elçisi olarak değerlendir

**Kampanya Örnekleri:**
- Sadık müşterilere ekstra puan
- Erken sezon indirimi
- Arkadaşını getir kampanyası


### Recent Customers (Yeni Müşteriler)

**Profil:** İlk alışverişini yeni yapmış

**Strateji:**
- Karşılama mesajı gönder
- İkinci alışverişi teşvik et
- Marka değerlerini anlat
- Loyalty avantajlarını açıkla

**Kampanya Örnekleri:**
- Hoş geldin kuponu
- İkinci alışverişte bonus puan
- Ürün kullanım ipuçları


### At Risk (Risk Altında)

**Profil:** Değerli ama aktivitesi düşen müşteriler

**Strateji:**
- Acil müdahale et
- Güçlü teklifler sun
- Kaybetme nedenini anla
- Yeniden kazanmaya çalış

**Kampanya Örnekleri:**
- Agresif winback teklifi
- "Son şans" kampanyası
- Kişisel arama


### Lost (Kayıp)

**Profil:** Uzun süredir alışveriş yapmayan

**Strateji:**
- Maliyet-fayda analizi yap
- Seçici winback kampanyası
- Düşük maliyetli kanallar kullan

**Kampanya Örnekleri:**
- Toplu e-posta kampanyası
- Sezonsal hatırlatma
- Büyük kampanya duyurusu


## Sık Karşılaşılan Sorunlar ve Çözümler

### Sorun 1: At Risk Oranı Yükseliyor

**Çözüm:**
1. Risk altındaki müşterileri listeleyin
2. Winback kampanyası başlatın
3. Kişisel iletişim kurun
4. Kaybetme nedenlerini araştırın


### Sorun 3: VIP Müşteriler Düşüyor

**Çözüm:**
1. VIP programını gözden geçirin
2. Kişisel ilgi artırın
3. Özel avantajlar ekleyin
4. Geri bildirim alın


## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 01.12.2025 | İlk sürüm oluşturuldu | Aydınlı Grup |


---

## SECTION 3: CRM-DASHBOARD-KPI-TR

﻿---
layout: default
title: "CRM Dashboard ve KPI Rehberi"
parent: CRM

## İçindekiler

1. [Amaç](#amaç)
2. [Kapsam](#kapsam)
3. [Tanımlar](#tanımlar)
4. [Sorumluluklar](#sorumluluklar)
5. [CRM KPI'ları](#crm-kpıları)
6. [Dashboard Kullanımı](#dashboard-kullanımı)
7. [Raporlama Periyotları](#raporlama-periyotları)
8. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
9. [Mağaza İpuçları](#mağaza-ipuçları)
10. [Revizyon Geçmişi](#revizyon-geçmişi)


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


#### Customer Match Rate

**Tanım:** CRM'deki kayıtlı müşterilere eşleştirilen satış oranı

**Formül:**
```
Customer Match Rate % = (Eşleştirilmiş Satış / Toplam Satış) × 100
```

**Hedef:** %75 ve üzeri


#### New Customer Acquisition

**Tanım:** Dönem içinde kazanılan yeni müşteri sayısı

**Formül:**
```
New Customer Rate % = (Yeni Müşteri / Toplam Satış Yapılan Müşteri) × 100
```

**Hedef:** %20-30 arası (sektör ve lokasyona göre değişir)


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


#### Coupon Redemption Rate

**Tanım:** Dağıtılan kuponların kullanılma oranı

**Formül:**
```
Coupon Redemption % = (Kullanılan Kupon / Dağıtılan Kupon) × 100
```

**Hedef:** %15-25 arası


### 5. Kampanya KPI'ları

#### Campaign Response Rate

**Tanım:** Kampanya hedef kitlesinin kampanyaya katılım oranı

**Formül:**
```
Response Rate % = (Kampanyaya Katılan / Hedef Kitle) × 100
```

**Hedef:** %10-20 arası


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


#### First Contact Resolution (FCR)

**Tanım:** İlk temasta çözülen ticket oranı

**Formül:**
```
FCR % = (İlk Temasta Çözülen / Toplam Ticket) × 100
```

**Hedef:** %60 ve üzeri


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


*Bu doküman Aydınlı Grup CRM Operasyonları tarafından hazırlanmıştır.*  
*© 2025 Aydınlı Grup - Tüm hakları saklıdır.*




---

## SECTION 4: CRM-DATA-QUALITY-TR

﻿---
layout: default
title: "CRM Veri Kalitesi Yönetimi"
parent: CRM

## İçindekiler

1. [Amaç](#amaç)
2. [Kapsam](#kapsam)
3. [Tanımlar](#tanımlar)
4. [Sorumluluklar](#sorumluluklar)
5. [Veri Kalitesi İlkeleri](#veri-kalitesi-ilkeleri)
6. [Veri Doğrulama Kuralları](#veri-doğrulama-kuralları)
7. [Yaygın Veri Hataları](#yaygın-veri-hataları)
8. [Düzeltme Süreçleri](#düzeltme-süreçleri)
9. [Duplicate Yönetimi](#duplicate-yönetimi)
10. [KPI'lar](#kpılar)
11. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
12. [Mağaza İpuçları](#mağaza-ipuçları)
13. [Revizyon Geçmişi](#revizyon-geçmişi)


## Kapsam

### Bu Doküman Kimleri Kapsar?

| Rol | Sorumluluk |
|-----|------------|
| Mağaza Personeli | Doğru veri girişi yapmak |
| Mağaza Müdürü | Veri kalitesini denetlemek |
| Bölge Müdürü | Bölgesel veri kalitesini izlemek |
| CRM Merkez | Veri temizleme ve standardizasyon |
| IT Ekibi | Sistem doğrulama kuralları |

### Kapsanan Veriler

| Veri Alanı | Kritiklik | Doğrulama Seviyesi |
|------------|-----------|-------------------|
| Cep Telefonu | Yüksek | Otomatik + Manuel |
| E-posta | Yüksek | Otomatik |
| Ad Soyad | Yüksek | Manuel |
| Doğum Tarihi | Orta | Otomatik |
| Adres | Düşük | Manuel |
| Cinsiyet | Düşük | Manuel |


## Sorumluluklar

### Mağaza Personeli

| Görev | Detay | Sıklık |
|-------|-------|--------|
| Doğru giriş | Müşteri bilgilerini doğru girmek | Her işlemde |
| Doğrulama | Girilen verileri müşteriden teyit almak | Her işlemde |
| Güncelleme | Değişen bilgileri güncellemek | Talep üzerine |
| Raporlama | Hatalı veriyi bildirmek | Tespit halinde |

### Mağaza Müdürü

| Görev | Detay | Sıklık |
|-------|-------|--------|
| Denetim | Veri girişlerini kontrol etmek | Haftalık |
| Eğitim | Personeli veri kalitesi konusunda eğitmek | Sürekli |
| Düzeltme | Tespit edilen hataları düzeltmek | Anında |
| Raporlama | Veri kalitesi KPI'larını izlemek | Aylık |

### CRM Merkez

| Görev | Detay | Sıklık |
|-------|-------|--------|
| Toplu temizlik | Sistematik veri temizleme | Aylık |
| Duplicate yönetimi | Mükerrer kayıtları birleştirmek | Sürekli |
| Kural güncelleme | Doğrulama kurallarını güncellemek | İhtiyaç halinde |
| Analiz | Veri kalitesi trendlerini analiz etmek | Aylık |


## Veri Doğrulama Kuralları

### Telefon Numarası

| Kural | Geçerli | Geçersiz |
|-------|---------|----------|
| Format | 5XX XXX XXXX | 0532 123 4567 |
| Uzunluk | 10 hane | 9 veya 11 hane |
| Başlangıç | 5 ile başlamalı | 0 ile başlamamalı |
| Teklik | Benzersiz olmalı | Başka müşteride olmamalı |

**Sistem Doğrulaması:**
```
✓ 5321234567 → Geçerli
✗ 05321234567 → Geçersiz (11 hane)
✗ 4321234567 → Geçersiz (5 ile başlamıyor)
✗ 532123456 → Geçersiz (9 hane)
```

### E-posta Adresi

| Kural | Geçerli | Geçersiz |
|-------|---------|----------|
| Format | kullanici@domain.com | kullanici@domain |
| @ işareti | Zorunlu | Eksik olamaz |
| Domain | Geçerli domain | test, asdf |
| Teklik | Benzersiz olmalı | Başka müşteride olmamalı |

**Yaygın E-posta Hataları:**

| Hata | Örnek | Olası Doğru |
|------|-------|-------------|
| Türkçe karakter | ahmet.yılmaz@email.com | ahmet.yilmaz@email.com |
| Boşluk | ahmet yilmaz@email.com | ahmet.yilmaz@email.com |
| Eksik domain | ahmet@gmail | ahmet@gmail.com |
| Yanlış domain | ahmet@gmial.com | ahmet@gmail.com |

### Ad Soyad

| Kural | Doğru | Yanlış |
|-------|-------|--------|
| Büyük harf başlangıç | Ahmet Yılmaz | ahmet yılmaz |
| Tam ad | Ahmet | A. |
| Özel karakter yok | Ahmet Yılmaz | Ahmet Yılmaz!!! |
| Sayı yok | Ahmet Yılmaz | Ahmet123 |

**Standart Format:**
- Ad: İlk harf büyük, geri kalan küçük
- Soyad: İlk harf büyük, geri kalan küçük
- Birden fazla ad: Her kelimenin ilk harfi büyük

### Doğum Tarihi

| Kural | Geçerli | Geçersiz |
|-------|---------|----------|
| Format | GG/AA/YYYY | YYYY-AA-GG |
| Yaş | 16-100 arası | 5 yaş veya 120 yaş |
| Gelecek tarih | Olamaz | Gelecek tarih |
| Mantıksal | Gerçekçi | 01/01/1900 |


## Düzeltme Süreçleri

### 1. Mağaza Seviyesinde Düzeltme

**Müşteri talep ederse:**

**Adım 1:** Müşteri kimliğini doğrulayın

**Adım 2:** CRM'de müşteriyi bulun

**Adım 3:** "Düzenle" butonuna tıklayın

**Adım 4:** Hatalı alanı düzeltin

**Adım 5:** Değişikliği kaydedin

**Adım 6:** Müşteriye bilgi verin

### 2. Toplu Düzeltme (CRM Merkez)

Belirli paternler için toplu düzeltme yapılabilir:

| Patern | Düzeltme |
|--------|----------|
| 05XXXXXXXXX | Baştaki 0'ı kaldır |
| email@gmial.com | @gmail.com olarak düzelt |
| AHMET YILMAZ | Ahmet Yılmaz olarak formatla |

### 3. Düzeltme Talep Süreci

**Mağazanın kendisi düzeltemiyorsa:**

**Adım 1:** Ticket açın (Kategori: Veri Düzeltme)

**Adım 2:** Müşteri bilgilerini belirtin
- Customer ID
- Hatalı alan
- Doğru değer
- Kanıt (varsa)

**Adım 3:** CRM Merkez inceler ve düzeltir

**Adım 4:** Düzeltme bilgisi mağazaya iletilir


## Sık Karşılaşılan Sorunlar ve Çözümler

### Sorun 1: Müşteri Telefon Numarasını Değiştirmiş

**Durum:** Eski numara ile kayıtlı, yeni numara ile aranıyor.

**Çözüm:**
1. Eski numara ile kaydı bulun
2. Müşteri kimliğini doğrulayın
3. Telefon numarasını güncelleyin
4. Müşteriye onay verin


### Sorun 3: Duplicate Kayıt Şüphesi

**Durum:** Aynı müşteri farklı numaralarla geliyor.

**Çözüm:**
1. Her iki kaydı karşılaştırın
2. Müşteriden teyit alın
3. CRM Merkez'e merge talebi açın
4. Müşteriye süreç hakkında bilgi verin


## Mağaza İpuçları

### Doğru Veri Girişi İçin

| Yapın | Yapmayın |
|-------|----------|
| ✅ Telefonu müşteriden teyit alın | ❌ Tahmin etmeyin |
| ✅ E-postayı harf harf doğrulayın | ❌ Acele etmeyin |
| ✅ Kayıt önce mevcut müşteriyi arayın | ❌ Doğrudan yeni kayıt açmayın |
| ✅ Sahte bilgi yerine boş bırakın | ❌ aaa@aaa.com kabul etmeyin |
| ✅ Şüpheli duplicate'i bildirin | ❌ Görmezden gelmeyin |

### Veri Kalitesi Kontrol Listesi

**Her Müşteri Kaydında:**
- [ ] Telefon 10 hane ve 5 ile başlıyor mu?
- [ ] E-posta @ ve . içeriyor mu?
- [ ] Ad soyad doğru formatta mı?
- [ ] Müşteri zaten kayıtlı değil mi?
- [ ] KVKK izinleri alındı mı?

### Müşteriye Yaklaşım

**Doğru bilgi almak için:**
> "Doğum gününüzde size özel bir sürprizimiz olacak, bu yüzden doğum tarihinizi doğru almam önemli."

> "Size kampanyalardan haberdar edebilmemiz için e-posta adresinizi doğru kaydetmem gerekiyor. Harf harf söyler misiniz?"

**Bilgi vermek istemezse:**
> "Tabii ki, bu tamamen sizin tercihiniz. O alanı boş bırakıyorum."


*Bu doküman Aydınlı Grup CRM Operasyonları tarafından hazırlanmıştır.*  
*© 2025 Aydınlı Grup - Tüm hakları saklıdır.*




---

## SECTION 5: CRM-DO-AND-DONT-TR

﻿---
layout: default
title: "CRM Yapılması ve Yapılmaması Gerekenler"
parent: CRM

## İçindekiler

1. [Amaç](#amaç)
2. [Kapsam](#kapsam)
3. [Genel Kurallar](#genel-kurallar)
4. [Müşteri Kaydı](#müşteri-kaydı)
5. [Veri Güvenliği ve KVKK](#veri-güvenliği-ve-kvkk)
6. [Müşteri İletişimi](#müşteri-iletişimi)
7. [Loyalty ve Kampanyalar](#loyalty-ve-kampanyalar)
8. [Ticketing](#ticketing)
9. [Sistem Kullanımı](#sistem-kullanımı)
10. [Sorumluluklar](#sorumluluklar)
11. [İhlal Sonuçları](#ihlal-sonuçları)
12. [Revizyon Geçmişi](#revizyon-geçmişi)


## Kapsam

### Bu Doküman Kimleri Kapsar?

| Rol | Uyum Zorunluluğu |
|-----|------------------|
| Mağaza Personeli | Zorunlu |
| Mağaza Müdürü | Zorunlu + Denetim |
| Bölge Müdürü | Denetim |


## Müşteri Kaydı

### ✅ YAPIN

| Kural | Açıklama |
|-------|----------|
| ✅ Kayıt öncesi mevcut müşteriyi arayın | Duplicate önlemek için |
| ✅ Telefon numarasını doğrulayın | Hatalı veri önlemek için |
| ✅ E-postayı harf harf teyit edin | Bounce önlemek için |
| ✅ Müşteriden onay alarak kaydedin | KVKK uyumluluğu için |
| ✅ Bilgi vermek istemezse boş bırakın | Sahte veri yerine |
| ✅ Welcome bonusu müşteriye söyleyin | Memnuniyet için |

### ❌ YAPMAYIN

| Kural | Risk |
|-------|------|
| ❌ Doğrudan yeni kayıt açmayın | Duplicate oluşur |
| ❌ Telefonu tahmin etmeyin | Yanlış kişiye ulaşılır |
| ❌ aaa@aaa.com gibi sahte mail girmeyin | Veri kalitesi düşer |
| ❌ Doğum tarihini uydurma girmeyin | Yanlış kampanya gider |
| ❌ İzin almadan kayıt yapmayın | KVKK ihlali |
| ❌ Müşteriyi kayda zorlamayın | Müşteri kaybedersiniz |


## Müşteri İletişimi

### ✅ YAPIN

| Kural | Açıklama |
|-------|----------|
| ✅ Her müşteriye "Üye misiniz?" sorun | Eşleştirme için |
| ✅ Puanları ve kuponları hatırlatın | Müşteri avantajı için |
| ✅ Kampanyaları doğru aktarın | Güven için |
| ✅ Müşteri talebini dinleyin | Memnuniyet için |
| ✅ Profesyonel ve nazik olun | Marka imajı için |
| ✅ Şikayetleri ciddiye alın | Sadakat için |

### ❌ YAPMAYIN

| Kural | Risk |
|-------|------|
| ❌ Müşteriye baskı yapmayın | Müşteri kaybı |
| ❌ Yanlış bilgi vermeyin | Güven kaybı |
| ❌ Müşteriyle tartışmayın | İtibar kaybı |
| ❌ Kişisel iletişim bilgisi vermeyin | Profesyonellik |
| ❌ Müşteriye küçümseyici davranmayın | Şikayet riski |
| ❌ Başka departmanları suçlamayın | Kurumsal imaj |


## Ticketing

### ✅ YAPIN

| Kural | Açıklama |
|-------|----------|
| ✅ Her şikayeti ticket olarak kaydedin | Takip için |
| ✅ Doğru kategori ve öncelik seçin | Doğru yönlendirme için |
| ✅ Detaylı açıklama yazın | Çözüm için |
| ✅ Kanıt/belge ekleyin | Doğrulama için |
| ✅ Müşteriye ticket numarası verin | Takip için |
| ✅ SLA sürelerine dikkat edin | Uyumluluk için |
| ✅ Takip bilgisi verin | Müşteri memnuniyeti için |

### ❌ YAPMAYIN

| Kural | Risk |
|-------|------|
| ❌ Şikayeti kaydetmeden geçmeyin | Takip kaybı |
| ❌ Ticket'ı yanıtsız bırakmayın | SLA ihlali |
| ❌ Yanlış kategori seçmeyin | Gecikme |
| ❌ Eksik bilgi ile ticket açmayın | Çözüm gecikmesi |
| ❌ Müşteriye gerçekçi olmayan söz vermeyin | Güven kaybı |
| ❌ Çözülmeden ticket kapatmayın | Tekrar açılır |


## Önemli Uyarılar

### 🚨 KESİNLİKLE YASAK

Aşağıdaki eylemler **kesinlikle yasaktır** ve ciddi yaptırımlara tabidir:

| # | Eylem | Sonuç |
|---|-------|-------|
| 1 | Müşteri verilerini satmak/paylaşmak | İş akdi feshi + yasal işlem |
| 2 | Sahte müşteri kaydı oluşturmak | Disiplin + mali sorumluluk |
| 3 | Başkasının hesabıyla işlem yapmak | Disiplin işlemi |
| 4 | Sistem verilerini silmek/değiştirmek | İş akdi feshi |
| 5 | Yetkisiz indirim/kupon uygulamak | Mali sorumluluk |
| 6 | Müşteri şikayetini gizlemek | Disiplin işlemi |
| 7 | KVKK ihlali yapmak | Yasal yaptırım + tazminat |


## İhlal Sonuçları

### İhlal Seviyeleri

| Seviye | Örnek | Sonuç |
|--------|-------|-------|
| **Düşük** | Veri formatı hatası | Uyarı + düzeltme |
| **Orta** | Tekrarlayan kayıtsızlık | Yazılı uyarı |
| **Yüksek** | KVKK ihlali, veri paylaşımı | Disiplin işlemi |
| **Kritik** | Kasıtlı suistimal | İş akdi feshi + yasal işlem |

### İhlal Raporlama

İhlal tespit edildiğinde:
1. Durumu derhal mağaza müdürüne bildirin
2. Kanıtları koruyun
3. Mağaza müdürü bölge müdürüne raporlar
4. CRM Merkez bilgilendirilir


## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 01.12.2025 | İlk sürüm oluşturuldu | Aydınlı Grup |


---

## SECTION 6: CRM-LOYALTY-CAMPAIGNS-TR

﻿---
layout: default
title: "CRM Loyalty Programı ve Kampanya Yönetimi"
parent: CRM

## İçindekiler

1. [Amaç](#amaç)
2. [Kapsam](#kapsam)
3. [Tanımlar](#tanımlar)
4. [Sorumluluklar](#sorumluluklar)
5. [Loyalty Programı Yapısı](#loyalty-programı-yapısı)
6. [Puan Sistemi](#puan-sistemi)
7. [Kampanya Türleri](#kampanya-türleri)
8. [Kupon Yönetimi](#kupon-yönetimi)
9. [Süreç Adımları](#süreç-adımları)
10. [KPI'lar](#kpılar)
11. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
12. [Mağaza İpuçları](#mağaza-ipuçları)
13. [Revizyon Geçmişi](#revizyon-geçmişi)


## Kapsam

### Bu Doküman Kimleri Kapsar?

| Rol | Sorumluluk |
|-----|------------|
| Mağaza Personeli | Loyalty işlemlerini yürütmek |
| Mağaza Müdürü | Kampanya uygulamalarını denetlemek |
| Bölge Müdürü | Bölgesel performansı takip etmek |
| CRM Merkez | Kampanya oluşturma ve yönetimi |
| Pazarlama Ekibi | Kampanya stratejisi belirleme |

### Kapsanan Süreçler

1. Loyalty programına üyelik
2. Puan kazanma ve kullanma
3. Kupon oluşturma ve kullanma
4. Kampanya uygulama
5. Üyelik yönetimi
6. Raporlama ve analiz


## Sorumluluklar

### Mağaza Personeli

| Görev | Detay |
|-------|-------|
| Üyelik kaydı | Yeni müşterileri loyalty programına kaydetmek |
| Puan işleme | Satışlarda puan kazandırmak/kullandırmak |
| Kupon uygulama | Geçerli kuponları satışa uygulamak |
| Bilgilendirme | Müşteriyi kampanyalar hakkında bilgilendirmek |
| Sorun çözümü | Loyalty ile ilgili sorunları çözmek/yönlendirmek |

### Mağaza Müdürü

| Görev | Detay |
|-------|-------|
| Kampanya takibi | Aktif kampanyaların uygulanmasını denetlemek |
| Performans izleme | Mağaza loyalty KPI'larını izlemek |
| Eğitim | Personeli kampanyalar konusunda eğitmek |
| Raporlama | Kampanya performansını raporlamak |

### CRM Merkez

| Görev | Detay |
|-------|-------|
| Kampanya tasarımı | Kampanyaları oluşturmak ve yapılandırmak |
| Kupon üretimi | Toplu kupon oluşturmak |
| Sistem yönetimi | Loyalty sisteminin teknik yönetimi |
| Analiz | Kampanya etkinliğini analiz etmek |


## Puan Sistemi

### Puan Kazanma

| Koşul | Puan Oranı | Örnek |
|-------|------------|-------|
| Standart Alışveriş | 1 TL = 1 Puan | 500 TL = 500 Puan |
| Çarpanlı Kampanya (2x) | 1 TL = 2 Puan | 500 TL = 1.000 Puan |
| Çarpanlı Kampanya (3x) | 1 TL = 3 Puan | 500 TL = 1.500 Puan |
| Doğum Günü Alışverişi | 1 TL = 2 Puan | Doğum günü haftasında |

### Puan Kazanma Kuralları

| Kural | Açıklama |
|-------|----------|
| Eşleştirme zorunlu | Puan kazanmak için satış müşteriye eşleştirilmeli |
| İndirimli ürünler | İndirimli satış tutarı üzerinden puan hesaplanır |
| İade durumu | İade edilen ürünün puanı düşürülür |
| Geçerlilik | Puanlar 12 ay geçerlidir |

### Puan Kullanma

| Koşul | Değer | Kural |
|-------|-------|-------|
| Minimum Kullanım | 100 Puan | En az 100 puan kullanılabilir |
| Puan Değeri | 100 Puan = 10 TL | Her 100 puan 10 TL değerinde |
| Maksimum Kullanım | Sepet tutarının %50'si | Tek seferde en fazla sepet tutarının yarısı kadar |
| Nakit İadesi | Yok | Puanlar nakde çevrilemez |

### Puan Geçerliliği

```
┌─────────────────────────────────────────────────────────────────┐
│                    PUAN GEÇERLİLİK TAKVİMİ                      │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  Kazanım: Ocak 2025           →    Son Kullanım: Ocak 2026     │
│  Kazanım: Haziran 2025        →    Son Kullanım: Haziran 2026  │
│  Kazanım: Aralık 2025         →    Son Kullanım: Aralık 2026   │
│                                                                 │
│  ⚠️ Süresi dolan puanlar otomatik silinir                       │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```


## Kupon Yönetimi

### Kupon Özellikleri

| Özellik | Açıklama |
|---------|----------|
| Kupon Kodu | Benzersiz alfanumerik kod |
| İndirim Tipi | Yüzde (%) veya Tutar (TL) |
| Minimum Sepet | Kuponun geçerli olması için minimum tutar |
| Maksimum İndirim | İndirim üst limiti (yüzde kuponlarda) |
| Geçerlilik | Başlangıç - Bitiş tarihi |
| Kullanım Limiti | Tek kullanım / Çoklu kullanım |
| Geçerli Ürünler | Tüm ürünler / Belirli kategoriler |
| Hariç Ürünler | Kampanya dışı ürünler |

### Kupon Durumları

| Durum | Açıklama |
|-------|----------|
| Aktif | Kullanıma hazır |
| Kullanıldı | Zaten kullanılmış |
| Süresi Doldu | Geçerlilik tarihi geçmiş |
| İptal Edildi | Manuel olarak iptal edilmiş |
| Kilitli | Belirli koşul sağlanana kadar kilitli |

### Kupon Kullanım Kuralları

| Kural | Açıklama |
|-------|----------|
| Tek kupon | Bir satışta tek kupon kullanılabilir |
| Puan + Kupon | Aynı satışta hem puan hem kupon kullanılabilir |
| İndirimli ürün | İndirimli ürünlerde kupon geçerli olmayabilir |
| İade durumu | Kuponlu satış iadesinde kupon iade edilmez |


### 2. Satışta Puan Kazandırma

**Adım 1:** Satış işlemini başlatın

**Adım 2:** Müşteriyi telefon numarası ile arayın

**Adım 3:** Müşteriyi satışa eşleştirin

**Adım 4:** Satışı tamamlayın

**Adım 5:** Sistem otomatik puan hesaplar

**Adım 6:** Kazanılan puan fişte görünür

```
┌─────────────────────────────────────────┐
│           SATIŞ FİŞİ                    │
├─────────────────────────────────────────┤
│  Ürün: Polo Tişört         350,00 TL   │
│  Ürün: Keten Pantolon      650,00 TL   │
│  ─────────────────────────────────────  │
│  TOPLAM:                  1.000,00 TL   │
│  ─────────────────────────────────────  │
│  Kazanılan Puan:              1.000    │
│  Toplam Puan Bakiyesi:        3.500    │
└─────────────────────────────────────────┘
```


### 4. Kupon Kullanımı

**Adım 1:** Müşteriyi satışa eşleştirin

**Adım 2:** "Kuponlar" sekmesini açın

**Adım 3:** Müşterinin aktif kuponlarını görüntüleyin

**Adım 4:** Uygun kuponu seçin

**Adım 5:** Kupon koşullarını kontrol edin:
- [ ] Minimum sepet tutarı sağlandı mı?
- [ ] Ürünler kupon kapsamında mı?
- [ ] Kupon süresi geçerli mi?

**Adım 6:** "Kuponu Uygula" butonuna tıklayın

**Adım 7:** İndirimli tutarı doğrulayın

**Adım 8:** Ödemeyi alın




## Sık Karşılaşılan Sorunlar ve Çözümler

### Sorun 1: Kupon Çalışmıyor

**Kontrol Listesi:**
- [ ] Kupon süresi dolmuş mu?
- [ ] Minimum sepet tutarı sağlandı mı?
- [ ] Ürünler kupon kapsamında mı?
- [ ] Kupon daha önce kullanılmış mı?
- [ ] Müşteri eşleştirmesi yapıldı mı?

**Çözüm:** Koşulları kontrol edin, sağlanmıyorsa müşteriye açıklayın.


### Sorun 3: Müşteri Yanlış Puan Kullandı

**Çözüm:**
1. İşlemi iptal edin (mağaza müdürü onayı gerekir)
2. Yeni işlem oluşturun
3. Doğru puan miktarını kullandırın
4. Durumu ticket ile belgeleyin


## Mağaza İpuçları

### Loyalty Satışı Artırma

1. **Her müşteriye sorun:** "Aydınlı Club üyemiz misiniz?"
2. **Avantajları anlatın:** "Şu an 500 puan kazanabilirsiniz"
3. **Puanları hatırlatın:** "3.500 puanınız var, bugün kullanmak ister misiniz?"
4. **Kampanyaları duyurun:** "Üyelere özel %20 indirim var"

### Üyelik Kaydını Teşvik

| Yaklaşım | Örnek |
|----------|-------|
| Anlık avantaj | "Hemen üye olun, 50 TL'lik hoş geldin kuponu kazanın" |
| Gelecek avantaj | "Bir sonraki alışverişinizde kullanacağınız puanlar kazanın" |
| Özel gün | "Doğum gününüzde özel indirim kuponu gönderelim" |
| Erken erişim | "Yeni koleksiyonları herkesten önce görün" |

### Kampanya Uygulama Kuralları

| Yapın | Yapmayın |
|-------|----------|
| ✅ Kampanya koşullarını açıklayın | ❌ Koşulları gizlemeyin |
| ✅ Müşteriye en avantajlı seçeneği önerin | ❌ Müşteriyi yanıltmayın |
| ✅ Kupon/puan kombinasyonunu kontrol edin | ❌ Sistem dışı indirim uygulamayın |
| ✅ İşlem sonrası kazanımları bildirin | ❌ Geçersiz kupon kabul etmeyin |

### Sorunlu Durumlar

| Durum | Yaklaşım |
|-------|----------|
| Müşteri kampanyayı kaçırmış | Gelecek kampanyadan haberdar edin |
| Puan süresi dolmuş | Anlayışla karşılayın, yeni kazanım teşvik edin |
| Kupon çalışmıyor | Koşulları sabırla açıklayın |
| Sistem hatası | Özür dileyin, ticket açın, müşteriyi takip için bilgilendirin |


*Bu doküman Aydınlı Grup CRM Operasyonları tarafından hazırlanmıştır.*  
*© 2025 Aydınlı Grup - Tüm hakları saklıdır.*




---

## SECTION 7: CRM-OVERVIEW-TR

﻿---
layout: default
title: "CRM Genel Bakış"
parent: CRM

## İçindekiler

1. [Hızlı Bakış (EN/TR Toggle)](#hızlı-bakış-entr-toggle)
2. [Amaç](#amaç)
3. [Kapsam](#kapsam)
4. [Tanımlar](#tanımlar)
5. [Sorumluluklar](#sorumluluklar)
6. [CRM Sistem Mimarisi](#crm-sistem-mimarisi)
7. [Veri Akışı](#veri-akışı)
8. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
9. [Mağaza İpuçları](#mağaza-ipuçları)
10. [Revizyon Geçmişi](#revizyon-geçmişi)


## Amaç

Bu doküman, Aydınlı Grup bünyesindeki U.S. Polo Assn., Pierre Cardin ve Cacharel franchise mağazaları için CRM (Müşteri İlişkileri Yönetimi) sisteminin genel yapısını, hedeflerini ve işleyişini tanımlar.

### CRM Vizyonu

- Müşteri odaklı bir perakende deneyimi sunmak
- Müşteri verilerini güvenli ve etkin bir şekilde yönetmek
- Satış ve pazarlama stratejilerini müşteri davranışlarına göre optimize etmek
- Franchise ağı genelinde tutarlı bir müşteri deneyimi sağlamak

### CRM Hedefleri

| Hedef | Açıklama |
|-------|----------|
| Müşteri Tanıma | Her müşteriyi benzersiz olarak tanımlamak ve satın alma geçmişini takip etmek |
| Kişiselleştirme | Müşteri tercihlerine göre özelleştirilmiş iletişim ve teklifler sunmak |
| Sadakat Artırma | Loyalty programı ile müşteri bağlılığını güçlendirmek |
| Veri Kalitesi | Temiz, doğru ve güncel müşteri verileri tutmak |
| Uyumluluk | KVKK ve veri koruma düzenlemelerine tam uyum sağlamak |


## Tanımlar

### Temel CRM Terimleri

| Terim | Tanım |
|-------|-------|
| **CRM** | Customer Relationship Management - Müşteri İlişkileri Yönetimi. Müşteri verilerini toplama, analiz etme ve müşteri ilişkilerini yönetme sistemi. |
| **Müşteri Profili** | Bir müşteriye ait tüm demografik bilgiler, iletişim tercihleri ve satın alma geçmişinin bütünü. |
| **Loyalty Programı** | Müşteri sadakatini artırmak için tasarlanmış puan/kupon bazlı ödül sistemi. |
| **Opt-in** | Müşterinin pazarlama iletişimi almayı kabul etmesi. KVKK kapsamında açık rıza gerektirir. |
| **Opt-out** | Müşterinin pazarlama iletişiminden çıkma talebi. |
| **Ticket** | Müşteri şikayet, talep veya geri bildirimlerinin sistemde kayıt altına alındığı iş birimi. |
| **RFM Segmenti** | Recency (Yenilik), Frequency (Sıklık), Monetary (Değer) analizine göre oluşturulan müşteri segmenti. |
| **KVKK** | 6698 Sayılı Kişisel Verilerin Korunması Kanunu. |
| **Duplicate** | Aynı müşteriye ait birden fazla kayıt (mükerrer kayıt). |
| **Merge** | Mükerrer müşteri kayıtlarının tek bir profilde birleştirilmesi işlemi. |
| **POS** | Point of Sale - Satış noktası terminali. |
| **Customer 360** | Müşterinin tüm etkileşimlerini tek bir görünümde sunan ekran. |

### İletişim İzin Tipleri

| İzin Tipi | Açıklama | Varsayılan |
|-----------|----------|------------|
| SMS İzni | SMS ile pazarlama mesajı gönderimi | Kapalı |
| E-posta İzni | E-posta ile pazarlama iletişimi | Kapalı |
| Arama İzni | Telefon ile pazarlama araması | Kapalı |
| Veri İşleme İzni | Kişisel verilerin işlenmesi (zorunlu) | Zorunlu |


## CRM Sistem Mimarisi

### Sistem Bileşenleri

```
┌─────────────────────────────────────────────────────────────────┐
│                      CRM MERKEZİ SİSTEMİ                        │
├─────────────────────────────────────────────────────────────────┤
│  ┌───────────┐  ┌───────────┐  ┌───────────┐  ┌───────────┐    │
│  │ Müşteri   │  │ Kampanya  │  │ Loyalty   │  │ Ticketing │    │
│  │ Veritabanı│  │ Motoru    │  │ Modülü    │  │ Sistemi   │    │
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
     │  (Mağaza)   │   │  (Mağaza)   │   │  (Mağaza)   │
     └─────────────┘   └─────────────┘   └─────────────┘
```

### Entegrasyon Noktaları

| Sistem | Entegrasyon Tipi | Veri Akışı |
|--------|------------------|------------|
| POS Sistemi | Çift yönlü | Satış → CRM, Kupon → POS |
| E-ticaret | Çift yönlü | Online satış → CRM |
| SMS Gateway | Tek yönlü | CRM → SMS |
| E-posta Servisi | Tek yönlü | CRM → E-posta |
| Stok Yönetimi | Tek yönlü | Stok → CRM (ürün bilgisi) |




### Sorun 2: Mükerrer Müşteri Kaydı

**Belirti:** Aynı müşteri için birden fazla profil mevcut.

**Olası Nedenler:**
- Farklı telefon numaraları ile kayıt yapılmış
- Email ile kayıt vs telefon ile kayıt
- Manuel giriş hataları

**Çözüm:**
1. Duplicate merge talebini CRM Merkez'e iletin
2. Müşterinin doğru bilgilerini not alın
3. Yeni satışları en güncel profile kaydedin


### Sorun 4: Kupon Çalışmıyor

**Belirti:** Müşterinin kuponu POS'ta geçerli değil hatası veriyor.

**Olası Nedenler:**
- Kupon süresi dolmuş
- Minimum sepet tutarı sağlanmamış
- Kupon zaten kullanılmış
- Ürün kategorisi kupon kapsamı dışında

**Çözüm:**
1. Kupon detaylarını CRM'den kontrol edin
2. Koşulları müşteriye açıklayın
3. Alternatif kampanya varsa önerin


## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 01.12.2025 | İlk sürüm oluşturuldu | Aydınlı Grup |


---

## SECTION 8: CRM-STORE-CRM-CHECKLIST-TR

﻿---
layout: default
title: "Mağaza CRM Kontrol Listesi"
parent: CRM

## İçindekiler

1. [Amaç](#amaç)
2. [Kapsam](#kapsam)
3. [Günlük Kontrol Listesi](#günlük-kontrol-listesi)
4. [Haftalık Kontrol Listesi](#haftalık-kontrol-listesi)
5. [Aylık Kontrol Listesi](#aylık-kontrol-listesi)
6. [Satış Süreci Kontrol Listesi](#satış-süreci-kontrol-listesi)
7. [Müşteri Kaydı Kontrol Listesi](#müşteri-kaydı-kontrol-listesi)
8. [Sorumluluklar](#sorumluluklar)
9. [Mağaza İpuçları](#mağaza-ipuçları)
10. [Revizyon Geçmişi](#revizyon-geçmişi)


## Kapsam

### Bu Kontrol Listeleri Kimleri Kapsar?

| Rol | Kullanım |
|-----|----------|
| Mağaza Personeli | Günlük işlem kontrolleri |
| Mağaza Müdürü | Günlük/haftalık/aylık denetimler |
| Bölge Müdürü | Aylık uyumluluk kontrolü |


## Haftalık Kontrol Listesi

### Pazartesi - Hafta Başlangıcı

| Sıra | Görev | Sorumlu | Kontrol |
|------|-------|---------|---------|
| 1 | Geçen hafta performansını değerlendir | Mağaza Müdürü | ☐ |
| 2 | Haftalık hedefleri belirle | Mağaza Müdürü | ☐ |
| 3 | Ekiple performans toplantısı yap | Mağaza Müdürü | ☐ |
| 4 | Yeni kampanya duyurularını kontrol et | Mağaza Müdürü | ☐ |
| 5 | Veri kalitesi raporunu incele | Mağaza Müdürü | ☐ |

### Hafta İçi

| Sıra | Görev | Sorumlu | Sıklık | Kontrol |
|------|-------|---------|--------|---------|
| 1 | Duplicate şüphelerini kontrol et | Mağaza Müdürü | 2x/hafta | ☐ |
| 2 | Veri girişi kalitesini denetle | Mağaza Müdürü | 2x/hafta | ☐ |
| 3 | Ticket çözüm durumlarını takip et | Mağaza Müdürü | Günlük | ☐ |
| 4 | Personel CRM kullanımını gözlemle | Mağaza Müdürü | Sürekli | ☐ |

### Cuma - Hafta Sonu

| Sıra | Görev | Sorumlu | Kontrol |
|------|-------|---------|---------|
| 1 | Haftalık KPI performansını değerlendir | Mağaza Müdürü | ☐ |
| 2 | Çözülmemiş ticketları eskalasyon et | Mağaza Müdürü | ☐ |
| 3 | Hafta sonu kampanyalarını hazırla | Mağaza Müdürü | ☐ |
| 4 | Haftalık raporu bölge müdürüne gönder | Mağaza Müdürü | ☐ |


## Satış Süreci Kontrol Listesi

### Satış Öncesi

| Sıra | Görev | Kontrol |
|------|-------|---------|
| 1 | CRM sisteminde aktif oturum var mı? | ☐ |
| 2 | Güncel kampanyaları biliyor musunuz? | ☐ |
| 3 | POS ve CRM entegrasyonu çalışıyor mu? | ☐ |

### Satış Sırası

| Sıra | Görev | Kontrol |
|------|-------|---------|
| 1 | Müşteriye "Üye misiniz?" sorusu soruldu mu? | ☐ |
| 2 | Telefon numarası ile müşteri arandı mı? | ☐ |
| 3 | Müşteri bulunduysa satışa eşleştirildi mi? | ☐ |
| 4 | Müşteri bulunamadıysa yeni kayıt önerildi mi? | ☐ |
| 5 | Müşterinin aktif kuponu kontrol edildi mi? | ☐ |
| 6 | Puan bakiyesi müşteriye söylendi mi? | ☐ |
| 7 | Kupon/puan kullanımı soruldu mu? | ☐ |
| 8 | Geçerli kampanya uygulandı mı? | ☐ |

### Yeni Müşteri Kaydı (Gerekirse)

| Sıra | Görev | Kontrol |
|------|-------|---------|
| 1 | Önce mevcut müşteri arandı mı? | ☐ |
| 2 | Zorunlu alanlar doğru girildi mi? (Ad, Soyad, Telefon) | ☐ |
| 3 | Telefon formatı doğru mu? (5XXXXXXXXX) | ☐ |
| 4 | E-posta adresi doğrulandı mı? | ☐ |
| 5 | KVKK aydınlatma metni gösterildi/okundu mu? | ☐ |
| 6 | Veri işleme izni alındı mı? | ☐ |
| 7 | İletişim izinleri soruldu ve kaydedildi mi? | ☐ |
| 8 | Kayıt başarıyla tamamlandı mı? | ☐ |

### Satış Sonrası

| Sıra | Görev | Kontrol |
|------|-------|---------|
| 1 | Kazanılan puan müşteriye söylendi mi? | ☐ |
| 2 | Güncel kampanyalar hakkında bilgi verildi mi? | ☐ |
| 3 | Doğum günü yakınsa not edildi mi? | ☐ |
| 4 | Müşteri memnuniyeti soruldu mu? | ☐ |


## Ticket Açma Kontrol Listesi

| Sıra | Görev | Kontrol |
|------|-------|---------|
| 1 | Müşteri CRM'de tanımlandı mı? | ☐ |
| 2 | Doğru kategori seçildi mi? | ☐ |
| 3 | Doğru alt kategori seçildi mi? | ☐ |
| 4 | Öncelik seviyesi belirlendi mi? | ☐ |
| 5 | Konu başlığı açıklayıcı mı? | ☐ |
| 6 | Açıklama detaylı yazıldı mı? | ☐ |
| 7 | İlgili satış/ürün eklendi mi? | ☐ |
| 8 | Kanıt/belgeler yüklendi mi? (fotoğraf, fiş) | ☐ |
| 9 | Müşteri beklentisi not edildi mi? | ☐ |
| 10 | Müşteriye ticket numarası verildi mi? | ☐ |


## Mağaza İpuçları

### Kontrol Listesi Kullanım İpuçları

1. **Her gün aynı saatte kontrol yapın** - Rutin oluşturun
2. **Eksik maddeleri hemen tamamlayın** - Ertelemeyin
3. **Sorunları anında raporlayın** - Biriktirmeyin
4. **Ekiple paylaşın** - Herkes sorumluluğunu bilsin

### Başarı İçin Kritik Maddeler

| Kritik Madde | Neden Önemli |
|--------------|--------------|
| Müşteri eşleştirmesi | Penetration KPI'ı etkiler |
| KVKK izni | Yasal zorunluluk |
| Doğru veri girişi | Veri kalitesi KPI'ı etkiler |
| Ticket takibi | SLA uyumluluğu etkiler |

### Kontrol Listesi Arşivleme

- Günlük kontrol listeleri: 1 ay sakla
- Haftalık kontrol listeleri: 3 ay sakla
- Aylık kontrol listeleri: 1 yıl sakla


*Bu doküman Aydınlı Grup CRM Operasyonları tarafından hazırlanmıştır.*  
*© 2025 Aydınlı Grup - Tüm hakları saklıdır.*




---

## SECTION 9: CRM-STORE-USER-GUIDE-TR

﻿---
layout: default
title: "Mağaza CRM Kullanım Kılavuzu"
parent: CRM

## İçindekiler

1. [Amaç](#amaç)
2. [Kapsam](#kapsam)
3. [Tanımlar](#tanımlar)
4. [Sorumluluklar](#sorumluluklar)
5. [Süreç Adımları](#süreç-adımları)
6. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
7. [Mağaza İpuçları](#mağaza-ipuçları)
8. [Revizyon Geçmişi](#revizyon-geçmişi)


## Kapsam

### Bu Kılavuz Kimleri Kapsar?

| Rol | Kullanım Amacı |
|-----|----------------|
| Satış Danışmanı | Günlük CRM işlemlerini gerçekleştirmek |
| Kasiyer | Satış sırasında müşteri eşleştirmesi yapmak |
| Mağaza Müdürü | Ekibi denetlemek ve eğitmek |

### Kapsanan İşlemler

1. CRM sistemine giriş
2. Müşteri arama ve sorgulama
3. Yeni müşteri kaydı
4. Müşteri bilgisi güncelleme
5. Satışta müşteri eşleştirme
6. Kupon ve puan işlemleri
7. Müşteri profili görüntüleme


## Sorumluluklar

### Satış Danışmanı Görevleri

| Görev | Detay | Önem |
|-------|-------|------|
| Müşteri sorgusu | Her satışta müşteri araması yapmak | Zorunlu |
| Yeni kayıt | Sistemde olmayan müşteriyi kaydetmek | Zorunlu |
| KVKK onayı | İzin formunu imzalatmak | Zorunlu |
| Veri doğrulama | Girilen bilgilerin doğruluğunu teyit etmek | Zorunlu |
| Kupon kullanımı | Geçerli kuponları uygulamak | İsteğe bağlı |

### Mağaza Müdürü Görevleri

| Görev | Detay | Sıklık |
|-------|-------|--------|
| Eğitim takibi | Personelin CRM kullanımını izlemek | Sürekli |
| Hata düzeltme | Yanlış girişleri tespit ve düzeltmek | Günlük |
| Performans raporu | CRM eşleştirme oranını takip etmek | Günlük |


### 2. Müşteri Arama

#### 2.1 Hızlı Arama (Quick Search)

**Adım 1:** Ana ekranda arama kutusuna tıklayın

**Adım 2:** Aşağıdaki yöntemlerden birini kullanın:

| Arama Kriteri | Format | Örnek |
|---------------|--------|-------|
| Telefon | 10 hane (başında 0 olmadan) | 5321234567 |
| E-posta | tam@email.com | ahmet.yilmaz@email.com |
| Customer ID | 10 haneli numara | 1000045678 |

**Adım 3:** Enter tuşuna basın veya arama ikonuna tıklayın

**Adım 4:** Sonuçlar listesinden doğru müşteriyi seçin

#### 2.2 Gelişmiş Arama (Advanced Search)

**Adım 1:** Ana ekranda "Gelişmiş Arama" butonuna tıklayın

**Adım 2:** Aşağıdaki alanlardan bir veya birkaçını doldurun:

| Alan | Açıklama |
|------|----------|
| Ad | Müşteri adı (min. 3 karakter) |
| Soyad | Müşteri soyadı (min. 3 karakter) |
| Telefon | Kısmi veya tam numara |
| E-posta | Kısmi veya tam adres |
| Doğum Tarihi | GG/AA/YYYY formatında |
| Kayıt Tarihi Aralığı | Başlangıç - Bitiş tarihi |

**Adım 3:** "Ara" butonuna tıklayın

**Adım 4:** Sonuç listesinden doğru müşteriyi seçin


### 4. Müşteri Bilgisi Güncelleme

**Adım 1:** Müşteriyi arayın ve profilini açın

**Adım 2:** "Düzenle" veya "Güncelle" butonuna tıklayın

**Adım 3:** Değiştirilecek alanları güncelleyin

| Güncellenebilir Alanlar | Koşul |
|-------------------------|-------|
| Telefon numarası | Müşteri onayı ile |
| E-posta adresi | Müşteri onayı ile |
| Adres bilgileri | Müşteri onayı ile |
| İletişim izinleri | Müşteri talebi ile |
| Doğum tarihi | Kimlik ibrazı ile |

**Adım 4:** "Kaydet" butonuna tıklayın

**Adım 5:** Güncelleme onay mesajını bekleyin

> ⚠️ **Dikkat:** Ad, soyad ve TC kimlik numarası gibi temel bilgiler mağazadan değiştirilemez. Bu bilgilerin güncellenmesi için CRM Merkez'e talep açın.


### 6. Kupon ve Puan İşlemleri

#### 6.1 Kupon Kullanımı

**Adım 1:** Müşteriyi satışa eşleştirin

**Adım 2:** "Kuponlar" sekmesine gidin

**Adım 3:** Müşterinin aktif kuponlarını görüntüleyin

| Kupon Bilgisi | Açıklama |
|---------------|----------|
| Kupon Kodu | Benzersiz kupon numarası |
| İndirim Tipi | % veya TL |
| Geçerlilik | Son kullanma tarihi |
| Koşullar | Min. sepet, geçerli kategoriler |

**Adım 4:** Uygulanacak kuponu seçin

**Adım 5:** "Kuponu Uygula" butonuna tıklayın

**Adım 6:** İndirimli tutarı doğrulayın

**Adım 7:** Ödemeyi alın

#### 6.2 Puan Sorgulama

**Adım 1:** Müşteri profilini açın

**Adım 2:** "Loyalty" veya "Puanlar" sekmesine gidin

**Adım 3:** Aşağıdaki bilgileri görüntüleyin:

| Bilgi | Açıklama |
|-------|----------|
| Toplam Puan | Kullanılabilir puan bakiyesi |
| Kazanılan Puan | Toplam kazanılan puan |
| Harcanan Puan | Kullanılan puan |
| Puan Geçerliliği | Son kullanma tarihi |

#### 6.3 Puan Kazandırma

Puanlar satış sonrası otomatik olarak hesaplanır:

```
Kazanılan Puan = (Satış Tutarı × Puan Çarpanı)
```

Standart puan çarpanı: Her 1 TL = 1 Puan

> ⚠️ **Dikkat:** İade işlemlerinde kazanılan puanlar otomatik olarak düşürülür.




### Sorun 2: Müşteri Kaydı Başarısız

**Olası Nedenler ve Çözümler:**

| Hata Mesajı | Neden | Çözüm |
|-------------|-------|-------|
| "Telefon zaten kayıtlı" | Duplicate | Mevcut kaydı bulun |
| "Geçersiz telefon formatı" | Yanlış format | 5XXXXXXXXX formatında girin |
| "Zorunlu alan boş" | Eksik bilgi | Tüm zorunlu alanları doldurun |
| "KVKK onayı gerekli" | İzin eksik | Veri işleme iznini işaretleyin |


### Sorun 4: Müşteri Eşleştirmesi Yapılamıyor

**Çözüm:**
1. Satış iptal etmeden müşteri araması yapın
2. "Müşteri Ekle" butonunun aktif olduğundan emin olun
3. Arama sonucu boşsa yeni kayıt oluşturun
4. Satış tamamlandıktan sonra eşleştirme yapılamaz


## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 01.12.2025 | İlk sürüm oluşturuldu | Aydınlı Grup |


---

## SECTION 10: CRM-TICKETING-PROCESS-TR

﻿---
layout: default
title: "CRM Ticketing ve Müşteri Şikayet Yönetimi"
parent: CRM

## İçindekiler

1. [Amaç](#amaç)
2. [Kapsam](#kapsam)
3. [Tanımlar](#tanımlar)
4. [Sorumluluklar](#sorumluluklar)
5. [Süreç Adımları](#süreç-adımları)
6. [SLA Süreleri](#sla-süreleri)
7. [KPI'lar](#kpılar)
8. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
9. [Mağaza İpuçları](#mağaza-ipuçları)
10. [Revizyon Geçmişi](#revizyon-geçmişi)


## Kapsam

### Bu Doküman Kimleri Kapsar?

| Rol | Sorumluluk |
|-----|------------|
| Mağaza Personeli | Ticket açma ve ilk müdahale |
| Mağaza Müdürü | Ticket takibi ve eskalasyon |
| Bölge Müdürü | Kritik ticketların yönetimi |
| CRM Merkez | Merkezi çözüm ve kapanış onayı |
| Kalite Ekibi | Ürün kalitesi ile ilgili ticketlar |

### Kapsanan Süreçler

1. Ticket oluşturma
2. Ticket kategorilendirme
3. Ticket atama ve yönlendirme
4. Kanıt/belge ekleme
5. Ticket güncelleme
6. Ticket çözümleme
7. Ticket kapatma
8. Müşteri bilgilendirme


## Sorumluluklar

### Mağaza Personeli

| Görev | Detay |
|-------|-------|
| Ticket açma | Müşteri şikayetini sisteme girmek |
| Bilgi toplama | Sorunla ilgili tüm detayları almak |
| Kanıt ekleme | Fotoğraf, fiş, vb. belgeleri yüklemek |
| İlk müdahale | Mağaza seviyesinde çözülebilecek sorunları çözmek |
| Müşteriyi bilgilendirme | Süreç hakkında müşteriyi güncel tutmak |

### Mağaza Müdürü

| Görev | Detay |
|-------|-------|
| Ticket onayı | Açılan ticketları doğrulamak |
| Önceliklendirme | Ticketları önem sırasına göre sıralamak |
| Eskalasyon | Çözülemeyen ticketları üst seviyeye iletmek |
| Performans takibi | Mağaza ticket KPI'larını izlemek |
| Kapanış onayı | Çözülen ticketları kapatmak |

### CRM Merkez Ekibi

| Görev | Detay |
|-------|-------|
| Merkezi çözüm | Mağaza seviyesinde çözülemeyen ticketları çözmek |
| Koordinasyon | İlgili departmanlarla iletişim kurmak |
| SLA takibi | Tüm ticketların SLA'da kalmasını sağlamak |
| Trend analizi | Tekrarlayan sorunları raporlamak |
| Politika güncelleme | Süreçleri iyileştirmek |


### 2. Ticket İşleme Akışı

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   Ticket    │────▶│   Mağaza    │────▶│   CRM       │────▶│   İlgili    │
│   Açılır    │     │   İnceleme  │     │   Merkez    │     │   Departman │
└─────────────┘     └─────────────┘     └─────────────┘     └─────────────┘
       │                   │                   │                   │
       ▼                   ▼                   ▼                   ▼
   Açık              Mağazada            Merkez'e           Departman
   Durumu            Çözüldü?            Eskalasyon         Yanıtı
                         │                   │                   │
                    Evet / Hayır        Atama/Yönlendirme    Çözüm
                         │                   │                   │
                         ▼                   ▼                   ▼
                  ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
                  │   Çözüldü   │     │   İşlemde   │     │   Çözüldü   │
                  │   Durumu    │     │   Durumu    │     │   Durumu    │
                  └─────────────┘     └─────────────┘     └─────────────┘
                         │                                       │
                         └───────────────────────────────────────┘
                                           │
                                           ▼
                                   ┌─────────────┐
                                   │  Müşteri    │
                                   │  Onayı      │
                                   └─────────────┘
                                           │
                                           ▼
                                   ┌─────────────┐
                                   │  Ticket     │
                                   │  Kapatılır  │
                                   └─────────────┘
```


### 4. Ticket Güncelleme

**Her güncellemede kaydedilecekler:**
- Yapılan işlem
- İletişim detayları (kim, ne zaman, nasıl)
- Sonraki adım
- Tahmini çözüm süresi

**Güncelleme Formatı:**
```
[Tarih - Saat] [Kullanıcı]
İşlem: [Yapılan işlem açıklaması]
Sonuç: [İşlemin sonucu]
Sonraki Adım: [Plananan aksiyon]
```


## SLA Süreleri

### Kategori Bazlı SLA

| Kategori | Öncelik | İlk Yanıt | Çözüm |
|----------|---------|-----------|-------|
| Ürün Kalitesi | Normal | 4 saat | 48 saat |
| Ürün Değişim | Normal | 2 saat | 24 saat |
| İade Talebi | Normal | 2 saat | 48 saat |
| Fiyat/Kampanya | Yüksek | 1 saat | 24 saat |
| Mağaza Hizmeti | Normal | 4 saat | 48 saat |
| Loyalty/Puan | Normal | 2 saat | 24 saat |

### VIP Müşteri SLA

VIP müşterilerde tüm SLA süreleri %50 kısaltılır.

| Normal SLA | VIP SLA |
|------------|---------|
| 48 saat | 24 saat |
| 24 saat | 12 saat |
| 4 saat | 2 saat |


## KPI'lar

### Ticket Performans KPI'ları

| KPI | Tanım | Formül | Hedef |
|-----|-------|--------|-------|
| **First Contact Resolution (FCR)** | İlk temasta çözülen ticket oranı | (İlk Temasta Çözülen / Toplam Ticket) × 100 | >60% |
| **SLA Compliance** | SLA'da kapatılan ticket oranı | (SLA İçinde Kapatılan / Toplam Kapatılan) × 100 | >95% |
| **Average Resolution Time** | Ortalama çözüm süresi | Toplam Çözüm Süresi / Kapatılan Ticket | <36 saat |
| **Customer Satisfaction (CSAT)** | Müşteri memnuniyet puanı | Memnun Müşteri / Anket Yanıtı × 100 | >85% |
| **Reopened Ticket Rate** | Tekrar açılan ticket oranı | (Tekrar Açılan / Toplam Kapatılan) × 100 | <5% |
| **Ticket per Transaction** | İşlem başına ticket oranı | Toplam Ticket / Toplam Satış × 1000 | <2‰ |

### Hesaplama Örnekleri

**FCR Hesaplama:**
```
İlk temasta çözülen ticket: 150
Toplam ticket: 250
FCR = (150 / 250) × 100 = %60
```

**SLA Compliance Hesaplama:**
```
SLA içinde kapatılan: 190
Toplam kapatılan: 200
SLA Compliance = (190 / 200) × 100 = %95
```


### Sorun 2: Müşteri Kanıt Sağlayamıyor

**Durum:** Müşteri fişi kaybetmiş veya ürünü getirmemiş.

**Çözüm:**
1. CRM'den satış geçmişini kontrol edin
2. Ödeme yöntemine göre banka ekstresini talep edin
3. Mağaza güvenlik kamera kaydını kontrol edin
4. Durumu ticket notlarına kaydedin
5. Mağaza müdürü onayı ile işlem yapın


### Sorun 4: SLA Süresi Dolmak Üzere

**Durum:** Ticket çözüme ulaşmadı, SLA dolacak.

**Çözüm:**
1. Hemen eskalasyon yapın
2. Müşteriyi bilgilendirin: "Konunuz üst yönetime iletildi"
3. Ticket notlarına gecikme nedenini yazın
4. Tahmini yeni süreyi belirtin
5. Öncelik seviyesini yükseltin


## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 01.12.2025 | İlk sürüm oluşturuldu | Aydınlı Grup |


---
