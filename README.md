<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Datacraft Solutions</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        header { background: #0073e6; color: white; text-align: center; padding: 15px; }
        nav { text-align: center; padding: 10px; background: #f4f4f4; }
        nav a { margin: 0 15px; text-decoration: none; color: #333; font-weight: bold; cursor: pointer; }
        .container { padding: 20px; text-align: center; }
        footer { background: #0073e6; color: white; text-align: center; padding: 10px; position: fixed; bottom: 0; width: 100%; }
        img.logo { width: 150px; display: block; margin: 0 auto; }
        .banner { width: 100%; max-height: 300px; object-fit: cover; }
        .hidden { display: none; }
        .graphics { max-width: 80%; margin: 20px auto; display: block; }
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
        <img src="logo.png" alt="Datacraft Solutions Logo" class="logo">
        <h1>Welcome to Datacraft Solutions</h1>
        <p>"Transforming Data, Empowering Decisions"</p>
    </header>
    <nav>
        <a onclick="showSection('home')">Home</a>
        <a onclick="showSection('services')">Services</a>
        <a onclick="showSection('about')">About Us</a>
        <a onclick="showSection('contact')">Contact</a>
    </nav>
    <img src="banner.jpg" alt="Datacraft Solutions Banner" class="banner">
    <div class="container" id="home">
        <h2>Home</h2>
        <p>Providing top-notch data entry and presentation services to streamline your business.</p>
    </div>
    <div class="container hidden" id="services">
        <h2>Our Services</h2>
        <p>We offer data entry, data analysis, financial reporting, and presentation services.</p>
        <img src="services-graphic.jpg" alt="Our Services" class="graphics">
    </div>
    <div class="container hidden" id="about">
        <h2>About Us</h2>
        <p>We are a team of experienced individuals highly motivated about data and have given our best in the media sector with the biggest production houses.</p>
    </div>
    <div class="container hidden" id="contact">
        <h2>Contact Us</h2>
        <p>Email: datacraftsolutionss@gmail.com</p>
    </div>
    <footer>
        <p>&copy; 2025 Datacraft Solutions. All Rights Reserved.</p>
    </footer>
</body>
</html>
