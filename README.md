# Flutter_FarahNasywa_2208107010051

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## 🙋‍♀️ Author
(Farah Nasywa - 2208107010051)
Proyek ini dibuat sebagai tugas untuk mata kuliah Pemrograman Berbasis Mobile. 

# 📰 News Portal App - Flutter

Aplikasi **Portal Berita** ini dibangun menggunakan Flutter. Aplikasi ini menampilkan daftar berita teknologi dari TechCrunch melalui API, serta dilengkapi dengan fitur kategori, detail berita, login, dan registrasi pengguna.

---

## ✨ Fitur Aplikasi
- 🔐 **Login & Registrasi**  
  Menggunakan API sederhana dan `shared_preferences` untuk menyimpan token.

- 📰 **Tampilan Berita Utama (Home)**  
  Menampilkan list berita dari [NewsAPI.org](https://newsapi.org/) berdasarkan sumber TechCrunch.

- 📂 **Kategori Berita**  
  Menampilkan ikon-ikon kategori seperti General, Transportasi, Entertainment, dengan efek toast ketika dipilih.

- 📄 **Detail Berita**  
  Menampilkan halaman detail berita yang diklik, lengkap dengan gambar, judul, waktu, dan isi berita.

- 👤 **Profil Page**  
  Menampilkan nama user yang login, serta tombol logout.
---

## 🧰 Teknologi & Package
- [Flutter](https://flutter.dev/) - Framework utama
- [http](https://pub.dev/packages/http) - Mengambil data dari API
- [shared_preferences](https://pub.dev/packages/shared_preferences) - Menyimpan data user
- [curved_navigation_bar](https://pub.dev/packages/curved_navigation_bar) - Navigasi bawah melengkung
- [fluttertoast](https://pub.dev/packages/fluttertoast) - Menampilkan pesan kecil

---

## 📥 Cara Menjalankan Aplikasi
1. Clone repo ini:
   ```bash
   git clone https://github.com/farahNasywa/Flutter_FarahNasywa_2208107010051.git
   cd News-Portal-with-Flutter
   ```
2. Jalankan perintah
   ```bash 
   flutter pub get
   ```
3. Jalankan aplikasi 
   ```bash
   flutter run
   ```

# 📁 Struktur Folder
Berikut ini adalah struktur file utama pada aplikasi:
```bash
lib/
├── main.dart             # Entry point aplikasi
├── home.dart             # Halaman utama berita
├── detail.dart           # Detail dari berita
├── kategori.dart         # Pilihan kategori berita
├── profil.dart           # Halaman profil pengguna
├── formlogin.dart        # Form login pengguna
└── formregist.dart       # Form registrasi pengguna
```
# 📸 Cuplikan Layar
![WhatsApp Image 2025-05-19 at 13 29 17](https://github.com/user-attachments/assets/48174f4d-602a-49ad-b23e-ebc4acd4c6a2)
![WhatsApp Image 2025-05-19 at 13 29 17 (2)](https://github.com/user-attachments/assets/9bcf2163-dc8e-4ddb-be20-3862bab8da94)
![WhatsApp Image 2025-05-19 at 13 29 17 (1)](https://github.com/user-attachments/assets/e7234854-b0da-40cc-9728-4f72d8164ad6)
![WhatsApp Image 2025-05-19 at 13 29 17 (3)](https://github.com/user-attachments/assets/e3bbe57e-9ccb-4af5-9c7b-f660b09cce28)
![WhatsApp Image 2025-05-19 at 13 29 18](https://github.com/user-attachments/assets/0c64a867-9e69-4c68-bf6d-113d4b56c28c)
![WhatsApp Image 2025-05-19 at 13 29 18 (1)](https://github.com/user-attachments/assets/6b0e7ca9-0757-4ba4-aee5-a00fe8839757)



