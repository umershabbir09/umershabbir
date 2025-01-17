# umershabbir

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Front Page</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f4f4f9;
        }
        header {
            background: linear-gradient(to right, #0366d6, #24292e);
            color: #fff;
            padding: 2rem 0;
            text-align: center;
            position: relative;
        }
        header h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
        }
        header p {
            font-size: 1.2rem;
        }
        header img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid #fff;
            position: absolute;
            top: 100%;
            left: 50%;
            transform: translate(-50%, -50%);
        }
        nav {
            background: #24292e;
            color: white;
            display: flex;
            justify-content: center;
            padding: 1rem 0;
            margin-top: 75px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1.1rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1100px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        section {
            margin-bottom: 2rem;
        }
        section h2 {
            color: #0366d6;
            margin-bottom: 1rem;
            font-size: 2rem;
        }
        .skills, .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .skills div, .projects div {
            flex: 1 1 calc(33.333% - 1rem);
            background: #fff;
            padding: 1rem;
            border-radius: 5px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .projects div img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 5px;
            margin-bottom: 0.5rem;
        }
        footer {
            background: #24292e;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
        footer p {
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My GitHub Portfolio</h1>
        <p>Frontend Developer | WordPress Developer | Lifelong Learner</p>
        <img src="https://via.placeholder.com/150" alt="Profile Picture">
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Hi, I'm Umer Shabbir, a passionate frontend developer with expertise in building responsive websites and creating seamless user experiences. I enjoy learning new technologies and bringing ideas to life through code.</p>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <div class="skills">
                <div>HTML</div>
                <div>CSS</div>
                <div>JavaScript</div>
                <div>WordPress</div>
                <div>Bootstrap</div>
                <div>Git/GitHub</div>
            </div>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="projects">
                <div>
                    <img src="https://via.placeholder.com/300x150" alt="Weather App">
                    <h3>Weather App</h3>
                    <p>A real-time weather checker application.</p>
                </div>
                <div>
                    <img src="https://via.placeholder.com/300x150" alt="Tic-Tac-Toe">
                    <h3>Tic-Tac-Toe</h3>
                    <p>A classic game built using JavaScript.</p>
                </div>
                <div>
                    <img src="https://via.placeholder.com/300x150" alt="Quiz Application">
                    <h3>Quiz Application</h3>
                    <p>An interactive quiz app with a timer and scoring system.</p>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Me</h2>
            <p>Email: <a href="mailto:umershabbir388@gmail.com">umershabbir388@gmail.com</a></p>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Umer Shabbir. All Rights Reserved.</p>
    </footer>
</body>
</html>
