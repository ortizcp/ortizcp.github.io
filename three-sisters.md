layout: page
title: "three-sisters"
permalink: /about

<!DOCTYPE html>
<html lang="eng">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Three Sisters</title>
    <link href="resources/css/threesisters.css" type="text/css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="banner">
            <nav>
                <ul>
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Portfolio</a></li>
                    <li><a href="#">Meet The Team</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </nav>
            <div class="header">
                <h1>Three Sisters Virtual Home Decor</h1>
            </div>
        </div>
    </header>
    <!--- Main Content -->
    <div class="main-content">
        <p><strong>Three Sisters Virtual Home Decor</strong> transforms your living space through the power of digital design. Using cutting-edge virtual photography and graphic design, we capture your home’s essence and reimagine it with fresh visual styles, curated color palettes, and personalized mood boards. Whether you're looking for a modern refresh, a cozy retreat, or a bold transformation, our virtual redesigns help you visualize your dream home before making any changes.</p>
        <p>Our mission is to make home styling effortless, inspiring, and accessible. With a seamless online experience, we eliminate the guesswork from interior design, allowing you to experiment with different aesthetics before committing to a new look. At <strong>Three Sisters Virtual Home Decor</strong>, we believe every home should reflect its owner’s personality and style—our innovative approach ensures that your space not only looks beautiful but feels uniquely yours.</p>
    </div>
    <div class="services">
        <h2>Our Services</h2>
    <div class="services-container">
        <div class="service-item">
            <img class="photo-img" src="resources/photograph.jpeg"/>
            <h4>Professional Photographs</h4>
        </div>
        <div class="service-item">
            <img class="mood-img" src="resources/moodboard.jpg"/>
            <h4>Mood Boards</h4>
        </div>
        <div class="service-item">
            <img class="color-img" src="resources/colorpalette.jpg"/>
            <h4>Color Palettes</h4>
        </div>
        <div class="service-item">
            <img class="mock-img" src="resources/beforeafter.jpeg"/>
            <h4>Before and After Mock-ups</h4>
        </div>
    </div>
    </div>
    <div class="team">
        <h2>Meet the Design Team</h2>
    <div class="about-container">
        <div class="about-item">
            <img class="me-img" src="resources/me.jpg"/>
            <h3>Courtney Ortiz</h3>
            <h4>Designer</h4>
            <p>With a keen eye for aesthetics and a passion for transforming spaces through digital design, Courtney specializes in color theory, interior styling, and graphic visualization. She creates stunning virtual redesigns that inspire clients to reimagine their homes with confidence.</p>
        </div>
        <div class="about-item">
            <img class="kels-img" src="resources/kels.jpeg"/>
            <h3>Kelsey Harrell</h3>
            <h4>Photographer</h4>
            <p>Kelsey captures high-quality images of living spaces, providing the perfect foundation for virtual home redesigns. With an eye for detail and a talent for lighting and composition, she brings each space to life, ensuring a seamless transformation from photo to design.</p>
        </div>
        <div class="about-item">
            <img class="tab-img" src="resources/tab.jpeg"/>
            <h3>Tabitha Taylert</h3>
            <h4>Graphic Designer</h4>
            <p>Tabitha specializes in creating visually striking designs that bring virtual home transformations to life. With a deep understanding of color, texture, and composition, she crafts stunning digital visuals that help clients envision their ideal living spaces.</p>
        </div>
    </div>
    </div>
    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <span class="copyright">© 2025  Three Sisters, All Rights Reserved</span>
            <span class="location">Richmond, VA</span>
          </div>
    </footer>
</body>
</html>

html {
    font-family: Raleway;
    font-size: 16px;
    color: rgb(82, 81, 81);
}

nav {
    position: absolute;
    top: 20px;
    right: 20px;
}

nav ul {
    display: flex;
    gap: 20px;
    list-style: none; 
}

nav ul li {
    display: inline-block; 
    margin-right: 20px; 
    color: #F1F0E8;
}

