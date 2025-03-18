<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio ★</title>
    <link rel="icon" href="favicon.ico" type="image/x-icon" />
    <link rel="stylesheet" href="style.css" />

    <style>
        
        body {
            background: linear-gradient(to right, #4facfe, #00f2fe);
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            font-family: Arial, sans-serif;
            color: #ffffff;
            text-align: center;
            margin: 0;
            padding: 0;
        }

       
        .container {
            width: 85%;
            margin: auto;
            padding: 20px;
        }

        
        .content {
            background: rgba(255, 255, 255, 0.2);
            backdrop-filter: blur(10px);
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            margin-bottom: 20px;
        }

       
        .header, .footer {
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        
        .nav-links a {
            color: #ffffff;
            text-decoration: none;
            font-weight: bold;
            margin: 0 20px;
            transition: color 0.3s ease-in-out;
        }

        .nav-links a:hover {
            color: #ffeb3b;
        }

       
        .responsive-iframe {
            width: 100%;
            height: 315px;
            border-radius: 10px;
        }

        
        .image-map img {
            max-width: 100%;
            border-radius: 10px;
        }

        
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0px); }
        }

        .floating-circle {
            position: absolute;
            width: 120px;
            height: 120px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            top: 10%;
            left: 5%;
            animation: float 6s infinite ease-in-out;
        }

    </style>
</head>
<body>

    <div class="container">
        
        <div class="header">
            <h1>Welcome to Our Portfolio</h1>
        </div>

        <div class="nav-links">
            <a href="#about">About Us</a> | 
            <a href="#projects">Projects</a> | 
            <a href="#contact">Contact</a>
        </div>

        <div id="about" class="content">
            <h2>About</h2>
            <p>Hello! We are john Henry Cariat &amp; We're passionate about web development.</p>
        </div>

        <div id="projects" class="content">
            <h2>Our Projects</h2>
            <ul>
                <li><a href="project1.html">Project 1</a></li>
                <li><a href="project2.html">Project 2</a></li>
            </ul>

            <h3>Our Favorite Tutorial</h3>
            <iframe class="responsive-iframe" src="https://www.youtube.com/embed/HD13eq_Pmp8" allowfullscreen></iframe>

            <h3>Our University Location</h3>
            <iframe class="responsive-iframe" src="https://www.google.com/maps/embed/v1/place?q=Cebu+Eastern+College&key=AIzaSyBFw0Qbyq9zTFTd-tUY6dZWTgaQzuU17R8" allowfullscreen></iframe>

            <h3>Clickable Image Map</h3> <p> <span> &#9757;</span>
            <div class="image-map">
                <img src="world-map.jpg" usemap="#worldmap" alt="World Map" />
                <map name="worldmap">
                    <area shape="rect" coords="34,44,270,350" href="https://www.google.com" alt="Google">
                    <area shape="rect" coords="290,172,333,250" href="https://www.youtube.com" alt="YouTube">
                </map>
            </div>
        </div>

        <div id="contact" class="content">
            <h2>Contact Me</h2>
            <p>Email:johnhenry4@gmail.com</p>
        </div>

        <div class="footer">
            <p>Our favorite Emojis: <span class="emoji-list">&#128077; &#128516; &#129304; &#128540;</span></p>
        </div>
    </div>

    
    <div class="floating-circle"></div>

</body>
</html>