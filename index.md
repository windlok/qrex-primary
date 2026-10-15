# Gizlilik Politikası - QREX

**Son Güncelleme:** 15 Ekim 2026

## Giriş

QREX ("biz", "uygulama"), kullanıcılarının gizliliğini ciddiye alır. Bu gizlilik politikası, QREX uygulamasının hangi bilgileri topladığını, nasıl kullandığını ve koruduğunu açıklar.

## Toplanan Bilgiler

### 1. Kamera İzni
**Amaç:** QR kod tarama işlevi için  
**Kullanım:** Kamera erişimi yalnızca QR kodları taramak için kullanılır. Kamera görüntüleri cihazınızda kalır ve hiçbir sunucuya gönderilmez.  
**Veri Saklama:** Kamera görüntüleri saklanmaz, yalnızca anlık olarak QR kod tespit edilir.

### 2. Konum İzni
**Amaç:** QR kodlarına konum bilgisi ekleme (isteğe bağlı özellik)  
**Kullanım:** Konum bilgisi yalnızca kullanıcı talep ettiğinde QR kod içeriğine eklenir. Konum verileri sunucuya gönderilmez.  
**Veri Saklama:** Konum bilgisi yalnızca oluşturulan QR kodunda yerel olarak saklanır.

### 3. Galeri ve Dosya Erişimi
**Amaç:** 
- QR kodlarını galeriye kaydetme
- Logo/resim ekleme için galeri erişimi
- Galeriden QR kod okutma

**Kullanım:** Galeri erişimi yalnızca kullanıcının onayıyla ve belirtilen işlemler için kullanılır.  
**Veri Saklama:** Seçilen görseller cihazda yerel olarak saklanır, hiçbir sunucuya yüklenmez.

### 4. İnternet İzni
**Amaç:** 
- QR kod içeriğindeki URL'leri açma
- Sosyal medya paylaşımı
- E-posta/SMS/Harita uygulamaları ile entegrasyon

