<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Basantpriya Enterprises</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: #f8f5f2;
}

header {
    background: #c8a27c;
    padding: 20px;
    text-align: center;
    color: white;
}

nav {
    background: #a67c52;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    text-align: center;
    padding: 30px;
}

.hero h2 {
    color: #5c4033;
}

.products {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
}

.product {
    background: white;
    border-radius: 12px;
    padding: 15px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    text-align: center;
}

.product img {
    width: 100%;
    border-radius: 10px;
}

.product h3 {
    color: #5c4033;
}

.btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 15px;
    background: #25D366;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

.footer {
    text-align: center;
    padding: 20px;
    background: #c8a27c;
    color: white;
}
</style>
</head>

<body>

<header>
    <h1>Basantpriya Enterprises</h1>
    <p>Handmade Macrame Collection 🌿</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">Contact</a>
</nav>

<section class="hero">
    <h2>Premium Handmade Macrame Products</h2>
    <p>Designed by Priyanka Rajput</p>
</section>

<section class="products">

    <div class="product">
        <img src="product1.jpg" alt="">
        <h3>Macrame Hanging Lamp</h3>
        <p>₹1499</p>
        <a class="btn" href="https://wa.me/919829022898?text=I%20want%20to%20order%20Macrame%20Lamp">Order on WhatsApp</a>
    </div>

    <div class="product">
        <img src="product2.jpg" alt="">
        <h3>Macrame Curtain</h3>
        <p>₹2999</p>
        <a class="btn" href="https://wa.me/919829022898?text=I%20want%20to%20order%20Macrame%20Curtain">Order on WhatsApp</a>
    </div>

    <div class="product">
        <img src="product3.jpg" alt="">
        <h3>Macrame Handbag</h3>
        <p>₹999</p>
        <a class="btn" href="https://wa.me/919829022898?text=I%20want%20to%20order%20Macrame%20Handbag">Order on WhatsApp</a>
    </div>

</section>

<div class="footer">
    <p>📞 WhatsApp: 9829022898</p>
    <p>© 2026 Basantpriya Enterprises | Handmade with ❤️</p>
</div>

</body>
</html>
