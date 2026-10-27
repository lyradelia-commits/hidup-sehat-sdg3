# Hidup Sehat — Edukasi Kesehatan Masyarakat (SDG 3)

Website statis bertema **SDG 3: Kehidupan Sehat dan Sejahtera** yang berisi edukasi
kesehatan masyarakat untuk publik. Dibangun dengan **HTML dan CSS murni tanpa framework**
sebagai tugas mata kuliah **Pemrograman Web**.

---

## 1. Identitas Kelompok dan Pembagian Tugas

**Mata kuliah:** Pemrograman Web
**Judul tugas:** Website Edukasi Kesehatan Masyarakat Bertema SDG 3
**Jumlah halaman:** 7 halaman HTML statis

| No | Nama | NIM | Pembagian tugas |
|---|---|---|---|
| 1 | **Kadek Lyradelia Pracili** | 2515091032 | Struktur proyek & stylesheet global (`css/style.css`), halaman Beranda, halaman Sumber, pengelolaan aset gambar, build & deploy ke GitHub Pages |
| 2 | **Astria Laura Dwi Putri** | 2515091082 | Halaman Pola Hidup Sehat dan Gizi Seimbang, penyusunan tabel data (kebutuhan tidur, porsi Isi Piringku), verifikasi angka rujukan WHO/Kemenkes |
| 3 | **Dhea Natasya Putri** | 2515091131 | Halaman Aktivitas Fisik, Kesehatan Mental, dan Pencegahan Penyakit, navigasi & menu mobile, pengujian responsif 1440/768/375 px |

> Pembagian tugas di atas mengikuti kepemilikan halaman. Silakan sesuaikan isi kolom
> terakhir bila pembagian di kelompok berbeda.

---

## 2. Judul, Tema SDGs, dan Sasaran Pengguna

**Judul website:** Hidup Sehat — Edukasi Kesehatan Masyarakat

**Tema SDGs:** **Goal 3 — Good Health and Well-being (Kehidupan Sehat dan Sejahtera)**

Alasan memilih tema ini: SDG 3 menyentuh seluruh siklus hidup manusia, dan capaiannya
sangat ditentukan oleh perilaku harian — makan, bergerak, tidur, mengelola stres,
menjaga kebersihan — bukan hanya oleh layanan rumah sakit. Perilaku itulah yang bisa
diedukasi lewat media yang mudah diakses, salah satunya website.

**Sasaran pengguna:**

| Segmen | Kebutuhan yang dilayani |
|---|---|
| **Remaja & mahasiswa (15–24 tahun)** | Anjuran aktivitas fisik, gizi praktis dengan budget terbatas, cara mengenali stres dan mencari bantuan |
| **Keluarga muda / orang tua** | Panduan porsi makan keluarga, jadwal imunisasi anak, kebiasaan bersih di rumah |
| **Masyarakat umum dengan literasi kesehatan rendah** | Penjelasan singkat tanpa istilah medis rumit, angka yang bisa langsung dipakai |
| **Kader kesehatan / pelajar** | Rujukan cepat ke sumber resmi WHO dan Kemenkes yang bisa diverifikasi |

---

## 3. Tujuan, Manfaat, dan Deskripsi Setiap Halaman

### 3.1 Tujuan

1. Menyediakan kanal edukasi kesehatan berbahasa Indonesia yang **ringkas, mudah dibaca, dan berbasis rujukan resmi** (WHO dan Kementerian Kesehatan RI).
2. Menerjemahkan angka dan anjuran kesehatan menjadi **tindakan harian yang konkret**, bukan sekadar informasi.
3. Membiasakan pembaca **memverifikasi sumber** — setiap angka bisa dilacak ke publikasi aslinya.
4. Memenuhi capaian pembelajaran mata kuliah Pemrograman Web: membangun situs **statis, valid, dan responsif** tanpa framework.

### 3.2 Manfaat

