<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .container {
            width: 80%;
            margin: 0 auto;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        section {
            padding: 50px 0;
        }

        section h2 {
            text-align: center;
        }

        .project {
            border-bottom: 1px solid #ccc;
            padding-bottom: 20px;
            margin-bottom: 20px;
        }

        .project h3 {
            margin-top: 0;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: absolute;
            width: 100%;
            bottom: 0;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>My Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Welcome to my portfolio! I am a passionate web developer with experience in HTML, CSS, and JavaScript.</p>
            <p>I enjoy creating responsive and user-friendly web applications that solve real-world problems.</p>
            <p>Feel free to explore my projects below and don't hesitate to get in touch!</p>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project">
                <h3>Project 1: Sample Project</h3>
                <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non risus.</p>
                <a href="#">View Project</a>
            </div>
            <div class="project">
                <h3>Project 2: Another Sample Project</h3>
                <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non risus.</p>
                <a href="#">View Project</a>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Feel free to reach out to me via email or connect with me on social media!</p>
            <ul>
                <li>Email: example@example.com</li>
                <li>Twitter: <a href="#">@example_twitter</a></li>
                <li>LinkedIn: <a href="#">example_linkedin</a></li>
            </ul>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 My Portfolio. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
