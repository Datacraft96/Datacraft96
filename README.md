
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Datacraft Solutions</title>
  <style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }

    header {
        background: #d0a85c; /* logo tone */
        color: white;
        text-align: center;
        padding: 15px;
    }

    nav {
        text-align: center;
        padding: 10px;
        background: #f4f4f4;
        flex-wrap: wrap;
    }

    nav a {
        margin: 10px 15px;
        text-decoration: none;
        color: #333;
        font-weight: bold;
        display: inline-block;
    }

    .container {
        padding: 20px;
        text-align: center;
    }

    footer {
        background: #d0a85c;
        color: white;
        text-align: center;
        padding: 10px;
        position: relative;
        bottom: 0;
        width: 100%;
    }

    img.logo {
        width: 120px;
        display: block;
        margin: 0 auto;
    }

    .banner {
        width: 100%;
        max-height: 300px;
        object-fit: cover;
    }

    .hidden {
        display: none;
    }

    .graphics {
        max-width: 100%;
        margin: 20px auto;
        display: block;
    }

    iframe {
        width: 100%;
        max-width: 700px;
        height: 600px;
        border: none;
    }

    @media (max-width: 768px) {
        header h1 {
            font-size: 1.5rem;
        }

        nav {
            flex-direction: column;
        }

        nav a {
            margin: 10px 5px;
            font-size: 1rem;
        }

        .container {
            padding: 10px;
        }

        iframe {
            height: 500px;
        }
    }
</style>

  <script>
    function showSection(sectionId) {
      document.querySelectorAll('.container').forEach(section => section.classList.add('hidden'));
      document.getElementById(sectionId).classList.remove('hidden');
    }
  </script>
</head>
<body>
  <header>
    <img src="DATA LOGO.jpg" alt="Datacraft Solutions Logo" class="logo" />
    <h1>Datacraft Solutions</h1>
    <p>"Smart Data, Smarter Decision"</p>
  </header>

  <nav>
    <a onclick="showSection('home')">Home</a>
    <a onclick="showSection('about')">About</a>
    <a onclick="showSection('vision')">Vision</a>
    <a onclick="showSection('services')">Services</a>
    <a onclick="showSection('contact')">Contact</a>
  </nav>

  <!-- HOME -->
  <div class="container" id="home">
    <h2>Why Data Presentation Matters</h2>
    <p>In today’s fast-paced world, people have so much to do — why get stuck figuring out data? Let us handle your data needs while you focus on what matters most. Good data presentation saves time, improves clarity, and empowers smarter decision-making.</p>

    <h3>Get Your Free Data Consultation </h3>
    <p><strong>Fill the form below to let us know how we can help you:</strong></p>
    
<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdA5aSR9sfL_rnv_-Ls4l9Q96dijPNPK1USAyZqDMvfw6S25w/viewform?embedded=true" width="700" height="600" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>

  </div>

  <!-- ABOUT -->
  <div class="container hidden" id="about">
    <h2>About Us</h2>
    <p>We are experienced individuals, experts in data presentation with over 15+ years of experience in Power BI, Microsoft Advanced Excel, and data analysis tools. Whether it's a small task or a complex problem, <strong>Datacraft is your solution.</strong></p>
    <p><em>"Where Data Meets Craft."</em></p>
  </div>

  <!-- VISION -->
  <div class="container hidden" id="vision">
    <h2>Our Vision</h2>
    <p>To become the go-to data partner for organizations across industries, delivering clear, elegant, and meaningful data solutions that empower smarter choices and measurable success. Our vision is data clarity, your vision made real.</p>
  </div>

  <!-- SERVICES -->
  <div class="container hidden" id="services">
    <h2>Our Services & Pricing</h2>
    <ul>
      <li>✔ Data Entry – ₹199/hour</li>
      <li>✔ Data Analysis – ₹299/hour</li>
      <li>✔ Power BI Dashboards – ₹499/hour</li>
      <li>✔ Excel Automation (Advanced) – ₹399/hour</li>
    </ul>
    <p><strong>First Task is FREE!</strong> Try us risk-free and see the value we bring.</p>
  </div>

  <!-- CONTACT -->
  <div class="container hidden" id="contact">
    <h2>Contact Us</h2>
    <p>If you have any questions or want to connect with us directly, feel free to reach out.</p>
    <div class="contact-info">
      📧 Email: <a href="mailto:datacraftsolutionss@gmail.com">datacraftsolutionss@gmail.com</a><br/>
      📞 Phone: <a href="tel:+918605744143">+91 86057 44143</a>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 Datacraft Solutions. All rights reserved.<br>
    📧 datacraftsolutionss@gmail.com | 📞 +91 86057 44143</p>
  </footer>
</body>
</html>
