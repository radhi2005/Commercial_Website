# Ex02 Commercial Website
## Date:27-02-2026
# NAME:RADHIMEENA M
# REG NO:212223040159

## AIM:
To create a commercial website using CSS Flexbox.

## ALGORITHM:
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM:
## index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Radhimeena - 212223040159</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header>
        <h1> ColorCart</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
            <a href="#account">Account</a>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="home">
        <div class="home-text">
            <h2>Welcome to ColorCart</h2>
            <p>Your one stop shop for trendy products!</p>
            <button>Shop Now</button>
        </div>
        <div class="home-img">
            <img src="https://images.unsplash.com/photo-1607082348824-0a96f2a4b9da" alt="shopping">
        </div>
    </section>

    <!-- Products Section -->
    <section id="products">
        <h2 class="title">Our Products</h2>
        <div class="product-container">
            <div class="card">
                <img src="C:\Users\mhrad\Downloads\radhiii.jpg">
                <h3>Smart Phone</h3>
                <p>₹15,000</p>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1526178613552-2b45c6c302f0">
                <h3>Headphones</h3>
                <p>₹2,000</p>
            </div>

            <div class="card">
                <img src="C:\Users\mhrad\Downloads\wtach.jpg">
                <h3>Smart Watch</h3>
                <p>₹3,500</p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>ColorCart is a fast growing online shopping platform delivering quality products with exciting offers and fast delivery.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Email: support@colorcart.com</p>
        <p>Phone: +91 9876543210</p>
    </section>

    <!-- Account Section -->
    <section id="account" class="account">
        <h2>User Login</h2>
        <input type="text" placeholder="Username">
        <input type="password" placeholder="Password">
        <button>Login</button>
    </section>

    <!-- Footer -->
    <footer>
        <p>Follow Us:</p>
        <div class="social">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">Twitter</a>
        </div>
        <p>© 2026 ColorCart. All Rights Reserved.</p>
    </footer>

</body>
</html>
```
style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: linear-gradient(to right, #ff9a9e, #fad0c4);
}

/* Header */
header {
    background: #222;
    color: white;
    padding: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
    transition: 0.3s;
}

nav a:hover {
    color: yellow;
}

/* Home Section */
.home {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 50px;
    background: #fff;
}

.home img {
    width: 400px;
    border-radius: 10px;
}

.home button {
    padding: 10px 20px;
    background: #ff4b2b;
    color: white;
    border: none;
    cursor: pointer;
    transition: 0.3s;
}

.home button:hover {
    background: #ff416c;
}

/* Products */
.title {
    text-align: center;
    margin: 30px;
    color: #333;
}

.product-container {
    display: flex;
    justify-content: space-around;
    padding: 20px;
}

.card {
    background: white;
    width: 250px;
    padding: 15px;
    border-radius: 10px;
    text-align: center;
    transition: 0.3s;
}

.card img {
    width: 100%;
    border-radius: 10px;
}

.card:hover {
    transform: scale(1.05);
    box-shadow: 0 0 15px gray;
}

/* About */
.about {
    background: #4facfe;
    color: white;
    padding: 40px;
    text-align: center;
}

/* Contact */
.contact {
    background: #43e97b;
    padding: 40px;
    text-align: center;
}

/* Account */
.account {
    background: #fa709a;
    padding: 40px;
    text-align: center;
}

.account input {
    display: block;
    margin: 10px auto;
    padding: 8px;
    width: 200px;
}

.account button {
    padding: 8px 15px;
    background: black;
    color: white;
    border: none;
}

/* Footer */
footer {
    background: #111;
    color: white;
    text-align: center;
    padding: 20px;
}

.social a {
    color: yellow;
    margin: 0 10px;
    text-decoration: none;
}
```
## OUTPUT:
<img width="1348" height="646" alt="image" src="https://github.com/user-attachments/assets/ea9335f6-1812-4c94-910d-f9427a33d3e9" />
<img width="1343" height="642" alt="image" src="https://github.com/user-attachments/assets/240f13e5-42f6-49d1-81e5-af2111350d0e" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
