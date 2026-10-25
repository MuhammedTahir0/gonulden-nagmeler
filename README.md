# 📖 Gönülden Nağmeler — Nur Kendir

> *"Sessizlikte Gizlenen Asalet, Kırık Kalpler ve Tevekkül Durağı"*

Bu proje, **Nur Kendir**'in ([@hafsa_ennur38](https://www.instagram.com/hafsa_ennur38/)) Instagram hesabında paylaştığı 95 özgün görsel ve edebi metnin derlendiği, modern tipografi ve geleneksel kitap estetiği ile tasarlanmış dijital kitap ve web sitesidir.

---

## ✨ Özellikler

- 📜 **95 Bölümlük Tam Arşiv:** Her gönderinin hem ana görsel aforizması hem de alt tefekkür metni eksiksiz yer alır.
- **Yatay Gönderi Okuyucu:** Gönderiler tek kart olarak açılır. Telefonda sağa/sola kaydırın; bilgisayarda okuyucu odaktayken yön tuşlarını kullanın. Önceki / sayaç / Sonraki çubuğu hem gönderinin üstünde hem altında bulunur ve birlikte güncellenir. Alt çubuktan geçişte yeni gönderinin başına dönülür; uzun yazılar dikey okunmaya devam eder.
- 🔍 **Canlı Arama & Filtreleme:** Arama çubuğu üzerinden başlık ve metinler içinde anında arama yapılabilir.
- 📊 **Okuma İlerleme Çubuğu:** Sayfayı kaydırdıkça okuma durumunu gösteren zarif gösterge.
- **Açılır-Kapanır İçindekiler:** Altı bölüm başlangıçta kapalıdır; bölüm başlığına tıklayın veya klavyeyle Enter/Space kullanın. Bölümler bağımsız açılıp kapanır, gönderi bağlantıları ilgili kartı açar:
  1. *Duruş ve Asalet*
  2. *Bir Kalbe İyi Gelmek*
  3. *Kendi Elinden Tutmak*
  4. *Nur'un Kaleminden: Seccade ve Tevekkül*
  5. *Gönülden Nağmeler*
  6. *Hikmet Damlaları*
- 🖨️ **Baskı & PDF Modu:** Tek tuşla temiz, sayfa numaralı ve kitap formatında PDF çıktısı alma desteği.
- 📱 **Duyarlı Tasarım:** Telefonlarda uzun metin ve hashtag satırları taşmadan kırılır; dar ekranlarda kart başlıkları ve bağlantılar alt alta yerleşir. Üst menü iki satıra iner, dokunmatik kontroller en az 44 px alana sahiptir.
- ⚡ **Sıfır Bağımlılık:** Hızlı yüklenen, harici çerçeve (framework) gerektirmeyen saf HTML5, CSS3 ve modern JavaScript.

### Alt gezinme çubuğu ve açılır-kapanır bölümler — 2026-10-25

- Gönderinin altına üsttekiyle eşzamanlı çalışan gezinme çubuğu eklendi. Arama, dokunmatik kaydırma, ilk/son gönderi ve sıfır sonuç durumlarında her iki çubuğun sayaçları ve düğmeleri aynı durumu gösterir.
- Fihristte yerel HTML `details` / `summary` kullanılır; açma/kapama JavaScript kapalıyken de çalışır. Yazdırmada bölümler geçici olarak açılır ve ardından kullanıcının açık/kapalı durumu geri yüklenir.
- OMP Gemini 3.8 Flash/high alt ajanıyla gerçek Chromium'da alt/üst düğmeler, dokunmatik kaydırma, fihrist/klavye etkileşimi, arama, yazdırma medyası ve 320/375/430/1440 px yerleşimler kontrol edildi. 95 gönderinin ve fihrist bağlantılarının metinleri korundu. Fiziksel telefon/Safari üzerinde test yapılmadı.

### Yatay kaydırmalı okuma — 2026-10-25

