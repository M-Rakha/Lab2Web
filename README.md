# Modul Praktikum Pemrograman Web
Nama : Muhammad Rakha Ghani
Nim : 312410421
Kelas : TI.24.A3

# Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat file baru dengan nama lab2_css_dasar.html
3. Buat struktur dasar dari dokumen HTML.
4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

# 1. Membuat Dokumen HTML
Buatlah dokumen HTML seperti berikut :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/0f14802d9502c0c3c99f9e77c293b3fd0be5075f/Cuplikan%20layar%202025-09-30%20104120.png)

Selanjutnya buka pada brwoser untuk melihat hasilnya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/0f14802d9502c0c3c99f9e77c293b3fd0be5075f/Cuplikan%20layar%202025-09-30%20104142.png)

# 2. Mendeklarasikan CSS Internal
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/c5f6bf1fbf8f93a0723b260b0ae6c58559c39fd5/Cuplikan%20layar%202025-09-30%20110136.png)
![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/c5f6bf1fbf8f93a0723b260b0ae6c58559c39fd5/Cuplikan%20layar%202025-09-30%20110210.png)

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/c5f6bf1fbf8f93a0723b260b0ae6c58559c39fd5/Cuplikan%20layar%202025-09-30%20110226.png)

# 3. Menambahkan Inline CSS
Kemudian tambahkan deklarasi inline CSS pada tag p seperti berikut.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/9542da1c7f7ca3dc773c6df143996a3d9571cd71/Cuplikan%20layar%202025-09-30%20223952.png)
![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/9542da1c7f7ca3dc773c6df143996a3d9571cd71/Cuplikan%20layar%202025-09-30%20224008.png)

Simpan kembali dan refresh kembali browser untuk melihat perubahannya.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/9542da1c7f7ca3dc773c6df143996a3d9571cd71/Cuplikan%20layar%202025-09-30%20224129.png)

# 4. Membuat CSS Eksternal
Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.
Kalau internal CSS ditulis di dalam file HTML, Eksternal CSS dipisahin jadi file khusus dengan ekstensi .css. Jadi HTML sama CSS tidak bercampur, lebih mudah kalo nanti mau edit tampilan.
Bikin file baru di folder project, kasih nama style_eksternal.css 
Kemudian buat kode seperti yang ada di contoh pratikum

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/efa1dfd75127e85f51816f5a26d359c9560cbd15/Cuplikan%20layar%202025-09-30%20231724.png)

Sekarang buka file lab2_css_dasar.html tadi, Tambahin tag di dalam buat nyambungin ke file CSS eksternal

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/efa1dfd75127e85f51816f5a26d359c9560cbd15/code.png)

Tampilan hasil nya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/efa1dfd75127e85f51816f5a26d359c9560cbd15/Cuplikan%20layar%202025-09-30%20232532.png)

# 5. Menambahkan CSS Selector
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file style_eksternal.css, tambahkan kode berikut.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/52723fc9af873b28999bf536a8a13831595bb1b4/Cuplikan%20layar%202025-09-30%20233856.png)

Kemudian simpan kembali dan refresh browser untuk melihat perubahannya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/52723fc9af873b28999bf536a8a13831595bb1b4/Cuplikan%20layar%202025-09-30%20233835.png)

# Selesai, Terima Kasih.

# PERTANYAAN & TUGAS :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/96a2c8da0f79c3ea45456604e340f16227cfe6a7/Cuplikan%20layar%202025-09-30%20234555.png)

# 1. Eksperimen Properti CSS
Kita bisa mengubah atau menambahkan properti CSS biar tampilan halaman berubah.
Contohnya:

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/8f3072e713998c4be1621dbf06eeb9d587fd2535/Cuplikan%20layar%202025-10-01%20000053.png)

Hasilnya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/8f3072e713998c4be1621dbf06eeb9d587fd2535/Cuplikan%20layar%202025-10-01%20000106.png)

# 2. Perbedaan h1 {…} dengan #intro h1 {…}
h1 {…} → berlaku ke semua elemen di halaman.
#intro h1 {…} → hanya berlaku untuk yang ada di dalam elemen dengan ID intro

# 3. Prioritas CSS (Internal, Eksternal, Inline)
Contoh code :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/dea2fe6ee54c05e22ec326b2dd980bed1150e2d4/Cuplikan%20layar%202025-10-01%20001326.png)

Hasil Code :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/dea2fe6ee54c05e22ec326b2dd980bed1150e2d4/Cuplikan%20layar%202025-10-01%20001338.png)

# 4. Jika Elemen Punya ID dan Class
Kalau elemen punya ID dan Class sekaligus, ID lebih kuat daripada Class.
Contoh kode di HTML:

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/096d7809a79643090cdf8121afea4afe833a1469/Cuplikan%20layar%202025-10-01%20002705.png)

Contoh code di CSS

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab2Web/096d7809a79643090cdf8121afea4afe833a1469/Cuplikan%20layar%202025-10-01%20002807.png)

Hasil nya :



Hasil: teks merah, karena aturan ID mengalahkan Class.






