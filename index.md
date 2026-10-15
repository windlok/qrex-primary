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
