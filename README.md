#CSS
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color: #333;
}
header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 1rem;
}
header h1 {
    margin: 0;
    font-size: 2.5rem;
}
section {
    padding: 2rem;
    margin: 2rem 0;
}
section h2 {
    font-size: 2rem;
    border-bottom: 2px solid #4CAF50;
    padding-bottom: 0.5rem;
}
#about img {
    max-width: 150px;
    border-radius: 50%;
    display: block;
    margin: 1rem auto;
}

#skills ul {
    list-style-type: none;
    padding: 0;
}
#skills li {
    background-color: #f4f4f4;
    margin: 0.5rem 0;
    padding: 0.5rem;
    border-left: 5px solid #4CAF50;
}
#projects .project {
    margin-bottom: 2rem;
}
#projects img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 0.5rem 0;
}
#resume a {
    color: #4CAF50;
    text-decoration: none;
    font-weight: bold;
}
#contact p {
    margin: 0.5rem 0;
}
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
}
footer p {
    margin: 0;
}

#HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="CNstyle1.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Your Name</h1>
        <p>Your tagline or a brief introduction</p>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <img src="your-image.jpg" alt="Your Name">
        <p>A short bio highlighting your skills and experience.</p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Skill 1</li>
            <li>Skill 2</li>
            <li>Skill 3</li>
            <!-- Add more skills as needed -->
        </ul>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project Title 1</h3>
            <img src="project-image1.jpg" alt="Project 1">
            <p>Project description goes here.</p>
        </div>
        <div class="project">
            <h3>Project Title 2</h3>
            <img src="project-image2.jpg" alt="Project 2">
            <p>Project description goes here.</p>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <!-- Resume Section -->
    <section id="resume">
        <h2>Resume</h2>
        <a href="your-resume.pdf" download>Download My Resume (PDF)</a>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
        <p>Phone: Your Phone Number</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
        <!-- Add any additional links or information here -->
    </footer>
</body>
</html>

