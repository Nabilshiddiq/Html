
# Anatomi CSS
## Penjelasan
- `Selector`: Apa yang ingin di modifikasi
- `Property`: Bagian apa yang ingin dimodifikasi
- `Property value`: bentuk modifikasinya seperti apa
Contoh diatas, yang ingin di modifikasi adalah seluruh tag `<p>` pada komponen warna teksnya menjadi warna merah. 
- `p` merupakan selector yang dimana selector adalah sebuah penanda yang digunakan untuk memberikan tanda terhadap tag html yang ingin di modifikasi
- `color` merupakan property yang di mana property digunakan untuk menambahkan atau mengatur ukuran teks, jenis font, warna teks, warna background, dan sebagainya
- `red` adalah nilai dari property
**Kode**
```CSS

    p {
      color : red ; 
    }
```
**Hasil**
![gambar](asetCSS/PP.JPG)
**Penjelasan**
- `Selector`: Apa yang ingin di modifikasi
- `Property`: Bagian apa yang ingin dimodifikasi
- `Property value`: bentuk modifikasinya seperti apa
Contoh diatas, yang ingin di modifikasi adalah seluruh tag `<p>` pada komponen warna teksnya menjadi warna merah. 
Contoh lain, yang ingin dimodifikasi adalah seluruh jendela pada komponen kusennya menjadi terbuka. 
**Hasil**
![gambar](asetCSS/ACCS.JPG)

# Percobaan Pertama
## Penjelasan
- `<!DOCTYPE html>`: Mendefinisikan jenis dokumen HTML yang digunakan, dalam hal ini HTML5.
- `<html>`: Elemen utama yang memuat seluruh konten dokumen.
-  `<head>`: Bagian yang berisi informasi tambahan tentang dokumen, seperti judul dan link ke stylesheet eksternal.
- `<title>`: Menentukan judul halaman web yang akan ditampilkan di tab browser.
- `<style>`: Bagian di mana Anda dapat menambahkan aturan CSS untuk mengubah tampilan elemen HTML di halaman.
- `p { color: red; }`: Aturan CSS yang mengubah warna teks pada semua elemen `<p>` menjadi merah.
- `<body>`: Bagian yang berisi konten aktual halaman web, seperti teks, gambar, atau elemen lainnya.
- `<p>Welcome CSS</p>`: Elemen paragraf dengan teks "Welcome CSS", yang akan ditampilkan dengan warna merah karena aturan CSS yang telah ditentukan sebelumnya.
**Kode**
```HTMl
<!Doctype html>
<html>
  <head>
    <style> 
    p {
      color : red ; 
    }
    </style>
   </head>
   <body>
    <p> WELCOME CSS </p>
    <p> WELCOME CSS </p>
     </body>
</html>

```
### Hasil
![gambar](asetCSS/PP.JPG)
#  Percobaan Kedua
## Kode CSS
```
button{
Width:150px;
Height:50px;
Color: white;
text-align: right ;
margin-top :50px;
}
```
## Color
### Before
![gambar](asetCSS/WRN.JPG)
### After 

![gambar](asetCSS/WRN.W.jpg)Color adalah memberikan warna kepada tulisan yang dimana sebelum di kasih color atau warna tulisan nya berwarna hitam. setelah dikasih color atau warna tulisan klik aku berwarna putih
## TEXT-ALIGN

### Before
![gambar](asetCSS/WRN.jpg)
### After 

![gambar](asetCSS/RGHT.jpg)
Text-align adalah memberikan perataan kepada teks dimana saat kita menggunakan text-align = right  membuat posisi teks lebih ke samping kanan. 
## margin-top 
### Before
![Gambar](asetCSS/WRN.JPG)
### After

![gambar](asetCSS/MRGN.JPG)
Margin top digunakan untuk menentukan jarak antara batas atas suatu elemen dengan elemen di atasnya.

# Pemanggilan CSS
### Inline 
**Penjelasan**
Tag `<p>` yang memiliki gaya inline yang diterapkan langsung ke dalam elemen tersebut. Gaya tersebut adalah `font-size: 48px;`, yang berarti teks di dalam paragraf akan ditampilkan dengan ukuran font 48 piksel. Gaya ini diterapkan menggunakan atribut style pada elemen `<p>`.
```HTML
<!DOCTYPE html>
<html>
  <head>
    
  </head>
  <body>
    <p style="font-size: 48px;">Welcome CSS!</p>
    
  </body>
  
</html>

```
**Hasil**
![gambar](asetCSS/I.JPG)
### Internal
**Penjelasan**
- `h1`: Menetapkan warna teks biru dan margin atas sebesar `10000 pixel` untuk semua elemen `<h1>` dalam dokumen.
- `.merah`: Menetapkan warna teks merah untuk semua elemen yang memiliki kelas "merah".
- `.biru`: Menetapkan warna teks biru untuk semua elemen yang memiliki kelas "biru".
- `.kuning`: Menetapkan warna teks kuning untuk semua elemen yang memiliki kelas "kuning".
- `#hijau`: Menetapkan warna teks hijau untuk elemen dengan `ID "hijau"`.
- `.teks-besar`: Menetapkan ukuran font sebesar 60 piksel untuk semua elemen yang memiliki kelas "teks-besar".

