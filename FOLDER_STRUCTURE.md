# 🎉 Website Pernikahan - Struktur Folder Foto

## 📁 Struktur Folder yang Sudah Dibuat

```
wedding/
├── public/
│   └── images/              ← FOLDER UTAMA FOTO
│       ├── hero/            ← Background untuk halaman depan
│       ├── moments/         ← Foto cerita/perjalanan
│       ├── gallery/         ← Kumpulan foto
│       ├── venue/           ← Foto tempat acara
│       ├── couple/          ← Foto pasangan
│       └── README.md        ← Panduan di folder
├── src/
│   ├── App.tsx              ← File utama (SUDAH UPDATE)
│   ├── main.tsx
│   └── index.css
├── PHOTO_GUIDE.md           ← BACALAH INI UNTUK DETAIL LENGKAP
├── index.html
├── package.json
├── vite.config.ts
└── tsconfig.json
```

## 🖼️ Daftar Foto Yang Harus Ditambahkan

### 1. Hero Background

- **Tempat:** `public/images/hero/background.jpg`
- **Apa itu:** Foto latar belakang di halaman depan
- **Ukuran:** Minimal 1920x1080 piksel

### 2. Moments (Cerita Perjalanan)

- **Tempat:** `public/images/moments/`
- **File yang dibutuhkan:**
  - `moment-1.jpg`
  - `moment-2.jpg`
  - `moment-3.jpg`
  - `moment-4.jpg`
  - `nest-1.jpg`
  - `nest-2.jpg`

### 3. Gallery (Galeri Foto)

- **Tempat:** `public/images/gallery/`
- **File yang dibutuhkan:**
  - `photo-1.jpg`
  - `photo-2.jpg`
  - `photo-3.jpg`
  - `photo-4.jpg`
  - `photo-5.jpg`
  - `photo-6.jpg`

### 4. Venue (Foto Tempat)

- **Tempat:** `public/images/venue/venue.jpg`
- **Apa itu:** Foto venue/lokasi pernikahan

### 5. Couple Details

- **Tempat:** `public/images/couple/details.jpg`
- **Apa itu:** Foto untuk halaman detail

## ✏️ Perubahan Yang Sudah Dilakukan

### Di App.tsx:

1. ✅ Hero background diubah ke `/images/hero/background.jpg`
2. ✅ Semua foto moments diubah ke path lokal
3. ✅ Semua foto gallery diubah ke path lokal
4. ✅ Venue foto diubah ke path lokal
5. ✅ Dihapus semua referensi Google URL

### Benefit:

- ✨ Website lebih cepat (no external URL dependency)
- 📱 Bisa offline
- 🔒 Private (foto tidak terlihat di Google)
- 📊 Kontrol penuh atas foto

## 🚀 Langkah Berikutnya

1. Buka kolom Files di VS Code
2. Navigasi ke `public/images/`
3. Tambahkan foto Anda ke folder yang sesuai
4. Gunakan nama file **PERSIS** seperti yang tercantum
5. Refresh browser (F5 atau Ctrl+R)
6. Foto Anda akan muncul di website!

## 📖 Dokumentasi Lengkap

Baca file `PHOTO_GUIDE.md` untuk:

- Tips fotografi
- Optimasi ukuran file
- Troubleshooting
- FAQ

---

**Selamat! Website Anda sudah siap untuk foto lokal! 🎊**
