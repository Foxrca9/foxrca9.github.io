<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Service Website</title>
    <link rel="stylesheet" href="styles.css">
    <script src="scripts.js" defer></script>
</head>
<body>
    <header>
        <div class="container">
            <h1>Online Service</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <main>
        <section id="home">
            <div class="container">
                <h2>Welcome to Our Online Service</h2>
                <p>We offer the best online services to meet your needs.</p>
            </div>
        </section>
        <section id="about">
            <div class="container">
                <h2>About Us</h2>
                <p>Our company provides top-notch online services with a focus on quality and customer satisfaction.</p>
            </div>
        </section>
        <section id="services">
            <div class="container">
                <h2>Our Services</h2>
                <ul>
                    <li>Service 1: Description of service 1.</li>
                    <li>Service 2: Description of service 2.</li>
                    <li>Service 3: Description of service 3.</li>
                </ul>
            </div>
        </section>
        <section id="contact">
            <div class="container">
                <h2>Contact Us</h2>
                <form id="contactForm">
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                    <label for="message">Message:</label>
                    <textarea id="message" name="message" required></textarea>
                    <button type="submit">Submit</button>
                </form>
            </div>
        </section>
    </main>
    <footer>
        <div class="container">
            <p>&copy; 2024 Online Service. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