**Kullanım:** İnternet bağlantısı yalnızca kullanıcının başlattığı işlemler için kullanılır (örn: URL'yi tarayıcıda açma).  
**Veri Transferi:** Hiçbir kullanıcı verisi bizim sunucularımıza gönderilmez. Tüm internet trafiği kullanıcının cihazından doğrudan hedef servislere gider.

## Veri Paylaşımı ve Üçüncü Taraf Servisler

QREX, hiçbir kişisel veriyi üçüncü taraflarla paylaşmaz. Uygulama şu özelliklere sahiptir:

- ✅ **Tamamen Çevrimdışı Çalışır:** QR kod oluşturma ve tarama işlemleri cihazda yapılır
- ✅ **Sunucu Yok:** Hiçbir merkezi sunucu kullanılmaz
- ✅ **Analitik Yok:** Kullanıcı davranışı takip edilmez
- ✅ **Reklam Yok:** Üçüncü taraf reklam servisleri kullanılmaz

## Veri Güvenliği

### Şifreli QR Kodlar
Uygulama, hassas bilgiler içeren QR kodları şifreleme özelliği sunar:
- Şifreler cihazda hash'lenerek saklanır
- Şifrelenmiş veri yalnızca cihazda saklanır
- Şifreler hiçbir sunucuya gönderilmez

### Yerel Depolama
Tüm QR kod geçmişi ve ayarlar cihazın yerel hafızasında saklanır:
- Veriler şifreli yerel depolama (flutter_secure_storage / EncryptedSharedPreferences) kullanılarak cihazda tutulur
- Uygulama kaldırıldığında tüm veriler silinir
- Veriler bulut senkronizasyonu yapılmaz

## Çocukların Gizliliği

QREX, 13 yaşından küçük çocuklardan bilerek kişisel bilgi toplamaz. Ebeveynler, çocuklarının uygulamayı kullanımını denetlemelidir.

## Kullanıcı Hakları

Kullanıcılar aşağıdaki haklara sahiptir:

1. **Veri Silme:** Uygulama ayarlarından tüm QR geçmişini silebilir
2. **İzin İptali:** Cihaz ayarlarından istediğiniz zaman izinleri iptal edebilir
3. **Veri Dışa Aktarma:** QR kodlarınızı dosya olarak dışa aktarabilir

## İzinlerin Kullanımı

| İzin | Zorunlu mu? | Amaç |
|------|-------------|------|
| Kamera | Hayır* | QR kod tarama |
| Konum | Hayır | QR'a konum ekleme (isteğe bağlı) |
| Galeri | Hayır | QR kaydetme ve logo ekleme |
| İnternet | Hayır** | URL açma, paylaşım |

*Kamera izni olmadan QR tarama çalışmaz, ancak QR oluşturma çalışır  
**İnternet izni olmadan URL'ler otomatik açılmaz

## Değişiklikler

Bu gizlilik politikası güncellenebilir. Önemli değişiklikler uygulama içinde bildirilecektir. Son güncelleme tarihi bu sayfanın başında belirtilmiştir.

## İletişim

Gizlilik politikası hakkında sorularınız varsa:

**E-posta:** tastay2@gmail.com  
**Geliştirici:** MutaLabs

## Yasal Uyumluluk

Bu uygulama aşağıdaki düzenlemelere uygundur:
- KVKK (Türkiye Kişisel Verilerin Korunması Kanunu)
- GDPR (Avrupa Genel Veri Koruma Yönetmeliği) - geçerli olduğu ölçüde
- Google Play Geliştirici Program Politikaları

---

**QREX**, kullanıcı gizliliğini korumaya kararlıdır. Tüm veriler cihazınızda kalır ve sizin kontrolünüzdedir.

# Privacy Policy - QREX

**Last Updated:** October 15, 2026

## Introduction

QREX ("we", "the app") takes the privacy of its users seriously. This privacy policy explains what information the QREX app collects, how it uses it, and how it protects it.

## Information Collected

### 1. Camera Permission
**Purpose:** QR code scanning  
**Use:** Camera access is used solely to scan QR codes. Camera images stay on your device and are never sent to any server.  
**Data Retention:** Camera images are not stored; QR codes are only detected momentarily.

### 2. Location Permission
**Purpose:** Adding location information to QR codes (optional feature)  
**Use:** Location information is only added to QR code content when the user requests it. Location data is not sent to any server.  
**Data Retention:** Location information is only stored locally inside the QR code you create.

### 3. Gallery and File Access
**Purpose:**
- Saving QR codes to the gallery
- Gallery access for adding logos/images
- Scanning QR codes from gallery images

**Use:** Gallery access is only used with user approval and for the stated actions.  
**Data Retention:** Selected images are stored locally on the device and never uploaded to any server.

### 4. Internet Permission
**Purpose:**
- Opening URLs contained in QR codes
- Social media sharing
- Integration with email/SMS/map apps

**Use:** The internet connection is only used for user-initiated actions (e.g. opening a URL in the browser).  
**Data Transfer:** No user data is sent to our servers. All internet traffic goes directly from the user's device to the target services.

## Data Sharing and Third-Party Services

QREX does not share any personal data with third parties. The app:

- ✅ **Works Fully Offline:** QR code creation and scanning happen on-device
- ✅ **No Servers:** No central servers are used
- ✅ **No Analytics:** User behavior is not tracked
- ✅ **No Ads:** No third-party advertising services are used

## Data Security

### Encrypted QR Codes
The app offers encryption for QR codes containing sensitive information:
- Passwords are hashed on-device before storage
- Encrypted data is stored only on the device
- Passwords are never sent to any server

### Local Storage
All QR code history and settings are stored in the device's local memory:
- Data is kept on-device using encrypted local storage (flutter_secure_storage / EncryptedSharedPreferences)
- All data is deleted when the app is uninstalled
- No cloud synchronization is performed

## Children's Privacy

QREX does not knowingly collect personal information from children under 13. Parents should supervise their children's use of the app.

## User Rights

Users have the following rights:

1. **Data Deletion:** Delete all QR history from the app settings
2. **Permission Revocation:** Revoke permissions at any time from device settings
3. **Data Export:** Export your QR codes as a file

## Use of Permissions

| Permission | Required? | Purpose |
|------------|-----------|---------|
| Camera | No* | QR code scanning |
| Location | No | Adding location to QR (optional) |
| Gallery | No | Saving QRs and adding logos |
| Internet | No** | Opening URLs, sharing |

*QR scanning does not work without camera permission, but QR creation does  
**URLs do not open automatically without internet permission

## Changes

This privacy policy may be updated. Significant changes will be announced inside the app. The last update date is shown at the top of this page.

## Contact

If you have questions about this privacy policy:

**Email:** tastay2@gmail.com  
**Developer:** MutaLabs

## Legal Compliance

This app complies with the following regulations:
- KVKK (Turkish Personal Data Protection Law)
- GDPR (EU General Data Protection Regulation) - to the extent applicable
- Google Play Developer Program Policies

---

**QREX** is committed to protecting user privacy. All data stays on your device and under your control.

