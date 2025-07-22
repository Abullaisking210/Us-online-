html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Us Online Service</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; }
    header { background-color: #3498db; color: white; padding: 20px; text-align: center; }
    nav { background: #2c3e50; padding: 10px; text-align: center; }
    nav a { color: white; margin: 10px; text-decoration: none; }
    section { padding: 20px; }
    footer { background: #333; color: white; text-align: center; padding: 10px; }
    form input, form textarea {
      display: block;
      margin: 10px 0;
      padding: 10px;
      width: 100%;
      max-width: 400px;
    }
    .services {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }
    .service-card {
      border: 1px solid #ccc;
      padding: 15px;
      width: 250px;
      border-radius: 5px;
    }
  </style>
</head>
<body>

<header>
  <h1>Us Online Service</h1>
  <p>Your One-Stop Digital Service Provider</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#services">Services</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About Us</h2>
  <p>Us Online Service offers fast, reliable digital services including bill payments, form filling, online registrations, and more.</p>
</section>

<section id="services">
  <h2>Our Services</h2>
  <div class="services">
    <div class="service-card">
      <h3>Bill Payment</h3>
      <p>Pay your electricity, gas, and water bills easily.</p>
    </div>
    <div class="service-card">
      <h3>Form Filling</h3>
      <p>We help with online government and private form filling.</p>
    </div>
    <div class="service-card">
      <h3>Registrations</h3>
      <p>From exams to portals — we handle your online registrations.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <form>
    <input type="text" placeholder="Your Name" required />
    <input type="email" placeholder="Your Email" required />
    <textarea placeholder="Your Message" required></textarea>
    <input type="submit" value="Send Message" />
  </form>
</section>

<footer>
  <p>&copy; 2025 Us Online Service. All rights reserved.</p>
</footer>

</body>
</html>
