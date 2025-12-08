---
layout: default
title: "Sipariş Yönetimi Kılavuzu – TR"
parent: Supply Chain
---

# Sipariş Yönetimi Kılavuzu – TR

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

Bu doküman, franchise mağazaları için sipariş yönetimi süreçleri hakkında kapsamlı rehberlik sağlamaktadır. Etkili sipariş yönetimi, optimal envanter seviyelerini sağlar, stoksuzluğu minimize eder, fazla stoğu azaltır ve müşteriler için sürekli ürün bulunabilirliğini korur.

### Sipariş Yönetimi Misyonu

"Doğru ve zamanında sipariş vererek doğru ürünlerin doğru zamanda bulunmasını sağlamak."

### Temel Hedefler

| Hedef | Etki |
|-------|------|
| **Envanter Optimizasyonu** | Stok seviyelerini dengele |
| **Talep Karşılama** | Müşteri ihtiyaçlarını karşıla |
| **Maliyet Kontrolü** | Taşıma maliyetlerini minimize et |
| **Verimlilik** | Süreçleri optimize et |
| **Doğruluk** | Sipariş hatalarını azalt |

---

## Kapsam

### Sipariş Türleri

| Sipariş Türü | Açıklama | Zamanlama |
|--------------|----------|-----------|
| **Sezon Siparişi** | Sezon öncesi toplu sipariş | 4-6 ay önceden |
| **Yenileme Siparişi** | Düzenli stok tazeleme | Haftalık/İki haftalık |
| **Özel Sipariş** | Müşteriye özel talepler | Gerektiğinde |
| **Transfer Siparişi** | Mağazalar arası hareketler | Gerektiğinde |
| **Acil Sipariş** | Acil stok ihtiyaçları | Aynı gün |

### Sistem Erişimi

| Sistem | Amaç | Erişim |
|--------|------|--------|
| **B2B Portalı** | Sipariş gönderimi | Tüm mağazalar |
| **ERP Sistemi** | Envanter takibi | Müdür seviyesi |
| **WMS** | Depo durumu | Sadece görüntüleme |
| **Takip Portalı** | Sevkiyat takibi | Tüm mağazalar |

---

## Tanımlar

| Terim (EN) | Terim (TR) | Tanım |
|------------|------------|-------|
| PO | Satınalma Siparişi | Purchase Order |
| SKU | Stok Kodu | Stok Tutma Birimi |
| MOQ | Minimum Sipariş | Minimum Sipariş Miktarı |
| Lead Time | Tedarik Süresi | Siparişten teslimata süre |
| Reorder Point | Yeniden Sipariş Noktası | Yeniden siparişi tetikleyen seviye |
| Safety Stock | Güvenlik Stoğu | Tampon envanter |
| Open-to-Buy | Satın Alma Bütçesi | Satın alma bütçesi |
| Allocation | Tahsis | Stok dağılımı |
| Back Order | Bekleyen Sipariş | Karşılanmamış sipariş |
| Fill Rate | Doldurma Oranı | Sipariş tamamlanma yüzdesi |

---

## Sorumluluklar

### Mağaza Personeli

| Sorumluluk | Standart |
|------------|----------|
| Stok seviyelerini izle | Günlük |
| Düşük stok ürünlerini raporla | Hemen |
| Sipariş önerileri hazırla | Haftalık |
| Alınan siparişleri doğrula | Aynı gün |
| Envanter sistemini güncelle | Gerçek zamanlı |

### Mağaza Müdürü

| Sorumluluk | Standart |
|------------|----------|
| Sipariş gönderimlerini onayla | Son tarihten önce |
| Sipariş bütçesini yönet | Tahsis dahilinde |
| Sipariş geçmişini incele | Haftalık |
| Bölge ile koordine ol | Gerektiğinde |
| Sipariş doğruluğunu sağla | Gönderim başına |

### Bölge Müdürü

| Sorumluluk | Standart |
|------------|----------|
| Bölgesel siparişleri denetle | Haftalık inceleme |
| Bölgesel envanteri dengele | Aylık |
| Özel siparişleri onayla | 48 saat içinde |
| Transferleri koordine et | Gerektiğinde |
| Bölgesel performansı izle | Aylık |

### Merkez Tedarik Zinciri

| Sorumluluk | Standart |
|------------|----------|
| Siparişleri işle | 24 saat dönüş |
| Tahsisleri yönet | Politikaya göre |
| Tedarikçilerle koordine ol | Sürekli |
| Sistem bakımı | Sürekli |
| Performans raporlaması | Aylık |

