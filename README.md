# Ex02 Commercial Website
## Date:15/09/2025

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
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

## PROGRAM
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TrendLine - Commercial Website</title>
    <link rel="stylesheet" href="port.css">
</head>
<body>

    
    <header class="header">
        <div class="logo">TrendLine</div>
        <nav class="nav">
            <a href="#">Home</a>
            <a href="#">Products</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
    </header>

   
    <section class="hero">
        <h1>Welcome to TrendLine</h1>
        <p>Your one-stop shop for trendy fashion and accessories.</p>
        <button>Shop Now</button>
    </section>

    
    <section class="products">
        <h2>Our Best Sellers</h2>
        <div class="product-grid">
            <div class="product-card">
                <img src="https://assets.ajio.com/medias/sys_master/root/20230606/7wXp/647e8ae242f9e729d7273b80/-473Wx593H-466239355-lavender-MODEL.jpg" alt="Product 1">
                <h3>Casual Shirt</h3>
                <p>₹799</p>
            </div>
            <div class="product-card">
                <img src="https://images.meesho.com/images/products/395683058/y3hi0_512.webp?width=512" alt="Product 2">
                <h3>Leather Bag</h3>
                <p>₹1,999</p>
            </div>
            <div class="product-card">
                <img src="https://baccabucci.com/cdn/shop/files/IMG_9335-min.jpg?v=1695364953" alt="Product 3">
                <h3>Shoes</h3>
                <p>₹2,499</p>
            </div>
            <div class="product-card">
                <img src="https://www.jiomart.com/images/product/original/rvczsoocvi/punnkfunnk-gen-9-bluetooth-calling-smart-watch-specially-made-for-girl-women-free-rose-golden-strap-1-6-inch-full-sunlight-proof-display-product-images-orvczsoocvi-p608456897-0-202403141918.jpg?im=Resize=(1000,1000)" alt="Product 4">
                <h3>Watch</h3>
                <p>₹3,499</p>
            </div>
        </div>
    </section>

    <section class="about">
        <h2>About Us</h2>
        <p>At TrendLine, we believe fashion should be accessible and stylish for everyone. We bring you the latest trends at affordable prices.</p>
    </section>

    <footer class="footer">
        <p>Created by Bavadharani </p>
    </footer>

</body>
</html>
```
port.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}


.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #222;
    color: #fff;
    padding: 15px 30px;
}
.header .logo {
    font-size: 1.5rem;
    font-weight: bold;
}
.header .nav a {
    color: #fff;
    margin: 0 10px;
    text-decoration: none;
}
.header .nav a:hover {
    text-decoration: underline;
}

.hero {
    background: #f4f4f4;
    text-align: center;
    padding: 60px 20px;
}
.hero h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}
.hero button {
    background: #ff6600;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}
.hero button:hover {
    background: #e65c00;
}

.products {
    padding: 40px 20px;
    text-align: center;
}
.product-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}
.product-card {
    background: white;
    border: 1px solid #ddd;
    padding: 15px;
    width: 200px;
    text-align: center;
}
.product-card img {
    max-width: 100%;
    margin-bottom: 10px;
}
.product-card h3 {
    margin: 10px 0 5px;
}
.product-card p {
    color: green;
    font-weight: bold;
}

.about {
    background: #f9f9f9;
    padding: 30px 20px;
    text-align: center;
}

.footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}

```
## OUTPUT
<img width="1918" height="1145" alt="image" src="https://github.com/user-attachments/assets/52551295-70cb-4f63-8010-2f8ea835bc39" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
