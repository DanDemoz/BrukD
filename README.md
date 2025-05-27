<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>BrukD – Ready-Made Clothing</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #0f172a, #1e3a8a, #9333ea);
      background-size: 400% 400%;
      animation: gradientShift 20s ease infinite;
      color: #f1f5f9;
      line-height: 1.6;
    }

    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    header {
      text-align: center;
      padding: 4rem 1rem 2rem;
      background: rgba(15, 23, 42, 0.9);
      backdrop-filter: blur(10px);
    }

    header h1 {
      font-size: 3rem;
      background: linear-gradient(to right, #f59e0b, #84cc16, #06b6d4);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    header nav {
      margin-top: 1rem;
    }

    header nav a {
      color: #facc15;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    header nav a:hover {
      color: #f472b6;
    }

    section {
      padding: 3rem 1rem;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      font-size: 2rem;
      text-align: center;
      margin-bottom: 2rem;
      color: #e0f2fe;
      border-bottom: 2px dashed #38bdf8;
      padding-bottom: 0.5rem;
    }

    .product-grid, .team-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 2rem;
    }

    .product-card, .team-member {
      background: rgba(255, 255, 255, 0.05);
      border: 2px solid rgba(255, 255, 255, 0.1);
      padding: 1rem;
      border-radius: 20px;
      text-align: center;
      box-shadow: 0 10px 30px rgba(0,0,0,0.3);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .product-card:hover, .team-member:hover {
      transform: scale(1.05);
      box-shadow: 0 20px 40px rgba(0,0,0,0.4);
    }

    .product-card img, .team-member img {
      max-width: 100%;
      border-radius: 12px;
      margin-bottom: 0.75rem;
      border: 3px solid #3b82f6;
    }

    h3, h4 {
      margin: 0.5rem 0;
      color: #f0abfc;
    }

    p {
      font-size: 0.95rem;
    }

    #contact p {
      text-align: center;
      font-size: 1rem;
    }

    #contact a {
      color: #a5f3fc;
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      background: rgba(0, 0, 0, 0.5);
      font-size: 0.9rem;
      color: #cbd5e1;
    }
  </style>
</head>
<body>
  <header>
    <h1>BrukD</h1>
    <p>Ready-Made Streetwear That Moves With You</p>
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
