# Ex.07 Restaurant Website
## Date:22/12/2024

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
'''
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin : 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background-image: url('Screenshot 2024-12-17 191121.png');
            background-size: cover;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }
        header h1 {
            font-size: 3rem;
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #343a40;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
            display: block;
        }
        nav a:hover {
            background-color: #495057;
        }
        .container {
            padding: 20px;
        }
        .menu-items, .admin, .contact {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .menu-item, .admin-card {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 10px;
            text-align: center;
            flex: 1 1 calc(25% - 40px);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .menu-item img, .admin-card img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Taste Junction</h1>
        <p>Your ultimate stop for irresistible tastes</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#administration">Administration</a>
        <a href="#contact">Contact Us</a>
    </nav>
    
    <section id="home" class="container">
        <h2>Home</h2>
        <p>Taste Junction: Your journey to deliciousness starts here.<br>A destination for food lovers, a junction for taste.</p>
    </section>

    <section id="menu" class="container">
        <h2>Menu</h2>
        <div class="menu-items">
            <div class="menu-item">
                <img src="img1 web.png" alt="Dish 1">
                <p>Mayasiyan Parotta</p>
            </div>
            <!-- Repeat for 12 items -->
            <div class="menu-item">
                <img src="img2web.jpeg" alt="Dish 12">
                <p>Butter Chicken with Naan</p>
            </div>
            <div class="menu-item">
                <img src="img3 web.jpeg" alt="Dish 12">
                <p>Biriyani</p>
            </div>
            <div class="menu-item">
                <img src="img4 web.jpeg" alt="Dish 12">
                <p>Sushi Platter</p>
            </div>
            <div class="menu-item">
                <img src="img5 web.jpeg" alt="Dish 12">
                <p>Chocolate Lava Cake</p>
            </div>
            <div class="menu-item">
                <img src="img6 web.png" alt="Dish 12">
                <p>South Indian special</p>
            </div>
            <div class="menu-item">
                <img src="img7 web.jpeg" alt="Dish 12">
                <p>Tiramisu</p>
            </div>

            <div class="menu-item">
                <img src="img8 web.jpeg" alt="Dish 12">
                <p>Veggie Burger with Sweet Potato Fries</p>
            </div>
            <div class="menu-item">
                <img src="img9 web.jpeg" alt="Dish 12">
                <p>Shrimp Alfredo Pasta</p>
            </div>
            <div class="menu-item">
                <img src="img10 web.jpeg" alt="Dish 12">
                <p>Margherita Pizza</p>
            </div>
            <div class="menu-item">
                <img src="img11 web.jpeg" alt="Dish 12">
                <p>Mediterranean Falafel Wrap</p>
            </div>
            <div class="menu-item">
                <img src="img12 web.png" alt="Dish 12">
                <p>Adobo Chicken Wings</p>
            </div>
            
        </div>
    </section>

    <section id="administration" class="container">
        <h2>Administration</h2>
        <div class="admin">
            <div class="admin-card">
                <img src="can-1.jpeg" alt="Admin 1">
                <p> Sanjeev Kapoor- Manager</p>
            </div>
            <!-- Repeat for 6 people -->
            <div class="admin-card">
                <img src="can-2.webp" alt="Admin 6">
                <p>Chef</p>
            </div>
        </div>
    </section>

    <section id="contact" class="container">
        <h2>Contact Us</h2>
        <p>Address: 123 Food Street,Saveetha Nagar,Thandalam,Chennai</p>
        <p>Phone: 012-8975564</p>
        <p>Email: contact@tastejunction.com</p>
    </section>

    <footer>
        <p>&copy; 2024 Taste Junction | Designed by Austin Aro A</p>
    </footer>
</body>
</html>
'''

## OUTPUT:

![alt text](image.png)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
