# Sample-portfolio-website-html-css
Sample Portfolio website with HTML and CSS

## HTML Code
### Create index.html file in /var/www/html directory and copy below code.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="about" class="section">
        <div class="container">
            <h1>About Me</h1>
            <p>Write a brief introduction about yourself here.</p>
        </div>
    </section>
    <section id="projects" class="section">
        <div class="container">
            <h1>Projects</h1>
            <div class="project">
                <h2>Project Title</h2>
                <p>Description of the project.</p>
                <a href="#">View Project</a>
            </div>
            <!-- Repeat the project div for each project you want to showcase -->
        </div>
    </section>
    <section id="contact" class="section">
        <div class="container">
            <h1>Contact Me</h1>
            <p>You can reach me at your@email.com</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2023 Your Name</p>
    </footer>
</body>
</html>
```

## CSS Code 

### Create style.css file in the same directory whete index.html document has been created.

```
/* Reset some default styles */
body, h1, h2, p, ul, li {
    margin: 0;
    padding: 0;
}

/* Set a background color */
body {
    background-color: #f8f9fa;
    font-family: Arial, sans-serif;
}

/* Navigation styles */
nav ul {
    list-style: none;
    display: flex;
    justify-content: space-around;
    padding: 1rem;
    background-color: #343a40;
}

nav a {
    color: #ffffff;
    text-decoration: none;
}

/* Section styles */
.section {
    padding: 4rem 0;
    text-align: center;
}

.container {
    max-width: 960px;
    margin: 0 auto;
    padding: 0 1rem;
}

/* Project styles */
.project {
    background-color: #ffffff;
    border-radius: 10px;
    padding: 1.5rem;
    box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.1);
    margin-bottom: 2rem;
}

.project h2 {
    margin-bottom: 1rem;
    color: #333333;
}

.project a {
    color: #007bff;
    text-decoration: none;
    font-weight: bold;
}

/* Footer styles */
footer {
    background-color: #343a40;
    color: #ffffff;
    text-align: center;
    padding: 1rem 0;
}
```
