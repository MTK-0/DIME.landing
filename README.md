<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>DIME | Revolutionizing Healthcare Through Data-Driven Solutions</title>
    <style>
        /* General Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f4f9;
            color: #2c3e50;
            line-height: 1.6;
        }
        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header */
        header {
            background-color: #ffffff;
            box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            z-index: 1000;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 5%;
            max-width: 1200px;
            margin: auto;
        }
        nav h1 {
            font-size: 1.8rem;
            color: #005082;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 30px;
        }
        nav ul li {
            font-size: 1rem;
        }
        nav ul li a:hover {
            border-bottom: 2px solid #005082;
            padding-bottom: 2px;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            background: url('https://source.unsplash.com/1600x900/?hospital,technology') no-repeat center center/cover;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 0 5%;
            background-blend-mode: overlay;
            background-color: rgba(0, 80, 130, 0.6);
        }
        .hero h2 {
            font-size: 3rem;
            font-weight: 600;
        }
        .hero p {
            font-size: 1.2rem;
            margin: 20px 0;
        }
        .cta-button {
            padding: 12px 30px;
            background-color: #ff4f4f;
            border: none;
            color: white;
            border-radius: 30px;
            font-size: 1rem;
            transition: background-color 0.3s ease;
            cursor: pointer;
        }
        .cta-button:hover {
            background-color: #d94141;
        }

        /* Section Styles */
        .section {
            padding: 80px 5%;
            text-align: center;
        }
        .section h3 {
            font-size: 2.5rem;
            color: #005082;
            margin-bottom: 20px;
        }
        .section p {
            font-size: 1.1rem;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.8;
            color: #555;
        }

        /* Alternate Background */
        .alt-background {
            background-color: #f9fafc;
        }

        /* Footer */
        footer {
            background-color: #002e47;
            color: #ffffff;
            padding: 40px 5%;
            text-align: center;
        }
        footer p {
            margin-bottom: 10px;
            font-size: 0.9rem;
        }
        footer a {
            color: #ff4f4f;
            font-weight: bold;
        }
        footer a:hover {
            text-decoration: underline;
        }

        /* Media Queries */
        @media (max-width: 768px) {
            .hero h2 {
                font-size: 2.2rem;
            }
            .hero p {
                font-size: 1rem;
            }
            .cta-button {
                padding: 10px 20px;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <nav>
            <h1>DIME</h1>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#solutions">Solutions</a></li>
                <li><a href="#partners">Partners</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div>
            <h2>Transforming Healthcare Through Data-Driven Insights</h2>
            <p>At DIME, we leverage advanced data analytics and AI to revolutionize patient care and healthcare systems worldwide.</p>
            <button class="cta-button">Get Involved</button>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <h3>About DIME</h3>
        <p>DIME is at the forefront of healthcare transformation, driven by a mission to create data-powered healthcare solutions that predict and prevent diseases, improve patient outcomes, and streamline provider workflows. Our goal is to foster a future where healthcare is personalized, predictive, and accessible for everyone.</p>
    </section>

    <!-- Solutions Section -->
    <section id="solutions" class="section alt-background">
        <h3>Our Solutions</h3>
        <p>We develop AI-driven tools that enhance diagnostic precision, automate administrative processes, and offer actionable insights to healthcare providers. From electronic health records (EHR) to patient health apps, our solutions empower providers and patients alike. Prebook our EHR system today to transform how you manage patient data.</p>
    </section>

    <!-- Partners Section -->
    <section id="partners" class="section">
        <h3>Partner with Us</h3>
        <p>We're actively seeking mentors, strategic partners, and talented individuals passionate about healthcare innovation. Join us in shaping the future of healthcare, one breakthrough at a time. Let’s work together to make an impact on global health systems.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section alt-background">
        <h3>Contact Us</h3>
        <p>Interested in partnering, mentoring, or joining our team? Reach out to us at <a href="mailto:contact@dimehealthtech.com">contact@dimehealthtech.com</a>. Together, we can revolutionize healthcare.</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 DIME Health Tech. All rights reserved.</p>
        <p><a href="https://www.dimehealthtech.com">Visit our website</a></p>
    </footer>

</body>
</html>
