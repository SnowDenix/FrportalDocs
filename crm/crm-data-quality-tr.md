---
layout: default
title: "CRM Veri Kalitesi Yönetimi"
parent: CRM
nav_order: 8
---

# CRM Veri Kalitesi Yönetimi

> **Son Güncelleme:** 01 Aralık 2025 | **Versiyon:** 1.0  
> **Hazırlayan:** Aydınlı Grup

---

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
10. [Ekran Görüntüleri](#ekran-görüntüleri)
11. [KPI'lar](#kpılar)
12. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
13. [Mağaza İpuçları](#mağaza-ipuçları)
14. [Revizyon Geçmişi](#revizyon-geçmişi)

---

## Amaç

Bu doküman, Aydınlı Grup franchise mağazalarında (U.S. Polo Assn., Pierre Cardin, Cacharel) CRM sistemindeki müşteri verilerinin kalitesini sağlamak ve sürdürmek için gereken standartları ve süreçleri tanımlar.

### Veri Kalitesinin Önemi

- **Müşteri deneyimi:** Doğru veri, kişiselleştirilmiş hizmet demektir
- **Pazarlama etkinliği:** Kaliteli veri, hedefli kampanya demektir
- **Operasyonel verimlilik:** Temiz veri, hızlı işlem demektir
- **Maliyet tasarrufu:** Hatalı veriler ekstra maliyet yaratır
- **Yasal uyumluluk:** KVKK doğru ve güncel veri gerektirir

---

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

---

## Tanımlar

### Veri Kalitesi Terimleri

| Terim | Tanım |
|-------|-------|
| **Veri Kalitesi** | Verinin doğru, eksiksiz, tutarlı ve güncel olma durumu |
| **Duplicate** | Aynı müşteriye ait birden fazla kayıt |
| **Merge** | Mükerrer kayıtların birleştirilmesi |
| **Data Cleansing** | Hatalı verilerin düzeltilmesi/temizlenmesi |
| **Validation** | Veri girişinde format/içerik kontrolü |
| **Standardization** | Verilerin tek bir formata dönüştürülmesi |
| **Enrichment** | Mevcut verilerin zenginleştirilmesi |
| **Decay** | Verinin zaman içinde eskimesi/geçersizleşmesi |

### Veri Kalitesi Boyutları

| Boyut | Açıklama | Örnek |
|-------|----------|-------|
| **Doğruluk (Accuracy)** | Verinin gerçeği yansıtması | Telefon numarası gerçekten müşteriye ait mi? |
| **Tamlık (Completeness)** | Gerekli tüm alanların dolu olması | E-posta alanı boş mu? |
| **Tutarlılık (Consistency)** | Farklı sistemlerde aynı verinin tutarlı olması | POS ve CRM'de aynı isim mi? |
| **Güncellik (Timeliness)** | Verinin güncel olması | Adres hala geçerli mi? |
| **Teklik (Uniqueness)** | Her müşterinin tek kaydı olması | Duplicate var mı? |
| **Geçerlilik (Validity)** | Verinin kurallara uygunluğu | Telefon 10 hane mi? |

---

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

---

## Veri Kalitesi İlkeleri

### Temel İlkeler

1. **İlk Seferde Doğru:** Veriyi ilk girişte doğru almak, sonradan düzeltmekten kolaydır
2. **Kaynaktan Doğrulama:** Veriyi müşteriden teyit alarak girin
3. **Standardizasyon:** Belirlenen formatlara uyun
4. **Minimum Veri:** Sadece gerekli verileri toplayın
5. **Düzenli Güncelleme:** Müşteri ile her temasta bilgileri doğrulayın

### Golden Record Kuralı

Her müşterinin sistemde tek bir "Golden Record" (ana kayıt) olmalıdır:

```
┌─────────────────────────────────────────────────────────────────┐
│                     GOLDEN RECORD                                │
├─────────────────────────────────────────────────────────────────┤
│  Customer ID: 1000045678                                        │
│  Ad Soyad: AHMET YILMAZ                                         │
│  Telefon: 532 123 4567                                          │
│  E-posta: ahmet.yilmaz@email.com                                │
│  ─────────────────────────────────────────────────────────────  │
│  Tüm satışlar, puanlar, kuponlar bu kayda bağlı olmalı         │
│  Duplicate kayıtlar bu kayıtla merge edilmeli                   │
└─────────────────────────────────────────────────────────────────┘
```

---

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

---

## Yaygın Veri Hataları

### Hata Kategorileri

| Kategori | Açıklama | Etki |
|----------|----------|------|
| Format Hatası | Yanlış formatta veri | Sistem reddi |
| Yazım Hatası | Typo, eksik karakter | İletişim hatası |
| Eksik Veri | Zorunlu alan boş | Eksik profil |
| Duplicate | Mükerrer kayıt | Bölünmüş veri |
| Güncel Olmayan | Eski bilgi | Ulaşılamama |
| Sahte Veri | Uydurma bilgi | Kullanılamaz veri |

### En Sık Rastlanan Hatalar

| Hata | Örnek | Neden |
|------|-------|-------|
| Yanlış telefon | 532 123 456 (9 hane) | Acele giriş |
| Typo e-posta | ahmet@gmial.com | Dikkat eksikliği |
| Sahte e-posta | aaa@aaa.com | Müşteri vermek istemedi |
| Yanlış doğum tarihi | 01/01/2000 (herkes için) | Bilgi alınmadı |
| Tam ad yerine kısaltma | A. Yılmaz | Acele |
| Duplicate kayıt | Aynı müşteri 2 telefon ile | Kontrol yapılmadı |

### Hata Etkileri

| Hata | İş Etkisi |
|------|-----------|
| Yanlış telefon | SMS gitmez, müşteriye ulaşılamaz |
| Yanlış e-posta | Kampanya e-postaları gitmez |
| Duplicate | Puanlar bölünür, müşteri mağdur olur |
| Eksik veri | Kişiselleştirme yapılamaz |
| Sahte veri | Pazarlama bütçesi boşa gider |

---

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

---

## Duplicate Yönetimi

### Duplicate Oluşma Nedenleri

| Neden | Açıklama |
|-------|----------|
| Farklı telefon | Müşteri farklı numara vermiş |
| Farklı e-posta | Kayıtlar farklı e-posta ile yapılmış |
| Yazım farkı | "Ahmet" vs "Ahmed" |
| Yeni kayıt | Mevcut kayıt aranmadan yeni açılmış |
| Farklı mağaza | Farklı mağazalarda kayıt |

### Duplicate Tespit

**Belirtiler:**
- Müşteri "Puanlarım nerede?" diyor ama bakiyesi sıfır
- Aynı isimde birden fazla kayıt çıkıyor
- Müşteri farklı numara söylediğinde farklı profil açılıyor

**Tespit Ekranı:**
```
┌─────────────────────────────────────────────────────────────────┐
│  OLASI DUPLICATE TESPİTİ                                        │
├─────────────────────────────────────────────────────────────────┤
│  Kayıt 1                    │  Kayıt 2                          │
│  ─────────────────────────  │  ─────────────────────────────── │
│  ID: 1000045678             │  ID: 1000098765                   │
│  Ad: Ahmet Yılmaz           │  Ad: Ahmet Yilmaz                 │
│  Tel: 532 123 4567          │  Tel: 533 987 6543                │
│  Email: ahmet@email.com     │  Email: ahmet@email.com           │
│  Puan: 2.500                │  Puan: 1.000                      │
│  ─────────────────────────────────────────────────────────────  │
│  E-posta aynı → Yüksek olasılıkla aynı müşteri                 │
└─────────────────────────────────────────────────────────────────┘
```

### Merge Süreci

**Adım 1:** Duplicate tespit edin

**Adım 2:** Her iki kaydı karşılaştırın

**Adım 3:** Merge talebini CRM Merkez'e iletin:
- Her iki Customer ID
- Hangi kaydın "Golden Record" olacağı
- Müşteriden alınan doğru bilgiler

**Adım 4:** CRM Merkez merge işlemini yapar:
- Puanlar birleştirilir
- Satış geçmişi birleştirilir
- Kuponlar aktarılır
- İkinci kayıt pasife alınır

**Adım 5:** Müşteriye bilgi verilir

### Merge Kuralları

| Kural | Açıklama |
|-------|----------|
| En eski kayıt ana kayıt olur | Daha fazla geçmişe sahip |
| Puanlar toplanır | Kayıp yaşanmaz |
| En güncel bilgi kullanılır | Telefon, adres vb. |
| Satış geçmişi korunur | Tüm işlemler görünür |

---

## Ekran Görüntüleri

### Veri Kalitesi Dashboard

![Veri Kalitesi Dashboard - Placeholder](screenshots/crm-data-quality-dashboard.png)

*Ekran görüntüsü eklenecektir.*

### Duplicate Yönetimi

![Duplicate Yönetimi - Placeholder](screenshots/crm-duplicate-management.png)

*Ekran görüntüsü eklenecektir.*

---

## KPI'lar

### Veri Kalitesi KPI'ları

| KPI | Tanım | Formül | Hedef |
|-----|-------|--------|-------|
| **Data Completeness** | Profil tamamlanma oranı | (Dolu Alanlar / Toplam Alan) × 100 | >80% |
| **Phone Validity** | Geçerli telefon oranı | (Geçerli Telefon / Toplam Kayıt) × 100 | >95% |
| **Email Validity** | Geçerli e-posta oranı | (Geçerli Email / Email Girilen) × 100 | >90% |
| **Duplicate Rate** | Mükerrer kayıt oranı | (Duplicate Kayıt / Toplam Kayıt) × 100 | <2% |
| **Bounce Rate** | Ulaşılamayan iletişim oranı | (Bounce / Gönderilen) × 100 | <5% |
| **Data Decay Rate** | Veri eskime oranı | (Güncel Olmayan / Toplam) × 100 | <10% |

### Hesaplama Örnekleri

**Data Completeness:**
```
Toplam zorunlu alan: 6 (Ad, Soyad, Telefon, Email, Cinsiyet, Doğum)
Ortalama dolu alan: 5
Completeness = (5 / 6) × 100 = %83
```

**Duplicate Rate:**
```
Tespit edilen duplicate: 150
Toplam müşteri: 10.000
Duplicate Rate = (150 / 10.000) × 100 = %1.5
```

---

## Sık Karşılaşılan Sorunlar ve Çözümler

### Sorun 1: Müşteri Telefon Numarasını Değiştirmiş

**Durum:** Eski numara ile kayıtlı, yeni numara ile aranıyor.

**Çözüm:**
1. Eski numara ile kaydı bulun
2. Müşteri kimliğini doğrulayın
3. Telefon numarasını güncelleyin
4. Müşteriye onay verin

---

### Sorun 2: E-posta Bounce Ediyor

**Durum:** Gönderilen e-postalar geri dönüyor.

**Çözüm:**
1. E-posta adresini kontrol edin
2. Yaygın typoları kontrol edin (gmial, hotnail vb.)
3. Müşteriden doğru e-postayı alın
4. CRM'de güncelleyin

---

### Sorun 3: Duplicate Kayıt Şüphesi

**Durum:** Aynı müşteri farklı numaralarla geliyor.

**Çözüm:**
1. Her iki kaydı karşılaştırın
2. Müşteriden teyit alın
3. CRM Merkez'e merge talebi açın
4. Müşteriye süreç hakkında bilgi verin

---

### Sorun 4: Sahte Veri Girişi

**Durum:** aaa@aaa.com gibi sahte bilgiler.

**Çözüm:**
1. Bu tür kayıtları tespit edin
2. Mümkünse müşteriden doğru bilgi alın
3. Alınamıyorsa alanı boş bırakın
4. Asla sahte veri kabul etmeyin

---

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

---

## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 01.12.2025 | İlk sürüm oluşturuldu | Aydınlı Grup |

---

*Bu doküman Aydınlı Grup CRM Operasyonları tarafından hazırlanmıştır.*  
*© 2025 Aydınlı Grup - Tüm hakları saklıdır.*


