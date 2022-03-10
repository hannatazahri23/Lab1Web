### 1. Membuat paragraf

```html
<!-- ini paragraf pertama -->
<p align="center">
    Hypertext Markup Language atau HTML adalah bahasa markup yang digunakan untuk membuat struktur halaman website. HTML terdiri dari kombinasi teks dan simbol yang disimpan dalam sebuah file. Dalam membuat file HTML, terdapat standar atau format khusus yang harus diikuti. Format tersebut telah tertuang dalam standar kode internasional atau ASCII (American Standard Code for Information Interchange). 
</p>

<!-- ini paragraf kedua -->
<p align="right">
    Dengan adanya HTML, pengguna dapat membuat atau menyusun heading, paragraf, gambar, link, dan lainnya supaya dapat dilihat banyak orang melalui halaman website. Untuk bisa diakses secara umum, pengguna perlu membukanya lewat aplikasi browser, seperti Internet Explorer, Chrome, atau Mozilla Firefox. 
</p>
```
![gambar.1](img/membuat_paragraf_HTML.JPG)
#

### 2. Membuat judul paragraf
```html
<!-- ini judul web -->
<h1>HTML</h1>

<!-- ini judul paragraf pertama -->
<h3>Apa itu HTML?</h3>

<!-- ini judul paragraf kedua -->
<h3>Apa fungsi HTML?</h3>
```
![gambar2](img/membuat_judul.JPG)
### 3. Memformat teks
```html
<!-- macam-macam tag untuk memformat teks, contohnya seperti tag "<i>" untuk memiringkan huruf, "<u>" membuat garis bawah, "<mark>" membuat garis warna dan "<b>" untuk menebalkan huruf. -->

<!-- CONTOH..!! -->
<p align="center">
    <i>Hypertext Markup Language</i> atau <b>HTML</b> adalah bahasa markup yang digunakan untuk membuat struktur halaman website. HTML terdiri dari kombinasi teks dan simbol yang disimpan dalam sebuah file. Dalam membuat file HTML, terdapat standar atau format khusus yang harus diikuti. Format tersebut telah tertuang dalam standar kode internasional atau <u>ASCII (American Standard Code for Information Interchange).</u> 
</p>

<h3>Apa fungsi HTML?</h3>

<p align="right">
    Dengan adanya HTML, pengguna dapat <mark>membuat atau menyusun heading, paragraf, gambar, link, dan lainnya supaya dapat dilihat banyak orang melalui halaman website.</mark> Untuk bisa diakses secara umum, pengguna perlu membukanya lewat aplikasi browser, seperti Internet Explorer, Chrome, atau Mozilla Firefox. 
</p>
```
![gambar3](img/memformat_teks.JPG)
#

### 4. Menyisipkan gambar
![gambar4.0](img/contohIMG.JPG)
```html
<!-- menyisipkan gambar pada web, harus sesuai dengan nama format pada folder -->
    <img src="img/LOGO_UPB_NEW-1.png" alt="Logo Universitas" width="200px">
```
![gambar4.1](img/menyisipkan_gambar.JPG)
#

### 5. Menambahkan hyperlink
```html
<!-- menambahkan hyperlink navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Halaman1</a>
    <a href="lab1_halaman2.html">Halaman2</a>
    <a href="#">My_Repository</a>
</nav>
```
![gambar5](img/menambahkan_hyperlink.JPG)
#

## Jawaban soal Pertanyaan..!!
1. Iya, karena kita salah memasuki kode inputannya sehingga membuat tag tersebut tidak dapat bekerja.
2. tag ```<p>``` digunakan untuk membuat paragraf, sedangkan tag ```<br>``` digunakan untuk membuat blocks paragraf transparan.
3. perbedaan atribut ```"title"``` dan ```"alt"``` pada tag ```<img>``` adalah, ```"title"``` berfungsi untuk memunculkan nama pada sebuah gambar ketika cursor diarahan ke gambar tersebut, sedangkan ``"alt"`` berfungsi untuk memunculkan nama pada sebuah gambar ketika gambar sedang tidak bekerja atau *error*.
4. menurut saya gunakan atribut ``"width"`` saja, karena atribut ``"width"`` digunakan untuk mengatur lebar pada ukuran gambar, secara tidak langsung ukuran itu mencakup tinggi dan lebar pada samping, sedangkan ``"height"`` hanya digunakan untuk mengatur ukuran tinggi pada gambar.