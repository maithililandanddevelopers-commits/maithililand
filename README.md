<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Maithili Land and Developers - Real Estate in Nagpur. Flats & Plots for Sale and Rent. 1BHK, 2BHK, 3BHK. Contact us today!">
<title>Maithili Land and Developers | Nagpur Properties</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<!-- HEADER -->
<header>
  <img src="images/logo.png" alt="Maithili Land and Developers Logo">
  <div>
    <h1>Maithili Land and Developers</h1>
    <div class="contact-btns">
      <button onclick="window.location.href='tel:8850114073'">Call</button>
      <button onclick="window.location.href='mailto:maithililandanddevelopers@gmail.com'">Mail</button>
      <button onclick="window.open('https://wa.me/918850114073','_blank')">WhatsApp</button>
      <button onclick="window.open('https://www.instagram.com/','_blank')">Instagram</button>
      <button onclick="window.open('https://www.youtube.com/','_blank')">YouTube</button>
    </div>
  </div>
</header>

<!-- NAV -->
<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#projects">Properties</a></li>
    <li><a href="#requirements">Requirements</a></li>
    <li><a href="#location">Location</a></li>
  </ul>
</nav>

<!-- ABOUT -->
<section id="about">
  <h2>About Us</h2>
  <p>We are a trusted real estate company in Nagpur, offering premium 1BHK, 2BHK, 3BHK Flats & Plots for Sale and Rent with transparency and commitment. Explore our properties and get in touch today!</p>
</section>

<!-- PROPERTY GALLERY -->
<section id="projects">
  <h2>Our Properties</h2>
  <div class="project-list">
    <div class="project-item">
      <img src="images/flat1.jpg" alt="1BHK Flat">
      <h3>1BHK Flat - Sale</h3>
      <p>Location: Somalwada, Nagpur</p>
      <a class="button" href="#">View Details</a>
    </div>
    <div class="project-item">
      <img src="images/flat2.jpg" alt="2BHK Flat">
      <h3>2BHK Flat - Rent</h3>
      <p>Location: Manish Nagar, Nagpur</p>
      <a class="button" href="#">View Details</a>
    </div>
    <div class="project-item">
      <img src="images/plot1.jpg" alt="Plot">
      <h3>Plot - Sale</h3>
      <p>Location: Nagpur</p>
      <a class="button" href="#">View Details</a>
    </div>
  </div>

  <!-- Slider -->
  <div class="slider">
    <img src="images/flat1.jpg" alt="Flat 1">
    <img src="images/flat2.jpg" alt="Flat 2">
    <img src="images/flat3.jpg" alt="Flat 3">
    <img src="images/plot1.jpg" alt="Plot 1">
  </div>
</section>

<!-- REQUIREMENTS FORM -->
<section id="requirements">
  <h2>Submit Your Requirement</h2>
  <form onsubmit="alert('Requirement Submitted!'); return false;">
    <input type="text" placeholder="Name" required>
    <input type="email" placeholder="Email" required>
    <input type="tel" placeholder="Mobile" required>
    <select required>
      <option value="">Select Property Type</option>
      <option value="1BHK">1BHK</option>
      <option value="2BHK">2BHK</option>
      <option value="3BHK">3BHK</option>
      <option value="Plot">Plot</option>
    </select>
    <select required>
      <option value="">For Sale/Rent</option>
      <option value="Sale">Sale</option>
      <option value="Rent">Rent</option>
    </select>
    <textarea placeholder="Comment"></textarea>
    <button type="submit" class="button">Submit</button>
  </form>
</section>

<!-- LOCATION -->
<section id="location">
  <h2>Our Location</h2>
  <iframe src="https://www.google.com/maps?q=205+Gajanan+Apartments+Behind+Amrut+Loan+Somalwada+Manish+Nagar+Nagpur&output=embed" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
</section>

<!-- FOOTER -->
<footer>
  <p>&copy; 2026 Maithili Land and Developers. All Rights Reserved.</p>
  <p>Follow us: <a href="https://www.instagram.com/" target="_blank">Instagram</a> | <a href="https://www.youtube.com/" target="_blank">YouTube</a></p>
</footer>

<script src="script.js"></script>
</body>
</html>
