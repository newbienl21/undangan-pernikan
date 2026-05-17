# 💍 Undangan Pernikahan — Ahmad & Siti

Website undangan pernikahan digital yang elegan, dibuat dengan HTML, CSS, dan JavaScript murni — tanpa framework, siap deploy ke GitHub Pages.

---

## ✨ Fitur

- Halaman cover animasi dengan ornamen botanical emas
- Profil mempelai beserta nama orang tua
- Detail acara Akad Nikah & Resepsi
- Hitung mundur (countdown) otomatis ke hari H
- Timeline kisah cinta
- Galeri foto (placeholder)
- Form RSVP konfirmasi kehadiran
- Desain responsif (mobile & desktop)

---

## 🚀 Cara Deploy ke GitHub Pages

### Langkah 1 — Buat repository baru di GitHub

1. Buka [github.com](https://github.com) → klik **New repository**
2. Beri nama repository, contoh: `undangan-pernikahan`
3. Set ke **Public**
4. Klik **Create repository**

### Langkah 2 — Upload file ke repository

**Cara A — Lewat browser (mudah):**
1. Di halaman repository, klik **Add file** → **Upload files**
2. Upload semua file berikut:
   - `index.html`
   - `.github/workflows/deploy.yml`
   - `README.md`
3. Klik **Commit changes**

**Cara B — Lewat Git (terminal):**
```bash
git init
git add .
git commit -m "first commit: wedding invitation website"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO-NAME.git
git push -u origin main
```

### Langkah 3 — Aktifkan GitHub Pages

1. Buka tab **Settings** di repository
2. Klik **Pages** di menu kiri
3. Pada bagian **Source**, pilih **GitHub Actions**
4. Simpan pengaturan

### Langkah 4 — Lihat website

Setelah beberapa menit, website akan live di:
```
https://USERNAME.github.io/REPO-NAME/
```

---

## ✏️ Cara Kustomisasi

Buka file `index.html` dan ganti bagian-bagian berikut:

| Yang diganti | Cari teks ini |
|---|---|
| Nama mempelai pria | `Ahmad Fauzi Ramadhan, S.T.` |
| Nama mempelai wanita | `Siti Nurhaliza Putri, S.Pd.` |
| Nama panggilan | `Ahmad` dan `Siti` di semua bagian |
| Nama orang tua | `H. Rahmat Santoso`, `Hj. Nurhayati`, dll. |
| Tanggal pernikahan | `Sabtu, 12 Juli 2025` |
| Waktu acara | `08.00 – 10.00 WIB`, `11.00 – 15.00 WIB` |
| Lokasi acara | `Masjid Al-Ikhlas`, `Gedung Serbaguna Melati` |
| Alamat lengkap | Sesuaikan di bagian detail acara |
| Link Google Maps | `https://maps.google.com` → ganti dengan link peta asli |
| Nomor WhatsApp | `6281234567890` di footer |
| Email | `ahmad.siti@email.com` di footer |
| Countdown target | `2025-07-12T08:00:00` di bagian `<script>` |

### Menambah foto
Ganti elemen galeri placeholder dengan tag gambar:
```html
<img src="foto1.jpg" style="width:100%; height:100%; object-fit:cover;">
```
Upload foto ke repository, lalu sesuaikan nama file di `index.html`.

---

## 📁 Struktur File

```
undangan-pernikahan/
├── index.html              # Halaman utama website
├── README.md               # Panduan ini
└── .github/
    └── workflows/
        └── deploy.yml      # Auto-deploy ke GitHub Pages
```

---

*Dibuat dengan ❤️ untuk hari bahagia yang istimewa.*
