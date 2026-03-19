# 🌿 NutriX — Website Produk Minuman Kesehatan

<img width="1824" height="922" alt="image" src="https://github.com/user-attachments/assets/c19e68e2-2813-4c5e-9328-f0d76a35659c" />
<img width="1824" height="922" alt="image" src="https://github.com/user-attachments/assets/3d2f086d-42b9-4ca0-aa90-c7c66fffa577" />
<img width="1824" height="922" alt="image" src="https://github.com/user-attachments/assets/acc68bcc-feb6-4047-bd4c-d15a0561cb86" />
<img width="1824" height="922" alt="image" src="https://github.com/user-attachments/assets/126c7eda-43c3-43e4-8277-179dc7f3a8d7" />
<img width="1824" height="922" alt="image" src="https://github.com/user-attachments/assets/96e74caf-18bd-4c52-9f70-8f64a19a581f" />
<img width="1824" height="922" alt="image" src="https://github.com/user-attachments/assets/2ddbb3b6-bd61-470b-851c-469cc07aacdb" />

> Website landing page dan toko online untuk brand minuman kesehatan **NutriX** — diformulasikan secara ilmiah untuk mendukung energi, fokus, dan imunitas harianmu.

## 🌐 Demo

👉 https://brightt123.github.io/nutrix.github.io/index.html

## 📋 Tentang Proyek

NutriX adalah proyek website statis yang dibangun menggunakan **HTML, CSS, dan JavaScript murni** — tanpa framework atau library tambahan. Website ini dirancang sebagai platform pemasaran dan penjualan produk minuman kesehatan dengan tampilan modern, bersih, dan responsif.

Proyek ini cocok sebagai:
- 🎯 Portfolio desain UI/UX
- 🛍️ Template toko online produk kesehatan
- 📚 Referensi belajar HTML/CSS/JavaScript

---

## 📁 Struktur File

```
nutrix/
├── index.html              # Halaman utama / Landing Page
├── nutrix-products.html    # Halaman daftar semua produk
├── nutrix-product.html     # Halaman detail produk (dinamis, semua produk)
├── nutrix-cart.html        # Halaman keranjang belanja
└── nutrix-about.html       # Halaman tentang brand NutriX
```

> **Penting:** Semua file harus berada di folder yang sama agar navigasi antar halaman berfungsi dengan benar.

---

## 🗂️ Penjelasan Tiap Halaman

### 1. `index.html` — Landing Page
Halaman pertama yang dilihat pengunjung. Berisi:
- **Hero section** dengan animasi background geometric floating shapes
- **Trust bar** — statistik kepercayaan (rating, jumlah pembeli, garansi)
- **Carousel produk** — menampilkan 5 produk unggulan dengan navigasi
- **How it works** — 4 langkah cara order
- **Testimoni** — ulasan dari pembeli nyata
- **CTA Banner** — ajakan untuk segera membeli

### 2. `nutrix-products.html` — Halaman Produk
Menampilkan semua 8 produk NutriX. Fitur yang tersedia:
- **Filter kategori** — Semua, Energi, Relaksasi, Imunitas, Fokus, Bundle
- **Sorting** — Paling populer, harga termurah/termahal, nama A–Z
- **Wishlist** — tombol ❤️ untuk menyimpan produk favorit
- **Tambah ke keranjang** — dengan notifikasi toast
- **Klik card produk** — langsung masuk ke halaman detail produk

### 3. `nutrix-product.html` — Halaman Detail Produk
**Satu file untuk semua produk** — menggunakan URL parameter `?id=1` s/d `?id=8`. Fitur:
- **Carousel gambar** — 4 slide dengan thumbnail di bawah
- **Pilih varian rasa** — Tropical Mango, Citrus Burst, dll
- **Pilih ukuran** — 15 Sachet, 30 Sachet, 60 Sachet
- **Quantity counter** — tambah/kurang jumlah produk
- **Tombol Beli** — langsung ke keranjang
- **Wishlist**
- **3 Tab konten:** Deskripsi, Informasi Nutrisi, Cara Pakai
- **Rekomendasi produk** lainnya

### 4. `nutrix-cart.html` — Keranjang Belanja
Halaman checkout sebelum pembayaran. Fitur:
- **Daftar item** — dengan gambar, nama, qty, dan harga
- **Ubah quantity** dan **hapus item**
- **Kode promo** — coba masukkan `NUTRIX20` untuk diskon 20%
- **Ringkasan harga** — subtotal, diskon, ongkir, total
- **Rekomendasi produk** yang belum ada di keranjang
- **Toast notification** setiap aksi

### 5. `nutrix-about.html` — Tentang Kami
Halaman brand story NutriX. Berisi:
- **Hero section** dark dengan floating shapes
- **Statistik brand** — tahun berdiri, jumlah pelanggan, produk, rating
- **Cerita brand** — latar belakang pendirian NutriX
- **Nilai-nilai brand** — 6 value cards
- **Tim pendiri** — 4 orang dengan jabatan dan keahlian
- **Proses ilmiah** — 4 tahap pembuatan produk
- **Sertifikasi** — BPOM, Halal MUI, Non-GMO, ISO 22000

---

## ✨ Fitur Utama

### 🎨 Desain
- **Dark/Light mode** — toggle dengan animasi smooth, tersimpan di `localStorage`
- **Fully responsive** — tampil sempurna di desktop, tablet, dan HP
- **Tipografi premium** — Syne (heading) + Space Grotesk (body)
- **Palet warna konsisten** — sistem CSS variables teal sebagai warna utama
- **Animasi halus** — floating shapes, fade-up, carousel transitions

