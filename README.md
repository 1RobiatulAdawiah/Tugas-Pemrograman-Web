# Tugas-Pemrograman-Web
Tugas pemrograman web 1 (18 September 2024) 
By Robiatul Adawiah / Informatika 3-A / 231730028

## Here is the list that is needed
```
fontawesome.com
https://getbootstrap.com/docs/5.0/components/according/
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" 
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
```
## Head Syntax
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>company profile</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" 
    rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" 
    crossorigin="anonymous">
    <link rel="stylesheet"
    href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
    integrity="sha384-AYMEC3Yw5cVb3ZcuHt0A93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p"
    crossorigin="anonymous">
    <link rel="stylesheet" href="style.css"> 
    <script src="https://kit.fontawesome.com/860c0beb9f.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYMEC3Yw5cVb3ZcuHt0A93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p"
    crossorigin="anonymous">
  </head>
```
## Body -> Navbar Syntax
```
<body>
  <!--navigasi-->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark shadow-lg fixed-top">
        <div class="container">
          <a class="navbar-brand" href="#">Beranda Robiatul</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse text-right" id="navbarText">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" href="#layanan">Layanan</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#portofolio">Portofolio</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#tentang">Tentang</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#staff">Staff</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#kontak">Kontak kami</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
```
## Body -> Banner Syntax
```
<div class="container-fluid banner">
        <div class="container text-center">
          <h4 class="display-6">Selamat Datang di Website Kami</h4>
          <h3 class="display-1" > HALOOOOOOOO</h3>
          <a href="#layanan">
            <button type="button" class="btn btn-danger btn-lg"> cek layanan</button>
          </a>
        </div>
      </div>
```
## Body -> Layanan Syntax
```
<div class="container-fluid layanan pt-5 pb-5">
        <div class="container text-center">
          <h2 class="display-3" id="layanan">Layanan</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel, dolores.</p>
          <div class="row pt-4">
            <div class="col-md-4">
              <span class="lingkaran"><i class="fas fa-code fa-5x"></i></span>
              
              <h3 class="mt-3">programing</h3>
              <p>Programming adalah sebuah proses untuk membuat program di komputer. Program yang dimaksud bisa berupa software, website, aplikasi, dan masih banyak lagi. </p>
            </div>

            <div class="col-md-4">
              <span class="lingkaran"><i class="fas fa-palette fa-5x"></i></span>
              
              <h3 class="mt-3">Design thinking</h3>
              <p>adalah suatu metode yang dilakukan untuk memecahkan suatu masalah dengan cara yang kreatif dan praktis. Jadi, dalam sebuah tim pengembangan perangkat lunak, tim akan mencari dan memahami permasalahan yang dialami oleh pengguna dan mendefinisikan solusi apa yang cocok serta efektif untuk menyelesaikan masalah tersebut.</p>
            </div>

            <div class="col-md-4">
              <span class="lingkaran"><i class="fas fa-network-wired fa-5x"></i></span>
              
              <h3 class="mt-3">Networking</h3>
              <p>teknik pemrograman yang memungkinkan komputer untuk berkomunikasi dan berbagi informasi melalui jaringan komputer. Ini termasuk membangun aplikasi yang berkomunikasi menggunakan protokol jaringan seperti TCP/IP, UDP, dan HTTP.</p>
            </div>
          </div>
        </div>
      </div>
