<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Profile</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        body {
            background: #1a1a2e;
            color: #e6e6e6;
            line-height: 1.6;
            font-size: 16px;
            padding: 20px;
        }

        .container {
            max-width: 1000px;
            margin: auto;
            overflow: hidden;
            padding: 0 20px;
        }

        header {
            background: #16213e;
            color: #fff;
            padding: 10px 0;
            text-align: center;
            border-bottom: 2px solid #0f3460;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            background: #0f3460;
            padding: 10px 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #ff4c29;
        }

        .intro {
            text-align: center;
            margin-top: 20px;
        }

        .intro h1 {
            font-size: 2.5rem;
            color: #e94560;
        }

        .intro p {
            font-size: 1.2rem;
            margin-top: 10px;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 40px;
        }

        .project {
            background: #0f3460;
            border-radius: 5px;
            padding: 20px;
            text-align: center;
            transition: transform 0.3s;
        }

        .project:hover {
            transform: scale(1.05);
        }

        .project h3 {
            margin-bottom: 10px;
            color: #ff4c29;
        }

        .project p {
            font-size: 1rem;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px 0;
            background: #16213e;
            color: #fff;
        }

        footer p {
            margin-bottom: 5px;
        }

        footer a {
            color: #ff4c29;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>My GitHub Profile</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <div class="container">
        <section class="intro" id="about">
            <h1>Welcome!</h1>
            <p>I'm a passionate developer who is constantly exploring new technologies and building cool projects.</p>
        </section>

        <section class="projects" id="projects">
            <div class="project">
                <h3>Project One</h3>
                <p>A brief description of this amazing project.</p>
            </div>
            <div class="project">
                <h3>Project Two</h3>
                <p>A brief description of another fantastic project.</p>
            </div>
            <div class="project">
                <h3>Project Three</h3>
                <p>Details about a third awesome project.</p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 My GitHub Profile</p>
        <p>Connect with me on <a href="https://github.com/yourusername" target="_blank">GitHub</a></p>
    </footer>
</body>
</html>
