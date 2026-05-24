# 📁 Portfolio Jalalludin Muhammad Akbar

## Struktur File

```
portfolio/
├── index.html        ← Halaman utama (Profile & Intro)
├── projects.html     ← Halaman project portfolio
├── style.css         ← CSS utama (shared)
├── projects.css      ← CSS khusus halaman projects
├── script.js         ← JavaScript interaktif
├── images/           ← Folder untuk foto & gambar
│   └── profile.jpg   ← (taruh foto profile di sini)
└── projects/         ← Folder detail project (opsional)
```

---

## 🖼️ Cara Ganti Foto Profile

1. Siapkan foto dengan nama: `profile.jpg`
2. Upload ke folder: `/images/`
3. Buka `index.html`, cari bagian ini:
   ```html
   <!-- <img src="images/profile.jpg" alt="Jalalludin Muhammad Akbar"> -->
   <div class="profile-placeholder">...</div>
   ```
4. Hapus tag `<div class="profile-placeholder">...</div>`
5. Uncomment (hapus `<!--` dan `-->`) tag `<img>`
6. Save dan upload ulang

---

## ➕ Cara Tambah Project Baru

1. Buka file: `projects.html`
2. Scroll ke bawah, cari komentar `CARA TAMBAH PROJECT BARU`
3. Copy salah satu block `<div class="project-card">...</div>`
4. Paste setelah project terakhir (sebelum `</div><!-- end projects-grid -->`)
5. Ganti isi sesuai project baru:
   - `data-category` → `arduino` / `elektronika` / `sensor` / `robotik`
   - Emoji ikon di tengah card
   - Nama & deskripsi project
   - Tag komponen yang digunakan
6. Upload ulang file ke hosting

### Kategori Filter yang Tersedia:
- `arduino` → Project berbasis Arduino
- `elektronika` → Rangkaian elektronika
- `sensor` → Project berbasis sensor
- `robotik` → Project robotik

---

## 🌐 Cara Hosting

### GitHub Pages (GRATIS):
1. Buat akun di github.com
2. Buat repository baru (misal: `portfolio`)
3. Upload semua file ke repository
4. Masuk Settings → Pages
5. Source: pilih branch `main` → folder `/ (root)`
6. Website live di: `https://username.github.io/portfolio`

### Netlify (GRATIS):
1. Buat akun di netlify.com
2. Drag & drop folder portfolio ke Netlify
3. Website langsung live dengan URL gratis
4. Bisa custom domain

### Vercel (GRATIS):
1. Buat akun di vercel.com
2. Connect ke GitHub repository
3. Deploy otomatis setiap kali update

---

## 🔄 Cara Update Website

1. Edit file yang diinginkan
2. Upload ulang ke hosting
3. Website otomatis terupdate

---

## 🎨 Warna & Tema

Untuk ganti warna, edit bagian `:root` di `style.css`:

```css
:root {
  --gold-primary: #d6b58a;  /* Warna emas utama */
  --gold-light: #e7c9a9;    /* Emas terang */
  --gold-dark: #c8a97e;     /* Emas gelap */
  --bg-primary: #0a0f1e;    /* Background utama */
}
```

---

© 2024 Jalalludin Muhammad Akbar | SMK 7 Semarang
