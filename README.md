<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url(a2-white-page_109181-143.avif);
            background-position: center;
            background-size: cover;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        nav a:hover {
            background-color: #666;
        }
        .hero {
            height: 400px;
            background-image: url(pngtree-delicious-food-illustration-picture-image_2423194.jpg);
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        .hero h1 {
            font-size: 4em;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .menu-section, .about-section, .contact-section, .reservation-section {
            margin: 40px 0;
        }
        h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .menu-item {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
            border-bottom: 1px solid #ddd;
        }
        .contact-form, .reservation-form {
            display: flex;
            
            flex-direction: column;
            max-width: 600px;
            margin: auto;
        }
        .contact-form input, .contact-form textarea, .reservation-form input, .reservation-form select {
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
        }
        .contact-form button, .reservation-form button {
            padding: 10px;
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }

        .about-section {
    margin: 40px 0;
    padding: 20px;
    background-image: url(depositphotos_104648666-stock-photo-group-of-people-brainstorming-on.jpg);
    background-size: cover;
    background-position: center;
    color: white; 
    text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.7);
}

.reservation-section {
    margin: 40px 0;
    padding: 40px;
    background-image: url(istockphoto-1161231986-612x612.jpg);
    background-size: cover;
    background-position: center;
    color: white; 
    text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.7);
}

.contact-section {
    margin: 40px 0;
    padding: 40px;
    background-image: url(communication-and-technology-concept-hand-putting-wooden-block-cube-symbol-telephone-email-address-website-page-contact-us-or-e-mail-marketing-contact-us-in-customer-support-c.jpg); 
    background-size: cover;
    background-position: center;
    color: white; 
    text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.7);
}

.menu-section {
    margin: 40px 0;
    padding: 40px;
    background-image: url(5a3c246e-b5ec-4068-999b-bd3579d7ecb0.webp); 
    background-size: cover;
    background-position: center;
    color: white; 
    text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.7);
    position: relative; 
        }

    </style>
</head>
<body>

<header>
    <h1>CULINARY PLEASURES</h1>
    <h1>Welcome to Our Restaurant</h1>
</header>

<nav>
    <a href="#menu">Menu</a>
    <a href="#contact">contact</a>
    <a href="#reservation">Table Reservation</a>
    <a href="#about">About us</a>
</nav>

<div class="hero">
    <h1>Delicious Food Awaits</h1><br><br><br>
</div>

<div class="container">
    
    <section id="menu" class="menu-section">
        <h2>Our Menu</h2>
       
        <div class="menu-category">
            <h3>Appetizers</h3>
            <div class="menu-item">
                <span>Garlic Bread</span>
                <span>Rs 80</span>
            </div>
            <div class="menu-item">
                <span>Bruschetta</span>
                <span>Rs 120</span>
            </div>
            <div class="menu-item">
                <span>Chicken Wings (6 pieces)</span>
                <span>Rs 200</span>
            </div>
            <div class="menu-item">
                <span>Mozzarella Sticks</span>
                <span>Rs 150</span>
            </div>
            <div class="menu-item">
                <span>Tomato Basil Soup</span>
                <span>Rs 100</span>
            </div>
        </div>

        <div class="menu-category">
            <h3>Main Courses</h3>
            <div class="menu-item">
                <span>Grilled Salmon</span>
                <span>Rs 350</span>
            </div>
            <div class="menu-item">
                <span>Spaghetti Carbonara</span>
                <span>Rs 300</span>
            </div>
            <div class="menu-item">
                <span>Margherita Pizza (12 inches)</span>
                <span>Rs 250</span>
            </div>
            <div class="menu-item">
                <span>Butter Chicken with Naan</span>
                <span>Rs 400</span>
            </div>
            <div class="menu-item">
                <span>Veggie Lasagna</span>
                <span>Rs 270</span>
            </div>
        </div>

        <div class="menu-category">
            <h3>Desserts</h3>
            <div class="menu-item">
                <span>Chocolate Lava Cake</span>
                <span>Rs 150</span>
            </div>
            <div class="menu-item">
                <span>Tiramisu</span>
                <span>Rs 180</span>
            </div>
            <div class="menu-item">
                <span>Cheesecake (Blueberry/Strawberry)</span>
                <span>Rs 200</span>
            </div>
            <div class="menu-item">
                <span>Gulab Jamun with Ice Cream</span>
                <span>Rs 100</span>
            </div>
        </div>

        <div class="menu-category">
            <h3>Beverages</h3>
            <div class="menu-item">
                <span>Fresh Lime Soda</span>
                <span>Rs 50</span>
            </div>
            <div class="menu-item">
                <span>Iced Tea (Peach/Lemon)</span>
                <span>Rs 60</span>
            </div>
            <div class="menu-item">
                <span>Cappuccino</span>
                <span>Rs 90</span>
            </div>
            <div class="menu-item">
                <span>Mocktails (Virgin Mojito/Blue Lagoon)</span>
                <span>Rs 120</span>
            </div>
        </div>        
    </section>
    
    <section id="reservation" class="reservation-section">
        <h2>Reserve a Table</h2>
        <form class="reservation-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <input type="date" required>
            <input type="time" required>
            <select required>
                <option value="" disabled selected>Number of People</option>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
                <option value="6+">6+</option>
            </select>
            <button type="submit">Reserve Now</button>
        </form>
    </section>

    
    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <form class="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="4" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <section id="about" class="about-section">
        <h2>About Us</h2>
        <p>
            We are a family-owned restaurant serving delicious meals made with fresh ingredients. Our passion for food shows in every dish we create. Whether you’re in the mood for a hearty meal or a light snack, we’ve got something for everyone!
        </p>
    </section>
    
    Follow on us:<br>
     <a href="https://www.instagram.com/_shreyash__8?utm_source=qr&igsh=ODZ2cjBqY3FrcHRp" target="_blank">Instrgram</a><br>
     <a href="www.linkedin.com/in/shreyash-singh-053340322"target="_blank">Linkedin</a>
</div>

<footer>
    <p>&copy; 2024 Our Restaurant | All Rights Reserved</p>
</footer>


</body>
</html>
