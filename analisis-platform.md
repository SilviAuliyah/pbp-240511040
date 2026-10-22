# Analisis Komparatif Platform (Web, Desktop, dan Mobile)

Dokumen ini berisi analisis komparatif antara tiga platform utama dalam pengembangan perangkat lunak: Web, Desktop, dan Mobile.

## Tabel Komparasi Platform

| Aspek | Web | Desktop | Mobile |
| :--- | :--- | :--- | :--- |
| **Bahasa utama** | JavaScript, TypeScript, HTML, CSS, PHP, Python | C++, C#, Java, Python, Swift, Go | Java, Kotlin, Swift, Dart (Flutter), JavaScript (React Native) |
| **Arsitektur** | Client-Server, Web APIs, Microservices, Single Page Application (SPA), Progressive Web App (PWA) | Monolithic, Client-Server, Event-Driven Architecture, Component-Based | Client-Server, Model-View-Controller (MVC), Model-View-ViewModel (MVVM), Clean Architecture |
| **Cara distribusi** | Dihosting pada web server dan diakses langsung oleh pengguna melalui browser tanpa perlu instalasi | Menggunakan file installer (.exe, .msi, .dmg, .deb) atau didistribusikan melalui App Store resmi (Microsoft Store, Mac App Store) | Melalui toko aplikasi resmi (Google Play Store, Apple App Store) atau file paket instalasi (.apk, .ipa) |
| **Keunggulan** | Multiplatform (cross-platform) tanpa instalasi, pembaruan aplikasi terpusat secara real-time, tidak memakan memori penyimpanan lokal | Performa sangat tinggi, akses penuh ke hardware/resource sistem lokal, dapat beroperasi secara offline | Portabel dan fleksibel, akses sensor perangkat keras bawaan (GPS, kamera, akselerometer), mendukung push notification |
| **Keterbatasan** | Sangat tergantung pada koneksi internet, akses fitur hardware terbatas oleh browser, rentan dari sisi keamanan client | Proses instalasi dan update relatif kompleks, ketergantungan pada sistem operasi tertentu (OS-dependent) | Ukuran layar terbatas, keterbatasan memori (RAM) dan daya baterai, aturan publikasi toko aplikasi cukup ketat |
| **Contoh aplikasi** | Google Docs, Canva, Figma (Web), Trello | Visual Studio Code, Adobe Photoshop, Microsoft Word, Spotify Desktop | WhatsApp Mobile, Instagram, Gojek, Mobile Legends |

---

## Kesimpulan

Berdasarkan analisis komparatif di atas, dapat disimpulkan bahwa tidak ada satu platform tunggal yang paling unggul untuk segala jenis kebutuhan perangkat lunak, karena setiap platform (Web, Desktop, dan Mobile) memiliki karakteristik, keunggulan, serta keterbatasannya masing-masing:

* **Platform Web** sangat unggul dalam hal aksesibilitas dan kemudahan distribusi tanpa instalasi, sehingga sangat cocok untuk aplikasi kolaboratif yang menuntut pembaruan cepat secara real-time.
* **Platform Desktop** menawarkan performa optimal serta kendali penuh terhadap perangkat keras lokal, menjadikannya pilihan utama untuk aplikasi berat yang memerlukan pemrosesan tinggi dan bekerja secara offline.
* **Platform Mobile** memberikan mobilitas tinggi serta pengalaman pengguna yang interaktif dengan memanfaatkan berbagai sensor perangkat genggam secara maksimal.

Pemilihan platform dalam pengembangan perangkat lunak harus disesuaikan secara bijak dengan target pengguna, ketersediaan sumber daya, serta fungsionalitas inti dari aplikasi yang akan dibangun.

---

## Sumber Referensi

1. **MDN Web Docs.** *Web Development and Architecture Overview.* Tersedia di: https://developer.mozilla.org/
2. **Android Developers Documentation.** *Guide to App Architecture.* Tersedia di: https://developer.android.com/topic/architecture
3. **Microsoft Learn.** *Windows Desktop Application Development Documentation.* Tersedia di: https://learn.microsoft.com/en-us/windows/apps/
4. **Sommerville, I. (2016).** *Software Engineering (10th Edition).* Pearson Education.