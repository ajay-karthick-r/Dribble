# Project Responsive Web Design using Bootstrap
## Date:15/10/2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
pro.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ARM CART- Our Online Store</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header>
    <nav class="navbar">
      <div class="logo">ARM CART</div>
      <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="shop.html">Shop</a></li>
        <li><a href="#">About</a></li>
        <li><a href="shop.html">Contact</a></li>
        <li><a href="#">Cart 🛒</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>Welcome to ARM CART</h1>
    <p>Discover the latest trends and deals!</p>
    <a href="shop.html" class="btn">Shop Now</a>
  </section>

  <section class="products">
    <h2>Featured Products</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="Screenshot 2025-10-15 112825.png" alt="Product 1" />
        <h3>Men Fashion</h3>
        <p>₹1,499</p>
        <button>Add to Cart</button>
      </div>
      <div class="product-card">
        <img src="Screenshot 2025-10-15 113001.png" alt="Product 2" />
        <h3>Women Fashion</h3>
        <p>₹2,999</p>
        <button>Add to Cart</button>
      </div>
      <div class="product-card">
        <img src="Screenshot 2025-10-15 113207.png" alt="Product 3" />
        <h3>Home Utilities</h3>
        <p>₹500</p>
        <button>Add to Cart</button>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; ARM CART 2025 . All rights reserved.</p>
  </footer>

</body>
</html>

shop.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Product Grid</title>
  <style>
    .product-card {
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 15px;
      transition: box-shadow 0.3s ease;
    }
    .product-card:hover {
      box-shadow: 0 0 10px rgba(0,0,0,0.15);
    }
    .product-image {
      height: 200px;
      object-fit: contain;
      margin-bottom: 10px;
    }
    .rating {
      color: #f5c518;
    }
  </style>
</head>
<body>
  <div class="container py-4">
    <h2 class="mb-4">Featured Products</h2>
    <div class="row row-cols-1 row-cols-md-3 g-4">
      
      
      <div class="col">
        <div class="product-card text-center">
          <img src="Screenshot 2025-10-15 111715.png" class="product-image" alt="Product 1">
          <h5 class="mt-2">Watch</h5>
          <p class="text-success fw-bold">₹2,499</p>
          <p class="rating">★★★★☆ (4.2)</p>
          <button class="btn btn-primary">Add to Cart</button>
        </div>
      </div>

      <div class="col">
        <div class="product-card text-center">
          <img src="Screenshot 2025-10-15 112005.png" class="product-image" alt="Product 2">
          <h5 class="mt-2">SPEAKERS</h5>
          <p class="text-success fw-bold">₹5,999</p>
          <p class="rating">★★★★★ (4.8)</p>
          <button class="btn btn-primary">Add to Cart</button>
        </div>
      </div>

      <div class="col">
        <div class="product-card text-center">
          <img src="Screenshot 2025-10-15 112159.png" class="product-image" alt="Product 3">
          <h5 class="mt-2">Headphones</h5>
          <p class="text-success fw-bold">₹299</p>
          <p class="rating">★★★☆☆ (3.9)</p>
          <button class="btn btn-primary">Add to Cart</button>
        </div>
      </div>

      <div class="col">
        <div class="product-card text-center">
          <img src="Screenshot 2025-10-15 112356.png" class="product-image" alt="Product 3">
          <h5 class="mt-2">Cars</h5>
          <p class="text-success fw-bold">₹1,299</p>
          <p class="rating">★★★☆☆ (3.9)</p>
          <button class="btn btn-primary">Add to Cart</button>
        </div>
      </div>

    </div>
  </div>
</body>
</html>
```
## OUTPUT:

![alt text](<Screenshot 2025-10-15 113424.png>)
![alt text](<Screenshot 2025-10-15 113449.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
