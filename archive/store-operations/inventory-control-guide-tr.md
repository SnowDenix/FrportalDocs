---
layout: default
title: "Envanter Kontrol Kılavuzu – TR"
parent: Store Operations
---

# Envanter Kontrol Kılavuzu – TR

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

Bu doküman, tüm Aydınlı Grup franchise mağazalarında envanter yönetimi, stok kontrolü ve döngüsel sayım için kapsamlı prosedürler oluşturmaktadır. Doğru envanter, ürün bulunabilirliğini sağlar, fire'ı minimize eder ve işletme sermayesini optimize eder.

### Envanter Yönetimi Hedefleri

- **Doğruluk:** %99+ envanter doğruluğu
- **Bulunabilirlik:** Doğru ürün, doğru yer, doğru zaman
- **Verimlilik:** Optimize edilmiş stok seviyeleri
- **Görünürlük:** Gerçek zamanlı envanter bilgisi
- **Koruma:** Fire ve kaybı minimize etme

---

## Kapsam

Bu kılavuz şunları kapsar:
- Teslimat alma ve işleme
- Stok organizasyonu ve yenileme
- Döngüsel sayım prosedürleri
- Yıllık envanter sayımları
- Envanter düzeltme süreçleri
- Mağazalar arası transferler

---

## Tanımlar

| Terim (EN) | Terim (TR) | Tanım |
|------------|------------|-------|
| SKU | Stok Kodu | Stok Tutma Birimi - benzersiz ürün tanımlayıcı |
| Shrinkage | Fire | Hırsızlık, hasar veya hatadan envanter kaybı |
| Cycle Count | Döngüsel Sayım | Süregelen kısmi envanter sayımları |
| Physical Inventory | Fiziksel Envanter | Tam mağaza envanter sayımı |
| Variance | Fark | Sistem ve gerçek stok arasındaki fark |
| Receiving | Mal Kabul | Teslimat kabul süreci |
| Transfer | Transfer | Lokasyonlar arasında stok hareketi |
| Stock-out | Stok Sıfır | Bir ürünün sıfır envanteri |
| Overstock | Fazla Stok | Aşırı envanter |
| FIFO | İlk Giren İlk Çıkar | İlk Giren, İlk Çıkar envanter yöntemi |

---

## Sorumluluklar

### Satış Personeli

| Görev | Sıklık |
|-------|--------|
| Satış alanı stoğunu koruma | Sürekli |
| Düşük stok ürünlerini raporlama | Fark edildiğinde |
| Döngüsel sayımlara katılım | Atandığında |
| Hasarlı ürünleri raporlama | Hemen |

### Depo Personeli

| Görev | Sıklık |
|-------|--------|
| Teslimatları alma ve işleme | Teslimat başına |
| Arka stoğu organize etme | Günlük |
| Satış alanını yenileme | Günde birkaç kez |
| Döngüsel sayım yapma | Programa göre |

### Mağaza Müdürü

| Görev | Sıklık |
|-------|--------|
| Envanter doğruluğunu denetleme | Günlük |
| Envanter düzeltmelerini onaylama | Gerektiğinde |
| Teslimat programlarını yönetme | Haftalık |
| Yıllık envanteri yönetme | Yıllık |
| Farkları araştırma | Gerçekleştiğinde |

---

## Süreç Adımları

### Mal Kabul Süreci

