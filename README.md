# Xobdor.Xeteli
It is a social platform where all assamese literatures will be explore.
<!DOCTYPE html>
<html>
<head>
  <title>Portfolio Website</title>
  <style>
/* Global Styles */
body {
  margin: 0;
  padding: 0;
  font-family: Times New Roman, sans-serif;
  background-color: #000000;
  color: #fff700;
}

/* Header Styles */
.header {
  width: 100%;
  background-color: #000000;
}
.header h1 {
  font-size: 16px;
}
.dropdown-menu {
  display: flex;
  justify-content: space-around;
  list-style-type: none;
  padding: 0;
  margin: 0;
}

.dropdown-menu li {
  display: inline;
}

.dropdown-menu li a {
  text-decoration: none;
  color: #fff;
  padding: 10px;
}

/* Hero Section Styles */
.hero {
  width: 100%;
  text-align: center;
  padding: 100px 0;
  background-color: #fff700;
  color: #000000;
}

.hero h1 {
  font-size: 48px;
  margin-bottom: 20px;
}

.hero p {
  font-size: 24px;
  margin-bottom: 40px;
}

.cta-button {
  margin-top: 20px;
}

.cta-button button {
  background-color: #fff;
  color: #000000;
  padding: 10px 20px;
  font-size: 18px;
  border: none;
  cursor: pointer;
}

/* Portfolio, Services, Testimonial, Blog Section Styles */
.portfolio-section,
.services-section,
.testimonial-section,
.blog-section {
  padding: 50px 0;
}

.portfolio-container,
.services-container,
.testimonial-container,
.blog-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.portfolio-item,
.service,
.testimonial-item,
.blog-item {
  padding: 20px;
  text-align: center;
  background-color: #fff700
color: #000000;
}

.portfolio-item img,
.service img,
.testimonial-item img,
.blog-item img {
  width: 100%;
}

/* Call to Action Section Styles */
.cta-section {
  padding: 50px;
  text-align: center;
  background-color: #fff700;
  color: #000000;
}

/* About and Contact Section Styles */
.about-section,
.contact-section {
  padding: 50px;
  text-align: center;
}

/* Footer Section Styles */
footer {
   background-color: #fff700;
  color: #000000;
  padding: 20px;
  text-align: center;
}

.social-icons {
  display: flex;
  justify-content: center;
  gap: 10px;
}

.social-icons img {
  border-radius: 50%;
}

</style>
  <script src="script.js"></script>
