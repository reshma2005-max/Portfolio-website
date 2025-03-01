<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<link rel="stylesheet" href="style.css">
<body>
    <!-- Navbar -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Home Section -->
    <section id="home">
        <div class="content">
            <h1>Welcome to My Portfolio</h1>
            <p>Discover my work and skills</p>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="content">
            <h2>About Me</h2>
            <p>I am a passionate developer with expertise in web technologies.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <div class="content">
            <h2>My Projects</h2>
            <div class="projects-container">
                <div class="project-card">
                    <h3>Project 1</h3>
                    <p>A brief description of project 1.</p>
                </div>
                <div class="project-card">
                    <h3>Project 2</h3>
                    <p>A brief description of project 2.</p>
                </div>
                <div class="project-card">
                    <h3>Project 3</h3>
                    <p>A brief description of project 3.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="content">
            <h2>Contact Me</h2>
            <p>Feel free to reach out for any inquiries!</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 My Portfolio</p>
    </footer>
</body>
</html>
</body>
</html># Portfolio-website

 {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

/* Smooth Scroll */
html {
    scroll-behavior: smooth;
}

/* Body */
body {
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

/* Navbar */
nav {
    background-color: #333;
    position: sticky;
    top: 0;
    z-index: 10;
    transition: background-color 0.3s ease;
}

nav ul {
    list-style: none;
    padding: 1rem;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1rem;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #ddd;
}

/* Home Section */
#home {
    height: 100vh;
    background: url('https://via.placeholder.com/1500x900') no-repeat center center/cover;
    color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    animation: fadeIn 2s ease-out;
}

#home h1 {
    font-size: 3rem;
    margin-bottom: 20px;
    opacity: 0;
    animation: fadeIn 2s forwards;
}

#home p {
    font-size: 1.5rem;
    opacity: 0;
    animation: fadeIn 2.5s forwards;
}

/* About Section */
#about {
    padding: 50px;
    background-color: #fff;
    text-align: center;
    animation: slideIn 1s ease-out;
}

#about h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

#about p {
    font-size: 1.2rem;
    color: #555;
}

/* Projects Section */
#projects {
    padding: 50px;
    background-color: #f0f0f0;
    animation: slideIn 1s ease-out;
}

#projects h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    text-align: center;
}

.projects-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.project-card {
    background-color: #fff;
    width: 30%;
    margin-bottom: 20px;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}

.project-card h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

.project-card p {
    font-size: 1rem;
}

/* Contact Section */
#contact {
    padding: 50px;
    background-color: #fff;
    text-align: center;
    animation: slideIn 1s ease-out;
}

#contact h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

#contact p {
    font-size: 1.2rem;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
    margin-top: 20px;
}

footer p {
    font-size: 1rem;
}

/* Animations */
@keyframes fadeIn {
    0% {
        opacity: 0;
    }
    100% {
        opacity: 1;
    }
}

@keyframes slideIn {
    0% {
        transform: translateY(50px);
        opacity: 0;
    }
    100% {
        transform: translateY(0);
        opacity: 1;
    }
}
