# 📖 Gönülden Nağmeler — Nur Kendir

> *"Sessizlikte Gizlenen Asalet, Kırık Kalpler ve Tevekkül Durağı"*

Bu proje, **Nur Kendir**'in ([@hafsa_ennur38](https://www.instagram.com/hafsa_ennur38/)) Instagram hesabında paylaştığı 95 özgün görsel ve edebi metnin derlendiği, modern tipografi ve geleneksel kitap estetiği ile tasarlanmış dijital kitap ve web sitesidir.

---

## ✨ Özellikler

- 📜 **95 Bölümlük Tam Arşiv:** Her gönderinin hem ana görsel aforizması hem de alt tefekkür metni eksiksiz yer alır.
- 🔍 **Canlı Arama & Filtreleme:** Arama çubuğu üzerinden başlık ve metinler içinde anında arama yapılabilir.
- 📊 **Okuma İlerleme Çubuğu:** Sayfayı kaydırdıkça okuma durumunu gösteren zarif gösterge.
- 📑 **İçindekiler Fihristi:** 6 ana tematik bölüme ayrılmış hızlı atlama fihristi:
  1. *Duruş ve Asalet (Sükûtun Gücü & Şahsiyet)*
  2. *Kırık Kalpler ve Yaralar (Dert, Hüzün ve İmtihan)*
  3. *Hakiki Sevgi ve İnsan İlişkileri (Vefa, Dostluk ve Mesafe)*
  4. *Tevekkül, Dua ve İlahi Adalet (Hüküm Yalnız Allah’ındır)*
  5. *Zaman, Gençlik ve Ahir Zaman (Dünyanın Faniliği)*
  6. *Kudüs ve Ümmet Bilinci (Gazze, Diriliş ve Onur)*
- 🖨️ **Baskı & PDF Modu:** Tek tuşla temiz, sayfa numaralı ve kitap formatında PDF çıktısı alma desteği.
- 📱 **Duyarlı Tasarım:** Telefonlarda uzun metin ve hashtag satırları taşmadan kırılır; dar ekranlarda kart başlıkları ve bağlantılar alt alta yerleşir. Üst menü iki satıra iner, dokunmatik kontroller en az 44 px alana sahiptir.
- ⚡ **Sıfır Bağımlılık:** Hızlı yüklenen, harici çerçeve (framework) gerektirmeyen saf HTML5, CSS3 ve modern JavaScript.

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
