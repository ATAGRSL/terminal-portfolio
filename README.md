# Terminal Portfolio - Ata Gürsel

Gelişmiş interaktif terminal temalı portfolyo sitesi. Modern web teknolojileri ile oluşturulmuş, gerçekçi terminal deneyimi sunan bir portfolyo uygulaması.

## 🌟 Özellikler

### 🎭 Terminal Simülasyonu
- Gerçekçi terminal arayüzü (siyah arka plan, yeşil metin)
- Komut geçmişi (yukarı/aşağı ok tuşları ile)
- Tab tamamlama özelliği
- Otomatik odaklanma

### 🌧️ Matrix Rain Efekti
- Arka planda çalışan Matrix karakter efekti
- Japonca karakterler ve sayılar
- Performans odaklı animasyon sistemi
- `matrix` komutu ile açma/kapama

### 🔊 Ses Sistemi
- Web Audio API ile gerçekçi terminal ses efektleri
- Klavye sesi, Enter sesi, Hata sesi
- Ses açma/kapama butonu
- 🔊 SES / 🔇 SESSİZ

### 📁 Dosya Sistemi
Gerçekçi Linux terminal komutları:
- `ls` - Dizindeki dosyaları listele
- `cd [dizin]` - Dizini değiştir
- `pwd` - Mevcut dizini göster
- `cat [dosya]` - Dosya içeriğini göster
- `mkdir [dizin]` - Yeni dizin oluştur
- `rm [dosya]` - Dosya/dizin sil

### 👤 Portfolyo Komutları
- `hakkimda` - Kişisel tanıtım
- `projelerim` - GitHub projeleri
- `iletisim` - İletişim bilgileri
- `yardim` - Tüm komutlar

### 🛠️ Araçlar
- `calc [işlem]` - Güvenli hesap makinesi
- `weather [şehir]` - Gerçek hava durumu (API)
- `joke` - Rastgele şakalar (API)
- `fortune` - İlham verici sözler (API)
- `neofetch` - Sistem bilgilerini göster
- `theme [renk]` - Tema değiştirici

### 🎨 Tema Sistemi
6 farklı tema:
- `matrix` - Orijinal Matrix teması
- `red` - Kırmızı tema
- `blue` - Mavi tema
- `green` - Yeşil tema
- `purple/mor` - Mor tema
- `cyberpunk` - Siyah-mor Cyberpunk teması

## 🚀 Kurulum ve Çalıştırma

### Gereksinimler
- Modern web tarayıcısı (Chrome, Firefox, Safari, Edge)
- JavaScript etkin
- Ses desteği için Web Audio API

### Çalıştırma
1. Projeyi indirin veya klonlayın
2. Terminali açın ve proje dizinine gidin
3. HTTP sunucusu başlatın:
   ```bash
   python3 -m http.server 8000
   ```
4. Tarayıcınızda açın:
   ```
   http://localhost:8000/terminal-portfolio.html
   ```

## 💻 Kullanım

Terminal açıldıktan sonra:
1. `yardim` yazıp Enter'a basın - Tüm komutları görün
2. `hakkimda` yazın - Portfolyo bilgilerini görün
3. `theme cyberpunk` yazın - Cyberpunk temasına geçin
4. `weather istanbul` yazın - İstanbul'un hava durumunu öğrenin

## 🛡️ Güvenlik

- `eval()` kullanılmaz - Güvenli `Function()` constructor kullanılır
- Hesap makinesinde sadece güvenli karakterler kabul edilir
- API çağrıları güvenli endpoint'ler ile yapılır
- XSS koruması için HTML sanitization uygulanır

## 🎯 Performans Optimizasyonları

- **Animasyon sistemi**: Renk kodlu metinler için optimize edilmiş
- **API caching**: Gereksiz API çağrılarını önler
- **DOM manipülasyonu**: Minimum seviyede tutulur
- **Memory management**: Döngüsel referanslar temizlenir

## 🏗️ Teknik Detaylar

### Kullanılan Teknolojiler
- **HTML5** - Semantik yapı
- **CSS3** - CSS Variables, Animasyonlar, Flexbox
- **JavaScript (ES6+)** - Async/await, Promise, Web Audio API

### Dosya Yapısı
```
terminal-portfolio/
├── terminal-portfolio.html  # Ana uygulama
└── README.md              # Proje dokümantasyonu
```

### API Entegrasyonları
- **OpenWeatherMap API** - Hava durumu verisi
- **Official Joke API** - Şaka verisi
- **Quotable API** - İlham verici sözler

## 🎮 İnteraktif Özellikler

### Komut Geçmişi
- ↑↓ ok tuşları ile geçmiş komutlara erişim
- Tab tuşu ile komut tamamlama
- Otomatik komut kaydetme

### Animasyon Sistemi
- Typewriter efekti tüm metinlerde
- Renk kodları destekli animasyon
- Ses efektleri ile birlikte çalışır

### Responsive Tasarım
- Tüm ekran boyutlarında çalışır
- Mobil uyumlu
- Dokunmatik ekran desteği

## 📝 Geliştirme

### Yeni Komut Eklemek
```javascript
'komut-adi': (args) => {
    // Komut mantığı
    return ['Çıktı mesajı'];
}
```

### Yeni Tema Eklemek
```javascript
} else if (color === 'yeni-tema') {
    root.style.setProperty('--primary-color', '#renk-kodu');
    return ['[color=#renk-kodu]Yeni tema aktif![/color]'];
}
```

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/yeni-ozellik`)
3. Commit edin (`git commit -am 'Yeni özellik eklendi'`)
4. Push edin (`git push origin feature/yeni-ozellik`)
5. Pull Request oluşturun

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

## 👨‍💻 Geliştirici

**Ata Gürsel**
- **LinkedIn**: https://www.linkedin.com/in/atagursel/
- **GitHub**: https://github.com/ATAGRSL


## 🎯 Son Notlar

Bu terminal portfolyo, modern web teknolojilerinin gücünü gösterecek şekilde tasarlanmıştır. Hem teknik beceri hem de yaratıcılığı bir araya getiren bu proje, interaktif web uygulamaları geliştirmek isteyenler için mükemmel bir örnek teşkil etmektedir.

---

⭐ **Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!**
