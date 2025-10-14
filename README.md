# Ex.07 Restaurant Website
## Date:15/10/2025

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
<html>
    <head>
        <title>Tokyo Breeze - Home</title>
        <link rel="stylesheet" href="home.css">
    </head>
    <body>
        <header>
            <nav>
                <ul class="navbar">
                    <li><a href="home.html">Home</a>
                        
                    </li>
                    <li><a href="menu.html">Menu</a>
                       
                    </li>
                    <li><a href="admin.html">Admin</a>
                        
                    </li>
                    <li><a href="contact.html">Contact</a>
                        
                    </li>
                </ul>
            </nav>
        </header>

        <section class="head">
            <h1 class="title">Tokyo Breeze</h1>
            <p class="tagline">A Breeze of Flavours from the Heart of Japan</p>
            <img src="Restaurant img.jpg"  class="head-img">
            <p class="intro">Tokyo Breeze blends the artistry of Japanese cuisine with a touch of modern charm. Feel the breeze of flavours dancing through every dish which feels refreshing, light and unforgettable.</p>
        </section>

        <footer>
            <p>&copy; Sandya S - 25017264. All Rights Reserved.</p>
        </footer>
    </body>
</html>

menu.html
<html>
    <head>
        <title>Tokyo Breeze - Menu</title>
        <link rel="stylesheet" href="menu.css">
    </head>
    <body>
        <header>
            <nav>
                <ul class="navbar">
                    <li><a href="home.html">Home</a>
                        
                    </li>
                    <li><a href="menu.html">Menu</a>
                        
                    </li>
                    <li><a href="admin.html">Admin</a>
                        
                    </li>
                    <li><a href="contact.html">Contact</a>
                        
                    </li>
                </ul>
            </nav>
        </header>

        <section class="menu-section">
            <h1>Menu</h1>
            <div class="menu-container">
              <div class="menu-item"><img src="sushi.jpg"><p>Sushi Platter</p></div>
              <div class="menu-item"><img src="ramen.jpg"><p>Ramen</p></div>
              <div class="menu-item"><img src="tempura shrimp.jpg"><p>Tempura Shrimp</p></div>
               <div class="menu-item"><img src="sashimi slices japanese.jpg"><p> Sashimi Slices</p></div>
               <div class="menu-item"><img src="miso soup.jpg"><p>Miso Soup</p></div> 
               <div class="menu-item"><img src="matcha dessert.webp"><p>Matcha Dessert</p></div>
               <div class="menu-item"><img src="bento box.jpg"><p>Bento Box</p></div>
               <div class="menu-item"><img src="teriyaki chicken.jpg"><p>Teriyaki Chicken</p></div>
                <div class="menu-item"><img src="japanese green tea.jpeg"><p>Japanese Green Tea</p></div>
                <div class="menu-item"><img src="dorayaki.jpg"><p>Dorayaki</p></div>
                </div>
        </section>

        <footer>
            <p>&copy; Sandya S - 25017264. All Rights Reserved.</p>
        </footer>
    </body>
</html>

admin.html
<html>
    <head>
        <title>Tokyo Breeze - Team</title>
        <link rel="stylesheet" href="admin.css">
    </head>
    <body>
        <header>
            <nav>
                <ul class="navbar">
                    <li><a href="home.html">Home</a>
                        
                    </li>
                    <li><a href="menu.html">Menu</a>
                        
                    </li>
                    <li><a href="admin.html">Admin</a>
                        
                    </li>
                    <li><a href="contact.html">Contact</a>
                        
                    </li>
                </ul>
            </nav>
        </header>

        <section class="team-section">
            <h1>Meet Our Team</h1>
            <p class="team-intro">The breeze of perfection begins with our people - the heart behind every flavour of Tokyo Breeze.</p>
            <div class="team-container">
            <div class="team-member">
                <img src ="IMG-20250625-WA0039.jpg">
                <h3>Sandya</h3>
                <p>Founder & CEO</p>
            </div>
            <div class="team-member">
                <img src="General Manager.jpg">
                <h3>Haruto</h3>
                <p>General Manager</p>
            </div>
            <div class="team-member">
                <img src="Assistant Manager.jpg">
                <h3>Sophie</h3>
                <p>Assistant Manager</p>
            </div>
            <div class="team-member">
                <img src="restaurant administrator - Copy.jpg">
                <h3>Julie</h3>
                <p>Restaurant Administrator</p>
            </div>
            <div class="team-member">
                <img src="executive chef.jpg">
                <h3>Takashi</h3>
                <p>Executive Chef</p>
            </div>
        </section>

        <footer>
            <p>&copy; Sandya S - 25017264. All Rights Reserved.</p>
        </footer>
    </body>
    
</html>

