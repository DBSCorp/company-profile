<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DBS Innovation Enterprise</title>
    <link rel="stylesheet" href="styles.css"> <!-- Consider moving inline styles into styles.css for better organization -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
        }
        nav {
            position: fixed; /* Fixed navigation might cover content, add padding-top to .container */
            top: 0;
            width: 100%;
            background-color: white;
            z-index: 10;
            padding: 10px 0;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            text-decoration: none;
            color: black;
            font-weight: bold;
            padding: 10px;
            transition: color 0.3s ease-in-out; /* Added hover effect for better UX */
        }
        nav ul li a:hover {
            color: #007bff; /* Change color on hover */
        }
        .container {
            max-width: 800px;
            margin: 80px auto 20px auto; /* Add more margin-top if needed due to fixed nav */
            padding: 20px;
            background: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }
        section {
            padding: 40px 20px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
        }

    
    <nav>
        <ul>
            <li><a href="#about-us">About Us</a></li>
            <li><a href="#our-products">Our Products</a></li>
            <li><a href="#why-choose-us">Why Choose Us</a></li>
            <li><a href="#contact-us">Contact Us</a></li>
            <li><a href="#careers">Careers</a></li>
            <li><a href="#privacy-policy">Privacy Policy</a></li>
        </ul>
    </nav>
    
    <div class="container">
        <section id="about-us">
            <h2>About Us</h2>
            <p>DBS Innovation Enterprise is committed to revolutionizing the business landscape with our innovative foldable stalls.</p>
            <h3>Our Mission</h3>
            <ul>
                <li>Provide high-quality, durable, and versatile foldable stalls.</li>
                <li>Support local businesses with practical and affordable solutions.</li>
                <li>Continuously innovate to stay at the forefront of efficiency.</li>
            </ul>
            <h3>Our Vision</h3>
            <p>To be the leading provider of innovative and portable business solutions across Malaysia and beyond.</p>
        </section>
        
        <section id="our-products">
            <h2>Our Products</h2>
            <ul>
                <li><strong>Standard Foldable Stall</strong> – Ideal for small businesses.</li>
                <li><strong>Premium Foldable Stall</strong> – Enhanced features with additional storage.</li>
                <li><strong>Custom Foldable Stalls</strong> – Tailored branding and design.</li>
            </ul>
        </section>
        
        <section id="why-choose-us">
            <h2>Why Choose Us</h2>
            <ul>
                <li>✔ Durability & Quality</li>
                <li>✔ Ease of Use</li>
                <li>✔ Customization Options</li>
                <li>✔ Competitive Pricing</li>
                <li>✔ Customer Satisfaction</li>
            </ul>
        </section>
        
        <section id="contact-us">
            <h2>Contact Us</h2>
            <p>Email: <a href="mailto:your-email@example.com">your-email@example.com</a></p> <!-- Replace with actual email -->
            <p>Phone: +60 XXXXXXXXXX</p> <!-- Replace with actual phone number -->
            <p>Address: [Your Business Address]</p> <!-- Add actual business address -->
            <p>Follow us on: <a href="#">Facebook</a> | <a href="#">Instagram</a> | <a href="#">LinkedIn</a></p>
        </section>
        
        <section id="careers">
            <h2>Careers</h2>
            <p>Join our team and be part of an innovative company. Check our latest job openings: <a href="#">Careers Page</a></p>
        </section>
        
        <section id="privacy-policy">
            <h2>Privacy Policy</h2>
            <p>Read our <a href="#">Privacy Policy</a> to understand how we handle your personal information.</p>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2025 DBS Innovation Enterprise. All rights reserved.</p>
    </footer>
</body>
</html>
