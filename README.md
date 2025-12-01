# Html
Project for html 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My E-Commerce Site</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Store</h1>
        <nav>
            <a href="#products">Products</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product-grid">
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Product 1">
                <h3>Wireless Headphones</h3>
                <p>High-quality wireless headphones with noise cancellation. Battery life: 30 hours. Price: $99.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Product 2">
                <h3>Smartphone Case</h3>
                <p>Durable silicone case for iPhone. Colors: Black, White, Blue. Price: $19.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Product 3">
                <h3>Laptop Stand</h3>
                <p>Adjustable aluminum stand for better ergonomics. Height: 5-10 inches. Price: $49.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Product 4">
                <h3>Bluetooth Speaker</h3>
                <p>Portable speaker with waterproof design. Sound range: 20Hz-20kHz. Price: $79.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 My Store. All rights reserved.</p>
    </footer>
</body>
</html>
#styles.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 1rem;
    text-decoration: none;
}

#products {
    padding: 2rem;
    text-align: center;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1rem;
    max-width: 1200px;
    margin: 0 auto;
}

.product {
    background: white;
    border: 1px solid #ddd;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.product img {
    width: 100%;
    height: auto;
}

.product h3 {
    margin: 0.5rem 0;
}

.product p {
    color: #666;
}

button {
    background-color: #28a745;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
    border-radius: 4px;
}

button:hover {
    background-color: #218838;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    position: fixed;
    width: 100%;
    bottom: 0;
}
