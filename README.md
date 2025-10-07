# Ex.07 Restaurant Website
# Date:07\10\2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:


```
index.html



<html>
<head>
  <title>SHAKTHI RESTAURANTS</title>
  <style>
    body { background-color: lightyellow; font-family: Arial; text-align: center; }
    nav a { margin: 10px; text-decoration: none; color: white; background-color: brown; padding: 5px 10px; border-radius: 5px; }
    img { width: 300px; height: 200px; border-radius: 10px; }
  </style>
</head>
<body>

  <h1>SHAKTHI RESTAURANTS</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact</a>
  </nav>

  <h2>30% Off This Weekend!</h2>
  <p>Enjoy delicious food and warm service at our restaurant.</p>
  <img src="logo.jpg" alt="Restaurant Banner">

  <h3>Our Specials</h3>
  <p>Try our new Italian dishes and desserts!</p>

  <footer>
    <p>© 2025 SHAKTHI| Designed by DARSHINI</p>
  </footer>
</body>
</html>


menu.html


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shakthi Restaurant - Menu</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #fff8f0; 
            color: #333;
        }

        
        header {
            background-color: #ff704d; 
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        /* Navigation */
        nav {
            background-color: #ff9966;
            overflow: hidden;
        }

        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #ff704d;
        }

        /* Menu Section */
        .menu-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 30px;
        }

        .menu-item {
            background-color: #fff3e6;
            border: 2px solid #ff9966;
            border-radius: 10px;
            text-align: center;
            padding: 15px;
            transition: transform 0.3s;
        }

        .menu-item:hover {
            transform: scale(1.05);
        }

        .menu-item img {
            width: 100%;
            height: 180px;
            border-radius: 10px;
            object-fit: cover;
        }

        .menu-item h3 {
            margin: 10px 0 5px 0;
            color: #ff704d;
        }

        .menu-item p {
            margin: 0;
            font-size: 1.1em;
            font-weight: bold;
        }

        /* Footer */
        footer {
            background-color: #ff704d;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Shakthi Restaurant</h1>
        <p>Delicious Food, Fresh Ingredients, Happy Customers!</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <section class="menu-container">
        <div class="menu-item">
            <img src="butter chicken.jpg" alt="Butter Chicken">
            <h3>Butter Chicken</h3>
            <p>₹250</p>
        </div>
        <div class="menu-item">
            <img src="pizza.jpg" alt="Margherita Pizza">
            <h3>Margherita Pizza</h3>
            <p>₹180</p>
        </div>
        <div class="menu-item">
            <img src="biriyani.jpg" alt="Veg Biryani">
            <h3>Veg Biryani</h3>
            <p>₹150</p>
        </div>
        <div class="menu-item">
            <img src="paneer.jpg" alt="Paneer Tikka">
            <h3>Paneer Tikka</h3>
            <p>₹200</p>
        </div>
        <div class="menu-item">
            <img src="noodles.jpg" alt="Chicken Noodles">
            <h3>Chicken Noodles</h3>
            <p>₹180</p>
        </div>
        <div class="menu-item">
            <img src="french fries.jpg" alt="French Fries">
            <h3>French Fries</h3>
            <p>₹80</p>
        </div>
        <div class="menu-item">
            <img src="soup.jpg" alt="Veg Soup">
            <h3>Veg Soup</h3>
            <p>₹100</p>
        </div>
        <div class="menu-item">
            <img src="shawarma.jpg" alt="Chcken shawarma">
            <h3>Chicken shawarma</h3>
            <p>₹120</p>
        </div>
        <div class="menu-item">
            <img src="pasta.jpg" alt="Pasta Alfredo">
            <h3>Pasta Alfredo</h3>
            <p>₹220</p>
        </div>
        <div class="menu-item">
            <img src="sandwich.jpg" alt="Grilled Sandwich">
            <h3>Grilled Sandwich</h3>
            <p>₹130</p>
        </div>
        <div class="menu-item">
            <img src="dosa.jpg" alt="Masala Dosa">
            <h3>Masala Dosa</h3>
            <p>₹100</p>
        </div>
        <div class="menu-item">
            <img src="falooda.jpg.png" alt="Ice Cream">
            <h3>Ice Cream</h3>
            <p>₹90</p>
        </div>
    </section>

    <footer>
        <p>Designed by Shakthi</p>
    </footer>

</body>
</html>




administration.html

<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Administration - Delight Bites</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <style>
        .person img{
            width: 30%;
            height:45%;
        }
    </style>
    <header>
        <h1>Delight Bites</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administration</a>
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>

    <main class="admin-page">
        <h2>Meet Our Team</h2>
        <div class="team-grid">
            <div class="person">
                <img src="bhat.jpg" alt="Person 1">
                <p>Ravi Kumar<br><span>Founder & CEO</span></p>
            </div>
            <div class="person">
                <img src="damu.jpg" alt="Person 2">
                <p>Damodharan<br><span>Chef Head</span></p>
            </div>
            <div class="person">
                <img src="neeta.jpg" alt="Person 3">
                <p>Neeta<br><span>Marketing Manager</span></p>
            </div>
            <div class="person">
                <img src="finance.jpg" alt="Person 4">
                <p>Darshini<br><span>Finance Officer</span></p>
            </div>
            <div class="person">
                <img src="musk.jpg" alt="Person 5">
                <p>Elon Musk<br><span>Logistics Head</span></p>
            </div>
            <div class="person">
                <img src="ratan.jpg" alt="Person 6">
                <p>Ratan Tata<br><span>Customer Support</span></p>
            </div>
        </div>
    </main>

    <footer>
        <p>© 2025 Delight Bites | Designed by shakthi</p>
    </footer>
</body>
</html>



contact.html



<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact Us - Delight Bites</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #fffaf0;
        }

        header {
            background-color: #b22222;
            padding: 20px 0;
            color: white;
            text-align: center;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .contact-section {
            padding: 40px;
            text-align: center;
        }

        .contact-section h2 {
            font-size: 32px;
            margin-bottom: 10px;
            color: #b22222;
        }

        .contact-section .intro {
            font-size: 18px;
            margin-bottom: 30px;
            color: #333;
        }

        .contact-box {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
        }

        .contact-item {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            width: 250px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.05);
        }

        .contact-item h3 {
            margin-bottom: 10px;
            color: #444;
        }

        .contact-item p {
            font-size: 16px;
            color: #666;
            line-height: 1.6;
        }

        footer {
            background-color: #f4f4f4;
            text-align: center;
            padding: 15px 0;
            font-size: 14px;
            color: #444;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Delight Bites</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administration</a>
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>

    <main class="contact-section">
        <h2>Get in Touch</h2>
        <p class="intro">
            We’d love to hear from you! Whether you have a question, feedback, or just want to say hello — reach out to us anytime.
        </p>

        <div class="contact-box">
            <div class="contact-item">
                <h3>Address</h3>
                <p>123 Foodie Street,<br> Anna Nagar, Chennai,<br> Tamil Nadu - 600040, India</p>
            </div>
            <div class="contact-item">
                <h3>Phone</h3>
                <p>+91 98765 43210</p>
            </div>
            <div class="contact-item">
                <h3>Email</h3>
                <p>contact@delightbites.com</p>
            </div>
        </div>
    </main>

    <footer>
        <p>© 2025 Delight Bites | Designed by <strong>S. Ramya Rajan</strong></p>
    </footer>
</body>


```
# OUTPUT:
![alt text](<Screenshot 2025-10-07 130143.png>)
![alt text](<Screenshot 2025-10-07 130308.png>)
![alt text](<Screenshot 2025-10-07 130346.png>)
![alt text](<Screenshot 2025-10-07 130359.png>)
![alt text](<Screenshot 2025-10-07 130109.png>)









# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