```CSS
h1 {
  color : blue ;
  margin-top : 10000px ;


}

 .merah { 
  color : red ;
}

.biru{
  color : blue ;
}

.kuning{
  color : yellow ;
}

#hijau {
  color :green ;
}

.teks-besar{
  font-size :60px;
}
```
**Hasil**
![gambar](asetCSS/INC.JPG)
### External
**Penjelasan**
`<link rel="stylesheet" href="Style.CSS">`: Menautkan dokumen HTML dengan file CSS eksternal bernama "Style.CSS", sehingga dokumen HTML dapat menerapkan gaya yang didefinisikan dalam file CSS tersebut.
**Code**
```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>CSS</title>
    <link rel="stylesheet" href="Style.CSS">
    
  </head>
  <body>
    
    
     </body>
  
</html>
```
**Hasil**
![gambar](asetCSS/E.JPG)
# Selektor CSS
### Elemen Selector 
**Penjelasan**
`h1`: Ini adalah elemen selector yang menargetkan semua elemen `<h1>` dalam dokumen HTML untuk menerapkan aturan gaya tertentu, seperti warna teks biru dan margin atas sebesar 10000 piksel.
**Code**
```HTML
<h1>Halo RPL 1</h1>
h1 {
  color: blue;
  margin-top: 10000px;
}


```
**Hasil**
![gambar](asetCSS/ES.JPG)
### Class Selector
**Penjelasan**
- `<!DOCTYPE html>`: Mendefinisikan tipe dokumen sebagai HTML versi 5. 
- `<html>`: Menandakan awal dan akhir dari dokumen HTML.
- `<head>`: Berisi informasi tambahan tentang dokumen HTML, seperti judul dan tautan ke file CSS.    
- `<title>CSS</title>`: Menentukan judul dokumen yang akan ditampilkan di tab browser.
- `<link rel="stylesheet" href="Style.CSS">`: Menautkan dokumen HTML dengan file CSS eksternal bernama "Style.CSS", sehingga dokumen HTML dapat menerapkan gaya yang didefinisikan dalam file CSS tersebut.
- `<body>`: Berisi konten yang akan ditampilkan kepada pengguna.  
- `<p class="biru"> ini warna biru </p>`: Elemen ini hanya memiliki satu kelas CSS, yaitu "biru". Oleh karena itu, elemen tersebut akan menerapkan gaya yang telah ditentukan untuk kelas "biru" dalam file CSS atau dalam bagian gaya internal/inline yang berkaitan dengan kelas tersebut. Dan memberikan warna biru. 

**Code**
```HTML
 <!DOCTYPE html>
 <html>
  <head>
    <title>CSS</title>
    <link rel="stylesheet" href="Style.CSS">
    
  </head>
  <body>
    
    
    <p class="biru" >ini warna biru </p>
    
     </body>
  
</html>


```
**Hasil**
![gambar](asetCSS/BR.jpg) 



### ID Selector
**Penjelasan**
- `<!DOCTYPE html>`: Mendefinisikan tipe dokumen sebagai HTML versi 5. 
- `<html>`: Menandakan awal dan akhir dari dokumen HTML.
- `<head>`: Berisi informasi tambahan tentang dokumen HTML, seperti judul dan tautan ke file CSS.    
- `<title>CSS</title>`: Menentukan judul dokumen yang akan ditampilkan di tab browser.
- `<link rel="stylesheet" href="Style.CSS">`: Menautkan dokumen HTML dengan file CSS eksternal bernama "Style.CSS", sehingga dokumen HTML dapat menerapkan gaya yang didefinisikan dalam file CSS tersebut.
- `<body>`: Berisi konten yang akan ditampilkan kepada pengguna.  
- Elemen `<p id="hijau"> ini warna hijau </p>` memiliki atribut `id` yang menentukan identitas uniknya dalam dokumen HTML. Dengan demikian, fungsi dari atribut `id` ini adalah untuk memberikan cara yang unik untuk merujuk atau menargetkan elemen tersebut dalam CSS. Dan memberikan warna hijau pada teks. 
**Code**
```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>CSS</title>
    
    <link rel="stylesheet" href="Style.CSS">
    
  </head>
  <body>
    <p style="font-size: 48px;">Welcome CSS!</p>
    <h1>Halo RPL 1</h1>
    
    <p id="hijau" > ini warna hijau </p>
  </body>
  
</html>

```
**Hasil**
![gambar](asetCSS/HJ.jpg)

# TEXT 

## Text align Left 
`text-align` dengan nilai `left` digunakan untuk mengatur teks agar tersusun sejajar dengan sisi kiri dari elemen tempat teks tersebut berada.
## Text align Right
`text-align` dengan nilai `right` digunakan untuk mengatur teks agar tersusun sejajar dengan sisi kanan dari elemen tempat teks tersebut berada. 
## Text justify
`text-align` dengan nilai `justify` digunakan untuk mengatur teks agar terlihat rata di kedua sisi (baik kiri maupun kanan) dari elemen tempat teks tersebut berada.
### Penjelasan
`text-align` dengan nilai `center` digunakan untuk mengatur teks agar terletak di tengah dari elemen tempat teks tersebut berada.berarti teks akan diatur agar berada di tengah secara horizontal dalam elemen tersebut, dengan ruang yang sama di sisi kiri dan kanan.
### Kode
```
 <p> selamat datang</p>
 p{
  text-align : center ;
  }
```
### Hasil
**Before**
![gambar](asetCSS/AC.JPG)
**After**
![gambar](asetCSS/BC.JPG)
### Kesimpulan
Selamat datang" yang terdapat dalam elemen `<p>` akan diatur menjadi rata tengah secara horizontal di dalam elemen tersebut, karena properti CSS text-align: center; diterapkan pada elemen `<p>`. 

