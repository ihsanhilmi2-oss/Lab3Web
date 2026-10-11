# Praktikum HTML dan CSS Eksternal

## 1. Deskripsi
Praktikum ini bertujuan untuk mempelajari penggunaan HTML dan CSS dalam pembuatan halaman web sederhana. HTML digunakan untuk membangun struktur halaman, sedangkan CSS digunakan untuk mengatur tampilan, warna, jarak, dan desain elemen halaman web.

## 2. Tujuan Praktikum
- Memahami struktur dasar HTML.
- Memahami cara menghubungkan CSS eksternal dengan HTML.
- Mempelajari penggunaan CSS Selector, ID Selector, dan Class Selector.
- Mengatur tampilan navigasi, bagian konten, dan tombol menggunakan CSS.

## 3. Struktur File
File yang digunakan dalam praktikum ini adalah:

```text
project/
├── lab2_css_eksternal.html
├── style_eksternal.css
└── README.md
```

## 4. Penjelasan File

### A. lab2_css_eksternal.html
File HTML berfungsi untuk membuat struktur halaman web, meliputi:
- Header dengan judul CSS Internal dan Inline CSS.
- Navigasi untuk berpindah ke halaman lain.
- Bagian konten dengan judul Hello World.
- Paragraf informasi mengenai pembelajaran HTML dan CSS.
- Tombol Informasi selengkapnya.

HTML juga menggunakan CSS internal untuk mengatur jenis huruf, ukuran judul, warna teks, dan garis bawah header.

### B. style_eksternal.css
File CSS eksternal digunakan untuk mengatur tampilan halaman web, meliputi:

- **Navigation (`nav`)**: Mengatur warna latar belakang hijau, warna teks, dan jarak navigasi.
- **Navigation Link (`nav a`)**: Mengatur warna tautan, menghilangkan garis bawah, dan memberikan jarak.
- **Hover**: Mengubah warna latar belakang tautan ketika kursor diarahkan ke tautan.
- **ID Selector (`#intro`)**: Mengatur latar belakang biru, border, tinggi minimum, dan padding pada bagian konten.
- **ID Selector (`#intro h1`)**: Mengatur judul di dalam konten agar rata kiri dan berwarna putih.
- **Class Selector (`.button`)**: Mengatur tampilan tombol, padding, margin, dan warna teks.
- **Class Selector (`.btn-primary`)**: Memberikan warna latar belakang merah pada tombol utama.

## 5. Cara Menghubungkan CSS Eksternal
CSS eksternal dihubungkan dengan HTML menggunakan tag `<link>` di dalam bagian `<head>`.

```html
<link rel="stylesheet" href="style_eksternal.css">
```

Nama file pada atribut `href` harus sesuai dengan nama file CSS yang digunakan.

## 6. Langkah Menjalankan Program
1. Buka folder project menggunakan Visual Studio Code.
2. Pastikan file HTML dan CSS berada dalam folder yang sama.
3. Simpan seluruh file.
4. Buka file `lab2_css_eksternal.html` menggunakan browser.
5. Amati hasil tampilan halaman web.

## 7. Hasil Praktikum
Halaman web menampilkan navigasi berwarna hijau, bagian konten dengan latar belakang biru, serta tombol berwarna merah. Tampilan tersebut menunjukkan bahwa CSS eksternal berhasil diterapkan pada elemen HTML.

## 8. Kesimpulan
Berdasarkan praktikum ini, HTML dan CSS memiliki fungsi yang saling melengkapi dalam pembuatan halaman web. HTML digunakan untuk menyusun struktur halaman, sedangkan CSS digunakan untuk memperindah tampilannya. Penggunaan CSS eksternal memudahkan pengelolaan desain karena aturan tampilan dapat ditulis secara terpisah dari dokumen HTML.