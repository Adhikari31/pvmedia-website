<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>PVMedia | Let's Scale Your Brand</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Urbanist:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
  <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
</head>
<body>
<header class="fade-in">
  <div class="container">
    <h1>PVMedia</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="contact.html">Contact</a>
    </nav>
  </div>
</header>

<section class="hero" data-aos="fade-up">
  <div class="container center">
    <h2>Let's Scale Your Brand</h2>
    <p>Premium marketing solutions crafted exclusively for eCommerce brands ready to dominate.</p>
    <a href="contact.html" class="btn">Work With Us</a>
  </div>
</section>

<section class="about" data-aos="fade-up">
  <div class="container center">
    <h3>Who We Are</h3>
    <p>At PVMedia, we partner with visionaries to build, grow, and accelerate high-converting eCommerce empires with bespoke strategies.</p>
    <p>We are passionate about helping brands scale to their maximum potential through targeted marketing, optimization, and data-driven solutions.</p>
  </div>
</section>

<section class="cta" data-aos="fade-up">
  <div class="container center">
    <h3>Ready to Grow?</h3>
    <p>Our team is ready to work with you and elevate your eCommerce brand.</p>
    <a href="contact.html" class="btn">Get Started</a>
  </div>
</section>

<footer class="fade-in">
  <p>© 2025 PVMedia. All rights reserved.</p>
</footer>

<script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
<script>
  AOS.init({
    duration: 1000,
    easing: 'ease-in-out',
    once: true,
  });
</script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Services | PVMedia</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Urbanist:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
  <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
</head>
<body>
<header class="fade-in">
  <div class="container">
    <h1>PVMedia</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="contact.html">Contact</a>
    </nav>
  </div>
</header>

<section class="services" data-aos="fade-up">
  <div class="container">
    <h2>Our Expertise</h2>
    <p>We provide specialized marketing solutions designed to fuel growth in your eCommerce business.</p>
    <div class="grid">
      <div class="card">
        <h4>Paid Ads Management</h4>
        <p>We scale your business with top-tier strategies across Meta, TikTok, and Google Ads.</p>
      </div>
      <div class="card">
        <h4>Conversion Optimization</h4>
        <p>Enhance your store's performance with expert conversion rate optimization strategies.</p>
      </div>
      <div class="card">
        <h4>Brand Growth Consulting</h4>
        <p>Tailored brand strategies to help you create memorable and profitable customer experiences.</p>
      </div>
    </div>
  </div>
</section>

<footer class="fade-in">
  <p>© 2025 PVMedia. All rights reserved.</p>
</footer>

<script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
<script>
  AOS.init({
    duration: 1000,
    easing: 'ease-in-out',
    once: true,
  });
</script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Contact | PVMedia</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Urbanist:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
  <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
</head>
<body>
<header class="fade-in">
  <div class="container">
    <h1>PVMedia</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="contact.html">Contact</a>
    </nav>
  </div>
</header>

<section class="contact" data-aos="fade-up">
  <div class="container center">
    <h2>Start Scaling</h2>
    <p>Email us at <a href="mailto:hello@pvmedia.com">hello@pvmedia.com</a> to start growing your eCommerce brand.</p>
    <p>We're excited to discuss how we can help you achieve new heights with your business.</p>
  </div>
</section>

<footer class="fade-in">
  <p>© 2025 PVMedia. All rights reserved.</p>
</footer>

<script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
<script>
  AOS.init({
    duration: 1000,
    easing: 'ease-in-out',
    once: true,
  });
</script>
</body>
</html>
body {
  margin: 0;
  font-family: 'Urbanist', sans-serif;
  background-color: #0a0f1a;
  color: #c0c0c0;
  overflow-x: hidden;
}
h1, h2, h3, h4 {
  font-family: 'Playfair Display', serif;
}
.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
  padding: 40px 20px;
}
header {
  background: #0a0f1a;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 40px;
}
header h1 {
  font-size: 28px;
  color: #c0c0c0;
}
nav a {
  margin-left: 20px;
  color: #c0c0c0;
  text-decoration: none;
  font-weight: 600;
}
.hero, .about, .services, .contact {
  text-align: center;
  padding: 100px 20px;
}
h2 {
  font-size: 48px;
  margin-bottom: 20px;
  color: #ffffff;
}
h3, h4 {
  margin-bottom: 15px;
  color: #b0b0b0;
}
p {
  font-size: 18px;
  color: #c0c0c0;
}
.btn {
  margin-top: 30px;
  display: inline-block;
  padding: 14px 30px;
  background: #c0c0c0;
  color: #0a0f1a;
  border-radius: 30px;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.3s ease;
}
.btn:hover {
  background: #ffffff;
}
footer {
  background: #0a0f1a;
  text-align: center;
  padding: 30px 20px;
  font-size: 14px;
  color: #7d7d7d;
}
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
  margin-top: 40px;
}
.card {
  background: #101827;
  border-radius: 15px;
  padding: 30px;
  transition: transform 0.3s ease;
}
.card:hover {
  transform: translateY(-10px);
}
.center {
  text-align: center;
}
a {
  color: #c0c0c0;
}
a:hover {
  color: #ffffff;
}


