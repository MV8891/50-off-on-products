# 50-off-on-products
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Product Store</title>
    <style>
        /* Basic styling - customize colors/fonts */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #35424a;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        .product {
            background: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .product img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 0 auto 15px;
        }
        .price {
            color: #e8491d;
            font-weight: bold;
            font-size: 1.2em;
        }
        .btn {
            display: inline-block;
            background: #e8491d;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }
        footer {
            text-align: center;
            padding: 20px 0;
            background: #35424a;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>My Product Store</h1>
            <p>Amazing products at great prices!</p>
        </div>
    </header>

    <div class="container">
        <!-- Product 1 -->
        <div class="product">
            <h2>Product Name 1</h2>
            <img src="https://via.placeholder.com/300x200" alt="Product 1">
            <p>Description of the product goes here. Explain why it's awesome!</p>
            <p class="price">$19.99</p>
            <a href="YOUR_AFFILIATE_LINK_1" class="btn" target="_blank">Buy Now</a>
        </div>

        <!-- Product 2 -->
        <div class="product">
            <h2>Product Name 2</h2>
            <img src="https://via.placeholder.com/300x200" alt="Product 2">
            <p>Description of the product goes here. Explain why it's awesome!</p>
            <p class="price">$29.99</p>
            <a href="YOUR_AFFILIATE_LINK_2" class="btn" target="_blank">Buy Now</a>
        </div>

        <!-- Add more products as needed -->
    </div>

    <footer>
        <p>My Product Store &copy; 2023</p>
    </footer>
</body>
</html>
