# Lab9Web

## Nama : Prananda Aditya

## NIM : 312010130

## Kelas : TI.20.A1

## Mata Kuliah : Pemoggraman Web

# langkah langkah praktikum 9

## 1. Buat file baru dengan nama header.php

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta chasrset="UTF-8"F>
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet" media="screen" />
</head>
<body>
    <div class="container">
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
        <nav>
            <a href="home.php">Home</a>
            <a href="about.php">Tentang</a>
            <a href="kontak.php">Kontak</a>
        </nav>
```

## 2. Buat file baru dengan nama footer.php

```
    <footer>
        <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
    </footer>
</div>
</body>
</html>
```

## 3. Buat file dengan nama home.php

```
<?php require('header.php); ?>

<div class="content">
    <h2>Ini Halaman Home</h2>
<p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

## 4. Buat file baru dengan nama about.php

```
<?php require('header.php'); ?>
    <div class="content">
        <h2>Ini Halaman About</h2>
        <p>Ini adalah bagian content dari halaman.</p>
    </div>
<?php require('footer.php'); ?>
```

## 5. Output

![p](img/about.png)
![p](img/home.png)

# Pertanyaan dan Tugas

<br>Implementasikan konsep modularisasi pada kode program praktikum 8 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama.

## Berikut struktur direktori yang saya buat

```
lab8_php_database
├── config
│   ├── hapus.php
│   ├── koneksi.php
│   ├── tambah.php
│   └── ubah.php
├── layouts
│   ├── footer.php
│   ├── head-static.php
│   ├── header.php
│   ├── main.php
│   ├── tambah.php
│   └── ubah.php
├── static
│   ├── css
│   │   └── style.css
│   └── img
├── index.php
├── tambah.php
└── ubah.php
```

## config

<br>Dalam folder tersebut menyimpan file khusus php yang nanti akan dieksekusi

koneksi.php
