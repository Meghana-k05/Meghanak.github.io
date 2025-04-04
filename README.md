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
            background-color: #f3e5f5;
            color: #4a148c;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .top-header {
            display: flex;
            justify-content: center;
            gap: 40px;
            padding: 15px;
            background: #6a1b9a;
            font-size: 1.2rem;
            border-bottom: 4px solid #d1c4e9;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        .top-header a {
            color: #ffffff;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s ease;
        }
        .top-header a:hover {
            color: #d1c4e9;
        }
        header {
            font-size: 3rem;
            font-weight: bold;
            padding: 30px;
            background: linear-gradient(to right, #6a1b9a, #4a148c);
            color: #ffffff;
            text-transform: uppercase;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        .products-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            padding: 40px;
        }
        .product-box {
            border: none;
            padding: 20px;
            border-radius: 15px;
            background: #ffffff;
            box-shadow: 0px 6px 15px rgba(0, 0, 0, 0.15);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .product-box:hover {
            transform: translateY(-10px);
            box-shadow: 0px 12px 30px rgba(0, 0, 0, 0.25);
        }
        .product-box img {
            width: 100%;
            border-radius: 15px;
        }
        .buy-btn {
            background: #7b1fa2;
            color: #ffffff;
            padding: 12px 25px;
            border: none;
            border-radius: 10px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: background 0.3s ease;
            margin-top: 10px;
        }
        .buy-btn:hover {
            background: #4a148c;
        }
        #contact {
            background: #6a1b9a;
            color: #ffffff;
            padding: 30px;
            margin-top: 20px;
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
                <img src="https://images.app.goo.gl/VmuWzjhtoHcGGeuS9" alt="Peppermint Roll-On">
                <h3>Peppermint Roll-On</h3>
                <p>Cool and refreshing, this roll-on helps ease headaches and tension.</p>
                <p class="price"><strong>₹200</strong></p>
                <button class="buy-btn">Buy Now</button>
            </div>
            <div class="product-box">
                <img src="https://images.app.goo.gl/L3PXfseLkAFVN75k6" alt="Lavender Roll-On">
                <h3>Lavender Roll-On</h3>
                <p>Calming lavender to help reduce stress-related headaches.</p>
                <p class="price"><strong>₹180</strong></p>
                <button class="buy-btn">Buy Now</button>
            </div>
            <div class="product-box">
                <img src="https://images.app.goo.gl/7VFCFtdcT2jr8ujX9" alt="Eucalyptus Roll-On">
                <h3>Eucalyptus Roll-On</h3>
                <p>Refreshing eucalyptus for sinus relief and headache comfort.</p>
                <p class="price"><strong>₹220</strong></p>
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