## TEXT decoration
### None
`text-decoration: none`; digunakan untuk menghilangkan dekorasi teks, seperti garis bawah atau garis tengah. Ini berarti teks yang terdapat di dalam elemen tersebut tidak akan memiliki dekorasi tambahan seperti garis bawah, garis tengah, atau gaya lain yang biasanya ditampilkan secara default oleh browser.
### Overline
`Text-decoration: overline;`adalah properti CSS yang digunakan untuk menambahkan garis di atas teks. Ketika properti ini diterapkan pada sebuah elemen teks, teks tersebut akan memiliki garis di atasnya.
### Line-throught
`Text-decoration: line-through`; adalah properti CSS yang digunakan untuk menambahkan garis tengah di tengah teks. Ketika properti ini diterapkan pada sebuah elemen teks, teks tersebut akan memiliki garis yang melintasi di tengahnya.

### Penjelasan
`Text-decoration: underline`; adalah properti CSS yang digunakan untuk menambahkan garis di bawah teks. Ketika properti ini diterapkan pada sebuah elemen teks, teks tersebut akan memiliki garis di bawahnya.
### Code
```
text-decoration : underline;
```

### Hasil
**Before**
![gambar](asetCSS/AC.JPG)
**After**
![gambar](asetCSS/BU.JPG)
### Kesimpulan
Selamat datang" Dan Terima kasih yang terdapat dalam elemen `<p>` akan membuat tulisan mempunyai garis bawah di teks. karena properti CSS text-decoration : underline ; diterapkan pada elemen `<p>`. 

## Text-Transform
## Text-transform lowercase
`Text-transform: lowercase;` adalah properti CSS yang digunakan untuk mengubah teks menjadi huruf kecil (huruf kecil). Ketika properti ini diterapkan pada sebuah elemen teks, semua karakter huruf dalam teks tersebut akan diubah menjadi huruf kecil.
## text-transform capitalize
`Text-transform: capitalize`; adalah properti CSS yang digunakan untuk mengubah teks agar setiap kata dalam teks tersebut dimulai dengan huruf kapital. Ketika properti ini diterapkan pada sebuah elemen teks, huruf pertama dari setiap kata dalam teks tersebut akan diubah menjadi huruf kapital, sedangkan huruf lainnya akan tetap dalam format huruf kecil.
## text-transform none
`Text-transform: none;`adalah properti CSS yang mengembalikan teks ke format aslinya tanpa transformasi apapun. Ini berarti teks akan ditampilkan sesuai dengan format yang sudah ditulis dalam elemen HTML tanpa adanya perubahan pada huruf besar atau huruf kecilnya.

### Penjelasan
`Text-transform: uppercase;` adalah properti CSS yang digunakan untuk mengubah teks menjadi huruf besar (kapital). Ketika properti ini diterapkan pada sebuah elemen teks, semua karakter huruf dalam teks tersebut akan diubah menjadi huruf kapital.
### Kode
```
p{
  
  text-transform : uppercase ;
  
 }
```

### Hasil
![gambar](asetCSS/BUP.JPG)
### Kesimpulan
teks yang ada di dalam elemen `<p>` akan diubah menjadi huruf kapital semua. Dengan menerapkan properti `text-transform: uppercase;`, semua huruf dalam teks tersebut akan diubah menjadi huruf besar (uppercase).

## Text-indent
`Text-indent` adalah properti CSS yang digunakan untuk mengatur jarak atau indentasi awal dari paragraf atau teks di dalam sebuah elemen
## Letter Spacing
Letter spacing adalah properti CSS yang digunakan untuk mengatur jarak antara karakter (huruf) dalam teks.
### Kode
```
.halaman-1{
       letter-spacing : 100 px ;
       }
```
### Hasil
**Before**
![gambar](asetCSS/BC.JPG)
**After**
![gambar](asetCSS/LT.JPG)
### Kesimpulan
teks di dalam elemen yang memiliki kelas "halaman-1" akan memiliki jarak antar huruf yang sangat besar. Dengan menerapkan properti letter-spacing: 100px;, spasi antara huruf-huruf dalam teks akan diperbesar menjadi 100 piksel.

## Line-height
Line height adalah properti CSS yang digunakan untuk mengatur tinggi baris di dalam sebuah elemen teks.

## Word Spacing
Word spacing adalah properti CSS yang digunakan untuk mengatur jarak antara kata-kata dalam teks

# Background
## Background-color
Background-color adalah properti CSS yang digunakan untuk mengatur warna latar belakang dari sebuah elemen HTML contoh warna aqua.

### Kode program
```
.halaman-1{
    
       Background-color :aqua ;
       }
```

### Hasil
**Before**
![gambar](asetCSS/BGH.JPG)**After**
![gambar](asetCSS/BUP.JPG)
### Kesimpulan
`Background-color: aqua;`, di gunakan untuk membuat latar belakang dari elemen tersebut akan diubah menjadi warna aqua.

