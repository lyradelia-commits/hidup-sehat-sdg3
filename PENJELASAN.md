# Penjelasan Singkat untuk Presentasi

Dokumen ini menjelaskan isi website dan alasan teknis di baliknya. Dipakai kalau
dosen bertanya "kenapa dibuat begini" saat presentasi.

---

## 1. Kenapa ada 7 halaman, bukan 5?

Ketentuan minimal 5 halaman. Saya buat 7 karena tema SDG 3 punya lima sub-materi
(pola hidup sehat, gizi, aktivitas fisik, kesehatan mental, pencegahan penyakit),
lalu ditambah **beranda** dan **halaman sumber**. Halaman sumber penting karena
tugas meminta sumber gambar dicantumkan, dan lebih rapi kalau dikumpulkan di satu
tempat, bukan hanya di caption.

## 2. Bagaimana CSS-nya disusun?

Satu file: `css/style.css`, dihubungkan dari semua halaman lewat:

```html
<link rel="stylesheet" href="css/style.css">
```

File CSS dibagi menjadi 20 bagian bernomor dengan komentar, urutannya:

1. **Variabel warna** (`:root`) — semua warna dan radius disimpan sebagai variabel
   supaya kalau mau ganti tema hijau, cukup ubah satu blok, tidak perlu mencari
   satu per satu di seluruh file.
2. **Reset ringan** — `box-sizing: border-box` supaya `padding` tidak menambah
   lebar elemen (penyebab klasik layout jebol).
3. **Utilitas** — `.container`, `.bagian`, `.eyebrow`, `.sr-only`.
4. **Header & navigasi** — `position: sticky` supaya menu tetap terlihat saat
   di-scroll.
5. **Hero**, **tombol**, **kartu**, **statistik**, **tabel**, **accordion**,
   **footer**, **kepala halaman**.
6. **Media query** — bagian 18.
7. **Aksesibilitas & cetak** — `prefers-reduced-motion` dan `@media print`.

## 3. Bagaimana cara membuatnya responsive tanpa framework?

Tiga teknik, semuanya CSS murni:

**a. Grid otomatis dengan `auto-fit` + `minmax`**

```css
.grid-3 { grid-template-columns: repeat(auto-fit, minmax(255px, 1fr)); }
```

Artinya: isi sebanyak mungkin kolom, tapi tiap kolom minimal 255 px. Kalau layar
tidak cukup, jumlah kolom otomatis berkurang. Tidak perlu menulis media query
untuk setiap jumlah kolom.

**b. Ukuran huruf yang menyesuaikan layar dengan `clamp()`**

```css
h1 { font-size: clamp(2rem, 1.35rem + 3.2vw, 3.5rem); }
```

`clamp(minimal, ideal, maksimal)` — di ponsel jadi 2rem, di desktop maksimal
3.5rem, dan di antaranya mengikuti lebar layar (`vw`). Jadi tidak perlu tiga
media query terpisah hanya untuk mengatur ukuran judul.

**c. Dua breakpoint utama**

```css
@media (max-width: 1040px) { /* menu jadi lipat, kolom jadi satu */ }
@media (max-width: 560px)  { /* tabel jadi kartu, tombol selebar layar */ }
```

Breakpoint 1040 px dipilih karena pada lebar di bawah itu tujuh item menu tidak
lagi muat satu baris. Breakpoint 560 px dipilih karena di bawah lebar itu tabel
empat kolom sudah terlalu sempit untuk dibaca.

## 4. Kenapa tabel berubah jadi kartu di ponsel?

Tabel dengan empat kolom di layar 390 px akan menghasilkan teks yang sangat
sempit atau scroll horizontal. Solusinya:

```css
@media (max-width: 560px) {
  table, tbody, tr, th, td { display: block; }
  thead { display: none; }
  tbody td::before { content: attr(data-label); }
}
```

Setiap sel diubah menjadi blok, header tabel disembunyikan, lalu judul kolom
dipindahkan ke tiap sel lewat atribut `data-label`:

```html
<td data-label="Contoh">Bayam, kangkung, brokoli</td>
```

