# 🏥 Rumah Sehat

Website **Rumah Sehat** adalah situs profil klinik kesehatan yang dikembangkan menggunakan **WordPress** dan diekspor menjadi **versi statis** menggunakan plugin **Simply Static**.  
Proyek ini bertujuan untuk menampilkan informasi umum mengenai layanan klinik, profil dokter, lokasi, serta formulir kontak untuk janji temu secara profesional dan ringan.

---

## 🌐 Demo Online
Website saat ini dihosting di Vercel:  
👉 [https://rumah-sehat.vercel.app](https://rumah-sehat.vercel.app)

---

## ⚙️ Teknologi yang Digunakan
- **WordPress** – sebagai CMS utama untuk mengelola konten.  
- **Simply Static** – plugin untuk mengekspor versi statis WordPress.  
- **Vercel** – platform hosting modern untuk website statis.  
- **WPForms** – plugin formulir kontak dengan integrasi Google reCAPTCHA v2.  
- **Rank Math SEO** – untuk optimasi SEO pada setiap halaman.  
- **Astra Theme + Elementor** – untuk desain halaman yang responsif dan modern.

---

## 🧩 Struktur Halaman Utama

1. **Beranda**  
   Halaman utama yang berisi gambaran umum tentang Rumah Sehat, visi & misi, serta ajakan untuk berkonsultasi.  

2. **Dokter**  
   Menampilkan daftar dokter dan tenaga medis beserta profil, pengalaman, serta bidang spesialisasinya.  

3. **Layanan**  
   Berisi daftar layanan medis yang tersedia di Rumah Sehat, seperti pemeriksaan umum, laboratorium, konsultasi kesehatan, dan layanan spesialis.  
   Setiap layanan dijelaskan secara singkat agar pasien dapat memahami manfaat dan prosedur pelayanannya.  

4. **Lokasi**  
   Menampilkan alamat lengkap, peta interaktif, serta daftar cabang klinik (Jakarta Barat, Jakarta Timur, Jakarta Selatan, Jakarta Utara, dan Jakarta Pusat sebagai kantor pusat).  

5. **Kontak & Janji Temu**  
   Formulir online untuk pasien yang ingin mengajukan pertanyaan atau membuat janji temu dengan dokter.  
   Dilengkapi dengan proteksi **Google reCAPTCHA v2** untuk mencegah spam (aktif di WordPress lokal).

---

## 🖥️ Cara Menjalankan di Localhost

1. Pastikan **XAMPP** atau **LAMP** sudah terinstal.  
2. Letakkan folder WordPress di:
   ```bash
   /opt/lampp/htdocs/wordpress
3. Jalankan server lokal:
   ```bash
   sudo /opt/lampp/lampp start
4. Akses situs di browser:
   ```bash
   http://localhost/wordpress