- 95 yazı özgün tematik sırasıyla tek bir yerel yatay kaydırma alanına taşındı; kart yüksekliği aktif yazıya göre değişir. Altı bölüm girişi ve bütün yazı metinleri korundu.
- Arama yalnız eşleşen gönderiler arasında gezinir. Fihrist ve doğrudan gönderi/bölüm bağlantıları ilgili kartı seçer; gerekirse arama filtresini temizler.
- Yazdırma/PDF görünümü, arama filtresi açık olsa bile 95 yazıyı ve altı bölüm girişini dikey kitap düzeninde açar. JavaScript kapalıysa özgün dikey okuma görünümü kullanılabilir.
- OMP Gemini 3.8 Flash/high alt ajanları uyguladı ve gerçek Chromium/CDP dokunma olaylarıyla iki yönde kaydırmayı doğruladı. Kısa/uzun kart yüksekliği, düğmeler, klavye, arama, bağlantılar, yazdırma medyası ve JavaScript kapalı görünüm kontrol edildi; özgün 95 yazının kimlikleri, sırası ve metinleri değişmedi.
- 320–1440 px genişlikler ve yatay telefon görünümünde kontrol edildi. Fiziksel telefon/Safari üzerinde test yapılmadı.

### Mobil uyumluluk düzeltmesi — 2026-10-25

- Uzun ve kesintisiz hashtaglerin 320–430 px ekranlarda sayfayı yaklaşık 709 px'e genişletmesi giderildi; yatay taşma gizlenmedi, metin sarmalama düzeltildi.
- Kapak, fihrist, yazı kartları ve sonsöz için mobil boşluklar ve yazı boyutları düzenlendi. Yapışkan üst menünün fihrist/yazı başlıklarını örtmemesi için dinamik kaydırma mesafesi eklendi.
- OMP Gemini 3.8 Flash/high alt ajanıyla gerçek Chromium'da 320, 375, 390, 430, 768, 1024, 1440 px ve 812×375 yatay görünüm kontrol edildi; belge ve metinlerde yatay taşma görülmedi.
- Arama/eşleşmeyen arama/temizleme, fihrist ve doğrudan yazı bağlantısı, yukarı çık ve yazdırma medyası kontrol edildi. Orijinal dosyayla karşılaştırmada 95 yazının kimlikleri ve metinleri değişmedi.
- Bu kabul tarayıcı cihaz emülasyonudur; fiziksel telefon ve Safari üzerinde test yapılmadı.

---

## 🚀 Vercel'e Yükleme Adımları

Bu repo Vercel için hazır olarak yapılandırılmıştır (`vercel.json` mevcuttur).

1. [vercel.com](https://vercel.com) adresine gidip GitHub hesabınızla giriş yapın.
2. **"Add New..."** butonuna tıklayıp **"Project"** seçin.
3. Repolarınız arasından **`gonulden-nagmeler`** reposunu seçip **"Import"** butonuna basın.
4. Framework Preset olarak **"Other"** kalabilir (herhangi bir derleme ayarına gerek yoktur).
5. **"Deploy"** butonuna basın! Siteniz birkaç saniye içinde canlıya alınacaktır.

---

## 📂 Dosya Yapısı

```
gonulden-nagmeler/
├── index.html                           # Ana web sitesi ve dijital kitap arayüzü
├── vercel.json                          # Vercel dağıtım ve yönlendirme ayarları
├── README.md                            # Proje dokümantasyonu
├── hafsa_ennur38_nur_gonderileri.md     # Ham gönderi ve aforizma dökümü
└── Nur_Kendir_Gonulden_Nagmeler_Kitap.md # Kitap formatındaki Markdown arşivi
```

---

## 🖋️ Yazar

- **Nur Kendir** ([@hafsa_ennur38](https://www.instagram.com/hafsa_ennur38/)) — *muallime🌸 • Hafıza • Radyo Programcısı*
