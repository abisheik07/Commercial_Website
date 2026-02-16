# Ex02 Commercial Website
## Date:16/02/2026
## NAME: ABISHEIK RAJ J
## REG NO:212224230006

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
<html>
<head>
    <title>My Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="navbar">
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</div>

<section id="home">
    <h1>Welcome to SPADE</h1>
    <p>We provide quality products at affordable prices.</p>
</section>

<section id="products">
    <h2>Our Products</h2>

    <div class="product-container">
        <div class="product">
            <h3>Product 1</h3>
            <p>Price: ₹500</p>
        </div>

        <div class="product">
            <h3>Product 2</h3>
            <p>Price: ₹700</p>
        </div>

        <div class="product">
            <h3>Product 3</h3>
            <p>Price: ₹900</p>
        </div>
    </div>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>We are a trusted company serving customers since 2020.</p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Email: spadeshop@gmaiL.com</p>
    <p>Phone: +91 9876543210</p>
</section>

<footer>
    <p>© 2026 My Shop. All Rights Reserved.</p>
</footer>

</body>
</html>

```
style.css
```
body {
    font-family: Arial;
    margin: 0;
}

.navbar {
    background-color: black;
    padding: 15px;
    text-align: center;
}

.navbar a {
    color: white;
    text-decoration: none;
    margin: 15px;
}

.navbar a:hover {
    color: yellow;
}

section {
    padding: 30px;
    text-align: center;
}

.product-container {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.product {
    border: 1px solid gray;
    padding: 20px;
    width: 150px;
}
    
footer {
    background-color: black;
    color: white;
    text-align: center;
    padding: 10px;
}

```

## OUTPUT
<img width="1910" height="1132" alt="image" src="https://github.com/user-attachments/assets/657b545c-6ade-4b4a-9827-bd8c9321a271" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
