# practical-12
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Bloom Pots Shop</title>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<style>
body {
    font-family: 'Segoe UI';
    background: #f3f8f4;
}

/* Navbar */
.navbar {
    background: #ffffff;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

/* Carousel */
.carousel img {
    height: 500px;
    object-fit: cover;
}

/* Hero */
.hero-text {
    position: absolute;
    top: 40%;
    left: 10%;
    color: white;
}
.hero-text h1 {
    font-size: 50px;
    font-weight: bold;
}

/* Cards */
.card {
    border-radius: 15px;
    overflow: hidden;
    transition: 0.4s;
    border: none;
}
.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 25px rgba(0,0,0,0.2);
}
.card img {
    height: 220px;
    object-fit: cover;
}

/* Buttons */
.btn {
    border-radius: 25px;
}

/* Cart Box */
.cart-box {
    background: white;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

/* Footer */
footer {
    background: #1c3b2a;
    color: white;
}
</style>
</head>

<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg navbar-light">
<div class="container">
<a class="navbar-brand fw-bold">🌿 Bloom Pots</a>
<ul class="navbar-nav ms-auto">
<li class="nav-item"><a class="nav-link active">Home</a></li>
<li class="nav-item"><a class="nav-link">Shop</a></li>
<li class="nav-item"><a class="nav-link">Cart</a></li>
<li class="nav-item"><a class="nav-link">Contact</a></li>
</ul>
</div>
</nav>

<!-- CAROUSEL -->
<div id="slider" class="carousel slide" data-bs-ride="carousel">

<div class="carousel-inner">

<div class="carousel-item active position-relative">
<img src="https://images.pexels.com/photos/1084199/pexels-photo-1084199.jpeg" class="d-block w-100">
<div class="hero-text">
<h1>Beautiful Flower Pots 🌸</h1>
<p>Decorate your home naturally</p>
<button class="btn btn-success">Shop Now</button>
</div>
</div>

<div class="carousel-item">
<img src="https://images.pexels.com/photos/4503751/pexels-photo-4503751.jpeg" class="d-block w-100">
</div>

<div class="carousel-item">
<img src="https://images.pexels.com/photos/2123482/pexels-photo-2123482.jpeg" class="d-block w-100">
</div>

</div>
</div>

<!-- PRODUCTS -->
<section class="container py-5">
<h2 class="text-center mb-5">Our Flower Pots</h2>

<div class="row">

<div class="col-md-4">
<div class="card">
<img src="https://images.pexels.com/photos/1005058/pexels-photo-1005058.jpeg">
<div class="card-body">
<h5>Ceramic Pot</h5>
<p>₹499</p>
<button class="btn btn-dark w-100">Add to Cart</button>
</div>
</div>
</div>

<div class="col-md-4">
<div class="card">
<img src="https://images.pexels.com/photos/1084199/pexels-photo-1084199.jpeg">
<div class="card-body">
<h5>Hanging Pot</h5>
<p>₹399</p>
<button class="btn btn-dark w-100">Add to Cart</button>
</div>
</div>
</div>

<div class="col-md-4">
<div class="card">
<img src="https://images.pexels.com/photos/2123482/pexels-photo-2123482.jpeg">
<div class="card-body">
<h5>Clay Pot</h5>
<p>₹299</p>
<button class="btn btn-dark w-100">Add to Cart</button>
</div>
</div>
</div>

<div class="col-md-4">
<div class="card">
<img src="https://images.pexels.com/photos/4503751/pexels-photo-4503751.jpeg">
<div class="card-body">
<h5>Mini Desk Pot</h5>
<p>₹199</p>
<button class="btn btn-dark w-100">Add to Cart</button>
</div>
</div>
</div>

<div class="col-md-4">
<div class="card">
<img src="https://images.pexels.com/photos/1400375/pexels-photo-1400375.jpeg">
<div class="card-body">
<h5>Decorative Pot</h5>
<p>₹599</p>
<button class="btn btn-dark w-100">Add to Cart</button>
</div>
</div>
</div>

<div class="col-md-4">
<div class="card">
<img src="https://images.pexels.com/photos/1092730/pexels-photo-1092730.jpeg">
<div class="card-body">
<h5>Garden Pot</h5>
<p>₹699</p>
<button class="btn btn-dark w-100">Add to Cart</button>
</div>
</div>
</div>

</div>
</section>

<!-- CART -->
<section class="container py-5">
<h2 class="text-center">Your Cart 🛒</h2>

<div class="row">

<div class="col-md-6">
<div class="cart-box">
<p>Ceramic Pot - ₹499</p>
<p>Mini Pot - ₹199</p>
<hr>
<h5>Total: ₹698</h5>
<button class="btn btn-dark w-100">Checkout</button>
</div>
</div>

<div class="col-md-6">
<div class="cart-box">
<input class="form-control mb-2" placeholder="Name">
<input class="form-control mb-2" placeholder="Phone">
<input class="form-control mb-2" placeholder="Address">
<button class="btn btn-success w-100">Confirm Order</button>
</div>
</div>

</div>
</section>

<!-- ABOUT -->
<section class="container text-center py-5">
<h2>About Us</h2>
<p>We provide premium quality flower pots to make your home green and beautiful 🌿</p>
</section>

<!-- FOOTER -->
<footer class="text-center p-4">
<p>© 2026 Bloom Pots Shop</p>
<p>📍 India | 📞 +91 9876543210</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
