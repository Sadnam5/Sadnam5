<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Wind Breaker</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>🌬️ Wind Breaker</h1>
    <p>Love advice and unique products – shirts & plants</p>
    <nav>
      <a href="#about">About</a>
      <a href="#advice">Love Advice</a>
      <a href="#shop">Shop</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Wind Breaker</h2>
    <p>We help people understand love while offering stylish shirts and beautiful plants to grow with.</p>
  </section>

  <section id="advice">
    <h2>Love Advice</h2>
    <ul>
      <li>❤️ What Is Love? Let's Talk</li>
      <li>💡 Learning to Love Yourself</li>
      <li>🌱 Growing Through Relationships</li>
    </ul>
  </section>

  <section id="shop">
    <h2>Shop</h2>
    <div class="product">🪴 Peace Lily – $15</div>
    <div class="product">👕 “Love Grows” Shirt – $25</div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email us at: <a href="mailto:love@windbreaker.com">love@windbreaker.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Wind Breaker. All rights reserved.</p>
  </footer>
</body>
</html>
body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  background: #fdf6f0;
  color: #333;
}

header {
  background: #d3e5ff;
  padding: 2rem;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 2.5rem;
}

nav a {
  margin: 0 1rem;
  text-decoration: none;
  color: #333;
}

section {
  padding: 2rem;
  max-width: 800px;
  margin: auto;
}

.product {
  background: #fff;
  padding: 1rem;
  margin: 1rem 0;
  border-radius: 8px;
  box-shadow: 0 0 8px rgba(0,0,0,0.1);
}

footer {
  text-align: center;
  padding: 1rem;
  background: #eee;
}
