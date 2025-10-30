# PRAKTIKUM 6: TWITTER BOOTSTRAP

Nama   : Adinda Aulia Nabila Putri

Nim    : 312410309
 
Kelas  : TI.24.A.4 



<img width="816" height="579" alt="Screenshot 2025-10-30 195709" src="https://github.com/user-attachments/assets/e1f350d7-e2c3-4fe2-a652-580328aded13" />


1. Jawabannya

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Refactor Layout Praktikum 4</title>

  <!-- Link Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
        rel="stylesheet" 
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
        crossorigin="anonymous">
</head>

<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark mb-4">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Praktikum 6</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" href="#">Bootstrap</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Portofolio</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Container Utama -->
  <div class="container">

    <!-- Baris Heading -->
    <div class="row mb-4">
      <div class="col-md-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Heading 1</h5>
            <p class="card-text">Deskripsi singkat heading 1.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Heading 2</h5>
            <p class="card-text">Deskripsi singkat heading 2.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Heading 3</h5>
            <p class="card-text">Deskripsi singkat heading 3.</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Baris Konten Utama dan Sidebar -->
    <div class="row">
      <!-- Konten Utama -->
      <div class="col-md-8">
        <div class="card mb-4">
          <div class="card-body">
            <h4 class="card-title">Konten Utama</h4>
            <p class="card-text">
              Ini adalah area untuk artikel atau isi utama website.
              Anda dapat menambahkan teks, gambar, atau elemen lain di sini.
            </p>
          </div>
        </div>
      </div>

      <!-- Sidebar -->
      <div class="col-md-4">
        <div class="card mb-4">
          <div class="card-body">
            <h5 class="card-title">Sidebar</h5>
            <p class="card-text">
              Ini adalah bagian sidebar untuk link tambahan atau informasi lainnya.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Script Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" 
          integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" 
          crossorigin="anonymous"></script>
</body>
</html>
```

  Membuat folder dengan nama ```LAB6_BOOTSTRAP``` dengan file didalamnya ```index.html```. Code ini focus pada penerapan Bootstrap untuk membuat layout halaman web yang responsif dan rapi. Pada elemen ```<head>``` terdapat infomasi dokumen seperti:
  
  * ```meta name="viewport"``` untuk membuat tampilan web responsif di berbagai ukuran layar.
  * ```link``` untuk menampilkan judul di tab browser.


Lalu pada bagian navbar terdapat elemen ```navbar-expand-lg``` yang dimana navbar akan melebar penuh di layar dan berubah menjadi tombol menu dilayar kecil, dan juga ada elemen ```navbar-dark bg-dark``` untuk memberikan warna gelap dan teks putih. 


  Berikut hasil pada Browser 

<img width="1355" height="591" alt="Screenshot 2025-10-30 203127" src="https://github.com/user-attachments/assets/5c358468-e262-4f79-bf3e-15e6b802b286" />



2. Jawabannya

```
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Form Bootstrap</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<div class="container mt-5">
  <h3 class="text-center mb-4">Form Kontak</h3>

  <form>
    <div class="mb-3">
      <label for="nama" class="form-label">Nama Lengkap</label>
      <input type="text" class="form-control" id="nama" placeholder="Masukkan nama Anda">
    </div>

    <div class="mb-3">
      <label for="email" class="form-label">Alamat Email</label>
      <input type="email" class="form-control" id="email" placeholder="nama@contoh.com">
    </div>

    <div class="mb-3">
      <label for="pesan" class="form-label">Pesan</label>
      <textarea class="form-control" id="pesan" rows="3" placeholder="Tulis pesan Anda di sini"></textarea>
    </div>

    <button type="submit" class="btn btn-primary">Kirim</button>
  </form>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

  Membuat file baru di VSCode dengan nama ```bootstrap.html``` pada file ini menampilkan komponen form dari bootstrap supaya tampilan form menjadi rapi, modern, dan responsif. Di file ini terdapat beberapa elemen dan atribut sebagai berikut: 

  * ```<input type="teks">``` untuk memasukkan nama pengguna. Di lengkapi label "Naman Lengkap" dan terdapat atribut ```placholder``` sebagai petunjuk pengisian. 

  * ```<input type="email">``` agar hanya menerima format email yang valid. label dan ```placeholder``` digunakan untuk memberikan panduan pengisian.

  * ```<textarea>```  untuk menulis pesan atau komentar. dilengkapi label dan ```placeholder``` agar pengguna tahu fungsi kolom ini.

  * ```<button type="submit" class="btn btn-primary">kirim</button>``` tombol ini akan mengirim data form ktika ditekan dengan gaya tombol baru khas Bootstrap.


 Berikut hasil pada Browser 

<img width="1361" height="645" alt="Screenshot 2025-10-30 205013" src="https://github.com/user-attachments/assets/2e4cf926-ae6f-4fd4-9664-dffbfcdaa629" />



3. Jawabannya

```
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - Adinda Aulia</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
  <div class="container">
    <a class="navbar-brand" href="#">Adinda Aulia Nabila Putri</a>
  </div>
</nav>

<!-- Tentang Saya -->
<div class="container my-5">
  <div class="row align-items-center">
    <div class="col-md-4">
      <img src="https://picsum.photos/300" alt="Foto Saya" class="img-fluid rounded">
    </div>
    <div class="col-md-8">
      <h2>Adinda Aulia Nabila Putri</h2>
      <p>Hai saya Adinda Aulia Nabila Putri Mahasiswa Teknik Informatika yang memiliki keterarikan dengan dunia teknologi.</p>
    </div>
  </div>
</div>

<!-- Portfolio -->
<div class="container my-5">
  <h3 class="text-center mb-4">Portfolio Saya</h3>
  <div class="row">
    <div class="col-md-4 mb-3">
      <div class="card">
        <img src="https://picsum.photos/400/200" class="card-img-top" alt="Project 1">
        <div class="card-body">
          <h5 class="card-title">Proyek 1</h5>
          <p class="card-text">Website profil menggunakan HTML dan Bootstrap.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4 mb-3">
      <div class="card">
        <img src="https://picsum.photos/401/200" class="card-img-top" alt="Project 2">
        <div class="card-body">
          <h5 class="card-title">Proyek 2</h5>
          <p class="card-text">Form login interaktif dengan validasi JavaScript.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4 mb-3">
      <div class="card">
        <img src="https://picsum.photos/402/200" class="card-img-top" alt="Project 3">
        <div class="card-body">
          <h5 class="card-title">Proyek 3</h5>
          <p class="card-text">Dashboard admin responsif menggunakan Bootstrap Grid.</p>
        </div>
      </div>
    </div>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

 Membuat file baru dengan nama ```portfolio.html``` pada file ini menampilkan informasi tentang profil pribadi. Tujuan pembuatan halaman ini untuk memperkenalkan diri dan menampilkan hasil karya dalam bidang Teknik Informatika.


 Berikut hasil pada Browser 

<img width="1336" height="709" alt="Screenshot 2025-10-30 205705" src="https://github.com/user-attachments/assets/3ca6cb27-d3a8-4011-ba1d-417a199ef783" />