## Background-image
Background-image adalah properti CSS yang digunakan untuk menentukan gambar yang akan digunakan sebagai latar belakang dari sebuah elemen HTML.
### Kode Program
```
.halaman-1{
    
       background-image: url("Camera/F.png"); 
       }
```
### Hasil
**Before**
![gambar](asetCSS/BI.JPG)
### Kesimpulan
elemen yang memiliki kelas "halaman-1" akan memiliki gambar latar belakang yang ditentukan oleh URL "Camera/F.png".

## Background-repeat
Background-repeat adalah properti CSS yang digunakan untuk mengatur bagaimana gambar latar belakang akan diulang (repeated) jika ukuran gambar tersebut lebih kecil dari ukuran elemen yang ditetapkan.
## Background-attachment fixed
`background-attachment: fixed;` adalah properti CSS yang digunakan untuk mengontrol apakah gambar latar belakang akan tetap diam atau bergulir bersama konten saat pengguna menggulir halaman.
### Kode program
```
.halaman-1{
    
     background-attachment: fixed ;
       }
```

### Hasil

### Kesimpulan
elemen yang memiliki kelas "halaman-1" akan tetap diam relatif terhadap jendela browser.
## Background-Size
Background-size adalah properti CSS yang digunakan untuk mengatur ukuran dari gambar latar belakang sebuah elemen HTML.
### Kode Program
```
.halaman-1{
    
     background-size: 100%;
       }
```
### Hasil

### Kesimpulan
properti `background-size: 100%;`, ukuran gambar latar belakang akan diatur sedemikian rupa sehingga seluruh area latar belakang elemen tersebut tercakup oleh gambar tersebut.
## Background-Posetion
Background-position adalah properti CSS yang digunakan untuk menentukan posisi awal atau titik referensi dari gambar latar belakang yang diterapkan pada sebuah elemen HTML.
### Kode program
```
.halaman-1{
    
     background-position: 50px;
       }

```

### Hasil

### Kesimpulan
properti `background-position: 50px;`, gambar latar belakang akan dimulai dari posisi 50 piksel dari sisi kiri elemen tersebut dan tetap berada di posisi vertikal tengah secara default.

# Font
## Font Size
Font-size adalah properti CSS yang digunakan untuk mengatur ukuran font teks dalam sebuah elemen HTML.

### Kode Program
```
.halaman-1{
    
     font-size : 100px;
       }
```
### Hasil

### Kesimpulan
properti font-size: 100px;, ukuran font dalam elemen tersebut akan diperbesar menjadi 100 piksel.
## Font-style italic
Font-style adalah properti CSS yang digunakan untuk menentukan gaya huruf (font style) dari sebuah teks.
italic: Menampilkan teks dalam gaya miring (italic), jika font tersebut mendukung.
### Kode program
```
.halaman-1{
    
     font-style: italic ;
       }
```

### Hasil
**After**
![gambar](asetCSS/FI.JPG)
**Before**
![gambar](asetCSS/BUP.JPG)
### Kesimpulan
properti `font-style: italic;`, teks dalam elemen tersebut akan ditampilkan dengan gaya huruf miring.

## Font-weight Bold
`font-weight: bold;` dalam CSS, teks dalam elemen yang diberi aturan tersebut akan ditampilkan dengan ketebalan huruf yang lebih tebal dari biasanya. 
### Kode program
```
.halaman-1{
    
     font-weight: bold ;
       }
    

```
### Hasil

### Kesimpulan
`font-weight: bold;`, teks dalam elemen tersebut akan memiliki gaya huruf tebal.

## Font-family justify
`Font-family justify`properti ini mengatur teks agar rata di kedua sisi, sehingga ruang antara kata-kata disesuaikan untuk mengisi seluruh lebar elemen dengan cara yang seragam. 

# Box Model
## Border-Width
`Border-wkdth`digunakan untuk menentukan lebar border dari sebuah elemen.

## Border-style solid
`border-style: solid;` adalah properti CSS yang mengatur gaya border menjadi garis lurus dan solid.
### Kode program
```
img{
   ​​​​border-style: solid;
    }
```
### Hasil
![gambar](asetCSS/BSS.JPG)
### Kesimpulan
`border-style: solid;` adalah properti CSS yang mengatur gaya border menjadi garis lurus dan solid.

## Border-color orangered
`border-color: orangered`; adalah properti CSS yang mengatur warna border dari sebuah elemen menjadi oranye merah (orangered). 
## Kode program
```
.F{
      border-color: orangered;
      }
```
## Hasil 
**Before**
![gambar](asetCSS/BCO.JPG)
**After**
![gambar](asetCSS/BBCO.JPG)
### Kesimpulan
Mengatur warna atau memberikan warna orangered pada pinggiran  border 
# Padding
## Padding-left
`padding-left` adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di sebelah kiri konten dalam sebuah elemen. 
### Kode Program
```
F{
    
    padding-left: 29px;
    }
```
### Hasil
**Before**
![gambar](asetCSS/PL.JPG)
**After**
![gambar](asetCSS/BBCO.JPG)
### Kesimpulan
elemen HTML yang memiliki kelas "F" akan memiliki ruang tambahan di bagian kiri sebesar 29 piksel.  Dan membuat tulisan klik disini tidak terlalu ke kiri. 
## Padding-bottom
`padding-bottom` adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di bagian bawah konten dalam sebuah elemen. 
### Kode Program
```
.F{

    padding-bottom: 25px;
    }
```
### Hasil
**Before**
![gambar](asetCSS/PB.JPG)
**After**
![gambar](asetCSS/BBCO.JPG)
### Kesimpulan
 elemen HTML yang memiliki kelas "F" akan memiliki ruang tambahan di bagian bawah sebesar 25 piksel.  Dan membuat tulisan klik disini tidak terlalu ke bawah. 
