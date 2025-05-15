<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Business</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      color: #333;
      background-color: #f4f4f4;
    }
    header {
      background: #333;
      color: #fff;
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      height: 50px;
    }
    nav ul {
      list-style: none;
      display: flex;
      gap: 15px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
    }
    section {
      padding: 40px 20px;
      background: #fff;
      margin: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .gallery {
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
    }
    .gallery img {
      width: 30%;
      border-radius: 8px;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    input, textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
      width: 100%;
      max-width: 400px;
    }
    button {
      padding: 10px;
      background: #333;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      width: 120px;
    }
    .social-links a {
      margin-right: 15px;
      text-decoration: none;
      color: #333;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #333;
      color: white;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <img src="logo.png" alt="Your Business Logo" class="logo" />
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>  <!-- Home Section -->  <section id="home">
    <h1>Welcome to Our Business</h1>
    <p>Your trusted partner for [your business description].</p>
  </section>  <!-- About Section -->  <section id="about">
    <h2>About Us</h2>
    <p>[Insert description about your business, mission, and values here]</p>
  </section>  <!-- Gallery Section -->  <section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
      <img src="image1.jpg" alt="Gallery Image 1" />
      <img src="image2.jpg" alt="Gallery Image 2" />
      <img src="image3.jpg" alt="Gallery Image 3" />
    </div>
  </section>  <!-- Contact Section -->  <section id="contact">
    <h2>Contact Us</h2>
    <form action="mailto:your@email.com" method="post" enctype="text/plain">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required /><label for="email">Email:</label>
  <input type="email" id="email" name="email" required />

  <label for="message">Message:</label>
  <textarea id="message" name="message" required></textarea>

  <button type="submit">Send</button>
</form>
<div class="social-links">
  <a href="https://facebook.com" target="_blank">Facebook</a>
  <a href="https://instagram.com" target="_blank">Instagram</a>
  <a href="https://linkedin.com" target="_blank">LinkedIn</a>
</div>

  </section>  <!-- Footer -->  <footer>
    <p>&copy; 2025 Your Business Name. All rights reserved.</p>
  </footer>
</body>
</html>
