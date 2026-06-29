# Gizlilik Politikası — Zikr

**Yürürlük tarihi:** 17 Mayıs 2026
**Son güncelleme:** 28 Haziran 2026

Bu Gizlilik Politikası, **Görkem Yıldırım** ("biz", "geliştirici") tarafından geliştirilen
**Zikr** mobil uygulamasının ("Uygulama") kullanıcılarından
("siz", "kullanıcı") hangi verileri topladığını, bu verileri nasıl kullandığını,
sakladığını ve paylaştığını açıklar.

Uygulamayı kullanarak bu politikayı okuduğunuzu, anladığınızı ve kabul ettiğinizi
beyan etmiş olursunuz.

---

## 1. Sorumlu Veri Yöneticisi

- **Geliştirici:** Görkem Yıldırım (bireysel geliştirici)
- **İletişim:** gorkemyildirim@outlook.com
- **Uygulama Bundle ID:** com.gorkemyildirim.zikr

KVKK (6698 sayılı kanun) ve GDPR (EU 2016/679) bakımından "veri sorumlusu"
yukarıdaki gerçek kişidir.

---

## 2. Topladığımız Veriler

Zikr, gizlilik öncelikli tasarlanmıştır. **Reklam göstermez, sizi izlemez ve
reklam/izleme amacıyla hiçbir kimlik (IDFA/GAID) kullanmaz.** Aşağıdaki kategoriler
dışında **hiçbir kişisel veri toplamayız**.

### 2.1 Cihaz Üzerinde Yerel Olarak Saklanan Veriler

Aşağıdaki veriler **yalnızca cihazınızda**, şifreli yerel depolamada (MMKV) tutulur
ve sunucularımıza **gönderilmez** (Premium Bulut Yedek özelliği etkin olmadıkça —
bkz. madde 4.1):

- Zikir listeniz (başlık, anlam, uzun dua, Arapça metin, hedef, duraklama noktası)
- Sayaç değerleri ve günlük aktivite kayıtları
- Uygulama ayarlarınız (dil, tema, yazı boyutu, titreşim/ses tercihleri)
- Premium üyelik durumu

### 2.2 Satın Alma Verileri

Premium üyelik satın alındığında **Apple App Store StoreKit** üzerinden:

- Anonim satın alma kimliği (transaction ID)
- Satın alma durumu (tek seferlik lifetime ürün — abonelik değil)
- Apple kullanıcı kimliği (bizimle paylaşılmaz; yalnızca Apple ile)

işlenir. Üçüncü taraf abonelik yönetim servisi kullanmıyoruz; tüm satın alma
akışı doğrudan Apple StoreKit üzerinden çalışır.

Apple'ın gizlilik politikası: https://www.apple.com/legal/privacy/

### 2.3 Kilitlenme ve Hata Raporları (Sentry)

Uygulamada Sentry (Functional Software, Inc., EU bölgesi) hata izleme servisi
kullanılır. Sentry'ye yalnızca anonim teknik bilgi gönderilir:

- Yığın izi (stack trace) — kişisel veri içermez
- Cihaz modeli, işletim sistemi sürümü
- Uygulama sürümü, kilitlenme zamanı

Bu veriler **kullanıcıya bağlı değildir**, takip amacı taşımaz, yalnızca
uygulamanın kararlılığını iyileştirmek için kullanılır. Sentry verileri
AB sunucularında (Frankfurt) işlenir.

Sentry gizlilik politikası: https://sentry.io/privacy/

---

## 3. Verileri Nasıl Kullanırız?

- **Yerel veriler**: Uygulamanın temel işlevini (sayaç, ayarlar) sağlamak için
- **Satın alma verileri**: Premium özelliklerini açmak için (tek seferlik
  lifetime satın alma — abonelik değil)
- **Hata verileri**: Uygulama kalitesini iyileştirmek için (anonim)

**Reklam göstermeyiz, sizi izlemeyiz ve hiçbir veriyi üçüncü taraflara satmayız.**

---

## 4. Üçüncü Taraf Hizmetler

