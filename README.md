# Timeless-elegance-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bracelet Bliss - Handcrafted Bracelets</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #8b5a3c;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #d2b48c;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #333;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #8b5a3c;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product {
            width: 300px;
            margin: 20px;
            text-align: center;
        }
        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product p {
            color: #666;
        }
        .contact form {
            display: flex;
            flex-direction: column;
        }
        .contact input, .contact textarea {
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .contact button {
            padding: 10px;
            background-color: #8b5a3c;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .contact button:hover {
            background-color: #a0522d;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #8b5a3c;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bracelet Bliss</h1>
        <p>Handcrafted bracelets for every style</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container" id="home">
        <h2>Welcome to Bracelet Bliss</h2>
        <p>Discover unique, handcrafted bracelets made with love. From bohemian beads to minimalist designs, we have something for everyone. Shop our collection and add a touch of elegance to your wrist!</p>
    </div>
    <div class="container" id="gallery">
        <h2>Our Bracelets</h2>
        <div class="gallery">
            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Bohemian+Bracelet" alt="Bohemian Bracelet">
                <h3>Bohemian Bead Bracelet</h3>
                <p>$25 - Colorful and free-spirited</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Minimalist+Bracelet" alt="Minimalist Bracelet">
                <h3>Minimalist Silver Bracelet</h3>
                <p>$30 - Sleek and timeless</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Leather+Bracelet" alt="Leather Bracelet">
                <h3>Leather Wrap Bracelet</h3>
                <p>$20 - Durable and stylish</p>
            </div>
        </div>
    </div>
    <div class="container contact" id="contact">
        <h2>Contact Us</h2>
        <form id="contactForm">
            <input type="text" id="name" placeholder="Your Name" required>
            <input type="email" id="email" placeholder="Your Email" required>
            <textarea id="message" placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>
    <footer>
        <p>&copy; 2023 Bracelet Bliss. All rights reserved.</p>
    </footer>
    <script>
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your message! We\'ll get back to you soon.');
            // In a real site, you'd send this to a server (e.g., via email API)
        });
    </script>
</body>
</html>
