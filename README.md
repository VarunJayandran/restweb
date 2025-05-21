# Ex.07 Restaurant Website
# Date:20/05/2025
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
HOME.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MAD HOUSE</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MAD HOUSE</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>WELCOME TO MAD HOUSE CHAIN OF RESTAURANTS</h1>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="team.html">Team</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    

    <section id="about">
        <h2>About Us</h2>
        <p>Welcome to MAD HOUSE Restaurant, where we serve the finest dishes made from the fresh ingredients. Our chefs are dedicated to providing you with an unforgettable dining experience.</p>
    </section>
    <div class="image-row">
        <img src="hire-south-indian-chef-for-hotel.jpg" alt="Image 1" width="420" height="250">
        <img src="download.jpg" alt="Image 2" width="420" height="250">
        <img src="Untitled design (14).webp" alt="Image 3" width="420" height="250">
    </div>
    

</body>
</html>
~~~
menu.html
~~~
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>MENU</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="team.html">Team</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="mutton-biriyani-recipe.jpeg" alt="Chicken biriyani" width="150">
                <p>Chicken biriyani - 210 Rs</p>
            </div>
            <div class="menu-item">
                <img src="images.jpg" alt="Chicken Soup" width="150">
                <p>Chicken Soup - 80 Rs</p>
            </div>
            <div class="menu-item">
                <img src="hm-soy-sauce-noodles-with-cabbage-mpwf-superJumbo.jpg" alt="noodle" width="150">
                <p>noodle - 175 Rs</p>
            </div>
            <div class="menu-item">
                <img src="Chicken-burger-recipes-d0908a0.jpg" alt="Cheese Burger" width="150">
                <p>Cheese Burger - 199 Rs</p>
            </div>
            <div class="menu-item">
                <img src="Pizza-3007395.jpg" alt="Pizza" width="150">
                <p>Pizza - 299 Rs</p>
            </div>
            <div class="menu-item">
                <img src="1200x900px_French_Fries_Overload_With_Beef.png" alt="Loaded Fries" width="150">
                <p>Loaded Fries - 99 Rs</p>
            </div>
            <div class="menu-item">
                <img src="Mediterranean-tomato-and-cucumber-salad-11.jpg" alt="Salad" width="150">
                <p>Salad - 149 Rs</p>
            </div>
            <div class="menu-item">
                <img src="Frozen-Hashbrowns-in-Air-Fryer-SQUARE.jpg" alt="hash browns" width="150">
                <p>hash browns - 169 Rs</p>
            </div>
            <div class="menu-item">
                <img src="Pasta-Alfredo-1-3.jpg" alt="Pasta" width="150">
                <p>Italian Pasta - 299 Rs</p>
            </div>
            <div class="menu-item">
                <img src="2-hersheys-perfectly-chocolate-chocolate-cake-recipe-hero.jpg" alt="cake" width="150">
                <p>Chocolate cake - 159 Rs</p>
            </div>
            <div class="menu-item">
                <img src="chocolate-icecream-in-an-icecream-maker.jpg" alt="Ice Cream" width="150">
                <p>Ice Cream - 99 Rs</p>
            </div>
            <div class="menu-item">
                <img src="best-coffee-brands-2.avif" alt="Espresso" width="150">
                <p>Espresso  - 49 Rs</p>
            </div>
        </div>        
    </section>
</body>
</html>
~~~
team.html
~~~
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Team</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Meet Our Team</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section>
        <div class="team">
            <div class="team-member">
                <img src="ceo.jpg" alt="Owner" class="team-img">
                <p><b>VARUN JAYANDRAN</b></p>
                <p>25 Year of Experience</p>
            </div>
            <div class="team-member">
                <img src="chef-cooking-kitchen-while-wearing-professional-attire_23-2151208316.avif" alt="Chef adavan" class="team-img">
                <p><b>NITHISH</b></p>
                <p>Head Chef - Expert in Multi Cuisine</p>
            </div>
            <div class="team-member">
                <img src="istockphoto-1165683221-612x612.jpg" alt="Chef Johnson" class="team-img">
                <p><b>SANJAY</b></p>
                <p>Pastry Chef - Creating Delicious Desserts</p>
            </div>
            <div class="team-member">
                <img src="we-serve-best-cakes_637285-7884.avif" alt="KANNAN" class="team-img">
                <p><b>ARSHAD</b></p>
                <p>Waiter - Your Destination for the Best Service</p>
            </div>
            <div class="team-member">
                <img src="BAR.jpg" alt="NEASAMANI" class="team-img">
                <p><b>BALA</b></p>
                <p>BARTENDER - Meant for the Best Service</p>
            </div>
        </div>
    </section>
</body>
</html>
~~~
contact.html
~~~
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="team.html">Team</a></li>
            </ul>
        </nav>
    </header>
    <section>
        <p>Email: madhouse@gmail.com</p>
        <p>Phone: +91 9383938393</p>
        <b>Address: 69/96, KOLATHUR, Chennai</b>
    </section>
    
</body>
</html>
~~~
styles.css
~~~
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.9;
    font-size: large;
    background-image: url('99-996466_background-images-for-restaurants.jpg');
    background-size: cover; 
    background-position: center;
    background-repeat: no-repeat; 
    height: 100vh;
    color: rgb(0, 0, 0);
}
header {
    background-image: url('99-996466_background-images-for-restaurants.jpg'); 
    color: rgb(0, 0, 0);
    padding: 10px 0;
    text-align: center;
    font-style: oblique;
    border-radius: 20px;
}


nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: rgb(239, 0, 0);
    text-decoration: none;
    font-weight: bold;
    font-size: larger;
}

section {
    padding: 20px;
    margin: 30px;
}



footer {
    text-align: center;
    padding: 10px 0;
    background: #050602;
    color: rgb(9, 9, 9);
    position: fixed;
    bottom: 0;
    width: 100%;
    

    
}

.menu-grid {
    display: grid;
    grid-template-columns: repeat(6, 1fr); 
    gap: 20px;
    margin: 20px auto;
    text-align: center;
}

.menu-item img {
    width: 150px;
    height: 150px; 
    object-fit: cover; 
    border: 2px solid #ffffff; 
    border-radius: 5px; 
    display: block; 
    margin: 0 auto; 
}

.menu-item p {
    margin-top: 10px; 
    font-size: 17px; 
    color: #000000; 
    font-weight: 800;
}

.team {
    display: flex;
    justify-content: center;
    flex-wrap: wrap; 
    gap: 75x; 
    margin: 10px auto;
    max-width: 1200px; 
}

.team-member {
    text-align:center;
    width: 200px; 
}

.team-img {
    width: 150px; 
    height: 150px; 
    object-fit: cover; 
    border-radius: 50%;
    margin-bottom: 10px;
}

.team-member p {
    margin: 5px 0;
    font-size: 24px;
    color: #000000;
}
.image-row {
    display: flex; 
    justify-content: center; 
    gap: 25px;
    margin: 20px 0; 
}

.image-row img {
    border: 6px solid #0a0a0a; 
    border-radius: 20px; 
}
~~~
# OUTPUT:
![001](https://github.com/user-attachments/assets/a661e6f0-6724-4191-b232-cc57c7a9cc0f)
![002](https://github.com/user-attachments/assets/d37fb66c-00a5-4768-97d9-e5ae2bac2323)
![003](https://github.com/user-attachments/assets/f9562776-a101-468e-abcb-85b606d66665)
![004](https://github.com/user-attachments/assets/51f24f0d-3f5b-4002-a2dc-7d26600df249)



# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
