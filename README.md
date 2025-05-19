# Proyek Artikel - Kelompok 2

Repositori ini merupakan bagian dari tugas kolaboratif pengembangan artikel menggunakan GitHub. Artikel ini mencakup empat topik utama:

1. Dasar-dasar Git dan GitHub
2. CSS Flexbox dan penggunaannya
3. CSS Grid dan penggunaannya
4. Bootstrap serta implementasinya

## Anggota:
- Muhammad Jordan (admin, integrator & Bootstrap)
- Ika Mi'rad Saputri (Git dan GitHub)
- M.Raga Al Abtad Purma (CSS Flexbox)
- Muhammad Ismail (CSS Grid)

Setiap kontributor bekerja melalui fitur branch dan pull request, lalu digabungkan oleh admin melalui proses review.

---

1. **Git**
   
   A. Jelaskan apa itu Git?
   
Git adalah sebuah jenis software dalam VCS (Version Control System) yang memiliki fungsi sebagai alat kolaborasi untuk mengelola perubahan, menyimpan riwayat perubahan file yang terdapat dalam sebuah folder (repository).

   B. Apa saja perintah dasar dalam Git?
   
Berikut adalah perintah dasar dalam Git yang paling umum digunakan:
  a) **git init**: Digunakan untuk menginisialisasi repository Git baru di dalam sebuah direktori.
  b) **git add**: Digunakan untuk menambahkan perubahan file ke dalam staging area sebelum di-commit.
  c) **git commit**: Digunakan untuk menyimpan snapshot perubahan ke dalam riwayat versioning Git.
  d) **git status**: Menampilkan informasi status file (apakah sudah di-stage, di-commit, atau belum).
  e) **git clone**: Digunakan untuk menggandakan repository dari server (remote) ke komputer lokal.
  f) **git push**: Mengirim commit dari repository lokal ke repository remote.
  g) **git pull**: Mengambil dan menggabungkan perubahan terbaru dari repository remote ke lokal.
  h) **git branch**: Digunakan untuk melihat, membuat, atau menghapus branch.
  i) **git config**: Digunakan untuk mengatur konfigurasi Git seperti username dan email.
  j) **git merge**: Menggabungkan perubahan dari satu branch ke branch aktif.
  k) **git stash**: Menyimpan sementara perubahan yang belum siap di-commit, agar bisa berpindah branch tanpa kehilangan pekerjaan.    
  
   C. Apa fungsi dari Git?
   
 Git mempunyai beberapa fungsi diantaranya sebagai berikut:
  1. **Digunakan untuk kolaborasi**
     Git bisa digunakan untuk kolaborasi dengan banyak orang untuk mengerjakan proyek yang sama
  2.**Membantu mengorganisir**
     Git dapat menyimpan folder projek secara optimal
  3. **Proyek open source**
     Git adalah sebuah tools yang bersifat open source, dimana dapat dipakai dalam membuat software secara open source
  4. **Sebagai platform fleksibilitas**
     Git menjadi platform yang dleksibilitas karena bisa digunakan sebagai solusi untuk hosting di berbagai macam proyek
  5. **Menjadi backup**
     Git dapat menjadi backup karena git bisa melakukan restore script program untuk mengembalikan kembali ke versi sebelumnya

2. **Github**
   
   A. Jelaskan apa itu Github?
   
Github adalah sebuah platform berbasis web atau platform pengembangan software online yang berbasis cloud yang dapat digunakan untuk menyimpan, melacak, dan juga sebagai tempat kolaborasi dalam sebuah proyek

   B. Apa saja perintah dasar dalam Github?
   
Berikut adalah beberapa perintah dasar yang umum dalam menggunakan:
  a) **Repository**: Tempat penyimpanan kode dan file proyek
  b) **Branch**: Cabang dari repository utama untuk mengembangkan fitur baru tanpa memengaruhi kode utama
  c) **Commit**: Merekam setiap perubahan yang dilakukan dalam repository
  d) **Push**: Untuk mengirim commit dari lokal ke repository Github (remote)
  e) **Pull**: Untuk mengambil dan menggabungkan setiap perubahan terbaru dari repository Github ke lokal
  f) **Pull** Request: Sebuah permintaan untuk menggabungkan perubahan dari satu branch ke branch lain
  g) **Fork**: Untuk menyalin repository orang lain ke akun kita agar mudah dimodifikasi secara bebas
  h) **Issues**: Digunakan untuk melaporkan bug, request fitur dan untuk diskusi dalam menggerjakan sebuah proyek
  i) **README.md**: Sebuah file dokumentasi utama dalam repository Github yang menjelaskan isi, cara penggunaan, dan informasi penting proyek
  
   C. Apa fungsi dari Github?

