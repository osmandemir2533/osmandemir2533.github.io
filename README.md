# Osman Demir Kişisel Web Sitesi - Portfolio

Modern, responsive ve kullanıcı dostu bir kişisel web sitesi projesi. React ve Material-UI ile geliştirilmiş, GitHub Pages üzerinde yayınlanmaktadır. SPA (Single Page Application) mimarisi kullanılarak geliştirilmiştir. GitHub Pages'de yayında olan portfolio sitemin Backend kısmında ise dinamik iletişim formu, responsive tasarım ve modern UI/UX prensipleri içerir.

[![Website](https://img.shields.io/badge/Website-Live-1976d2?style=for-the-badge&logo=google-chrome&logoColor=white)](https://osmandemir2533.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/osmandemir2533)

---

## 🚀 Projeyi Çalıştırmak İçin

### Gereksinimler
- Node.js (v14 veya üzeri)
- npm (v6 veya üzeri)

### Kurulum

```bash
# Repoyu klonlayın
git clone https://github.com/osmandemir2533/osmandemir2533.github.io.git

# Proje dizinine gidin
cd osmandemir2533.github.io

# Gerekli paketleri yükleyin
npm install

# Geliştirme sunucusunu başlatın
npm start
```

---

## 📁 Dosya ve Klasör Yapısı

```
osmandemir2533-portfoliowebsite-anakod/
│
├── public/
│   ├── index.html        # Ana HTML dosyası (Google Analytics kodu burada)
│   ├── 404.html          # 404 hata sayfası
│   └── logos/            # Logo dosyaları
│
├── src/
│   ├── assets/
│   │   └── styles/       # SCSS/CSS dosyaları
│   ├── components/
│   │   ├── Footer.js
│   │   ├── Header/...
│   │   └── ScrollToTop.js
│   ├── pages/
│   │   ├── Home.js
│   │   ├── About.js
│   │   ├── Experience.js
│   │   ├── Projects.js
│   │   ├── ProjectDetail.js
│   │   ├── Contact.js
│   │   ├── Games.js
│   │   └── games/        # Oyunların alt dosyaları
│   ├── App.js
│   ├── Routes.js
│   ├── theme.js
│   └── index.js
│
├── package.json
├── webpack.config.js
└── .babelrc
```
### Bundle Edilmiş Proje Yapısı (GitHub Pages'de Yayınlanan)
```
osmandemir2533.github.io/
│
├── index.html            # Ana HTML dosyası
├── 404.html              # 404 hata sayfası
├── bundle.js             # Minified ve optimize edilmiş JavaScript bundle
└── bundle.js.LICENSE.txt # Kullanılan kütüphanelerin lisansları
```

### 🛠️ Kullanılan Teknolojiler ve Kütüphaneler

#### Frontend
- **React**: Modern UI geliştirme
- **Material-UI (MUI)**: UI bileşenleri ve tema
- **React Router DOM**: Sayfa yönlendirme (SPA)
- **Framer Motion**: Animasyonlar
- **SASS/SCSS**: Gelişmiş stil dosyaları
- **Webpack & Babel**: Build ve modern JS desteği
- **Webpack**: Modül bundler ve build tool
- **Babel**: Modern JavaScript özelliklerini eski tarayıcılarda çalıştırmak için
- **react-markdown**: Proje detaylarında markdown desteği
- **Google Analytics (GA4)**: Ziyaretçi takibi
- **FontAwesome**: İkonlar
- **gh-pages**: GitHub Pages deploy

#### Backend (İletişim Formu)
- **Node.js**: Backend runtime
- **Express**: Web framework
- **Nodemailer**: E-posta gönderimi için
- **Render**: Backend hosting platformu

---

### 🗂️ Sayfa Yapısı

1. **Ana Sayfa (Home)**
   > ![Ana Sayfa](https://i.imgur.com/ovvHnHA.png)
   - Hero section
   - Proje Github Yönlendirme
   - Yetenekler ve teknolojiler
   - Smooth scroll navigasyon

2. **Hakkımda (About)**
   > ![Hakkımda](https://i.imgur.com/fvayIV4.png)
   - Kişisel bilgiler
   - Eğitim geçmişi
   - Profesyonel özet

3. **Projelerim (Projects)**
   > ![Projelerim](https://i.imgur.com/WT802Lo.png)
   > ![Projelerim 2](https://i.imgur.com/vkgIArE.png)
   - Tüm projelerinin detaylı listesi, görseller, canlı demo ve GitHub linkleri.
   - Her projeye tıklayınca detay sayfası (ProjectDetail) açılır, burada projenin README'si markdown olarak gösterilir.

4. **Oyunlar (Games)**
   > ![Oyunlar](https://i.imgur.com/GbMGQpW.png)
   > ![Oyunlar2](https://i.imgur.com/FTgWfEX.png)
   > ![Oyunlar3](https://i.imgur.com/ALMJ8Yj.png)
   - Kendi geliştirdiğin oyunlar burada listelenir.
   - **Tic-Tac-Toe:** Flask tabanlı, AI destekli, canlı demo linkiyle.
   - **Galactic Escape:** Kısa açıklama: "Galactic Escape, uzay temalı, refleks ve dikkat gerektiren bir mini browser oyunudur. Hedef: Engellerden kaçarak en yüksek puanı almak."
   - Oyun kartları, görselleriyle birlikte, tıklanınca oynanabilir.

5. **Deneyim (Experience)**
   > ![Deneyim](https://i.imgur.com/thFP9Xf.png)
   - İş deneyimleri
   - Proje deneyimleri
   - Timeline görünümü


6. **İletişim (Contact)**
   > ![İletişim](https://i.imgur.com/XDcgxf6.png)
   - İletişim formu
   - Sosyal medya linkleri
---

### 📊 Google Analytics Entegrasyonu

- Google Analytics (GA4) kodu doğrudan `public/index.html` dosyasına eklenmiştir.
- Ziyaretçi, şehir, trafik kaynağı gibi veriler Google Analytics panelinden izlenebilir.
- Statik siteye hiçbir zararı yoktur, GitHub Pages ile %100 uyumludur.

---

### Teknik Detaylar

#### Bundle.js Açıklaması
- `bundle.js` dosyası, tüm JavaScript kodunun Webpack tarafından optimize edilmiş ve minify edilmiş halidir
- Boyut: 622KB
- İçerik: Tüm React bileşenleri, kütüphaneler ve uygulama mantığı
- Performans optimizasyonları uygulanmıştır

#### Routing
- **HashRouter** kullanıldı (GitHub Pages uyumluluğu için)
- URL formatı: `https://osmandemir2533.github.io/#/sayfa-adi`
- Sayfa geçişlerinde smooth scroll

#### Stil ve Tema
- Material-UI tema sistemi
- Özel renk paleti
- Responsive tasarım
- SCSS modülleri

#### İletişim Formu
- Backend: Render üzerinde host edilen Node.js servisi
- API Endpoint: `https://backendurl.com/api/`
- Form validasyonu
- Başarılı/başarısız durum bildirimleri

#### Performans Optimizasyonları
- Code splitting
- Lazy loading
- Image optimization
- Bundle size optimization

---



### 🕹️ Oyunlar Hakkında

### Tic-Tac-Toe
- Flask tabanlı, AI (Minimax & MCTS) destekli, responsive ve canlı demo.
- [Canlı Oyna](https://tic-tac-toe-2fjq.onrender.com/)

### Galactic Escape
- Uzay temalı, refleks ve dikkat gerektiren mini browser oyunu.
- Oyunlar sayfasından erişilebilir ve oynanabilir.

---
## 📧 İletişim Formu Detayları

İletişim formu, ayrı bir backend servisi üzerinden çalışmaktadır. Backend servisi Render üzerinde host edilmektedir.

### Backend Repository
[websiteEmailPost](https://github.com/osmandemir2533/websiteEmailPost)

### API Endpoint
```
POST https://backend-url.com/api/
Content-Type: application/json

{
  "name": "string",
  "email": "string",
  "message": "string"
}
```

---

## 🔧 Önemli Noktalar

1. GitHub Pages için HashRouter kullanılmalı
2. Tüm asset'ler public klasöründe olmalı
3. Build sonrası dist klasörü deploy edilmeli
4. Backend URL'i environment variable olarak tutulmalı
5. GitHub Pages'de sayfa yenileme sorunu (HashRouter ile çözüldü)
6. Backend CORS ayarları
7. Form gönderimi sonrası state yönetimi

---

## 📬 İletişim

Benimle her zaman iletişime geçebilirsiniz:

[![Web Sitem](https://img.shields.io/badge/Web%20Site-1976d2?style=for-the-badge&logo=google-chrome&logoColor=white)](https://osmandemir2533.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/osmandemir2533/)

---

> Proje, modern web standartlarına uygun olarak geliştirilmiştir.  
> Responsive tasarımı ile tüm cihazlarda sorunsuz çalışır.  
> Statik olarak GitHub Pages'de yayınlanır, Google Analytics ile ziyaretçi takibi yapılır.