## Padding-Right
`padding-right` adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di sebelah kanan konten dalam sebuah elemen. 
### Kode Program
```
.F{
    
    padding-right: 29px;
    }
```
### Hasil
**Before**
![gambar](asetCSS/PR.JPG)
**After**
![gambar](asetCSS/BBCO.JPG)
### Kesimpulan
elemen HTML yang memiliki kelas "F" akan memiliki ruang tambahan di bagian kanan sebesar 29 piksel.  Dan membuat tulisan klik disini tidak terlalu ke kanan. 
## Padding-top
`padding-top`adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di bagian atas konten dalam sebuah elemen.
### Kode program
```

.F{
    
    padding-top: 20px;
    }
```
### Hasil
**Before**
![gambar](asetCSS/PT.JPG)
**After**
![gambar](asetCSS/BBCO.JPG)
### Kesimpulan
elemen HTML yang memiliki kelas "F" akan memiliki ruang tambahan di bagian atasnya sebesar 20 piksel.  Dan membuat tulisan klik disini tidak terlalu ke atas. 
# Margin
## Margin-Left
`margin-left`adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di sebelah kiri dari sebuah elemen terhadap elemen lain di sekitarnya. 
### Kode Program
```
img{
    
    margin-left: 600px;
    }
```
### Hasil
**Before**
![gambar](asetCSS/ML.JPG)
**After**
![gambar](asetCSS/AML.JPG)
## Margin-Top
`margin-top` adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di bagian atas dari sebuah elemen terhadap elemen lain di atasnya.
### Kode Program
```
img{
    
    margin-top: 50px;
    }
```
### Hasil
**Before**
![gambar](asetCSS/MT.JPG)

**After**
![gambar](asetCSS/AML.JPG)
### Kesimpulan
atura gaya ini memengaruhi tata letak (layout) elemen-elemen HTML dengan tag "F" dengan menambahkan margin di bagian atas sebesar 60 piksel.
## Margin-Right
`margin-right` adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di sebelah kanan dari sebuah elemen terhadap elemen lain di sekitarnya.
### Kode program
```
F{
    
    margin-right: 60px;
    }
```
### Hasil

![gambar](asetCSS/AML.JPG)
### Kesimpulan
elemen-elemen HTML dengan tag "F" akan memiliki jarak atau spasi tambahan sebesar 60 piksel di sebelah kanan. 
## Margin-Bottom
`margin-bottom` adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di bagian bawah dari sebuah elemen terhadap elemen lain di bawahnya. 

### Kode program
```
.F{

    Margin-bottom: 90px
}

```
### Hasil
**Before**
![gambar](asetCSS/MB.JPG)
**After**
![gambar](asetCSS/AML.JPG)
### Kesimpulan
elemen-elemen yang memiliki kelas "F" akan memiliki jarak atau spasi sebesar 90 piksel di bagian bawahnya.
# Pseudo-classes

##  Hover
- `button:hover`: adalah pseudo-class selector yang menargetkan tombol (button) ketika pengguna mengarahkan kursor ke atasnya (hover) atau diklik. 
- `background-color: red;`: Properti ini menetapkan warna latar belakang tombol menjadi merah ketika tombol sedang di-hover.
- `color: white;`: Properti ini menetapkan warna teks pada tombol menjadi putih ketika tombol di-hover.
- `height: 100px;`: Properti yang digunakan untuk membuat  tinggi (height) tombol menjadi 100 piksel ketika tombol di-hover.
- `width: 100px;`: Properti yang digunakan untuk membuat lebar (width) tombol menjadi 100 piksel ketika tombol di-hover.
### Kode program
```
button:hover{
  background-color:red;
  color:white;
  height:100px;
  
  width:100px;

}
```
### Hasil
![gambar](asetCSS/PA.JPG)
### Kesimpulan
Setiap property memberikan perubahan yang berbeda dari hover akan memberikan perubahan saat di klik, width dan height untuk mengatur lebar dan tinggi, background-color red memberikan warna merah ketika diklik, dan color white digunakan untuk memberikan warna putih pada teks. 

## Active
`button:active`: adalah pseudo-class selector yang menargetkan tombol (`button`) ketika tombol tersebut sedang dalam keadaan "active", atau tombol sedang ditekan. 
`color: yellow;`: Properti memberikan warna kuning pada teks ketika tombol sedang active atau tombol sedang ditekan. 
### Kode program
```
button:active{
  color: yellow ;
}
```
### Hasil
![gambar](asetCSS/PAK.JPG)
### Kesimpulan
Teks klik akan berganti warna menjadi kuning jika ditekan dan berputar. 

