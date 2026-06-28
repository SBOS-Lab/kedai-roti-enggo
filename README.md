# 🍞 Kedai Roti Enggo — Website

Website one-page modern untuk **Kedai Roti Enggo**, toko roti & bakery di Sentani, Jayapura, Papua. Dibangun dengan HTML, TailwindCSS, dan JavaScript murni — tanpa framework, tanpa build tool.

---

## 🌐 Preview

> Buka `index.html` langsung di browser, atau gunakan Live Server di VS Code.

---

## 🛠️ Tech Stack

| Teknologi | Versi | Keterangan |
|-----------|-------|------------|
| HTML5 | — | Struktur semantik one-page |
| [TailwindCSS](https://tailwindcss.com) | v3 CDN | Utility-first styling + custom config |
| [Font Awesome](https://fontawesome.com) | v6.5 | Semua ikon |
| [Google Fonts](https://fonts.google.com) | — | Playfair Display + Poppins |
| JavaScript | ES6+ | Interaktivitas (tanpa library eksternal) |

---

## 📁 Struktur Proyek

```
kedai-roti-enggo/
└── index.html       # Seluruh website dalam satu file
```

---

## ✨ Fitur

- **Fully Responsive** — Mobile, tablet, dan desktop
- **Sticky Navbar** — Dengan highlight aktif saat scroll
- **Mobile Menu** — Hamburger menu untuk layar kecil
- **Hero Section** — Full-screen dengan overlay gradient
- **Filter Produk** — Filter kategori tanpa reload halaman
- **FAQ Accordion** — Buka/tutup dengan animasi smooth
- **Galeri** — Grid foto dengan hover zoom effect
- **Testimoni** — 6 ulasan pelanggan
- **Google Maps** — Embed lokasi toko
- **Floating WhatsApp** — Tombol WA muncul saat scroll
- **Back to Top** — Tombol kembali ke atas

---

## 📋 Struktur Halaman

```
Header (Navbar)
├── Hero Section
├── Tentang Kami
├── Kenapa Memilih Kami
├── Produk Unggulan
├── Promo Spesial
├── Cara Pemesanan
├── Galeri
├── Testimoni
├── Lokasi & Jam Operasional
├── FAQ
├── Call To Action
└── Footer
```

---

## 🎨 Palet Warna

| Nama | Hex | Penggunaan |
|------|-----|------------|
| Kuning Roti | `#FFBF00` | Aksen utama, CTA |
| Cokelat Roti | `#8B5E3C` | Warna sekunder |
| Cokelat Tua | `#5C4033` | Background gelap, navbar |
| Cream | `#FFF8E7` | Background terang |
| Abu Tua | `#333333` | Teks utama |

---

## 📍 Informasi Toko

| | |
|-|---|
| **Nama** | Kedai Roti Enggo |
| **Alamat** | Yahim, Kec. Sentani, Kabupaten Jayapura, Papua 99359 |
| **Telepon** | 0821-888-569 |
| **WhatsApp** | [wa.me/62821888569](https://wa.me/62821888569) |
| **Google Maps** | [Buka Maps](https://maps.app.goo.gl/PUqUNFVyeNTDMwbi8) |
| **Jam (Sen–Jum)** | 07.00 – 21.00 WIT |
| **Jam (Sab–Min)** | 06.00 – 22.00 WIT |

---

## 🚀 Cara Menjalankan

1. Clone atau download repositori ini
2. Buka `index.html` di browser **atau** gunakan ekstensi Live Server di VS Code

Tidak diperlukan instalasi, build step, atau koneksi server.

---

## 📦 Cara Kustomisasi

| Yang ingin diubah | Lokasi di `index.html` |
|-------------------|------------------------|
| Nama & info toko | Cari teks `Kedai Roti Enggo` |
| Nomor WhatsApp | Cari `62821888569` |
| Produk & harga | Section `id="products"` |
| Promo | Section `id="promo"` |
| Foto galeri | Section `id="gallery"` |
| Warna utama | `tailwind.config` di tag `<script>` |
| Jam operasional | Section `id="location"` |

---

## 📄 Lisensi

Proyek ini dibuat untuk keperluan **Kedai Roti Enggo**. Dilarang digunakan ulang untuk keperluan komersial tanpa izin.

---

<p align="center">Made with ❤️ in Sentani, Papua</p>
