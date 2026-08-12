# Portofolio & Tugas Sekolah - Grace Caroline

Website portofolio interaktif ini dibuat khusus untuk mempublikasikan profil pribadi Anda serta kumpulan tugas sekolah untuk mata pelajaran **Informatika** dan **Bahasa Indonesia**. Desain website mengusung tema **pastel pink** yang estetis, modern, dan seimbang.

## 🚀 Fitur Utama
1. **Navigasi Single Page Application (SPA)**: Perpindahan antar menu (Dashboard, Profil, Informatika, Bahasa Indonesia) berjalan mulus tanpa reload halaman.
2. **Dashboard Dinamis**: Menampilkan statistik jumlah tugas otomatis, daftar tugas terbaru, dan widget **Catatan Tempel (Sticky Notes)** interaktif untuk pengingat belajar.
3. **Penyimpanan Lokal (LocalStorage)**: Tugas sekolah baru yang Anda tulis dan catatan tempel akan tersimpan secara otomatis di browser Anda. Data tidak akan hilang bahkan setelah halaman di-refresh.
4. **Fitur Pencarian Real-Time**: Cari judul atau deskripsi tugas Anda dengan mudah di halaman mata pelajaran.
5. **Form & Detail Interaktif**: Tulis tugas baru melalui form modal dan baca tugas secara detail dengan tampilan popup yang bersih.
6. **Ikon Modern & Estetis**: Menggunakan Lucide Icons untuk semua visual ikon di dalam website.

---

## 💻 Cara Menjalankan Website Secara Lokal

Karena website ini dibangun dalam satu file HTML mandiri (`index.html`), Anda bisa menjalankannya dengan sangat mudah:

### Metode 1: Klik Ganda
Cukup klik ganda (double-click) file `index.html` di komputer Anda, dan website akan terbuka di browser kesayangan Anda.

### Metode 2: Menggunakan Live Server (Rekomendasi di VS Code)
Jika Anda menggunakan Visual Studio Code:
1. Instal ekstensi **Live Server**.
2. Klik kanan pada file `index.html` dan pilih **Open with Live Server**.
3. Website akan dijalankan di alamat lokal (biasanya `http://127.0.0.1:5500/index.html`).

---

## 🌐 Cara Meng-hosting Website ke Internet (Gratis)

Ada beberapa platform gratis dan sangat mudah untuk mempublikasikan website satu file HTML Anda agar dapat diakses oleh teman dan guru:

### 1. GitHub Pages (Sangat Direkomendasikan)
1. Buat akun di [GitHub](https://github.com).
2. Buat repositori baru (misal diberi nama `grace-portfolio`).
3. Upload file `index.html` dan `avatar.png` ke repositori tersebut.
4. Masuk ke tab **Settings** repositori > pilih menu **Pages** di sebelah kiri.
5. Pada bagian **Build and deployment**, ubah Source menjadi **Deploy from a branch** dan pilih branch `main` / `root`. Klik **Save**.
6. Tunggu beberapa menit, website Anda akan aktif di alamat `https://username-anda.github.io/grace-portfolio/`.

### 2. Netlify Drop (Paling Cepat & Instan)
1. Buka situs [Netlify Drop](https://app.netlify.com/drop).
2. Seret (drag and drop) folder `tugas-sekolah-portfolio` yang berisi `index.html` dan `avatar.png` ke area yang disediakan.
3. Website Anda langsung online dalam hitungan detik dengan URL acak (Anda bisa mengubah nama subdomain-nya secara gratis di menu Domain Settings Netlify).

### 3. Vercel
1. Buka [Vercel](https://vercel.com).
2. Hubungkan dengan akun GitHub Anda atau upload langsung folder proyek Anda.
3. Website Anda akan di-hosting secara instan dan gratis.

---

## 📁 Struktur Berkas Proyek
- `index.html` - Struktur utama website, konfigurasi Tailwind CSS, styling CSS, dan logika interaksi JavaScript.
- `avatar.png` - Foto profil estetik yang telah digenerasikan untuk tampilan Profil & Dashboard.
- `README.md` - Petunjuk dokumentasi ini.
