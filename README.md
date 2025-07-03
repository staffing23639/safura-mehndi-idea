<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MehndiConnect - Connecting Artists with Clients</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #fffaf5;
      color: #333;
    }
    header {
      background-color: #8c4a3c;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 30px;
      background: #5a2f25;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: 500;
    }
    .hero {
      padding: 60px 20px;
      text-align: center;
      background: linear-gradient(135deg, #ffefec, #f5d7cd);
    }
    .hero h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 18px;
      margin-top: 0;
    }
    .btn {
      background: #8c4a3c;
      color: white;
      padding: 12px 24px;
      border: none;
      margin-top: 20px;
      font-size: 16px;
      border-radius: 8px;
      cursor: pointer;
    }
    .section {
      padding: 50px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .section h2 {
      text-align: center;
      margin-bottom: 30px;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .feature-box {
      background: #fff;
      border: 1px solid #eee;
      padding: 20px;
      border-radius: 12px;
      text-align: center;
    }
    footer {
      background-color: #5a2f25;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .product-gallery, .artist-profiles {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 6px;
    }
  </style>
</head>
<body>
  <header>
    <h1>MehndiConnect</h1>
    <p>Where Art Meets Tradition</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#artists">Artists</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero">
    <h1>Book Trusted Mehndi Artists Near You</h1>
    <p>Explore Designs | Book Appointments | Shop Mehndi Products</p>
    <button class="btn">Get Started</button>
  </div>

  <div class="section" id="services">
    <h2>Our Services</h2>
    <div class="features">
      <div class="feature-box">
        <h3>Bridal Packages</h3>
        <p>Specially curated designs for weddings and big occasions.</p>
      </div>
      <div class="feature-box">
        <h3>Festival Bookings</h3>
        <p>Book artists for Eid, Karwa Chauth, Teej, and more.</p>
      </div>
      <div class="feature-box">
        <h3>Group Discounts</h3>
        <p>Book for events like haldi, mehndi parties with friends & family.</p>
      </div>
      <div class="feature-box">
        <h3>On-Demand Artists</h3>
        <p>Browse verified Mehndi artists available in your area.</p>
      </div>
    </div>
  </div>

  <div class="section" id="artists">
    <h2>Top Mehndi Artists</h2>
    <div class="artist-profiles">
      <div class="card">
        <img src="https://via.placeholder.com/200x200.png?text=Artist+1" alt="Artist 1">
        <h4>Reena Sharma</h4>
        <p>Bridal & Arabic Mehndi | Delhi</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/200x200.png?text=Artist+2" alt="Artist 2">
        <h4>Fatima Khan</h4>
        <p>Traditional Mehndi | Mumbai</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/200x200.png?text=Artist+3" alt="Artist 3">
        <h4>Anjali Patel</h4>
        <p>Minimalist Designs | Ahmedabad</p>
      </div>
    </div>
  </div>

  <div class="section" id="products">
    <h2>Shop Mehndi Products</h2>
    <div class="product-gallery">
      <div class="card">
        <img src="https://via.placeholder.com/200x200.png?text=Mehndi+Cone" alt="Product 1">
        <h4>Organic Mehndi Cone (Pack of 5)</h4>
        <p>₹199</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/200x200.png?text=Stencil+Kit" alt="Product 2">
        <h4>DIY Mehndi Stencil Kit</h4>
        <p>₹249</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/200x200.png?text=Bridal+Kit" alt="Product 3">
        <h4>Bridal Mehndi Kit</h4>
        <p>₹499</p>
      </div>
    </div>
  </div>

  <div class="section" id="contact">
    <h2>Contact Us</h2>
    <p style="text-align: center;">Email: support@mehndiconnect.in | Phone: +91-9876543210</p>
  </div>

  <footer>
    <p>&copy; 2025 MehndiConnect. All rights reserved.</p>
  </footer>
</body>
</html>
