<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Streetwear Clothing</title>
  <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Montserrat', sans-serif;
      background: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(45deg, #000, #444);
      color: #fff;
      text-align: center;
      padding: 40px 20px;
    }
    nav {
      background: #222;
      display: flex;
      justify-content: center;
      padding: 15px 0;
    }
    nav a {
      color: #fff;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #3D95CE;
    }
    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
      padding: 40px 0;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      grid-gap: 20px;
    }
    .product {
      background: #fff;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      overflow: hidden;
      text-align: center;
      transition: transform 0.3s;
    }
    .product:hover {
      transform: translateY(-5px);
    }
    .product img {
      width: 100%;
      height: auto;
    }
    .product h3 {
      margin: 15px 0;
    }
    .product p {
      font-size: 1.1em;
      margin-bottom: 15px;
    }
    .venmo-btn {
      background: #3D95CE;
      color: #fff;
      padding: 10px 20px;
      margin-bottom: 15px;
      text-decoration: none;
      display: inline-block;
      border-radius: 3px;
      transition: background 0.3s;
    }
    .venmo-btn:hover {
      background: #2a7a9e;
    }
    footer {
      background: #000;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 40px;
    }
    th, td {
      padding: 12px;
      text-align: center;
      border: 1px solid #ddd;
    }
    th {
      background: #3D95CE;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <h1>Streetwear Clothing</h1>
    <p>Exclusively Venmo Payments</p>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>
  <section id="home" class="container">
    <h2>Welcome</h2>
    <p>Discover our latest streetwear styles. All transactions are via Venmo.</p>
  </section>
  <section id="products" class="container">
    <h2>Products</h2>
    <div class="products">
      <div class="product">
        <img src="shirt.jpg" alt="Cool Shirt">
        <h3>Cool Shirt</h3>
        <p>$29.99</p>
        <a class="venmo-btn" href="https://venmo.com/?txn=pay&recipients=YourVenmoUsername&amount=29.99&note=Cool+Shirt">Buy with Venmo</a>
      </div>
      <div class="product">
        <img src="hoodie.jpg" alt="Urban Hoodie">
        <h3>Urban Hoodie</h3>
        <p>$49.99</p>
        <a class="venmo-btn" href="https://venmo.com/?txn=pay&recipients=YourVenmoUsername&amount=49.99&note=Urban+Hoodie">Buy with Venmo</a>
      </div>
      <div class="product">
        <img src="cap.jpg" alt="Stylish Cap">
        <h3>Stylish Cap</h3>
        <p>$19.99</p>
        <a class="venmo-btn" href="https://venmo.com/?txn=pay&recipients=YourVenmoUsername&amount=19.99&note=Stylish+Cap">Buy with Venmo</a>
      </div>
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
  <footer>
    <p>&copy; 2025 Streetwear Clothing</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Streetwear Clothing</title>
  <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Streetwear Clothing</h1>
    <p>Exclusively Venmo Payments</p>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="cool-shirt.html">Cool Shirt</a>
    <a href="urban-hoodie.html">Urban Hoodie</a>
    <a href="stylish-cap.html">Stylish Cap</a>
  </nav>
  <section id="home" class="container">
    <h2>Welcome</h2>
    <p>Discover the latest streetwear. Click on a product for details.</p>
  </section>
  <section id="products" class="container">
    <h2>Products</h2>
    <div class="products">
      <div class="product">
        <a href="cool-shirt.html">
          <img src="shirt.jpg" alt="Cool Shirt">
          <h3>Cool Shirt</h3>
        </a>
        <p>$29.99</p>
      </div>
      <div class="product">
        <a href="urban-hoodie.html">
          <img src="hoodie.jpg" alt="Urban Hoodie">
          <h3>Urban Hoodie</h3>
        </a>
        <p>$49.99</p>
      </div>
      <div class="product">
        <a href="stylish-cap.html">
          <img src="cap.jpg" alt="Stylish Cap">
          <h3>Stylish Cap</h3>
        </a>
        <p>$19.99</p>
      </div>
    </div>
  </section>
  <footer>
    <p>&copy; 2025 Streetwear Clothing</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cool Shirt - Streetwear Clothing</title>
  <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Streetwear Clothing</h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="cool-shirt.html">Cool Shirt</a>
    <a href="urban-hoodie.html">Urban Hoodie</a>
    <a href="stylish-cap.html">Stylish Cap</a>
  </nav>
  <section class="container">
    <h2>Cool Shirt</h2>
    <img src="shirt.jpg" alt="Cool Shirt" style="width:100%; max-width:400px;">
    <p>High-quality cool shirt for an urban look. Price: $29.99</p>
    <a class="venmo-btn" href="https://venmo.com/?txn=pay&recipients=YourVenmoUsername&amount=29.99&note=Cool+Shirt">Buy with Venmo</a>
    <p><a href="index.html">Back to Products</a></p>
  </section>
  <footer>
    <p>&copy; 2025 Streetwear Clothing</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Urban Hoodie - Streetwear Clothing</title>
  <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Streetwear Clothing</h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="cool-shirt.html">Cool Shirt</a>
    <a href="urban-hoodie.html">Urban Hoodie</a>
    <a href="stylish-cap.html">Stylish Cap</a>
  </nav>
  <section class="container">
    <h2>Urban Hoodie</h2>
    <img src="hoodie.jpg" alt="Urban Hoodie" style="width:100%; max-width:400px;">
    <p>Cozy and stylish hoodie for everyday wear. Price: $49.99</p>
    <a class="venmo-btn" href="https://venmo.com/?txn=pay&recipients=YourVenmoUsername&amount=49.99&note=Urban+Hoodie">Buy with Venmo</a>
    <p><a href="index.html">Back to Products</a></p>
  </section>
  <footer>
    <p>&copy; 2025 Streetwear Clothing</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Stylish Cap - Streetwear Clothing</title>
  <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Streetwear Clothing</h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="cool-shirt.html">Cool Shirt</a>
    <a href="urban-hoodie.html">Urban Hoodie</a>
    <a href="stylish-cap.html">Stylish Cap</a>
  </nav>
  <section class="container">
    <h2>Stylish Cap</h2>
    <img src="cap.jpg" alt="Stylish Cap" style="width:100%; max-width:400px;">
    <p>Sleek cap to complete your look. Price: $19.99</p>
    <a class="venmo-btn" href="https://venmo.com/?txn=pay&recipients=YourVenmoUsername&amount=19.99&note=Stylish+Cap">Buy with Venmo</a>
    <p><a href="index.html">Back to Products</a></p>
  </section>
  <footer>
    <p>&copy; 2025 Streetwear Clothing</p>
  </footer>
</body>
</html>
/* Common styling for all pages */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: 'Montserrat', sans-serif;
  background: #f4f4f4;
  color: #333;
  line-height: 1.6;
}
header {
  background: linear-gradient(45deg, #000, #444);
  color: #fff;
  text-align: center;
  padding: 40px 20px;
}
nav {
  background: #222;
  display: flex;
  justify-content: center;
  padding: 15px 0;
}
nav a {
  color: #fff;
  margin: 0 20px;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}
nav a:hover {
  color: #3D95CE;
}
.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
  padding: 40px 0;
}
.products {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  grid-gap: 20px;
}
.product {
  background: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  overflow: hidden;
  text-align: center;
  transition: transform 0.3s;
}
.product:hover {
  transform: translateY(-5px);
}
.product img {
  width: 100%;
  height: auto;
}
.product h3 {
  margin: 15px 0;
}
.product p {
  font-size: 1.1em;
  margin-bottom: 15px;
}
.venmo-btn {
  background: #3D95CE;
  color: #fff;
  padding: 10px 20px;
  text-decoration: none;
  display: inline-block;
  border-radius: 3px;
  transition: background 0.3s;
}
.venmo-btn:hover {
  background: #2a7a9e;
}
footer {
  background: #000;
  color: #fff;
  text-align: center;
  padding: 20px;
  margin-top: 20px;
}
table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 40px;
}
th, td {
  padding: 12px;
  text-align: center;
  border: 1px solid #ddd;
}
th {
  background: #3D95CE;
  color: #fff;
}
