# e-commerce
available all type of items in this store 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My E-Commerce Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>My E-Commerce Store</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <h2>Shop the Latest Trends</h2>
        <p>Best deals on top-quality products!</p>
        <button>Shop Now</button>
    </section>

    <section class="products">
        <h2>Featured Products</h2>
        <div class="product-list">
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 1">
                <h3>Product 1</h3>
                <p>$19.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 2">
                <h3>Product 2</h3>
                <p>$24.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 3">
                <h3>Product 3</h3>
                <p>$29.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 My E-Commerce Store. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
}

header {
    background: #333;
    color: white;
    padding: 10px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.banner {
    background: #f4f4f4;
    padding: 50px 20px;
}

.products {
    padding: 20px;
}

.product-list {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.product {
    border: 1px solid #ddd;
    padding: 10px;
    width: 200px;
}

.product img {
    width: 100%;
}

button {
    background: #007BFF;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
}

button:hover {
    background: #0056b3;
}

footer {
    background: #333;
    color: white;
    padding: 10px;
    margin-top: 20px;
}
