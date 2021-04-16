# Praktikum 3
# Pemrograman Web
```
Muhammad Rizkiansyah
311910071
TI19C1
Universitas Pelita Bangsa
```
## Langkah-langkah Praktikum
Persiapan membuat dokumen HTML dengan nama file lab3_list.html seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
      <h1>Membuat List</h1>
    </header>
</body>
</html>
```
## Membuat Ordered List
Kemudian tambahkan kode untuk membuat Ordered List seperti berikut
```
<section id="order-list">
    <h2>Ordered List</h2>
       <ol>
        <li>Pemrograman Web</li>
        <li>Sistem Informasi</li>
        <li>Basis Data 2</li>
    </ol>
</section>
```
![membuat list](https://user-images.githubusercontent.com/81758407/115006465-1d317280-9ed3-11eb-9507-6135887cc80e.PNG)
## Membuat Unorderd List
Kemudian tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada 
section unordered-list, seperti berikut.
```
<section id="unorder-list">
    <h2>Unordered List</h2>
    <ul type="square">
        <li>Jaringan Komputer</li>
        <li>Struktur Data</li>
        <li>Algoritma &amp; Pemrograman</li>
    </ul>
</section>
```
![list 2](https://user-images.githubusercontent.com/81758407/115007211-f1fb5300-9ed3-11eb-9a07-b85524ebc03f.PNG)
## Membuat Description List
Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list.
```
<section id="unorder-list">
    <h2>Description List</h2>
    <dl>
        <dt>Fakultas Teknik</dt>
        <dd>Teknik Industri</dd>
        <dd>Teknik Informatika</dd>
        <dd>Teknik Lingkungan</dd>
        <dt>Fakultas Ekonomi dan Bisnis</dt>
        <dd>Akuntansi</dd>
        <dd>Manajemen</dd>
        <dd>Bisnis Digital</dd>
    </dl>
</section>
```
![description list](https://user-images.githubusercontent.com/81758407/115007499-3c7ccf80-9ed4-11eb-8925-2d274b7dcfcb.PNG)
## Membuat Tabel
Buat file baru dengan nama lab3_tabel.html seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
     <header>
        <h1>Membuat Table</h1>
     </header>
</body>
</html>
```
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
```
<table border="1" cellpadding="4" cellspacing="0">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
        </tr>
    </thead>
 <tbody>
        <tr>
            <td>1.</td>
            <td>Teknik</td>
            <td>Teknik Informatika</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>Teknik</td>
            <td>Teknik Industri</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>Teknik</td>
            <td>Teknik Lingkungan</td>
        </tr>
 </tbody>
</table>
```
![tabel 1](https://user-images.githubusercontent.com/81758407/115008159-ff650d00-9ed4-11eb-837f-465f23f4aad4.PNG)
## Mengatur Margin dan Padding
Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan 
cellspacing pada tag table.
```
<table border="1" cellpadding="4" cellspacing="0">
```
![TABLE](https://user-images.githubusercontent.com/81758407/115008300-27ed0700-9ed5-11eb-9d06-156c278d7165.PNG)
## Menggabungkan Sel Data
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk 
menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara 
horizontal). 
```
<table border="1" cellpadding="6" cellspacing="0">
    <thead>
        <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
        </tr>
    </thead>
 <tbody>
    <tr>
        <td>1.</td>
        <td rowspan="3">Teknik</td>
        <td>Teknik Informatika</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>Teknik Industri</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>Teknik Lingkungan</td>
    </tr>
 </tbody>
</table>
```
![rowspan](https://user-images.githubusercontent.com/81758407/115008599-81edcc80-9ed5-11eb-9229-5d0914f43c49.PNG)
## Membuat Form
Buat file baru dengan nama lab3_form.html seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Form</h1>
    </header>
</body>
</html>
```
![membuat form](https://user-images.githubusercontent.com/81758407/115008778-bbbed300-9ed5-11eb-8f88-1dbc8a627eb5.PNG)
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
```
<form action="proses.php" method="post">
    <fieldset>
        <legend>Data Pelanggan</legend>
        <p>
            <label for="nama">Nama</label>
            <input type="text" id="nama" name="nama">
        </p>
        <p>
             <label for="alamat">Alamat</label>
            <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
        </p>
        <p>
            <label>Jenis Kelamin</label>
            <input id="jk_l" type="radio" name="kelamin" value="L" /><label
                for="jk_l">Laki-laki</label>
            <input id="jk_p" type="radio" name="kelamin" value="P" /><label
                for="jk_p">Perempuan</label>
        </p>
        <p><input type="submit" value="Login"></p>
    </fieldset>
</form>
```
![data pelanggan](https://user-images.githubusercontent.com/81758407/115009252-4b648180-9ed6-11eb-8737-f5b1944df74d.PNG)
## Menabahkan Style pada Form
Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut.
```
<style>
    form p > label {
        display: inline-block;
        width: 100px;
    }
    form input[type="text"], form textarea {
        border: 1px solid #197a43;
    }
    form input[type="submit"] {
        border: 1px solid #197a43;
        background-color: #197a43;
        color: #ffffff;
        font-weight: bold;
        padding: 5px 15px;
    }
</style>
```
![style login](https://user-images.githubusercontent.com/81758407/115009969-0db42880-9ed7-11eb-9068-27a5404125aa.PNG)
## Pertanyaan dan Tugas
1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Form Pendaftaran</title>

    <!-- menyisipkan css eksternal -->
 <link rel="stylesheet" href="style_eksternal.css" type="text/css">
</head>

<body>

          <!-- menambahkan link navigasi -->
    <nav>
        <a href="#">Home</a>
        <li class="dropdown"><a href="#">Menu</a>
            <ul class="isi-dropdown">
                <li><a href="lab1_tag_dasar.html">Dasar HTML</a></li>
                <li><a href="lab1_halaman2.html">Biodata</a></li>
                <li><a href="lab2_css_dasar.html">CSS Dasar</a></li>
                <li><a href="http://www.google.com">Google</a></li>
                <li><a href="form_data_pelanggan.html">Daftar</a></li>

            </ul>
        </li>
        
    </nav>
    <header>
        <h1>Form Pendafaran</h1>
    </header>

    <form action="proses.php" method="post">
        <fieldset>
            <legend>Daftar</legend>
            <p>
                <label for="nama">Nama</label>
                <input type="text" id="nama" name="nama">
            </p>
            <p>
                <label>Jenis Kelamin</label>
                <select name="Jenis Kelamin">
                    <option selected="selected">-Pilih Jenis kelamin-</option>
                    <option value="Laki-Laki">Laki-laki</option>
                    <option value="Perempuan">Perempuan</option>
                </select>
            </p>
            <p>
                <label for="kota">Kota Kelahiran</label>
                <input type="location" id="kota" name="kota">
            </p>
            <p>
                <label for="tgl">Tanggal Lahir</label>
                <input type="date" id="tgl" name="tgl">
            </p>
            <p>
                <label for="alamat">Alamat</label>
                <textarea id="alamat" name="alamat" cols="30" rows=""></textarea>
            </p>
            <p><input type="submit" value="Daftar"></p>
        </fieldset>
    </form>
</body>
</html>
```

![form](https://user-images.githubusercontent.com/81758407/115010803-0a6d6c80-9ed8-11eb-83fc-ec4f4f89a670.jpg)
![form1](https://user-images.githubusercontent.com/81758407/115010811-0c373000-9ed8-11eb-9705-e19de8a6185a.jpg)
![form2](https://user-images.githubusercontent.com/81758407/115010816-0ccfc680-9ed8-11eb-8f09-c3fa49000736.jpg)