# Transition 
### Penjelasan
+ `Transition`:  untuk mengatur pertunjukan perubahan, mengubah penampilan elemen dari satu keadaan ke keadaan lain, memberikan dinamika visual yang menarik dalam desain web Anda.
+ `Transition-delay`: properti ini memberikan momen kejutan atau antisipasi sebelum perubahan yang dijanjikan terjadi, menambah dramatisasi pada tampilan elemen.
- `Transition-duration`: menentukan lamanya waktu ketika elemen berubah, memungkinkan Anda untuk mengatur seberapa lama penonton (pengguna) menikmati perubahan tersebut.
- `Transition-property`: menentukan apa yang akan berubah, seperti warna, ukuran, atau posisi, menciptakan efek transisi yang beragam dan menarik.
- `Transition-timing-function`:  properti ini mengatur ritme perubahan, menentukan apakah transisi akan bergerak dengan lembut dan halus seperti aliran air, atau tiba-tiba dan dramatis seperti petir yang menyambar.
### Kode program
```
button:hover{
  
  transition:all 0.9s ease-in;
  
}
```

# Transform 
### Penjelasan
- `transform: scale(0.5);`= Mengubah ukuran elemen menjadi setengah dari ukuran aslinya.
- `transform: scalex(0.5);`= Hanya mengubah skala elemen secara horizontal menjadi setengah dari ukuran aslinya.
- `transform: rotate(45deg);`= Memutar elemen sebesar 45 derajat searah jarum jam.
- `transform: skewX(-25deg);`= Membengkokkan elemen secara horizontal sebesar -25 derajat (ke arah kiri).
- `transform: skew(25deg,5deg);`= Membengkokkan elemen sebesar 25 derajat secara horizontal (ke kanan) dan 5 derajat secara vertikal (ke atas).
- `transform: translate(50px,52px);`= Menggeser elemen sebesar 50 piksel ke kanan dan 52 piksel ke bawah.
- `transform: matrix(0.7,-0.5,0.5,0.4,0.5,0.7);`= Menggambarkan transformasi menggunakan matriks 2D den
### Kode Program
```
button:active{
  
  transform:matrix(0.7,-0.5,0.5,0.4,0.5,0.7);
  }
```
### Hasil
![gambar](asetCSS/TRANS.JPG)

### Kesimpulan
Setiap properti transform mengubah tampilan elemen dengan cara yang berbeda-beda sesuai dengan property. 

# Flexbox 
## Flex Container
### Display Flex
`display: flex`, kita dapat dengan mudah mengatur tata letak elemen-elemen di dalamnya dengan properti-properti seperti `flex-direction`, `justify-content`, `align-items`, dan lain-lain.

### Kesimpulan
`display: flex`, kita dapat dengan mudah mengatur tata letak elemen-elemen di dalamnya menggunakan properti-properti seperti `flex-direction`, `justify-content`, `align-items`, dan properti lainnya yang terkait dengan model tata letak flexbox.


### Flex-Direction
- `flex-direction: column;`: Mengatur tata letak dari flex container menjadi vertikal, sehingga flex items diatur dari atas ke bawah.
- `flex-direction: column-reverse;`: Mengatur tata letak dari flex container menjadi vertikal terbalik, sehingga flex items diatur dari bawah ke atas.
- `flex-direction: row;`: Mengatur tata letak dari flex container menjadi horizontal, sehingga flex items diatur dari kiri ke kanan.
- `flex-direction: row-reverse;`: Mengatur tata letak dari flex container menjadi horizontal terbalik, sehingga flex items diatur dari kanan ke kiri.
### Kode Program
```
.box-container{
  
  flex-direction: column;
  
}
```
## Hasil
![gambar](asetCSS/JCY.JPG)
### Kesimpulan
Setiap properti flex-direction mengubah tampilan elemen dengan cara yang berbeda-beda sesuai dengan property. 
Contoh`column` untuk tata letak vertikal dari atas ke bawah.
`column-reverse` untuk tata letak vertikal terbalik dari bawah ke atas. `row` untuk tata letak horizontal dari kiri ke kanan.`row-reverse` untuk tata letak horizontal terbalik dari kanan ke kiri.
### Align-Items
- `align-items: center;`: Flex items akan diatur di tengah-tengah sumbu silang dari flex container.
- `align-items: flex-start;`: Flex items akan diatur pada awal sumbu silang dari flex container.
- `align-items: flex-end;`: Flex items akan diatur pada akhir sumbu silang dari flex container.
- `align-items: baseline;`: Flex items akan diatur sedemikian rupa sehingga garis dasar dari teks pada masing-masing item berada pada level yang sama.
- `align-items: stretch;`: Flex items akan diperpanjang untuk mencapai tinggi maksimal flex container, mengisi ruang kosong di sepanjang sumbu silang.
### Kode Program
```
.box-container{
  
  align-items:center ;
  
}
```
### Hasil
![gambar](asetCSS/FIY.JPG)
### Kesimpulan
Setiap properti align-items mengubah tampilan elemen dengan cara yang berbeda-beda sesuai dengan property. 
Contoh`center` untuk menempatkan flex items di tengah-tengah sumbu silang.`flex-start` untuk menempatkan flex items di awal sumbu silang.`flex-end` untuk menempatkan flex items di akhir sumbu silang.`baseline` untuk menempatkan flex items sehingga garis dasar teks masing-masing item berada pada level yang sama.`stretch` untuk memperpanjang flex items sehingga mencapai tinggi maksimal flex container, mengisi ruang kosong di sepanjang sumbu silang.
### Justify-Content
 - `justify-content: flex-start;`: Mengatur fleks item ditempatkan di bagian awal (mulai) dari sumbu utama flex container.
