<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Relief Roll-On</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f1f8f5;
            color: #333;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .top-header {
            display: flex;
            justify-content: center;
            gap: 40px;
            padding: 15px;
            background: #1d6c5e;
            font-size: 1.2rem;
            border-bottom: 4px solid #e9c46a;
        }
        .top-header a {
            color: #ffffff;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s ease;
        }
        .top-header a:hover {
            color: #e9c46a;
        }
        header {
            font-size: 2.8rem;
            font-weight: bold;
            padding: 25px;
            background: #f1f8f5;
            color: #1d6c5e;
            text-transform: uppercase;
        }
        .products-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            padding: 30px;
        }
        .product-box {
            border: none;
            padding: 25px;
            border-radius: 20px;
            background: #ffffff;
            box-shadow: 0px 6px 15px rgba(0, 0, 0, 0.15);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .product-box:hover {
            transform: translateY(-10px);
            box-shadow: 0px 10px 25px rgba(0, 0, 0, 0.2);
        }
        .product-box img {
            width: 100%;
            border-radius: 15px;
        }
        .buy-btn {
            background: #1d6c5e;
            color: #ffffff;
            padding: 12px 25px;
            border: none;
            border-radius: 10px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: background 0.3s ease;
        }
        .buy-btn:hover {
            background: #155147;
        }
    </style>
</head>
<body>
    <div class="top-header">
        <a href="#about">About</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </div>
    <header>
        Relief Roll-On
    </header>
    <div id="about">
        <h2>About Us</h2>
        <p>Experience natural, fast-acting headache relief with our specially formulated roll-ons. Blended with essential oils to provide instant comfort.</p>
    </div>
    <div id="products">
        <h2>Our Products</h2>
        <div class="products-container">
            <div class="product-box">
                <img src="peppermint_rollon.jpg" alt="Peppermint Roll-On">
                <h3>Peppermint Roll-On</h3>
                <p>Cool and refreshing, this roll-on helps ease headaches and tension.</p>
                <p class="price">₹150</p>
                <button class="buy-btn">Buy Now</button>
            </div>
            <div class="product-box">
                <img src="lavender_rollon.jpg" alt="Lavender Roll-On">
                <h3>Lavender Roll-On</h3>
                <p>Calming lavender to help reduce stress-related headaches.</p>
                <p class="price">₹200</p>
                <button class="buy-btn">Buy Now</button>
            </div>
            <div class="product-box">
                <img src="eucalyptus_rollon.jpg" alt="Eucalyptus Roll-On">
                <h3>Eucalyptus Roll-On</h3>
                <p>Refreshing eucalyptus for sinus relief and headache comfort.</p>
                <p class="price">₹200</p>
                <button class="buy-btn">Buy Now</button>
            </div>
        </div>
    </div>
    <div id="contact">
        <h2>Contact Us</h2>
        <p>Email: rollon@support.com</p>
        <p>Phone: +91 98598 74641</p>
    </div>
</body>
</html>
