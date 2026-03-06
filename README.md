<!DOCTYPE html>
<html lang="en">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Albert Rapha | Personal Website</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family: "Segoe UI", sans-serif;
}

body{
background:#f8f9fb;
color:#333;
line-height:1.6;
}

/* NAVBAR */

header{
background:white;
box-shadow:0 2px 10px rgba(0,0,0,0.05);
position:sticky;
top:0;
z-index:100;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
}

.logo{
font-size:22px;
font-weight:600;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:25px;
}

nav ul li a{
text-decoration:none;
color:#333;
font-weight:500;
transition:0.3s;
}

nav ul li a:hover{
color:#0077ff;
}

/* HERO */

.hero{
height:90vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:0 20px;
background:linear-gradient(135deg,#ffffff,#eef2f7);
}

.hero h1{
font-size:50px;
margin-bottom:10px;
}

.hero p{
font-size:18px;
margin-bottom:25px;
color:#666;
}

.btn{
padding:12px 28px;
background:#0077ff;
color:white;
border-radius:25px;
text-decoration:none;
font-weight:500;
transition:0.3s;
}

.btn:hover{
background:#005fd1;
}

/* SECTIONS */

.section{
padding:80px 10%;
text-align:center;
}

.section h2{
font-size:32px;
margin-bottom:20px;
}

/* ABOUT */

.about p{
max-width:600px;
margin:auto;
color:#555;
}

/* PROJECTS */

.projects-grid{
margin-top:40px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.project-card{
background:white;
padding:30px;
border-radius:12px;
box-shadow:0 4px 15px rgba(0,0,0,0.05);
transition:0.3s;
}

.project-card:hover{
transform:translateY(-6px);
}

.project-card h3{
margin-bottom:10px;
}

/* CONTACT */

.contact p{
color:#555;
margin-top:10px;
}

/* FOOTER */

footer{
margin-top:60px;
padding:20px;
background:white;
text-align:center;
font-size:14px;
color:#777;
}

</style>
</head>

<body>

<header>
<nav>

<div class="logo">YourName</div>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>
</header>

<section class="hero">

<div>

<h1>Hello, I'm Your Name</h1>

<p>
A passionate developer creating simple and elegant digital experiences.
</p>

<a href="#contact" class="btn">Contact Me</a>

</div>

</section>

<section id="about" class="section about">

<h2>About Me</h2>

<p>
I am a developer interested in technology, programming, and modern web design.
I enjoy building clean, fast, and user-friendly websites. This page is my
personal space to share projects and experiences.
</p>

</section>

<section id="projects" class="section">

<h2>Projects</h2>

<div class="projects-grid">

<div class="project-card">
<h3>Portfolio Website</h3>
<p>A personal website to showcase my work and projects.</p>
</div>

<div class="project-card">
<h3>Web App</h3>
<p>A responsive web application built with modern tools.</p>
</div>

<div class="project-card">
<h3>Open Source</h3>
<p>Contributions to open source projects and collaborations.</p>
</div>

</div>

</section>

<section id="contact" class="section contact">

<h2>Contact</h2>

<p>Email: your@email.com</p>
<p>GitHub: github.com/yourusername</p>

</section>

<footer>

<p>© 2026 Albert Rapha — Personal Website</p>

</footer>

<script>

document.querySelectorAll('a[href^="#"]').forEach(anchor => {

anchor.addEventListener("click", function(e){

e.preventDefault();

document.querySelector(this.getAttribute("href")).scrollIntoView({
behavior:"smooth"
});

});

});

</script>

</body>
</html>