```
## Body -> Portofolio Syntax
```
<div class="container-fluid pt-5 pb-5 bg-light">
        <div class="container text-center">
          <h2 class="display-3" id="portofolio">portofolio</h2>
          <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae, sunt aperiam fuga nisi sed tempora accusantium facilis reprehenderit pariatur officiis?
          </p>
          <div class="row pt-4 gx-4 gy-4">
            <div class="col-md-4">
              <div class="card">
                <img src="https://hariannusantara.com/wp-content/uploads/2019/05/KUMPULAN-GAMBAR-KUCING-LUCU-DAN-IMUT-4.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>
            <div class="col-md-4">
              <div class="card">
                <img src="https://blog.eikontechnology.com/wp-content/uploads/2018/08/perkembangan_teknologi_masa_kini.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>
           <div class="col-md-4">
              <div class="card">
                <img src="https://i1.wp.com/www.maxmanroe.com/vid/wp-content/uploads/2018/12/Pengertian-Teknologi-Adalah.jpg?fit=700%2C379&ssl=1" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://www.klikmania.net/wp-content/uploads/2018/10/Masa-Depan-Dunia-di-Tangan-AI.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://digitalbisa.id/uploads/articles/teknologi-digital-sebagai-salah-satu-kendaraan-menuju-kemajuan-bangsa-PusEWcDLE1.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://media.istockphoto.com/photos/future-financial-technology-controlled-by-ai-robot-using-machine-and-picture-id1273360297?k=20&m=1273360297&s=612x612&w=0&h=UtOS_HSItYfiH6cC2Uy7dY-b12sLKUS756OaEl_oOLQ=" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
```
## Body -> Tentang
```
<div class="container-fluid pt-5 pb-5">
        <div class="container">
          <h2 class="display-3 text-center" id="tentang">Tentang</h2>
          <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, adipisci.</p>
          <div class="clearfix pt-5"><img src="https://media.istockphoto.com/id/1385753861/id/foto/gambar-unit-pemrosesan-pusat-teknologi-pemrosesan-kerja-teknologi-komputer-di-tempat-kerja-cpu.jpg?s=612x612&w=is&k=20&c=YfV-pC_rKxB76phbqUnzscIzxU1eYkAxU8OTaWKjWRg=" class="col-md-6 float-md-end mb-3 crop-img" width="300" height="300"/>
          <p> CPU atau Central Processing Unit adalah bagian utama dari komputer yang menjalankan tugas khusus sehingga perangkatmu bisa berjalan sesuai dengan perintah yang dimasukkan.</p>
          <p>Tugas khususnya adalah mengolah data yang diterima dari komponen-komponen lain, seperti memori, sistem operasi, program aplikasi dan sebagainya.</p>
          <p>CPU terletak berada di papan sirkuit (motherboard) dan tersusun dari serangkaian transistor yang akan mengeksekusi instruksi lewat operasi bilangan biner.</p>
        </div>
        </div>
      </div>
```
## Body -> Staff Syntax
```
<div class="container-fluid pt-5 pb-5 bg-light">
        <div class="container text-center">
          <h2 class="display-3" id="staff">Staff Kamii</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, beatae earum odio veritatis tenetur porro voluptas ipsa ratione inventore alias.</p>
          <div class="row pt-4 gx-4">
            <div class="col-md-4 text-center staff">
              <img src="https://i.pinimg.com/originals/9f/6d/11/9f6d11082506439f0b9d316ecbdb36dc.jpg"
              class="rounded-circle mb-3"
              />
              <h4>Lupi</h4>
              <p>web Development</p>
              <p>
                <a href="" class="social"><i class="fab fa-twitter"></i></a>
                <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
                <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
              </p>
            </div>
<div class="col-md-4 text-center staff">
              <img src="https://png.pngtree.com/png-clipart/20221231/original/pngtree-cartoon-style-female-user-profile-icon-vector-illustraton-png-image_8836450.png"
              class="rounded-circle mb-3"
              />
              <h4>wijaya</h4>
              <p>web Designer</p>
              <p>
                <a href="" class="social"><i class="fab fa-twitter"></i></a>
                <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
                <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
              </p>
            </div>
<div class="col-md-4 text-center staff">
              <img src="https://s3.amazonaws.com/cms-assets.tutsplus.com/uploads/users/810/profiles/19338/profileImage/profile-square-extra-small.png"
              class="rounded-circle mb-3"
              />
              <h4>Marsu</h4>
              <p>Network Engineer</p>
              <p>
                <a href="" class="social"><i class="fab fa-twitter"></i></a>
                <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
                <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
              </p>
            </div>
          </div>
        </div>
      </div>
