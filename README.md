# Ex.07 Restaurant Website
# Date:06/10/25
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
home.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>STREET Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <h1>Street Restaurant</h1>
        <nav>
            <a href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="administration.html">Administration</a>
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>

    <section class="banner">
        <div class="image"> 
        <img src="home page.png" alt="Delicious Food Banner" >
        </div>
    </section>

    <section class="content">
        <h2>Welcome!</h2>
        <p>Discover the best food in town, made with passion,love and fresh ingredients.</p>
    </section>

    <footer>
        <p>&copy; 2025. Designed by PIRUTHIVIRAJ G</p>
    </footer>
</body>

</html>

menu.html
 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="menu-grid">
    <!-- Repeat for 12 items -->
    <div class="menu-item">
      <img src="burger.jpg" alt="Burger">
      <h3>Quinoa Burger</h3>
      <p>The burger patty is made from quinoa,a protein-rich seed and topped with melted cheese,caramelized onions,and sweet potato fries .</p>
    </div>
    <div class="menu-item">
      <img src="pasta.jpg" alt="Pasta">
      <h3>Penne Bolognese</h3>
      <p>The sauce is a classic italian meat sauce made with ground meat,tomatoes,and other vegetables like carrots and celery.</p>
    </div>
    <div class="menu-item">
      <img src="white pasta.jpg" alt="White sauce pasta">
      <h3>White sauce pasta</h3>
      <p>The pasta is tossed in a sauce made from milk,butter,and flour.the dish often include various vegetables and seasoned with herbs and spices.</p>
    </div>
    <div class="menu-item">
      <img src="noddles.jpg" alt="Noodles">
      <h3>Spaghetti with meatballs</h3>
      <p>The dish consists of spaghetti pastha topped with a tomato-based sauce and meatball,often served with grated cheese like parmesan.</p>
    </div>
    <div class="menu-item">
      <img src="lobster.jpg" alt="Lobster">
      <h3>Baked stuffed lobster</h3>
      <p>The meat is removed from the lobster and mix it with the stuffing.The mixture is then placed back into lobster shell and backed until it turn golden browen.</p>
    </div>
    <div class="menu-item">
      <img src="fruit juice.jpeg" alt="juice">
      <h3>fruit juice</h3>
      <p>This fruit drinks contains minerals and lack of fiber.</p>
    </div>
    <center><div class="menu-item">
      <img src="desert.jpg" alt="desert">
      <h3>Sizzling brownie with ice creame</h3>
      <p>The chocolate brownie is topped with a scoop of vanilla ice creame and drizzled with chocolate sauce.</p>
    </div></center>
    
    
  </section>

  <footer>
    <p>&copy; 2025. Designed by PIRUTHIVIRAJ G</p>
  </footer>
</body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="contact-info">
    <h2>service provider</h2>
    <p>📍 <strong>Address:</strong> 123 Food Street, Gourmet City, FL 45678</p>
    <p>📞 <strong>Phone:</strong> 9900000099</p>
    <p>✉ <strong>Email:</strong> availablealways@gmail.com</p>
  </section>

  <!-- Optional: Contact Form (if needed) -->
  <!--
  <section class="contact-form">
    <form>
      <label for="name">Name:</label><br>
      <input type="text" id="name" name="name"><br><br>

      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email"><br><br>

      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="5"></textarea><br><br>

      <button type="submit">Send Message</button>
    </form>
  </section>
  -->

  <footer>
    <p>&copy; 2025. Designed by PIRUTHIVIRAJ G</p>
  </footer>

</body>
</html>

administration.html
  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Administration</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="admin-grid">
    <!-- Repeat for 6 people -->
    <div class="admin-card">
      <img src="manager.jpeg" alt="Admin 1">
      <h3>John Smith</h3>
      <p>Manager</p>
    </div>
    <div class="admin-card">
      <img src="head chef.jpg" alt="Admin 2">
      <h3>David Lee</h3>
      <p>Head Chef</p>
    </div>
    <div class="admin-card">
      <img src="chef.jpeg" alt="Admin 3">
      <h3>Emily Rose</h3>
      <p>Assistant Chef</p>
    </div>
    <div class="admin-card">
      <img src="cashier.jpeg" alt="Admin 4">
      <h3>Sophie</h3>
      <p>Cashier</p>
    </div>
    <div class="admin-card">
      <img src="customer service.jpg" alt="Admin 6">
      <h3>Mike Jordan</h3>
      <p>Customer Service</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by PIRUTHIVIRAJ G</p>
  </footer>
</body>
</html>
```
# OUTPUT:
![alt text](<../Screenshot 2025-10-06 201536.png>)
![alt text](<../Screenshot 2025-10-06 201604.png>)
![alt text](<../Screenshot 2025-10-06 201623.png>)
![alt text](<../Screenshot 2025-10-06 201637.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
