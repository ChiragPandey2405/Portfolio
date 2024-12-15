<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: #121212;
            color: #ffffff;
        }

        header {
            background-color: #1f1f1f;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
            color: #00adb5;
        }

        nav {
            margin-top: 15px;
        }

        nav a {
            margin: 0 15px;
            color: #ffffff;
            text-decoration: none;
            font-size: 1.1rem;
        }

        nav a:hover {
            color: #00adb5;
        }
.amazon{
    background-size: cover;
    height: 200px;
    width: 300px;
}

        .container {
            padding: 20px;
        }

        .section {
            margin: 30px 0;
        }

        .section h2 {
            color: #00adb5;
            border-bottom: 2px solid #00adb5;
            display: inline-block;
            margin-bottom: 10px;
        }

        .section p {
            line-height: 1.6;
        }

        .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .project {
            background-color: #1f1f1f;
            border: 1px solid #333;
            border-radius: 8px;
            padding: 15px;
            width: calc(33% - 20px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .project:hover {
            border-color: #00adb5;
        }

        .project h3 {
            margin-top: 0;
            color: #ffffff;
        }

        footer {
            text-align: center;
            padding: 15px;
            background-color: #1f1f1f;
            color: #888;
        }

        footer a {
            color: #00adb5;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        @media (max-width: 768px) {
            .project {
                width: calc(50% - 20px);
            }
        }

        @media (max-width: 480px) {
            .project {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Chirag Pandey</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="container">
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>
                Hello<br>I'm Chirag Pandey passionate about web development and designing scalable solution to problems .
            <h2>Skills</h2>
            <p>1. Web Development<br>2.C++</p><hr>
            </p>
        </section>

        <section id="projects" class="section">
            <h2>Projects</h2>
            <div class="projects">
                <div class="project">
                    <h3>Amazone Clone </h3>
                    <div class="amazon" style="background-image:url('assignment.PNG') ;">
                    
                    </div>
                </div>
                
            </div>
        </section>

        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>
                Feel free to reach out to me at <a href="chirag.pandey2415@gmail.com">chirag.pandey2415@gmail.com</a> or connect with me on 
                <a href="https://www.linkedin.com/in/chirag-pandey-65175b341" target="_blank">LinkedIn</a>.
            </p>
        </section>
    </div>

    <footer>
        &copy; 2024 Your Chirag. Built with <a href="https://developer.mozilla.org/">HTML & CSS</a>.
    </footer>
</body>
</html>