### 🛠️ Fungsionalitas
- **Carousel dinamis** — jumlah item menyesuaikan lebar layar (1/2/3 item)
- **Filter & sort produk** — real-time tanpa reload
- **Kode promo** — input `NUTRIX20` untuk diskon 20%
- **Halaman produk dinamis** — 1 file untuk 8 produk via URL `?id=`
- **Toast notifications** — feedback visual setiap aksi pengguna
- **Breadcrumb navigasi** — selalu tahu posisi halaman

---

## 🎨 Panduan UI/UX

### Filosofi Desain
Website NutriX menggunakan pendekatan **"Clean & Modern Tech"** — memadukan estetika minimalis dengan elemen teknologi untuk brand minuman kesehatan berbasis sains.

### Sistem Warna
```
Warna utama  : #1D9E75 (Teal 600) — CTA, harga, highlight
Warna gelap  : #085041 (Teal 800) — header, trust bar
Warna muda   : #E1F5EE (Teal 50)  — background section, card
Teks utama   : #111110            — heading dan body
Teks sekunder: #6b6b67            — keterangan, label
Dark mode bg : #0d0d0d            — background utama
```

### Tipografi
```
Heading  : Syne — bold, modern, letter-spacing negatif
Body     : Space Grotesk — readable, geometric, professional
```

### Komponen UI yang Dipakai
| Komponen                     | Digunakan di                                   |
|---                           |---                                             |
| Floating shapes hero         | Landing page, About, CTA banner                |
| Carousel horizontal          | Landing page (produk), Product detail (gambar) |
| Card produk                  | Products page, rekomendasi                     |
| Filter chips                 | Products page                                  |
| Tab content                  | Product detail                                 |
| Pill toggle Moon/Sun         | Semua halaman (dark/light mode)                |
| Toast notification           | Cart, Products, Product detail                 |
| Sticky navbar                | Semua halaman                                  |
| Breadcrumb                   | Products, Product detail, Cart                 |

### Prinsip UI/UX yang Diterapkan

**1. Visual Hierarchy**
Ukuran font, warna, dan spacing dirancang untuk mengarahkan mata pengguna ke informasi paling penting — nama produk, harga, dan tombol beli.

**2. Feedback Visual**
Setiap interaksi pengguna (hover, klik, tambah keranjang) langsung memberikan respons visual — warna berubah, animasi muncul, atau toast notification tampil.

**3. Konsistensi**
Navbar, warna, tipografi, dan komponen sama persis di semua halaman sehingga pengguna tidak bingung saat berpindah halaman.

**4. Progressive Disclosure**
Informasi produk ditampilkan secara bertahap — ringkasan di card, detail di halaman produk, dan spesifikasi lengkap di dalam tab — agar tidak membebani pengguna sekaligus.

**5. Mobile-First**
Layout, ukuran tombol, dan carousel dirancang untuk mudah dioperasikan dengan jari di layar sentuh.

**6. Dark/Light Mode**
Memberikan kenyamanan bagi pengguna di berbagai kondisi pencahayaan. Preferensi tersimpan otomatis sehingga tidak perlu set ulang setiap kunjungan.

---

## 🚀 Cara Menjalankan

### Lokal (di komputer)
```bash
# 1. Clone repository
git clone https://github.com/username/username.github.io

# 2. Masuk folder
cd username.github.io

# 3. Buka di browser
# Double-click index.html
# atau buka di VS Code dengan Live Server
```

## 🔧 Cara Edit Konten

### Ganti data produk
Buka `nutrix-product.html`, cari:
```javascript
const PRODUCTS = {
  1: {
    name: 'NutriX Boost',     // Ganti nama produk
    price: 89000,             // Ganti harga
    tagline: '...',           // Ganti deskripsi singkat
    benefits: ['...'],        // Ganti daftar manfaat
  },
}
```

### Ganti warna brand
```css
:root {
  --teal-600: #1D9E75;  /* warna utama — ganti sesuai brand */
}
```

### Ganti nama brand
Cari `nutri<span>X</span>` di semua file, ganti dengan nama brandmu.

### Tambah produk baru
Di `nutrix-product.html`, tambahkan entry baru di `const PRODUCTS`:
```javascript
9: {
  name: 'Produk Baru',
  price: 90000,
  // ... isi lengkap sesuai format produk lainnya
}
```
Lalu di `nutrix-products.html`, tambahkan data produk ke array `PRODUCTS` dan `PRODUCT_PAGES`.

---

## 📦 Teknologi

| Teknologi | Kegunaan |
|---|---|
| **HTML5** | Struktur halaman |
| **CSS3** | Styling, animasi, dark/light mode via CSS variables |
| **JavaScript Vanilla** | Interaktivitas, carousel, filter, logika keranjang |
| **Google Fonts** | Syne & Space Grotesk |
| **localStorage** | Menyimpan preferensi dark/light mode |
| **URL Parameters** | Halaman produk dinamis `?id=1..8` |

> Tidak menggunakan framework apapun — murni HTML/CSS/JS.

---

## 📱 Responsif

| Layar | Layout |
|---|---|
| Desktop > 860px | 2 kolom product detail, 3 kolom grid produk |
| Tablet 600–860px | 2 kolom grid, carousel 2 item |
| Mobile < 600px | 1 kolom, carousel 1 item, navbar disederhanakan |

---

## 🗺️ Peta Navigasi

```
index.html (Landing Page)
│
├── nutrix-products.html (Semua Produk)
│   └── nutrix-product.html?id=1..8 (Detail Produk)
│       └── nutrix-cart.html (Keranjang)
│
├── nutrix-about.html (Tentang Kami)
│
└── nutrix-cart.html (Keranjang)
```

---


---

⭐ **Jika proyek ini bermanfaat, berikan bintang di repository ini!**
