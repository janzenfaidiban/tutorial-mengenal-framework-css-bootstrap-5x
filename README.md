# Mengenal Framework CSS Bootstrap 5 x

Bootstrap merupakan Framework CSS yang tersedia secara gratis bagi para pengembang / developer web di dunia.

Melalui tutorial ini diperkenalkan apa itu bootstrap dan bagaimana menerapkan bootstrap dalam proyek pengembangan website melalui berbagai referensi belajar yang telah tersedia.

<a href="https://youtu.be/tIBDSOzLmdo">Tampilkan Video</a> 
<br>
<br>
<a href="https://janzenfaidiban.github.io/tutorial-mengenal-framework-css-bootstrap-5x/">Tampilkan Demo</a>


## Penerapan Bootstrap menggunakan link CDN

<img src="https://raw.githubusercontent.com/janzenfaidiban/tutorial-mengenal-framework-css-bootstrap-5x/main/_screenshot/bootstrap-cdn.png" width="800px">

Membuthkan koneksi internet agar kita bisa gunakan bootstrap link CDN

```html
<!DOCTYPE html>
<html>
<head>
	<title>Bootstrap CDN</title>

	<!-- CSS BOOTSTRAP -->
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">

</head>
<body>

	<!-- .container start-->
	<!-- .container end-->

	<!-- footer start -->
	<!-- footer end -->

	<!-- JAVASCRIPT BOOTSTRAP -->
	<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3" crossorigin="anonymous"></script>

</body>
</html>
```

## Penerapan Bootstrap menggunakan file Download

<img src="https://raw.githubusercontent.com/janzenfaidiban/tutorial-mengenal-framework-css-bootstrap-5x/main/_screenshot/bootstrap-download.png" width="800px">


File atau folder bootstrap perlu di download terlebih dahulu ke dalam folder project kemudian bisa digunakan.

```html
<!DOCTYPE html>
<html>
<head>
	<title>Bootstrap Download</title>

	<!-- CSS BOOTSTRAP -->
	<link rel="stylesheet" type="text/css" href="./css/bootstrap.min.css">

</head>
<body>

	<!-- .container start -->
	<!-- .container end -->

	<!-- footer start -->
	<!-- footer end -->

	<!-- JAVASCRIPT BOOTSTRAP -->
	<script src="./js/bootstrap.bundle.js"></script>

</body>
</html>
```
