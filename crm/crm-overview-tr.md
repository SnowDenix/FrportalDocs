---
layout: default
title: "CRM Genel Bakış"
---

# CRM Genel Bakış

> **Son Güncelleme:** 01 Aralık 2025 | **Versiyon:** 1.0  
> **Hazırlayan:** Aydınlı Grup

---

## İçindekiler

1. [Amaç](#amaç)
2. [Kapsam](#kapsam)
3. [Tanımlar](#tanımlar)
4. [Sorumluluklar](#sorumluluklar)
5. [CRM Sistem Mimarisi](#crm-sistem-mimarisi)
6. [Veri Akışı](#veri-akışı)
7. [Ekran Görüntüleri](#ekran-görüntüleri)
8. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
9. [Mağaza İpuçları](#mağaza-ipuçları)
10. [Revizyon Geçmişi](#revizyon-geçmişi)

---

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

---

## Kapsam

### Bu Doküman Kimleri Kapsar?

- **Mağaza Personeli:** Günlük CRM işlemlerini gerçekleştiren satış danışmanları
- **Mağaza Müdürleri:** CRM performansını takip eden ve ekibi yönlendiren yöneticiler
- **Bölge Müdürleri:** Bölge genelinde CRM uyumluluğunu denetleyen yöneticiler
- **Franchise Sahipleri:** CRM yatırımının getirisini takip eden işletme sahipleri

### Kapsanan Süreçler

1. Müşteri kaydı ve profil yönetimi
2. Satış işlemlerinde müşteri eşleştirme
3. Loyalty programı işlemleri
4. Kampanya ve kupon yönetimi
5. Müşteri şikayet/talep yönetimi (Ticketing)
6. Veri kalitesi kontrolü
7. Raporlama ve analiz

### Kapsanan Markalar

| Marka | Segment | CRM Entegrasyonu |
|-------|---------|------------------|
| U.S. Polo Assn. | Sportswear / Casual | Tam Entegrasyon |
| Pierre Cardin | Premium / Business | Tam Entegrasyon |
| Cacharel | Men's Fashion | Tam Entegrasyon |

---

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

---

## Sorumluluklar

### Mağaza Personeli

| Görev | Açıklama | Sıklık |
|-------|----------|--------|
| Müşteri Kaydı | Yeni müşterileri CRM sistemine kaydetmek | Her satışta |
| Müşteri Eşleştirme | Mevcut müşterileri satış işlemine bağlamak | Her satışta |
| İzin Toplama | KVKK onaylarını almak ve sisteme işlemek | Kayıt anında |
| Veri Güncelleme | Müşteri bilgilerini güncellemek | Talep üzerine |
| Ticket Açma | Müşteri şikayetlerini sisteme girmek | İhtiyaç halinde |

### Mağaza Müdürü

| Görev | Açıklama | Sıklık |
|-------|----------|--------|
| Performans Takibi | Mağaza CRM KPI'larını izlemek | Günlük |
| Eğitim | Personeli CRM kullanımı konusunda eğitmek | Sürekli |
| Kalite Kontrolü | Veri kalitesini denetlemek | Haftalık |
| Raporlama | Bölge yönetimine CRM raporları sunmak | Aylık |
| Ticket Takibi | Açık ticketların çözümünü sağlamak | Günlük |

### Bölge Müdürü

| Görev | Açıklama | Sıklık |
|-------|----------|--------|
| Uyumluluk Denetimi | KVKK ve CRM politika uyumunu denetlemek | Aylık |
| Performans Analizi | Bölge geneli CRM performansını analiz etmek | Haftalık |
| En İyi Uygulamalar | Başarılı CRM uygulamalarını yaygınlaştırmak | Sürekli |
| Eskalasyon Yönetimi | Kritik müşteri sorunlarını yönetmek | İhtiyaç halinde |

### CRM Merkez Ekibi

| Görev | Açıklama | Sıklık |
|-------|----------|--------|
| Sistem Yönetimi | CRM sisteminin teknik yönetimi | Sürekli |
| Kampanya Yönetimi | Merkezi kampanyaların oluşturulması | Periyodik |
| Veri Analizi | Müşteri segmentasyonu ve analitik | Sürekli |
| Politika Güncelleme | CRM politikalarının güncellenmesi | İhtiyaç halinde |
| Eğitim Desteği | Saha ekiplerine eğitim materyali sağlamak | Sürekli |

---

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

---

## Veri Akışı

### Müşteri Kaydı Akışı

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   Müşteri   │────▶│   Mağaza    │────▶│    CRM      │────▶│   Merkez    │
│   Bilgisi   │     │   Girişi    │     │  Doğrulama  │     │  Veritabanı │
└─────────────┘     └─────────────┘     └─────────────┘     └─────────────┘
      │                    │                   │                    │
      ▼                    ▼                   ▼                    ▼
  Ad, Soyad            Telefon/           Duplicate              Profil
  Telefon              Email              Kontrolü              Oluşturma
  Email                Format             KVKK İzni             Customer ID
  KVKK Onayı           Kontrolü           Doğrulama             Atama
```

### Satış İşlemi Akışı

```
1. Satış Başlatma
       │
       ▼
2. Müşteri Sorgusu ──────────────────────┐
       │                                  │
       ▼                                  ▼
3a. Mevcut Müşteri               3b. Yeni Müşteri
    Bulundu                          Kaydı
       │                                  │
       ▼                                  ▼
4. Müşteri Eşleştirme ◀──────────────────┘
       │
       ▼
5. Satış Tamamlama
       │
       ▼
6. Puan/Kupon İşleme
       │
       ▼
7. Fiş/Fatura Yazdırma
```

---

## Ekran Görüntüleri

### Ana CRM Ekranı

![CRM Ana Ekran Görüntüsü - Placeholder](screenshots/crm-main-screen.png)

*Ekran görüntüsü eklenecektir.*

### Müşteri Arama Ekranı

![Müşteri Arama Ekran Görüntüsü - Placeholder](screenshots/crm-customer-search.png)

*Ekran görüntüsü eklenecektir.*

### Müşteri Profil Ekranı

![Müşteri Profil Ekran Görüntüsü - Placeholder](screenshots/crm-customer-profile.png)

*Ekran görüntüsü eklenecektir.*

---

## Sık Karşılaşılan Sorunlar ve Çözümler

### Sorun 1: Müşteri Bulunamıyor

**Belirti:** Sistemde kayıtlı müşteri arama sonuçlarında çıkmıyor.

**Olası Nedenler:**
- Telefon numarası yanlış formatta girilmiş
- Müşteri farklı bir numara ile kayıtlı
- Kayıt henüz senkronize olmamış

**Çözüm:**
1. Telefon numarasını başında 0 olmadan arayın (5XX XXX XXXX)
2. Müşteriye kayıtlı diğer numaralarını sorun
3. 5 dakika bekleyip tekrar deneyin
4. Sorun devam ederse IT destek talebi açın

---

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

---

### Sorun 3: KVKK İzni Alınamıyor

**Belirti:** Müşteri KVKK onayı vermek istemiyor.

**Çözüm:**
1. Müşteriye veri işlemenin zorunlu olduğunu açıklayın
2. Sadece veri işleme izni ile kayıt yapılabilir
3. Pazarlama izinleri opsiyoneldir
4. Müşteri hiçbir izin vermezse, sadece POS üzerinden anonim satış yapın

---

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

---

## Mağaza İpuçları

### Günlük Rutinler

1. **Mağaza Açılışı:** CRM sistemine giriş yapın ve günlük hedefleri kontrol edin
2. **Her Satışta:** Müşteri eşleştirmesi yapmayı unutmayın
3. **Mağaza Kapanışı:** Açık ticketları kontrol edin

### Müşteri Kaydı En İyi Uygulamalar

- Telefon numarasını müşteriden teyit alarak girin
- E-posta adresini harf harf doğrulayın
- KVKK metnini müşteriye okutun veya özetleyin
- Pazarlama izinlerini zorlamayın, ama faydalarını açıklayın

### Satış Artırıcı CRM Kullanımı

- Müşterinin geçmiş alımlarına bakarak çapraz satış önerisi yapın
- Doğum günü yaklaşan müşterilere özel teklif sunun
- Loyalty puanlarını hatırlatarak ek satış teşvik edin

### Veri Kalitesi İpuçları

- Her güncellemede müşteri bilgilerini doğrulayın
- Hatalı veri gördüğünüzde düzeltme talebinde bulunun
- Duplicate şüphesi varsa hemen rapor edin

---

## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 01.12.2025 | İlk sürüm oluşturuldu | Aydınlı Grup |

---

*Bu doküman Aydınlı Grup CRM Operasyonları tarafından hazırlanmıştır.*  
*© 2025 Aydınlı Grup - Tüm hakları saklıdır.*


