# ABOUT ME
<WELCOME>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ujjwala Sanaye | Portfolio</title>

    <!-- SEO -->
    <meta name="description" content="Ujjwala Sanaye – Portfolio of a BMS student and aspiring web developer">
    <meta name="author" content="Ujjwala Sanaye">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

    <!-- CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- NAVBAR -->
    <header>
        <nav class="navbar">
            <h2 class="logo">Ujjwala</h2>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- HERO -->
    <section id="home" class="hero">
        <h1>Hi, I'm <span>Ujjwala Sanaye</span></h1>
        <p>BMS Student | Aspiring Web Developer</p>
        <a href="#contact" class="btn">Contact Me</a>
    </section>

    <!-- ABOUT -->
    <section id="about" class="section">
        <h2>About Me</h2>
        <p>
            I am a BMS student at Aditya Institute of Management Studies and Research.
            I am passionate about web development and enjoy building clean,
            responsive websites using HTML and CSS.
        </p>
    </section>

    <!-- SKILLS -->
    <section id="skills" class="section gray">
        <h2>Skills</h2>
        <div class="skills-container">
            <div class="skill"><i class="fa-brands fa-html5"></i> HTML</div>
            <div class="skill"><i class="fa-brands fa-css3-alt"></i> CSS</div>
            <div class="skill"><i class="fa-solid fa-file-word"></i> MS Office</div>
            <div class="skill"><i class="fa-solid fa-comments"></i> Communication</div>
            <div class="skill"><i class="fa-solid fa-computer"></i> Computer Basics</div>
        </div>
    </section>

    <!-- PROJECTS -->
    <section id="projects" class="section">
        <h2>Projects</h2>
        <div class="projects-container">
            <div class="project-card">
                <h3>Portfolio Website</h3>
                <p>Personal portfolio built using HTML & CSS.</p>
                <a href="#" target="_blank">Live Demo</a>
            </div>
        </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="section gray">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:sanayeujjwala@gmail.com">sanayeujjwala@gmail.com</a></p>

        <div class="socials">
            <a href="#"><i class="fa-brands fa-github"></i></a>
            <a href="#"><i class="fa-brands fa-linkedin"></i></a>
        </div>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>© 2026 Ujjwala Sanaye | All Rights Reserved</p>
    </footer>

</body>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

html {
    scroll-behavior: smooth;
}

body {
    color: #333;
}

/* NAVBAR */
header {
    background: #2c3e50;
    padding: 15px 50px;
    position: sticky;
    top: 0;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    color: #fff;
}

.nav-links {
    list-style: none;
    display: flex;
}

.nav-links li {
    margin-left: 20px;
}

.nav-links a {
    color: #fff;
    text-decoration: none;
    font-weight: 500;
}

/* HERO */
.hero {
    height: 90vh;
    background: linear-gradient(to right, #1abc9c, #16a085);
    color: #fff;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.hero h1 span {
    color: #2c3e50;
}

.btn {
    margin-top: 20px;
    padding: 10px 25px;
    background: #2c3e50;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

/* SECTIONS */
.section {
    padding: 60px 80px;
    text-align: center;
}

.section h2 {
    margin-bottom: 20px;
}

.gray {
    background: #f4f4f4;
}

/* SKILLS */
.skills-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
}

.skill {
    background: #fff;
    padding: 15px 25px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* PROJECTS */
.projects-container {
    display: flex;
    justify-content: center;
}

.project-card {
    background: #fff;
    padding: 25px;
    border-radius: 10px;
    width: 300px;
    box-shadow: 0 0 15px rgba(0,0,0,0.1);
}

.project-card a {
    display: inline-block;
    margin-top: 10px;
    color: #1abc9c;
    text-decoration: none;
}

/* CONTACT */
.socials a {
    font-size: 24px;
    margin: 10px;
    color: #2c3e50;
}

/* FOOTER */
footer {
    background: #2c3e50;
    color: #fff;
    text-align: center;
    padding: 15px;
}

</html>