contact.html
<html>
    <head>
        <title>Tokyo Breeze - Contact Us</title>
        <link rel="stylesheet" href="contact.css">
    </head>
    <body>
        <header>
            <nav>
                <ul class="navbar">
                    <li><a href="home.html">Home</a>
                        
                    </li>
                    <li><a href="menu.html">Menu</a>
                        
                    </li>
                    <li><a href="admin.html">Admin</a>
                        
                    </li>
                    <li><a href="contact.html">Contact</a>
                        
                </ul>
            </nav>
        </header>

        <section class="contact-section">
            <h1>Contact Us</h1>
            <p>We'd love to hear from you!</p>

            <div class="contact-info">
                <p><b>Address: 545, Cherry Blossom Avenue, Blossom Heights, India</i> </b></p>
                <p><b>Email:</b>sandya.s.0504@gmail.com</p>
                <p><b>Phone:</b>+91 9876543210</p>
                <p><b>Open hours:</b>Mon-Sun | 11.00 AM - 10.00 PM</p>
            </div>
        </section>

        <footer>
            <p>&copy; Sandya S - 25017264. All Rights Reserved.</p>
        </footer>
    </body>
</html>

home.css
body {
  font: arial;
  margin: 0;
  padding: 0;
  background: url('Restaurant img.jpg') ;
  background-size: cover;
  background-position: center;
  text-align: center;
  height: 100%;
}

header {
  background-color: palevioletred;
  padding: 20px ;
}

.navbar {
  display: flex;
  justify-content: right;
  gap: 30px;
  margin: 0;
  padding: 0;
}

.navbar li a {
  color: white;
  font-weight: bold;
  font-size: 16px;
}

.navbar li a:hover {
  color: pink;
}

.head {
  padding: 40px;
  background-color: lavender;
  border-radius: 15px;
  margin: 40px auto;
  width:150vh;
  height:66vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-evenly;
}

.title {
  font: italic;
  font-size: 50px;
  color: violet;
  margin: 0;
}

.tagline {
  font-size: 18px;
  margin-top: 20px;
}

.head-img {
  width: 70%;
  max-width: 500px;
  border-radius: 10px;
  margin-top: 10px;

}

.intro {
  font-size: 20px;
  margin: 20px auto;
  width: 80%;
  color: darkmagenta;

}

footer {
  background-color: black;
  padding: 10px;
  color: white;
  font-size: 14px;
}

menu.css
body {
  margin: 0;
  font: arial;
  background: url('menu bg.jpg');
  background-size: cover;
  color: white;
}

header {
  background-color: palevioletred;
  padding: 10px ;
}

.navbar {
  display: flex;
  justify-content: right;
  gap: 30px;
}

.navbar li a {
  color: white;
  font-weight: bold;
  font-size: 16px;
  margin: 0;
  padding: 0;
}

.navbar li a:hover {
  color: pink;
}

.menu-section {
  padding: 5px;
  text-align: center;
  background-color: black;
  border-radius: 15px;
  margin: 20px 40px 10px 40px;
}

h1 {
  color: pink;
  font-size: 42px;
}

.menu-container {
  display: flex;
  flex-wrap:wrap;
  justify-content: center;
  gap: 30px;
  margin-top: 20px;
}

.menu-item {
  width: 200px;
  background-color: grey;
  border-radius: 15px;
  padding: 5px;
  box-shadow: 0 4px 10px gray;
  text-align: center;
}

.menu-item img {
  width: 100%;
  height: 180px;
  border-radius: 10px;
  object-fit: cover;
}

.menu-item p {
  font-size: 20px;
  color: black;
}

footer {
  background-color: black;
  padding: 5px;
  color: white;
  font-size: 14px;
  text-align: center;
}

admin.css
body {
  font: arial;
  margin: 0;
  background: url('admin bg.webp');
  background-size: cover;
  color: white;
  text-align: center;
}

header {
  background-color: palevioletred;
  padding: 10px ;
}

.navbar {
  display: flex;
  justify-content: right;
  gap: 30px;
}

.navbar li a {
  color: white;
  font-weight: bold;
}

.navbar li a:hover {
  color: pink;
}

.team-section {
  padding: 20px 20px;
  background-color: black;
  margin: 30px;
  font-size: 20px;
}

.team-section p {
  font-size: 18px;
  color: white;
}

.team-container {
  display: flex;
  justify-content: center;
  gap: 30px;
}

.team-member {
  background-color: grey;
  
  padding: 20px;
  width: 300px;
}

.team-member img {
  width: 100%;
  height: 300px;

  object-fit: cover;
  border: 3px solid pink;
}

footer {
  background-color: black;
  padding: 10px;
  color: white;
  font-size: 14px;
  text-align: center;
}

contact.css
body {
  font:arial;
  margin: 0;
  background: url('menu bg.jpg');
  background-size: cover;
  color: white;
  text-align: center;
}

header {
  background-color: palevioletred;
  padding: 10px ;
}

.navbar {
  display: flex;
  justify-content: right;
  gap: 30px;
}

.navbar li a {
  color: white;
  font-weight: bold;
}

.navbar li a:hover {
  color: pink;
}

.contact-section {
  padding: 80px 20px;
  background-color: black;
  margin: 80px;
  border-radius: 20px;
  
}

.contact-info p {
  font-size: 20px;
  color: white;
}

footer {
  background-color: black;
  padding: 15px;
  color: white;
  font-size: 14px;
  text-align: center;
}

```


## OUTPUT:
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)
![alt text](<Screenshot (46).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
