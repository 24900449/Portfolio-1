# Ex01 Portfolio
## Date:03.08.2026

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
index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Hi, I'm Priyanka</h1>
    <p>Computer Science Engineering Student</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>
        I'm a Computer Science Engineering student passionate about
        Java, Web Development, Machine Learning, and Cloud Computing.
        I enjoy building real-world projects and continuously learning
        new technologies.
    </p>
</section>

<section id="skills">
    <h2>Skills</h2>

    <div class="card">
        <h3>Programming</h3>
        <p>Java, C, Python</p>
    </div>

    <div class="card">
        <h3>Web</h3>
        <p>HTML, CSS, JavaScript</p>
    </div>

    <div class="card">
        <h3>Database</h3>
        <p>MySQL</p>
    </div>

    <div class="card">
        <h3>Tools</h3>
        <p>Git, GitHub, VS Code</p>
    </div>

</section>

<section id="projects">
    <h2>Projects</h2>

    <div class="card">
        <h3>Blood Donation App</h3>
        <p>
            A mobile application that helps hospitals quickly notify
            nearby blood donors through SMS or WhatsApp.
        </p>
    </div>

    <div class="card">
        <h3>Student Management System</h3>
        <p>
            Java-based desktop application for managing student records.
        </p>
    </div>

</section>

<section id="contact">
    <h2>Contact</h2>

    <p>Email : yourmail@gmail.com</p>
    <p>GitHub : https://github.com/yourusername</p>
    <p>LinkedIn : https://linkedin.com/in/yourprofile</p>

</section>

<footer>
    <p>© 2026 Priyanka | All Rights Reserved</p>
</footer>

<script src="script.js"></script>

</body>
</html>
```
style.css:
```
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f4f4f4;
    color:#333;
}

header{
    background:#0077cc;
    color:white;
    padding:50px;
    text-align:center;
}

nav{
    background:#222;
    padding:15px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:15px;
    font-weight:bold;
}

nav a:hover{
    color:skyblue;
}

section{
    padding:40px;
}

.card{
    background:white;
    margin:20px 0;
    padding:20px;
    border-radius:10px;
    box-shadow:0 5px 10px rgba(0,0,0,.2);
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
}
```
 




## OUTPUT
<img width="1910" height="1071" alt="Screenshot 2026-07-31 213450" src="https://github.com/user-attachments/assets/677b2d68-f4ae-48b3-bf80-7a89cafd8cf7" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