```
ADIM 1: TESLİMAT VARIŞI
├── Teslimatın beklenen sevkiyatla eşleştiğini doğrula
├── Teslimat dokümantasyonunu kontrol et
├── Kutuları dış hasar için incele
├── Toplam kutu/parça say
├── Tutarsızlıkları evrak üzerinde not et
└── Gerekirse notlarla teslimatı imzala

ADIM 2: AÇMA VE DOĞRULAMA
├── Kutuları belirlenen mal kabul alanında aç
├── Ürünleri paket listesiyle karşılaştır
├── Her SKU'yu envanter sistemine tara
├── Miktarların eşleştiğini doğrula
├── Hasar veya kusur için incele
├── Hasarlı ürünleri ayır
└── Tutarsızlıkları belgele

ADIM 3: İŞLEME
├── Sistemde kabulü onayla
├── Gerekirse güvenlik etiketlerini uygula
├── Önceden etiketli değilse fiyat etiketlerini uygula
├── Kategori/stile göre sırala
└── Saha veya arka stok için hazırla

ADIM 4: YERLEŞTİRME
├── Saha yenilemeyi önceliklendir
├── Planograma göre satış alanına yerleştir
├── Fazlayı organize edilmiş arka stokta depola
├── Sistemde envanter konumlarını güncelle
└── Ambalaj malzemelerini uygun şekilde at

ADIM 5: DOKÜMANTASYON
├── Mal kabul evraklarını tamamla
├── Paket listesi ve teslimat notunu dosyala
├── Tutarsızlıkları HQ'ya raporla
└── Hasarlı ürünleri politikaya göre işle
```

### Günlük Stok Yenileme

```
YENİLEME ÖNCELİK SIRASI

1. BOŞ FİKSTÜRLER (Kritik)
   └── Müşteriye görünen stok yok
   
2. DÜŞÜK STOK (Yüksek Öncelik)
   └── Minimum sergi miktarının altında
   
3. KIRILAN BEDENLER (Orta Öncelik)
   └── Sergilenen ürünlerde beden boşlukları
   
4. MANKEN ÜRÜNLERİ (Orta Öncelik)
   └── Mankenlerde sergilenen ürünler
   
5. PROMOSYON ÜRÜNLERİ (Orta Öncelik)
   └── Güncel kampanya ürünleri
   
6. GENEL DOLDURMA (Standart)
   └── Dolu görünümü koruma
```

### Döngüsel Sayım Süreci

```
DÖNGÜSEL SAYIM PROGRAMI

| Gün | Kategori | Örnek |
|-----|----------|-------|
| Pazartesi | Üstler | Polo, gömlek, t-shirt |
| Salı | Altlar | Pantolon, şort, kot |
| Çarşamba | Dış Giyim | Ceket, mont |
| Perşembe | Aksesuarlar | Kemer, kravat, çanta |
| Cuma | Tamamlama | Eksik kalan alanlar |

DÖNGÜSEL SAYIM ADIMLARI:
1. Atanan alan için sayım listesi yazdır
2. Mümkünse alanı müşterilerden temizle
3. Sahada ve arkada gerçek ürünleri say
4. Sayımı listeye kaydet
5. Sistem miktarıyla karşılaştır
6. Farkları araştır
7. Sayım sonuçlarını gönder
8. Doğrulanırsa envanteri düzelt
```

---

## Standartlar ve Kurallar

### Envanter Doğruluk Standartları

| Metrik | Hedef | Aksiyon Eşiği |
|--------|-------|---------------|
| SKU Doğruluğu | ≥%98 | <%95 araştırma tetikler |
| Adet Doğruluğu | ≥%99 | <%97 araştırma tetikler |
| Fire Oranı | Satışların <%1'i | >%1.5 aksiyon planı tetikler |
| Mal Kabul Doğruluğu | %100 | Her hata rapor gerektirir |

### Depo Organizasyonu

```
DEPO ALAN DÜZENİ

BÖLGE A: MAL KABUL
├── Gelen sevkiyatlar
├── İşleme alanı
└── Güvenlik etiketleme istasyonu

BÖLGE B: AKTİF STOK
├── Güncel sezon ürünleri
├── Yüksek hareket hızlı ürünler
└── Kategori/stile göre organize

BÖLGE C: YEDEK STOK
├── Taşan envanter
├── Gelecek sezon (varsa)
└── Toplu depolama

BÖLGE D: İADELER/HASARLAR
├── İşlenecek ürünler
├── Hasarlı ürünler
└── Transfer hazırlık alanı
```