Jadi di ponsel, pembaca tetap tahu "ini kolom apa" walaupun header tabelnya
sudah hilang. Ini teknik yang sering ditanyakan dosen karena terlihat seperti
sulap, padahal hanya CSS.

## 5. Kenapa pakai JavaScript kalau tugasnya HTML + CSS?

JavaScript hanya dipakai untuk **satu hal**: tombol "Menu" di layar kecil
(`js/main.js`, 30 baris). Tanpa JS, tombol menu tidak bisa membuka apa pun.

Tapi situs tetap bisa dipakai tanpa JS, karena semua tautan juga tersedia di
footer. Jadi JS di sini hanya menambah kenyamanan, bukan syarat agar situs
berfungsi. Tidak ada framework JS sama sekali.

## 6. Bagaimana kontennya dijamin valid?

- **HTML divalidasi** dengan W3C Markup Validation Service (validator.w3.org).
  Hasil: **0 error** untuk ketujuh halaman.
- **CSS divalidasi** dengan W3C CSS Validator (jigsaw.w3.org/css-validator).
  Hasil: **valid, 0 error**. Peringatan yang muncul hanya soal CSS variables
  (tidak bisa dicek statis oleh validator) dan properti vendor seperti
  `-webkit-backdrop-filter`, yang memang bukan error.

Satu hal yang sering jadi error di validator dan sudah dihindari: **urutan
heading tidak boleh melompat**. Contoh: setelah `<h2>` langsung `<h4>` itu error.
Karena itu heading di footer memakai `<h3>`, bukan `<h4>`.

## 7. Dari mana gambar-gambarnya?

Semua foto diambil dari artikel pada situs resmi penerbitnya, bukan dari mesin
pencari gambar (Google Images). Setiap foto:

- diambil dari halaman artikel aslinya (Medistra, Fithub, Alodokter, ANTARA,
  detikcom, KlikDokter, Halodoc, Cleopure, Jurnalpost, Farmasi UMMADA),
- nama penerbit + judul artikel dicantumkan pada caption di bawah foto,
- judul lengkap, penerbit, dan tautan artikelnya tercatat di `sumber.html`
  dan `README.md`.

Gambar hanya diubah ukuran dan dikompres agar situs cepat dimuat; isi foto tidak
diedit. Kredit dicantumkan sebagai bentuk kejujuran akademik dan agar sumbernya
bisa diverifikasi.

## 8. Kalau ditanya "ini responsive atau belum, buktinya apa?"

Bukti yang bisa ditunjukkan langsung:

1. Buka situs, tekan `F12`, aktifkan mode perangkat (ikon ponsel), lalu pilih
   lebar 390 px — menu berubah jadi tombol, tabel jadi kartu.
2. Coba lebar 820 px — tata letak dua kolom berubah jadi satu kolom.
3. Coba 1280 px — menu horizontal penuh, konten dua kolom.

Selain itu sudah diuji: tidak ada scroll horizontal di ketiga lebar tersebut
(`document.documentElement.scrollWidth` tidak melebihi lebar layar).

## 9. Poin yang bisa ditonjolkan saat presentasi

- **Tema jelas dan konsisten**: hijau sebagai warna kesehatan, dengan aksen kuning
  dari logo SDG 3.
- **Konten bersumber**: setiap angka bisa dilacak ke WHO atau Kemenkes RI.
- **Aksesibilitas dasar**: ada `alt` pada semua gambar, `aria-current` pada menu
  aktif, `aria-expanded` pada tombol menu, tautan "lewati ke konten" untuk
  pengguna keyboard, dan `prefers-reduced-motion`.
- **Tanpa framework**: semua tata letak ditulis manual dengan Grid dan Flexbox.
- **Bisa diakses publik**: sudah online lewat GitHub Pages, bukan hanya `localhost`.

## 10. Kalau ditanya "bagian mana yang paling susah?"

Jawaban jujur yang kuat: **membuat tabel tetap terbaca di ponsel**. Solusi
awalnya hanya `overflow-x: auto` (tabel bisa digeser), tetapi itu masih membuat
pengguna harus menggeser ke samping. Solusi akhirnya mengubah tabel menjadi kartu
bertumpuk dengan `data-label`, sehingga tidak perlu scroll horizontal sama sekali.
