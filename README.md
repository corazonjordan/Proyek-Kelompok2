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
