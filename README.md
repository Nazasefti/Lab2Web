## Lab2Web

## Nama : Naza Sefti Prianita

## NIM : 312210306

## Kelas : TI.22.A3

## Tugas Pemrograman Web 1

## Membuat Dokumen HTML

- Buatlah Dokumen HTML Seperti Berikut
  
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>CSS Dasar</title>
        </head>
        <body>
            <header>
                <h1>CSS Internal dan <i>Inline CSS</i></h1>
            </header>
            <nav>
                <a href="lab2_css_dasar.html">CSS Dasar</a>
                <a href="lab2_css_eksternal.html">CSS Eksternal</a>
                <a href="lab1_tag_dasar.html">HTML Dasar</a>
            </nav>
            <!-- CSS ID Selector -->
            <div id="intro">
                <h1>Naza Sefti Prianita</h1>
                <p style="text-align: center; color: #000000;">Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman
        Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat
        adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML
        dan CSS.</p>
        <!-- CSS Class Selector -->
            <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
            </div>
        </body>
        <head>

# Output

![Screenshot (15)](https://github.com/Nazasefti/Lab2Web/assets/115772516/0d9772c1-276e-4e7a-ba4c-b101130fdbe1)

# Mendeklarasikan CSS Internal

- Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.

        <head>
            <title>CSS Dasar</title>
            <style>
                body {
                    font-family:'Open Sans', sans-serif;
                }
                header {
                    min-height: 80px;
                    border-bottom:1px solid #77CCEF;
                }
                h1 {
                    font-size: 24px;
                    color: #0F189F;
                    text-align: center;
                    padding: 20px 10px;
                }
                h1 i {
                    color:#6d6a6b;
                }
            </style>
        <head>

- Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

![Screenshot (16)](https://github.com/Nazasefti/Lab2Web/assets/115772516/3619d58b-f473-46ec-9c10-53b9c830363c)

# Menambahkan CSS Sebaris

- Kemudian tambahkan deklarasi inline CSS pada tag
seperti berikut

        <p style="text-align: center; color: #ccd8e4;">

- Simpan kembali dan segarkan kembali browser untuk melihat perubahannya.
  
![Screenshot (17)](https://github.com/Nazasefti/Lab2Web/assets/115772516/38f5b354-63cf-41da-9a16-0f2f81e000fe)

# Membuat CSS Eksternal

- Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.

        nav{
            background: #20A759;
            color:#fff;
            padding: 10px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding:10px 20px;
        }
        nav .active,
        nav a:hover {
            background: #0B6B3A;
        }

- Kemudian tambahkan tag untuk merajuk file css yang sudah dibuat pada bagian

         <head>
         <!-- menyisipkan css eksternal -->
         <link rel="stylesheet" href="style_eksternal.css" type="text/css">
        </head>  
