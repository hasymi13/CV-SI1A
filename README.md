# MH Somaida - Modern Animated Portfolio Website

Website portofolio profesional dan modern untuk **MH Somaida** (UI/UX Designer & Creative Frontend Developer), dibangun dengan **React 19**, **Vite**, **Tailwind CSS v4**, dan transisi animasi dinamis menggunakan **Motion (Framer Motion)**.

---

## 🚀 Panduan Publikasi ke GitHub & GitHub Pages

Proyek ini telah dikonfigurasi penuh dengan **relative path (`base: './'`)** dan alur kerja otomatis **GitHub Actions (`.github/workflows/deploy.yml`)**, sehingga dapat langsung dipublikasikan ke GitHub dan di-hosting gratis di GitHub Pages tanpa konfigurasi tambahan!

### Langkah 1: Buat Repository Baru di GitHub
1. Masuk ke akun Anda di [GitHub.com](https://github.com).
2. Klik tombol **New** (atau ikon `+` di kanan atas) untuk membuat repository baru.
3. Beri nama repository, misalnya: `portfolio` atau `mh-somaida-portfolio`.
4. Pilih **Public**, lalu klik **Create repository** (jangan centang "Initialize with README" karena proyek ini sudah memilikinya).

---

### Langkah 2: Hubungkan & Push Proyek ke GitHub
Buka terminal di folder proyek ini di komputer Anda, lalu jalankan perintah berikut secara berurutan:

```bash
# 1. Inisialisasi Git
git init

# 2. Tambahkan semua file ke staging
git add .

# 3. Lakukan commit pertama
git commit -m "feat: initial commit MH Somaida animated portfolio"

# 4. Ubah branch utama menjadi main
git branch -M main

# 5. Hubungkan dengan repository GitHub Anda (ganti USERNAME dan REPO_NAME)
git remote add origin https://github.com/USERNAME/REPO_NAME.git

# 6. Push kode ke GitHub
git push -u origin main
```

---

### Langkah 3: Aktifkan GitHub Pages (Otomatis dengan GitHub Actions)
1. Buka repository Anda di GitHub, lalu klik menu **Settings** (Pengaturan).
2. Di bilah sisi kiri, pilih menu **Pages**.
3. Pada bagian **Build and deployment** -> **Source**, pilih opsi:
   👉 **`GitHub Actions`**
4. Selesai! GitHub Actions akan secara otomatis menjalankan file `.github/workflows/deploy.yml`, mengompilasi proyek dengan `npm run build`, dan mempublikasikannya ke alamat:
   ```
   https://USERNAME.github.io/REPO_NAME/
   ```

---

## 🛠️ Pengembangan Lokal (Local Development)

Jika Anda ingin menjalankan atau memodifikasi website ini di komputer lokal:

```bash
# 1. Install semua dependensi
npm install

# 2. Jalankan server pengembangan
npm run dev

# 3. Akses melalui browser
http://localhost:3000
```

### Build untuk Produksi
```bash
# Membuat bundle produksi di folder dist/
npm run build

# Menjalankan preview dari build produksi
npm run preview
```

---

## 🌟 Fitur Utama
- **Desain Modern & Terstruktur**: Terinspirasi dari estetika clean portofolio dengan kurva organik ungu-violet (*organic fluid shapes*).
- **Wajah Terlihat Utuh (Unobstructed View)**: Desain responsif memastikan foto potret profil tidak terhalang oleh kartu/badge di layar ponsel maupun desktop.
- **Rel Sosial Vertikal (*Vertical Social Rail*)**: Tautan Dribbble, Behance, Instagram, dan GitHub di sisi kiri dengan indikator panah animasi.
- **Laboratorium Animasi (*Kinetic Motion Lab*)**:
  - Efek kemiringan interaktif 3D (*3D Gyro Perspective Tilt*) dengan pantulan cahaya *real-time*.
  - Pilihan simulasi animasi: *Anime Spring Pop*, *Fluid Liquid Morph*, *Staggered Cascade*, dan *Zen Harmonic Float*.
- **Portofolio Bento Grid**: Filter kategori interaktif (*Mobile App*, *Web Dev*, *UI/UX Design*) dan modal studi kasus detail.
- **Dukungan Dua Bahasa**: Tombol alih bahasa instan antara **Bahasa Indonesia** dan **English**.
- **Dark & Light Mode**: Mode gelap dan terang yang halus dengan kontras terjaga.
- **Formulir Kontak Interaktif**: Validasi formulir instan dengan animasi umpan balik terkirim.

---

## 📦 Teknologi yang Digunakan
- **React 19**
- **Vite 8**
- **Tailwind CSS v4** (`@tailwindcss/vite`)
- **Motion / Framer Motion** (`motion/react`)
- **Lucide Icons**
- **TypeScript**

---

© 2026 MH Somaida. All rights reserved.
