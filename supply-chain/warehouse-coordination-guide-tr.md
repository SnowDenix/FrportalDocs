# Depo Koordinasyon Kılavuzu – TR

> **Son Güncelleme:** 01 Aralık 2025 | **Versiyon:** 1.0  
> **Hazırlayan:** Aydınlı Grup  
> **Markalar:** U.S. Polo Assn., Pierre Cardin, Cacharel

---

## İçindekiler

1. [Amaç](#amaç)
2. [Kapsam](#kapsam)
3. [Tanımlar](#tanımlar)
4. [Sorumluluklar](#sorumluluklar)
5. [Süreç Adımları](#süreç-adımları)
6. [Standartlar ve Kurallar](#standartlar-ve-kurallar)
7. [Kontrol Listeleri](#kontrol-listeleri)
8. [Örnekler / Senaryolar](#örnekler--senaryolar)
9. [KPI'lar](#kpilar)
10. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
11. [Revizyon Geçmişi](#revizyon-geçmişi)

---

## Amaç

Bu doküman, franchise mağazaları için depo koordinasyonu hakkında kapsamlı rehberlik sağlamaktadır. Mağazalar ve dağıtım merkezi arasındaki etkili koordinasyon, sorunsuz tedarik zinciri operasyonları, zamanında sipariş karşılama ve optimal envanter yönetimini sağlar.

### Temel Hedefler

| Hedef | Etki |
|-------|------|
| **Net İletişim** | Yanlış anlaşılmaları azalt |
| **Verimli Operasyonlar** | Gecikmeleri minimize et |
| **Doğru Karşılama** | Hataları azalt |
| **Zamanında Çözüm** | Hızlı sorun işleme |
| **Performans Takibi** | Sürekli iyileştirme |

---

## Kapsam

### Dağıtım Merkezi Ağı

| DC Lokasyonu | Kapsam | Fonksiyon |
|--------------|--------|-----------|
| **İstanbul (Ana)** | Türkiye, Avrupa, MENA | Birincil DC |
| **Bölgesel Hublar** | Yerel pazarlar | İkincil dağıtım |
| **Partner DC** | Amerika, APAC | Üçüncü parti lojistik |

### Depo Hizmetleri

| Hizmet | Açıklama | Uygunluk |
|--------|----------|----------|
| **Sipariş Karşılama** | Düzenli yenileme | Hafta içi |
| **Acil Siparişler** | Hızlı sevkiyatlar | Talep üzerine 7/24 |
| **İade İşleme** | İade ürün işleme | Hafta içi |
| **Onarım/Düzeltme** | Ürün onarımları | Randevuyla |
| **Envanter Sorguları** | Stok mevcudiyet kontrolleri | Hafta içi |

---

## Tanımlar

| Terim (EN) | Terim (TR) | Tanım |
|------------|------------|-------|
| DC | Dağıtım Merkezi | Distribution Center |
| WMS | Depo Yönetim Sistemi | Warehouse Management System |
| Pick & Pack | Toplama ve Paketleme | Sipariş hazırlama süreci |
| Allocation | Tahsis | Mağazalara stok dağılımı |
| Cross-docking | Çapraz Yükleme | Depolamadan doğrudan transfer |
| Staging | Hazırlama | Sevkiyat öncesi hazırlık alanı |
| Put-away | Yerleştirme | Malları depoya yerleştirme |
| Cycle Count | Döngüsel Sayım | Periyodik envanter doğrulama |

---

## Sorumluluklar

### Mağaza Ekibi

| Sorumluluk | Standart |
|------------|----------|
| Doğru siparişler gönder | Programa göre |
| Teslimat tercihlerini ilet | Önceden |
| Kabul sorunlarını raporla | 24 saat içinde |
| Envanter geri bildirimi sağla | Gerektiğinde |
| İadeleri koordine et | Prosedüre göre |

### Bölge Müdürü

| Sorumluluk | Standart |
|------------|----------|
| Bölgesel koordinasyonu denetle | Sürekli |
| Depo sorunlarını eskalasyon yap | Gerektiğinde |
| Bölgesel tahsisleri optimize et | Aylık |
| Depo performansını incele | Aylık |

### Merkez Depo Ekibi

| Sorumluluk | Standart |
|------------|----------|
| Siparişleri doğru işle | 24-48 saat |
| İletişim kanallarını sürdür | İş saatleri |
| Mağaza sorgularını çöz | Aynı gün |
| Karşılama KPI'larını izle | Günlük |
| Taşıyıcılarla koordine ol | Sürekli |

---

## Süreç Adımları

### Siparişten Teslimata Süreci

```
SİPARİŞTEN TESLİMATA İŞ AKIŞI

MAĞAZA                              DEPO
┌─────────────────┐           ┌─────────────────┐
│ Sipariş Gönder  │ ────────► │ Sipariş Al      │
│ B2B Portalı     │           │ WMS'de          │
└─────────────────┘           └────────┬────────┘
                                       │
                                       ▼
                              ┌─────────────────┐
                              │ Sipariş İncele  │
                              │ - Stok kontrol  │
                              │ - Miktar doğrula│
                              │ - Tahsis et     │
                              └────────┬────────┘
                                       │
                                       ▼
┌─────────────────┐           ┌─────────────────┐
│ Onay Al         │ ◄──────── │ Topla & Paketle │
│                 │           │ - Ürünleri topla│
│                 │           │ - Kalite kontrol│
└─────────────────┘           │ - Paketle       │
                              └────────┬────────┘
                                       │
                                       ▼
                              ┌─────────────────┐
                              │ Sevkiyat        │
                              │ - Belge oluştur │
                              │ - Taşıyıcı al   │
                              └────────┬────────┘
                                       │
                                       ▼
┌─────────────────┐           ┌─────────────────┐
│ Al ve Doğrula   │ ◄──────── │ Transit         │
│ Teslimat        │           │ - Takip         │
└────────┬────────┘           └─────────────────┘
         │
         ▼
┌─────────────────┐
│ Tamamla         │
│ - Sistemi güncelle│
│ - Kabulü onayla │
└─────────────────┘
```

### İletişim Kanalları

```
İLETİŞİM AKIŞI

STANDART SORGULAR
Mağaza → B2B Portal bileti → Depo Yanıtı (24 saat)

ACİL KONULAR
Mağaza → Telefon/WhatsApp → Depo (2 saat)

BÖLGESEL ESKALASYON
Mağaza → Bölge Müdürü → Merkez Tedarik Zinciri (4 saat)

SİSTEM SORUNLARI
Mağaza → IT Yardım Masası → Çözüm (4 saat)
```

---

## Standartlar ve Kurallar

### İletişim Standartları

| Standart | Gereksinim |
|----------|------------|
| **Yanıt Süresi** | Standart: 24 saat, Acil: 2 saat |
| **İletişim Kanalı** | Standart için B2B Portal, Acil için Telefon |
| **Dokümantasyon** | Tüm sorgular kaydedilir |
| **Takip** | Çözüme kadar |
| **Eskalasyon** | Tanımlı süreçe göre |

### Sipariş İşleme Standartları

| Standart | Hedef |
|----------|-------|
| **Sipariş İşleme** | 24-48 saat içinde |
| **Toplama Doğruluğu** | ≥%99.5 |
| **Paketleme Kalitesi** | Standarda %100 |
| **Zamanında Sevk** | ≥%98 |
| **Dokümantasyon** | %100 doğru |

### Depo Çalışma Saatleri

| Gün | Saatler | Hizmetler |
|-----|---------|-----------|
| Pazartesi-Cuma | 08:00-18:00 | Tam hizmet |
| Cumartesi | 08:00-13:00 | Sınırlı hizmet |
| Pazar | Kapalı | Sadece acil |

---

## Kontrol Listeleri

### Haftalık Koordinasyon Kontrol Listesi

```
HAFTALIK DEPO KOORDİNASYONU
Hafta: _____________ Mağaza: _____________

SİPARİŞ YÖNETİMİ
□ Haftalık sipariş zamanında gönderildi
□ Sipariş onayı alındı
□ Düzeltmeler iletildi
□ Teslimat programı onaylandı

ENVANTER İLETİŞİMİ
□ Stok sorunları depoya raporlandı
□ Tahsis soruları ele alındı
□ Transfer ihtiyaçları iletildi
□ İadeler işlendi

SORUN TAKİBİ
□ Açık biletler incelendi
□ Bekleyen sorunlar takip edildi
□ Çözülen sorunlar onaylandı
□ Yeni sorunlar belgelendi

PERFORMANS İNCELEME
□ Teslimat doğruluğu incelendi
□ Gecikmeler not edildi
□ Kalite sorunları raporlandı
□ Geri bildirim sağlandı

Tamamlayan: _____________
Tarih: _____________
```

### Sorun Eskalasyon Kontrol Listesi

```
DEPO SORUN ESKALASYONU
Tarih: _____________ Sorun #: _____________

SORUN BELİRLEME
□ Sorun net açıklandı
□ Etki değerlendirildi
□ Aciliyet belirlendi
□ Kanıt toplandı (fotoğraflar, belgeler)

İLK İLETİŞİM
□ Depoyla uygun kanal üzerinden iletişim kuruldu
□ Sorun detayları sağlandı
□ Bilet numarası alındı
□ Beklenen çözüm süresi not edildi

TAKİP
□ Takip planlandı
□ Durum kontrol edildi
□ Güncellemeler belgelendi
□ Gerekirse eskalasyon tetiklendi

ÇÖZÜM
□ Çözüm uygulandı
□ Onay alındı
□ Dokümantasyon tamamlandı
□ Önleyici tedbirler not edildi

Sorun Türü: _____________
Çözüm Süresi: _____________
Sonuç: _____________
```

---

## Örnekler / Senaryolar

### Senaryo 1: Standart Sipariş Sorgusu

**Durum:** Mağaza sipariş durumunu kontrol etmek istiyor

**Süreç:**
```
1. B2B Portalına giriş yap
2. Sipariş Geçmişine git
3. Sipariş numarasını bul
4. Durumu kontrol et:
   - Beklemede → İşleme sırasında
   - İşleniyor → Toplanıyor/paketleniyor
   - Sevk edildi → Transit (takip için tıkla)
   - Teslim edildi → Kabulü onayla
5. Soru varsa bilet gönder
6. Yanıt bekle (24 saat)
```

---

### Senaryo 2: Acil Stok Mevcudiyet Kontrolü

**Durum:** Müşteri mağazada olmayan ürün istiyor

**Süreç:**
```
1. Sistemde bölgesel envanteri kontrol et
2. Yerel olarak mevcut değilse depoyla iletişim kur
3. Depo yardım hattını ara (acil)
4. Şunları sağla:
   - SKU/ürün kodu
   - İhtiyaç duyulan miktar
   - Aciliyet seviyesi
5. Depo DC stoğunu kontrol eder
6. Mevcutsa:
   - Hızlandırılmış sevkiyat ayarla
   - Müşteriye ETA'yı onayla
7. Mevcut değilse:
   - Alternatif seçenekleri kontrol et
   - Müşteriye ilet
```

---

### Senaryo 3: Kalite Sorunu Raporlama

**Durum:** Kalite kusurlu ürünler alındı

**Süreç:**
```
1. Kusurlu ürünleri ayır
2. Tüm kusurları fotoğrafla
3. Belgele:
   - Sipariş/teslimat numarası
   - Etkilenen SKU'lar
   - Kusurlu miktar
   - Kusur açıklaması
4. B2B Portalı üzerinden kalite raporu gönder
5. Fotoğrafları ekle
6. Depo yanıtını bekle
7. Şunlar için talimatları izle:
   - DC'ye iade
   - Yerel imha
   - Kredi/değiştirme
```

---

### Senaryo 4: Teslimat Programı Değişikliği

**Durum:** Teslimat zamanını değiştirmek gerekiyor

**Süreç:**
```
1. Mevcut teslimat programını kontrol et
2. En az 48 saat önce depoyla iletişim kur
3. Program değişikliği talep et:
   - B2B Portalı (tercih edilen)
   - Telefon (acil)
4. Şunları sağla:
   - Sipariş numarası
   - Mevcut teslimat tarihi
   - Talep edilen yeni tarih/saat
   - Değişiklik nedeni
5. Onay al
6. Mağaza programını güncelle
```

---

## KPI'lar

### Depo Performans Metrikleri

| KPI | Formül | Hedef | Sıklık |
|-----|--------|-------|--------|
| **Sipariş Doğruluğu** | Doğru siparişler / Toplam | ≥%99 | Haftalık |
| **Zamanında Sevkiyat** | Zamanında / Toplam | ≥%98 | Haftalık |
| **Sorgu Yanıt Süresi** | Ort yanıt saati | <24 saat | Haftalık |
| **Sorun Çözümü** | SLA içinde çözülen / Toplam | ≥%95 | Aylık |
| **Toplama Doğruluğu** | Doğru toplamalar / Toplam | ≥%99.5 | Günlük |

### Performans Panosu

```
┌─────────────────────────────────────────────────────────────┐
│              DEPO KOORDİNASYON PANOSU                       │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  Sipariş Doğruluğu     [████████████████████░░] %99        │
│  Hedef: ≥%99           ✓ KARŞILIYOR                         │
│                                                             │
│  Zamanında Sevkiyat    [████████████████████░░] %98        │
│  Hedef: ≥%98           ✓ KARŞILIYOR                         │
│                                                             │
│  Ort Yanıt Süresi      [████████████████░░░░░░] 18 saat    │
│  Hedef: <24 saat       ✓ HEDEF İÇİNDE                       │
│                                                             │
│  Sorun Çözümü          [██████████████████████░░] %96      │
│  Hedef: ≥%95           ✓ AŞIYOR                             │
│                                                             │
│  Bu Haftanın Aktivitesi:                                    │
│  - İşlenen siparişler: 45                                   │
│  - İşlenen sorgular: 12                                     │
│  - Çözülen sorunlar: 8                                      │
│  - Bekleyen sorunlar: 2                                     │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## Sık Karşılaşılan Sorunlar ve Çözümler

### Sorun 1: Sipariş Gecikmeleri

**Problem:** Siparişler beklenenden uzun sürüyor

**Çözümler:**
- Depo kapasitesini/birikmeyi kontrol et
- Siparişleri daha erken gönder
- Acilse öncelikli sevkiyat kullan
- Gecikmeleri müşterilere ilet
- Envanter tamponu planla

---

### Sorun 2: Stok Tahsis Sorunları

**Problem:** Beklenen tahsisi almıyor

**Çözümler:**
- Tahsis kriterlerini incele
- Bölge Müdürüyle iletişim kur
- Gerekçeyle tahsis itirazı gönder
- Alternatif kaynakları değerlendir
- Diğer mağazalardan transfer talep et

---

### Sorun 3: İletişim Kopukluğu

**Problem:** Depodan yanıt alamıyor

**Çözümler:**
- Doğru kanal kullanıldığını doğrula
- Portalde bilet durumunu kontrol et
- Eskalasyon sürecine göre takip et
- Bölge Müdürüyle iletişim kur
- Tüm girişimleri belgele

---

### Sorun 4: Tekrarlayan Kalite Sorunları

**Problem:** Tutarlı ürün kalite problemleri

**Çözümler:**
- Tüm sorunları sistematik belgele
- Trend raporu derle
- Resmi kalite şikayeti gönder
- Tedarikçi araştırması talep et
- Gelen ürün incelemesi uygula

---

## Depo İletişim Dizini

### Acil İletişimler

| Fonksiyon | İletişim | Saatler |
|-----------|----------|---------|
| **Acil Siparişler** | +90 XXX XXX XXXX | 7/24 |
| **Teslimat Sorunları** | +90 XXX XXX XXXX | 08:00-20:00 |
| **Eskalasyon Hattı** | +90 XXX XXX XXXX | İş saatleri |

---

## En İyi Uygulamalar

### Etkili İletişim

1. **Net ve Spesifik Ol**
   - Sipariş/referans numaralarını sağla
   - Tüm ilgili detayları dahil et
   - Destekleyici dokümantasyon ekle

2. **Doğru Kanalı Kullan**
   - Standart: B2B Portalı
   - Acil: Telefon
   - Karmaşık: Takipli e-posta

3. **Her Şeyi Belgele**
   - Bilet numaralarını kaydet
   - Konuşma detaylarını not et
   - Tüm yazışmaları dosyala

4. **Tutarlı Takip Et**
   - Durumu düzenli kontrol et
   - Gerektiğinde eskalasyon yap
   - Çözümü onayla

---

## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 2025-12-01 | İlk versiyon oluşturuldu | Aydınlı Grup Tedarik Zinciri |

---

*Bu doküman Aydınlı Grup Tedarik Zinciri Ekibi tarafından hazırlanmıştır.*  
*© 2025 Aydınlı Grup - Tüm hakları saklıdır.*

