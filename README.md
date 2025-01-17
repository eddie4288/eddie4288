<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    White Glove Delivery & Installation
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Home Section -->
    <header>
        <h1>Impeccable delivery and installation, designed for you.</h1>
        <p>We specialize in the delivery, installation, and care of premium appliances and furniture.</p>
    <!-- About Us Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>With years of experience, we deliver personalized service and high-quality logistics solutions. Our values include punctuality, professionalism, and precision.</p>
        <h3>Certifications</h3>
        <p>We have experience with brands like Thermador and Sub-Zero. Our team is fully licensed and certified.</p>
    </section>
    <!-- Services Section -->
    <section id="services">
        <h2>Our Services</h2>
        <div>
            <h3>White Glove Delivery</h3>
            <p>Precision deliveries from transport to placement in your home.</p>
        </div>
        <div>
            <h3>Professional Installation</h3>
            <p>We install appliances and furniture, ensuring perfection before leaving.</p>
        </div>
        <div>
            <h3>Assembly and Setup</h3>
            <p>We assemble furniture and wall-mount TVs, ready for immediate use.</p>
        </div>
        <div>
            <h3>Packaging and Waste Removal</h3>
            <p>We collect and recycle leftover materials to leave your space clean.</p>
        </div>
        <button onclick="window.location.href='#contact'">Discover more</button>
    </section>
    <!-- Portfolio Section -->
    <section id="portfolio">
        <h2>Completed Projects</h2>
        <div>
            <img src="subzero-installation.jpg" alt="Sub-Zero refrigerator installation">
            <p>Sub-Zero refrigerator installation</p>
        </div>
        <div>
            <img src="modern-dining-set.jpg" alt="Modern dining set assembly">
            <p>Modern dining set assembly</p>
        </div>
        <div>
            <img src="tv-wall-mount.jpg" alt="TV wall mount in a minimalist living room">
            <p>TV wall mount in a minimalist living room</p>
        </div>
        <blockquote>
            "The team was professional and careful. Highly recommended!" – Naples, FL
        </blockquote>
    </section>
    <!-- Contact Us Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" required><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br>
            <label for="phone">Phone:</label><br>
            <input type="tel" id="phone" name="phone" required><br>
            <label for="service">Service Needed:</label><br>
            <select id="service" name="service">
                <option>White Glove Delivery</option>
                <option>Installation</option>
                <option>Assembly and Setup</option>
            </select><br>
            <label for="details">Additional Details:</label><br>
            <textarea id="details" name="details"></textarea><br>
            <button type="submit">Submit</button>
        </form>
    </section>
    <!-- Footer -->
    <footer>
        <p>Follow us on:  
            <a href="#">Facebook</a> | <a href="#">Instagram</a> | <a href="#">LinkedIn</a>
        </p>
        <p>&copy; 2025 White Glove Services. All rights reserved.</p>
    </footer>
</body>
</html>