| Hizmet                     | Amaç                                      | Veri Akışı                                                        |
| -------------------------- | ----------------------------------------- | ----------------------------------------------------------------- |
| Apple App Store / StoreKit | Satın alma işlemleri (lifetime IAP)       | Apple kullanıcı kimliği (bizimle paylaşılmaz)                     |
| Sentry                     | Kilitlenme ve hata raporlama              | Anonim teknik veri (AB sunucuları)                                |
| Expo / EAS                 | Uygulama dağıtımı, OTA güncelleme         | Yalnızca toplu istatistik                                         |

### 4.1 Premium Bulut Yedek (Gelecek Sürüm)

İleri sürümde Premium kullanıcılar için Supabase tabanlı bulut yedek opsiyonu
sunulacaktır. Bu özelliği etkinleştirirseniz:

- Zikir listeniz ve sayaç verileriniz şifreli olarak Supabase sunucularında
  saklanır
- Apple Sign-In ile hesap kimlik doğrulaması yapılır
- Bu özelliği istediğiniz zaman kapatabilir, verilerinizi silebilirsiniz

---

## 5. Veri Saklama Süresi

- **Yerel veriler**: Uygulamayı silene kadar cihazınızda kalır
- **Satın alma verileri**: Apple tarafında, yasal yükümlülükler süresince
- **Hata raporları**: 90 gün

---

## 6. Kullanıcı Haklarınız (KVKK ve GDPR)

Aşağıdaki haklara sahipsiniz:

- **Erişim**: Hakkınızda tuttuğumuz verilere erişme
- **Düzeltme**: Yanlış verilerin düzeltilmesini isteme
- **Silme** ("unutulma hakkı"): Uygulamayı kaldırarak yerel verilerin tümünü
  silebilirsiniz. Apple/Google verileri için doğrudan ilgili hizmete
  başvurun veya bizim aracılığımızla talep edin.
- **Taşınabilirlik**: Verilerinizin yapılandırılmış bir formatta verilmesini isteme
- **İtiraz**: Verilerinizin işlenmesine itiraz etme

Taleplerinizi `gorkemyildirim@outlook.com` adresine yazabilirsiniz; en geç **30 gün**
içinde yanıt veririz.

---

## 7. Çocukların Gizliliği

Uygulama **4+ yaş** olarak derecelendirilmiştir, ancak özellikle 13 yaş altındaki
çocuklara yönelik **değildir**. 13 yaş altı bir çocuktan bilerek veri toplamayız.
Çocuğunuzun bize veri ilettiğine inanıyorsanız lütfen iletişime geçin; verileri
sileriz.

---

## 8. Çerezler ve Yerel Depolama

Uygulama mobil cihazda çerez kullanmaz. Ancak yerel depolama (MMKV) tercihlerinizi
saklamak için kullanılır. Uygulamayı silerek tüm yerel veriyi temizleyebilirsiniz.

---

## 9. Veri Güvenliği

- Yerel veriler MMKV tabanlı şifreli depolamada saklanır
- Satın alma verileri TLS üzerinden iletilir
- Apple Sign-In ile Apple'ın güvenlik altyapısı kullanılır
- Hiçbir parola veya hassas finansal veri sunucularımızda saklanmaz

---

## 10. Politika Değişiklikleri

Bu politikayı zaman zaman güncelleyebiliriz. Önemli değişiklikleri uygulama içi
bildirim veya bu sayfanın güncellenmesi yoluyla bildiririz. "Son güncelleme"
tarihi en üstte yer alır.

---

## 11. İletişim

Soru, talep veya şikayetleriniz için:

- **E-posta:** gorkemyildirim@outlook.com
- **Konu:** "Zikr — Gizlilik"

Türkiye'de yerleşik kullanıcılar için: Kişisel Verileri Koruma Kurumu'na (KVKK)
şikayet hakkınız saklıdır — https://www.kvkk.gov.tr

EU/EEA kullanıcıları için: yerel veri koruma otoritenize başvurma hakkınız vardır.
