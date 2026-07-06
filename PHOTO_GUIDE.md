# 📸 Panduan Penggantian Foto

Website pernikahan Alya & Rafi sudah siap untuk menggunakan foto lokal Anda!

## ✅ Apa Yang Sudah Dilakukan

1. **Membuat struktur folder** untuk menyimpan foto:
   - `/public/images/hero/` - Foto background hero
   - `/public/images/moments/` - Foto cerita/moments
   - `/public/images/gallery/` - Foto untuk gallery
   - `/public/images/venue/` - Foto venue
   - `/public/images/couple/` - Foto pasangan

2. **Mengupdate App.tsx** untuk menggunakan path lokal `/images/...` alih-alih Google URLs

3. **Mengganti hero background** dengan gradient fallback jika foto tidak ditemukan

## 📋 Daftar Foto Yang Dibutuhkan

### Hero Background (1 foto)

- **Path:** `public/images/hero/background.jpg`
- **Ukuran:** Min. 1920x1080px (Full HD)
- **Format:** JPG atau PNG
- **Deskripsi:** Foto latar belakang untuk hero section

### Story Moments (6 foto)

- **Path:** `public/images/moments/`
- **File yang perlu:**
  - `moment-1.jpg` - Where it Began (October 2021)
  - `moment-2.jpg` - The First Date (November 2021)
  - `moment-3.jpg` - Wanderlust Hearts (Summer 2023)
  - `moment-4.jpg` - She Said Yes! (December 2025)
  - `nest-1.jpg` - Interior photo (Building Our Nest)
  - `nest-2.jpg` - Keys photo (Building Our Nest)

### Gallery (6 foto)

- **Path:** `public/images/gallery/`
- **File yang perlu:**
  - `photo-1.jpg` - The First Trip
  - `photo-2.jpg` - Quiet Moments
  - `photo-3.jpg` - The Proposal
  - `photo-4.jpg` - City Nights
  - `photo-5.jpg` - Slow Mornings
  - `photo-6.jpg` - Ready for Always

### Venue (1 foto)

- **Path:** `public/images/venue/venue.jpg`
- **Ukuran:** Min. 1200x800px
- **Deskripsi:** Foto venue/lokasi pernikahan

### Details Page (1 foto)

- **Path:** `public/images/couple/details.jpg`
- **Ukuran:** Min. 600x800px
- **Deskripsi:** Foto untuk event details section

## 🚀 Cara Menambahkan Foto

1. **Buka folder** `public/images/` di komputer Anda
2. **Masukkan foto Anda** ke folder yang sesuai
3. **Gunakan nama file** persis seperti tercantum di atas
4. **Refresh browser** untuk melihat perubahan

### Contoh:

```
wedding/
├── public/
│   └── images/
│       ├── hero/
│       │   └── background.jpg  ← Letakkan foto hero di sini
│       ├── moments/
│       │   ├── moment-1.jpg
│       │   ├── moment-2.jpg
│       │   └── ... (dst)
│       ├── gallery/
│       │   ├── photo-1.jpg
│       │   └── ... (dst)
│       ├── venue/
│       │   └── venue.jpg
│       └── couple/
│           └── details.jpg
```

## 💡 Tips

- **Format JPG** lebih baik untuk foto besar (ukuran file lebih kecil)
- **Format PNG** untuk gambar dengan transparent background
- **Optimalkan size** foto sebelum upload menggunakan:
  - TinyPNG (tinypng.com)
  - ImageOptim (imageoptim.com)
  - Photoshop atau GIMP
- **Aspek ratio yang bagus:**
  - Hero: 16:9 atau 19:10
  - Moments: Square (1:1) atau Portrait (3:4)
  - Gallery: Bervariasi (akan auto-adjust)
  - Venue: Landscape (4:3 atau 16:9)

## 🔧 Fallback Behavior

- Jika foto tidak ditemukan, website akan menampilkan:
  - Hero: Gradient warna biru-merah
  - Gallery/Moments: Placeholder background

## ❓ Pertanyaan Umum

**Q: Boleh menggunakan foto dari URL?**
A: Tidak perlu! Gunakan foto lokal untuk performa lebih baik dan tidak bergantung internet.

**Q: Berapa ukuran maksimal foto?**
A: Sebaiknya tidak lebih dari 2MB per foto. Optimalkan terlebih dahulu.

**Q: Bisa ganti nama file?**
A: Tidak untuk sekarang. Ikuti nama file yang sudah ditentukan. Untuk fleksibilitas lebih, edit `src/App.tsx` secara manual.

---

**Happy customizing! 💕**
