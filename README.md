# lab6_web

**Nama            : Muhamad Valentino Ramzi**

**NIM             : 312410454**

**Kelas           :  TI.24.A.5**

**Matkul          : Pemograman Web 1**

![foto](https://github.com/NadhiaShafira/Lab6Web/blob/ba39cb98851c1e0900db8753572ce89305c21ec7/assetss%20creenshots/ss1_setup_bootstrap.png.png) 

**Penjelasan**

```angkah pertama adalah menambahkan CDN Bootstrap 5 ke dalam struktur HTML dasar. Bootstrap digunakan agar tampilan lebih responsif dan mudah diatur dengan class bawaan.
Gambar di bawah menampilkan teks dan tombol Bootstrap pertama yang berhasil di-load.
```

![foto](https://github.com/NadhiaShafira/Lab6Web/blob/53871e72bb3bc2775bb53f9a4868a32bd4b3c72b/assetss%20creenshots/ss2_navbar_bootstrap.png.png)

**Penjelasan**

```Navbar dibuat menggunakan class .navbar dari Bootstrap.
Elemen ini memudahkan pengguna berpindah ke bagian halaman tertentu seperti Home, Artikel, dan Kontak.
```

![foto](https://github.com/NadhiaShafira/Lab6Web/blob/ff44bcef91613d4af5283cbf2b2a0dc44072d997/assetss%20creenshots/ss3_grid_system.png.png)

**Penjelasan**

```Bootstrap menggunakan sistem grid berbasis 12 kolom.
Class .row digunakan untuk membuat baris, dan .col untuk membagi kolom secara otomatis.
```

![foto](https://github.com/NadhiaShafira/Lab6Web/blob/3b3ee633190ba747ff1c7ce914ec5b8075112766/assetss%20creenshots/ss4_layout_main_sidebar.png.png)

**Penjelasan**

```Layout ini menggunakan .col-md-8 dan .col-md-4, menandakan pembagian 8:4 dari total 12 kolom grid Bootstrap.
Bagian kiri digunakan untuk konten utama, sedangkan bagian kanan untuk sidebar.
```

![foto](https://github.com/NadhiaShafira/Lab6Web/blob/2291ed07c7fb0f0dcab78d89ea2b95a7df6fd290/assetss%20creenshots/ss5_card_component.png.png)

**Penjelasan**

```Komponen card digunakan untuk menampilkan informasi singkat seperti artikel, produk, atau portfolio.
Bootstrap sudah menyediakan class .card, .card-body, dan .card-title agar tampilannya seragam.
```
![foto](https://github.com/NadhiaShafira/Lab6Web/blob/8dd8c67ea82d4450a3ec41a54cb6d3999a094eb9/assetss%20creenshots/ss6_form_kontak.png.png)

**Penjelasan**

```Bagian kontak berfungsi untuk menerima masukan dari pengunjung.
Form dibuat menggunakan class .form-control agar tampilan input terlihat seragam dan rapi.
```

![foto](https://github.com/NadhiaShafira/Lab6Web/blob/39ac79eb96ef12b8c55d8eace6ffc541166ffc65/assetss%20creenshots/ss7_footer.png.png) 

**Penjelasan**

```Footer berisi identitas pembuat halaman serta tahun pembuatan.
Menggunakan class .bg-dark dan .text-white agar tampil kontras dengan halaman utama.
```

**PORTOFOLIO**

![foto](https://github.com/NadhiaShafira/Lab6Web/blob/e5a1392bec1e40f8a31bc12800395ed6ca12af28/assetss%20creenshots/portofolio.png) 

**Penjelasan**

```
Langkah 1 – Struktur Dasar HTML & Import Bootstrap

Langkah pertama adalah membuat struktur dasar HTML dan menautkan CDN Bootstrap 5 ke dalam tag <head>.
Bootstrap digunakan agar halaman dapat memakai komponen siap pakai seperti tombol, grid, card, dan form dengan desain yang konsisten dan modern.

Langkah 2 – Navbar (Menu Navigasi)

Navbar berfungsi sebagai bagian navigasi utama pada halaman.
Bagian ini dibuat menggunakan class .navbar, .navbar-dark, dan .bg-dark dari Bootstrap agar tampil dengan latar gelap.
Menu terdiri dari tiga bagian yaitu Tentang, Portfolio, dan Kontak.
Selain itu, terdapat tombol hamburger yang muncul otomatis saat tampilan di layar kecil (mobile).

Langkah 3 – Bagian “Tentang Saya”

Bagian ini berisi foto dan deskripsi singkat tentang diri.
Layout diatur menggunakan Grid System Bootstrap (.row dan .col-md-*) agar elemen gambar dan teks tersusun rapi dan responsif.
Foto diberi class .rounded-circle supaya tampil bulat serta .shadow untuk menambahkan efek bayangan agar terlihat lebih menarik.
Bagian ini menjelaskan identitas dan minat pembuat halaman, yaitu Nadhia Shafira.

Langkah 4 – Bagian “Portfolio Saya”

Bagian ini menampilkan hasil proyek yang telah dikerjakan.
Masing-masing proyek ditampilkan menggunakan komponen Card Bootstrap dengan struktur gambar, judul, dan deskripsi.
Bootstrap secara otomatis membuat layout tiga kolom sejajar menggunakan kombinasi class .row dan .col-md-4.
Setiap card menampilkan informasi proyek yang berbeda, seperti pembuatan layout web, form kontak, dan desain halaman portfolio.

Langkah 5 – Footer / Kontak

Bagian footer terletak di bagian paling bawah halaman dan berfungsi menampilkan informasi pembuat serta tahun pembuatan halaman.
Warna latar belakang dibuat gelap menggunakan class .bg-dark dan teks diberi warna putih menggunakan .text-white.
Selain itu, footer juga menjadi bagian dengan ID kontak, yang dihubungkan dari menu navigasi bagian atas.

Langkah 6 – Script Bootstrap

Pada bagian paling bawah halaman ditambahkan link JavaScript bundle Bootstrap menggunakan CDN.
Script ini diperlukan agar fitur-fitur interaktif Bootstrap seperti navbar toggle (tombol hamburger) dapat berfungsi dengan baik.

```
