# Lab3Web
# Lab3Web_Praktikum3
# Membuat List di HTML
1. Membuat Dokumen HTML
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

![Screenshot (55)](https://github.com/fajarmrdnt16/Lab3Web/assets/81574674/f1b0b097-8c71-4bc8-b837-8fe394931d58)
![Screenshot (47)](https://github.com/fajarmrdnt16/Lab3Web/assets/81574674/6a6f8eba-ff57-4702-bb4d-6653b5417383)

2. Membuat Order List
Kemudian tambahkan kode untuk membuat Ordered List seperti berikut.
<section id="order-list">
<h2>Ordered List</h2>
<ol>
<li>Pemrograman Web</li>
<li>Sistem Informasi</li>
<li>Basis Data 2</li>
</ol>
</section>

![Screenshot (48)](https://github.com/fajarmrdnt16/Lab3Web/assets/81574674/0774d8fb-5da8-4da1-8cfc-660400d6c33e)

3. Membuat Order List
   Kemudian tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada section unordered-list, seperti berikut.
   <section id="unorder-list">
<h2>Unordered List</h2>
<ul type="square">
<li>Jaringan Komputer</li>
<li>Struktur Data</li>
<li>Algoritma &amp; Pemrograman</li>
</ul>
</section>

![Screenshot (49)](https://github.com/fajarmrdnt16/Lab3Web/assets/81574674/33080c55-ff3e-421b-b7de-c404799b5a05)

4. Membuat Description List
   Tambahkan kode untuk membuat description list setelah deklarasi unorderd-list.
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

![Screenshot (50)](https://github.com/fajarmrdnt16/Lab3Web/assets/81574674/9107e004-a5d9-4d5f-b637-3ea8682da7d8)

#Membuat Tabel Di HTML
1. Membuat Dokumen Di HTML
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

2. Menambahkan Kode pada Dokumen
   Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
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

![Screenshot (51)](https://github.com/fajarmrdnt16/Lab3Web/assets/81574674/3ca18d90-40a6-43a1-a453-2f56c60ceda4)

3. Menggabungkan Sel Data
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara horizontal).
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

![Screenshot (52)](https://github.com/fajarmrdnt16/Lab3Web/assets/81574674/4961c526-0910-483b-b09a-82d5521f0af6)

#Membuat Form Di HTML
1. Membuat Form
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

2. Masukan Kode Untuk Membuat Tabel
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

![Screenshot (53)](https://github.com/fajarmrdnt16/Lab3Web/assets/81574674/c4295540-4660-439b-a790-9cb6c32db0b2)

3. Membuat Style Pada Form
   Agar tampilan form lebih menarik dan berwarna, bisa ditambahkan CSS seperti berikut.
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

![Screenshot (54)](https://github.com/fajarmrdnt16/Lab3Web/assets/81574674/e1120f30-c4f9-4b41-b064-f2e39ec4cd05)

#Tugas Dan penyelesaian
1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
   Memasukan kode dibawah pada dokumen.
   <p>Pilih Agama:</p>
         <select>
        <option nama="agama" value="Islam">Islam</option>
        <option nama="agama" value="Kristen">Kristen</option>
        <option nama="agama" value="Budha">Budha</option>
        <option nama="agama" value="Hindu">Hindu</option>
        </select>
        <p>Pilih Jurusan:</p>
        <select name="Jurusan" size="3">        
         <option value="1">Teknik Informatika</option>        
        <option value="2">Manajemen</option>        
        <option value="3">Arsitek</option>        
        <option value="4">Teknik Lingkungan</option>        
        <option value="5">Sistem Informatika</option>        
         </select> 

 ![Screenshot (56)](https://github.com/fajarmrdnt16/Lab3Web/assets/81574674/6d8232b3-5200-4e28-a095-29a2c1066323)
