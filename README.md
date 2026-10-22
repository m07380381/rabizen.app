# rabizen.app
Official RABIZEN.app Website

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#0b1020">
  <title>RABIZEN — Ideas into Impact</title>
  <meta name="description" content="RABIZEN is a forward-thinking brand built around innovation, trust and growth.">

  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: Arial, sans-serif;
      background: #0b1020;
      color: #f5f5f5;
      line-height: 1.7;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 22px 8%;
      border-bottom: 1px solid #252b3c;
    }

    .logo {
      font-size: 25px;
      font-weight: bold;
      letter-spacing: 2px;
      color: #e8c477;
    }

    nav a {
      color: #ddd;
      text-decoration: none;
      margin-left: 20px;
      font-size: 14px;
    }

    .hero {
      min-height: 75vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 70px 20px;
      background: radial-gradient(ellipse at top, #1c2947, #0b1020 70%);
    }

    .tag {
      color: #e8c477;
      letter-spacing: 4px;
      font-size: 12px;
      margin-bottom: 20px;
    }

    h1 {
      font-size: clamp(42px, 9vw, 76px);
      line-height: 1.15;
      margin-bottom: 22px;
    }

    h1 span { color: #e8c477; }

    .hero p {
      max-width: 560px;
      color: #b9c0d0;
      margin-bottom: 30px;
    }

    .button {
      display: inline-block;
      background: #e8c477;
      color: #101525;
      padding: 12px 27px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }

    section { padding: 70px 8%; }

    .section-title {
      text-align: center;
      font-size: 32px;
      margin-bottom: 15px;
    }

    .intro {
      text-align: center;
      color: #b9c0d0;
      max-width: 650px;
      margin: 0 auto 35px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
      gap: 20px;
      margin-top: 35px;
    }

    .card {
      background: #131a2d;
      border: 1px solid #283149;
      padding: 28px;
      border-radius: 12px;
    }

    .card h3 {
      color: #e8c477;
      margin-bottom: 12px;
    }

    .card p { color: #b9c0d0; }

    .contact { text-align: center; background: #101729; }

    footer {
      padding: 25px 15px;
      text-align: center;
      color: #929bb0;
      border-top: 1px solid #252b3c;
      font-size: 13px;
    }

    @media (max-width: 500px) {
      header { padding: 18px 5%; }
      .logo { font-size: 21px; }
      nav a { margin-left: 10px; font-size: 12px; }
      section { padding: 55px 6%; }
    }
  </style>
</head>

<body>
  <header>
    <div class="logo">RABIZEN</div>
    <nav>
      <a href="#about">About</a>
      <a href="#vision">Vision</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <div class="tag">WELCOME TO RABIZEN</div>
      <h1>Ideas into <span>Impact.</span></h1>
      <p>
        A forward-thinking brand built on creativity, innovation
        and trust. We believe every great journey begins with an idea.
      </p>
      <a class="button" href="#about">Discover RABIZEN</a>
    </section>

    <section id="about">
      <h2 class="section-title">About RABIZEN</h2>
      <p class="intro">
        RABIZEN represents ambition, fresh thinking and the courage
        to build something meaningful for the future.
      </p>

      <div class="cards">
        <div class="card">
          <h3>Innovation</h3>
          <p>Exploring new ideas and creating smarter possibilities.</p>
        </div>
        <div class="card">
          <h3>Trust</h3>
          <p>Building lasting relationships through honesty and reliability.</p>
        </div>
        <div class="card">
          <h3>Growth</h3>
          <p>Moving forward with purpose, learning and continuous improvement.</p>
        </div>
      </div>
    </section>

    <section id="vision">
      <h2 class="section-title">Our Vision</h2>
      <p class="intro">
        To grow into a trusted name that connects ideas, people
        and opportunities through innovation and meaningful work.
      </p>
    </section>

    <section class="contact" id="contact">
      <h2 class="section-title">Let's Build the Future</h2>
      <p class="intro">
        RABIZEN is just getting started. Stay connected as our journey unfolds.
      </p>
      <a class="button" href="mailto:hello@rabizen.app">Get in Touch</a>
    </section>
  </main>

  <footer>
    © <span id="year"></span> RABIZEN. All rights reserved.
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
