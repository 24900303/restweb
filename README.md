# Ex.07 Restaurant Website
## Date:

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
**index.HTML**
```
**Name: RUDESH KANNA R

Reg.No:212223233002
**<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.webp" alt="Little Lemon Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Book</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="promo-banner">
            <h2>50% Off This Weekend</h2>
            <p>Eat well, be active, feel good about yourself.</p>
        </section>

        <section class="content-columns">
            <article class="column">
                <h3>Our New Menu</h3>
                <img src="air-fryer-whole-tandoori-chicken-3.jpg" alt="New Menu">
                <p>air fryer whole tandoori chicken</p>
                <a href="#">See our new menu</a>
            </article>

            <article class="column">
                <h3>Book a Table</h3>
                <img src="nicoise-salad-wooden-bowl.jpg" alt="Book a Table">
                <p>Salade Niçoise</p>
                <a href="#">Book your table now</a>
            </article>

            <article class="column">
                <h3>Opening Hours</h3>
                <img src="portrait-two-chefs-kitchen-restaurant-with-plates-vegetables_1089554-5703.jpg" alt="Opening Hours">
                <p>Each day offers a fresh and delicious option!</p>
                <p>Monday - Friday: 2pm - 10pm<br>Saturday: 2pm - 11pm<br>Sunday: 2pm - 9pm</p>
            </article>
        </section>
    </main>

    <footer>
        <div class="footer-logo">
            <img src="images.png" alt="Little Lemon Logo">
        </div>
        <div class="footer-text">
            <p>© 2024 Little Lemon</p>
        </div>
    </footer>
</body>
</html>
```
style.CSS
```

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
    color: #333;
}

header, footer {
    background-color: #fff;
    padding: 20px;
    border-bottom: 1px solid #ddd;
}

.logo {
    display: flex;
    align-items: center;
    justify-content: center; 
    padding: 20px;
}

.logo img {
    max-width: 450px; 
    height: auto;
}


nav {
    background-color: #000;
    display: flex;
    justify-content: center;
    border-radius: 10px; 
}

nav ul {
    list-style: none;
    display: flex;
    padding: 0;
    margin: 0;
}

nav li {
    flex: none; 
}

nav a {
    display: block;
    text-decoration: none;
    color: #fff; 
    padding: 10px 20px;
    text-align: center;
    transition: background-color 0.3s;
}

nav a:hover {
    background-color: #333;
}

header {
    width: 100%;
}

main {
    padding: 20px;
}

.promo-banner {
    background: url("burger-with-fries-coke-side_1304780-1125.jpg") center/cover no-repeat;
    color: #fff;
    text-align: center;
    padding: 50px 20px;
    margin-bottom: 20px;
    border-radius: 10px;
}

.content-columns {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.column {
    flex: 1;
    background-color: #ffcd7c;
    padding: 10px;
    border-radius: 05
    px;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.column img {
    width: 100%;
    height: 50%;
    border-radius: 10px;
    margin-bottom: 05px;
}

.column h3 {
    margin-top: 10px;
    font-size: 1.2em;
}

.column a {
    display: inline-block;
    margin-top: 10px;
    text-decoration: none;
    color: #0066cc;
    transition: color 0.3s;
}

.column a:hover {
    color: #004d99;
}

footer {
    display: flex;
    justify-content: space-between;
    padding: 20px;
}

.footer-logo img {
    width: 75px;
}

.footer-text {
    display: flex;
    align-items: center;
    color: #777;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/e8e3213f-3b54-45e0-a146-aec4e188faf5)![image](https://github.com/user-attachments/assets/b8f9911c-4c72-4a6b-9587-4bf2f80d0b3e)![image](https://github.com/user-attachments/assets/5e62d4de-031c-4489-adf8-054e2de7c3e1)






## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
