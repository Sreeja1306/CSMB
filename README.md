<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tour Guide</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Tour Guide</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h2>Explore Amazing Places</h2>
        <p>Your adventure starts here. Let us guide you to the best destinations.</p>
        <a href="#services" class="btn">Discover More</a>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Us</h2>
            <p>We are passionate travel experts who curate the best travel experiences for you.</p>
        </div>
    </section>

    <section id="services" class="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="service-item">
                <h3>Guided Tours</h3>
                <p>Explore new places with our expert local guides.</p>
            </div>
            <div class="service-item">
                <h3>Custom Packages</h3>
                <p>We create personalized travel packages tailored to your interests.</p>
            </div>
            <div class="service-item">
                <h3>Group Tours</h3>
                <p>Join group tours and meet like-minded travelers from all over the world.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form action="#">
                <label for="name">Your Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Your Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Your Message</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit" class="btn">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Tour Guide | All rights reserved.</p>
    </footer>
</body>
</html>