---

## Süreç Adımları

### Düzenli Yenileme Sipariş Süreci

```
YENİLEME SİPARİŞ SÜRECİ

ADIM 1: ENVANTER İNCELEME
├── Envanter raporu çalıştır
├── Yeniden sipariş noktasının altındaki ürünleri belirle
├── Satış hızını incele
├── Yaklaşan promosyonları kontrol et
└── Sezonluk faktörleri değerlendir

ADIM 2: SİPARİŞ HAZIRLIĞI
├── Gerekli miktarları hesapla
├── Beden oranlarını incele
├── Minimum sipariş miktarlarını kontrol et
├── Tedarik sürelerini değerlendir
└── Bütçe uygunluğunu doğrula

ADIM 3: SİPARİŞ GİRİŞİ
├── B2B portalına giriş yap
├── Ürün ve miktarları seç
├── Teslimat adresini doğrula
├── Gerekirse özel talimatlar ekle
└── Sipariş özetini incele

ADIM 4: SİPARİŞ GÖNDERİMİ
├── Siparişi gönder
├── Onay numarası al
├── Onay e-postasını kaydet
└── Beklenen teslimat tarihini not et

ADIM 5: SİPARİŞ TAKİBİ
├── Sipariş durumunu izle
├── Sevkiyat ilerlemesini takip et
├── Teslimata hazırlan
└── Gecikmeleri raporla
```

### Sipariş Hesaplama Yöntemi

```
YENİDEN SİPARİŞ MİKTARI HESAPLAMA

Adım 1: Ortalama Günlük Satışı Hesapla
Ortalama Günlük Satış = Toplam Satış (30 gün) ÷ 30

Adım 2: Tedarik Süresi Talebini Hesapla
Tedarik Süresi Talebi = Ortalama Günlük Satış × Tedarik Süresi (gün)

Adım 3: Güvenlik Stoğunu Hesapla
Güvenlik Stoğu = Ortalama Günlük Satış × Güvenlik Günleri

Adım 4: Yeniden Sipariş Noktasını Hesapla
Yeniden Sipariş Noktası = Tedarik Süresi Talebi + Güvenlik Stoğu

Adım 5: Sipariş Miktarını Hesapla
Sipariş Miktarı = (Hedef Stok Seviyesi) - (Mevcut Stok) + 
                  (Tedarik Süresi Boyunca Beklenen Satış)

ÖRNEK:
Ortalama Günlük Satış: 5 adet
Tedarik Süresi: 7 gün
Güvenlik Günleri: 3 gün
Mevcut Stok: 20 adet
Hedef Stok Seviyesi: 50 adet

Tedarik Süresi Talebi = 5 × 7 = 35 adet
Güvenlik Stoğu = 5 × 3 = 15 adet
Yeniden Sipariş Noktası = 35 + 15 = 50 adet
Sipariş Miktarı = 50 - 20 + 35 = 65 adet
```

---

## Standartlar ve Kurallar

### Sipariş Gönderim Standartları

| Standart | Gereksinim |
|----------|------------|
| **Sipariş Son Tarihi** | Haftalık siparişler için Salı 18:00 |
| **Minimum Sipariş** | Marka/kategori MOQ'ya göre |
| **Sipariş Sıklığı** | Haftalık (standart) |
| **Sistem Erişimi** | Sadece yetkili kullanıcılar |
| **Dokümantasyon** | Tüm siparişler belgelenir |

### Sipariş Doğruluk Gereksinimleri

| Metrik | Hedef |
|--------|-------|
| Ürün Seçimi | %100 doğru SKU |
| Miktar Doğruluğu | İhtiyacın %5'i dahilinde |
| Beden Oranı | Marka kılavuzlarına göre |
| Adres Doğruluğu | %100 doğru |
| Özel Talimatlar | Tam ve net |

### Bütçe Yönetimi

| Kural | Açıklama |
|-------|----------|
| **Satın Alma Limiti** | Tahsisi aşma |
| **Onay Gerekli** | Bütçeyi aşan siparişler için |
| **Öncelikli Ürünler** | Hızlı satanlara odaklan |
| **Sezonluk Düzeltme** | Yoğun dönemler için ayarla |
| **İndirim Dengesi** | İndirimli ürünleri dahil et |

---

## Kontrol Listeleri

### Sipariş Öncesi Kontrol Listesi