| Bagi | Manfaat |
|---|---|
| **Pembaca umum** | Tahu batas gula/garam/lemak, menit aktivitas fisik yang dibutuhkan, dan tanda kapan harus mencari bantuan kesehatan mental |
| **Mahasiswa** | Contoh penerapan nyata HTML semantik, CSS Grid/Flexbox, media query, dan aksesibilitas dasar |
| **Kelompok penyusun** | Latihan kerja tim: pembagian halaman, konsistensi desain, pengujian lintas perangkat, dan pengelolaan repositori |

### 3.3 Deskripsi setiap halaman

| No | Halaman | Tujuan halaman | Isi utama |
|---|---|---|---|
| 1 | **Beranda** (`index.html`) | Memberi gambaran tema dan mengarahkan pengunjung ke lima materi | Hero, 4 kartu statistik global (31% kurang aktif · 1 dari 7 gangguan mental · 75% kematian akibat PTM · 1/3 target SDG 3.4), 5 kartu pilar materi, alasan pentingnya pencegahan, ajakan bertindak |
| 2 | **Pola Hidup Sehat** (`pola-hidup-sehat.html`) | Menjelaskan kebiasaan dasar yang menopang kesehatan | Definisi pola hidup sehat, 7 kebiasaan (tidur, makan, gerak, kebersihan, rokok, stres, cek kesehatan), tabel kebutuhan tidur per usia, batas G4-G1-L5, ceklis harian, mitos vs fakta |
| 3 | **Gizi Seimbang** (`gizi-seimbang.html`) | Mengajarkan komposisi dan porsi makan yang benar | Prinsip Isi Piringku, tabel porsi per kelompok pangan, 4 angka acuan WHO (400 g · 25 g · <5 g · <10%), G4-G1-L5, tabel contoh menu sehari, FAQ |
| 4 | **Aktivitas Fisik** (`aktivitas-fisik.html`) | Menjelaskan berapa banyak gerak yang dibutuhkan tubuh | Data kurang gerak (WHO & SKI 2023), tabel anjuran per kelompok usia, cara membedakan intensitas ringan/sedang/berat, panduan mulai dari nol, tips mengurangi duduk lama |
| 5 | **Kesehatan Mental** (`kesehatan-mental.html`) | Mengurangi stigma dan menunjukkan jalan mencari bantuan | Definisi sehat mental (WHO), tabel pembeda stres–cemas–depresi, 6 kebiasaan menjaga pikiran, 6 tanda perlu bantuan, layanan bantuan di Indonesia (119 ext. 8, puskesmas, kampus, psikolog) |
| 6 | **Pencegahan Penyakit** (`pencegahan-penyakit.html`) | Membedakan strategi pencegahan penyakit menular dan tidak menular | Dua kelompok penyakit, 6 langkah cuci tangan pakai sabun, tabel jadwal imunisasi rutin, pengendalian faktor risiko PTM, bahaya rokok, FAQ |
| 7 | **Sumber** (`sumber.html`) | Menyediakan transparansi rujukan dan kredit aset | Tabel 25 sumber rujukan, tabel kredit 11 foto beserta penerbit dan tautan artikel asli, catatan tentang situs, informasi kontak darurat |

Semua halaman memakai navigasi, *footer*, dan gaya visual yang sama agar pengunjung
tidak merasa berpindah situs.

---

## 4. Teknologi yang Digunakan

| Kategori | Teknologi | Keterangan |
|---|---|---|
| **Markup** | HTML5 | Elemen semantik: `header`, `nav`, `main`, `section`, `article`, `figure`, `figcaption`, `table`, `thead`, `tbody`, `th scope`, `details`, `summary`, `footer` |
| **Styling** | CSS3 murni | CSS Custom Properties (variabel), Grid Layout, Flexbox, `clamp()`, media queries, `prefers-reduced-motion`, `@media print` |
| **Interaksi** | JavaScript ES5 (vanilla) | **32 baris**, hanya untuk tombol menu di layar kecil. Tanpa library, tanpa framework |
| **Tipografi** | Google Fonts — Plus Jakarta Sans | Lisensi SIL Open Font License 1.1, bobot 400/600/700/800 |
| **Ikon** | SVG inline | Ditulis langsung di HTML, tidak perlu file ikon tambahan |
| **Gambar** | JPEG terkompresi | Maksimal 1400 px, kualitas 85, disimpan lokal di `assets/img/` |
| **Version control** | Git + GitHub | Repositori publik, riwayat commit per tahap pengerjaan |
| **Hosting** | GitHub Pages | Hosting statis gratis, ter-deploy otomatis dari branch `main` |
| **Validasi** | Nu HTML Checker (`vnu.jar`) & W3C CSS Validator | Engine sama dengan validator.w3.org — hasil **0 error** |

