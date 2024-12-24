# Ex.07 Restaurant Website
# Date:08/11/24
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
## contact.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Pizza Delight</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color:olivedrab;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            font-size: 2em;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color:olivedrab#e74c3c;
            color: white;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
        form input[type="text"], form input[type="email"], form input[type="tel"], form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            box-sizing: border-box;
        }
        form input[type="submit"] {
            background-color:ilovrdrab#3ce76d#3ce76d;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        form input[type="submit"]:hover {
            background-color: #c0392b;
        }
    </style>
</head>
<body>
    <header>
        <h1>Pizza Hut</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="order.html">Order Now</a>
            <a href="signin.html">Sign In</a>
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>

    <div class="container">
        <h1>Contact Us</h1>
        <form>
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>
            <label for="phone">Phone Number:</label><br>
            <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required><br><br>

            <label for="email">Email ID:</label><br>
            <input type="email" id="email" name="email" placeholder="Enter your email address" required><br><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" placeholder="Enter your message here" required></textarea><br><br>

            <input type="submit" value="Submit">
        </form>
    </div>

    <footer>
        &copy; 2024 Pizza Delight. All Rights Reserved.
    </footer>
    <center>
        <h1>Our Proudly Guest</h1>
        <img src="chef.avif" alt="chef photo">
    </center>
   
    <div class="container">
        <div class="content-section">
            
        </div>
        <div class="pizza-gallery">
            <div class="pizza-item">
                <img src="chef1.jpeg" alt="Margherita Pizza" style="height: 300px;">
                <p>Margherita Pizza</p>
                
            </div>
            <div class="pizza-item">
                <img src="chef2.jpeg" alt="Pepperoni Pizza" style="height: 300px;">
                <p>Pepperoni Pizza</p>
                
            </div>
            <div class="pizza-item">
                <img src="chef3.jpeg" alt="Veggie Pizza" style="height: 300px;">
                <p>Veggie Pizza</p>
                
            </div>
            <div class="pizza-item">
                <img src="chef4.jpeg" alt="BBQ Chicken Pizza" style="height: 300px;">
                <p>BBQ Chicken Pizza</p>
                
            </div>
           
            </div>
        </div>
    </div>
</body>
</html>
~~~
## signin.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign In - Pizza Delight</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #e74c3c;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            font-size: 2em;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #e74c3c;
            color: white;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
        form input[type="text"], form input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            box-sizing: border-box;
        }
        form input[type="submit"] {
            background-color: #e74c3c;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        form input[type="submit"]:hover {
            background-color: #c0392b;
        }
    </style>
</head>
<body>
    <header>
        <h1>Pizza Hut</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="order.html">Order Now</a>
            <a href="signin.html">Sign In</a>
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>

    <div class="container">
        <h1>Sign In</h1>
        <form>
            <label for="username">Username:</label><br>
            <input type="text" id="username" name="username"><br><br>
            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password"><br><br>

            <input type="submit" value="Sign In">
        </form>
    </div>

    <footer>
        &copy; 2024 Pizza Delight. All Rights Reserved.
    </footer>
</body>
</html>
~~~
## index.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pizza Delight</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #e74c3c;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav {
            margin: 15px 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            font-size: 2.5em;
        }
        .pizza-gallery {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
        }
        .pizza-item {
            text-align: center;
            transition: transform 0.3s;
        }
        .pizza-item:hover {
            transform: scale(1.05);
        }
        .pizza-item img {
            width: 100%;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #e74c3c;
            color: white;
            width: 100%;
        }
        .btn {
            background-color: #e74c3c;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .btn:hover {
            background-color: #c0392b;
        }
    </style>
</head>
<body>
    <header>
        <h1>Pizza Hut</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="order.html">Order Now</a>
            <a href="signin.html">Sign In</a>
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>

    <div class="container">
        <div class="content-section">
            <h2>Welcome to Pizza Hut!</h2>
            <p>Pizza is the perfect food because it's the only food that you can eat with your hands and still look classy</p>
        </div>

        <h2>Our Pizza Varieties</h2>
        <div class="pizza-gallery">
            <div class="pizza-item">
                <img src="margherita.jpeg" alt="Margherita Pizza" style="height: 300px;">
                <p>Margherita Pizza</p>
                <p>$20.00</p>
            </div>
            <div class="pizza-item">
                <img src="peppaeroni.jpeg" alt="Pepperoni Pizza" style="height: 300px;">
                <p>Pepperoni Pizza</p>
                <p>$25.00</p>
            </div>
            <div class="pizza-item">
                <img src="veggie.jpeg" alt="Veggie Pizza" style="height: 300px;">
                <p>Veggie Pizza</p>
                <p>$30.00</p>
            </div>
            <div class="pizza-item">
                <img src="bbq.jpeg" alt="BBQ Chicken Pizza" style="height: 300px;">
                <p>BBQ Chicken Pizza</p>
                <p>$40.00</p>
            </div>
            <div class="pizza-item">
                <img src="cheese.jpeg" alt="Four Cheese Pizza" style="height: 300px;">
                <p>Four Cheese Pizza</p>
                <p>$45.00</p>
            </div>
            <div class="pizza-item">
                <img src ="hawaaian.jpeg" alt="Hawaiian Pizza" style="height: 300px;">
                <p>Hawaiian Pizza</p>
                <p>$4.50</p>
            </div>
            <div class="pizza-item">
                <img src="lovers.jpeg" alt="Meat Lovers Pizza" style="height: 300px;">
                <p>Meat Lovers Pizza</p>
                $100.00
            </div>
            <div class="pizza-item">
                <img src="panner.jpeg" alt="Spicy Paneer Pizza" style="height: 300px;">
                <p>Spicy Paneer Pizza</p>
                <p>$47.00</p>
            </div>
        </div>
    </div>

    <footer>
        &copy; 2024 Pizza Delight. All Rights Reserved.
    </footer>
