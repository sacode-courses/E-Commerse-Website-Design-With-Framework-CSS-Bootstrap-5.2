# Day09 - 📚 Desain Konten Produk

## Starter template

Copy & paste struktur dasar HTML dan taru di file proyek baru untuk memulai desain.

Struktur dasar HTML berikut sudah tercantum Bootstrap 5.x CSS, Bootstrap 5.x JavaScript, Font Awesome 6.x dan Google Font

```html
<!DOCTYPE html>
<html>

<head>
    <title>SaZhop</title>
    
    <!-- Bootstrap CSS only -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">

    <!-- Font Awesome CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css"
        integrity="sha512-1sCRPdkRXhBV2PBLUdRb4tMg1w2YPf37qatUFeS7zlBy7jJI8Lf4VHwWfZZfpXtYSLy85pkm9GaYVYMfw5BC1A=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />

    <!-- Google Font -->
    <link href='https://fonts.googleapis.com/css?family=Quicksand' rel='stylesheet'>

    <!-- Style -->
    <link href='./assets/css/style.css' rel='stylesheet'>

</head>

<body>

    <!-- TOP BAR START-->
    <!-- TOP BAR END -->

    <!-- HEADER START -->
    <!-- HEADER END -->

    <!-- BANNER START -->
    <!-- BANNER END -->

    <!-- CONTENT START -->
    <!-- CONTENT END -->

    <!-- FOOTER START -->
    <!-- FOOTER END -->

    <!-- Bootstrap JavaScript Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js" crossorigin="anonymous"></script>

</body>

</html>
```

## Section Produk

<img src="https://github.com/sacode-courses/e-commerse/blob/day09/_screenshot/produk.png" width="500px">


## Bagian Heading

```html
<!-- .row start -->
<div class="row my-5">

    <!-- .col start -->
    <div class="col-6 mx-auto my-5 text-center">
        <h1 class="display-5 fw-bolder text-success">
            <i class="fa-solid fa-seedling me-2"></i> Produk
        </h1>
        <p class="text-muted pt-4">Berbagai Jenis Produk Sayuran dan Buahan Segar <br> Dengan Harga Yang
            Sangat Terjangkau.</p>
    </div>
    <!-- .col end -->

</div>
<!-- .row end -->
```

## Bagian Produk Item

Template awal dengan komentar HTML. Sebelum ditambahkan elemen HTML.

```html
<!-- PRODUCT ITEM START -->
<div class="col-lg-3 mb-5">

    <!-- card start -->
        <!-- card image start-->
        <!-- card image end-->

        <!-- card header start-->
        <!-- card header end-->

        <!-- card body start-->
        <!-- card body end-->

        <!-- card footer start-->
        <!-- card footer end-->
    <!-- card end -->

</div>
<!-- PRODUCT ITEM END -->
```

Setelah ditambahkan elemen HTML lengkap.

```html
<!-- PRODUCT ITEM START -->
<div class="col-lg-3 mb-5">

    <!-- card start -->
    <div class="card border shadow">

        <!-- card image start-->
        <img src="./assets/img/thumbnail-1.jpg" class="card-img-top">
        <!-- card image end-->

        <!-- card header start-->
        <div class="card-header px-4">
            <a href="#" class="badge bg-warning link-success text-decoration-none">Sayur</a>
            <h1 class="display-5 card-title fw-bolder text-success">Wortel</h1>
        </div>
        <!-- card header end-->

        <!-- card body start-->
        <div class="card-body px-4">
            
            <small class="my-2 d-block">
                <a href="#" class="link-success"><i class="fa-regular fa-star"></i></a>
                <a href="#" class="link-success"><i class="fa-regular fa-star"></i></a>
                <a href="#" class="link-success"><i class="fa-solid fa-star"></i></a>
                <a href="#" class="link-success"><i class="fa-solid fa-star"></i></a>
                <a href="#" class="link-success"><i class="fa-solid fa-star"></i></a>
            </small>
            
            <p class="card-text text-secondary">Sayur segar dengan harga sangat terjangkau dengan
                pengiriman yang cepat.</p>

            <div class="d-flex justify-content-between">
                <h3 class="text-success fw-bolder">
                    Rp. 15.000,-
                </h3>
                <h6 class="fs-6 text-decoration-line-through text-danger">
                    Rp. 25.000,-
                </h6>
            </div>

        </div>
        <!-- card body end-->

        <!-- card footer start-->
        <div class="card-footer px-4 py-4">

            <!-- tombol keranjang -->
            <form action="./keranjang-belanja.html">
                <button class="btn btn-success btn-lg text-warning w-100 mb-2 py-3">
                    <i class="fa-solid fa-cart-shopping"></i> Masuk Keranjang
                </button>
            </form>

            <form action="./detail-produk.html">
                <!-- tombol detail -->
                <button class="btn btn-lg bg-light link-success w-100 py-3">
                    <i class="fa-solid fa-eye"></i> Detail
                </button>
            </form>

        </div>
        <!-- card footer end-->

    </div>
    <!-- card end -->

</div>
<!-- PRODUCT ITEM END -->
```

## Bagian Pagination

```html
<!-- .row start -->
<div class="row">

    <!-- .col start -->
    <div class="col-12">
        <nav aria-label="navigation">
            <ul class="pagination pagination-lg justify-content-center">
                <li class="page-item disabled">
                    <a class="page-link">Kembali</a>
                </li>
                <li class="page-item "><a class="page-link link-light bg-success" href="#">1</a></li>
                <li class="page-item"><a class="page-link link-success" href="#">2</a></li>
                <li class="page-item"><a class="page-link link-success" href="#">3</a></li>
                <li class="page-item">
                    <a class="page-link link-success" href="#">Selanjutnya</a>
                </li>
            </ul>
        </nav>
    </div>
    <!-- .col end -->

</div>
<!-- .row end --> 
```