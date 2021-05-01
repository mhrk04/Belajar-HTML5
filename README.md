# Belajar-HTML5
Belajar html mudah dengan menyalin kod dan menjalankannya. Kemudian lihat hasil di browser.

# Apa itu HTML ?

Pada tahun 1989, Tim Berners Lee dari organisasi European Organization for Nuclear Research (CERN) mencetuskan ide untuk menciptakan suatu script bahasa pemrograman pada suatu dokumen yang kemudian dikenal sebagai HTML. Tim Berners Lee diketaui sebagai penemu HTML. Saat ini penggunaan dan pengembangan HTML diatur oleh World Wide Web Consortium (W3C) dan versi terakhir dari HTML yang sekarang digunakan adalah HTML5. Versi ini memiliki fitur yang lebih baik dari versi HTML sebelumnya. HTML adalah kepanjangan dari HyperText Markup Language, merupakan bahasa interpretasi yang digunakan pada sebuah halaman web. HTML itu sendiri bukanlah sebuah bahasa pemrograman pada umumnya, seperti Java, C, C++, visual basic dan sejenisnya. HTML mendeskripsikan struktur halaman web yang ditulis dengan element atau tag yang yang mengapit konten atau teks didalamnya yang akan ditampilkan pada sebuah halaman web oleh browser. Jadi apapun website yang kita lihat pasti awalnya dibangun menggunakan HTML.

# Apa Kegunaan HTML ?

**HTML** berguna untuk menampilkan konten, menghubungkan (link) antar halaman, memberi struktur dan informasi terkait dengan sebuah halaman web. Konten sebuah web tidak hanya terbatas pada teks saja, melainkan konten interaktif lainnya seperti video, audio, gambar dan animasi dapat disisipkan dan ditampilkan pada halaman web.

Struktur dasar HTML memiliki susunan file seperti berikut ini :

```html
<html>
    <head>
        <title>Judul halaman</title>
    </head>
    <body>
        <!-- semua yang akan di tampilkan di web disimpan di dalam body -->
        <h1>Selamat datang</h1>
    </body>
</html>

```

# Struktur HTML

Struktur HTML terdiri dari 3 konsep dasar iaitu tag, elemen dan atribut.

## Tag HTML

**Tag HTML** adalah suatu penanda untuk menandai elemen-elemen dalam suatu dokumen HTML. Fungsi tag adalah untuk memberikan instruksi atau memberitahu kepada browser bagaimana suatu objek di tampilkan berdasarkan tag yang di gunakan, objek disini bisa berupa teks, video, audio dan gambar.

Tag HTML pada umumnya dibuat berpasangan, ada tag pembuka dan ada tag penutup. Tag pembuka ditulis seperti ini:

```html
<!--tag buka -->  
<nama_tag>
<!--tag penutup -->  
</nama_tag>
```
**Catatan** : Perbedaan antara tag pembuka dan tag penutup adalah tag penutup memiliki karakter garis miring sebelum nama tagnya.

## Elemen HTML
Rangkaian dari tag pembuka, konten dan tag penutup disebut dengan **elemen HTML**. Contoh berikut ini adalah elemen heading 1 dan elemen paragraf:

```html
<h1>Selamat Datang</h1>
<p>Selamat belajar pemrograman web.</p>
```
Pada contoh kode di atas, kita memiliki elemen heading 1 yang tersusun dari tag pembuka `<h1>`, konten elemen berupa teks bertuliskan Selamat Datang dan tag penutup `</h1>`. Kita juga memiliki elemen paragraf yang tersusun dari tag pembuka `<p>`, konten teks dan tag penutup `</p>`. Perbedaan dari kedua elemen ini adalah, elemen heading digunakan untuk menampilkan judul halaman, sedangkan elemen paragraf digunakan untuk menampilkan konten paragraf. Bila kita buka di browser, maka elemen heading akan dicetak lebih besar dan lebih tebal daripada elemen paragraf.

Bila kita memiliki contoh kode seperti ini:

```html
<body>
    <h1>Selamat datang</h1>
    <p>Selamat belajar pemrograman web di <b>mhaziqrk</b></p>
</body>
```
maka:

* `<body>`disebut tag body (atau tag pembuka body), `<h1>` adalah tag h1 dan `<p>` adalah tag p atau paragraf
* `<h1>Selamat datang</h1>` disebut elemen h1
* `<p>Selamat belajar pemrograman web di <b>mhaziqrk</b></p>` disebut elemen p atau paragraf
* `<b>mhaziqrk</b>` disebut elemen b atau bold, `<b>` itu sendiri disebut tag b atau bold
* semua bagian mulai dari tag pembuka body, berikut subelemen diantara tag pembuka dan penutup body, hingga tag tutup body disebut dengan elemen body.