</body>
</html>
~~~
## order.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Order Now - Pizza Delight</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #e74c3c;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            font-size: 2em;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #e74c3c;
            color: white;
            
            bottom: 0;
            width: 100%;
        }
        .pizza-gallery {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
        .pizza-item {
            text-align: center;
        }
        .pizza-item img {
            width: 100%;
            border-radius: 8px;
        }
        .order-form {
            margin-top: 30px;
        }
        form input, form select, form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            box-sizing: border-box;
        }
        form input[type="submit"] {
            background-color: #e74c3c;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        form input[type="submit"]:hover {
            background-color: #c0392b;
        }
    </style>
</head>
<body>
    <header>
        <h1>Pizza Hut</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="order.html">Order Now</a>
            <a href="signin.html">Sign In</a>
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>

    <div class="container">
        <h1>Order Your Favorite Pizza</h1>
        <div class="pizza-gallery">
            <div class="pizza-item">
                <img src="margherita.jpeg" alt="Margherita Pizza" style="height: 300px;">
                <p>Margherita Pizza</p>
            </div>
            <div class="pizza-item">
                <img src="peppaeroni.jpeg" alt="Pepperoni Pizza" style="height: 300px;">
                <p>Pepperoni Pizza</p>
            </div>
            <div class="pizza-item">
                <img src="veggie.jpeg" alt="Veggie Pizza" style="height: 300px;">
                <p>Veggie Pizza</p>
            </div>
            <div class="pizza-item">
                <img src="bbq.jpeg" alt="BBQ Chicken Pizza" style="height: 300px;">
                <p>BBQ Chicken Pizza</p>
            </div>
            <div class="pizza-item">
                <img src= "bbq.jpeg" alt="Four Cheese Pizza" style="height: 300px;">
                <p>Four Cheese Pizza</p>
            </div>
            <div class="pizza-item">
                <img src= "hawaaian.jpeg" alt="Hawaiian Pizza" style="height: 300px;">
                <p>Hawaiian Pizza</p>
            </div>
            <div class="pizza-item">
                <img src="lovers.jpeg" alt="Meat Lovers Pizza" style="height: 300px;">
                <p>Meat Lovers Pizza</p>
            </div>
            <div class="pizza-item">
                <img src="panner.jpeg" alt="Spicy Paneer Pizza" style="height: 300px;">
                <p>Spicy Paneer Pizza</p>
            </div>
            <div class="pizza-item">
                <img src="hawaaian.jpeg" alt="Buffalo Chicken Pizza" style="height: 300px;">
                <p>Buffalo Chicken Pizza</p>
            </div>
           
        </div>

        <div class="order-form">
            <h2>Order Now</h2>
            <form>
                <label for="pizza">Select Pizza Type:</label>
                <select id="pizza" name="pizza">
                    <option value="margherita">Margherita</option>
                    <option value="pepperoni">Pepperoni</option>
                    <option value="veggie">Veggie</option>
                    <option value="Supreme Pizza">Supreme Pizza</option>
                    <option value="Buffalo Chicken Pizza">Buffalo Chicken Pizza</option>
                    <option value="Spicy Paneer Pizza">Spicy Paneer Pizza</option>
                    <option value="Meat Lovers Pizza">Meat Lovers Pizza</option>

                </select><br><br>
    
                <label for="size">Size:</label>
                <select id="size" name="size">
                    <option value="small">Small</option>
                    <option value="medium">Medium</option>
                    <option value="large">Large</option>
                </select><br><br>
    
                <label for="address">Delivery Address:</label><br>
                <textarea id="address" name="address" rows="4" cols="50"></textarea><br><br>
    
                <input type="submit" value="Place Order">
            </form>
        </div>
    
        <footer>
            &copy; 2024 Pizza Delight. All Rights Reserved.
        </footer>
    </body>
    </html>
~~~
# OUTPUT:
![Screenshot 2024-12-15 190218](https://github.com/user-attachments/assets/0b391d66-b9b7-4f5e-a02a-ab76a594a85e)
![Screenshot 2024-12-15 190248](https://github.com/user-attachments/assets/4b7893ed-190b-4dd9-be18-28bf8bde86d6)
![Screenshot 2024-12-15 190307](https://github.com/user-attachments/assets/0d89db7d-5e98-4ae4-9e5e-5256fd681452)
![Screenshot 2024-12-15 190327](https://github.com/user-attachments/assets/e3d42688-3e34-44f7-a064-2b60f24fa1b3)
![Screenshot 2024-12-15 190348](https://github.com/user-attachments/assets/6e2bc5bc-a2e3-4fc1-8b45-ab8050894b08)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
