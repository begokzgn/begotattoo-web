# 🖤 Web Boilerplate — Bego Studio

Tüm freelance web projelerinin başlangıç şablonu.

---

## 📁 Klasör Yapısı
proje-adi/
├── index.html        → Ana sayfa
├── tasarim.txt       → Proje context dosyası (her işte doldur)
├── README.md         → Proje notları
├── css/              → Özel CSS (gerekirse)
├── js/               → Özel JS (gerekirse)
└── img/              → Görseller, og-image.jpg buraya
---

## 🚀 Yeni Proje Başlatırken

```bash
# 1. Boilerplate'i kopyala
cp -r web-boilerplate yeni-proje-adi

# 2. Klasöre gir
cd yeni-proje-adi

# 3. tasarim.txt'yi doldur
# 4. Claude'a ver, index.html'i özelleştir
# 5. GitHub'a push et
# 6. Cloudflare Pages'e bağla
```

---

## ⚙️ Tech Stack

| Araç | Kullanım |
|------|----------|
| HTML5 | Yapı |
| Tailwind CSS | Stil (CDN) |
| Alpine.js | Minimal JS (hamburger, form) |
| GitHub | Versiyon kontrolü |
| Cloudflare Pages | Hosting + Deploy |

---

## 🎨 Tasarım Kuralları

- **Tema:** Rich Black koyu
- **Köşeler:** Zero-radius (keskin)
- **Efekt:** Glassmorphism (.glass class hazır)
- **Responsive:** Mobile-first
- **Accent renk:** Her projede tasarim.txt'den alınır

---

## 📋 Deploy Adımları

1. `git init` → `git add .` → `git commit -m "ilk commit"`
2. GitHub'da yeni repo aç, push et
3. Cloudflare Pages → Connect to Git → repo seç
4. Build ayarı yok (statik HTML), direkt deploy
5. Müşteri domainini Cloudflare'e bağla

---

## ✅ Her Teslimden Önce Kontrol

- [ ] Tüm `BURAYA` placeholder'ları dolduruldu
- [ ] Mobilde test edildi
- [ ] Meta description yazıldı
- [ ] og:image yüklendi
- [ ] Tüm linkler çalışıyor
- [ ] Form test edildi
- [ ] Cloudflare'de yeşil (deploy OK)

---

*Bego Studio © 2026*
