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
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
}

header h1 {
    text-align: center;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 2rem 0;
}

section {
    margin-bottom: 2rem;
}

section h2 {
    text-align: center;
    margin-bottom: 1rem;
}

section .container {
    text-align: center;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
}

form label {
    display: block;
    margin: 0.5rem 0 0.2rem;
}

form input, form textarea {
    width: 100%;
    padding: 0.5rem;
    margin-bottom: 1rem;
}

form button {
    background: #333;
    color: #fff;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
}

</html>
document.addEventListener('DOMContentLoaded', function() {
    const form = document.getElementById('contactForm');

    form.addEventListener('submit', function(event) {
        event.preventDefault();

        const name = document.getElementById('name').value;
        const email = document.getElementById('email').value;
        const message = document.getElementById('message').value;

        if (name && email && message) {
            alert('Thank you for contacting us, ' + name + '!');
            form.reset();
        } else {
            alert('Please fill out all fields.');
        }
    });
});