</head>
<body>
  <header class="header">
    <nav>
      <ul class="dropdown-menu">
        <li><a href="#">Home</a></li>
        <li><a href="#">Portfolio</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Testimonials</a></li>
        <li><a href="#">Blog</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>Xobdor.Xeteli</h1>
    <p>তলসৰা শেৱালী l Tolxora Xewali</p>
    <div class="cta-button">
      <button>Get Started</button>
    </div>
  </section>

  <section class="portfolio-section">
    <div class="portfolio-container">
      <div class="portfolio-item">
        <img src="https://via.placeholder.com/imagesize" alt="Portfolio 1">
        <h2>Portfolio 1</h2>
        <p>Description of Portfolio 1</p>
      </div>
      <div class="portfolio-item">
        <img src="https://via.placeholder.com/imagesize" alt="Portfolio 2">
        <h2>Portfolio 2</h2>
        <p>Description of Portfolio 2</p>
      </div>
      <div class="portfolio-item">
        <img src="https://via.placeholder.com/imagesize" alt="Portfolio 3">
        <h2>Portfolio 3</h2>
        <p>Description of Portfolio 3</p>
      </div>
      <div class="portfolio-item">
        <img src="https://via.placeholder.com/imagesize" alt="Portfolio 4">
        <h2>Portfolio 4</h2>
        <p>Description of Portfolio 4</p>
      </div>
      <div class="portfolio-item">
        <img src="https://via.placeholder.com/imagesize" alt="Portfolio 5">
        <h2>Portfolio 5</h2>
        <p>Description of Portfolio 5</p>
      </div>
      <div class="portfolio-item">
        <img src="https://via.placeholder.com/imagesize" alt="Portfolio 6">
        <h2>Portfolio 6</h2>
        <p>Description of Portfolio 6</p>
      </div>
    </div>
  </section>

  <section class="services-section">
    <div class="services-container">
      <div class="service">
        <img src="https://via.placeholder.com/imagesize" alt="Service 1">
        <h2>Service 1</h2>
        <p>Description of Service 1</p>
      </div>
      <div class="service">
        <img src="https://via.placeholder.com/imagesize" alt="Service 2">
        <h2>Service 2</h2>
        <p>Description of Service 2</p>
      </div>
      <div class="service">
        <img src="https://via.placeholder.com/imagesize" alt="Service 3">
        <h2>Service 3</h2>
        <p>Description of Service 3</p>
     </div>
      <div class="service">
        <img src="https://via.placeholder.com/imagesize" alt="Service 4">
        <h2>Service 4</h2>
        <p>Description of Service 4</p>
      </div>
      <div class="service">
        <img src="https://via.placeholder.com/imagesize" alt="Service 5">
        <h2>Service 5</h2>
        <p>Description of Service 5</p>
      </div>
      <div class="service">
        <img src="https://via.placeholder.com/imagesize" alt="Service 6">
        <h2>Service 6</h2>
        <p>Description of Service 6</p>
      </div>
    </div>
  </section>

  <section class="testimonial-section">
    <div class="testimonial-container">
      <div class="testimonial-item">
        <img src="https://via.placeholder.com/imagesize" alt="Testimonial 1">
        <h2>Testimonial 1</h2>
        <p>Description of Testimonial 1</p>
      </div>
      <div class="testimonial-item">
        <img src="https://via.placeholder.com/imagesize" alt="Testimonial 2">
        <h2>Testimonial 2</h2>
        <p>Description of Testimonial 2</p>
      </div>
      <div class="testimonial-item">
        <img src="https://via.placeholder.com/imagesize" alt="Testimonial 3">
        <h2>Testimonial 3</h2>
        <p>Description of Testimonial 3</p>
      </div>
      <div class="testimonial-item">
        <img src="https://via.placeholder.com/imagesize" alt="Testimonial 4">
        <h2>Testimonial 4</h2>
        <p>Description of Testimonial 4</p>
      </div>
      <div class="testimonial-item">
        <img src="https://via.placeholder.com/imagesize" alt="Testimonial 5">
        <h2>Testimonial 5</h2>
        <p>Description of Testimonial 5</p>
      </div>
      <div class="testimonial-item">
        <img src="https://via.placeholder.com/imagesize" alt="Testimonial 6">
        <h2>Testimonial 6</h2>
        <p>Description of Testimonial 6</p>
      </div>
    </div>
  </section>

  <section class="blog-section">
    <div class="blog-container">
      <div class="blog-item">
        <img src="https://via.placeholder.com/imagesize" alt="Blog 1">
        <h2>Blog 1</h2>
        <p>Description of Blog 1</p>
      </div>
      <div class="blog-item">
        <img src="https://via.placeholder.com/imagesize" alt="Blog 2">
        <h2>Blog 2</h2>
        <p>Description of Blog 2</p>
      </div>
      <div class="blog-item">
        <img src="https://via.placeholder.com/imagesize" alt="Blog 3">
        <h2>Blog 3</h2>
        <p>Description of Blog 3</p>
      </div>
    </div>
  </section>

  <section class="cta-section">
    <div class="cta-container">
      <h2>Call to Action Section</h2>
      <p>Place your call to action content here.</p>
      <divclass="cta-button">
        <button>Get Started</button>
      </div>
    </div>
  </section>

  <section class="about-section">
    <div class="about-container">
      <h2>About Us</h2>
      <p>Write about your company or yourself here.</p>
    </div>
  </section>

  <section class="contact-section">
    <div class="contact-container">
      <h2>Contact Us</h2>
      <form>
        <!-- Contact form goes here -->
      </form>
    </div>
  </section>

  <footer>
    <div class="social-icons">
      <img src="https://via.placeholder.com/imagesize" alt="Facebook">
      <img src="https://via.placeholder.com/imagesize" alt="Twitter">
      <img src="https://via.placeholder.com/imagesize" alt="Instagram">
    </div>
  </footer>
</body>
</html>
