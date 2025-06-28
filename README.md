# Guruji_footwear_
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Premium Shoe Manufacturing | Dehradun</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    html {
      scroll-behavior: smooth;
    }

    /* Base Styles */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      color: #2c3e50;
      background-color: #f5f6fa;
      line-height: 1.6;
    }

    header {
      background-color: #2c3e50;
      color: white;
      padding: 30px 40px;
      text-align: center;
    }

    nav {
      background-color: #34495e;
      padding: 12px 0;
      text-align: center;
    }

    nav a {
      color: #ecf0f1;
      text-decoration: none;
      margin: 0 18px;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #1abc9c;
    }

    .hero {
      background: linear-gradient(rgba(44, 62, 80, 0.5), rgba(44, 62, 80, 0.5)),
                  url('placeholder-image.jpg') no-repeat center center/cover;
      height: 320px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
      padding: 0 20px;
    }

    section {
      padding: 50px 25px;
      max-width: 1100px;
      margin: auto;
      background-color: white;
      margin-bottom: 25px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);

      /* Animation defaults */
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.6s ease, transform 0.6s ease;
    }

    section.visible {
      opacity: 1;
      transform: translateY(0);
    }

    h2 {
      color: #2c3e50;
      margin-bottom: 20px;
    }

    h3 {
      color: #2980b9;
      margin-top: 25px;
    }

    ul {
      list-style-type: disc;
      padding-left: 20px;
    }

    .contact {
      background-color: #ecf0f1;
      padding: 40px 20px;
      text-align: center;
      border-radius: 10px;
    }

    .contact a {
      display: inline-block;
      margin-top: 10px;
      color: #2980b9;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    .contact a:hover {
      color: #1abc9c;
    }

    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Guruji Footwears - Leather Shoe Manufacturing Factory</h1>
    <p>Premium Footwear Manufacturing in Dehradun</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#brands">Brands</a>
    <a href="#craftsmanship">Craftsmanship</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero">
    <h2>Crafting Quality Leather Footwear Since Inception</h2>
  </div>

  <section id="about">
    <h2>About Our Factory</h2>
    <p>Located in the heart of Dehradun, Guruji Footwears specializes in high-quality leather shoe manufacturing. With a legacy of craftsmanship, our factory produces a diverse range of shoes including formal leather shoes, loafers, and ladies formal footwear.</p>
    <p>Our commitment to quality and durability has made us a trusted partner for prominent brands and fashion labels nationwide.</p>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <ul>
      <li>Men’s Leather Formal Shoes</li>
      <li>Premium Loafers</li>
      <li>Ladies Formal Footwear</li>
      <li>Handcrafted Genuine Leather Collections</li>
    </ul>
  </section>

  <section id="brands">
    <h2>Brands We Manufacture For</h2>
    <p>Our production facility is proud to be associated with and supply shoes for top-tier brands including:</p>
    <ul>
      <li><strong>Woodland</strong> – Rugged and premium outdoor leather shoes</li>
      <li><strong>Greenfields</strong> – Elegant and sustainable leather footwear lines</li>
    </ul>
  </section>

  <section id="craftsmanship">
    <h2>Craftsmanship in Every Step</h2>
    <p>At Guruji Footwears, each pair of shoes tells a story of tradition, quality, and unmatched skill. Our handmade shoes are the result of meticulous attention to detail, where artisans pour their experience and passion into every stitch.</p>

    <h3>Handmade Leather Loafers</h3>
    <p>Crafted for both style and comfort, our loafers combine traditional techniques with modern elegance. Each pair is hand-stitched with precision and designed to provide a soft, luxurious feel with every step. Whether it’s for a business meeting or casual outing, our loafers offer timeless versatility.</p>

    <h3>Elegant Belly Shoes</h3>
    <p>Our ladies’ belly shoes are a celebration of grace and durability. With supple leather uppers and cushioned soles, these shoes blend comfort with class. Ideal for daily wear or formal occasions, they are handcrafted to match modern fashion trends while honoring classic design.</p>

    <h3>Formal Leather Footwear</h3>
    <p>For the professional who values sophistication, our formal leather shoes are second to none. From polished oxfords to sleek derbies, each piece is handcrafted using premium hides, ensuring long-lasting form and function. The craftsmanship speaks of confidence, elegance, and refined taste.</p>

    <p>By focusing on quality materials and traditional craftsmanship, Guruji Footwears stands out as a beacon of excellence in the Indian leather shoe industry.</p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>We would love to hear from you for business inquiries, bulk orders, or collaborations.</p>
    <p><strong>Phone:</strong> <a href="tel:+918057501007">+91 8057501007</a></p>
    <p><strong>Email:</strong> <a href="mailto:gurujifwddn@gmail.com">gurujifwddn@gmail.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Guruji Footwears, Dehradun. All rights reserved.</p>
  </footer>

  <!-- Scroll Reveal Animation -->
  <script>
    document.addEventListener('DOMContentLoaded', () => {
      const sections = document.querySelectorAll('section');

      const revealOnScroll = () => {
        sections.forEach(section => {
          const rect = section.getBoundingClientRect();
          if (rect.top < window.innerHeight - 100) {
            section.classList.add('visible');
          }
        });
      };

      window.addEventListener('scroll', revealOnScroll);
      revealOnScroll(); // Reveal sections already in view on load
    });
  </script>
</body>
</html>
