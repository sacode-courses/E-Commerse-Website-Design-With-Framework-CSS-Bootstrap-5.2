# Day10 - 📚 Desain Keranjang Belanja

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

## Section Keranjang Belanja

<img src="https://github.com/sacode-courses/e-commerse/blob/day10/_screenshot/keranjang-belanja.png" width="500px">

## Bagian Heading

```html
<!-- .row start -->
<div class="row my-5">

    <!-- .col start -->
    <div class="col-6 mx-auto my-5 text-center">
        <h1 class="display-4 fw-bolder text-success">
            <i class="fa-solid fa-cart-shopping me-2"></i> Keranjang Belanja
        </h1>
        <p class="text-muted pt-4">Berbagai Jenis Produk Sayuran dan Buahan Segar <br> Dengan Harga Yang Sangat Terjangkau.</p>
    </div>
    <!-- .col end -->

</div>
<!-- .row end -->
```

## Bagian Keranjang Belanja

Template awal dengan komentar HTML. Sebelum ditambahkan elemen HTML.

```html
<!-- .row start -->

    <!-- .col start -->

        <!-- .card start -->

            <!-- .card-body start -->
            <!-- .card-body end -->
            
        <!-- .card end -->

    <!-- .col end -->

    <!-- .col start -->

        <!-- .list-group start -->
        <!-- .list-group end -->

        <!-- .btn start -->
        <!-- .btn end -->
        
    <!-- .col end -->

<!-- .row end -->
```

```html
<!-- .row start -->
<div class="row">

    <!-- .col start -->
    <div class="col-xl-8 col-lg-8 ">
        
        <!-- .card start -->
        <div class="card">
            <!-- .card-body start -->
            <div class="card-body">

                <div class="d-flex text-muted py-3">
                    <p class="me-auto">Ada <b>3 produk</b> di dalam keranjang</p>
                    <a href="#" class="text-decoration-none link-success">
                        <i class="fa-solid fa-trash me-2"></i> Kosongkan keranjang
                    </a>
                </div>

                <table class="table table-striped table-hover">
                    <thead>
                        <tr>
                            <th class="py-3 bg-success text-warning fw-bolder">Produk</th>
                            <th class="py-3 bg-success text-warning fw-bolder">Harga</th>
                            <th class="py-3 bg-success text-warning fw-bolder text-center">Hapus</th>
                        </tr>
                    </thead>
                    <tbody>

                        <!-- product item start -->
                        <tr>
                            <td class="d-flex d-grid gap-4">
                                <div>
                                    <input type="checkbox" class="form-check-input">
                                </div>
                                <div>
                                    <img src=".//assets/img/thumbnail-1.jpg" alt="Produk"
                                        class="img img-thumbnail" width="150px;">
                                </div>
                                <div>
                                    <h5 class="fw-bolder text-success">Wortel</h5>
                                    <small class="pt-2">
                                        <a href="#" class="link-success"><i class="fa-regular fa-star"></i></a>
                                        <a href="#" class="link-success"><i class="fa-regular fa-star"></i></a>
                                        <a href="#" class="link-success"><i class="fa-solid fa-star"></i></a>
                                        <a href="#" class="link-success"><i class="fa-solid fa-star"></i></a>
                                        <a href="#" class="link-success"><i class="fa-solid fa-star"></i></a>
                                    </small>
                                </div>
                            </td>
                            <td class="fw-bolder">
                                Rp. 20.000,-
                            </td>
                            <td class="text-center">
                                <a href="#" class="link-success"><i class="fa-solid fa-trash"></i></a>
                            </td>
                        </tr>
                        <!-- product item end -->

                        <!-- product item start -->
                        <tr>
                            <td class="d-flex d-grid gap-4">
                                <div>
                                    <input type="checkbox" class="form-check-input">
                                </div>
                                <div>
                                    <img src=".//assets/img/thumbnail-2.jpg" alt="Produk"
                                        class="img img-thumbnail" width="150px;">
                                </div>
                                <div>
                                    <h5 class="fw-bolder text-success">Paprika</h5>
                                    <small class="pt-2">
                                        <a href="#" class="link-success"><i class="fa-regular fa-star"></i></a>
                                        <a href="#" class="link-success"><i class="fa-regular fa-star"></i></a>
                                        <a href="#" class="link-success"><i class="fa-solid fa-star"></i></a>
                                        <a href="#" class="link-success"><i class="fa-solid fa-star"></i></a>
                                        <a href="#" class="link-success"><i class="fa-solid fa-star"></i></a>
                                    </small>
                                </div>
                            </td>
                            <td class="fw-bolder">
                                Rp. 20.000,-
                            </td>
                            <td class="text-center">
                                <a href="#" class="link-success"><i class="fa-solid fa-trash"></i></a>
                            </td>
                        </tr>
                        <!-- product item end -->

                        <!-- product item start -->
                        <tr>
                            <td class="d-flex d-grid gap-4">
                                <div>
                                    <input type="checkbox" class="form-check-input">
                                </div>
                                <div>
                                    <img src=".//assets/img/thumbnail-3.jpg" alt="Produk"
                                        class="img img-thumbnail" width="150px;">
                                </div>
                                <div>
                                    <h5 class="fw-bolder text-success">Jus Mangga</h5>
                                    <small class="pt-2">
                                        <a href="#" class="link-success"><i class="fa-regular fa-star"></i></a>
                                        <a href="#" class="link-success"><i class="fa-regular fa-star"></i></a>
                                        <a href="#" class="link-success"><i class="fa-solid fa-star"></i></a>
                                        <a href="#" class="link-success"><i class="fa-solid fa-star"></i></a>
                                        <a href="#" class="link-success"><i class="fa-solid fa-star"></i></a>
                                    </small>
                                </div>
                            </td>
                            <td class="fw-bolder">
                                Rp. 20.000,-
                            </td>
                            <td class="text-center">
                                <a href="#" class="link-success"><i class="fa-solid fa-trash"></i></a>
                            </td>
                        </tr>
                        <!-- product item end -->

                    </tbody>
                </table>
            </div>
            <!-- .card-body end -->
        </div>
        <!-- .card end -->
    </div>
    <!-- .col end -->

    <!-- .col start -->
    <div class="col-xl-4 col-lg-4 mt-5 mt-md-5 mt-lg-0 mt-xl-0">

        <!-- .list-group start -->
        <ul class="list-group">
            <li class="list-group-item d-flex justify-content-between p-4">
                <div>
                    Sub Total
                </div>
                <div class="fw-bolder text-success">
                    Rp 20.000
                </div>
            </li>
            <li class="list-group-item d-flex justify-content-between p-4">
                <div>
                    Pengiriman
                </div>
                <div class="fw-bolder text-success">
                    Free
                </div>
            </li>
            <li class="list-group-item d-flex justify-content-between p-4">
                <div>
                    Tujuan
                </div>
                <div class="fw-bolder text-success">
                    Biak
                </div>
            </li>
            <li class="list-group-item d-flex justify-content-between p-4 bg-success text-warning">
                <div class="fw-bold">
                    Total
                </div>
                <div class="fw-bolder">
                    Rp 20.000
                </div>
            </li>
        </ul>
        <!-- .list-group end -->

        <!-- .btn start -->
        <a href="#" class="btn btn-lg btn-success text-warning fw-bolder w-100 py-4 mt-4">
            <i class="fa-solid fa-cart-shopping me-2"></i> Proses Sekarang
        </a>
        <!-- .btn end -->

    </div>
    <!-- .col end -->
</div>
<!-- .row end -->
```