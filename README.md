# Ex.07 Restaurant Website
## Date:
14.12.24
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
index

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bon_Appitite</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="banner">
        <h1>Welcome to Bon_Appitite</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="intro">
        <h2>A Pot Full of Joy!</h2>
        <p>Welcome to Bon_Appitite, where we serve delicious meals in a warm and friendly atmosphere.</p>
    </section>

    <footer>
        <p>© 2024 MADHU SHRIE J</p>
    </footer>
</body>
</html>

menu

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }

        header.banner {
            background-color: #222;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header.banner h1 {
            margin: 0;
        }

        header.banner nav ul {
            list-style: none;
            padding: 0;
            margin: 10px 0 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        header.banner nav ul li {
            display: inline;
        }

        header.banner nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 1.2em;
            transition: color 0.3s;
        }

        header.banner nav ul li a:hover {
            color: #ff6347;
        }

        .menu {
            padding: 20px;
            text-align: center;
        }

        .menu h2 {
            font-size: 2em;
            color: #222;
            margin-bottom: 20px;
        }

        .menu-items {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 0;
        }

        .item {
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            padding: 15px;
        }

        .item img {
            max-width: 100%;
            height: auto;
            border-bottom: 2px solid #f4f4f4;
        }

        .item h3 {
            font-size: 1.5em;
            margin: 10px 0;
        }

        .item p {
            font-size: 1.2em;
            color: #555;
        }

        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header class="banner">
        <h1>Menu</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="menu">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="item">
                <img src="soup.jpg" alt="soup">
                <h3>soup</h3>
                <p>Rs. 250</p>
            </div>

            <div class="item">
                <img src="burger.jpeg" alt="burger">
                <h3>burger</h3>
                <p>Rs. 50</p>
            </div>

            <div class="item">
                <img src="fried chicken.jpg" alt="fried chicken">
                <h3>fried chicken</h3>
                <p>Rs. 450</p>
            </div>

            <div class="item">
                <img src="dosaa.jpg" alt="dosaa">
                <h3>dosaa</h3>
                <p>Rs. 150</p>
            </div>

            <div class="item">
                <img src="puttu & kadalai.jpg" alt="puttu & kadalai">
                <h3>puttu & kadalai</h3>
                <p>Rs. 300</p>
            </div>

            <div class="item">
                <img src="tandoori.jpg" alt="tandoori">
                <h3>tandoori</h3>
                <p>Rs. 550</p>
            </div>

            <div class="item">
                <img src="noodles.jpg" alt="noodles">
                <h3>noodles</h3>
                <p>Rs. 250</p>
            </div>

            <div class="item">
                <img src="apple pie.jpg" alt="apple pie">
                <h3>apple pie</h3>
                <p>Rs. 1250</p>
            </div>

            <div class="item">
                <img src="biriyani.jpg" alt="biriyani">
                <h3>biriyani</h3>
                <p>Rs. 390</p>
            </div>

            <div class="item">
                <img src="pizza.jpg" alt="pizza">
                <h3>pizza</h3>
                <p>Rs. 500</p>
            </div>

            <div class="item">
                <img src="egg tart.jpg" alt="egg tart">
                <h3>egg tart</h3>
                <p>Rs. 350</p>
            </div>

            <div class="item">
                <img src="cheese cake.jpg" alt="cheese cake">
                <h3>cheese cake</h3>
                <p>Rs. 200</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 MADHU SHRIE J</p>
    </footer>
</body>
</html>

administration 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        .banner {
            background-color: #afa74c;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        .banner h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav ul li {
            margin: 0;
        }

        nav ul li a {
            display: block;
            padding: 10px 20px;
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            background-color: #afac4c;
        }

        .team {
            padding: 40px 20px;
            text-align: center;
        }

        .team h2 {
            margin-bottom: 20px;
            font-size: 2em;
            color: #afaa4c;
        }

        .team-members {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .member {
            background: white;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            width: 200px;
            padding: 20px;
            text-align: center;
        }

        .member img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 15px;
        }

        .member h3, .member h4, .member h5, .member h6 {
            margin: 10px 0 5px;
            font-size: 1.2em;
            color: #333;
        }

        .member p {
            margin: 0;
            font-size: 0.9em;
            color: #666;
        }

        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header class="banner"> 
        <h1>Our Team</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="team">
        <h2>Meet Our Team</h2>
        <div class="team-members">
            <div class="member">
                <img src="madhu shrie j.png" alt="madhu shrie j">
                <h3>Madhu shrie j </h3>
                <p>Owner</p>
            </div>
            <div class="member">
                <img src="vijay1.jpg" alt="vijay1">
                <h3>vijay</h3>
                <p>Management Team</p>
            </div>
            <div class="member">
                <img src="surya2.jpg" alt="surya2">
                <h3>surya</h3>
                <p>Management Team</p>
            </div>
            <div class="member">
                <img src="harthikp6.jpg" alt="harthikp">
                <h3>harthik</h3>
                <p>Senior Chef</p>
            </div>
            <div class="member">
                <img src="saipallavi4.jpg" alt="saipallavi4">
                <h3>saipallavi</h3>
                <p>Chef</p>
            </div>
            <div class="member">
                <img src="dhoni5.jpg" alt="dhoni">
                <h3>dhoni</h3>
                <p>Chef</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 MADHU SHRIE J</p>
    </footer>
</body>
</html>

contact 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        .banner {
            background-color: #a5af4c;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        .banner h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav ul li {
            margin: 0;
        }

        nav ul li a {
            display: block;
            padding: 10px 20px;
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            background-color: #a7af4c;
        }

        .contact {
            padding: 40px 20px;
            text-align: center;
        }

        .contact h2 {
            margin-bottom: 20px;
            font-size: 2em;
            color: #a7af4c;
        }

        .contact p {
            font-size: 1.2em;
            margin: 10px 0;
            color: #555;
        }

        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header class="banner">
        <h1>Contact Us</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h2>contact us</h2>
        <p><strong>Address:</strong>no.41 , brother street ,anna nagar ,chennai</p>
        <p><strong>Phone:</strong> 9443419387</p>
        <p><strong>Email:</strong> Bon_Appitite@restaurant.com</p>
    </section>

    <footer>
        <p>&copy; 2024 MADHU SHRIE J</p>
    </footer>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (40).png>)
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (43).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