**Yang sengaja TIDAK dipakai:** Bootstrap, Tailwind, Bulma, jQuery, React, Vue,
SASS/SCSS, maupun build tool apa pun. Total ada **0 dependensi** — cukup buka
`index.html` di browser.

---

## 5. Penjelasan Penting dari Implementasi

Lima hal yang diminta — HTML, CSS, navigasi, Flexbox/Grid, dan media queries — masing-masing
satu paragraf penjelasan + satu contoh kode yang benar-benar dipakai di proyek.

### 5.1 HTML — semantik dan struktur halaman

Semua halaman memakai kerangka yang sama: `header` (logo + navigasi) → `main` (isi) →
`footer`. Tiga baris berikut wajib ada dan punya alasan masing-masing:

```html
<html lang="id">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="css/style.css">
```

`lang="id"` agar pembaca layar memakai pelafalan Indonesia. `viewport` adalah syarat
agar media query bekerja di ponsel — tanpa baris ini halaman dirender selebar ±980 px
lalu dikecilkan, sehingga semua teks terlihat kecil. CSS ditaruh di file eksternal
karena itu yang disyaratkan tugas.

Tabel diberi `caption` + `scope` supaya terbaca sebagai tabel oleh pembaca layar:

```html
<table>
  <caption>Jadwal imunisasi rutin (Kemenkes RI)</caption>
  <thead><tr><th scope="col">Usia</th><th scope="col">Imunisasi</th></tr></thead>
  <tbody><tr><th scope="row">2 bulan</th><td data-label="Imunisasi">DPT-HB-Hib 1</td></tr></tbody>
</table>
```

Atribut `data-label` bukan atribut standar HTML — dipakai CSS pada bagian 5.5 untuk
menampilkan nama kolom ketika tabel berubah menjadi kartu di layar kecil.

### 5.2 CSS — satu file, variabel, dan teks adaptif

Seluruh 7 halaman memakai satu file `css/style.css` (936 baris, dibagi 20 bagian
berkomentar). Warna dan ukuran disimpan sebagai variabel agar tema bisa diubah dari
satu tempat, dan ukuran judul memakai `clamp()` sehingga tidak perlu media query:

```css
:root { --hijau-700: #146c52; --garis: #d8e6df; --radius: 16px; --lebar: 1120px; }

/* minimum 2rem · mengikuti lebar layar · maksimum 3.5rem */
h1 { font-size: clamp(2rem, 1.35rem + 3.2vw, 3.5rem); }

.container { width: min(100% - 2.5rem, var(--lebar)); margin-inline: auto; }
```

Hasil terukur: H1 menjadi **33,6 px di 375 px**, **46 px di 768 px**, dan **56 px di
1440 px** — tanpa satu pun media query tambahan.

### 5.3 Navigasi — Flexbox dan penanda halaman aktif

Header memakai `position: sticky` agar menu tetap terlihat saat di-scroll, dengan
susunan Flexbox satu baris:

```css
.nav { display: flex; align-items: center; justify-content: space-between; gap: 1rem; }
```

Halaman aktif ditandai dengan `aria-current="page"` (atribut, bukan class), lalu
diwarnai lewat selektor atribut. Cara ini membuat penanda aktif juga terbaca pembaca
layar, bukan sekadar berbeda warna:

```html
<li><a href="index.html" aria-current="page">Beranda</a></li>
```

