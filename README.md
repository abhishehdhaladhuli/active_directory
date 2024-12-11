<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Global Styles */
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #333;
        }

        /* Header */
        header {
            background: linear-gradient(to right, #6a11cb, #2575fc);
            color: white;
            padding: 2rem 1rem;
            text-align: center;
        }

        header h1 {
            margin: 0.5rem 0;
            font-size: 2.5rem;
        }

        header p {
            font-size: 1.2rem;
        }

        /* Navigation */
        nav {
            text-align: center;
            margin: 1rem 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #ddd;
        }

        /* Section Styling */
        section {
            padding: 2rem 1rem;
            text-align: center;
        }

        section h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        section p {
            max-width: 600px;
            margin: 0 auto;
            font-size: 1rem;
        }

        /* Projects Grid */
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 2rem;
        }

        .project {
            background: #f4f4f4;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s;
        }

        .project img {
            width: 100%;
            display: block;
        }

        .project h3 {
            padding: 1rem;
            margin: 0;
        }

        .project:hover {
            transform: translateY(-10px);
        }

        /* Footer */
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            font-size: 0.9rem;
        }

        footer a {
            color: #6a11cb;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Web Developer | Open Source Contributor | Tech Enthusiast</p>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hi! I'm a passionate web developer who loves building modern and user-friendly applications. With a strong background in coding and design, I aim to create projects that make a difference.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <div class="project">
                <img src="https://via.placeholder.com/300x200" alt="Project 1">
                <h3>Project One</h3>
            </div>
            <div class="project">
                <img src="https://via.placeholder.com/300x200" alt="Project 2">
                <h3>Project Two</h3>
            </div>
            <div class="project">
                <img src="https://via.placeholder.com/300x200" alt="Project 3">
                <h3>Project Three</h3>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Feel free to reach out to me via email at <a href="mailto:yourname@example.com">yourname@example.com</a> or connect with me on <a href="https://github.com/yourusername" target="_blank">GitHub</a>.</p>
    </section>

    <footer>
        <p>&copy; 2024 Your Name. Built with ❤️ for the web. <a href="https://github.com/yourusername">View on GitHub</a></p>
    </footer>
</body>
</html>
