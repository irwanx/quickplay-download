# 🎬 QuickPlay - Modern Streaming App

<div align="center">

[![Platform](https://img.shields.io/badge/Platform-Android-green?style=for-the-badge&logo=android)](https://github.com/irwanx/quickplay-download/releases)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter)](https://flutter.dev)
[![Node.js](https://img.shields.io/badge/Node.js-339939?style=for-the-badge&logo=nodedotjs)](https://nodejs.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![Version](https://img.shields.io/badge/Version-v1.1.8-orange?style=for-the-badge)](https://github.com/irwanx/quickplay-download/releases)

</div>

> **Aplikasi streaming drama Asia all-in-one dengan tampilan modern, performa cepat, dan 21 provider konten dari seluruh dunia.**

---

## 🔄 Cara Kerja Sistem

```mermaid
graph LR
    subgraph User
        A[Android App] --> B[Flutter Web]
        A --> C[Next.js Web]
        A --> D[Telegram Bot]
    end
    
    subgraph Backend
        E[api-drama Node.js] --> F[Express Server]
        F --> G[Redis Cache]
        F --> H[MySQL Database]
        F --> I[Proxy Service]
    end
    
    subgraph Scraping
        J[21 Platform Providers] --> K[Axios + Cheerio]
        K --> L[Data Normalization]
    end
    
    E --> J
    I --> E
    
    style A fill:#02569B,color:#fff
    style E fill:#339939,color:#fff
    style J fill:#FF6B6B,color:#fff
```

---

## ✨ Demo

| Platform     | Link                                            |
| ------------ | ----------------------------------------------- |
| Next.js Web  | [m.quickplay.my.id](https://m.quickplay.my.id)  |
| Flutter Web  | [quickplay.my.id](https://quickplay.my.id)      |
| Telegram Bot | [quickplaystrbot](https://t.me/quickplaystrbot) |

---

## 🌐 21 Provider Terintegrasi

|                                         Provider                                         |                                         Provider                                         |                                        Provider                                        |
| :--------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: |
|     <img src="https://api-drama.dobda.id/logo/melolo.png" height="30"><br>**Melolo**     |   <img src="https://api-drama.dobda.id/logo/dramabox.png" height="30"><br>**DramaBox**   |  <img src="https://api-drama.dobda.id/logo/shortmax.png" height="30"><br>**ShortMax**  |
|  <img src="https://api-drama.dobda.id/logo/reelshort.png" height="30"><br>**ReelShort**  |   <img src="https://api-drama.dobda.id/logo/netshort.png" height="30"><br>**NetShort**   | <img src="https://api-drama.dobda.id/logo/meloshort.png" height="30"><br>**MeloShort** |
| <img src="https://api-drama.dobda.id/logo/flickreels.png" height="30"><br>**FlickReels** |  <img src="https://api-drama.dobda.id/logo/freereels.png" height="30"><br>**FreeReels**  | <img src="https://api-drama.dobda.id/logo/dramawave.png" height="30"><br>**DramaWave** |
| <img src="https://api-drama.dobda.id/logo/snackshort.png" height="30"><br>**SnackShort** |   <img src="https://api-drama.dobda.id/logo/fundrama.png" height="30"><br>**FunDrama**   | <img src="https://api-drama.dobda.id/logo/starshort.png" height="30"><br>**StarShort** |
|     <img src="https://api-drama.dobda.id/logo/flextv.png" height="30"><br>**FlexTV**     |  <img src="https://api-drama.dobda.id/logo/dramarush.png" height="30"><br>**DramaRush**  |   <img src="https://api-drama.dobda.id/logo/rapidtv.png" height="30"><br>**RapidTV**   |
|  <img src="https://api-drama.dobda.id/logo/dramapops.png" height="30"><br>**Dramapops**  |  <img src="https://api-drama.dobda.id/logo/goodshort.png" height="30"><br>**GoodShort**  |   <img src="https://api-drama.dobda.id/logo/reelife.png" height="30"><br>**Reelife**   |
|  <img src="https://api-drama.dobda.id/logo/dramanova.png" height="30"><br>**DramaNova**  | <img src="https://api-drama.dobda.id/logo/stardusttv.png" height="30"><br>**StardustTV** | <img src="https://api-drama.dobda.id/logo/dramabite.png" height="30"><br>**DramaBite** |

## 🌍 13 Supported Languages

|                  |               |                  |
| :--------------- | :------------ | :--------------- |
| 🇮🇩 **Indonesian** | 🇬🇧 **English** | 🇯🇵 **Japanese**   |
| 🇰🇷 **Korean**     | 🇹🇭 **Thai**    | 🇸🇦 **Arabic**     |
| 🇧🇷 **Portuguese** | 🇪🇸 **Spanish** | 🇻🇳 **Vietnamese** |
| 🇩🇪 **German**     | 🇫🇷 **French**  | 🇮🇹 **Italian**    |
| 🇹🇷 **Turkish**    |               |                  |

---

## 🚀 Fitur Unggulan

### Multi-Language Content
Mendukung **13 bahasa** dari seluruh dunia.

### Smart Video Player
- HLS (m3u8) & MP4 via `media_kit`
- Subtitle WebVTT (auto-convert SRT→WebVTT)
- Quality selection (720p, 1080p, auto)
- Persistent fit settings
- Auto-play next episode

### Progressive Search
Pencarian ke **semua 21 provider secara paralel** — hasil muncul satu per satu.

### Watch History & My List
- Progress per-episode tersimpan lokal
- History dock di profil
- My List — bookmark favorit
- Swipe-to-delete

### UI Premium
- Material Design 3 + tema Light/Dark
- Skeleton loading via shimmer
- Banner carousel featured content
- Glassmorphism navigasi
- Responsive — mobile, tablet, web, desktop

### Community & Feedback
- Papan komunitas antar pengguna
- Form feedback dengan lampiran gambar

---

## 📱 Screenshots

### Utama

|                       Home                       |                       Detail                       |                       Video                       |
| :----------------------------------------------: | :------------------------------------------------: | :-----------------------------------------------: |
| <img src="assets/images/home.jpg" width="200" /> | <img src="assets/images/detail.jpg" width="200" /> | <img src="assets/images/video.jpg" width="200" /> |
|                _Tampilan Beranda_                |                  _Halaman Detail_                  |                _Player Streaming_                 |

### Navigasi

|                       Search                       |                       Discover                       |                     My List                      |
| :------------------------------------------------: | :--------------------------------------------------: | :----------------------------------------------: |
| <img src="assets/images/search.png" width="200" /> | <img src="assets/images/discover.png" width="200" /> | <img src="assets/images/suka.jpg" width="200" /> |
|                 _Pencarian Cepat_                  |                  _Jelajahi Konten_                   |                 _Drama Favorit_                  |

### Profil & Pengaturan

|                       Profile                       |                      Community                       |
| :-------------------------------------------------: | :--------------------------------------------------: |
| <img src="assets/images/profile.png" width="200" /> | <img src="assets/images/comunity.png" width="200" /> |
|                _Profil & Pengaturan_                |                 _Komunitas Pengguna_                 |

### Settings

|                       Settings 1                       |                       Settings 2                       |                       Settings 3                       |
| :----------------------------------------------------: | :----------------------------------------------------: | :----------------------------------------------------: |
| <img src="assets/images/settings 1.png" width="200" /> | <img src="assets/images/settings 2.png" width="200" /> | <img src="assets/images/settings 3.jpg" width="200" /> |
|                  _Pengaturan - Tema_                   |                 _Pengaturan - Bahasa_                  |                _Pengaturan - Pemutaran_                |

---

## ⬇️ Download & Install

### Situs Resmi
👉 **[https://quickplay.my.id/landing](https://quickplay.my.id/landing)**

### GitHub Releases
1. Buka **[Releases](https://github.com/irwanx/quickplay-download/releases)**
2. Pilih versi terbaru
3. Unduh `.apk` (contoh: `QuickPlay-v1.1.8.apk`)
4. Install — izinkan **"Unknown Sources"**

---

## ⚠️ Legal Disclaimer & DMCA Policy

**QuickPlay** adalah proyek open source untuk **tujuan edukasi** dalam pengembangan aplikasi mobile dengan Flutter dan backend Node.js.

### Konten
- Pengembang **tidak menghosting, menyimpan, atau mendistribusikan** media apapun
- Aplikasi ini hanya sebagai interface/client yang mengambil konten yang tersedia secara publik di internet
- Semua konten media, gambar, dan deskripsi adalah milik pemilik masing-masing
- Data dikontrol otomatis oleh user, server hanya proxy (tidak menyimpan media)

### Tanggung Jawab
- Pengguna bertanggung jawab penuh untuk mematuhi hukum setempat terkait streaming/pengunduhan konten
- Penggunaan untuk tujuan Edukasi/Belajar - Dilarang untuk memperjualbelikan proyek ini

### DMCA Policy
- Kami menghormati hak kekayaan intelektual dan DMCA
- Jika Anda menemukan pelanggaran hak cipta, silakan hubungi kami langsung
- Kami akan segera menindaklanjuti permintaan removal yang valid

### Keamanan Data
- Server melakukan **pembersihan data otomatis setiap 3 jam** via cron job
- Redis cache di-flush secara berkala, tidak ada media yang disimpan permanen
- MySQL database di-truncate secara periodik

### Lisensi
Proyek ini dilisensikan di bawah **MIT License** — lihat file [LICENSE](LICENSE).

---

<div align="center">

Built with ☕ by **Irwan (dobda.id)**

</div>
