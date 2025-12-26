<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Interior Design Studio</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="hero">
    <div class="container">
      <h1>Interior Design Studio</h1>
      <p>Minimal. Modern. Made for living.</p>
      <a href="#contact" class="btn">Get a quote</a>
    </div>
  </header>

  <nav class="nav">
    <div class="container">
      <a href="#">Home</a>
      <a href="#services">Services</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <main class="container">
    <section id="welcome" class="welcome">
      <h2>Welcome</h2>
      <p>
        We design calm, functional spaces—bedrooms, kitchens, and turnkey projects.
        From concept to execution, we blend craft with clarity.
      </p>
    </section>

    <section id="services" class="grid two">
      <div>
        <h3>Services</h3>
        <ul class="list">
          <li><strong>Bedroom design:</strong> Wardrobes, wall panels, lighting</li>
          <li><strong>Kitchen modular:</strong> Layouts, finishes, hardware</li>
          <li><strong>Turnkey execution:</strong> Carpentry, paint, electrical</li>
          <li><strong>3D & moodboards:</strong> Visuals for decision-making</li>
        </ul>
      </div>
      <div class="card note">
        <h4>Why us</h4>
        <p>Transparent rates, vendor network, and on-site supervision for smooth delivery.</p>
      </div>
    </section>

    <section id="portfolio">
      <h3>Portfolio</h3>
      <div class="grid three">
        <figure class="card">
          <img src="images/living.jpg" alt="Modern living room" />
          <figcaption>Living room—warm neutrals</figcaption>
        </figure>
        <figure class="card">
          <img src="images/kitchen.jpg" alt="Minimal kitchen" />
          <figcaption>Kitchen—matte white & oak</figcaption>
        </figure>
        <figure class="card">
          <img src="images/bedroom.jpg" alt="Cozy bedroom" />
          <figcaption>Bedroom—soft textures</figcaption>
        </figure>
      </div>
    </section>

    <section id="contact" class="contact">
      <h3>Contact</h3>
      <p><strong>WhatsApp:</strong> +91-XXXXXXXXXX</p>
      <p><strong>Email:</strong> hello@interiorstudio.in</p>
      <form class="contact-form" action="#" method="post">
        <input type="text" name="name" placeholder="Your name" required />
        <input type="email" name="email" placeholder="Your email" required />
        <textarea name="message" rows="4" placeholder="Tell us about your space" required></textarea>
        <button type="submit" class="btn">Send</button>
      </form>
    </section>
  </main>

  <footer class="footer">
    <div class="container">
      <small>© 2025 Interior Design Studio • Gurgaon & NCR</small>
    </div>
  </footer>
</body>
</html>
