# Hidup Sehat — Edukasi Kesehatan Masyarakat (SDG 3)

Website statis bertema **SDG 3: Kehidupan Sehat dan Sejahtera**, berisi edukasi
kesehatan masyarakat untuk publik. Dibuat sebagai tugas mata kuliah
**Pemrograman Web** menggunakan **HTML dan CSS murni tanpa framework**
(tidak ada Bootstrap, Tailwind, React, atau library CSS lainnya).

## 🌐 Link

| Kebutuhan tugas | Link |
|---|---|
| **Versi online** (tampilan langsung) | https://lyradelia-commits.github.io/hidup-sehat-sdg3/ |
| **Versi repositori GitHub** (source code) | https://github.com/lyradelia-commits/hidup-sehat-sdg3 |

## 📄 Halaman (7 halaman)

| No | File | Isi |
|---|---|---|
| 1 | `index.html` | Beranda: pengenalan SDG 3, statistik kunci, navigasi ke lima materi |
| 2 | `pola-hidup-sehat.html` | Tujuh kebiasaan dasar, tabel kebutuhan tidur, batas G4-G1-L5, mitos vs fakta |
| 3 | `gizi-seimbang.html` | Panduan Isi Piringku, angka acuan WHO, tabel menu harian |
| 4 | `aktivitas-fisik.html` | Anjuran WHO per kelompok usia, intensitas sedang/berat, tips mulai dari nol |
| 5 | `kesehatan-mental.html` | Beda stres–cemas–depresi, kebiasaan menjaga pikiran, layanan bantuan |
| 6 | `pencegahan-penyakit.html` | 6 langkah cuci tangan, jadwal imunisasi, skrining, bahaya rokok |
| 7 | `sumber.html` | Daftar sumber rujukan + kredit foto dan lisensi |

## 📁 Struktur folder

```
hidup-sehat-sdg3/
├── index.html
├── pola-hidup-sehat.html
├── gizi-seimbang.html
├── aktivitas-fisik.html
├── kesehatan-mental.html
├── pencegahan-penyakit.html
├── sumber.html
├── css/
│   └── style.css          ← satu-satunya file CSS (eksternal)
├── js/
│   └── main.js            ← hanya untuk tombol menu di ponsel
├── assets/
│   ├── favicon.svg
│   └── img/               ← 9 foto, sudah dikompres
└── README.md
```

## ✅ Kesesuaian dengan ketentuan tugas

- **Dua link** — versi online (GitHub Pages) dan versi repositori GitHub, keduanya tercantum di atas.
- **Minimal 5 halaman** — tersedia 7 halaman HTML yang saling terhubung.
- **Konten sesuai tema SDG 3** — pola hidup sehat, gizi seimbang, aktivitas fisik,
  kesehatan mental, dan pencegahan penyakit.
- **Sumber gambar dicantumkan** — nama penerbit dan judul artikel tercantum pada
  setiap caption gambar dan di halaman `sumber.html` (lihat juga bagian bawah README ini).
- **HTML + CSS tanpa framework** — semua tata letak dibuat dengan CSS Grid, Flexbox,
  dan media query sendiri. Tidak ada CDN framework apa pun.
- **Konten valid** — seluruh 7 halaman lolos **W3C Markup Validation Service**
  (0 error) dan CSS lolos **W3C CSS Validator** (0 error).
- **Bisa diakses orang luar** — di-hosting gratis di GitHub Pages (publik).
- **Statis dan responsive** — diuji pada lebar 390 px (ponsel), 820 px (tablet),
  dan 1280 px (desktop). Tabel otomatis berubah menjadi kartu bertumpuk di layar kecil.

## 📱 Responsif

| Lebar layar | Perilaku |
|---|---|
| ≤ 560 px | Menu jadi tombol "Menu", tabel jadi kartu bertumpuk, tombol selebar layar |
| 561–1040 px | Navigasi jadi menu lipat, kolom konten menumpuk satu kolom |
| > 1040 px | Navigasi horizontal penuh, tata letak dua kolom |

## 🔎 Sumber konten

Angka dan anjuran diambil dari lembaga resmi, lalu ditulis ulang dengan bahasa sendiri:

- **WHO** — *Physical activity*, *Healthy diet*, *Salt reduction*, *Noncommunicable
  diseases*, *Mental disorders*, *Mental health*, *Tobacco*, *Hand hygiene* fact sheets.
- **Kementerian Kesehatan RI** — Isi Piringku, G4-G1-L5, aktivitas fisik, jadwal
  imunisasi rutin, kebutuhan tidur, layanan Sehat Jiwa (119 ext. 8).
