<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>BrukD – Ready-Made Clothing</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #222;
      line-height: 1.6;
    }

    header {
      background: #1e293b;
      color: white;
      text-align: center;
      padding: 2rem;
    }

    header nav a {
      margin: 0 1rem;
      color: #e2e8f0;
      text-decoration: none;
    }

    header nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 2rem;
    }

    .product-grid, .team-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.5rem;
      margin-top: 1rem;
    }

    .product-card, .team-member {
      background: white;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      text-align: center;
    }

    .product-card img, .team-member img {
      max-width: 100%;
      border-radius: 8px;
      margin-bottom: 0.5rem;
    }

    footer {
      background: #1e293b;
      color: white;
      text-align: center;
      padding: 1rem;
    }

    a {
      color: #1e40af;
    }
  </style>
</head>
<body>
  <header>
    <h1>BrukD</h1>
    <p>Ready-Made Streetwear that Moves With You</p>
    <nav>
      <a href="#products">Products</a>
      <a href="#team">Our Team</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="products">
    <h2>Our Top Picks</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="images/windbreaker_black.jpg" alt="Urban Windbreaker">
        <h3>Urban Windbreaker</h3>
        <p>$89.99 – Sizes: S-XL</p>
      </div>
      <div class="product-card">
        <img src="images/cargo_khaki.jpg" alt="Cargo Pants">
        <h3>Relaxed Fit Cargo Pants</h3>
        <p>$69.50 – Sizes: 28-36</p>
      </div>
      <div class="product-card">
        <img src="images/graphictee_white.jpg" alt="Graphic Tee">
        <h3>Minimalist Graphic Tee</h3>
        <p>$32.00 – Sizes: S-XXL</p>
      </div>
    </div>
  </section>

  <section id="team">
    <h2>Meet the Team</h2>
    <div class="team-grid">
      <div class="team-member">
        <img src="images/team_bruk.jpg" alt="Bruk Teshome">
        <h4>Bruk Teshome</h4>
        <p>Founder & CEO</p>
      </div>
      <div class="team-member">
        <img src="images/team_linda.jpg" alt="Linda Chen">
        <h4>Linda Chen</h4>
        <p>Creative Director</p>
      </div>
      <div class="team-member">
        <img src="images/team_anthony.jpg" alt="Anthony Mensah">
        <h4>Anthony Mensah</h4>
        <p>Logistics Manager</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:support@brukd.com">support@brukd.com</a></p>
    <p>Phone: +1 (416) 555-0192</p>
    <p>123 Style St, Toronto, ON</p>
  </section>

  <footer>
    <p>&copy; 2025 BrukD. All rights reserved.</p>
  </footer>
</body>
</html>
