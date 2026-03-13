# Lourasshoe.com<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SoleX - Premium Shoes</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:#f4f4f4;
}

/* Navbar */
nav{
    background:black;
    color:white;
    padding:15px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

nav h1{
    margin:0;
}

nav ul{
    list-style:none;
    display:flex;
    gap:20px;
}

nav ul li{
    cursor:pointer;
}

/* Hero section */
.hero{
    height:400px;
    background:linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)), 
    url("https://images.unsplash.com/photo-1542291026-7eec264c27ff");
    background-size:cover;
    color:white;
    display:flex;
    justify-content:center;
    align-items:center;
    flex-direction:column;
    text-align:center;
}

.hero h2{
    font-size:40px;
}

.hero button{
    padding:10px 20px;
    border:none;
    background:red;
    color:white;
    font-size:16px;
    cursor:pointer;
}

/* Products */
.products{
    padding:40px;
    text-align:center;
}

.product-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:20px;
}

.card{
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
}

.card img{
    width:100%;
    border-radius:10px;
}

/* Footer */
footer{
    background:black;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:40px;
}
</style>
</head>

<body>

<nav>
<h1>SoleX</h1>
<ul>
<li>Home</li>
<li>Shop</li>
<li>About</li>
<li>Contact</li>
</ul>
</nav>

<section class="hero">
<h2>Step Into Style</h2>
<p>Premium Shoes For Every Step</p>
<button>Shop Now</button>
</section>

<section class="products">
<h2>Our Shoes</h2>

<div class="product-grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1528701800489-20be3c4f0c44">
<h3>Runner Pro</h3>
<p>$79</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1519741497674-611481863552">
<h3>Street Classic</h3>
<p>$69</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1460353581641-37baddab0fa2">
<h3>Sport Max</h3>
<p>$89</p>
</div>

</div>
</section>

<footer>
<p>© 2026 SoleX Shoes | All Rights Reserved</p>
</footer>

</body>
</html>
