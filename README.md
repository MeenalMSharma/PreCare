# 🎈 Blank app template

A simple Streamlit app template for you to modify!

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://blank-app-template.streamlit.app/)

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Disease Detection | PreCare.com</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" media="screen and (max-width: 1170px)" href="css/phone.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Labrada&family=Phudu:wght@500&family=Rubik&display=swap" rel="stylesheet">
</head>
<body>
    <nav id="navbar">
      <ul>
        <li class="item"><a href="#home">Home</a></li>
        <li class="item"><a href="#services">Services</a></li>
        <li class="item"><a href="#contact">Contact Us</a></li>
      </ul>
    </nav>
    <section id="home">
        <h1 class="h-primary">Welcome To PreCare</h1>
        <p>Our website is based on Deep Learning models for disease detection.</p>
        <p>This can help reducing risk.</p>
        <button class="btn">Check Now</button>
    </section>
    <hr>
    <section class="services-container">
        <h1 class="h-primary center">Our Services</h1>
        <div id="services">
            <div class="box">
                <img width="500px" height="500px" src="image (3).png" alt="">
                <h2 class="h-secondary center">Brain Tumor</h2>
                <p class="center">Upload CT scan, MRI or X-rays.</p>
            </div>
            <div class="box">
                <img width="500px" height="500px"  src="image (4).png" alt="">
                <h2 class="h-secondary center">Pneumonia</h2>
                <p class="center">Upload CT scan, MRI or X-rays.</p>
            </div>
            <div class="box">
                <img width="500px" height="500px"  src="image (5).png" alt="">
                <h2 class="h-secondary center">COVID-19</h2>
                <p class="center">Upload CT scan, MRI or X-rays.</p>
            </div>
        </div>
    </section>
    <hr>
    <section id="contact">
        <h1 class="h-primary center">Contact us to get results on e-mail</h1>
        <div id="contact-box">
            <form action="post">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" name="name" id="name" placeholder="Enter your name">
                </div>
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" name="name" id="email" placeholder="Enter your email">
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number:</label>
                    <input type="phone" name="name" id="phone" placeholder="Enter your phone">
                </div>
                <div class="form-group">
                    <label for="message">Message:</label>
                    <textarea name="message" id="message" cols="30" rows="10"></textarea>
                </div>
                <div>
                    <input type="radio" name="gender" id="Male" value="Male">
                    <label for="Male">Male</label>
                    <input type="radio" name="gender" id="Female" value="Female">
                    <label for="Female">Female</label>
                </div>
            </form>
        </div>
    </section>
    <footer>
        <div class="center">
            Copyright &copy; www.PreCare.com All Rights Reserved.
        </div>
    </footer>
    <script src="script.js"></script>
</body>
</html>
