<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Datacraft Solutions</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f9f9f9; }
    header { background: #0073e6; color: white; text-align: center; padding: 20px; }
    nav { background: #f4f4f4; text-align: center; padding: 15px; }
    nav a {
      margin: 0 20px;
      text-decoration: none;
      color: #0073e6;
      font-weight: bold;
      font-size: 16px;
      cursor: pointer;
    }
    nav a:hover { color: #004b99; }
    .logo { width: 120px; height: auto; display: block; margin: 0 auto 10px auto; }
    .container { padding: 30px; text-align: center; }
    .hidden { display: none; }
    footer {
      background: #0073e6;
      color: white;
      text-align: center;
      padding: 12px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    form { margin-top: 20px; max-width: 500px; margin-left: auto; margin-right: auto; }
    input, textarea {
      display: block;
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      background: #0073e6;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover { background: #005bb5; }
    ul { list-style: none; padding: 0; }
    li { margin: 10px 0; }
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
  </nav>

  <!-- HOME -->
  <div class="container" id="home">
    <h2>Why Data Presentation Matters</h2>
    <p>In today’s fast-paced world, people have so much to do — why get stuck figuring out data? Let us handle your data needs while you focus on what matters most. Good data presentation saves time, improves clarity, and empowers smarter decision-making.</p>

    <h3>Register with Us</h3>
    <form>
      <input type="text" placeholder="Full Name" required />
      <input type="email" placeholder="Email" required />
      <input type="tel" placeholder="Phone Number" required />
      <textarea placeholder="Describe your problem or what you need from Datacraft Solutions..." required></textarea>
      <input type="text" placeholder="Enter OTP (sent to your phone)" required />
      <button type="submit">Register</button>
    </form>
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
    <p>To be the leading data service provider empowering businesses and individuals to make informed decisions by delivering clear, beautiful, and actionable data presentations. We aim to make data handling stress-free, accurate, and accessible for everyone.</p>
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

  <footer>
    <p>&copy; 2025 Datacraft Solutions. All rights reserved.</p>
  </footer>
</body>
</html>