```
## Body -> Client Syntax
```
<div class="container-fluid client pt-5 pb-5">
        <div class="container text-center">
          <div class="row pt-4 gx-4 gy-4">
            <div class="col">
              <img src="https://static.vecteezy.com/system/resources/previews/022/101/068/original/microsoft-logo-transparent-free-png.png"/>
            </div>
            <div class="col">
              <img src="https://static.vecteezy.com/system/resources/previews/002/445/918/original/social-media-facebook-logo-icon-free-vector.jpg"/>
            </div>
            <div class="col">
              <img src="https://www.1min30.com/wp-content/uploads/2018/04/Couleur-logo-IBM.jpg"/>
            </div>
            <div class="col">
              <img src="https://static.vecteezy.com/system/resources/previews/023/986/900/original/linkedin-logo-linkedin-logo-transparent-linkedin-icon-transparent-free-free-png.png"/>
            </div>
            <div class="col">
              <img src="https://freelogopng.com/images/all_img/1657955447google-logo-black-and-white.png"/>
            </div>
            </div>
          </div>
        </div>
       </div>
```
## Body -> Kontak Syntax
```
 <div class="container-fluid pt-5 pb-5 kontak">
          <div class="container">
            <h2 class="display-3 text-center" id="kontak">kontak kami</h2>
            <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam, at.</p>
            <div class="row pb-3">
              <div class="col-md-6">
                <input class="form-control form-control-lg mb-3" type="text" placeholder="Nama"/>
                <input class="form-control form-control-lg mb-3" type="text" placeholder="Email"/>
                <input class="form-control form-control-lg mb-3" type="text" placeholder="No phone"/>
              </div>
              <div class="col-md-6">
                <textarea class="form-control form-control-lg" rows="5"></textarea>
              </div>
            </div>
            <div class="col-md-3 mx-auto text-center">
              <button type="button" class="btn btn-danger btn-lg">Kirim Pesan</button>
            </div>
          </div>
        </div>
        <div class="container text-center pt-5 pb-5">
          All Rights Reserved &copy; 2024
        </div>

