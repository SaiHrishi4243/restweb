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

```
home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
        }
        header {
            background-color: #d84315;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            background-color: #bf360c;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #e64a19;
        }
        .banner {
            background-image: url('banner.jpg');
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2.5rem;
        }
        .content {
            padding: 20px;
        }
        footer {
            background-color: #bf360c;
            color: white;
            text-align: center;
            padding: 10px;
        }
        .menu-items, .admin-team {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .menu-item, .admin-member {
            border: 1px solid #ccc;
            padding: 10px;
            text-align: center;
            width: 200px;
            background-color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to York Restaurent</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <div class="banner">
        <p>Delicious Food Awaits</p>
    </div>
    <div class="content">
        <h2>About Us</h2>
        <p>Welcome to our restaurant, where we serve the best dishes with love and care. Explore our menu and meet our team.</p>
    </div>
    <footer>
        <p>&copy; 2025 | Designed by Sai Hrishi.M(24900846)</p>
    </footer>
</body>
</html>

```

```
menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Our Menu</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <div class="content">
        <div class="menu-items">
            <div class="menu-item">Pizza</div>
            <div class="menu-item">Pasta</div>
            <div class="menu-item">Burger</div>
            <div class="menu-item">Salad</div>
            <div class="menu-item">Steak</div>
            <div class="menu-item">Sushi</div>
            <div class="menu-item">Tacos</div>
            <div class="menu-item">Sandwich</div>
            <div class="menu-item">Soup</div>
            <div class="menu-item">Dessert</div>
            <div class="menu-item">Drinks</div>
            <div class="menu-item">Special Dish</div>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 | Designed by Sai Hrishi.M(24900846)</p>
    </footer>
</body>
</html>
```

```
administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Administration</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <div class="content">
        <div class="admin-team">
            <div class="admin-member">
                <img src="image.png" alt="Admin 1" style="width: 200px; height:200px;">
                <h3>John Doe</h3>
                <p>Manager</p>
            </div>
            <div class="admin-member">
                <img src="image1.png" alt="Admin 2" style="width: 200px; height:200px;">
                <h3>will Smith</h3>
                <p>Chef</p>
            </div>
            <div class="admin-member">
                <img src="image5.png" alt="Admin 3" style="width: 200px; height:200px;">
                <h3>Emily Davis</h3>
                <p>Assistant Manager</p>
            </div>
            <div class="admin-member">
                <img src="image2.png" alt="Admin 4" style="width: 200px; height:200px;">
                <h3>Michael Brown</h3>
                <p>Head Waiter</p>
            </div>
            <div class="admin-member">
                <img src="image3.png" alt="Admin 5" style="width: 200px; height:200px;">
                <h3>Sarah Wilson</h3>
                <p>Sommelier</p>
            </div>
            <div class="admin-member">
                <img src="image4.png" alt="Admin 6" style="width: 200px; height:200px;">
                <h3>Chris Johnson</h3>
                <p>Bartender</p>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 | Designed by Sai Hrishi.M(24900846)</p>
    </footer>
</body>
</html>
```

```
contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <div class="content">
        <h2>Get in Touch</h2>
        <p>Address: 123 Food Street, Gourmet City, GC 56789</p>
        <p>Phone: +123 456 7890</p>
        <p>Email: contact@restaurant.com</p>
    </div>
    <footer>
        <p>&copy; 2025 | Designed by Sai Hrishi.M(24900846)</p>
    </footer>
</body>
</html>
```

## OUTPUT:

![alt text](<Screenshot 2025-01-02 131054.png>)

![alt text](<Screenshot 2025-01-02 131107.png>)

![alt text](<Screenshot 2025-01-02 131337.png>)

![alt text](<Screenshot 2025-01-02 131351.png>)

![alt text](<Screenshot 2025-01-02 131401.png>)

![alt text](<Screenshot 2025-01-02 131434.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