```
SİPARİŞ ÖNCESİ İNCELEME KONTROL LİSTESİ
Tarih: _____________ Mağaza: _____________

ENVANTER ANALİZİ
□ Mevcut stok seviyeleri incelendi
□ Düşük stok ürünleri belirlendi
□ Fazla stok ürünleri belirlendi
□ Satış hızı analiz edildi
□ Satış oranları hesaplandı

TALEP FAKTÖRLERİ
□ Yaklaşan promosyonlar not edildi
□ Sezonluk değerlendirmeler yapıldı
□ Yerel etkinlikler belirlendi
□ Hava durumu faktörleri değerlendirildi
□ Geçmiş veriler analiz edildi

BÜTÇE İNCELEME
□ Satın alma bütçesi kontrol edildi
□ Kalan bütçe doğrulandı
□ Öncelikli ürünler belirlendi
□ Onay gereksinimleri not edildi

SİSTEM HAZIRLIĞI
□ B2B portal erişimi doğrulandı
□ Giriş bilgileri hazır
□ Sipariş şablonu güncellendi
□ Teslimat adresi onaylandı

Müdür Onayı: _____________
Tarih: _____________
```

### Sipariş Gönderim Kontrol Listesi

```
SİPARİŞ GÖNDERİM KONTROL LİSTESİ
Tarih: _____________ Sipariş #: _____________

SİPARİŞ GİRİŞİ
□ Tüm ürünler siparişe eklendi
□ Miktarlar doğrulandı
□ Beden oranları doğru
□ MOQ gereksinimleri karşılandı
□ Teslimat adresi onaylandı
□ Özel talimatlar eklendi

SİPARİŞ İNCELEME
□ Toplam miktar kontrol edildi
□ Toplam değer incelendi
□ Bütçe uyumu doğrulandı
□ Tedarik süresi kabul edilebilir
□ Beklenen teslimat tarihi not edildi

GÖNDERİM
□ Sipariş başarıyla gönderildi
□ Onay numarası alındı
□ Onay kaydedildi/yazdırıldı
□ Takvim hatırlatıcısı ayarlandı
□ Ekip bilgilendirildi

SİPARİŞ DETAYLARI
Sipariş Numarası: _____________
Toplam Adet: _____________
Toplam Değer: _____________
Beklenen Teslimat: _____________
Gönderen: _____________
```

---

## Örnekler / Senaryolar

### Senaryo 1: Düzenli Haftalık Sipariş

**Durum:** Salı haftalık sipariş gönderimi

**Süreç:**
```
1. Pazartesi: Envanter raporu çalıştır
2. Pazartesi: Satış hızını analiz et
3. Pazartesi: Yenileme ihtiyaçlarını belirle
4. Pazartesi: Sipariş listesini hazırla
5. Salı Sabah: Müdür incelemesi ve onayı
6. Salı Öğleden Sonra: 18:00'dan önce sipariş gönder
7. Salı: Onayı kaydet
8. Çarşamba: Sipariş onayının alındığını doğrula
```

### Senaryo 2: Acil Stok Talebi

**Durum:** Kilit ürün beklenmedik şekilde tükendi

**Süreç:**
```
1. Gerçek stoğu doğrula (fiziksel sayım)
2. Bölgesel envanteri kontrol et (diğer mağazalar)
3. Mevcutsa: Mağaza transferi talep et
4. Mevcut değilse: Bölge Müdürüyle iletişime geç
5. Acil sipariş talebi gönder
6. Gerekçe sun (satış verileri)
7. Onay durumunu takip et
8. Hızlandırılmış teslimatı koordine et
```

### Senaryo 3: Sezon Sipariş Planlaması

**Durum:** Sezon öncesi toplu sipariş

**Süreç:**
```
1. Önceki sezon performansını incele
2. Kategoriye göre satış oranlarını analiz et
3. En çok satan stilleri/renkleri belirle
4. HQ önerilerini incele
5. Yerel pazar tercihlerini değerlendir
6. Beden oranlarını hesapla
7. Bütçe dahilinde sipariş hazırla
8. Son tarihe kadar gönder
9. HQ tahsisini incele
10. Gerekirse düzeltme talep et
```

---

## KPI'lar

### Sipariş Yönetimi Metrikleri

| KPI | Formül | Hedef | Sıklık |
|-----|--------|-------|--------|
| **Sipariş Doğruluğu** | Doğru sipariş / Toplam sipariş | ≥%98 | Haftalık |
| **Sipariş Zamanlaması** | Zamanında gönderim / Toplam | %100 | Haftalık |
| **Doldurma Oranı** | Alınan adet / Sipariş edilen adet | ≥%95 | Aylık |
| **Stoksuzluk Oranı** | Stoksuz gün / Toplam gün | <%2 | Haftalık |
| **Envanter Devir Hızı** | SMM / Ortalama Envanter | Yılda 4-6x | Üç aylık |

