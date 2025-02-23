<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Streetwear Clothing</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, sans-serif; line-height: 1.6; }
    header { background: #000; color: #fff; padding: 20px; text-align: center; }
    nav { background: #333; display: flex; justify-content: center; padding: 10px; }
    nav a { color: #fff; margin: 0 15px; text-decoration: none; }
    .container { width: 90%; margin: auto; padding: 20px 0; }
    .products { display: flex; flex-wrap: wrap; justify-content: center; }
    .product { border: 1px solid #ccc; margin: 10px; padding: 10px; width: 250px; text-align: center; }
    .product img { width: 100%; }
    .venmo-btn {
      background: #3D95CE; color: #fff; padding: 10px;
      text-decoration: none; display: inline-block; margin-top: 10px;
    }
    footer { background: #000; color: #fff; text-align: center; padding: 20px; margin-top: 20px; }
    table { width: 100%; border-collapse: collapse; margin-top: 20px; }
    table, th, td { border: 1px solid #ccc; }
    th, td { padding: 10px; text-align: center; }
  </style>
</head>
<body>
  <header>
    <h1>Streetwear Clothing</h1>
    <p>Only Accepting Venmo Payments</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home" class="container">
    <h2>Welcome</h2>
    <p>Discover the latest streetwear styles. All payments are done via Venmo.</p>
  </section>

  <section id="products" class="container">
    <h2>Products</h2>
    <div class="products">
      <!-- Product 1 -->
      <div class="product">
        <img src="shirt.jpg" alt="Cool Shirt">
        <h3>Cool Shirt</h3>
        <p>$29.99</p>
        <a class="venmo-btn" href="https://venmo.com/?txn=pay&recipients=YourVenmoUsername&amount=29.99&note=Cool+Shirt">Buy with Venmo</a>
      </div>
      <!-- Product 2 -->
      <div class="product">
        <img src="hoodie.jpg" alt="Urban Hoodie">
        <h3>Urban Hoodie</h3>
        <p>$49.99</p>
        <a class="venmo-btn" href="https://venmo.com/?txn=pay&recipients=YourVenmoUsername&amount=49.99&note=Urban+Hoodie">Buy with Venmo</a>
      </div>
      <!-- Product 3 -->
      <div class="product">
        <img src="cap.jpg" alt="Stylish Cap">
        <h3>Stylish Cap</h3>
        <p>$19.99</p>
        <a class="venmo-btn" href="https://venmo.com/?txn=pay&recipients=YourVenmoUsername&amount=19.99&note=Stylish+Cap">Buy with Venmo</a>
      </div>
      <!-- Add more products as needed -->
    </div>

    <h3>Product Summary</h3>
    <table>
      <tr>
        <th>Product</th>
        <th>Price</th>
        <th>Payment</th>
      </tr>
      <tr>
        <td>Cool Shirt</td>
        <td>$29.99</td>
        <td>Venmo</td>
      </tr>
      <tr>
        <td>Urban Hoodie</td>
        <td>$49.99</td>
        <td>Venmo</td>
      </tr>
      <tr>
        <td>Stylish Cap</td>
        <td>$19.99</td>
        <td>Venmo</td>
      </tr>
    </table>
  </section>

  <section id="contact" class="container">
    <h2>Contact</h2>
    <p>Email us at <a href="mailto:info@streetwear.com">info@streetwear.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Streetwear Clothing</p>
  </footer>
</body>
</html>