### FIFO Prensipleri

| Prensip | Uygulama |
|---------|----------|
| **İlk Giren, İlk Çıkar** | Eski stok önce satılır |
| **Yeni Teslimatlar** | Mevcut stoğun arkasına yerleştir |
| **Saha Stoğu** | Arka stokla rotasyon yap |
| **Tarihli Ürünler** | Tarihleri kontrol et, en eskiyi önce sat |

---

## Kontrol Listeleri

### Günlük Envanter Kontrol Listesi

```
GÜNLÜK ENVANTER KONTROL LİSTESİ
Tarih: _____________ Personel: _____________

SABAH KONTROLÜ
□ Satış alanı turu tamamlandı
□ Boş fikstürler belirlendi
□ Düşük stok ürünleri not edildi
□ Yenileme listesi oluşturuldu
□ Arka stok, saha ihtiyaçları için kontrol edildi

YENİLEME
□ Tüm boş fikstürler dolduruldu
□ Beden serileri tamamlandı
□ Manken ürünleri yenilendi
□ Promosyon sergileri dolu
□ Kabin ürünleri sahaya iade edildi

ARKA STOK
□ Depo organize edildi
□ Yeni teslimatlar yerleştirildi
□ FIFO rotasyonu doğrulandı
□ Hasarlı ürünler ayrıldı
□ Transfer ürünleri hazırlandı

GÜN SONU
□ Son saha kontrolü
□ Eksiklik raporu gönderildi
□ Yarının ihtiyaçları not edildi
□ Depo güvenli
```

### Teslimat Mal Kabul Kontrol Listesi

```
TESLİMAT MAL KABUL KONTROL LİSTESİ
Tarih: _____________ Teslimat #: _____________

ÖN KABUL
□ Beklenen teslimat listesi incelendi
□ Mal kabul alanı temiz
□ Tarama ekipmanı hazır
□ Personel atandı

KABUL
Tedarikçi: _______________________
Alınan kutular: _____ Beklenen: _____
□ Dış hasar not edildi: _______________
□ Sürücü imzası alındı

DOĞRULAMA
Alınan toplam SKU: _____
Alınan toplam adet: _____
□ Tüm ürünler tarandı
□ Sayımlar paket listesiyle eşleşiyor
□ Hasarlı ürünler: _____ adet
□ Eksik ürünler: _____ adet
□ Fazla ürünler: _____ adet

TUTARSIZLIK RAPORU
□ Tutarsızlık formu tamamlandı (gerekirse)
□ Fotoğraflar çekildi (hasar varsa)
□ HQ bilgilendirildi (fark >%5 ise)

İŞLEME
□ Güvenlik etiketleri uygulandı
□ Fiyat etiketleri doğrulandı
□ Ürünler yerleşim için sıralandı
□ Evraklar dosyalandı

Kabul eden imzası: _____________
Müdür imzası: _____________
```

---

## Örnekler / Senaryolar

### Senaryo 1: Eksik Teslimat

**Durum:** 100 adet teslimat, paket fişi 120 gösteriyor

**Süreç:**
```
1. Eksikliği hemen belgele
2. Teslimat makbuzuna not: "100 alındı, 120 bekleniyordu"
3. Sürücüye değiştirilmiş makbuzu imzalat
4. Tutarsızlık raporunu tamamla
5. Sistemde sadece 100 kabul et
6. Detaylarla HQ'ya bildir
7. Tüm evrakları dosyala
8. Çözüm için takip et
```

### Senaryo 2: Döngüsel Sayımda Fark Bulundu

**Durum:** Sistem 15 gösteriyor, gerçek sayım 12

**Süreç:**
```
1. Doğrulamak için yeniden say
2. Kabinleri kontrol et
3. Fikstür altlarını kontrol et
4. Arka stoğu kontrol et
5. Son satışları incele
6. Yanlış taramaları kontrol et
7. Fark onaylanırsa:
   - Bulguları belgele
   - Müdür incelemesi
   - Onaylanırsa envanteri düzelt
   - Neden kodu not et
8. Desen bulunursa daha fazla araştır
```

