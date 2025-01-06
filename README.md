# Vastrae
Vastrae Clothing Brand Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vastrae Clothing</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Responsive Styles */
        body, html {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }

        .header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
        }

        .header .logo {
            text-align: center;
            font-size: 24px;
            font-weight: bold;
        }

        .nav ul {
            list-style: none;
            text-align: center;
            padding: 0;
        }

        .nav ul li {
            display: inline;
            margin: 0 15px;
        }

        .nav ul li a {
            text-decoration: none;
            color: #fff;
        }

        .hero {
            text-align: center;
            padding: 50px 15px;
            background: #f4f4f4;
        }

        .products {
            padding: 50px 15px;
            background: #fff;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .product-card {
            border: 1px solid #ddd;
            padding: 15px;
            text-align: center;
        }

        .product-card img {
            width: 100%;
            max-width: 150px;
            margin: 0 auto 10px;
        }

        .btn {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #555;
        }

        .contact {
            padding: 50px 15px;
            background: #f9f9f9;
        }

        footer {
            text-align: center;
            padding: 20px 0;
            background: #333;
            color: #fff;
        }

        @media (max-width: 768px) {
            .nav ul li {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <div class="container">
            <h1 class="logo">Vastrae Clothing</h1>
            <nav class="nav">
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#products">Shop</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="container">
            <h2>Style Redefined</h2>
            <p>Discover the latest trends and timeless classics with Vastrae Clothing.</p>
        </div>
    </section>

    <section id="products" class="products">
        <div class="container">
            <h2>Our Collection</h2>
            <div class="product-grid">
                <div class="product-card">
                    <img src="https://via.placeholder.com/150" alt="T-Shirt">
                    <h3>Classic T-Shirt</h3>
                    <p>$20.00</p>
                    <button class="btn">Add to Cart</button>
                </div>
                <div class="product-card">
                    <img src="https://via.placeholder.com/150" alt="Hoodie">
                    <h3>Stylish Hoodie</h3>
                    <p>$40.00</p>
                    <button class="btn">Add to Cart</button>
                </div>
                <div class="product-card">
                    <img src="https://via.placeholder.com/150" alt="Jeans">
                    <h3>Denim Jeans</h3>
                    <p>$50.00</p>
                    <button class="btn">Add to Cart</button>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Vastrae</h2>
            <p>At Vastrae Clothing, we believe in crafting designs that speak to individuality and elegance. From casual wear to statement pieces, our collection reflects a commitment to quality and creativity.</p>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Get in Touch</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" required>

                <label for="message">Message:</label>
                <textarea id="message" rows="4" required></textarea>

                <button type="submit" class="btn">Submit</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Vastrae Clothing. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>
