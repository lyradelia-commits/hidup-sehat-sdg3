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
- **Sumber gambar dicantumkan** — kredit fotografer dan lisensi tercantum pada
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

## 🖼️ Sumber gambar (Wikimedia Commons)

Semua foto berasal dari Wikimedia Commons dan digunakan sesuai lisensinya.
Foto berlisensi CC BY / CC BY-SA mencantumkan nama pembuat pada caption di halaman.

| Berkas | Judul asli di Commons | Pembuat | Lisensi |
|---|---|---|---|
| `hero-beranda.jpg` | Healthy is health.jpg | SharonDawn | CC BY-SA 4.0 |
| `gizi-hero.jpg` | Healthy meal planning with fresh fruits and vegetables in a bright kitchen setting.jpg | Shixart1985 | CC BY 2.0 |
| `gizi-pasar.jpg` | Vegetable and fruit section in Denpasar market..JPG | Rudolph.A.furtado | CC0 |
| `gizi-hidrasi.jpg` | Boy drinking water in house.jpg | Debske | CC0 |
| `aktivitas-hero.jpg` | Jogger Centennial Park 001.jpg | Sardaka | CC BY-SA 4.0 |
| `aktivitas-yoga.jpg` | Outdoor Yoga At the Park.jpg | Vuemobi Media | CC BY-SA 2.0 |
| `mental-hero.jpg` | Meditation Focus Point.jpg | Bondigoldwiki | CC0 |
| `pencegahan-hero.jpg` | Washing hands with soap (1).jpg | Beat Ruest | CC BY-SA 4.0 |
| `pencegahan-tensi.jpg` | Blood pressure measurement, Poland.png | Kris D | CC BY-SA 2.0 |

Tautan halaman asal tiap gambar:

- https://commons.wikimedia.org/wiki/File:Healthy_is_health.jpg
- https://commons.wikimedia.org/wiki/File:Healthy_meal_planning_with_fresh_fruits_and_vegetables_in_a_bright_kitchen_setting.jpg
- https://commons.wikimedia.org/wiki/File:Vegetable_and_fruit_section_in_Denpasar_market..JPG
- https://commons.wikimedia.org/wiki/File:Boy_drinking_water_in_house.jpg
- https://commons.wikimedia.org/wiki/File:Jogger_Centennial_Park_001.jpg
- https://commons.wikimedia.org/wiki/File:Outdoor_Yoga_At_the_Park.jpg
- https://commons.wikimedia.org/wiki/File:Meditation_Focus_Point.jpg
- https://commons.wikimedia.org/wiki/File:Washing_hands_with_soap_(1).jpg
- https://commons.wikimedia.org/wiki/File:Blood_pressure_measurement,_Poland.png

Keterangan lisensi:

- **CC0** — domain publik, bebas dipakai tanpa syarat atribusi (kredit tetap dicantumkan).
- **CC BY 2.0** — bebas dipakai dan diubah, wajib mencantumkan pembuat.
- **CC BY-SA 2.0 / 4.0** — seperti CC BY, karya turunan memakai lisensi yang sama.
  Gambar di situs ini hanya diubah ukuran dan dikompres, isinya tidak diubah.

Font **Plus Jakarta Sans** dimuat dari Google Fonts dengan lisensi SIL Open Font License 1.1.

## 🚀 Menjalankan secara lokal

Cukup buka `index.html` di browser (klik dua kali). Semua path bersifat relatif,
jadi folder ini bisa dipindah atau di-zip tanpa merusak tampilan.

## ⚠️ Catatan

Situs ini bersifat edukatif untuk masyarakat umum, **bukan pengganti konsultasi
medis**. Untuk keluhan kesehatan, hubungi fasilitas kesehatan terdekat.
Layanan konseling kesehatan jiwa Kemenkes: **119 ekstensi 8**.