```css
.nav-menu a[aria-current="page"] { background: var(--hijau-900); color: #fff; }
```

Di bawah 1040 px tujuh item menu tidak muat lagi, sehingga diganti tombol:

```css
@media (max-width: 1040px) {
  .nav-toggle { display: inline-flex; margin-left: auto; min-height: 44px; }
  .situs-header nav { display: contents; }   /* agar tombol menempel ke kanan */
  .nav-menu { position: absolute; top: 100%; left: 0; right: 0; display: none; }
  .nav-menu.buka { display: flex; }
}
```

JavaScript hanya 32 baris untuk menambah/hapus class `.buka` dan menjaga atribut
`aria-expanded`. Situs tetap bisa dipakai tanpa JavaScript karena seluruh tautan juga
tersedia di footer.

### 5.4 Flexbox dan Grid — pembagian tugasnya

**Grid** untuk tata letak dua dimensi (hero, kartu, statistik, footer). **Flexbox**
untuk susunan satu arah (navbar, tombol, daftar centang).

```css
/* Grid: jumlah kolom menyesuaikan sendiri, 1 -> 2 -> 3 */
.grid-3 { grid-template-columns: repeat(auto-fit, minmax(255px, 1fr)); }

/* Grid dua kolom dengan proporsi 1.05 : 0.95 supaya sisi teks lebih lebar */
.hero-dalam { display: grid; grid-template-columns: 1.05fr .95fr; gap: 2rem; }

/* Flexbox: tombol otomatis turun baris kalau ruang habis */
.hero-aksi { display: flex; flex-wrap: wrap; gap: .75rem; }
```

Satu baris `auto-fit` + `minmax` di atas menggantikan dua media query, karena jumlah
kolom dihitung sendiri oleh browser.

### 5.5 Media queries — lima titik henti

Titik henti ditentukan dari **kapan tata letak mulai rusak**, bukan dari nama perangkat:

| Media query | Alasan batasnya | Yang berubah |
|---|---|---|
| `min-width: 1000px` | 3 kolom kartu masih nyaman di atas lebar ini | Kartu pilar dipaksa 3+3, tidak menggantung |
| `max-width: 1040px` | 7 menu + logo tidak muat satu baris | Menu jadi tombol, hero & konten jadi 1 kolom |
| `min-width: 561px` – `max-width: 900px` | 4 kartu statistik pecah jadi 3+1 | Statistik jadi 2×2 |
| `max-width: 700px` | Tabel 5 kolom sudah terlalu sempit | **Tabel jadi kartu bertumpuk** |
| `max-width: 560px` | Lebar ponsel umum | Teks 17 px, tombol selebar layar, target sentuh 44 px |

Bagian tersulit adalah tabel. Tabel 4–5 kolom di layar 375 px hanya menyisakan ±60 px
per kolom, jadi sel diubah menjadi blok dan nama kolom ditampilkan dari `data-label`:

```css
@media (max-width: 700px) {
  table, tbody, tr, th, td { display: block; width: 100%; }
  thead { display: none; }                    /* header tabel disembunyikan */
  caption { display: block; width: 100%; }    /* kalau tidak, caption menyusut */

  tbody td::before {
    content: attr(data-label);                /* nama kolom dari atribut HTML */
    display: block;
    font-size: .75rem;
    font-weight: 700;
    text-transform: uppercase;
    color: var(--teks-lembut);
  }
}
```

Hasilnya di ponsel tabel tetap terbaca tanpa perlu digeser ke samping:

```
DEWASA 18-64 TAHUN          <- isi <th scope="row">, jadi judul kartu
AKTIVITAS AEROBIK           <- dari data-label kolom 2
150-300 menit per minggu
INTENSITAS BERAT            <- dari data-label kolom 3
75-150 menit per minggu
```

**Hasil pengujian di tiga viewport:**

