# Laporan Proyek Website Personal

## Deskripsi Proyek

### Tujuan
Proyek ini bertujuan untuk membuat website personal yang berfungsi sebagai portfolio online untuk menampilkan profil, keterampilan, dan karya-karya yang telah dikerjakan.

### Fitur Utama
1. **Halaman Beranda (Home)** - Menampilkan informasi singkat tentang diri, keahlian, dan CTA (Call to Action) untuk menghubungi atau melihat portfolio.
2. **Halaman Portfolio** - Menampilkan beberapa proyek yang telah dikerjakan dengan deskripsi singkat dan teknologi yang digunakan.
3. **Halaman Kontak** - Berisi formulir kontak dan informasi kontak lainnya seperti email, telepon, dan media sosial.
4. **Toggle Mode Tema** - Fitur untuk beralih antara tema gelap (dark mode) dan terang (light mode).
5. **Tampilan Responsif** - Desain yang dapat menyesuaikan dengan berbagai ukuran layar (desktop, tablet, mobile).

### Teknologi yang Digunakan
- **HTML5** - Untuk struktur dan konten website
- **CSS3** - Untuk styling dan layout website
- **JavaScript** - Untuk interaktivitas seperti toggle tema, menu mobile, dan validasi form
- **Font Awesome** - Untuk ikon-ikon di website
- **Google Fonts (Poppins)** - Untuk tipografi website

## Struktur Folder dan File

```
website-personal/
├── index.html                 # Halaman beranda
├── portfolio.html             # Halaman portfolio
├── contact.html               # Halaman kontak
├── style.css                  # File CSS utama
├── js/
│   └── script.js              # File JavaScript utama
└── img/
    └── poto.jpg               # Foto profil
```

### Penjelasan File:
1. **index.html** - Berisi struktur halaman beranda dengan informasi singkat tentang diri, keahlian, dan tombol CTA.
2. **portfolio.html** - Menampilkan grid karya-karya dengan deskripsi dan teknologi yang digunakan.
3. **contact.html** - Berisi formulir kontak dan informasi kontak seperti email, telepon, lokasi, dan media sosial.
4. **style.css** - File CSS yang mengatur tampilan seluruh website, termasuk layout, warna, responsivitas, dan animasi.
5. **script.js** - Berisi fungsi JavaScript untuk mengatur interaktivitas website, seperti toggle menu mobile, switch tema gelap/terang, dan pengiriman formulir.

## Implementasi Fitur
1. **Tema Gelap/Terang** - Website secara default menggunakan tema gelap, namun pengguna dapat beralih ke tema terang dengan mengklik ikon di navbar. Preferensi tema disimpan di localStorage.
2. **Menu Mobile Responsif** - Pada tampilan mobile, menu navigasi berubah menjadi menu hamburger yang dapat diklik untuk menampilkan opsi navigasi.
3. **Validasi Form** - Form kontak memiliki validasi sederhana dan menampilkan pesan demo saat dikirim.
4. **Animasi Hover** - Terdapat animasi hover pada tombol, kartu proyek, dan link navigasi untuk meningkatkan user experience.

## Status Hosting
Proyek ini belum di-hosting dan masih dalam tahap pengembangan lokal.

## Rencana Pengembangan Ke Depan
1. Menambahkan halaman blog untuk berbagi tulisan dan artikel.
2. Mengimplementasikan backend untuk formulir kontak agar dapat benar-benar mengirim pesan.
3. Menambahkan lebih banyak proyek dan detail pada halaman portfolio.
4. Optimalisasi SEO untuk meningkatkan visibilitas di mesin pencari.
5. Hosting website di layanan hosting atau platform seperti GitHub Pages, Netlify, atau Vercel.
