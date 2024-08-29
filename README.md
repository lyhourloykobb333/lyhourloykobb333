<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }

        nav a:hover {
            background-color: #555;
        }

        .hero {
            background-image: url('your-hero-image.jpg');
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 2px 2px 4px #000;
        }

        .hero h1 {
            font-size: 3em;
        }

        .section {
            padding: 40px 20px;
            text-align: center;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            transition: transform 0.2s;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        footer {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <h1>Image Store</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#gallery">Gallery</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero">
        <h1>Discover Beautiful Images</h1>
    </section>

    <section id="gallery" class="section">
        <h2>Featured Images</h2>
        <div class="gallery">
            <img src="image1.jpg" alt="Image 1">
            <img src="image2.jpg" alt="Image 2">
            <img src="image3.jpg" alt="Image 3">
            <img src="image4.jpg" alt="Image 4">
        </div>
    </section>

    <section id="about" class="section">
        <h2>About Us</h2>
        <p>We are passionate about providing high-quality images for all your needs, from personal projects to professional work. Browse our collection and find the perfect image for you!</p>
    </section>

    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Email: support@imagestore.com | Phone: +123 456 7890</p>
    </section>

    <footer>
        <p>&copy; 2024 Image Store. All rights reserved.</p>
    </footer>
</body>

</html>
