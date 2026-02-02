# Ex01 Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>

    <!-- STEP 2: Link CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- STEP 3: Navigation Bar -->
    <header>
        <nav class="navbar">
            <h1 class="logo">MyPortfolio</h1>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- STEP 4: Sections -->
    <section id="home" class="section home">
        <h2>Hello, I'm Magendra 👋</h2>
        <p>Aspiring Web Developer</p>
        <img src="🫡.png.jpg" alt="Profile Image">
    </section>

    <section id="about" class="section about">
        <h2>About Me</h2>
        <p>
            I am S.Magendra Sanjay, 2nd year C.S.E student form Saveetha Engineering College,I am a passionate about web development, learning modern technologies
            and building clean, user-friendly interfaces.
        </p>
    </section>

    <section id="projects" class="section projects">
        <h2>Projects</h2>
        <div class="project-grid">
            <div class="project-card">Project 1</div>
            <div class="project-card">Project 2</div>
            <div class="project-card">Project 3</div>
        </div>
    </section>

    <section id="contact" class="section contact">
        <h2>Contact Me</h2>
        <p>Email: magendra@example.com</p>
        <p>GitHub: github.com/magendra</p>
    </section>

    <footer>
        <p>© 2026 Magendra Sanjay</p>
    </footer>

</body>
</html>


style.css

/* STEP 5: Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body {
    background-color: #f5f5f5;
    color: #333;
    line-height: 1.6;
}

/* STEP 6: Header & Navbar */
header {
    background: #111;
    padding: 15px 40px;
}

.navbar {
    display: flex; /* STEP 7: Flexbox */
    justify-content: space-between;
    align-items: center;
}

.logo {
    color: #fff;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
}

.nav-links a {
    color: #fff;
    text-decoration: none;
    transition: color 0.3s ease; /* STEP 8 */
}

.nav-links a:hover {
    color: #00adb5;
}

/* Sections */
.section {
    padding: 60px 40px;
    text-align: center;
}

.home img {
    width: 180px;
    border-radius: 50%;
    margin-top: 20px;
}

/* Projects Grid */
.project-grid {
    display: grid; /* STEP 7: CSS Grid */
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-top: 30px;
}

.project-card {
    background: #fff;
    padding: 30px;
    border-radius: 10px;
    transition: transform 0.3s ease;
}

.project-card:hover {
    transform: translateY(-8px);
}

/* Footer */
footer {
    background: #111;
    color: #fff;
    text-align: center;
    padding: 15px;
}
```

## OUTPUT
![alt text](<../1 (2).png>)
![alt text](<../2 (2).png>)
![alt text](<../3 (2).png>)

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
