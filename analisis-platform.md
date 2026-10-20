# Analisis Komparatif Platform: Web, Desktop, dan Mobile

**Mata Kuliah:** Pemrograman Berbasis Platform
**Nama:** Fajri Nurshodiq
**NIM:** 240511171

## Tabel Perbandingan

| Aspek | Web | Desktop | Mobile |
|---|---|---|---|
| **Bahasa utama** | HTML, CSS, JavaScript/TypeScript (frontend); PHP, Python, Node.js, Java, dll. (backend) | C++, C#, Java, Python; Electron memakai JavaScript | Kotlin dan Java (Android); Swift (iOS); Dart/Flutter dan JavaScript/React Native untuk lintas platform |
| **Arsitektur** | Client-server: browser (client) meminta data ke server melalui HTTP/HTTPS, biasanya lewat REST API atau GraphQL | Aplikasi berjalan langsung di sistem operasi lokal dan mengakses sumber daya perangkat (file, memori, perangkat keras) secara langsung; bisa standalone atau terhubung ke server | Aplikasi berjalan di OS mobile (Android/iOS) dengan siklus hidup aplikasi, sandbox keamanan, dan izin (permission) per fitur; umumnya terhubung ke backend via API |
| **Cara distribusi** | Diakses lewat URL di browser; di-deploy ke server/hosting/cloud tanpa instalasi oleh pengguna | Installer (.exe, .msi, .dmg, .deb), portable app, atau toko aplikasi seperti Microsoft Store | Toko aplikasi resmi (Google Play Store, Apple App Store) atau file APK untuk Android |
| **Keunggulan** | Lintas platform lewat browser; tidak perlu instalasi; pembaruan langsung untuk semua pengguna; biaya distribusi rendah | Performa tinggi; akses penuh ke perangkat keras dan sistem file; dapat berjalan offline; cocok untuk aplikasi berat | Portabel dan selalu dibawa pengguna; akses sensor (GPS, kamera, akselerometer); notifikasi push; pengalaman sentuh yang natural |
| **Keterbatasan** | Bergantung pada koneksi internet dan performa browser; akses perangkat keras terbatas; rentan terhadap isu keamanan web | Harus dibuat/disesuaikan per sistem operasi (kecuali memakai framework lintas platform); instalasi dan pembaruan dilakukan di tiap perangkat | Ukuran layar dan baterai terbatas; fragmentasi perangkat/versi OS (terutama Android); proses review toko aplikasi; kebijakan dan biaya developer account |
| **Contoh aplikasi** | Google Docs, Tokopedia (versi web), Wikipedia | Microsoft Word, Adobe Photoshop, Visual Studio Code | WhatsApp, Gojek, Instagram |

## Referensi

1. W3C. *Web Standards*. https://www.w3.org/standards/
2. Microsoft. *.NET Multi-platform App UI (.NET MAUI) Documentation*. https://learn.microsoft.com/en-us/dotnet/maui/
3. Apple. *Apple Developer Documentation*. https://developer.apple.com/documentation/

## Refleksi

1. **Dari ketiga platform, saya paling tertarik mempelajari Web. karena web terasa paling dekat dengan keseharian saya, Hampir setiap hari saya membuka website tanpa perlu menginstal apa pun, dan lama-lama saya jadi penasaran bagaimana semua itu dibuat. Menurut saya web juga paling ramah untuk pemula karena tutorial dan dokumentasinya banyak dan gratis. Selain itu, saya merasa bekal HTML, CSS, dan JavaScript nanti bisa membantu saya belajar platform lain seperti Desktop dan Mobile.

2. **Tantangan terbesar saya saat setup adalah menginstal Node.js. Setelah instalasi selesai, saya mengetik `node --version` di terminal, tetapi perintahnya tidak dikenali. Jujur, saya sempat bingung dan mengira file yang saya unduh salah versi, jadi saya mengunduhnya ulang. Hasilnya tetap sama dan saya merasa waktu saya terbuang. Setelah mencari tutorial di YouTube dan bertanya ke teman yang sudah berhasil, barulah saya paham bahwa masalahnya ada pada PATH environment variable yang belum saya atur.

3. **Dari pengalaman ini saya belajar untuk tidak langsung mengunduh ulang saat ada error. Rencana saya ke depan membaca pesan error dengan teliti, memeriksa PATH, lalu mencari solusi di dokumentasi resmi sebelum bertanya ke teman. Saya juga akan mencatat langkah yang berhasil supaya kalau harus setup ulang, saya tidak mengulangi kesalahan yang sama.