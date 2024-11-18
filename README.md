# Mohammad-Abbas
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohammad Abbas - Personal Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Mohammad Abbas</h1>
            <p>Welcome to my personal website!</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Hello! My name is Mohammad Abbas. I am passionate about technology, web development, and creating meaningful digital experiences. This website showcases my work and interests.</p>
            <img src="profile.jpg" alt="Mohammad Abbas" class="profile-image">
        </div>
    </section>

    <section id="portfolio">
        <div class="container">
            <h2>Portfolio</h2>
            <div class="gallery">
                <img src="project1.jpg" alt="Project 1">
                <img src="project2.jpg" alt="Project 2">
                <img src="project3.jpg" alt="Project 3">
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>If you'd like to get in touch, feel free to send me an email at <a href="mailto:example@example.com">example@example.com</a>.</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Mohammad Abbas. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    background: #007BFF;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

header p {
    font-size: 1.2em;
}

nav {
    background: #333;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0;
}

nav ul li a {
    color: white;
    text-decoration: none;
    padding: 15px 20px;
    display: block;
}

nav ul li a:hover {
    background: #575757;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

h2 {
    color: #007BFF;
}

.profile-image {
    max-width: 200px;
    border-radius: 50%;
    margin-top: 20px;
}

.gallery {
    display: flex;
    gap: 20px;
}

.gallery img {
    max-width: 100%;
    height: auto;
    border: 2px solid #ddd;
    border-radius: 5px;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}