- `justify-content: flex-end;`: Mengatur fleks item ditempatkan di bagian akhir (akhir) dari sumbu utama flex container.
- `justify-content: center;`: Mengatur fleks item ditempatkan di tengah-tengah sumbu utama flex container.
- `justify-content: space-around;`: Mengatur fleks item didistribusikan secara merata di sekitar sumbu utama flex container, dengan ruang yang sama di antara mereka.
- `justify-content: space-between;`: Mengatur fleks item didistribusikan secara merata di sepanjang sumbu utama flex container, dengan ruang yang sama di antara fleks item pertama dan terakhir, tetapi tidak ada ruang di antara fleks item yang berdekatan.
### Kode Program
```
.box-container{
  
  justify-content: center ;
}
```
### Hasil
![Gambar](asetCSS/JCY.JPG)

### Kesimpulan
Setiap properti justify-Content mengubah tampilan elemen dengan cara yang berbeda-beda sesuai dengan property. 
Contoh`flex-start` untuk menempatkan flex items di awal (mulai) sumbu utama.`flex-end` untuk menempatkan flex items di akhir (akhir) sumbu utama.`center` untuk menempatkan flex items di tengah-tengah sumbu utama.`space-around` untuk mendistribusikan flex items secara merata di sekitar sumbu utama dengan ruang yang sama di antara mereka.`space-between` untuk mendistribusikan flex items secara merata di sepanjang sumbu utama dengan ruang yang sama di antara flex items pertama dan terakhir, tetapi tidak ada ruang di antara flex items yang berdekatan.

## Flex Items

### Penjelasan HTML
- Tag `<DOCTYPE html>` memberitahu web bahwa dokumen HTML adalah versi 5
- Tag pembuka `<html>` menandai awal sebuah dokumen HTML sampai dengan tag penutup `</html>`
- Tag pembuka `<head>` berisi informasi tentang halaman HTML sampai dengan tag penutup `</head>` ,biasanya dalam tag head terdapat tag `<title>` untuk memberikan informasi judul halaman HTML
- Apapun tag yang berada di antara tag pembuka `<body>` sampai dengan tag penutup `</body>` akan tampil di web browser.
- `<title>`: Menentukan judul halaman.
- `<link rel="stylesheet" href="Tugassbox.css">`: Menghubungkan dokumen dengan stylesheet eksternal.
- `<body class="main-container">`: Memulai konten utama halaman dengan kelas "main-container".
- `<div class="hero-container">`: Kontainer utama untuk semua konten.
- `<div class="box-container">`: Kontainer untuk setiap kotak konten.
- `<h1 class="item box-item-1">Selamat Datang</h1>`: Teks "Selamat Datang" dengan kelas "item" dan "box-item-1".
- `<h1 class="item box-item-2">di <b>Web Fadhil</b></h1>`: Teks "di Web Fadhil" dengan kelas "item" dan "box-item-2", kata "Web Fadhil" ditebalkan.
- `<div class="item box-item-3">`: Kontainer untuk tombol "Klik disini" dengan kelas "item" dan "box-item-3".
- `<button class="F">Klik disini</button>`: Tombol dengan teks "Klik disini" dan kelas "F".
- `<div class="item-box">`: Kontainer untuk gambar.
- `<img src="camera/F.png">`: Gambar "F.png" dari direktori "camera".
## Penjelasan CSS
- `body`: Mengatur latar belakang seluruh halaman menjadi warna ungu (purple).
- `.main-container`: Memberikan latar belakang warna ungu (purple) pada elemen dengan kelas "main-container". Ini mungkin digunakan sebagai wadah utama untuk konten.
- `.box-item-1 dan .box-item-2`: Mengatur tampilan teks pada elemen-elemen dengan kelas "box-item-1" dan "box-item-2". Ini termasuk mengatur ukuran font menjadi 50px, warna putih, dan memberikan jarak atas sejauh 10px.
- `.F:hover`: Mengatur tampilan tombol dengan kelas "F" saat kursor berada di atasnya (hover). Saat tombol di-hover, ukurannya diperbesar, warna dan border berubah, dan posisinya digeser ke kiri dengan transisi animasi selama 0.9 detik.
- `button:active`: Memberikan efek transformasi rotasi sebesar 45 derajat pada tombol ketika tombol sedang aktif (ditekan).
- `img`: Mengatur tampilan gambar dengan lebar dan tinggi masing-masing 250px, dengan sudut melingkar sebesar 200px, serta menetapkan margin kiri sejauh 400px dan margin atas sejauh -400px. Hal ini dapat mempengaruhi posisi dan tata letak gambar dalam halaman.

### Kode Program
```HTML
<!DOCTYPE html>
<html>
<head>
    <title>Belajar CSS3</title>
    <link rel="stylesheet" href="Tugassbox.css">
</head>
<body class="main-container">
    <div class="hero-container">
    <div class="box-container">
    <h1 class="item box-item-1">
    Selamat Datang
    </h1>
    
    <h1 class="item box-item-2">
    di <b>Web Fadhil</b>
    </h1>
    <div class="item box-item-3">
    <button class="F">Klik disini</button>
    </div>
    </div>
    
    <div class="box-container">
    <div class="item-box">
    <img src="camera/F.png">
    </div>
        </div>
    </div>
</body>
</html>

```

