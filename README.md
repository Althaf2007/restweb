# Ex.07 Restaurant Website
## Date:25/12/2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

```
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AF Restaurant</title>
    <style>
        body {
            background-color: cornsilk;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color:rgb(4, 255, 184);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color:rgb(53, 31, 15);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color:grey;
        }
        .hero {
             background-color:rgb(188, 244, 49);
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .hero h1 {
            font-size: 3rem;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .menu-item {
            border: 1px solid rgb(158, 241, 110);
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color:rgb(39, 209, 104);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>AF Restaurant</h1>
    </header>
    <nav>
        <a href="home.html">home</a>
        <a href="about.html">About</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="hero">
        <h1>Welcome to Our Restaurant</h1>
    </div>
    <section id="about">
        <h2>About Us</h2>
        <p>We are passionate about serving delicious food made with fresh ingredients. Join us for an unforgettable dining experience!</p>
    </section>
    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu">
            <div class="menu-item">
                <img src="Ven-Pongal-3.jpg">
                <h3>Ven Pongal</h3>
                <p>Venn or ven (hot) pongal has been described as a rice and lentil porridge similar to the South Asian staple khichdi.</p>
            </div>
            <div class="menu-item">
                <img src="idli.webp">
                <h3>Idli</h3>
                <p>Idli is made by steaming batter made from rice and pulses(specifically black lentils),into two to three inches thick patties using a mold. </p>
            </div>
            <div class="menu-item">
                <img src="Plain-Dosa.webp">
                <h3>Dosa</h3>
                <p>A dosa is a thin, savoury crepe in Indian cuisine made from a fermented batter of ground black gram and rice.</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Phone:7866522130</p>
        <p>Email:afres34@gmail.com</p>
        <p>Address: No.14,Kasim street,Royapettah,Chennai</p>
    </section>
    <footer>
        <p>&copy; AF Restaurant. All Rights Reserved.</p>
    </footer>
</body>
</html>

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - AF Restaurant</title>
    <style>
        body {
            background-color: rgb(161, 254, 0);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(255, 179, 0);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(9, 255, 222);
        }
        nav a {
            color: rgb(248, 97, 97);
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(198, 224, 114);
        }
        section {
            padding: 20px;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            text-align: center;
        }
        .menu-item {
            border: 1px solid rgb(12, 245, 105);
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color: rgb(23, 153, 13);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Our Menu</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Explore Our Dishes</h2>
        <div class="menu">
            <div class="menu-item">
                <img src="Ven-Pongal-3.jpg" alt="Ven Pongal">
                <h3>Ven Pongal</h3>
                <p>Venn or ven (hot) pongal has been described as a rice and lentil porridge similar to the South Asian staple khichdi.</p>
            </div>
            <div class="menu-item">
                <img src="idli.webp" alt="Idli">
                <h3>Idli</h3>
                <p>Idli is made by steaming batter made from rice and pulses(specifically black lentils),into two to three inches thick patties using a mold. </p>
            <div class="menu-item">
                <img src="Plain-Dosa.webp" alt="Dosa">
                <h3>Dosa</h3>
                <p>A dosa is a thin, savoury crepe in Indian cuisine made from a fermented batter of ground black gram and rice.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; AF Restaurant. All Rights Reserved.</p>
        <p> Designed and developed by: K.Mohamed Althaf</p>
    </footer>
</body>
</html>

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - AF Restaurant</title>
    <style>
        body {
            background-color: rgb(8, 248, 228);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(198, 33, 168);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(41, 255, 80);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(23, 205, 255);
        }
        .welcome {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 50px;
        }
        .welcome h1 {
            font-size: 2.5rem;
        }
        .welcome p {
            font-size: 1.2rem;
            margin: 20px 0;
        }
        .features {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
            text-align: center;
        }
        .feature {
            margin: 10px;
            padding: 20px;
            border: 1px solid rgb(79, 15, 15);
            border-radius: 5px;
            width: 300px;
        }
        footer {
            background-color: rgb(16, 88, 196);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to AF Restaurant</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="about.html">About</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="welcome">
        <h1>Your Destination for Exquisite Cuisine</h1>
        <p>AF Restaurant offers a wide range of delicious dishes made from the freshest ingredients. Experience the taste of perfection with every bite!</p>
    </div>
    <section class="features">
        <div class="feature">
            <h3>Fresh Ingredients</h3>
            <p>We use only the freshest and highest-quality ingredients to prepare our dishes.</p>
        </div>
        <div class="feature">
            <h3>Family-Friendly</h3>
            <p>Enjoy a welcoming and comfortable atmosphere perfect for family gatherings.</p>
        </div>
        <div class="feature">
            <h3>Exceptional Service</h3>
            <p>Our friendly staff is here to make your dining experience unforgettable.</p>
        </div>
    </section>
    <footer>
        <p>&copy; AF Restaurant. All Rights Reserved.</p>
        <p> Designed and developed by: K.Mohamed Althaf</p>
    </footer>
</body>
</html>

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - AF Restaurant</title>
    <style>
        body {
            background-color: rgb(68, 175, 15);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(239, 173, 19);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(4, 247, 227);
        }
        nav a {
            color: rgb(128, 10, 246);
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(232, 10, 248);
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
            text-align: justify;
        }
        footer {
            background-color: rgb(253, 33, 117);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>About AF Restaurant</h1>
    </header>
    <nav>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Our Story</h2>
        <div class="content">
            <p>Welcome to AF Restaurant, where we bring together a love for fresh, delicious meals and a passion for hospitality. Established with the goal of creating memorable dining experiences, Java Foods is your go-to destination for a delightful culinary journey.</p>
            <p>Our team is committed to using the finest ingredients to prepare dishes that reflect authenticity and innovation. Whether you're here for a hearty meal, a light snack, or a sweet treat, our menu is designed to cater to every craving.</p>
            <p>We take pride in our warm and inviting atmosphere, perfect for family gatherings, friendly get-togethers, or a quiet meal on your own. At Java Foods, we believe food is more than just sustenance—it's an experience, and we are thrilled to share it with you.</p>
        </div>
    </section>
    <footer>
        <p>&copy; AF Restaurant. All Rights Reserved.</p>
        <p> Designed and developed by: K.Mohamed Althaf</p>
    </footer>
</body>
</html>

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - AF Restaurant</title>
    <style>
        body {
            background-color: rgb(208, 250, 94);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(253, 79, 79);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(243, 155, 31);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(109, 61, 230);
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .contact-info {
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.6;
        }
        footer {
            background-color: rgb(222, 112, 16);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    <nav>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>A warm welcome</h2>
        <div class="contact-info">
            <p><strong>Phone:</strong> 7866522130</p>
            <p><strong>Email:</strong> afres34@gmail.com</p>
            <p><strong>Address:</strong> No.14,Kasim street,Royapettah,Chennai</p>
            <p>we value your feedback</p>
    </section>
    <footer>
        <p>&copy; AF Restaurant. All Rights Reserved.</p>
        <p> Designed and developed by: K.Mohamed Althaf</p>
    </footer>
</body>
</html>

```

## OUTPUT:

![alt text](<pj00/resapp/static/Screenshot 2024-12-25 114036.png>)
![alt text](<pj00/resapp/static/Screenshot 2024-12-25 113939.png>)
![alt text](<pj00/resapp/static/Screenshot 2024-12-25 113845.png>)
![alt text](<pj00/resapp/static/Screenshot 2024-12-25 113741.png>)
![alt text](<pj00/resapp/static/Screenshot 2024-12-25 113824.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
