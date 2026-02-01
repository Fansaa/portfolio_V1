# Personal Portfolio – Static Build

Repository / folder ini berisi **hasil build (static export)** dari sebuah website **Personal Portfolio berbasis Next.js**.  
Seluruh file di dalamnya **siap langsung di-deploy** ke static hosting tanpa membutuhkan Node.js runtime.

---

## 📌 Deskripsi Singkat

- Framework: **Next.js (Static Export)**
- Tipe: **Static Website**
- Tujuan: **Personal Portfolio**
- Status: **Production-ready build**

Folder ini **bukan source code**, melainkan output dari proses build.

---

## 📁 Struktur Utama

### Core Files
- **`index.html`**  
  Halaman utama website (entry point).

- **`default.html`**  
  Fallback halaman default server.

---

### Next.js Build Output
- **`_next/`**  
  Asset utama Next.js (JS, CSS, runtime).

- **`_next/static/`**  
  File statis hasil optimasi build.

- **`_not-found/`, `404/`**  
  Routing halaman error.

---

### Error Pages
Digunakan oleh server / hosting:
- `400.html`
- `401.html`
- `403.html`
- `404.html`
- `413.html`
- `500.html`
- `cp_errordocument.shtml`

---

### Assets
- **`fathan-fardian-sanum.jpg`**  
  Gambar profil utama.

- **`portrait-of-informatics-engineering-student.jpg`**  
  Gambar pendukung.

- **`placeholder-*.png / jpg / svg`**  
  Asset placeholder UI.

---

### Build Metadata
- `_next_INDEX.txt`
- `_next_full.txt`
- `_next_tree.txt`
- `_next_PAGE__.txt`
- `index.txt`

Digunakan untuk keperluan internal build dan debugging.

---

## 🚀 Cara Deployment

### Shared Hosting / cPanel
1. Upload **seluruh isi folder ini** ke:
2. Pastikan `index.html` berada di root directory.
3. Website langsung dapat diakses.

### Static Hosting (Netlify, dsb)
- **Publish directory**: root folder ini
- **Build command**: tidak diperlukan

---

## ⚠️ Catatan Penting

- Jangan mengedit file di dalam folder `_next/`.
- Untuk perubahan konten atau desain:
1. Edit source code Next.js
2. Jalankan build ulang (`next build && next export`)
3. Upload ulang hasil build

---

## 👤 Author

**Fathan Fardian Sanum**  
Personal Portfolio Website  
Built using Next.js (Static Export)

---

