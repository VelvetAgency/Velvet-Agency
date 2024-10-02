<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Velvet Agency - High-quality marketing services to boost business sales, provide real-time analytics, and keep you updated with monthly subscriptions.">
    <title>Velvet Agency</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            color: #fff;
            background: linear-gradient(135deg, #001f3f 25%, #004080 100%);
            animation: backgroundAnimation 10s infinite alternate;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        @keyframes backgroundAnimation {
            0% { background: #001f3f; }
            100% { background: #004080; }
        }
        header {
            text-align: center;
            padding: 40px 0;
            background: rgba(0, 0, 0, 0.7);
        }
        header h1 {
            margin: 0;
            font-size: 48px;
            letter-spacing: 2px;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ffcc00; /* Highlight color on hover */
        }
        section {
            flex: 1;
            padding: 40px 20px;
            max-width: 1200px;
            margin: auto;
        }
        .services {
            background-color: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
        }
        .service-item {
            margin-bottom: 20px;
            padding: 10px;
            border-radius: 8px;
            background-color: rgba(255, 255, 255, 0.2);
            transition: transform 0.3s;
        }
        .service-item:hover {
            transform: scale(1.05);
        }
        footer {
            background: rgba(0, 0, 0, 0.7);
            text-align: center;
            padding: 20px 0;
        }
        .social-links a {
            margin: 0 10px;
            color: #fff;
            text-decoration: none;
            font-size: 24px;
            transition: color 0.3s;
        }
        .social-links a:hover {
            color: #ffcc00; /* Highlight color on hover */
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        @media (max-width: 768px) {
            header h1 {
                font-size: 36px;
            }
            nav a {
                font-size: 14px;
            }
            .social-links a {
                font-size: 18px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Velvet Agency</h1>
    <nav>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <p>High-Quality Marketing Services for Your Business</p>
</header>

<section id="services">
    <div class="services">
        <h2>Our Services</h2>
        <div class="service-item">
            <h3>Business Boost Sales</h3>
            <img src="https://via.placeholder.com/600x400.png?text=Business+Boost" alt="Business Boost Sales">
            <p>We help businesses enhance their sales through targeted marketing strategies and impactful campaigns.</p>
        </div>
        <div class="service-item">
            <h3>Monthly Subscriptions</h3>
            <img src="https://via.placeholder.com/600x400.png?text=Monthly+Subscriptions" alt="Monthly Subscriptions">
            <p>Stay updated on your business performance with our monthly subscription packages that provide continuous insights.</p>
        </div>
        <div class="service-item">
            <h3>Real-Time Analytics & Data</h3>
            <img src="https://via.placeholder.com/600x400.png?text=Real-Time+Analytics" alt="Real-Time Analytics">
            <p>Get real-time data on your business metrics to make informed decisions that drive growth and success.</p>
        </div>
    </div>
</section>

<footer id="contact">
    <h2>Contact Us</h2>
    <p>Reach out to Velvet Agency through our social media channels or on Discord.</p>
    <div class="social-links">
        <a href="https://facebook.com" target="_blank"><i class="fab fa-facebook"></i></a>
        <a href="https://instagram.com" target="_blank"><i class="fab fa-instagram"></i></a>
        <a href="https://discord.com" target="_blank"><i class="fab fa-discord"></i></a>
    </div>
</footer>

</body>
</html>
