<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            background-color: #444;
            overflow: hidden;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            float: left;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .container {
            display: flex;
            flex-wrap: wrap;
        }
        .image-container {
            margin: 10px;
        }
        .image-container img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
        }
        form button:hover {
            background-color: #444;
        }
        .project-list {
            display: flex;
            flex-direction: column;
        }
        .project-item {
            background-color: #e2e2e2;
            margin: 10px;
            padding: 15px;
            border-radius: 5px;
        }
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
        <p>Welcome to my website! Here you will find information about me, my work, and my upcoming projects.</p>
        <div class="container">
            <div class="image-container">
                <img src="your-image.jpg" alt="Your Image">
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery">
        <h2>Gallery</h2>
        <p>Here are some images I would like to share:</p>
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
        <p>If you have any questions or just want to chat, feel free to send me a message below!</p>
        <form action="https://formspree.io/f/your-endpoint-id" method="POST">
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
