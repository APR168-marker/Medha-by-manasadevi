<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Medha by Manasadevi</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <img src="images/logo.png" alt="Medha by Manasadevi Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h1>Welcome to Medha by Manasadevi</h1>
        <p>Your beauty, our passion.</p>
        <a href="#services" class="cta-button">Explore Services</a>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="service-list">
            <div class="service-item">
                <img src="images/haircut.jpg" alt="Haircut">
                <h3>Haircut & Styling</h3>
                <p>Professional haircuts and styling for all hair types.</p>
            </div>
            <div class="service-item">
                <img src="images/spa.jpg" alt="Spa">
                <h3>Spa & Relaxation</h3>
                <p>Rejuvenate your body and mind with our spa treatments.</p>
            </div>
            <div class="service-item">
                <img src="images/makeup.jpg" alt="Makeup">
                <h3>Makeup & Bridal</h3>
                <p>Get the perfect look for your special day.</p>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>Medha by Manasadevi is a premium grooming salon dedicated to enhancing your natural beauty. Our team of experts provides personalized services to make you feel confident and radiant.</p>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <div class="gallery-images">
            <img src="images/gallery1.jpg" alt="Gallery Image 1">
            <img src="images/gallery2.jpg" alt="Gallery Image 2">
            <img src="images/gallery3.jpg" alt="Gallery Image 3">
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2023 Medha by Manasadevi. All rights reserved.</p>
    </footer>

    <!-- JavaScript -->
    <script src="script.js"></script>
</body>
</html>
