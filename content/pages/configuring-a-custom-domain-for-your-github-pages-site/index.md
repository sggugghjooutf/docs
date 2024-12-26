<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Space Exploration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0d1b2a;
            color: #fff;
        }
        header {
            background-color: #1b263b;
            color: white;
            text-align: center;
            padding: 1.5rem;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #415a77;
        }
        nav a {
            color: #4CAF50;
            padding: 14px 20px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #778da9;
            color: black;
        }
        main {
            padding: 2rem;
        }
        .gallery img {
            width: 100%;
            height: auto;
            max-width: 300px;
            margin: 10px;
        }
        footer {
            background-color: #1b263b;
            color: white;
            text-align: center;
            padding: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Space Exploration</h1>
        <p>Discovering the Universe and Beyond</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#goals">Goals</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact Us</a>
    </nav>
    <main>
        <section id="home">
            <h2>Welcome to Space Exploration</h2>
            <p>Space exploration is the investigation of the universe beyond Earth's atmosphere. It inspires innovation and expands our understanding of the cosmos.</p>
        </section>
        <section id="goals">
            <h2>Goals of Space Exploration</h2>
            <ul>
                <li>Understanding the origins of the universe.</li>
                <li>Searching for extraterrestrial life.</li>
                <li>Advancing technology for space and Earth applications.</li>
                <li>Exploring new planets and resources.</li>
            </ul>
        </section>
        <section id="gallery" class="gallery">
            <h2>Gallery</h2>
            <img src="space1.jpg" alt="Space Image 1">
            <img src="space2.jpg" alt="Space Image 2">
            <img src="space3.jpg" alt="Space Image 3">
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" required><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br>
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Space Exploration. All Rights Reserved.</p>
    </footer>
</body>
</html>
