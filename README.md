<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Datacraft Solutions</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #ffffff;
      color: #000;
      line-height: 1.6;
      word-wrap: break-word;
      overflow-wrap: break-word;
    }

    header {
      background: #0a5d6e;
      color: white;
      text-align: center;
      padding: 20px 10px;
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

    img.logo {
      width: 140px;
      display: block;
      margin: 0 auto 10px auto;
    }

    .iframe-container {
      position: relative;
      width: 100%;
      padding-bottom: 75%;
      height: 0;
      overflow: hidden;
      max-width: 700px;
      margin: 20px auto;
    }

    .iframe-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
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

    ul {
      text-align: left;
      max-width: 400px;
      margin: 0 auto;
      padding-left: 20px;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 1.4rem;
      }

      nav a {
        font-size: 14px;
        margin: 8px;
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
    <h2>Why Data Presentation Matters</h2>
    <p>In today’s fast-paced world, people have so much to do — why get stuck figuring out data? Let us handle your data needs while you focus on what matters most. Good data presentation saves time, improves clarity, and empowers smarter decision-making.</p>
    <h3>Get Your Free Data Consultation</h3>
    <p><strong>Fill the form below to let us know how we can help you:</strong></p>
    <div class="iframe-container">
      <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdA5aSR9sfL_rnv_-Ls4l9Q96dijPNPK1USAyZqDMvfw6S25w/viewform?embedded=true">Loading…</iframe>
    </div>
  </div>

  <div class="container" id="about">
    <h2>About Us</h2>
    <p>We

