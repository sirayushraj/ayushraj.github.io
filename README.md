<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A personal website to showcase images, projects, and more.">
    <meta name="keywords" content="personal website, gallery, projects, contact">
    <meta name="author" content="Your Name">
    <title>Your Professional Website</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Insert the updated CSS here */
    </style>
</head>
<body>
    <header>
        <h1>Your Website Name</h1>
        <p>Welcome to my personal website!</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#gallery">Gallery</a>
        <a href="#projects">Future Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>Hey there! I created this website to showcase my images and projects. I'm open to suggestions on how to improve this space!</p>
        <div class="container">
            <div class="image-container">
                <img src="your-image.jpg" alt="Your Image">
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery">
        <h2>Gallery</h2>
        <p>Check out some of my favorite images:</p>
        <div class="container">
            <div class="image-container">
                <img src="image1.jpg" alt="Image 1">
            </div>
            <div class="image-container">
                <img src="image2.jpg" alt="Image 2">
            </div>
            <div class="image-container">
                <img src="image3.jpg" alt="Image 3">
            </div>
        </div>
    </section>

    <!-- Future Projects Section -->
    <section id="projects">
        <h2>Future Projects</h2>
        <div class="project-list">
            <div class="project-item">
                <h3>Project 1</h3>
                <p>Description of the first project.</p>
            </div>
            <div class="project-item">
                <h3>Project 2</h3>
                <p>Description of the second project.</p>
            </div>
            <div class="project-item">
                <h3>Project 3</h3>
                <p>Description of the third project.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>If you have any questions or just want to chat, feel free to send me a message!</p>
        <form action="https://formspree.io/f/xzzzlkll" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Your Website. All rights reserved.</p>
    </footer>
</body>
</html>
