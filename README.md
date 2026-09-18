Website Sederhana

Project website sederhana menggunakan HTML, CSS, dan JavaScript dengan struktur file yang terpisah agar lebih rapi dan mudah dikembangkan.

📁 Struktur Folder
project/
├── index.html
├── css/
│   └── style.css
└── js/
    └── script.js

🛠️ Teknologi

HTML5 — struktur halaman

CSS3 — tampilan dan desain

JavaScript — interaksi dan fungsionalitas

🚀 Cara Menjalankan

Clone atau download project ini.

Buka folder project.

Jalankan file index.html menggunakan browser.

Atau jika menggunakan Visual Studio Code, kamu dapat menggunakan ekstensi Live Server:

Buka folder project di Visual Studio Code.

Klik kanan pada index.html.

Pilih Open with Live Server.

Website akan terbuka di browser.

📄 Penjelasan File
index.html

File utama yang berisi struktur halaman website.

CSS dihubungkan menggunakan:

<link rel="stylesheet" href="css/style.css">


JavaScript dihubungkan menggunakan:

<script src="js/script.js"></script>

css/style.css

Berisi kode untuk mengatur tampilan website seperti:

Warna

Font

Ukuran

Spacing

Button

Layout

Responsive design

js/script.js

Berisi kode JavaScript untuk memberikan interaksi pada website.

Contoh:

const tombol = document.getElementById("btnKlik");

tombol.addEventListener("click", function () {
    alert("Tombol berhasil diklik!");
});

🎯 Tujuan Project

Project ini dapat digunakan sebagai template dasar untuk belajar dan mengembangkan website menggunakan HTML, CSS, dan JavaScript.

📌 Pengembangan Selanjutnya

Beberapa fitur yang dapat ditambahkan:

Responsive navigation

Dark mode

Form kontak

Animasi CSS

Validasi form dengan JavaScript

Local Storage

API integration

👨‍💻 Lisensi

Project ini bebas digunakan untuk keperluan belajar dan pengembangan pribadi.