| Aspek | Desktop 1440 px | Tablet 768 px | Smartphone 375 px |
|---|---|---|---|
| Kolom konten | 2 kolom | 1 kolom | 1 kolom |
| Kartu | 3 kolom | 2 kolom | 1 kolom |
| Teks dasar | 16 px | 16 px | 17 px |
| Navigasi | 7 menu horizontal | Tombol Menu 44 px | Tombol Menu 44 px |
| Tabel | tabel penuh | tabel penuh | kartu bertumpuk |
| Scroll horizontal | tidak ada | tidak ada | tidak ada |

### 5.6 Aksesibilitas (ringkas)

- `alt` deskriptif pada semua gambar, `skip-link` untuk pengguna keyboard, dan
  `:focus-visible` dengan outline 3 px.
- `aria-current`, `aria-expanded`, dan `aria-controls` pada navigasi.
- Satu `h1` per halaman tanpa melompati level heading.
- Target sentuh minimal 44 px dan animasi dimatikan saat `prefers-reduced-motion`.

---

## 6. Struktur Folder

```
hidup-sehat-sdg3/
├── .gitignore                   # mengecualikan folder preview & file OS
├── README.md                    # dokumentasi ini
│
├── index.html                   # 1. Beranda
├── pola-hidup-sehat.html        # 2. Pola Hidup Sehat
├── gizi-seimbang.html           # 3. Gizi Seimbang
├── aktivitas-fisik.html         # 4. Aktivitas Fisik
├── kesehatan-mental.html        # 5. Kesehatan Mental
├── pencegahan-penyakit.html     # 6. Pencegahan Penyakit
├── sumber.html                  # 7. Sumber & kredit
│
├── css/
│   └── style.css                # satu-satunya stylesheet (936 baris)
│
├── js/
│   └── main.js                  # 32 baris, hanya untuk menu mobile
│
└── assets/
    ├── favicon.svg              # ikon tab browser (416 byte)
    └── img/                     # 11 foto, total lebih kurang 1,1 MB
        ├── hero-beranda.jpg
        ├── aktivitas-hero.jpg
        ├── aktivitas-lari.jpg
        ├── aktivitas-yoga.jpg
        ├── gizi-hero.jpg
        ├── gizi-hidrasi.jpg
        ├── gizi-pasar.jpg
        ├── minum-air-makan.jpg
        ├── mental-hero.jpg
        ├── pencegahan-hero.jpg
        └── pencegahan-tensi.jpg
```

**Ringkasan jumlah berkas:**

| Jenis | Jumlah | Ukuran |
|---|---|---|
| Halaman HTML | 7 file | lebih kurang 148 KB (2.402 baris) |
| Stylesheet | 1 file | 23 KB (936 baris) |
| JavaScript | 1 file | 1 KB (32 baris) |
| Gambar | 11 file | lebih kurang 1,1 MB |
| Ikon | 1 file | 416 byte |
| Dokumentasi | 2 file | 7 KB |
| **Total repositori** | **23 file** | **lebih kurang 1,3 MB** |

**Alasan penataan ini:**

- `css/` dan `js/` dipisah karena tugas mensyaratkan **CSS eksternal**, bukan `<style>` di dalam HTML.
- `assets/img/` menyimpan gambar **secara lokal**, bukan hotlink ke situs lain. Kalau memakai `<img src="https://medistra.com/...">`, gambar akan mati saat situs sumber mengganti atau menghapus berkasnya, dan halaman menjadi lebih lambat.
- Folder `preview/` (screenshot hasil pengujian) **tidak di-commit** karena hanya dipakai saat menyusun laporan.

---

## 7. URL Website dan Repositori

| Keperluan | URL |
|---|---|
| **Website (versi online)** | https://lyradelia-commits.github.io/hidup-sehat-sdg3/ |
| **Repositori GitHub** | https://github.com/lyradelia-commits/hidup-sehat-sdg3 |
| Halaman Sumber (bukti rujukan) | https://lyradelia-commits.github.io/hidup-sehat-sdg3/sumber.html |

Situs di-hosting di **GitHub Pages** (gratis, publik, HTTPS) dan ter-deploy otomatis
setiap kali ada `push` ke branch `main`.