### Senaryo 3: Hasarlı Ürün Teslim Alındı

**Durum:** Teslimattta 5 ürün kusurlu

**Süreç:**
```
1. Hasarlı ürünleri ayır
2. Fotoğraflarla belgele
3. Mal kabul evraklarına not et
4. Envantere KOYMA
5. Hasarlı ürün formunu tamamla
6. HQ'ya gönder
7. Politikaya göre ürünleri tut:
   - Satıcıya iade, VEYA
   - İndirimle sat, VEYA
   - Dokümantasyonla imha et
8. Envanteri buna göre güncelle
```

---

## KPI'lar

### Envanter Performans Metrikleri

| KPI | Formül | Hedef | Sıklık |
|-----|--------|-------|--------|
| **Envanter Doğruluğu** | Doğru SKU / Toplam SKU | ≥%98 | Döngüsel sayım |
| **Fire Oranı** | Kayıp değer / Satışlar | <%1 | Yıllık |
| **Stoksuzluk Oranı** | Stoksuz SKU / Toplam | <%3 | Haftalık |
| **Stok Günü** | Envanter / Günlük satış | 45-60 gün | Aylık |
| **Mal Kabul Doğruluğu** | Doğru kabuller / Toplam | %100 | Teslimat başına |

### Envanter Panosu

```
┌─────────────────────────────────────────────────────────────┐
│              HAFTALIK ENVANTER PERFORMANSI                  │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  Envanter Doğruluğu    [████████████████████░░] %98.2      │
│  Hedef: ≥%98           ✓ KARŞILIYOR                         │
│                                                             │
│  Stoksuzluk Oranı      [███░░░░░░░░░░░░░░░░░░░] %2.1       │
│  Hedef: <%3            ✓ HEDEF İÇİNDE                       │
│                                                             │
│  Fire YTD              [█████████░░░░░░░░░░░░░] %0.8       │
│  Hedef: <%1            ✓ YOLUNDA                            │
│                                                             │
│  En Çok Stoksuz Kategoriler:                                │
│  1. Erkek Polo (M, L bedenler)                             │
│  2. Kemerler (Siyah, 32-34)                                │
│  3. Kadın Bluzlar (S)                                      │
│                                                             │
│  Aksiyon: En çok stoksuz ürünler için siparişi hızlandır   │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## Sık Karşılaşılan Sorunlar ve Çözümler

### Sorun 1: Kronik Stoksuzluk

**Problem:** Aynı ürünler sürekli stoksuz kalıyor

**Çözümler:**
- Yeniden sipariş noktalarını incele
- Satış hızını analiz et
- Sipariş miktarlarını artır
- Öncelikli tahsis talep et
- Mağaza transferi düşün

---

### Sorun 2: Yüksek Fire Oranı

**Problem:** Envanter kaybı hedefleri aşıyor

**Çözümler:**
- Güvenlik önlemlerini artır
- Mal kabul prosedürlerini incele
- Daha fazla döngüsel sayım yap
- Personeli kayıp önleme konusunda eğit
- Fire desenlerini analiz et

---

### Sorun 3: Düzensiz Arka Stok

**Problem:** Gerektiğinde ürünler bulunamıyor

**Çözümler:**
- Bölge sistemi uygula
- Günlük organizasyon zamanı
- Net etiketleme
- Eski ürünlerin düzenli temizlenmesi
- Personel hesap verebilirliği

---

## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 2025-12-01 | İlk versiyon oluşturuldu | Aydınlı Grup |

---

*Bu doküman Aydınlı Grup Mağaza Operasyonları Ekibi tarafından hazırlanmıştır.*  
*© 2025 Aydınlı Grup - Tüm hakları saklıdır.*


