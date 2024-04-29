# Percobaan 2 to
## Kode css
      button {widht:150px;
              height:50px;
              margin-top:50px;
              padding-left:20px;
              background-color:#7949ff;
              color:white;
              font-family:arial;
              border-radius:5px;
              }


## Font size
### before

![[IMG-20240219-WA0009 1.jpg]]

### After

![[IMG-20240219-WA0008 1.jpg]]

## Color

![[IMG-20240219-WA0010 1.jpg]]

## Border

# Anatomi CSS
![gmbar](anatomi_css.jpg)

# Percobaan Pertama CSS
### Kode program

```css
    
    p {
      color: red;
      
}
```
### Hasil
![gmbar](IMG_20240304_094823.jpg)
### Penjelasan
Deklarasi gaya CSS { color: red; } menetapkan properti color ke nilai "red", sehingga teks dalam elemen paragraf akan ditampilkan dengan warna merah.

___
# Percobaan Kedua CSS
## Kode Css
```CSS
button{width: 150px; height: 50px; 
   font-size: 100px;
   Background-color:red;
   color:blue;}
```
## Font size
```CSS
button{font-size : 100px;}
```
### Hasil
![gambar](IMG_20240219_121110.jpg)

### Penjelasan
button { font-size: 100px; } adalah aturan CSS yang menentukan gaya untuk semua elemen <`button`> dalam dokumen HTML
**Button**: Ini adalah selector yang menargetkan semua elemen <`button`> dalam dokumen HTML.
**font-size :100px;** :Ini adalah deklarasi gaya yang terkait dengan selector tersebut. Di sini, kita menetapkan properti font-size dengan nilai 100px, yang berarti teks di dalam elemen <`button`> akan ditampilkan dengan ukuran font sebesar 100 piksel.
___
## Background Color
```CSS
button{background-color: red;}
```
### Hasil
![gambar](IMG_20240219_121048.jpg)
### Penjelasan
Kode program button{background-color: red;} merupakan aturan CSS yang menetapkan warna latar belakang (background-color) menjadi merah untuk semua elemen <`button`> dalam dokumen HTML yang terhubung dengan stylesheet tersebut. Ini berarti semua tombol dalam dokumen HTML akan memiliki latar belakang merah ketika aturan CSS ini diterapkan
____
## Font Color
```CSS
button{color:blue;}
```
### Hasil
![gambar](IMG_20240219_121042 2.jpg)
![gambar](IMG_20240219_121100.jpg)
### Penjelasan
Kode program CSS tersebut adalah aturan CSS yang mendefinisikan styling untuk elemen-elemen yang menggunakan tag <`button`>. Dalam aturan tersebut, warna teks (color) diatur menjadi biru (blue).
____
# Cara Pemanggilan di CSS
___
## Pemanggilan Secara Internal
 Ini melibatkan penempatan kode CSS di dalam tag `style` di dalam elemen `head` dari dokumen HTML. 
 Contohnya:
 ```CSS
 <head>
    <style>
        p {
            color: blue;
        }
    </style>
</head>
<body>
    <p>Ini adalah teks biru</p>
</body>

```
## Pemanggilan Secara Eksternal
External CSS: Ini melibatkan penempatan kode CSS dalam file terpisah dengan ekstensi .css, yang kemudian dipanggil dalam elemen `link` di dalam elemen `head` dari dokumen HTML. Contohnya:
```Css
<head>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
```
Isi Dari File Style.Css:
```css
p{color:red;}
```
## Pemanggilan Secara Inline
Ini adalah metode untuk menambahkan gaya langsung ke elemen HTML menggunakan atribut style. Contohnya: 
```css
<p style="color: red;">Ini adalah teks merah</p>.
```
# Selector
## Selector ID
Selector ID: Untuk memilih elemen dengan ID tertentu, gunakan tanda pagar (#) diikuti dengan nama ID sebagai selector. Contohnya:

```css
#judul {
    font-size: 24px;
}
```
`#judul`Ini akan menerapkan gaya pada elemen dengan ID judul.
## Selector Class
Selector Class: Untuk memilih elemen dengan class tertentu, gunakan titik (.) diikuti dengan nama class sebagai selector. Contohnya:

```css
.teks-merah {
    color: red;
}
```
Ini akan menerapkan gaya pada semua elemen dengan class teks-merah.
## Selector Elemen
Selector Elemen: Untuk memilih semua elemen dengan tag tertentu, gunakan nama tag sebagai selector. Contohnya:
```css

p {
    color: red;
}
```
Ini akan menerapkan gaya pada semua elemen `<p>` dalam dokumen HTML.

---
# Materi Text
___
## Text-Align
### Penjelasan
Kode CSS p {text-align: right;} digunakan untuk mengatur tata letak teks dalam elemen paragraf (p) di halaman web. Dalam konteks ini, text-align: right; mengarahkan teks di dalam elemen paragraf untuk diposisikan ke kanan dari kotak yang memuatnya, sehingga teks tersebut akan rata kanan.
### Kode program
```css
p{Text-Align:right;}
```
### Hasil
![[Screenshot_2024-03-04-12-05-31-55_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
text-align merupakan property untuk membuat teks pada tampilan browser menjadi kekanan (text-align:right;),kekiri (Text-Align:left;), ke tengah(Text-Align:center;), dan rata kanan kiri(Text-Align:justify;)
___
## Text-decoration
### Penjelasan
Kode CSS p {text-decoration: underline;} digunakan untuk memberikan dekorasi garis bawah pada teks dalam elemen paragraf (p) di halaman web. Dengan demikian, semua teks di dalam elemen paragraf akan memiliki garis bawah.
### Kode program
```css
p{Text-decoration:underline;}
```
### Hasil
![[Screenshot_2024-03-04-12-06-56-40_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
Kesimpulannya, kode CSS `p {text-decoration: underline;}` digunakan untuk memberikan dekorasi garis bawah pada teks dalam elemen paragraf (`<p>`) di halaman web.
___
## Text-Tranform
### Penjelasan
Kode CSS p {text-transform: lowercase;} digunakan untuk mengubah semua teks dalam elemen paragraf (p) menjadi huruf kecil (lowercase). Ini berarti semua huruf dalam teks akan ditampilkan dalam bentuk huruf kecil.
### Kode program
```css
p{text-transform:lowercase;}
```
### Hasil
![[Screenshot_2024-03-04-12-15-37-22_e3c1f266f17b29c7b40472751f031275 1.jpg]]
### Kesimpulan
Kesimpulannya, kode {text-transform:lowercase;} ini akan membuat semua teks di dalam elemen paragraf menjadi huruf kecil.
___
## Text-indent
### Penjelasan
text-indent: Ini adalah properti CSS yang mengatur jarak indentasi awal dari teks dalam sebuah elemen.
50px: Ini adalah nilai indentasi yang diberikan dalam piksel. Dalam kasus ini, teks dalam semua elemen paragraf akan di-indentasi sejauh 50 piksel dari sisi kiri.
### Kode program
```css
p{Text-indent:50px;}
```
### Hasil
![[Screenshot_2024-03-04-12-16-26-48_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
Kesimpulannya, kode tersebut mengatur indentasi awal teks dalam semua elemen paragraf sejauh 50 piksel dari sisi kiri.
___
## Letter-spacing
### Penjelasan
{Letter-spacing: 20px;} mengatur jarak antara baris dalam elemen paragraf (p) menjadi 20 piksel. Ini berarti setiap baris teks dalam elemen paragraf akan memiliki jarak horizontal sebesar 20 piksel.
### Kode program
```css
p{letter-spacing:20px}
```
### Hasil
![[Screenshot_2024-03-04-12-18-49-36_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
Kesimpulannya, kode CSS ini akan membuat jarak antara baris dalam elemen paragraf menjadi 20 piksel, menciptakan ruang horizontal yang lebih besar di antara setiap baris teks.
___
## Line-height
### Penjelasan
line-height: Ini adalah properti CSS yang mengatur tinggi baris di dalam elemen. Di sini, nilainya adalah 50px, yang berarti jarak antara baris dalam paragraf akan setara dengan 50 piksel.
### Kode program

```css
P{Line-height:50px;}
```
### Hasil
![[Screenshot_2024-03-04-12-19-53-50_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
kode Line-height:20px; mengatur tinggi baris untuk semua elemen paragraf menjadi 20 piksel.
___
## Word-Spacing
### Penjelasan
word-spacing: Ini adalah properti CSS yang mengatur jarak antara kata-kata di dalam elemen. Di sini, nilainya adalah 50px, yang berarti jarak antara kata-kata dalam paragraf akan setara dengan 50 piksel.
### Kode program
```css
P{Word-Spacing:50px;}

```
### Hasil
![[Screenshot_2024-03-04-12-20-18-13_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
kode Word-spacing:50px; mengatur jarak antara kata-kata di dalam semua elemen paragraf menjadi 50 piksel.
___
# Materi Background
___
## Background-Size
### Penjelasan
background-size: 200px;: Properti ini mengatur ukuran latar belakang. Di sini, latar belakang akan memiliki lebar 200 piksel, dengan tinggi yang disesuaikan agar proporsi aslinya tetap terjaga.
### Kode program
```css
P{background-size:200px;}
```
### Hasil
![[Screenshot_2024-03-04-13-15-10-32_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
Kode property tersebut bertujuan mengatur ukuran gambar latar belakang dengan size pixel.
___
## Background-Repeat
### Penjelasan
background-repeat: no-repeat;Properti ini menentukan apakah gambar latar belakang akan diulang atau tidak. Dalam kasus ini, gambar latar belakang tidak akan diulang.

### Kode program
```css
P{background-repeat:no-repeat;}
```
### Hasil
![[Screenshot_2024-03-04-12-30-21-41_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
Kode property tersebut berguna agar gambar tidak akan ber ulang Dengan menggunakan value (no-repeat)
___
## Background-attachment
### Penjelasan
background-attachment: fixed; Properti ini menentukan apakah latar belakang akan tetap diam atau akan bergulir bersama dengan isi elemen saat pengguna menggulir halaman. Dalam kasus ini, latar belakang akan tetap diam, artinya posisinya akan tetap konstan saat halaman digulir.
### Kode program
```css
p{background-attachment:fixed;}
```
### Hasil
![[Screenshot_2024-03-04-13-15-10-32_e3c1f266f17b29c7b40472751f031275 1.jpg]]
### Kesimpulan
Kode property tersebut akan mengatasi gambar yang bergulir akan diam dengan menggunakan value (fixed)
___
## Background-position
### Penjelasan
background-position: top; Properti ini mengatur posisi latar belakang di dalam elemen. Di sini, latar belakang akan diposisikan di bagian atas elemen.
### Kode program
```css
p
{Background-position:top;}
```
### Hasil
![[Screenshot_2024-03-04-12-41-48-46_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
Kode property tersebut akan menentukan posisi gambar latar belakang ke atas (top).
___
## Background-image
### Penjelasan
background-image: url(gambar/wallpaper.jpg); Properti ini menentukan gambar apa yang akan digunakan sebagai latar belakang. Di sini, gambar dengan nama file "walpaper.jpg" akan digunakan.
### Kode program
```css
p
{Background-image:url(gambar/walpaper.jpg);}
```
### Hasil
![[Screenshot_2024-03-04-12-36-19-54_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
Kode property tersebut akan menentukan gambar Apa yang digunakan untuk latar-belakang.
___
# Materi Font
___
## Font-Weight
### Penjelasan
Font-weight: bold; adalah properti CSS yang digunakan untuk mengatur ketebalan teks. Dalam hal ini, nilai yang diberikan adalah "bold", yang membuat teks yang menggunakan properti ini untuk diatur dengan ketebalan yang lebih besar dari teks biasa.
### Kode program
```css
p{Font-Weight:bold;}
```
### Hasil
![[Screenshot_2024-03-04-13-30-15-73_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
Properti CSS ini digunakan untuk mengatur ketebalan teks. Dalam hal ini, nilai yang diberikan adalah "bold".
___
## Font-Size
### Penjelasan
Font-size: 50px; adalah properti CSS yang digunakan untuk mengatur ukuran font menjadi 50 piksel. Ini berarti teks yang diberikan akan ditampilkan dengan ukuran 50 piksel, membuatnya lebih besar dari ukuran font standar yang biasa digunakan dalam tata letak halaman web
### Kode program
```Css
P{Font-Size:50px;}
```
### Hasil
![[Screenshot_2024-03-04-13-33-41-41_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
Kode property bertujuan agar teks membuatnya lebih besar dari ukuran font standar yang biasa digunakan dalam tata letak halaman web.
___
## Font-Style
### Penjelasan
Font-style: italic; adalah properti CSS yang digunakan untuk mengatur gaya teks menjadi miring (italic). Ini berarti teks yang diberikan akan miring, seperti yang sering kita lihat dalam gaya teks untuk menekankan kata-kata atau membuat teks menonjol.
### Kode program
```css
p{Font-Style:italic;}
```
### Hasil
![[Screenshot_2024-03-04-13-34-49-67_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
Kode properti yang bertujuan untuk mengatur gaya teks yang dalam kasus ini menjadi miring (italic).
___
## Font-family
### Penjelasan
Font-family: Times New Roman; adalah properti CSS yang digunakan untuk menentukan jenis font yang akan digunakan untuk menampilkan teks. Dalam hal ini, jenis font yang dipilih adalah "Times New Roman." Ini akan mengubah teks yang menggunakan properti ini untuk diatur dengan gaya huruf yang khas dari jenis font Times New Roman, yang sering kali terlihat formal dan terstruktur.
### Kode program
```css
P{Font-family:Times-New-Roman;}
```
### Hasil
![[Screenshot_2024-03-04-13-31-32-29_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
Kode properti ini digunakan untuk menetapkan jenis font yang akan digunakan untuk menampilkan teks, di mana dalam kasus ini, jenis font yang dipilih adalah Times New Roman.
___
# Box Model
___
# Materi Border
## Border-Radius
### Penjelasan
### Kode program
```css
Button{border-radius:10px;}
```
### Hasil
![[Screenshot_2024-03-06-00-05-15-21_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan

___
## Border-color
### Penjelasan
### Kode program
```css
Button{Border-color:green;}
```
### Hasil
![[Screenshot_2024-03-06-00-08-10-00_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan

___
## Border-style
### Penjelasan
### Kode program
```css
Button{Border-style:dashed;}
```
### Hasil
![[Screenshot_2024-03-06-00-09-24-39_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan

___
## Border-width
### Penjelasan
### Kode program
```css
Button{border-width:20px;}
```
### Hasil
![[Screenshot_2024-03-06-00-09-48-67_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan
___
# Materi Height & width
___
## Height
### Penjelasan
### Kode program
```css
Button{height:100px;}
```
### Hasil
![[Screenshot_2024-03-06-00-16-38-78_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan

## Width
### Penjelasan
### Kode program
```css
Button{width:100px;}
```
### Hasil
![[Screenshot_2024-03-06-00-17-00-39_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan

___
# Materi Padding
___
## Padding-top
### Penjelasan
### Kode program
```css
Button{Padding-top:100px;}
```
### Hasil
![[Screenshot_2024-03-06-00-12-35-48_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan

___
## Padding-bottom
### Penjelasan
### Kode program
```css
Button{Padding-bottom:100px;}
```
### Hasil
![[Screenshot_2024-03-06-00-12-53-20_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan

___
## Padding-left
### Penjelasan
### Kode program
```css
Button{padding-left:100px;}
```
### Hasil
![[Screenshot_2024-03-06-00-13-24-68_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan

___
## Padding-right
### Penjelasan
### Kode program
```css
Button{padding-right:100px;}
```
### Hasil
![[Screenshot_2024-03-06-00-13-08-22_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan

___
# Materi Margin
___
## Margin-top
### Penjelasan
### Kode program
```css
Button{Margin-top:100px;}
```
### Hasil
![[Screenshot_2024-03-05-23-51-52-32_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan

___

## Margin-bottom
### Penjelasan
### Kode program
```css
Button{Margin-bottom:100px;}
```
### Hasil
![[Screenshot_2024-03-05-23-55-49-15_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan

___
## Margin-left
### Penjelasan
### Kode program
```css
Button{Margin-left:100px;}
```
### Hasil
![[Screenshot_2024-03-05-23-57-31-84_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan

___
## Margin-right
### Penjelasan
### Kode program
```css
Button{Margin-right:100px;}
```
### Hasil
![[Screenshot_2024-03-05-23-57-48-39_e3c1f266f17b29c7b40472751f031275.jpg]]
### Kesimpulan

___
# Transition
## Transition-delay
## Transition-Duration
## Transition-Property
## Transition-Timing-function
# Transfrom
## Transform-Scale
## Transform-ScaleX
## Transform-Rotate
## Transform-Skew
## Transform-SkewX
## Transform-Translate
## Transform-Matrix
# Flexbox
## display flex
## flex-direction
## align items
## justify-content
## Tantangan
### Kode Program
### Hasil

# Pengenalan Bootstrap

## Apa Itu Bootstrap?

Bootstrap adalah salah satu dari banyak framework front-end yang ada di web development.

Framework-front end menyediakan serangkaian alat dan gaya bawaan untuk mempercepat

proses pengembangan web dengan menyediakan komponen-komponen UI siap pakai dan

sistem grid yang responsif. Bootstrap khususnya, terkenal dengan kemampuannya dalam

menciptakan tata letak yang responsif dan komponen-komponen UI yang seragam.

Instalasi Bootstrap

Cara instalasi Bootstrap secara online / CDN.

sekarang kita akan menjelaskan bagaimana cara menginstall bootstrap secara online.

## Berikut langkah-langkahnya:

1. Masuklah ke website resmi Bootstrap dengan mengunjungi situs web resmi di

https://getbootstrap.com/.

2. Di laman utama web Bootstrap, cari dan klik menu "Introduction" yang terletak pada sisi

sebelah kiri website.

3. Pada bagian "Starter Template" di halaman Introduction, kita akan melihat kode yang

dapat kita gunakan untuk menghubungkan website kita yang mau diterapkan

Bootstrap.

4. Klik tombol "Copy" untuk menyalin seluruh kode tersebut.

5. Buatlah file baru dengan nama index.html atau nama yang kita inginkan menggunakan

teks editor atau editor HTML yang kita biasa pakai.

6. Tempelkan(paste) kode yang telah kita salin dari langkah sebelumnya ke dalam file

html yang baru kita buat. dengan menempelkan kode tersebut maka bootstrap kita

sudah terhubung namun harus secara online.

7. kita dapat mulai memberikan gaya pada tag-tag atau elemen dalam file HTML tersebut

dengan menggunakan kelas-kelas Bootstrap. kita dapat melihatnya pada website resmi

Bootstrap untuk mempelajari lebih lanjut tentang kelas-kelas yang tersedia dan cara

penggunaannya.

8. Untuk melihat hasilnya, buka file html tadi menggunakan web browser kita.

9. Halaman web yang ditampilkan akan menggunakan Bootstrap untuk gaya dan

fungsionalitasnya

Mengunduh dan menginstal Bootstrap secara lokal.
Untuk menginstal Bootstrap secara offline, kita perlu mengunduh file Bootstrap dan

menyimpannya di folder proyek kita. Berikut adalah langkah-langkah untuk menginstal

Bootstrap secara offline:

1. Unduh File Bootstrap: Kunjungi situs web resmi Bootstrap di https://getbootstrap.com/

dan cari tautan unduhan untuk versi Bootstrap yang diinginkan. Klik atau ikuti instruksi

untuk mengunduh file ZIP Bootstrap.

2. Ekstrak File Bootstrap: Setelah mengunduh file ZIP Bootstrap, temukan file tersebut

di komputer kita dan ekstrak isi file ZIP ke folder proyek kita. kita dapat menggunakan

aplikasi pengarsipan file atau ekstraksi bawaan (Archiver, 7zip, dll) pada sistem operasi

kita untuk mengekstrak file ZIP . Setelah diekstrak, kita akan memiliki folder Bootstrap

yang berisi berkas-berkas Bootstrap yang diperlukan.

3. Hubungkan Berkas Bootstrap pada Halaman HTML: Buka file HTML proyek kita

menggunakan teks editor atau editor HTML yang biasa kita gunakan. Di dalam tag

pada halaman HTML , tambahkan tautan ke berkas CSS Bootstrap dan skrip

JavaScript Bootstrap. Gunakan tag link di dalam tag head untuk tautan CSS dan tag

script di dalam tag body untuk javascript. Berikut contoh tautan yang umum di

bootstrap:

<link href="path/to/bootstrap.min.css" rel="stylesheet">

/ tautan bootstrap CSS

<script src="path/to/bootstrap.bundle.min.js">< script>

/ tautan bootstrap Javascript

dengan menuliskan script diatas, maka kita telah menghubungkan antara file html kita

dengan bootstrap yang kita unduh tadi.

4. Gunakan Kelas Bootstrap: Setelah tautan Bootstrap ditambahkan, Kita dapat

menggunakan kelas-kelas Bootstrap dalam elemen HTML proyek Kita untuk menerapkan

gaya dan fungsionalitas yang disediakan oleh bootstrap kita. Kita dapat masuk ke web resmi

Bootstrap untuk mempelajari lebih lanjut tentang kelas kelas yang tersedia dan cara

penggunaannya.

5. Jalankan File HTML: Setelah Kita selesai menghbungkan tautan dan menggunakan

kelas Bootstrap, Kita dapat menjalankan halaman HTML kita di web browser Kita untuk

melihat hasilnya. Buka file HTML menggunakan web browser Kita dan lihat hasilnya

Penggunaan Dasar

Struktur dasar dokumen HTML dengan Bootstrap.

Struktur dasar dokumen HTML dengan Bootstrap merupakan kerangka kerja awal yang

digunakan untuk membangun halaman web menggunakan Bootstrap. Ini termasuk tautan ke

berkas CSS Bootstrap dan skrip JavaScript (opsional, tergantung pada komponen yang

Anda gunakan), serta struktur dasar elemen HTML yang diperlukan
```
<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initialscale=1.0">

<title>Contoh Penggunaan Bootstrap< title>

< Tautan CSS Bootstrap -->

<link

href="https: stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.c

ss" rel="stylesheet">

< head>

<body>

< Isi Dokumen -->

<div class="container">

< Content di sini -->

< div>

< Skrip Bootstrap JS -->

<script

src="https: cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.m

in.js" integrity="sha384-

YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"

crossorigin="anonymous">< script>

< body>

< html>

Penggunaan Grid System Bootstrap untuk layout

responsif.

Grid System Bootstrap adalah sistem tata letak yang memungkinkan Anda untuk membuat

layout responsif dengan mudah. Dengan menggunakan kelas-kelas seperti .container ,

.row , dan .col , Anda dapat mengatur konten di halaman web Anda dengan baik, terlepas

dari ukuran perangkat pengguna.

<div class="container">

<div class="row">

<div class="col-md-4">Kolom 1< div>

<div class="col-md-4">Kolom 2< div>

<div class="col-md-4">Kolom 3< div>

< div>

< div>
```