**Catatan** : Penulisan elemen harus lengkap, mulai dari tag pembuka, konten dan tag penutup. Apa yang sudah dibuka wajib ditutup kembali!

Ada banyak tag yang dapat kita gunakan di dalam HTML untuk menampilkan konten. Bila kita bagi ke dalam dua area, maka ada tag-tag yang digunakan di dalam elemen head dan ada tag yang digunakan di dalam elemen body.

## Tag di dalam Elemen Head

Elemen yang ada di dalam head berfungsi sebagai informasi dari dokumen HTML dan tidak akan ditampilkan di layar browser. Beberapa tag yang dapat digunakan di dalam elemn head diantaranya adalah `<meta>`, `<title>`, `<style>`, `<script>` dan `<link>`.

```html
<head> 
    <meta charset="utf-8">
    <title>Judul halaman</title>
    <style> Style </style>
    <script> Javascript </script>
</head>
```
## Tag di dalam Elemen Body

Ada banyak tag yang dapat kita gunakan untuk menampilkan konten di dalam elemen body.

Ada tag yang berfungsi untuk menampilkan teks, seperti `<h1>, <h2>, <h3>, <h3>, <h4>, <h5>, <p>` dan sebagainya.

Ada juga tag untuk memformat teks, seperti `<b>`, `<i>`, `<strong>`, `<em>`, `<mark>`, `<del>` dan sebagainya.

Untuk menampilkan gambar kamu dapat menggunakan tag `<img>`, dan untuk membuat tautan kamu dapat menggunakan tag `<a>`.

Di dalam HTML, kamu dapat membuat elemen table dengan menggunakan kombinasi dari tag `<table>, <thead>, <tbody>, <tr>, <th>, dan <td>`. Kamu juga dapat membuat list dengan menggunakan kombinasi dari tag `<ul>, <ol>, <li>, <dl>, <dd>, dan <dt>`. Terkait pembuatan table dan list akan dibahas secara khusus di bagian selanjutnya.

Kamu juga dapat memasukkan video, audio atau format media lainnya menggunakan sejumlah tag seperti `<object>, <video>, <audio>, <embed>, dan <iframe>`.

Sampai pembahasan ini kamu cukup perlu paham terkait tag dan elemen. Adapun cara penggunaan tag-tag di atas akan dibahas di bagian khusus setelah ini. Bila kamu ingin tahu lebih lengkap tag HTML apa saja yang tersedia dapat dilihat di https://www.w3schools.com/tags/. Jangan terkejut bila kamu menemukan banyak tag di HTML. Kamu tak mesti menghapal semuanya, cukup pelajari tag-tag yang akan kamu gunakan saat membuat web nantinya.

## Attribut HTML

Atribut memiliki tugas khusus untuk memberikan informasi tambahan pada sebuah tag.

```html
<namatag nama-atribut="nilai-atribut"></namatag>

```
Dari contoh kode di atas yang dimaksud dengan atribut adalah tambahan yang ditulis di dalam tag pembuka. Contohnya bila kita hendak membuat tautan atau link, kamu akan perlu menulis minimal seperti ini:

```html
<a href="login.html">Login</a>
```

Pada contoh kode di atas, kita membuat tautan menggunakan tag `<a>`. Namun menggunakan tag `<a>` saja tidak cukup, karena kita perlu memberi tahu kepada browser kemana halaman akan dialihkan bila pengguna mengklik tautan Login. Oleh karena itu, tag `<a>` dilengkapi dengan atribut `href` yang harus diisi dengan nama URL tujuan dari tautan tersebut. Pada contoh di atas, href adalah nama atribut, dan "login.html" adalah nilai atribut. Nama dan nilai atribut dipisahkan dengan tanda sama dengan (=).

Selain tag `<a>` ada banyak tag lain yang memerlukan atribut. Bila dikelompokkan, ada dua jenis atribut, yakni atribut global dan atribut spesifik. Atribut global adalah atribut yang dapat diterapkan pada tag apapun karena sifatnya yang umum. Contoh atribut global diantaranya adalah `class, id, lang, title, style` dan sebagainya. Sedangkan atribut spesifik adalah atribut yang hanya berfungsi pada tag-tag tertentu, seperti atribut `href` yang hanya berlaku pada tag `<a>` dan `<link>`, atribut `src` yang hanya berlaku pada tag `<img>` dan `<script>`, dan sebagainya.

Daftar lebih lengkap atribut HTML dapat dilihat di https://www.w3schools.com/html/html_attributes.asp

[Kembali Ke atas](#belajar-html5)

