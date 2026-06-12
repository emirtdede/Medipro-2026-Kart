# 🎄 Medipro 2026 Yeni Yıl Kartı (Digital New Year Card)

Medipro ailesi için özel olarak tasarlanmış, 2026 yılına geçişi kutlayan, modern, etkileşimli ve estetik açıdan zengin bir dijital yeni yıl tebrik kartı. 

Bu web uygulaması; şık tasarımı, akıcı animasyonları ve anlamlı mesajları bir araya getirerek kullanıcılara unutulmaz bir kutlama deneyimi sunar.

---

## 🌟 Öne Çıkan Özellikler

- **Premium & Modern Arayüz**: Glassmorphism (cam morfolojisi) kart tasarımı, canlı arka plan geçişleri (radial-gradient), HSL neon parıltılar ve modern tipografi.
- **Etkileşimli Slayt Yapısı**: Medipro ekibinin kültürünü, dayanışmasını, geçmiş yılın emeklerini ve gelecek yıla dair güzel dileklerini aktaran 5 aşamalı akıcı slayt geçişi.
- **Dinamik Kar Yağışı (Canvas)**: Arka planda kesintisiz ve performans dostu bir şekilde akan HTML5 Canvas tabanlı kar tanesi animasyonu.
- **Etkileşimli Çam Ağacı ve Neon Işıklar**: Ekranın sağ alt köşesinde yer alan, JavaScript ile her 900ms'de bir rastgele HSL neon renkleriyle parıldayan ve animasyon hızları değişen ışıklara sahip animasyonlu çam ağacı.
- **Sinematik Video Kapanışı**: Slaytların tamamlanmasının ardından (`🎄` butonuna basıldığında veya son slaytta sola kaydırıldığında) akıcı bir geçişle devreye giren tam ekran döngüsel video overlay (`newyear.mp4`).
- **Mobil Uyumlu Swipe (Kaydırma) Desteği**: Hem masaüstü hem de mobil cihazlarda rahatça kontrol edilebilmesi için dokunmatik ekran kaydırma (touch swipe) hareket duyarlılığı.
- **Erişilebilirlik ve Performans**: 
  - `prefers-reduced-motion: reduce` desteği ile sisteminde animasyonları kapatmış olan kullanıcılara geçişleri kapatarak statik bir deneyim sunar.
  - Clamped font boyutu (`clamp()`) ve dinamik ölçekleme sayesinde her ekran boyutunda mükemmel okunabilirlik.

---

## 🛠️ Kullanılan Teknolojiler

Bu proje, harici hiçbir kütüphane veya ağır framework bağımlılığı olmaksızın, tamamen **Vanilla** (saf) teknolojiler ile yüksek performanslı çalışacak şekilde geliştirilmiştir:

- **HTML5**: Semantik yapı, video oynatma ve canvas yönetimi.
- **CSS3 (Vanilla)**: Modern yerleşim (Flexbox, Grid), özel animasyonlar (`@keyframes`), geçiş efektleri, değişkenler (`:root`) ve duyarlı tasarım.
- **JavaScript (Vanilla)**: Slayt akışı yönetimi, swipe algılama algoritmaları, çam ağacı ışık simülasyonu ve fizik tabanlı kar yağışı motoru.

---

## 📂 Proje Yapısı

```text
Medipro-2026-Kart/
├── index.html        # Projenin tüm arayüzü, stilleri (CSS) ve mantıksal kodları (JS)
├── newyear.mp4       # Slayt sonundaki sinematik tam ekran arka plan videosu
└── README.md         # Proje belgelendirmesi
```

---

## 🚀 Çalıştırma Talimatları

Projeyi yerel bilgisayarınızda çalıştırmak oldukça basittir:

1. **Depoyu Klonlayın**:
   ```bash
   git clone https://github.com/emirtdede/Medipro-2026-Kart.git
   ```
2. **Projeyi Başlatın**:
   - `index.html` dosyasına çift tıklayarak doğrudan web tarayıcınızda açabilirsiniz.
   - Veya daha kararlı bir video oynatımı/yükleme deneyimi için VS Code **Live Server** eklentisi gibi basit bir yerel sunucu ile çalıştırabilirsiniz.

---

## 👤 Yazar / Geliştirici
- [emirtdede](https://github.com/emirtdede)

---

*Medipro Ailesinin Yeni Yılı Kutlu Olsun!* 🎄🎉