```CSS
body{
  background-color:purple;
}
.main-container {
    background-color: purple;
}
.box-item-1{
    font-size: 50px;
    color: white;
    margin-top:10px;
    }
.box-item-2{
   font-size: 50px;
    color: white;
    margin-top:10px;
}

.F:hover {
    background-color: purple;
    margin-left:200px;
    padding-left:29px;
    padding-top:20px;
    padding-bottom:25px;
    padding-right:29px;
    color: orangered;
    border-color:orangered;
    margin-top: 50px; 
    margin-right:60px;
    margin-bottom:90px;
   transition:all 0.9s ease-in; 
}
 button:active{ 
  transform:rotate(45deg);
  }
img{
    width: 250px;
    height: 250px;
    border-radius: 200px;
    border-color: white;
    border-style: solid;
    margin-left: 400px;
    margin-top: -400px;
}

```
### Hasil
![gambar](asetCSS/TCSS.JPG)

# Position
## Position Relative
### Penjelasan
- `background-color: aqua;`: Memberikan warna latar belakang elemen menjadi aqua. 
- `position: relative;`: Menetapkan posisi elemen relatif terhadap posisi defaultnya. 
- `top: 20px;`: Menggeser elemen 20 piksel ke bawah dari posisi defaultnya.
- `left: 30px;`: Menggeser elemen 30 piksel ke kanan dari posisi defaultnya. 
### Kode Program
```
box-1{
  background-color:aqua;
  position:relative;
  top:20px;
  left:30px; 
}
```
### Hasil 
**BEFORE**
![gambar](asetCSS/P.JPG)
**AFTER**
![gambar](asetCSS/PRBA.JPG)
### Kesimpulan
elemen dengan kelas "box-1" mengatur latar belakang menjadi warna aqua dan menggeser elemen 20 piksel ke bawah dan 30 piksel ke kanan dari posisi defaultnya.
## Position Absolute
### Penjelasan

- `background-color: purple;`: Mengatur latar belakang elemen menjadi warna ungu (purple).
- `position: absolute;`: Menetapkan elemen ke dalam konteks posisi yang dihitung relatif terhadap elemen induk yang memiliki posisi non-static. 
- `top: 15px;`: . elemen 15 piksel dari atas relatif terhadap posisi elemen induk yang ditetapkan dalam konteks posisi absolut.
- `left: 10px;`: Menggeser elemen 10 piksel dari kiri relatif terhadap posisi elemen induk yang ditetapkan dalam konteks posisi absolut.
### Kode Program
```
.box-2{
  background-color:purple;
  position:absolute;
  top:15px;
  left:10px; 
}
```
### Hasil 
**BEFORE**
![gambar](asetCSS/P.JPG)
**AFTER**
![gambar](asetCSS/PAP.JPG)
### Kesimpulan
kelas "box-2" menetapkan latar belakangnya menjadi warna ungu (purple) dan mengatur posisinya secara absolut,dimana elemen digeser 15 piksel dari atas dan 10 piksel dari kiri.

## Position Fixed
### Penjelasan
- `top: 50px;`: Menggeser elemen 50 piksel ke bawah dari posisi defaultnya.
- `left: 30px;`: Menggeser elemen 55 piksel ke kanan dari posisi defaultnya. 
- `background-color: aqua;`: Mengatur latar belakang elemen menjadi warna aqua.
- `position: fixed;`: Mengatur elemen dalam posisi tetap, yang berarti elemen akan tetap berada pada lokasi yang sama saat kita scroll. 
### Kode Program
```
box-1{
  background-color:aqua;
  position:Fixed;
  top:50px;
  left:55px; 
}
```
### Hasil 
**BEFORE**
![gambar](asetCSS/P.JPG)
**AFTER**
![gambar](asetCSS/PF.JPG)
### Kesimpulan
position: fixed, elemen akan tetap berada pada posisinya yang ditentukan jika discrool.properti top dan left digunakan untuk menentukan jarak elemen dari tepi atas dan kiri. 

## Position Sticky
### Penjelasan
- `background-color: aqua;`: Mengatur latar belakang elemen menjadi warna aqua.
- `Position: sticky;`: Mengatur elemen dalam posisi "sticky", yang berarti elemen akan berperilaku seperti posisi relatif sampai mencapai posisi tertentu saat discrool kemudian akan tetap berada di tempat.elemen akan "melekat" pada posisi yang telah ditentukan saat jarak scroll mencapai nilai tertentu.
 - `top: 50px;`: Menggeser elemen sejauh 50 piksel dari atas elemen induk yang memiliki posisi tetap.
- `left: 55px;`: Menggeser elemen sejauh 55 piksel dari sisi kiri elemen induk yang memiliki posisi tetap.
### Kode Program
```
box-1{
  background-color:aqua;
  position:Sticky;
  top:50px;
  left:55px; 
}
```
### Hasil 
**BEFORE**
![gambar](asetCSS/P.JPG)
**AFTER**
![gambar](asetCSS/PS.JPG)
### Kesimpulan
`position: sticky`, elemen akan seperti posisi relatif sampai jarak scroll mencapai nilai tertentu. elemen akan tetap berada pada posisi yang telah ditentukan saat jarak scroll mencapai nilai tertentu, sambil tetap mengikuti pergeseran scroll di bawahnya.