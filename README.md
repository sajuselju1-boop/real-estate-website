# real-estate-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Kerala Real Estate</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --primary: #065f46;     /* Deep green */
      --secondary: #0f766e;
      --light: #f0fdfa;
      --dark: #0f172a;
      --gray: #64748b;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: white;
      color: var(--dark);
      line-height: 1.6;
    }

    section {
      padding: 4rem 1.5rem;
      max-width: 1100px;
      margin: auto;
    }

    h1, h2, h3 {
      font-weight: 700;
    }

    p {
      color: var(--gray);
    }

    /* HERO */
    .hero {
      background: linear-gradient(135deg, #065f46, #0f766e);
      color: white;
      text-align: center;
      padding: 6rem 1.5rem;
    }

    .hero h1 {
      font-size: 2.6rem;
      margin-bottom: 1rem;
    }

    .hero p {
      max-width: 650px;
      margin: auto;
      margin-bottom: 2rem;
      color: #d1fae5;
    }

    .btn {
      display: inline-block;
      background: white;
      color: var(--primary);
      padding: 0.8rem 1.7rem;
      border-radius: 30px;
      font-weight: 600;
      text-decoration: none;
      transition: 0.3s;
    }

    .btn:hover {
      transform: translateY(-2px);
    }

    /* ABOUT */
    .about {
      text-align: center;
    }

    .about p {
      max-width: 750px;
      margin: auto;
      margin-top: 1rem;
    }

    /* SERVICES */
    .services {
      background: var(--light);
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.5rem;
      margin-top: 2rem;
    }

    .card {
      background: white;
      padding: 2rem;
      border-radius: 16px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.06);
    }

    .card h3 {
      color: var(--primary);
      margin-bottom: 0.5rem;
    }

    /* TESTIMONIALS */
    .testimonial {
      background: #f8fafc;
      border-left: 4px solid var(--primary);
      padding: 1.5rem;
      border-radius: 8px;
      margin-top: 1.5rem;
    }

    /* CONTACT */
    .contact {
      text-align: center;
    }

    footer {
      text-align: center;
      padding: 1.5rem;
      background: #f1f5f9;
      color: var(--gray);
      font-size: 0.9rem;
    }

    @media (min-width: 768px) {
      .hero h1 {
        font-size: 3.3rem;
      }
    }
  </style>
</head>

<body>

  <!-- HERO -->
  <section class="hero">
    <h1>Trusted Real Estate in Kerala</h1>
    <p>
      Buy, sell, or invest in premium residential & commercial properties across Kerala
      with transparency, trust, and expert guidance.
    </p>
    <a class="btn" href="https://wa.me/91XXXXXXXXXX" target="_blank">
      WhatsApp for Property Details
    </a>
  </section>

  <!-- ABOUT -->
  <section class="about">
    <h2>About Us</h2>
    <p>
      We are a Kerala-based real estate consultancy helping clients find the right
      homes, land, and investment properties. From site visits to legal support,
      we ensure a smooth and secure property experience.
    </p>
  </section>

  <!-- SERVICES -->
  <section class="services">
    <h2 style="text-align:center;">Our Services</h2>

    <div class="grid">
      <div class="card">
        <h3>Residential Properties</h3>
        <p>Apartments, villas, and independent houses in prime locations.</p>
      </div>

      <div class="card">
        <h3>Land & Plots</h3>
        <p>Verified residential and commercial plots with clear documentation.</p>
      </div>

      <div class="card">
        <h3>Commercial Spaces</h3>
        <p>Shops, offices, and investment-ready commercial properties.</p>
      </div>

      <div class="card">
        <h3>Legal & Registration</h3>
        <p>Support with agreements, registration, and due-diligence.</p>
      </div>
    </div>
  </section>

  <!-- TESTIMONIALS -->
  <section>
    <h2 style="text-align:center;">Client Testimonials</h2>

    <div class="testimonial">
      <p>
        “Very professional service. They helped us find the perfect home in Kochi
        and handled everything smoothly.”
      </p>
      <strong>— Home Buyer, Kochi</strong>
    </div>

    <div class="testimonial">
      <p>
        “Transparent dealings and excellent property options. Highly trustworthy.”
      </p>
      <strong>— Investor, Calicut</strong>
    </div>
  </section>

  <!-- CONTACT -->
  <section class="contact">
    <h2>Get in Touch</h2>
    <p>Looking to buy or sell property in Kerala? Contact us today.</p>
    <br>
    <a class="btn" href="https://wa.me/91XXXXXXXXXX" target="_blank">
      Chat on WhatsApp
    </a>
  </section>

  <footer>
    © 2026 Kerala Real Estate. All Rights Reserved.
  </footer>

</body>
</html>
