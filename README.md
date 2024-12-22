<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zenless Zone Zero</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1a1a1a;
            color: #f5f5f5;
        }
        header {
            background: linear-gradient(135deg, #FF6F61, #8E44AD);
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
            color: #fff;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            color: #f5f5f5;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background: url('zenless-zone-zero-hero.jpg') no-repeat center/cover;
        }
        .hero h2 {
            color: #fff;
            font-size: 2.5em;
        }
        .hero p {
            font-size: 1.5em;
            color: #ddd;
        }
        .btn {
            display: inline-block;
            margin: 15px;
            padding: 15px 30px;
            background: #FF6F61;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.2em;
        }
        .btn:hover {
            background: #E64A19;
        }
        section {
            padding: 40px 20px;
        }
        section h2 {
            text-align: center;
            font-size: 2em;
            margin-bottom: 20px;
        }
        .screenshots {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .screenshots img {
            margin: 10px;
            border: 2px solid #fff;
            border-radius: 10px;
            max-width: 30%;
        }
        .trailer {
            text-align: center;
        }
        .trailer iframe {
            width: 80%;
            height: 400px;
            border: none;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: #aaa;
        }
        footer a {
            color: #FF6F61;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Zenless Zone Zero</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#screenshots">Screenshots</a>
            <a href="#trailer">Trailer</a>
            <a href="#download">Download</a>
        </nav>
    </header>

    <div class="hero">
        <h2>Enter the Thrilling Urban Adventure</h2>
        <p>Explore the chaos, uncover the truth, and fight for survival in a world unlike any other.</p>
        <a href="#download" class="btn">Download Now</a>
    </div>

    <section id="about">
        <h2>About Zenless Zone Zero</h2>
        <p>Zenless Zone Zero is a dynamic action RPG set in a post-apocalyptic urban fantasy world. With stunning visuals, fast-paced combat, and an engaging story, players will dive into the heart of a mysterious city filled with secrets, challenges, and unforgettable characters.</p>
    </section>

    <section id="screenshots">
        <h2>Screenshots</h2>
        <div class="screenshots">
            <img src="screenshot1.jpg" alt="Screenshot 1">
            <img src="screenshot2.jpg" alt="Screenshot 2">
            <img src="screenshot3.jpg" alt="Screenshot 3">
        </div>
    </section>

    <section id="trailer">
        <h2>Watch the Trailer</h2>
        <div class="trailer">
            <iframe src="https://www.youtube.com/embed/example" allowfullscreen></iframe>
        </div>
    </section>

    <section id="download">
        <h2>Download Zenless Zone Zero</h2>
        <p>Get ready to jump into the action! Click below to download the game for your platform.</p>
        <a href="#" class="btn">Download for PC</a>
        <a href="#" class="btn">Download for Mobile</a>
    </section>

    <footer>
        <p>&copy; 2024 Zenless Zone Zero. All rights reserved. <a href="#">Privacy Policy</a></p>
    </footer>
</body>
</html>
