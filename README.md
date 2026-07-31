# Ex01 Portfolio
## Date: 31/07/2026

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

    <!-- Navigation -->
    <header>
        <nav>
            <h2 class="logo">Portfolio</h2>

            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home -->
    <section id="home" class="hero">
        <div class="hero-text">
            <h1>Hello, I'm <span>Subiksha Kumar</span></h1>
            <p>Aspiring Web Developer | Student | Designer</p>
            <a href="#contact" class="btn">Contact Me</a>
        </div>

        <div class="hero-image">
            <img src="profile.jpeg" alt="Profile">
        </div>
    </section>

    <!-- About -->
    <section id="about">
        <h2>About Me</h2>

        <p>
            I am a passionate Computer Science student interested in
            Web Development, UI/UX Design, and Data Analytics.
            I enjoy creating responsive websites and learning new
            technologies.
        </p>
    </section>

    <!-- Skills -->
    <section id="skills">

        <h2>Skills</h2>

        <div class="skills-container">

            <div class="skill-card">HTML5</div>

            <div class="skill-card">CSS3</div>

            <div class="skill-card">JavaScript</div>

            <div class="skill-card">Python</div>

            <div class="skill-card">SQL</div>

            <div class="skill-card">UI/UX</div>

        </div>

    </section>

    <!-- Projects -->
    <section id="projects">

        <h2>Projects</h2>

        <div class="project-container">

            <div class="project-card">
                <h3>Portfolio Website</h3>

                <p>
                    A responsive portfolio website created using
                    HTML and CSS.
                </p>

            </div>

            <div class="project-card">
                <h3>Weather App</h3>

                <p>
                    Displays weather information using API integration.
                </p>

            </div>

            <div class="project-card">
                <h3>Student Management System</h3>

                <p>
                    A CRUD-based application for managing student records.
                </p>

            </div>

        </div>

    </section>

    <section id="contact">

    <h2>Contact Me</h2>

    <div class="contact-container">

        <div class="contact-card">

            <h3>Get In Touch</h3>

            <p><strong>Name:</strong> Subiksha Kumar</p>

            <p><strong>Degree:</strong> B.E. Computer Science and Engineering</p>

            <p><strong>College:</strong> Saveetha Engineering College</p>

            <p><strong>Email:</strong> subiksha@example.com</p>

            <p><strong>Phone:</strong> +91 6379925799</p>

            <p><strong>Location:</strong> Chennai, Tamil Nadu, India</p>

            <p>
                <strong>GitHub:</strong>
                <a href="https://github.com/2400100" target="_blank">
                    github.com/2400100
                </a>
            </p>

        </div>

    </div>

    </section>

    <!-- Footer -->

    <footer>

        <p>© 2026 Your Name | All Rights Reserved</p>

    </footer>

</body>
</html>
```

style.css:

```
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#f4f4f4;
    color:#333;
}

/* Navigation */

header{
    background:#222;
    color:white;
    position:fixed;
    width:100%;
    top:0;
    z-index:1000;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:18px 60px;
}

.logo{
    font-size:30px;
}

.nav-links{
    display:flex;
    list-style:none;
}

.nav-links li{
    margin-left:30px;
}

.nav-links a{
    color:white;
    text-decoration:none;
    font-size:18px;
    transition:.3s;
}

.nav-links a:hover{
    color:#00c3ff;
}

/* Hero */

.hero{
    display:flex;
    justify-content:space-around;
    align-items:center;
    padding:150px 60px 80px;
    flex-wrap:wrap;
}

.hero-text{
    max-width:500px;
}

.hero-text h1{
    font-size:50px;
    margin-bottom:20px;
}

.hero-text span{
    color:#0077ff;
}

.hero-text p{
    font-size:22px;
    margin-bottom:30px;
}

.btn{
    background:#0077ff;
    color:white;
    text-decoration:none;
    padding:12px 30px;
    border-radius:30px;
    transition:.4s;
}

.btn:hover{
    background:#0055aa;
}

.hero-image img{
    width:350px;
    height:350px;
    border-radius:50%;
    object-fit:cover;
    box-shadow:0 5px 20px rgba(0,0,0,.3);
}

/* Sections */

section{
    padding:80px 60px;
}

section h2{
    text-align:center;
    font-size:40px;
    margin-bottom:40px;
    color:#0077ff;
}

#about p{
    text-align:center;
    max-width:900px;
    margin:auto;
    line-height:1.8;
    font-size:20px;
}

/* Skills */

.skills-container{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:25px;
}

.skill-card{
    background:white;
    padding:30px;
    width:180px;
    text-align:center;
    border-radius:10px;
    box-shadow:0 4px 10px rgba(0,0,0,.2);
    transition:.4s;
    font-size:20px;
}

.skill-card:hover{
    transform:translateY(-10px);
    background:#0077ff;
    color:white;
}

/* Projects */

.project-container{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:30px;
}

.project-card{
    background:white;
    width:300px;
    padding:25px;
    border-radius:10px;
    box-shadow:0 5px 15px rgba(0,0,0,.2);
    transition:.4s;
}

.project-card:hover{
    transform:scale(1.05);
}

.project-card h3{
    margin-bottom:15px;
    color:#0077ff;
}

.project-card p{
    line-height:1.6;
}

/* Contact */

form{
    width:500px;
    max-width:100%;
    margin:auto;
    display:flex;
    flex-direction:column;
}

input,
textarea{
    padding:15px;
    margin:10px 0;
    border-radius:8px;
    border:1px solid #ccc;
    font-size:16px;
}

button{
    background:#0077ff;
    color:white;
    border:none;
    padding:15px;
    border-radius:8px;
    cursor:pointer;
    font-size:18px;
    transition:.4s;
}

button:hover{
    background:#0055aa;
}

/* Footer */

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
}

/* Responsive */

@media(max-width:768px){

nav{
    flex-direction:column;
}

.nav-links{
    flex-direction:column;
    margin-top:20px;
}

.nav-links li{
    margin:10px 0;
}

.hero{
    flex-direction:column;
    text-align:center;
}

.hero-image img{
    width:250px;
    height:250px;
    margin-top:40px;
}

.hero-text h1{
    font-size:36px;
}

section{
    padding:60px 20px;
}

}
```



## OUTPUT

<img width="1920" height="1200" alt="1 (1)" src="https://github.com/user-attachments/assets/50d6dce0-7169-42d0-bb18-e5072a8a6e00" />
<img width="1920" height="1200" alt="2" src="https://github.com/user-attachments/assets/27bb8955-bd02-464a-be71-e929c4e6df5a" />
<img width="1920" height="1200" alt="3" src="https://github.com/user-attachments/assets/5d28a5bb-3cee-44dd-af8a-53254ccb1d44" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