**Cara menjalankan secara lokal:** unduh/ekstrak repositori, lalu buka `index.html` di
browser (klik dua kali). Tidak perlu server, tidak perlu `npm install`, karena semua path
bersifat relatif dan tidak ada dependensi.

---

## 8. Referensi Konten dan Aset

### 8.1 Sumber konten (25 rujukan)

Angka dan anjuran di situs ini diambil dari publikasi resmi, lalu ditulis ulang dengan
bahasa sendiri. Daftar yang sama juga tersedia di halaman `sumber.html`.

| No | Sumber | Digunakan untuk |
|---|---|---|
| 1 | [WHO - Physical activity](https://www.who.int/news-room/fact-sheets/detail/physical-activity) | 150 menit/minggu, 60 menit/hari usia 5-17, data 31% kurang aktif |
| 2 | [WHO - Healthy diet](https://www.who.int/news-room/fact-sheets/detail/healthy-diet) | 400 g sayur-buah, 25 g serat, gula di bawah 10% energi |
| 3 | [WHO - Salt reduction](https://www.who.int/news-room/fact-sheets/detail/salt-reduction) | Garam di bawah 5 g/hari (natrium di bawah 2 g) |
| 4 | [WHO - Noncommunicable diseases](https://www.who.int/news-room/fact-sheets/detail/noncommunicable-diseases) | 43 juta kematian PTM 2021, 18 juta kematian dini |
| 5 | [WHO - Mental disorders](https://www.who.int/news-room/fact-sheets/detail/mental-disorders) | Hampir 1 dari 7 orang hidup dengan gangguan mental |
| 6 | [WHO - Mental health](https://www.who.int/news-room/fact-sheets/detail/mental-health-strengthening-our-response) | Definisi kesehatan mental |
| 7 | [WHO - Tobacco](https://www.who.int/health-topics/tobacco) | 8 juta kematian/tahun, 1,2 juta akibat asap rokok |
| 8 | [WHO - Hand hygiene](https://www.who.int/teams/integrated-health-services/infection-prevention-control/hand-hygiene) | Durasi cuci tangan 40-60 detik |
| 9 | [PBB - SDG 3](https://www.un.org/sustainabledevelopment/health/) | Target SDG 3.1 sampai 3.4 |
| 10 | [Kemenkes - Isi Piringku: Pedoman Makan Kekinian](https://ayosehat.kemkes.go.id/isi-piringku-pedoman-makan-kekinian-orang-indonesia) | Komposisi setengah piring sayur-buah |
| 11 | [Kemenkes - Isi Piringku, Kebutuhan Gizi Seimbang Harian](https://ayosehat.kemkes.go.id/isi-piringku-kebutuhan-gizi-harian-seimbang) | Konsep gizi seimbang |
| 12 | [Kemenkes - Batasi Gula Garam Lemak (G4-G1-L5)](https://ayosehat.kemkes.go.id/batasi-asupan-gula-garam-dan-lemak-biar-kamu-makin-keren) | Gula 4 sdm, garam 1 sdt, lemak 5 sdm |
| 13 | [Kemenkes - Aktivitas Fisik Rutin Cegah Hipertensi, Diabetes, Kolesterol](https://www.kemkes.go.id/id/aktivitas-fisik-rutin-cegah-hipertensi-diabetes-dan-kolesterol-tinggi) | Anjuran 30 menit lima hari seminggu |
| 14 | [BKPK Kemenkes - Aktifitas Fisik Penduduk Indonesia](https://www.badankebijakan.kemkes.go.id/aktifitas-fisik-penduduk-indonesia/) | Anjuran WHO 150-300 menit usia 18-64 |
| 15 | [BKPK Kemenkes - Kurang Bergerak, Ancaman Tersembunyi](https://www.badankebijakan.kemkes.go.id/kurang-bergerak-ancaman-tersembunyi-kesehatan-indonesia/) | SKI 2023: 37,4% penduduk usia 10 tahun ke atas kurang aktif |
| 16 | [Kemenkes - Pekan Imunisasi Dunia 2025](https://www.kemkes.go.id/id/pekan-imunisasi-dunia-2025-ayo-lengkapi-imunisasi-untuk-generasi-sehat-menuju-indonesia-emas) | Jadwal imunisasi rutin lengkap |
| 17 | [Kemenkes - 6 Langkah Cuci Tangan Pakai Sabun](https://ayosehat.kemkes.go.id/6-langkah-cuci-tangan-pakai-sabun) | Enam langkah CTPS |
| 18 | [Kemenkes - Lama Waktu Tidur yang Dibutuhkan Tubuh](https://upk.kemkes.go.id/new/lama-waktu-tidur-yang-dibutuhkan-oleh-tubuh) | Kebutuhan tidur per usia |
| 19 | [Kemenkes - Penting Tidur Berkualitas](https://keslan.kemkes.go.id/read/2539/penting-tidur-berkualitas-jaga-kesehatan-fisik-dan-mental) | Dewasa 7-9 jam, remaja 8-10 jam |
| 20 | [Medistra - Pola Makan Sehat: Kunci Mencegah Penyakit](https://medistra.com/article/pola-makan-sehat-kunci-mencegah-penyakit-dan-meningkatkan-kualitas-hidup) | Rujukan tambahan pola makan sehat |
| 21 | [Fithub - Jogging: Artinya dan Cara Melakukannya](https://fithub.id/blog/jogging-artinya) | Rujukan tambahan jogging |
| 22 | [ANTARA Sulteng - Gizi Seimbang pada Penderita Anemia](https://sulteng.antaranews.com/berita/177984/pakar-gizi-ingatkan-perlunya-gizi-seimbang-pada-penderita-anemia) | Rujukan tambahan gizi seimbang |
| 23 | [detikcom - Hari Lari Sedunia](https://news.detik.com/berita/d-6759293/hari-lari-sedunia-7-juni-yuk-simak-manfaat-berlari) | Manfaat berlari |
| 24 | [Halodoc - 4 Gangguan Mental yang Terjadi Tanpa Disadari](https://www.halodoc.com/artikel/4-gangguan-mental-yang-terjadi-tanpa-disadari) | Rujukan tambahan kesehatan mental |
| 25 | [Kemenkes - FAQ Layanan Healing119](https://kesprimkom.kemkes.go.id/assets/uploads/contents/others/FAQ_Cegah_Bunuh_Diri,_Dukung_Kesehatan_Jiwa__Kenali_Layanan_Healing119.id.pdf) | Layanan konseling 119 ekstensi 8 |

> **Catatan:** empat tautan `ayosehat.kemkes.go.id` di atas sempat mengembalikan
> status 503 karena situs Kemenkes sedang dalam pemeliharaan. URL-nya tetap
> dicantumkan karena itu alamat resmi artikel tersebut; bila sedang tidak bisa
> dibuka, materi yang sama bisa dicek lewat `kemkes.go.id`.

### 8.2 Aset gambar (11 foto)

Seluruh foto diambil dari **artikel pada situs resmi penerbitnya**, bukan dari mesin
pencari gambar, lalu disimpan ulang ke `assets/img/` agar situs tetap ringan dan tidak
bergantung pada server pihak lain. Nama penerbit dan judul artikel juga dicantumkan pada
caption di bawah setiap foto.

| Berkas lokal | Judul artikel asal | Penerbit | Tautan |
|---|---|---|---|
| `hero-beranda.jpg` | Pola Makan Sehat: Kunci Mencegah Penyakit dan Meningkatkan Kualitas Hidup | Medistra Hospital | [medistra.com](https://medistra.com/article/pola-makan-sehat-kunci-mencegah-penyakit-dan-meningkatkan-kualitas-hidup) |
| `aktivitas-hero.jpg` | Jogging: Artinya Apa dan Bagaimana Cara Melakukannya | Fithub Indonesia | [fithub.id](https://fithub.id/blog/jogging-artinya) |
| `gizi-hidrasi.jpg` | Jangan Remehkan Manfaat Air Putih | Alodokter | [alodokter.com](https://www.alodokter.com/jangan-remehkan-manfaat-air-putih) |
| `gizi-pasar.jpg` | Tips dan Trik Memilih Buah dan Sayuran di Pasar Tradisional | Jurnalpost | [jurnalpost.com](https://jurnalpost.com/tips-dan-trik-memilih-buah-dan-sayuran-di-pasar-tradisional/89125/) |
| `gizi-hero.jpg` | Pakar Gizi Ingatkan Perlunya Gizi Seimbang pada Penderita Anemia | ANTARA News Sulawesi Tengah | [antaranews.com](https://sulteng.antaranews.com/berita/177984/pakar-gizi-ingatkan-perlunya-gizi-seimbang-pada-penderita-anemia) |
| `minum-air-makan.jpg` | Kenapa Harus Minum Air Putih Setelah Makan? | Cleopure Water | [cleopurewater.com](https://cleopurewater.com/blog/kesehatan/kenapa-harus-minum-air-putih-setelah-makan/) |
| `aktivitas-lari.jpg` | Hari Lari Sedunia 7 Juni, Yuk Simak Manfaat Berlari | detikcom | [news.detik.com](https://news.detik.com/berita/d-6759293/hari-lari-sedunia-7-juni-yuk-simak-manfaat-berlari) |
| `aktivitas-yoga.jpg` | Jenis-jenis Yoga yang Baik bagi Tubuh | KlikDokter | [klikdokter.com](https://www.klikdokter.com/gaya-hidup/sehat-bugar/jenis-jenis-yoga-yang-baik-bagi-tubuh) |
| `mental-hero.jpg` | 4 Gangguan Mental yang Terjadi Tanpa Disadari | Halodoc | [halodoc.com](https://www.halodoc.com/artikel/4-gangguan-mental-yang-terjadi-tanpa-disadari) |
| `pencegahan-hero.jpg` | Cuci Tangan Pakai Sabun: Kebiasaan Sederhana untuk Mencegah Penyebaran Penyakit | Farmasi UMMADA | [farmasi.ummada.ac.id](https://farmasi.ummada.ac.id/2026/08/10/cuci-tangan-pakai-sabun-kebiasaan-sederhana-untuk-mencegah-penyebaran-penyakit/) |
| `pencegahan-tensi.jpg` | Berapa Tekanan Darah Normal Orang Dewasa? | Alodokter | [alodokter.com](https://www.alodokter.com/berapa-tekanan-darah-normal-orang-dewasa) |

Gambar hanya disesuaikan **ukuran dan kompresinya** (maksimal 1400 px, kualitas 85); isi
foto tidak diubah atau diedit ulang. Kredit dicantumkan sebagai bentuk kejujuran akademik
dan agar sumbernya dapat diverifikasi.

### 8.3 Aset lain

| Aset | Sumber | Lisensi |
|---|---|---|
| Font **Plus Jakarta Sans** | [Google Fonts](https://fonts.google.com/specimen/Plus+Jakarta+Sans) | SIL Open Font License 1.1 |
| Ikon navigasi & antarmuka | Dibuat sendiri sebagai SVG inline | Ikut lisensi proyek ini |
| `favicon.svg` | Dibuat sendiri (SVG manual) | Ikut lisensi proyek ini |

---

## Catatan Tambahan

**Hasil validasi:** seluruh 7 halaman lolos **Nu HTML Checker** (`vnu.jar` — engine yang
sama dengan validator.w3.org) dengan **0 error**, dan `css/style.css` lolos **W3C CSS
Validator** dengan **0 error**.

**Situs ini bersifat edukatif** untuk masyarakat umum dan **bukan pengganti konsultasi
medis**. Untuk keluhan kesehatan, hubungi fasilitas kesehatan terdekat. Layanan konseling
kesehatan jiwa Kementerian Kesehatan RI: **119 ekstensi 8**.