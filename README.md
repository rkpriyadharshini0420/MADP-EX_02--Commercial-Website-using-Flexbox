# Ex02 Commercial Website
## Date: 08-08-2025

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
# Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Commercial Website</title>
  <link rel="stylesheet" href="index.css">
</head>
<body>

  <header>
    <div class="container">
      <h1 class="logo">RentalBusiness</h1>
      <nav>
        <ul class="nav-links">
          <li><a href="#hero">Home</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="hero">
    <div class="container">
      <h2>Welcome to Our Commercial Website</h2>
      <p>We provide the best services for your business growth.</p>
      <a href="#services" class="btn">Explore Services</a>
    </div>
  </section>

  <section id="services">
    <div class="container">
      <h2>Our Services</h2>
      <div class="service-boxes">
        <div class="box">
          <h3>Web Design</h3>
          <p>Creative and responsive designs for your online presence.</p>
        </div>
        <div class="box">
          <h3>Marketing</h3>
          <p>Digital marketing solutions to boost your brand.</p>
        </div>
        <div class="box">
          <h3>Consulting</h3>
          <p>Professional advice tailored for your business goals.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="about">
    <div class="container">
      <h2>About Us</h2>
      <p>We are a team of experts passionate about helping businesses thrive. Our mission is to deliver top-notch commercial solutions for your success.</p>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" rows="5" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 MyBusiness. All Rights Reserved.</p>
    </div>
  </footer>

</body>
</html>


```

# Index.css

```

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
}

header {
  background: #333;
  color: #fff;
  padding: 20px 0;
  height: 70px;
}

.logo {
  float: left;
  font-size: 24px;
  font-weight: bold;
}

nav {
  float: right;
}

.nav-links {
  list-style: none;
}

.nav-links li {
  display: inline;
  margin-left: 20px;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

#hero {
  background: #007BFF;
  color: #fff;
  padding: 80px 0;
  text-align: center;
}

#hero .btn {
  display: inline-block;
  padding: 20px 20px;
  background: #fff;
  color: #007BFF;
  text-decoration: none;
  margin-top: 20px;
  border-radius: 5px;
}

#services, #about, #contact {
  padding: 60px 0;
  background: #fff;
}

#services .service-boxes {
  display: flex;
  justify-content: space-between;
  margin-top: 30px;
}

.box {
  flex: 1;
  margin: 0 10px;
  padding: 20px;
  background: #f9f9f9;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
}

form input, form textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 15px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

form button {
  background: #007BFF;
  color: #fff;
  border: none;
  padding: 12px 20px;
  border-radius: 5px;
  cursor: pointer;
}

footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 20px 0;
  margin-top: 40px;
}


```


## OUTPUT

<img width="1919" height="924" alt="image" src="https://github.com/user-attachments/assets/00c6ad13-6a23-4cd5-8903-dfbe619b8fc5" />



<img width="1908" height="917" alt="image" src="https://github.com/user-attachments/assets/d6956f04-8c4c-46ef-865b-e93b2c1b75a5" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