Github mempunyai beberapa fungsi diantaranya sebagai berikut:
  1. **meningkatkan kolaborasi secara tim**
     Github menyediakan sebuah ruang agar memudahkan seorang developer melakukan kontribusi dalam suatu proyek
  2. **Memudahkan memanejemen file**
     Github memudahkan seorang develpoer dalam mengatur file, hal ini karena Github sudah berbasis cloud sehingga pengguna bisa dengan mudah mengakses repository, mengunduh dan melakukan pengeditan dari lokasi dan perangkat yang berbeda
  3. **Mencegah perubahan kode yang justru dapat merusak kode asli**
     Github memiliki fitur branch dimana ketika kita melakukan perubahan kode pada branch itu tidak akan merubah atau merusak isi pada kode utama
  5. **Bisa menjadi portofolio bagi seorang developer**
     Github membantu seorang developer untuk menghasilkan portofolio yang bisa menjadi daya tarik bagi klien atau perusahaan dalam melamar pekerjaan

---
🎯 Materi CSS Grid
1. Apa itu CSS Grid?
CSS Grid adalah sistem layout berbasis grid dua dimensi (baris dan kolom) yang memungkinkan kita untuk menyusun elemen HTML dalam layout yang kompleks dan responsif dengan lebih mudah.
2. Terminologi Dasar

   
| Istilah        | Penjelasan                                      |
| -------------- | ----------------------------------------------- |
| Grid Container | Elemen induk yang menggunakan `display: grid`   |
| Grid Item      | Elemen anak dari grid container                 |
| Grid Line      | Garis vertikal dan horizontal yang membagi grid |
| Grid Track     | Baris atau kolom antara dua grid line           |
| Grid Cell      | Ruang antara dua baris dan dua kolom            |
| Grid Area      | Beberapa grid cell yang membentuk area tertentu |

3. Properti Utama Grid Container
   
| Properti                               | Fungsi                            |
| -------------------------------------- | --------------------------------- |
| `grid-column-start`, `grid-column-end` | Posisi mulai dan akhir kolom      |
| `grid-row-start`, `grid-row-end`       | Posisi mulai dan akhir baris      |
| `grid-area`                            | Menentukan area khusus untuk item |
| `justify-self`, `align-self`           | Posisi item secara individual     |

4. Properti pada Grid Item


| Properti                           | Fungsi                              |
| ---------------------------------- | ----------------------------------- |
| `display: grid`                    | Mengaktifkan CSS Grid               |
| `grid-template-columns`            | Menentukan jumlah dan ukuran kolom  |
| `grid-template-rows`               | Menentukan jumlah dan ukuran baris  |
| `gap` atau `grid-gap`              | Jarak antar baris dan kolom         |
| `justify-items`, `align-items`     | Posisi isi tiap grid item           |
| `justify-content`, `align-content` | Posisi seluruh grid dalam container |

🔧 Kode HTML + CSS (Contoh CSS Grid)

✅ HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contoh CSS Grid</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <header>Header</header>
    <aside>Sidebar</aside>
    <main>Main Content</main>
    <footer>Footer</footer>
  </div>
</body>
</html>
```

🎨 CSS (style.css):

```/* Grid container */
.container {
  display: grid;
  grid-template-areas:
    "header  header"
    "sidebar main"
    "footer  footer";
  grid-template-columns: 200px 1fr;
  grid-template-rows: auto 1fr auto;
  gap: 10px;
  height: 100vh;
  padding: 10px;
}

/* Area styling */
header {
  grid-area: header;
  background: #4CAF50;
  color: white;
  padding: 20px;
  text-align: center;
}

aside {
  grid-area: sidebar;
  background: #f0f0f0;
  padding: 20px;
}

main {
  grid-area: main;
  background: #ddd;
  padding: 20px;
}

footer {
  grid-area: footer;
  background: #333;
  color: white;
  text-align: center;
  padding: 10px;
}
/* Grid container */
.container {
  display: grid;
  grid-template-areas:
    "header  header"
    "sidebar main"
    "footer  footer";
  grid-template-columns: 200px 1fr;
  grid-template-rows: auto 1fr auto;
  gap: 10px;
  height: 100vh;
  padding: 10px;
}

