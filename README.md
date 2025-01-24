<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arya Lakshmi - Portfolio</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        body {
            line-height: 1.6;
            background: #f9f9f9;
            color: #333;
        }
        header {
            background: linear-gradient(135deg, #ff7eb3, #ff758c);
            color: white;
            padding: 2rem 1rem;
            text-align: center;
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        header p {
            font-size: 1.2rem;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #333;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 0.8rem 1.5rem;
            transition: background 0.3s;
        }
        nav a:hover {
            background: #ff7eb3;
        }
        section {
            padding: 2rem 1rem;
            max-width: 1100px;
            margin: auto;
        }
        .about,
        .skills,
        .hobbies,
        .contact {
            margin-bottom: 2rem;
            border-bottom: 1px solid #ddd;
            padding-bottom: 2rem;
        }
        h2 {
            color: #ff758c;
            font-size: 1.8rem;
            margin-bottom: 1rem;
        }
        p {
            font-size: 1rem;
            margin-bottom: 0.8rem;
        }
        .contact a {
            display: block;
            margin-bottom: 1rem;
            color: #ff758c;
            text-decoration: none;
            font-weight: bold;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background: #333;
            color: white;
            font-size: 0.9rem;
        }
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
            nav {
                flex-wrap: wrap;
            }
            nav a {
                flex: 1 1 auto;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Arya Lakshmi</h1>
        <p>Student | Computer Science Engineer | Tech Enthusiast</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#hobbies">Hobbies</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Me</h2>
        <p>Hi! I'm Arya Lakshmi, a Computer Science Engineering student at SCMS School of Engineering and Technology. I live in Kodungallur, Kerala, India, and I'm passionate about exploring new technology innovations.</p>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <h2>Skills</h2>
        <p>I have excellent communication skills, teamwork abilities, and leadership qualities. I'm constantly working to improve my technical expertise and expand my knowledge in various domains.</p>
    </section>

    <!-- Hobbies Section -->
    <section id="hobbies" class="hobbies">
        <h2>Hobbies</h2>
        <p>In my free time, I enjoy watching movies, listening to music, singing, traveling, and exploring delicious food.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <p>Feel free to reach out to me through the following channels:</p>
        <a href="https://www.linkedin.com/in/arya-lakshmi-m-p-5b7148292?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">LinkedIn</a>
        <a href="mailto:mparya022@gmail.com">mparya022@gmail.com</a>
    </section>

    <!-- Footer -->
    <footer>
        &copy; 2025 Arya Lakshmi | All Rights Reserved
    </footer>
</body>
</html>