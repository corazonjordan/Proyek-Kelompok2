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