nav ul li a {
    text-decoration: none; 
    color: #F1F0E8; 
}

.banner {
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    align-items: center;
    height: 400px;
    position: relative;
    text-align: center;
    background-color: #497D74;
}

.header {
    width: 100%;
    text-align: center;
    padding-bottom: 20px;
}

h1 {
    font-size: 3rem;
    color: #F1F0E8; 
    text-transform: uppercase;
}

h2 {
    font-size: 2rem;
    
}

.main-content {
    display: flex;
    text-align: center;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin-left: 250px;
    margin-right: 250px;
    padding: 20px;
}

.services {
    text-align: center;
}

.services-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 20px;
    padding: 30px;
    font-size: 2em;
    
    
}

.service-item {
    flex: 1; 
    min-width: 200px;
    height: 500px; 
    text-align: center;
    background-color: #F1F0E8;
    padding: 30px;
    border-radius: 10px;
    

}

.service-item img {
    width: 100%;
    max-width: 350px;
    height: 350px;
    border-radius: 10px;
    object-fit: cover;
}

.team {
    text-align: center;
    padding: 10px;
}

.about-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 30px;
    padding: 20px;
}

.about-item {
    flex: 1; 
    min-width: 200px; 
    text-align: center;
    padding: 0px;
    height: 300px;
    text-align: left;
    float: right;  
}

.about-item img {
    width: 150px; 
    height: 150px;
    object-fit: cover;
    margin-right: 10px;
    border-radius: 50%;
    float: left;
    margin-bottom: 60px;
    margin-top: 20px;
}

.about-item h3 {
    margin-bottom: 2px;
    margin-top: 30px;
}

.about-item h4 {
    margin-top: 0;
    line-height: 1.5;
}

.footer-content {
    display: flex;
    background-color: #497D74;
    color: #F1F0E8; 
    padding: 30px;
    justify-content: space-between;
}

@media screen and (max-width: 1024px) {
    /* Center and stack items in the About section */
    .about-container {
        flex-direction: column;
        align-items: center;
        gap: 20px;
    }

    .about-item {
        max-width: 80%; /* Allow some space on the sides */
        text-align: center;
    }

    .about-item h3, 
    .about-item h4 {
        text-align: center;
        margin: 5px 0;
    }

    .about-item p {
        font-size: 1rem;
        text-align: center;
        min-height: auto;
        line-height: 1.5;
    }

    /* Adjust the services container layout */
    .services-container {
        flex-direction: column;
        align-items: center;
    }

    .service-item {
        width: 80%;
        height: auto;
        padding: 20px;
    }

    .service-item img {
        width: 100%;
        height: auto;
        max-width: 300px;
        object-fit: cover;
    }

    /* Adjust navigation */
    nav {
        position: static;
        text-align: center;
        margin-top: 20px;
    }

    nav ul {
        flex-direction: column;
        gap: 10px;
    }

    /* Adjust the banner */
    .banner {
        height: auto;
        padding: 40px 20px;
    }

    .header {
        padding-bottom: 10px;
    }

    h1 {
        font-size: 2.5rem;
    }

    /* Footer adjustments */
    .footer-content {
        flex-direction: column;
        text-align: center;
        padding: 20px;
    }
}

@media screen and (max-width: 767px) {
    nav {
        position: static;
        text-align: center;
        padding: 10px 0;
    }

    nav ul {
        flex-direction: column;
        padding: 0;
    }

    nav ul li {
        margin: 5px 0;
    }

    .banner {
        height: 300px;
        padding: 20px;
    }

    .header h1 {
        font-size: 2rem;
    }

    .main-content {
        margin-left: 20px;
        margin-right: 20px;
    }

    .services-container, .about-container {
        flex-direction: column;
        align-items: center;
    }

    .service-item, .about-item {
        width: 90%;
    }

    .about-item img {
        float: none;
        margin: 10px auto;
        display: block;
    }

    .footer-content {
        flex-direction: column;
        text-align: center;
    }
}
