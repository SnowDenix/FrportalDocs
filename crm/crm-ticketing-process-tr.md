---
layout: default
title: "CRM Ticketing ve Müşteri Şikayet Yönetimi"
---

# CRM Ticketing ve Müşteri Şikayet Yönetimi

> **Son Güncelleme:** 01 Aralık 2025 | **Versiyon:** 1.0  
> **Hazırlayan:** Aydınlı Grup

---

## İçindekiler

1. [Amaç](#amaç)
2. [Kapsam](#kapsam)
3. [Tanımlar](#tanımlar)
4. [Sorumluluklar](#sorumluluklar)
5. [Süreç Adımları](#süreç-adımları)
6. [SLA Süreleri](#sla-süreleri)
7. [Ekran Görüntüleri](#ekran-görüntüleri)
8. [KPI'lar](#kpılar)
9. [Sık Karşılaşılan Sorunlar ve Çözümler](#sık-karşılaşılan-sorunlar-ve-çözümler)
10. [Mağaza İpuçları](#mağaza-ipuçları)
11. [Revizyon Geçmişi](#revizyon-geçmişi)

---

## Amaç

Bu doküman, Aydınlı Grup franchise mağazalarında (U.S. Polo Assn., Pierre Cardin, Cacharel) müşteri şikayet, talep ve geri bildirimlerinin CRM Ticketing sistemi üzerinden yönetilmesine ilişkin süreçleri tanımlar.

### Ticketing Sisteminin Hedefleri

- Müşteri sorunlarını hızlı ve etkili bir şekilde çözmek
- Tüm müşteri etkileşimlerini kayıt altına almak
- Şikayet çözüm süreçlerini standartlaştırmak
- Müşteri memnuniyetini artırmak
- Tekrarlayan sorunları analiz ederek kök nedenleri ortadan kaldırmak

---

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

---

## Tanımlar

### Temel Ticketing Terimleri

| Terim | Tanım |
|-------|-------|
| **Ticket** | Müşteri şikayet, talep veya geri bildiriminin sistemde kayıt altına alındığı iş birimi |
| **Ticket ID** | Her ticketa atanan benzersiz takip numarası |
| **SLA** | Service Level Agreement - Servis Seviyesi Anlaşması. Çözüm için belirlenen maksimum süre |
| **Eskalasyon** | Ticketın bir üst yetkili seviyeye yükseltilmesi |
| **First Contact Resolution (FCR)** | İlk temasta çözülen ticket oranı |
| **Ticket Owner** | Ticketın çözümünden sorumlu kişi |
| **Ticket Status** | Ticketın mevcut durumu (Açık, İşlemde, Beklemede, Çözüldü, Kapatıldı) |
| **Root Cause** | Sorunun kök nedeni |
| **Resolution** | Uygulanan çözüm |

### Ticket Durumları

| Durum | Açıklama | Renk Kodu |
|-------|----------|-----------|
| **Açık** | Yeni açılmış, henüz işlem başlamamış | 🔴 Kırmızı |
| **İşlemde** | Üzerinde çalışılıyor | 🟡 Sarı |
| **Beklemede** | Müşteri/tedarikçi yanıtı bekleniyor | 🟠 Turuncu |
| **Çözüldü** | Çözüm uygulandı, müşteri onayı bekleniyor | 🔵 Mavi |
| **Kapatıldı** | Süreç tamamlandı | 🟢 Yeşil |
| **İptal** | Geçersiz veya mükerrer ticket | ⚫ Gri |

---

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

---

## Süreç Adımları

### 1. Ticket Oluşturma

#### Adım 1: Müşteri Bilgilerini Doğrulama

**İşlem:** CRM'de müşteriyi arayın ve profilini açın

**Kontrol Listesi:**
- [ ] Müşteri sistemde kayıtlı mı?
- [ ] İletişim bilgileri güncel mi?
- [ ] Satın alma geçmişi görüntülendi mi?

#### Adım 2: Ticket Açma

**İşlem:** "Yeni Ticket" butonuna tıklayın

**Doldurulacak Alanlar:**

| Alan | Açıklama | Zorunlu |
|------|----------|---------|
| Müşteri | Otomatik seçili gelir | ✓ |
| Kategori | Ana şikayet kategorisi | ✓ |
| Alt Kategori | Detaylı kategori | ✓ |
| Öncelik | Kritik/Yüksek/Normal/Düşük | ✓ |
| Konu | Kısa başlık | ✓ |
| Açıklama | Detaylı sorun tanımı | ✓ |
| İlgili Satış | Varsa satış işlemi | - |
| İlgili Ürün | Varsa ürün SKU | - |

#### Adım 3: Kategori Seçimi

**Ana Kategoriler:**

| Kategori | Alt Kategoriler | Örnek |
|----------|-----------------|-------|
| **Ürün Kalitesi** | Dikiş hatası, Kumaş sorunu, Renk akması, Beden uyumsuzluğu | Gömlek dikişi açılmış |
| **Ürün Değişim** | Beden değişimi, Model değişimi, Renk değişimi | M beden yerine L isteniyor |
| **İade Talebi** | Ürün iadesi, Para iadesi | Ürünü iade etmek istiyor |
| **Eksik/Hatalı Teslimat** | Eksik ürün, Yanlış ürün, Hasarlı paket | Siparişteki 2 üründen 1'i eksik |
| **Fiyat/Kampanya** | Yanlış fiyatlandırma, Kampanya sorunu, Kupon sorunu | İndirim uygulanmamış |
| **Mağaza Hizmeti** | Personel davranışı, Bekleme süresi, Temizlik | Uzun kuyruk şikayeti |
| **Loyalty/Puan** | Puan sorunu, Kart sorunu, Üyelik | Puanlar yansımamış |
| **Diğer** | Genel geri bildirim, Öneri, Teşekkür | Ürün önerisi |

#### Adım 4: Öncelik Belirleme

| Öncelik | Kriter | SLA |
|---------|--------|-----|
| **Kritik** | Sağlık/güvenlik riski, medya tehdidi, VIP müşteri | 4 saat |
| **Yüksek** | Maddi kayıp, tekrar eden sorun, sosyal medya şikayeti | 24 saat |
| **Normal** | Standart şikayet, değişim/iade talebi | 48 saat |
| **Düşük** | Öneri, genel geri bildirim, bilgi talebi | 72 saat |

#### Adım 5: Kanıt Ekleme

**Yüklenebilir Belgeler:**
- Ürün fotoğrafı (hasar/kusur görünecek şekilde)
- Satış fişi/fatura kopyası
- Müşteri kimlik belgesi (gerekirse)
- Video kayıt (maksimum 30 saniye)
- E-posta/SMS yazışması

**Fotoğraf Çekim Kuralları:**
1. İyi aydınlatılmış ortamda çekin
2. Sorunlu bölgeyi yakın plan gösterin
3. Etiket ve barkodu görünür şekilde çekin
4. Minimum 3 farklı açıdan fotoğraf ekleyin

---

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

---

### 3. Eskalasyon Matrisi

| Seviye | Yetkili | Süre Aşımı | Aksiyon |
|--------|---------|------------|---------|
| Seviye 1 | Mağaza Personeli | - | İlk müdahale |
| Seviye 2 | Mağaza Müdürü | 24 saat | Mağaza içi çözüm |
| Seviye 3 | Bölge Müdürü | 48 saat | Bölgesel koordinasyon |
| Seviye 4 | CRM Merkez | 72 saat | Merkezi müdahale |
| Seviye 5 | Üst Yönetim | 96 saat | Yönetim kararı |

**Otomatik Eskalasyon Kuralları:**
- SLA %80'e ulaştığında uyarı e-postası gönderilir
- SLA aşıldığında otomatik üst seviyeye eskalasyon yapılır
- Kritik ticketlar doğrudan Seviye 3'ten başlar

---

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

---

### 5. Ticket Kapatma

#### Kapatma Öncesi Kontrol Listesi

- [ ] Müşteri sorunu çözüldü mü?
- [ ] Müşteri bilgilendirildi mi?
- [ ] Müşteri çözümü onayladı mı?
- [ ] Tüm belgeler eklendi mi?
- [ ] Root cause belirlendi mi?
- [ ] Çözüm notları yazıldı mı?

#### Kapatma Kategorileri

| Kategori | Açıklama |
|----------|----------|
| Çözüldü - Müşteri Memnun | Sorun giderildi, müşteri memnun |
| Çözüldü - Kısmi Memnuniyet | Sorun giderildi, müşteri kısmen memnun |
| Çözülemedi - Müşteri Kabul Etti | Çözüm bulunamadı, müşteri durumu kabul etti |
| Çözülemedi - Müşteri Memnun Değil | Çözüm bulunamadı, müşteri memnun değil |
| İptal - Mükerrer | Aynı konu için başka ticket mevcut |
| İptal - Geçersiz | Ticket konusu geçersiz veya yanlış açılmış |

---

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

---

## Ekran Görüntüleri

### Ticket Listesi

![Ticket Listesi - Placeholder](screenshots/crm-ticket-list.png)

*Ekran görüntüsü eklenecektir.*

### Yeni Ticket Formu

![Yeni Ticket - Placeholder](screenshots/crm-ticket-new.png)

*Ekran görüntüsü eklenecektir.*

### Ticket Detay

![Ticket Detay - Placeholder](screenshots/crm-ticket-detail.png)

*Ekran görüntüsü eklenecektir.*

---

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

---

## Sık Karşılaşılan Sorunlar ve Çözümler

### Sorun 1: Ticket Kategorisi Belirsiz

**Durum:** Müşteri şikayeti birden fazla kategoriye uyuyor.

**Çözüm:**
1. Ana sorunu belirleyin (müşterinin en çok şikayet ettiği konu)
2. Bu kategoriye göre ticket açın
3. Diğer konuları açıklama alanına not edin
4. Gerekirse ilişkili ticket oluşturun

---

### Sorun 2: Müşteri Kanıt Sağlayamıyor

**Durum:** Müşteri fişi kaybetmiş veya ürünü getirmemiş.

**Çözüm:**
1. CRM'den satış geçmişini kontrol edin
2. Ödeme yöntemine göre banka ekstresini talep edin
3. Mağaza güvenlik kamera kaydını kontrol edin
4. Durumu ticket notlarına kaydedin
5. Mağaza müdürü onayı ile işlem yapın

---

### Sorun 3: Müşteri Agresif Davranıyor

**Durum:** Müşteri bağırıyor, tehdit ediyor.

**Çözüm:**
1. Sakin kalın, kişisel almayın
2. Müşteriyi dinleyin, sözünü kesmeyin
3. Empati kurun: "Sizi anlıyorum..."
4. Somut çözüm önerin
5. Mağaza müdürünü çağırın
6. Ticketı "Kritik" öncelikle açın
7. Durumu detaylı belgeleyin

---

### Sorun 4: SLA Süresi Dolmak Üzere

**Durum:** Ticket çözüme ulaşmadı, SLA dolacak.

**Çözüm:**
1. Hemen eskalasyon yapın
2. Müşteriyi bilgilendirin: "Konunuz üst yönetime iletildi"
3. Ticket notlarına gecikme nedenini yazın
4. Tahmini yeni süreyi belirtin
5. Öncelik seviyesini yükseltin

---

## Mağaza İpuçları

### Etkili Ticket Açma

1. **Detaylı yazın:** "Müşteri memnun değil" yerine "Müşteri 15.11.2025 tarihinde aldığı mavi polo tişörtün dikişinin 3. yıkamada söküldüğünü bildirdi"
2. **Doğru kategori seçin:** Yanlış kategori, yanlış ekibe yönlendirir
3. **Kanıt ekleyin:** Fotoğrafsız ticket, çözümü geciktirir
4. **Müşteri beklentisini not edin:** "Müşteri para iadesi istiyor" veya "Müşteri değişim kabul eder"

### Müşteri İletişimi

1. **İlk yanıt kritik:** Müşteriye hemen geri bildirim verin
2. **Takip numarasını paylaşın:** "Ticket numaranız 12345, bu numara ile takip edebilirsiniz"
3. **Süre verin:** "24 saat içinde size dönüş yapacağız"
4. **Proaktif olun:** Müşteri sormadan güncelleme verin

### Çözüm Odaklı Yaklaşım

| Müşteri Beklentisi | Önerilen Yaklaşım |
|--------------------|-------------------|
| Sadece dinlenmek istiyor | Empati kurun, özür dileyin |
| Ürün değişimi istiyor | Stok kontrolü yapın, alternatif sunun |
| Para iadesi istiyor | Politika dahilinde çözüm sunun |
| Tazminat istiyor | Mağaza müdürü onayına yönlendirin |

### Yapılması Gerekenler

- ✅ Her şikayeti ciddiye alın
- ✅ Müşteriye dönüş süresi verin
- ✅ Söz verdiğiniz sürede dönün
- ✅ Çözümü takip edin
- ✅ Kapanış sonrası memnuniyet sorun

### Yapılmaması Gerekenler

- ❌ Müşteriyle tartışmayın
- ❌ Başka departmanı suçlamayın
- ❌ Gerçekçi olmayan söz vermeyin
- ❌ Ticketı yanıtsız bırakmayın
- ❌ Eksik bilgiyle ticket kapatmayın

---

## Revizyon Geçmişi

| Versiyon | Tarih | Değişiklik | Hazırlayan |
|----------|-------|------------|------------|
| 1.0 | 01.12.2025 | İlk sürüm oluşturuldu | Aydınlı Grup |

---

*Bu doküman Aydınlı Grup CRM Operasyonları tarafından hazırlanmıştır.*  
*© 2025 Aydınlı Grup - Tüm hakları saklıdır.*


