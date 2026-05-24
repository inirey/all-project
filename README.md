# 🚀 Reyns.my.id | Portofolio Kode & Proyek

> Halaman portofolio pribadi yang menampilkan seluruh proyek, repositori, dan karya kode secara otomatis langsung dari akun GitHub. Dibangun dengan tampilan modern, gelap, dan bernuansa teknologi.

🔗 **Kunjungi:** [reyns.my.id](https://reyns.my.id)

---

## ✨ Fitur Unggulan

✅ **Tampilan Modern & Responsif**  
Desain gelap dengan efek cahaya neon, animasi halus, dan mendukung semua perangkat (HP, Tablet, Laptop).

✅ **Data Otomatis dari GitHub**  
Mengambil data profil, statistik, dan daftar repositori secara langsung menggunakan **GitHub API**. Semua perubahan di GitHub akan otomatis terbarui di sini.

✅ **Sistem Keamanan Token**  
Menggunakan metode penyimpanan token terpisah di layanan eksternal (Pastebin), sehingga kode sumber di repositori ini **bersih total** dan aman dari deteksi kebocoran rahasia GitHub.

✅ **Informasi Lengkap Setiap Proyek**  
Menampilkan nama, deskripsi, bahasa pemrograman, jumlah bintang, garpu, dan waktu pembaruan terakhir.

✅ **Efek Visual Keren**  
Efek partikel latar belakang, kursor interaktif, animasi mengambang, dan bayangan menyala bikin tampilan makin hidup.

✅ **SEO Friendly**  
Sudah dilengkapi meta tag agar mudah ditemukan di mesin pencari.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** - Struktur dasar halaman
- **Tailwind CSS** - Untuk styling cepat dan responsif
- **JavaScript (Vanilla JS)** - Logika, pengambilan data API & interaksi
- **GitHub API** - Sumber data utama
- **Particles.js** - Efek animasi latar belakang
- **Pastebin** - Penyimpanan token aman terpisah

---

## ⚙️ Cara Kerja & Keamanan

Proyek ini dirancang dengan keamanan sebagai prioritas utama:

1.  **File Utama (`index.html`)**: Berisi seluruh tampilan dan logika, **TIDAK ADA** token atau kunci rahasia di sini. Aman sepenuhnya saat diunggah ke GitHub.
2.  **Token GitHub**: Disimpan secara terpisah di layanan [Pastebin](https://pastebin.com) dengan akses **RAW**. Token yang digunakan khusus izin baca saja (`public_repo`, `read:user`), jadi aman meski alamatnya diketahui orang lain.
3.  **Pengambilan Data**: Saat halaman dibuka, kode otomatis memuat token dari alamat Pastebin, lalu menggunakannya untuk mengambil data dari API GitHub.

---

## 🚀 Cara Pasang Sendiri

Kalau kamu mau pakai atau modifikasi proyek ini:

1.  **Clone / Fork** repositori ini.
2.  Buat **Personal Access Token** di GitHub (Pengaturan > Pengembang > Token). Centang izin: `public_repo` & `read:user` saja.
3.  Simpan token tersebut ke **Pastebin**, pilih eksposur *Unlisted*, lalu ambil tautan **RAW**-nya.
4.  Buka `index.html`, cari baris berikut dan ganti tautannya:
    ```html
    <script src="https://pastebin.com/raw/4MTUMTK9"></script>
    ```
5.  Ubah nama pengguna di bagian:
    ```js
    const GITHUB_USERNAME = "inirey";
    ```
6.  Unggah ke GitHub Pages, dan selesai! 🎉

---

## 📄 Lisensi

Proyek ini bersifat terbuka untuk pembelajaran dan pengembangan pribadi. Silakan digunakan, dimodifikasi, dan dikembangkan lebih lanjut.

---

<div align="center">
Dibuat dengan ❤️ oleh <strong>Reyns</strong> | 2026
</div>
