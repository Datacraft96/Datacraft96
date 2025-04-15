<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Datacraft Solutions</title>
  <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@700&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #ffffff;
      color: #000;
      line-height: 1.6;
      word-wrap: break-word;
      overflow-wrap: break-word;
    }

    h1, h2, h3 {
      font-family: 'Merriweather', serif;
      font-weight: 700;
    }

    header {
      background: #0a5d6e;
      color: white;
      text-align: center;
      padding: 20px 10px;
    }

    img.logo {
      width: 120px;
      max-width: 100%;
      height: auto;
      margin-bottom: 10px;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }

    nav {
      background: #f8f8f8;
      text-align: center;
      padding: 10px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    nav a {
      margin: 10px;
      text-decoration: none;
      color: #0a5d6e;
      font-weight: bold;
      font-size: 16px;
      cursor: pointer;
    }

    .container {
      display: none;
      padding: 20px;
      max-width: 95%;
      margin: auto;
      text-align: justify;
    }

    .container.active {
      display: block;
    }

    iframe {
      width: 100%;
      max-width: 700px;
      height: 600px;
      border: none;
    }

    footer {
      background: #0a5d6e;
      color: white;
      text-align: center;
      padding: 15px 10px;
      font-size: 14px;
    }

    .contact-info a {
      color: #0a5d6e;
      font-weight: bold;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 1.4rem;
      }

      nav a {
        font-size: 14px;
        margin: 8px;
      }

      iframe {
        height: 500px;
      }
    }
  </style>
  <script>
    function showSection(id) {
      document.querySelectorAll('.container').forEach(section => {
        section.classList.remove('active');
      });
      document.getElementById(id).classList.add('active');
    }

    window.onload = () => showSection('home');
  </script>
</head>
<body>
  <header>
    <img src="DATA LOGO.jpg" alt="Datacraft Solutions Logo" class="logo" />
    <h1>Datacraft Solutions</h1>
    <p><em>Smart Data, Smarter Decision</em></p>
  </header>

  <nav>
    <a onclick="showSection('home')">Home</a>
    <a onclick="showSection('about')">About</a>
    <a onclick="showSection('vision')">Vision</a>
    <a onclick="showSection('services')">Services</a>
    <a onclick="showSection('contact')">Contact</a>
  </nav>

  <div class="container" id="home">
    <h2>Why Data Presentation Matters?</h2>
    <p>In today’s fast-paced world, people have so much to do — why get stuck figuring out data? Let us handle your data needs while you focus on what matters most. Good data presentation saves time, improves clarity, and empowers smarter decision-making.</p>
    <h3>Get Your Free Data Consultation</h3>
    <p><strong>Fill the form below to let us know how we can help you:</strong></p>
    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdA5aSR9sfL_rnv_-Ls4l9Q96dijPNPK1USAyZqDMvfw6S25w/viewform?embedded=true">Loading…</iframe>
  </div>

  <div class="container" id="about">
    <h2>About Us</h2>
    <p>We are experienced individuals, experts in data presentation with over 15+ years of experience in Power BI, Microsoft Advanced Excel, and data analysis tools. Whether it's a small task or a complex problem, <strong>Datacraft is your solution.</strong></p>
    <p><em>"Where Data Meets Craft."</em></p>
  </div>

  <div class="container" id="vision">
    <h2>Our Vision</h2>
    <p>To become the go-to data partner for organizations across industries, delivering clear, elegant, and meaningful data solutions that empower smarter choices and measurable success. Our vision is data clarity, your vision made real.</p>
  </div>

  <div class="container" id="services">
    <h2>Our Services & Pricing</h2>
    <ul style="text-align: left; max-width: 400px; margin: 0 auto;">
      <li>✔ Data Entry – ₹199/hour</li>
      <li>✔ Data Analysis – ₹299/hour</li>
      <li>✔ Power BI Dashboards – ₹499/hour</li>
      <li>✔ Excel Automation (Advanced) – ₹399/hour</li>
    </ul>
    <p><strong>First Task is FREE!</strong> Try us risk-free and see the value we bring.</p>
  </div>

  <div class="container" id="contact">
    <h2>Contact Us</h2>
    <p>If you have any questions or want to connect with us directly, feel free to reach out.</p>
    <div class="contact-info">
      📧 Email: <a href="mailto:datacraftsolutionss@gmail.com">datacraftsolutionss@gmail.com</a><br />
      📞 Phone: <a href="tel:+918605744143">+91 86057 44143</a>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 Datacraft Solutions. All rights reserved.<br />
      📧 datacraftsolutionss@gmail.com | 📞 +91 86057 44143</p>
  </footer>
</body>
</html>
