# motivation-app
A simple motivation app made with HTML, CSS and JavaScript.
<head>
  <title>Daily Motivation</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="icon" href="icon.png">
</head>
<style>
.welcome {
  text-align: center;
  padding: 40px 20px;
  background: #1e88e5;
  color: white;<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Daily Motivation</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="icon" href="icon.png">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f2f4f7;
      color: #333;
    }

    /* Navbar */
    nav {
      background: #1e88e5;
      padding: 15px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      font-size: 14px;
    }

    /* Hero Section */
    .hero {
      background: linear-gradient(135deg, #1e88e5, #42a5f5);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    .hero h1 {
      font-size: 32px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 16px;
      opacity: 0.95;
    }

    /* Sections */
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      margin-bottom: 30px;
      color: #1e88e5;
    }

    /* Cards */
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
      text-align: center;
    }

    .card h3 {
      margin-bottom: 10px;
      color: #333;
    }

    .card p {
      font-size: 14px;
      color: #666;
    }

    /* Quotes */
    .quote {
      background: white;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
      margin-bottom: 20px;
      font-size: 18px;
    }

    /* Footer */
    footer {
      background: #1e88e5;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>

<body>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#features">Features</a>
    <a href="#quotes">Quotes</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Home -->
  <div class="hero" id="home">
    <h1>Daily Motivation</h1>
    <p>Inspire your life. One quote at a time.</p>
  </div>

  <!-- Features -->
  <section id="features">
    <h2>Why Choose This App?</h2>
    <div class="cards">
      <div class="card">
        <h3>Positive Thinking</h3>
        <p>Daily motivational thoughts to keep you focused and strong.</p>
      </div>
      <div class="card">
        <h3>Simple Design</h3>
        <p>Clean and distraction-free experience for everyone.</p>
      </div>
      <div class="card">
        <h3>Free Forever</h3>
        <p>No subscription. Just motivation.</p>
      </div>
    </div>
  </section>

  <!-- Quotes -->
  <section id="quotes">
    <h2>Motivational Quotes</h2>

    <div class="quote">
      “Wake up with determination. Go to bed with satisfaction.”
    </div>

    <div class="quote">
      “Your future depends on what you do today.”
    </div>

    <div class="quote">
      “Small steps every day lead to big results.”
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact</h2>
    <div class="card">
      <p>Email: yourname@gmail.com</p>
      <p>Made with ❤️ for positive people</p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    © 2026 Daily Motivation | All Rights Reserved
  </footer>

</body>
</html>

}
</style>
