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
* <body> disebut tag body (atau tag pembuka body), <h1> adalah tag h1 dan `<p>` adalah tag p atau paragraf
* <h1>Selamat datang</h1> disebut elemen h1
* <p>Selamat belajar pemrograman web di <b>mhaziqrk</b></p> disebut elemen p atau paragraf
* <b>mhaziqrk</b> disebut elemen b atau bold, <b> itu sendiri disebut tag b atau bold
* semua bagian mulai dari tag pembuka body, berikut subelemen diantara tag pembuka dan penutup body, hingga tag tutup body disebut dengan elemen body.

**Catatan** : Penulisan elemen harus lengkap, mulai dari tag pembuka, konten dan tag penutup. Apa yang sudah dibuka wajib ditutup kembali!



[Kembali Ke atas](#belajar-html5)