- **BKPK Kemenkes** — Survei Kesehatan Indonesia (SKI) 2023.
- **PBB** — Sustainable Development Goal 3.

Daftar lengkap dengan URL ada di halaman **`sumber.html`**.

## 🖼️ Sumber gambar

Seluruh foto diambil dari artikel pada situs resmi penerbitnya (bukan dari mesin
pencari gambar), lalu disimpan ulang ke folder `assets/img/` agar situs tetap
ringan. Nama penerbit dan judul artikel dicantumkan pada caption di bawah setiap
foto dan pada tabel kredit di halaman `sumber.html`.

| Berkas | Judul artikel / halaman asal | Penerbit | Tautan |
|---|---|---|---|
| `hero-beranda.jpg` | Pola Makan Sehat: Kunci Mencegah Penyakit dan Meningkatkan Kualitas Hidup | Medistra Hospital | https://medistra.com/article/pola-makan-sehat-kunci-mencegah-penyakit-dan-meningkatkan-kualitas-hidup |
| `aktivitas-hero.jpg` | Jogging: Artinya Apa dan Bagaimana Cara Melakukannya | Fithub Indonesia | https://fithub.id/blog/jogging-artinya |
| `gizi-hidrasi.jpg` | Jangan Remehkan Manfaat Air Putih | Alodokter | https://www.alodokter.com/jangan-remehkan-manfaat-air-putih |
| `gizi-pasar.jpg` | Tips dan Trik Memilih Buah dan Sayuran di Pasar Tradisional | Jurnalpost | https://jurnalpost.com/tips-dan-trik-memilih-buah-dan-sayuran-di-pasar-tradisional/89125/ |
| `gizi-hero.jpg` | Pakar Gizi Ingatkan Perlunya Gizi Seimbang pada Penderita Anemia | ANTARA News Sulawesi Tengah | https://sulteng.antaranews.com/berita/177984/pakar-gizi-ingatkan-perlunya-gizi-seimbang-pada-penderita-anemia |
| `minum-air-makan.jpg` | Kenapa Harus Minum Air Putih Setelah Makan? | Cleopure Water | https://cleopurewater.com/blog/kesehatan/kenapa-harus-minum-air-putih-setelah-makan/ |
| `aktivitas-lari.jpg` | Hari Lari Sedunia 7 Juni, Yuk Simak Manfaat Berlari | detikcom | https://news.detik.com/berita/d-6759293/hari-lari-sedunia-7-juni-yuk-simak-manfaat-berlari |
| `aktivitas-yoga.jpg` | Jenis-jenis Yoga yang Baik bagi Tubuh | KlikDokter | https://www.klikdokter.com/gaya-hidup/sehat-bugar/jenis-jenis-yoga-yang-baik-bagi-tubuh |
| `mental-hero.jpg` | 4 Gangguan Mental yang Terjadi Tanpa Disadari | Halodoc | https://www.halodoc.com/artikel/4-gangguan-mental-yang-terjadi-tanpa-disadari |
| `pencegahan-hero.jpg` | Cuci Tangan Pakai Sabun: Kebiasaan Sederhana untuk Mencegah Penyebaran Penyakit | Farmasi UMMADA | https://farmasi.ummada.ac.id/2026/08/10/cuci-tangan-pakai-sabun-kebiasaan-sederhana-untuk-mencegah-penyebaran-penyakit/ |
| `pencegahan-tensi.jpg` | Berapa Tekanan Darah Normal Orang Dewasa? | Alodokter | https://www.alodokter.com/berapa-tekanan-darah-normal-orang-dewasa |

Gambar hanya disesuaikan ukuran dan kompresinya agar cepat dimuat; isi foto tidak
diubah. Kredit selalu dicantumkan sebagai bentuk kejujuran akademik.

Font **Plus Jakarta Sans** dimuat dari Google Fonts dengan lisensi SIL Open Font License 1.1.

## 🚀 Menjalankan secara lokal

Cukup buka `index.html` di browser (klik dua kali). Semua path bersifat relatif,
jadi folder ini bisa dipindah atau di-zip tanpa merusak tampilan.

## ⚠️ Catatan

Situs ini bersifat edukatif untuk masyarakat umum, **bukan pengganti konsultasi
medis**. Untuk keluhan kesehatan, hubungi fasilitas kesehatan terdekat.
Layanan konseling kesehatan jiwa Kemenkes: **119 ekstensi 8**.
