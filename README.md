# 🌐 Website Portofolio - Irvan Alif

Website portofolio pribadi yang bersifat dinamis, dibangun menggunakan PHP, MySQL, Vue.js, dan Bootstrap 5. Data ditampilkan langsung dari database sehingga mudah diperbarui tanpa mengubah kode HTML.

---

## 📸 Tampilan Website

### Halaman Home (Hero Section)
<!-- [TARUH SCREENSHOT TAMPILAN HOME / HERO SECTION DI SINI]
     Isi: foto profil, nama, jabatan, statistik (semester, koordinator, sertifikat), tombol CTA -->

---

### Halaman About Me
<!-- [TARUH SCREENSHOT TAMPILAN ABOUT ME DI SINI]
     Isi: foto, bio singkat, info lokasi/email/status/jurusan, progress bar skills -->

---

### Skills & Pengalaman
<!-- [TARUH SCREENSHOT BAGIAN SKILLS DAN KARTU PENGALAMAN DI SINI]
     Isi: progress bar skills, kartu-kartu pengalaman organisasi -->

---

### Halaman Certificates
<!-- [TARUH SCREENSHOT TAMPILAN SECTION SERTIFIKAT DI SINI]
     Isi: grid kartu sertifikat dengan warna berbeda-beda -->

---

### Tampilan Mobile / Responsif
<!-- [TARUH SCREENSHOT TAMPILAN DI HP / LAYAR KECIL DI SINI]
     Opsional tapi nilai tambah: tunjukkan tampilan navbar collapse & layout mobile -->

---

## 🗂️ Struktur Project

```
portofolio/
├── index.php            # Halaman utama (dinamis dari DB + Vue.js)
├── config/
│   └── koneksi.php      # Konfigurasi koneksi database
├── Style/
│   └── style.css        # Custom CSS styling
├── image/
│   └── alip.jpeg        # Foto profil
└── portofolio.sql       # File database (import ke phpMyAdmin)
```

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| PHP | Mengambil data dari database dan mengirimnya ke Vue |
| MySQL | Menyimpan data profil, skills, pengalaman, sertifikat |
| Vue.js 3 | Menampilkan data secara interaktif menggunakan `{{ }}` dan `v-for` |
| Bootstrap 5 | Layout responsif, navbar, card, progress bar |
| Bootstrap Icons | Ikon-ikon pada tampilan |
| Google Fonts (Poppins) | Tipografi |

---

## ⚙️ Cara Instalasi

### 1. Persiapan
- Pastikan **Laragon** sudah terinstall dan berjalan
- Buka **phpMyAdmin** melalui Laragon

### 2. Import Database
1. Buka phpMyAdmin → klik **"New"** → buat database bernama `portofolio`
2. Pilih database `portofolio` → klik tab **"Import"**
3. Pilih file `portofolio.sql` → klik **"Go"**

### 3. Letakkan File Project
Salin seluruh folder project ke:
```
C:\laragon\www\portofolio\
```

### 4. Jalankan Website
Buka browser dan akses:
```
http://localhost/portofolio/
```

---

## 🗄️ Struktur Database

| Tabel | Isi |
|---|---|
| `profil` | Nama, jabatan, bio, lokasi, email, universitas, dll |
| `statistik` | Angka statistik hero (semester, koordinator, sertifikat) |
| `skills` | Nama skill dan persentase progress bar |
| `pengalaman` | Periode, jabatan, organisasi, deskripsi |
| `sertifikat` | Judul, penerbit, tanggal, deskripsi, ID sertifikat |

---

## ✨ Fitur

- **Hero Section** — perkenalan singkat dengan foto dan statistik dinamis
- **About Me** — bio, info pribadi, dan progress bar skills
- **Pengalaman** — kartu riwayat organisasi dan kegiatan
- **Sertifikat** — grid kartu sertifikat dengan warna berbeda
- **Responsif** — tampilan menyesuaikan di semua ukuran layar
- **Navbar** — navigasi tetap di atas (sticky) dengan efek blur

---

## 👤 Author

**Irvan Alif**
Mahasiswa Sistem Informasi — Universitas Mulawarman
