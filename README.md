# Republic-Signing-Solutions-LLC
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Business Website</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        header { background: #333; color: white; padding: 20px; text-align: center; }
        nav { display: flex; justify-content: center; background: #444; }
        nav a { color: white; padding: 14px 20px; text-decoration: none; }
        section { padding: 20px; text-align: center; }
        .contact-form { max-width: 400px; margin: auto; }
        input, textarea { width: 100%; padding: 10px; margin: 5px 0; }
        button { padding: 10px; background: #333; color: white; border: none; }
    </style>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            console.log("Page loaded successfully");
            
            const contactForm = document.querySelector(".contact-form");
            if (contactForm) {
                console.log("Contact form found");
                contactForm.addEventListener("submit", function(event) {
                    event.preventDefault();
                    console.log("Form submitted");
                });
            } else {
                console.log("Contact form not found");
            }
        });
    </script>
</head>
<body>
    <header>
        <h1>Republic Signing Solutions, LLC</h1>
        <p>Tagline or mission statement</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>About Us</h2>
        <p>Welcome to our business. We provide excellent services to our customers.</p>
    </section>
    <section id="services">
        <h2>Our Services</h2>
        <p>We offer high-quality services to meet your needs.</p>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <form class="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
</body>
</html>
