# Ex.07 Restaurant Website
# Date:
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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - THE GOLDEN PLATR</title>
  <link rel="stylesheet" href="home.css">
</head>
<body>
  <header>
    <h1>Welcome to THE GOLDEN PLATE</h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>
  <div class="banner"></div>
  <div class="container">
    <h2>About Us</h2>
    <p>We serve the most delicious food in town using only the freshest ingredients.</p>
  </div>
  <footer>
    <p>Website designed by BARKAVI</p>
  </footer>
</body>
</html>
```
menu.html
  ```
  <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Menu</title>
<link rel="stylesheet" href="menu.css">
</head>
<body>
<header>
  <h1>Our Menu</h1>
</header>
<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="admin.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>
<div class="container">
  <div class="menu-grid">
    <!-- Repeat for 12 items -->
    <div class="item">
      <img src="ff.jpg" alt="frenchfries">
      <h3>frenchfries</h3>
      <p>Rs.250</p>
    </div>
    <div class="item">
      <img src="pzz.jpg" alt="pizza">
      <h3>pizza</h3>
      <p>Rs.399</p>
    </div>
    <div class="item">
      <img src="vgs.jpg" alt="vegsandwich">
      <h3>vegsandwich</h3>
      <p>Rs.180</p>
    </div>
    <div class="item">
      <img src="hi.webp" alt="hot ice cream">
      <h3>hot ice cream</h3>
      <p>Rs.75</p>
    </div>
    <div class="item">
      <img src="wpppppp.jpg" alt="whitepasta">
      <h3>whitepasta</h3>
      <p>Rs.210</p>
    </div>
    <div class="item">
      <img src="nnnn.jpg" alt="noodles">
      <h3>noodles</h3>
      <p>Rs.150</p>
    </div>
    <div class="item">
      <img src="vf.webp" alt="vegfrankie">
      <h3>vegfrankie</h3>
      <p>Rs.240</p>
    </div>
    <div class="item">
      <img src="clll.jpg" alt="chicken lolipop">
      <h3>chicken lolipop</h3>
      <p>Rs.199</p>
    </div>
    <div class="item">
      <img src="fsfy.jpg" alt="fishfry">
      <h3>fishfry</h3>
      <p>Rs.999</p>
    </div>
    <div class="item">
      <img src="cm.jpg" alt="chicken momos">
      <h3>chicken momos</h3>
      <p>Rs.620</p>
    </div>
    <div class="item">
      <img src="c65555.jpg" alt="chicken 65">
      <h3>chicken 65</h3>
      <p>Rs.450</p>
    </div>
    <!-- Add 10 more -->
  </div>
</div>
<footer>
  <p>Website designed by BARKAVI</p>
</footer>
</body>
</html>



```
menu.css
```
body {
    font-family: sans-serif;
    background-color: #fdf6ec;
    margin: 0;
  }
  
  header {
    background-color: #8B0000;
    color: white;
    padding: 20px;
    text-align: center;
  }
  
  nav {
    background-color: #eee;
    text-align: center;
    padding: 10px;
  }
  
  nav a {
    margin: 0 15px;
    text-decoration: none;
    color: #8B0000;
  }
  
  .container {
    padding: 20px;
  }
  
  .menu-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
  }
  
  .item {
    background-color: white;
    padding: 10px;
    text-align: center;
    border: 1px solid #ccc;
  }
  
  .item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
  }
  
  footer {
    background-color: #8B0000;
    color: white;
    text-align: center;
    padding: 10px;
  }
  ```

admin.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Administration</title>
<link rel="stylesheet" href="admin.css">
</head>
<body>
<header>
  <h1>Our Team</h1>
</header>
<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="admin.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>
<div class="container">
  <div class="team">
    <!-- Repeat for 6 members -->
    <div class="member">
      <img src="mmm.webp" alt="Chef">
      <h3>Madhampatty rangaraj</h3>
      <p>Head Chef</p>
    </div>
    <div class="member">
      <img src="fmmmm.jpg" alt="Chef">
      <h3>Jane Smith</h3>
      <p>Chef</p>
    </div>
    <div class="member">
      <img src="jenii.jpg" alt="Manager">
      <h3>Jenifer</h3>
      <p>Manager</p>
    </div>
    <div class="member">
      <img src="johnn.jpg"h3>
      <h3>John</h3>
      <p>Chef</p>
    </div>
    <!-- 4 more -->
  </div>
</div>
<footer>
  <p>Website designed by BARKAVI</p>
</footer>
</body>
</html>

```
admin.css
```
body {
    font-family: sans-serif;
    background-color: #f9f9f9;
    margin: 0;
  }
  
  header, footer {
    background-color: #8B0000;
    color: white;
    text-align: center;
    padding: 20px 10px;
  }
  
  nav {
    background-color: #ddd;
    text-align: center;
    padding: 10px;
  }
  
  nav a {
    margin: 0 15px;
    text-decoration: none;
    color: #8B0000;
  }
  
  .container {
    padding: 20px;
  }
  
  .team {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
  }
  
  .member {
    background: white;
    padding: 10px;
    text-align: center;
  }
  
  .member img {
    width: 100%;
    height: 200px;
    object-fit: cover;
  }
  ```
  contact.html
  ```
  <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Contact Us</title>
<link rel="stylesheet" href="contact.css">
</head>
<body>
<header>
  <h1>Contact Us</h1>
</header>
<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="admin.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>
<div class="container">
  <h2>Reach Out to Us</h2>
  <p><strong>Address:</strong>RR nagar Town virudhunagar </p>
  <p><strong>Phone:</strong>8056722054</p>
  <p><strong>Email:</strong> thegoldenplate@gmail.com</p>
</div>
<footer>
  <p>Website designed by BARKAVI</p>
</footer>
</body>
</html>

```
contact.css
```
body {
    font-family: sans-serif;
    background-color: #f2f2f2;
    margin: 0;
  }
  
  header, footer {
    background-color: #8B0000;
    color: white;
    text-align: center;
    padding: 20px;
  }
  
  nav {
    background-color: #eee;
    text-align: center;
    padding: 10px;
  }
  
  nav a {
    margin: 0 15px;
    text-decoration: none;
    color: #8B0000;
  }
  
  .container {
    padding: 30px;
    background-color: white;
    margin: 20px;
    border-radius: 8px;
  }
  ```

# OUTPUT:
![alt text](<Screenshot (238).png>)
![alt text](<Screenshot (241).png>)
![alt text](<Screenshot (242).png>)
![alt text](<Screenshot (243).png>)
![alt text](<Screenshot (245).png>)
![alt text](<Screenshot (246).png>)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
