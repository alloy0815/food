<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foodies Delight</title>
    <style>
        /* CSS goes here */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
        }

        header {
            background: #333;
            color: #fff;
            padding: 1rem;
        }

        header nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
        }

        header nav ul li {
            margin: 0 15px;
        }

        header nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.1rem;
        }

        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://source.unsplash.com/1600x800/?food') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
        }

        .hero-content h1 {
            font-size: 4rem;
            margin-bottom: 1rem;
        }

        .hero-content p {
            font-size: 1.5rem;
            margin-bottom: 2rem;
        }

        .cta-button {
            background-color: #ff6600;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 1.2rem;
            text-decoration: none;
            border-radius: 5px;
        }

        .cta-button:hover {
            background-color: #ff3300;
        }

        .menu {
            padding: 4rem 2rem;
            background-color: #f4f4f4;
            text-align: center;
        }

        .menu h2 {
            margin-bottom: 3rem;
            font-size: 2.5rem;
        }

        .menu-items {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 2rem;
        }

        .menu-item {
            background: white;
            padding: 20px;
            width: 250px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }

        .menu-item img {
            width: 100%;
            height: 160px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .menu-item h3 {
            font-size: 1.5rem;
            color: #333;
        }

        .menu-item p {
            font-size: 1rem;
            color: #666;
        }

        .price {
            font-size: 1.3rem;
            font-weight: bold;
            color: #ff6600;
            margin-top: 10px;
        }

        .contact {
            background: #fff;
            padding: 3rem 2rem;
            text-align: center;
        }

        .contact form {
            max-width: 600px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
        }

        .contact input, .contact textarea {
            margin: 10px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }

        .contact button {
            background-color: #ff6600;
            color: white;
            padding: 15px;
            border: none;
            cursor: pointer;
            font-size: 1.2rem;
            border-radius: 5px;
        }

        .contact button:hover {
            background-color: #ff3300;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background: #333;
            color: white;
            margin-top: 3rem;
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Welcome to Foodies Delight</h1>
            <p>Where great food meets great taste</p>
            <a href="#menu" class="cta-button">Explore Menu</a>
        </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="menu">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="menu-item">
                <img src="https://source.unsplash.com/400x300/?burger" alt="Burger">
                <h3>Cheese Burger</h3>
                <p>Delicious cheese burger with fresh toppings.</p>
                <p class="price">$5.99</p>
            </div>
            <div class="menu-item">
                <img src="https://source.unsplash.com/400x300/?pizza" alt="Pizza">
                <h3>Margherita Pizza</h3>
                <p>Classic pizza with fresh mozzarella and basil.</p>
                <p class="price">$8.99</p>
            </div>
            <div class="menu-item">
                <img src="https://source.unsplash.com/400x300/?pasta" alt="Pasta">
                <h3>Spaghetti Bolognese</h3>
                <p>Rich meat sauce served over spaghetti.</p>
                <p class="price">$7.49</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <input type="text" id="name" placeholder="Your Name" required>
            <input type="email" id="email" placeholder="Your Email" required>
            <textarea id="message" placeholder="Your Message" required></textarea>
            <button type="submit" class="cta-button">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Foodies Delight. All rights reserved.</p>
    </footer>

    <script>
        // JavaScript goes here
        document.getElementById('contact-form').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('Thank you for reaching out! We will get back to you soon.');
            document.getElementById('contact-form').reset();
        });
    </script>

</body>
</html>
