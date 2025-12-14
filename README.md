# 🍽 Lapor Mangan! - Purwokerto

**Lapor Mangan!** adalah aplikasi web untuk menemukan informasi kuliner UMKM di Purwokerto. Aplikasi ini membantu Anda menjelajahi dan mendukung usaha kuliner lokal dengan mudah!

---

## 📋 Daftar Isi

- [Fitur Utama](#-fitur-utama)
- [Cara Menggunakan](#-cara-menggunakan)
  - [1. Membuka Aplikasi](#1-membuka-aplikasi)
  - [2. Mencari Kuliner](#2-mencari-kuliner)
  - [3. Filter dan Urutkan](#3-filter-dan-urutkan)
  - [4. Menggunakan Peta Interaktif](#4-menggunakan-peta-interaktif)
  - [5. Melihat Detail Kuliner](#5-melihat-detail-kuliner)
  - [6. Fitur Cuaca](#6-fitur-cuaca)
  - [7. Menggunakan MakanBot (Chatbot)](#7-menggunakan-makanbot-chatbot)
  - [8. Menambah Kuliner Baru](#8-menambah-kuliner-baru)
- [Tips Penggunaan](#-tips-penggunaan)
- [FAQ (Pertanyaan Umum)](#-faq-pertanyaan-umum)
- [Instalasi untuk Developer](#-instalasi-untuk-developer)

---

## ✨ Fitur Utama

| Fitur | Deskripsi |
|-------|-----------|
| 🗺 **Peta Interaktif** | Menampilkan lokasi setiap kuliner di peta Leaflet |
| 🔍 **Pencarian** | Cari kuliner berdasarkan nama |
| 🏷 **Filter Kategori** | Filter berdasarkan kategori (Soto, Sate, Bakso, dll.) |
| 📊 **Pengurutan** | Urutkan berdasarkan nama, rating, atau harga |
| 📍 **Terdekat** | Temukan kuliner terdekat dari lokasi Anda |
| 🎲 **Acak Pilihan** | Bingung mau makan apa? Gunakan fitur acak! |
| 🌤 **Info Cuaca** | Lihat cuaca terkini di Purwokerto |
| 🌧 **Rekomendasi Cuaca** | Dapatkan rekomendasi kuliner sesuai cuaca |
| 🤖 **MakanBot** | Chatbot AI untuk membantu mencari kuliner |
| ➕ **Tambah Kuliner** | Kontribusi dengan menambahkan kuliner baru |
| ⏰ **Filter Buka Sekarang** | Hanya tampilkan kuliner yang sedang buka |

---

## 📖 Cara Menggunakan

### 1. Membuka Aplikasi

1. Buka file `index.html` di browser Anda (Chrome, Firefox, Edge, dll.)
2. Atau akses melalui link website jika sudah di-deploy
3. Tunggu hingga peta dan daftar kuliner selesai dimuat

### 2. Mencari Kuliner

1. Gunakan **kotak pencarian** di bagian atas halaman
2. Ketik nama kuliner yang ingin dicari (contoh: "Soto", "Bakso", "Mendoan")
3. Hasil pencarian akan muncul secara otomatis

![Pencarian](https://via.placeholder.com/600x100?text=Kotak+Pencarian)

### 3. Filter dan Urutkan

#### Filter Kategori
- Klik dropdown **"Semua Kategori"**
- Pilih kategori yang diinginkan:
  - Soto
  - Sate
  - Bakso
  - Gudeg
  - Ayam
  - Lontong
  - Jajanan Tradisional
  - Makanan Berat

#### Urutkan
- Klik dropdown **"Urutkan"**
- Pilih opsi pengurutan:
  - **Nama A-Z** - Urutkan berdasarkan abjad
  - **Rating Tertinggi** - Tampilkan yang paling populer
  - **Harga Terendah** - Mulai dari yang paling murah
  - **Harga Tertinggi** - Mulai dari yang paling mahal

#### Filter Buka Sekarang
- Aktifkan toggle **"Hanya tampilkan yang buka sekarang"**
- Sistem akan menyaring berdasarkan jam operasional

### 4. Menggunakan Peta Interaktif

1. **Lihat Peta** - Peta menampilkan lokasi semua kuliner dengan marker
2. **Zoom In/Out** - Gunakan tombol +/- atau scroll mouse
3. **Klik Marker** - Klik ikon di peta untuk melihat info singkat
4. **Navigasi** - Drag peta untuk menjelajahi area lain

#### Tombol Fitur Peta:
| Tombol | Fungsi |
|--------|--------|
| 📍 **Terdekat** | Menemukan kuliner terdekat dari lokasi Anda |
| 🎲 **Acak Pilihan** | Memilih kuliner secara random |
| 🌤 **Rekomendasi Cuaca** | Saran kuliner berdasarkan cuaca saat ini |

### 5. Melihat Detail Kuliner

1. **Klik item** di daftar kuliner atau marker di peta
2. Popup detail akan muncul dengan informasi:
   - 📸 Foto kuliner
   - 📝 Nama dan deskripsi
   - 📍 Alamat lengkap
   - ⏰ Jam operasional
   - 💰 Kisaran harga
   - 🅿️ Informasi parkir
   - 🛵 Apakah tersedia keliling

3. Klik tombol **×** untuk menutup popup

### 6. Fitur Cuaca

#### Melihat Cuaca
1. Lihat **ikon cuaca** di pojok kanan atas header
2. Menampilkan suhu terkini di Purwokerto

#### Detail Cuaca
1. **Klik** pada info cuaca untuk melihat detail:
   - Suhu saat ini, minimum, dan maksimum
   - Kelembapan udara
   - Kecepatan angin
   - Waktu matahari terbit & terbenam
   - Kondisi cuaca

#### Rekomendasi Berdasarkan Cuaca
1. Klik tombol **🌤 Rekomendasi Cuaca**
2. Sistem akan menyarankan kuliner sesuai kondisi cuaca:
   - ☀️ **Cuaca Panas** → Minuman segar, es
   - 🌧 **Hujan** → Makanan hangat seperti soto, bakso
   - ❄️ **Dingin** → Makanan berkuah hangat

### 7. Menggunakan MakanBot (Chatbot)

MakanBot adalah asisten AI yang membantu Anda mencari rekomendasi kuliner!

#### Cara Menggunakan:
1. Klik tombol **💬** di pojok kanan bawah layar
2. Jendela chat akan terbuka
3. Ketik pertanyaan atau permintaan Anda
4. Tekan **Enter** atau klik tombol kirim
5. MakanBot akan memberikan respons

#### Contoh Percakapan:
```
Anda: "Halo"
Bot: "Halo! Selamat datang di LaporMangan. Ada yang bisa saya bantu? 😊"

Anda: "Rekomendasi sate dong"
Bot: "Untuk sate, saya rekomendasikan Sate Bebek Tambak di Jl. Tambak..."

Anda: "Mau yang murah"
Bot: "Banyak pilihan hemat! Coba cari 'jajanan tradisional'..."

Anda: "Makan apa ya kalau hujan?"
Bot: "Kalau hujan, cocok makan yang hangat-hangat seperti Soto Sokaraja..."
```

#### Kata Kunci yang Dipahami MakanBot:
- **Sapaan**: halo, hai, selamat pagi/siang/sore
- **Rekomendasi**: rekomendasi, sarankan, enak
- **Harga**: murah, terjangkau, hemat
- **Kategori**: soto, sate, bakso, gudeg, ayam
- **Legendaris**: legendaris, terkenal, ikonik
- **Cuaca**: panas, hujan, dingin

### 8. Menambah Kuliner Baru

Ingin menambahkan kuliner favorit Anda? Ikuti langkah berikut:

1. Klik tombol **+** di bagian header
2. Isi formulir dengan informasi:
   - **Nama Kuliner** (wajib)
   - **Kategori** (wajib)
   - **Alamat** (wajib)
   - **Jam Operasional** (wajib) - Format: `08:00 - 18:00`
   - **Harga** (wajib) - Format: `Rp 5.000 - 15.000`
   - **Deskripsi** (wajib)
   - **URL Foto** (opsional)
3. Klik **Simpan** untuk menambahkan

> ⚠️ **Catatan**: Data kuliner yang ditambahkan disimpan di browser (localStorage). Data akan hilang jika Anda membersihkan cache browser.

---

## 💡 Tips Penggunaan

1. **Izinkan Akses Lokasi** - Untuk fitur "Terdekat" bekerja optimal, izinkan browser mengakses lokasi Anda

2. **Gunakan Filter Kombinasi** - Kombinasikan pencarian + kategori + pengurutan untuk hasil terbaik

3. **Cek Jam Operasional** - Aktifkan "Buka Sekarang" agar tidak kecewa saat datang

4. **Manfaatkan MakanBot** - Jika bingung, tanya saja ke MakanBot untuk rekomendasi personal

5. **Perhatikan Cuaca** - Gunakan fitur rekomendasi cuaca untuk pengalaman makan yang lebih nyaman

---

## ❓ FAQ (Pertanyaan Umum)

### Apa itu Lapor Mangan?
Lapor Mangan adalah platform untuk menemukan kuliner UMKM di Purwokerto. Kami membantu Anda menjelajahi dan mendukung usaha kuliner lokal!

### Bagaimana cara kerja fitur "Terdekat"?
Fitur ini menggunakan GPS browser untuk mendeteksi lokasi Anda, kemudian menghitung jarak ke setiap kuliner dan mengurutkannya dari yang paling dekat.

### Apakah data kuliner selalu akurat?
Data kuliner dikumpulkan dari berbagai sumber dan kontribusi pengguna. Jam operasional dan harga bisa berubah, disarankan untuk menghubungi tempat terlebih dahulu.

### Bagaimana cara melaporkan informasi yang salah?
Gunakan fitur "Tambah Informasi" dengan form Google atau hubungi pengelola aplikasi.

### Apakah aplikasi ini gratis?
Ya! Lapor Mangan sepenuhnya gratis untuk digunakan.

### Mengapa peta tidak muncul?
Pastikan koneksi internet Anda stabil. Peta memerlukan koneksi untuk memuat data dari Leaflet.

---

## 🛠 Instalasi untuk Developer

### Clone Repository
```bash
git clone https://github.com/hanif-12-01/LAPORMANGAN.git
cd LAPORMANGAN
```

### Menjalankan Aplikasi
Cukup buka file `index.html` di browser. Tidak memerlukan server khusus.

### Struktur File
```
LAPORMANGAN/
├── index.html          # Halaman utama
├── style.css           # Stylesheet utama
├── styles.css          # Stylesheet tambahan
├── script.js           # JavaScript utama (data & logika)
├── chatbot.js          # Logika chatbot MakanBot
├── knowledge-base.js   # Basis pengetahuan chatbot
└── README.md           # Dokumentasi ini
```

### Teknologi yang Digunakan
- **HTML5** - Struktur halaman
- **CSS3** - Styling dan responsif
- **JavaScript (Vanilla)** - Logika aplikasi
- **Leaflet.js** - Peta interaktif
- **OpenWeatherMap API** - Data cuaca
- **Font Awesome** - Ikon
- **Google Fonts (Poppins)** - Typography

---

## 📞 Kontak & Dukungan

Jika Anda memiliki pertanyaan atau saran, silakan:
- Buka issue di [GitHub Repository](https://github.com/hanif-12-01/LAPORMANGAN/issues)
- Atau hubungi pengembang melalui GitHub

---

**Selamat menikmati kuliner Purwokerto! 🍽️**

*Dibuat dengan ❤️ untuk mendukung UMKM kuliner lokal*
