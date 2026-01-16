<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Optiforce Engineering Solutions</title>
  <style>
    :root {
      --primary: #0b3c5d;
      --secondary: #f59e0b;
      --light: #f8fafc;
      --dark: #0f172a;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: "Segoe UI", Tahoma, sans-serif;
    }

    body {
      background: var(--light);
      color: var(--dark);
      line-height: 1.6;
    }

    header {
      background: white;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      padding: 1rem 3rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    header img {
      height: 60px;
    }

    nav a {
      margin-left: 2rem;
      text-decoration: none;
      font-weight: 600;
      color: var(--primary);
    }

    nav a:hover {
      color: var(--secondary);
    }

    .hero {
      display: grid;
      grid-template-columns: 1fr 1fr;
      align-items: center;
      padding: 4rem 6rem;
      gap: 3rem;
    }

    .hero h1 {
      font-size: 3rem;
      color: var(--primary);
    }

    .hero p {
      font-size: 1.1rem;
      margin: 1.2rem 0 2rem;
    }

    .btn {
      display: inline-block;
      background: var(--secondary);
      color: white;
      padding: 0.8rem 1.8rem;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 600;
    }

    .btn:hover {
      opacity: 0.9;
    }

    section {
      padding: 4rem 6rem;
    }

    section h2 {
      font-size: 2.2rem;
      color: var(--primary);
      margin-bottom: 2rem;
      text-align: center;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }

    .card {
      background: white;
      padding: 2rem;
      border-radius: 16px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.08);
      text-align: center;
    }

    .card h3 {
      margin-bottom: 1rem;
      color: var(--primary);
    }

    .about {
      max-width: 900px;
      margin: auto;
      text-align: center;
      font-size: 1.1rem;
    }

    footer {
      background: var(--primary);
      color: white;
      padding: 2rem 3rem;
      text-align: center;
    }

    footer p {
      margin: 0.3rem 0;
    }

    @media (max-width: 900px) {
      .hero {
        grid-template-columns: 1fr;
        padding: 3rem 2rem;
      }

      section {
        padding: 3rem 2rem;
      }

      header {
        flex-direction: column;
        gap: 1rem;
      }

      nav a {
        margin-left: 1rem;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <img src="ChatGPT Image Jan 12, 2026, 10_03_20 PM.png" alt="Optiforce Logo" />
    <nav>
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero -->
  <div class="hero" id="home">
    <div>
      <h1>Optiforce Engineering Solutions</h1>
      <p><strong>Empowering Talent, Delivering Excellence</strong></p>
      <p>
        We provide reliable engineering, manpower, and technical solutions
        tailored to marine, mechanical, and industrial sectors.
      </p>
      <a href="#contact" class="btn">Get in Touch</a>
    </div>
  </div>

  <!-- Services -->
  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <h3>Engineering Services</h3>
        <p>Mechanical, marine, and industrial engineering support.</p>
      </div>
      <div class="card">
        <h3>Manpower Supply</h3>
        <p>Skilled and unskilled workforce for projects and operations.</p>
      </div>
      <div class="card">
        <h3>Project Support</h3>
        <p>End-to-end project coordination and site assistance.</p>
      </div>
      <div class="card">
        <h3>Technical Consulting</h3>
        <p>Expert guidance to improve efficiency and quality.</p>
      </div>
    </div>
  </section>

  <!-- About -->
  <section id="about">
    <h2>About Us</h2>
    <div class="about">
      <p>
        Optiforce Engineering Solutions is committed to delivering
        dependable engineering and manpower services with a strong focus
        on safety, quality, and client satisfaction. Our experienced team
        bridges talent with opportunity to drive project success.
      </p>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact Us</h2>
    <div class="about">
      <p><strong>Email:</strong> thennarasi29e@gmail.com</p>
      <p><strong>Phone:</strong> +91 91504 77894</p>
      <p><strong>Location:</strong> India</p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2026 Optiforce Engineering Solutions</p>
    <p>Empowering Talent, Delivering Excellence</p>
  </footer>

</body>
</html>
<img src="logo.png">