### Performans Panosu

```
┌─────────────────────────────────────────────────────────────┐
│              SİPARİŞ YÖNETİMİ PERFORMANSI                  │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  Sipariş Doğruluğu     [████████████████████░░] %98        │
│  Hedef: ≥%98           ✓ KARŞILIYOR                         │
│                                                             │
│  Sipariş Zamanlaması   [████████████████████████] %100     │
│  Hedef: %100           ✓ KARŞILIYOR                         │
│                                                             │
│  Doldurma Oranı        [██████████████████░░░░] %94        │
│  Hedef: ≥%95           ⚠ HEDEFİN ALTINDA                    │
│                                                             │
│  Stoksuzluk Oranı      [█░░░░░░░░░░░░░░░░░░░░░] %1.5       │
│  Hedef: <%2            ✓ HEDEF İÇİNDE                       │
│                                                             │
│  Bu Haftanın Siparişleri:                                   │
│  - Düzenli yenileme: 3 sipariş                             │
│  - Acil talepler: 1 sipariş                                │
│  - Mağaza transferleri: 2 sipariş                          │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## Sık Karşılaşılan Sorunlar ve Çözümler

### Sorun 1: Kaçırılan Sipariş Son Tarihi

**Problem:** Sipariş son tarihe kadar gönderilmedi

**Çözümler:**
- Takvim hatırlatıcıları ayarla
- Siparişleri önceden hazırla
- Yedek yetki ata
- Kaçırıldıysa hemen HQ'ya ulaş
- Son tarih uzatması talep et (sadece bir kez)

---

### Sorun 2: Sipariş Bütçeyi Aşıyor

**Problem:** Gerekli sipariş satın alma bütçesini aşıyor

**Çözümler:**
- Hızlı satan ürünlere öncelik ver
- Gerekçeyle bütçe artışı talep et
- Mağaza transferlerini değerlendir
- Zorunlu olmayan ürünleri ertele
- Bölge Müdürüyle tahsisi incele

---

### Sorun 3: Sistem Erişim Sorunları

**Problem:** B2B portalına erişilemiyor

**Çözümler:**
- İnternet bağlantısını kontrol et
- Tarayıcı önbelleğini temizle
- Farklı tarayıcı dene
- Gerekirse şifre sıfırla
- Hemen IT desteğine ulaş
- Yedek kullanıcının sipariş göndermesini sağla

---

### Sorun 4: Düşük Doldurma Oranı

**Problem:** Sipariş edilenden az alınıyor

**Çözümler:**
- Sipariş doğruluğunu incele
- Sipariş vermeden önce ürün mevcudiyetini kontrol et
- Bekleyen sipariş durumu için HQ'ya ulaş
- Öncelikli tahsis talep et
- Alternatif ürünleri değerlendir

---

## B2B Portal Kılavuzu

### Giriş Süreci

```
B2B PORTAL ERİŞİMİ

1. portal.aydinli.com adresine git
2. Kullanıcı adını gir (mağaza e-postası)
3. Şifreyi gir
4. İki faktörlü doğrulamayı tamamla
5. Sipariş panosuna eriş

NAVİGASYON
- Pano → Sipariş özeti
- Yeni Sipariş → Yenileme siparişi oluştur
- Sipariş Geçmişi → Geçmiş siparişleri görüntüle
- Takip → Sevkiyatları takip et
- Raporlar → Envanter raporlarını indir
- Destek → Yardım masasına ulaş
```

### Sipariş Giriş Adımları

```
YENİ SİPARİŞ OLUŞTURMA

1. "Yeni Sipariş"e tıkla
2. Marka seç (USPA/PC/Cacharel)
3. Kategori seç (Erkek/Kadın/Çocuk/Aksesuar)
4. Ürünlere göz at veya ara
5. Beden başına miktar gir
6. Sepete ekle
7. Tüm ürünler için tekrarla
8. Sepeti incele
9. Teslimat adresini doğrula
10. Özel talimatlar ekle
11. Siparişi gönder
12. Onayı kaydet
```

---

## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 2025-12-01 | İlk versiyon oluşturuldu | Aydınlı Grup Tedarik Zinciri |

---

*Bu doküman Aydınlı Grup Tedarik Zinciri Ekibi tarafından hazırlanmıştır.*  
*© 2025 Aydınlı Grup - Tüm hakları saklıdır.*


