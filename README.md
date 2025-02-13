# 🚀 CMS WordPress  

Selamat datang di repositori *CMS WordPress! Repositori ini berisi file inti **WordPress, salah satu **Content Management System (CMS)* paling populer yang digunakan untuk membangun berbagai jenis situs web, mulai dari blog pribadi hingga e-commerce dan website perusahaan.  

## 📖 Tentang WordPress  
WordPress adalah CMS open-source berbasis PHP dan MySQL yang memberikan fleksibilitas tinggi dalam pengelolaan konten. Dengan ribuan tema dan plugin yang tersedia, WordPress dapat disesuaikan sesuai dengan kebutuhan pengguna.  

---

## ✨ Fitur Utama  
✅ *Mudah Digunakan* – Instalasi cepat dengan antarmuka intuitif  
✅ *SEO-Friendly* – Fitur bawaan untuk optimasi mesin pencari (SEO)  
✅ *Dukungan Tema & Plugin* – Ribuan tema dan plugin gratis serta premium  
✅ *Keamanan & Pembaruan Rutin* – Sistem keamanan yang diperbarui secara berkala  
✅ *Manajemen Konten yang Fleksibel* – Mendukung berbagai jenis media dan format konten  

---

## 📥 Instalasi WordPress  
Ikuti langkah-langkah berikut untuk menginstal WordPress di server lokal atau hosting.  

### 1️⃣ Clone Repositori  
Jalankan perintah berikut di terminal atau command prompt:  
bash
$ apt install git
$ git clone https://github.com/CyberDaviid/CMS-WordPress.git

### 2️⃣ Konfigurasi Database  
1. *Buat Database Baru* di MySQL/MariaDB.  
2. **Edit file konfigurasi wp-config.php**, sesuaikan dengan detail database:  
   php
   define('DB_NAME', 'nama_database');
   define('DB_USER', 'username_database');
   define('DB_PASSWORD', 'password_database');
   define('DB_HOST', 'localhost'); 
   
3. Simpan file **wp-config.php**.  

### 3️⃣ Jalankan Instalasi  
- Untuk *server lokal*, akses:  
  
  1. http://localhost/NamaRepositori/
  2. Jikan mengunakan domain: http://domain/
  
- Untuk *hosting web*, akses domain yang digunakan.  
- Ikuti wizard instalasi, masukkan informasi situs, dan buat akun admin.  

---

## ⚙ Spesifikasi Server  
Untuk menjalankan WordPress dengan baik, pastikan server memenuhi spesifikasi berikut:  

| Komponen  | Spesifikasi Minimum | Rekomendasi |
|-----------|--------------------|-------------|
| *PHP*   | 7.4 atau lebih baru | 8.0 atau lebih baru |
| *MySQL* | 5.7 atau lebih baru | 8.0 atau lebih baru |
| *MariaDB* | 10.3 atau lebih baru | 10.5 atau lebih baru |
| *Web Server* | Apache/Nginx | Apache dengan mod_rewrite |
| *Memori RAM* | 512MB | 2GB atau lebih |

> *Catatan:* WordPress lebih optimal dengan *mod_rewrite* diaktifkan.  

---

## 🎨 Kustomisasi WordPress  
- *Tema:* Tambahkan tema ke direktori /wp-content/themes/, lalu aktifkan melalui dashboard WordPress.  
- *Plugin:* Tambahkan plugin ke direktori /wp-content/plugins/, lalu aktifkan melalui dashboard.  
- *Pengaturan Tambahan:*  
  - *Pengaturan Permalink: Akses **Settings > Permalinks* dan ubah sesuai kebutuhan.  
  - **Konfigurasi .htaccess**: Pastikan WordPress dapat menulis ke file .htaccess untuk mengelola permalinks.  

---

## 🔄 Pemeliharaan & Keamanan  
Agar situs WordPress tetap berjalan optimal dan aman, lakukan hal berikut secara berkala:  
🔹 *Perbarui WordPress, tema, dan plugin secara rutin.*  
🔹 *Backup database dan file secara berkala.*  
🔹 *Gunakan plugin keamanan* seperti Wordfence atau iThemes Security.  
🔹 *Batasi login gagal* untuk mencegah brute force attack.  
🔹 *Gunakan HTTPS* dengan SSL/TLS untuk keamanan tambahan.  

---

## 📌 Lisensi  
Proyek ini menggunakan lisensi *GPLv2 atau lebih baru*, sesuai dengan lisensi resmi WordPress. Silakan gunakan, modifikasi, dan distribusikan sesuai dengan ketentuan lisensi ini.  

---

## 📞 Kontak & Dukungan  
Jika Anda memiliki pertanyaan atau memerlukan bantuan lebih lanjut, silakan hubungi:  

📧 *Email*: [davidzon.juansa16@smk.belajar.id](mailto:davidzon.juansa16@smk.belajar.id)  
📱 *WhatsApp*: [+62 812-5594-4163](https://wa.me/6281255944163)  
🐙 *GitHub*: [CyberDaviid](https://github.com/CyberDaviid)  
