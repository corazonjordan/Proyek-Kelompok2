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