/* Area styling */
header {
  grid-area: header;
  background: #4CAF50;
  color: white;
  padding: 20px;
  text-align: center;
}

aside {
  grid-area: sidebar;
  background: #f0f0f0;
  padding: 20px;
}

main {
  grid-area: main;
  background: #ddd;
  padding: 20px;
}

footer {
  grid-area: footer;
  background: #333;
  color: white;
  text-align: center;
  padding: 10px;
}
```

🧪 Penjelasan:

display: grid                → Mengubah .container menjadi grid container
.

grid-template-areas          → Menentukan posisi elemen berdasarkan nama.

grid-area pada elemen        → Menghubungkan setiap elemen dengan area yang ditentukan.

gap                          → Jarak antar elemen.

---
🔰 Apa Itu Bootstrap?

Bootstrap adalah framework front-end open-source yang membantu developer dalam membuat tampilan website yang modern dan responsif dengan lebih cepat dan efisien.

Bootstrap menyediakan:

Komponen siap pakai (navbar, tombol, card, dll)

Grid system berbasis Flexbox

Utilitas CSS yang efisien

Responsivitas yang otomatis tanpa banyak media query manual

⚙️ Cara Menggunakan Bootstrap

1. Menggunakan CDN (Tanpa Instalasi)
<head>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>


2. Menggunakan NPM / Install Lokal
  npm install bootstrap
  Lalu import ke dalam file JS/SCSS Anda:
  
   import 'bootstrap/dist/css/bootstrap.min.css';
  
🧱 Struktur Grid Bootstrap
Bootstrap menggunakan sistem grid berbasis 12 kolom, dan dibagi ke dalam:

Container

Row

Column

🔍 Contoh Grid Responsive
```
<div class="container">
  <div class="row">
    <div class="col-md-6 bg-primary text-white p-3">Kolom Kiri</div>
    <div class="col-md-6 bg-success text-white p-3">Kolom Kanan</div>
  </div>
</div>
```
🧩 Komponen Bootstrap
1. Navbar
```
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">MySite</a>
    <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#nav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="nav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#">Beranda</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Tentang</a></li>
      </ul>
    </div>
  </div>
</nav>
```
2. Card
```
<div class="card" style="width: 18rem;">
   <img src="https://via.placeholder.com/150" class="card-img-top" alt="...">
   <div class="card-body">
    <h5 class="card-title">Judul</h5>
    <p class="card-text">Deskripsi singkat konten di dalam card.</p>
    <a href="#" class="btn btn-primary">Baca Selengkapnya</a>
  </div>
</div>
```

3. Button dan Alerts
```
<button class="btn btn-success">Sukses</button>
<div class="alert alert-warning mt-3">Ini adalah peringatan!</div>
```
🧪 Contoh Mini Project: Halaman Profil Sederhana
```<div class="container text-center my-5">
  <h1 class="mb-4">Profil Mahasiswa</h1>
  <div class="row justify-content-center">
    <div class="col-md-4">
      <div class="card shadow">
        <img src="https://via.placeholder.com/300" class="card-img-top" alt="Foto Mahasiswa">
        <div class="card-body">
          <h5 class="card-title">Muhammad Jordan</h5>
          <p class="card-text">Mahasiswa Ilmu Komputer | Universitas XYZ</p>
          <a href="#" class="btn btn-outline-primary">Hubungi Saya</a>
        </div>
      </div>
    </div>
  </div>
</div>
```
![Contoh Profile](https://github.com/corazonjordan/Proyek-Kelompok2/blob/main/Bootrstrap/Profile.png)

| Kelebihan              | Penjelasan                                |
| ---------------------- | ----------------------------------------- |
| 🚀 Cepat & Mudah       | Tak perlu styling dari nol                |
| 🔁 Responsif           | Secara otomatis menyesuaikan ukuran layar |
| 🧩 Komponen Siap Pakai | Navbar, modal, form, dll                  |
| 🎨 Konsistensi Desain  | Meminimalkan ketidaksesuaian UI           |

🚧 Kekurangan Bootstrap
1. Tampilan website bisa terlihat “mirip” dengan website lain jika tidak dikustomisasi
2. Ukuran file bisa besar jika tidak menggunakan versi kustom

✅ Kesimpulan
Boostrap adalah pilihan cerdas untuk membuat sebuah Website yang rapi,cepat namun tetap responsif. Dengan berba komponen siap pakai, framework ini sangat cocok untuk pemula maupun profesional. 

