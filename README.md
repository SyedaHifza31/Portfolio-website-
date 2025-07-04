<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Syeda Hifza | Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #fff;
            overflow-x: hidden;
        }
        header {
            background-color: #1f1f1f;
            padding: 20px;
            text-align: center;
            animation: fadeIn 2s ease;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .intro {
            padding: 40px;
            text-align: center;
            animation: slideUp 1.5s ease;
        }
        .skills {
            background-color: #1a1a1a;
            padding: 30px;
            text-align: center;
            animation: fadeIn 2s ease;
        }
        .skills img {
            width: 80px;
            margin: 15px;
            transition: transform 0.3s;
        }
        .skills img:hover {
            transform: scale(1.1);
        }
        .contact {
            background-color: #1f1f1f;
            padding: 30px;
            text-align: center;
            animation: slideUp 1.5s ease;
        }
        footer {
            text-align: center;
            padding: 10px;
            font-size: 0.9em;
            background-color: #121212;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideUp {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
    </style>
</head>
<body>
    <header>
        <h1>Syeda Hifza</h1>
        <p>Aspiring Frontend Developer</p>
    </header>

    <section class="intro">
        <h2>About Me</h2>
        <p>I am a motivated and passionate frontend developer who loves building clean, responsive websites. Currently focusing on enhancing my skills in web technologies and contributing to real-world projects.</p>
    </section>

    <section class="skills">
        <h2>My Skills</h2>
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" alt="HTML">
        <img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg" alt="CSS">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" alt="JavaScript">
    </section>

    <section class="contact">
        <h2>Contact Me</h2>
        <p>Email: hifzaali480@email.com</p>
        <p>Phone: 03111203972</p>
    </section>

    <footer>
        &copy; 2024 Syeda Hifza | Portfolio
    </footer>
</body>
</html>
# Portfolio-website-
My personal portfolio 
