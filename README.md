<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>PVMedia | Let's Scale Your Brand</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500&family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
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

<section class="hero fade-in">
  <div class="container">
    <h2>Let's Scale Your Brand</h2>
    <p>At PVMedia, we help eCommerce brands unlock their true potential with strategic marketing solutions crafted for explosive growth.</p>
    <a href="contact.html" class="btn">Work With Us</a>
  </div>
</section>

<footer class="fade-in">
  <p>© 2025 PVMedia. All rights reserved.</p>
</footer>

<script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Services | PVMedia</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500&family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
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

<section class="content fade-in">
  <div class="container">
    <h2>Our Services</h2>
    <ul>
      <li>Custom eCommerce Growth Strategies</li>
      <li>Paid Advertising (Meta, TikTok, Google)</li>
      <li>Conversion Rate Optimization</li>
      <li>Creative Consulting & UGC Strategies</li>
      <li>End-to-End Brand Scaling Solutions</li>
    </ul>
  </div>
</section>

<footer class="fade-in">
  <p>© 2025 PVMedia. All rights reserved.</p>
</footer>

<script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Contact | PVMedia</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500&family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
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

<section class="content fade-in">
  <div class="container">
    <h2>Contact Us</h2>
    <p>Ready to scale your brand? Reach out and let's make it happen.</p>
    <p>Email: <a href="mailto:hello@pvmedia.com">hello@pvmedia.com</a></p>
  </div>
</section>

<footer class="fade-in">
  <p>© 2025 PVMedia. All rights reserved.</p>
</footer>

<script src="script.js"></script>
</body>
</html>
body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  background-color: #0a1a2f; /* Navy */
  color: #c0c0c0; /* Silver */
  line-height: 1.6;
}

h1, h2 {
  font-family: 'Playfair Display', serif;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
  padding: 20px;
}

header {
  background: #0a1a2f;
  padding: 20px 0;
}

header h1 {
  float: left;
  font-size: 24px;
  color: #ffffff;
}

nav {
  float: right;
}

nav a {
  color: #c0c0c0;
  text-decoration: none;
  margin-left: 20px;
  font-weight: 600;
}

.hero {
  text-align: center;
  padding: 100px 20px;
}

.hero h2 {
  font-size: 48px;
  margin-bottom: 20px;
}

.hero p {
  font-size: 20px;
  margin-bottom: 40px;
}

.btn {
  display: inline-block;
  padding: 12px 30px;
  background: #c0c0c0;
  color: #0a1a2f;
  text-decoration: none;
  font-weight: 600;
  border-radius: 30px;
  transition: background 0.3s;
}

.btn:hover {
  background: #ffffff;
}

.content {
  padding: 80px 20px;
}

ul {
  list-style: none;
  padding: 0;
}

ul li {
  margin-bottom: 15px;
  font-size: 18px;
}

footer {
  text-align: center;
  padding: 30px 20px;
  background: #0a1a2f;
  font-size: 14px;
}

.fade-in {
  opacity: 0;
  animation: fadeIn 1.5s forwards;
}

@keyframes fadeIn {
  to {
    opacity: 1;
  }
}
const faders = document.querySelectorAll('.fade-in');

const appearOptions = {
  threshold: 0,
  rootMargin: "0px 0px -100px 0px"
};

const appearOnScroll = new IntersectionObserver(function(
  entries,
  appearOnScroll
) {
  entries.forEach(entry => {
    if (!entry.isIntersecting) {
      return;
    } else {
      entry.target.classList.add('appear');
      appearOnScroll.unobserve(entry.target);
    }
  });
}, appearOptions);

faders.forEach(fader => {
  appearOnScroll.observe(fader);
});

