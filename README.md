# Ex.06 Restaurant Website
## Date:23.12.2025

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

rest.html:

<html>
<head>
    <title>Thalapakkatti Restaurant</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>Thalapakkatti Restaurant</h1>
</header>

<nav>
    <a href="rest.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <img src="banner.jpg" alt="Restaurant Banner" style="width:80%; max-width:900px; border-radius:10px;">
    <h2>Welcome to Thalapakkatti</h2>
    <p>Authentic flavors, fresh ingredients, and a cozy dining experience.</p>
</section>

<footer>
    © Designed by devendran G.
</footer>
</body>
</html>

admin.html:

<html>
<head>
    <title>Thalapakkatti - Administration</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>Thalapakkatti Restaurant</h1>
</header>

<nav>
    <a href="rest.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Meet Our Team</h2>
    <div class="team-grid">
        <div class="card"><img src="image.2.jpg"><p>administrator-owner</p></div>
        <div class="card"><img src="person1.jpg"><p>Person 1 - Head Chef</p></div>
        <div class="card"><img src="person2.jpg"><p>Person 2 - Manager</p></div>
    </div>
</section>

<footer>
    © Designed by devendran G.
</footer>
</body>
</html>

contact.html:

<html>
<head>
    
    <title>Thalapakkatti - Contact Us</title>
    <link rel="stylesheet" href="index.css">
    
        
        
</head>
<body>

<header>
    <h1>Thalapakkatti Restaurant</h1>
</header>

<nav>
    <a href="rest.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <div class="contact-container">
        <h2>Contact Us</h2>
        <p><b>Address:</b> No. 83, Anna Salai,Mount Road, Chennai,Tamil Nadu 600002</p>
        <p><b>Phone:</b> +91 8989505660</p>
        <p><b>Email:</b> contact@dev.com</p>
        <p><b>Opening Hours:</b> Mon-Sun: 10:00 AM - 10:00 PM</p>
    </div>
</section>

<footer>
    © Designed by devendran G.
</footer>
</body>
</html>

index.css:
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #fff7f5;
    background-image:url("background.png") ;
    color: #333;
}
header {
    background-color: #b33a3a; /* Primary color */
    color: white;
    padding: 20px;
    text-align: center;
}
nav {
    background-color: #333;
    text-align: center;
}
nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    padding: 8px;
    display: inline-block;
}
nav a:hover {
    background-color: #f2c57c; /* Accent color */
    color: #333;
}
section {
    padding: 40px;
    text-align: center;
}
section p {
    color:yellow;

}
h2 {
    color: #b33a3a;
    font-style:oblique;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.menu-grid, .team-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    max-width: 1000px;
    margin: 20px auto;
    text-align: center;
    
}
.card {
    background-color: white;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    font-style: italic;
    color:#b33a3a;
    text-shadow:#f2c57c;
}
.card img {
    width: 80px;
    height: 100px;
    object-fit: cover;
    border-radius: 25px;
    align-items: center;
    border: #f2c57c;
    
}
footer {
    background-color:#333;
    color: white;
    
    text-align: center;
    padding: 15px;
}
contact-container {

            max-width: 800px;
            margin: 0 auto;
            text-align: left;
            padding: 20px;
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(240, 228, 8, 0.927);
        }
        .contact-container h2 {
            text-align: center;
            color: #b33a3a;
        }
        .contact-container p {
            color: aliceblue;
            font-size: 18px;
            margin: 10px 0;
        }
        .contact-container b {
            color: #b33a3a;
        
    
    
}

```

## OUTPUT:
![alt text](<Screenshot (38).png>)
![alt text](<Screenshot (39).png>) 
![alt text](<Screenshot (40).png>) 
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>) 
![alt text](<Screenshot (43).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