</body>
</html>
```
## Full Version Syntax
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>company profile</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" 
    rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" 
    crossorigin="anonymous">
    <link rel="stylesheet"
    href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
    integrity="sha384-AYMEC3Yw5cVb3ZcuHt0A93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p"
    crossorigin="anonymous">
    <link rel="stylesheet" href="style.css"> 
    <script src="https://kit.fontawesome.com/860c0beb9f.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYMEC3Yw5cVb3ZcuHt0A93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p"
    crossorigin="anonymous">
  </head>
<body>
  <!--navigasi-->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark shadow-lg fixed-top">
        <div class="container">
          <a class="navbar-brand" href="#">Beranda Robiatul</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse text-right" id="navbarText">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" href="#layanan">Layanan</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#portofolio">Portofolio</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#tentang">Tentang</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#staff">Staff</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#kontak">Kontak kami</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <!--banner-->
      <div class="container-fluid banner">
        <div class="container text-center">
          <h4 class="display-6">Selamat Datang di Website Kami</h4>
          <h3 class="display-1" > HALOOOOOOOO</h3>
          <a href="#layanan">
            <button type="button" class="btn btn-danger btn-lg"> cek layanan</button>
          </a>
        </div>
      </div>
      <!--layanan-->
      <div class="container-fluid layanan pt-5 pb-5">
        <div class="container text-center">
          <h2 class="display-3" id="layanan">Layanan</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel, dolores.</p>
          <div class="row pt-4">
            <div class="col-md-4">
              <span class="lingkaran"><i class="fas fa-code fa-5x"></i></span>
              
              <h3 class="mt-3">programing</h3>
              <p>Programming adalah sebuah proses untuk membuat program di komputer. Program yang dimaksud bisa berupa software, website, aplikasi, dan masih banyak lagi. </p>
            </div>

            <div class="col-md-4">
              <span class="lingkaran"><i class="fas fa-palette fa-5x"></i></span>
              
              <h3 class="mt-3">Design thinking</h3>
              <p>adalah suatu metode yang dilakukan untuk memecahkan suatu masalah dengan cara yang kreatif dan praktis. Jadi, dalam sebuah tim pengembangan perangkat lunak, tim akan mencari dan memahami permasalahan yang dialami oleh pengguna dan mendefinisikan solusi apa yang cocok serta efektif untuk menyelesaikan masalah tersebut.</p>
            </div>

            <div class="col-md-4">
              <span class="lingkaran"><i class="fas fa-network-wired fa-5x"></i></span>
              
              <h3 class="mt-3">Networking</h3>
              <p>teknik pemrograman yang memungkinkan komputer untuk berkomunikasi dan berbagi informasi melalui jaringan komputer. Ini termasuk membangun aplikasi yang berkomunikasi menggunakan protokol jaringan seperti TCP/IP, UDP, dan HTTP.</p>
            </div>
          </div>
        </div>
      </div>
      <!--portofolio-->
      <div class="container-fluid pt-5 pb-5 bg-light">
        <div class="container text-center">
          <h2 class="display-3" id="portofolio">portofolio</h2>
          <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae, sunt aperiam fuga nisi sed tempora accusantium facilis reprehenderit pariatur officiis?
          </p>
          <div class="row pt-4 gx-4 gy-4">
            <div class="col-md-4">
              <div class="card">
                <img src="https://hariannusantara.com/wp-content/uploads/2019/05/KUMPULAN-GAMBAR-KUCING-LUCU-DAN-IMUT-4.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://blog.eikontechnology.com/wp-content/uploads/2018/08/perkembangan_teknologi_masa_kini.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://i1.wp.com/www.maxmanroe.com/vid/wp-content/uploads/2018/12/Pengertian-Teknologi-Adalah.jpg?fit=700%2C379&ssl=1" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://www.klikmania.net/wp-content/uploads/2018/10/Masa-Depan-Dunia-di-Tangan-AI.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://digitalbisa.id/uploads/articles/teknologi-digital-sebagai-salah-satu-kendaraan-menuju-kemajuan-bangsa-PusEWcDLE1.jpg" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="card">
                <img src="https://media.istockphoto.com/photos/future-financial-technology-controlled-by-ai-robot-using-machine-and-picture-id1273360297?k=20&m=1273360297&s=612x612&w=0&h=UtOS_HSItYfiH6cC2Uy7dY-b12sLKUS756OaEl_oOLQ=" 
                class="card-img-top"
                width="200"
                height="200">
                <div class="card-body">
                  <h5 class="card-title">Lorem, ipsum.</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus eos laudantium ex quaerat aliquid repellendus.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!--tentang-->
      <div class="container-fluid pt-5 pb-5">
        <div class="container">
          <h2 class="display-3 text-center" id="tentang">Tentang</h2>
          <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, adipisci.</p>
          <div class="clearfix pt-5"><img src="https://media.istockphoto.com/id/1385753861/id/foto/gambar-unit-pemrosesan-pusat-teknologi-pemrosesan-kerja-teknologi-komputer-di-tempat-kerja-cpu.jpg?s=612x612&w=is&k=20&c=YfV-pC_rKxB76phbqUnzscIzxU1eYkAxU8OTaWKjWRg=" class="col-md-6 float-md-end mb-3 crop-img" width="300" height="300"/>
          <p> CPU atau Central Processing Unit adalah bagian utama dari komputer yang menjalankan tugas khusus sehingga perangkatmu bisa berjalan sesuai dengan perintah yang dimasukkan.</p>
          <p>Tugas khususnya adalah mengolah data yang diterima dari komponen-komponen lain, seperti memori, sistem operasi, program aplikasi dan sebagainya.</p>
          <p>CPU terletak berada di papan sirkuit (motherboard) dan tersusun dari serangkaian transistor yang akan mengeksekusi instruksi lewat operasi bilangan biner.</p>
        </div>
        </div>
      </div>
      <!--staff-->
      <div class="container-fluid pt-5 pb-5 bg-light">
        <div class="container text-center">
          <h2 class="display-3" id="staff">Staff Kamii</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, beatae earum odio veritatis tenetur porro voluptas ipsa ratione inventore alias.</p>
          <div class="row pt-4 gx-4">
            <div class="col-md-4 text-center staff">
              <img src="https://i.pinimg.com/originals/9f/6d/11/9f6d11082506439f0b9d316ecbdb36dc.jpg"
              class="rounded-circle mb-3"
              />
              <h4>Lupi</h4>
              <p>web Development</p>
              <p>
                <a href="" class="social"><i class="fab fa-twitter"></i></a>
                <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
                <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
              </p>
            </div>

            <div class="col-md-4 text-center staff">
              <img src="https://png.pngtree.com/png-clipart/20221231/original/pngtree-cartoon-style-female-user-profile-icon-vector-illustraton-png-image_8836450.png"
              class="rounded-circle mb-3"
              />
              <h4>wijaya</h4>
              <p>web Designer</p>
              <p>
                <a href="" class="social"><i class="fab fa-twitter"></i></a>
                <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
                <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
              </p>
            </div>

            <div class="col-md-4 text-center staff">
              <img src="https://s3.amazonaws.com/cms-assets.tutsplus.com/uploads/users/810/profiles/19338/profileImage/profile-square-extra-small.png"
              class="rounded-circle mb-3"
              />
              <h4>Marsu</h4>
              <p>Network Engineer</p>
              <p>
                <a href="" class="social"><i class="fab fa-twitter"></i></a>
                <a href="" class="social"><i class="fab fa-facebook-f"></i></a>
                <a href="" class="social"><i class="fab fa-linkedin-in"></i></a>
              </p>
            </div>
          </div>
        </div>
      </div>
      <!-- client -->
       <div class="container-fluid client pt-5 pb-5">
        <div class="container text-center">
          <div class="row pt-4 gx-4 gy-4">
            <div class="col">
              <img src="https://static.vecteezy.com/system/resources/previews/022/101/068/original/microsoft-logo-transparent-free-png.png"/>
            </div>
            <div class="col">
              <img src="https://static.vecteezy.com/system/resources/previews/002/445/918/original/social-media-facebook-logo-icon-free-vector.jpg"/>
            </div>
            <div class="col">
              <img src="https://www.1min30.com/wp-content/uploads/2018/04/Couleur-logo-IBM.jpg"/>
            </div>
            <div class="col">
              <img src="https://static.vecteezy.com/system/resources/previews/023/986/900/original/linkedin-logo-linkedin-logo-transparent-linkedin-icon-transparent-free-free-png.png"/>
            </div>
            <div class="col">
              <img src="https://freelogopng.com/images/all_img/1657955447google-logo-black-and-white.png"/>
            </div>
            </div>
          </div>
        </div>
       </div>
       <!-- kontak -->
        <div class="container-fluid pt-5 pb-5 kontak">
          <div class="container">
            <h2 class="display-3 text-center" id="kontak">kontak kami</h2>
            <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam, at.</p>
            <div class="row pb-3">
              <div class="col-md-6">
                <input class="form-control form-control-lg mb-3" type="text" placeholder="Nama"/>
                <input class="form-control form-control-lg mb-3" type="text" placeholder="Email"/>
                <input class="form-control form-control-lg mb-3" type="text" placeholder="No phone"/>
              </div>
              <div class="col-md-6">
                <textarea class="form-control form-control-lg" rows="5"></textarea>
              </div>
            </div>
            <div class="col-md-3 mx-auto text-center">
              <button type="button" class="btn btn-danger btn-lg">Kirim Pesan</button>
            </div>
          </div>
        </div>
        <div class="container text-center pt-5 pb-5">
          All Rights Reserved &copy; 2024
        </div>

</body>
</html>
```
