<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, Helvetica, sans-serif;
        }

        body{
            background:#f4f4f4;
            color:#333;
        }

        header{
            background:#0d6efd;
            color:white;
            padding:20px;
        }

        nav{
            display:flex;
            justify-content:space-between;
            align-items:center;
            max-width:1100px;
            margin:auto;
        }

        nav ul{
            list-style:none;
            display:flex;
        }

        nav ul li{
            margin-left:20px;
        }

        nav ul li a{
            color:white;
            text-decoration:none;
            font-weight:bold;
        }

        .hero{
            display:flex;
            justify-content:center;
            align-items:center;
            text-align:center;
            height:80vh;
            background:white;
        }

        .hero img{
            width:180px;
            height:180px;
            border-radius:50%;
            object-fit:cover;
            border:5px solid #0d6efd;
            margin-bottom:20px;
        }

        .hero h1{
            font-size:40px;
        }

        .hero p{
            margin:15px 0;
            font-size:18px;
        }

        .btn{
            display:inline-block;
            padding:12px 25px;
            background:#0d6efd;
            color:white;
            text-decoration:none;
            border-radius:5px;
        }

        section{
            padding:60px 20px;
            max-width:1100px;
            margin:auto;
        }

        h2{
            text-align:center;
            margin-bottom:30px;
            color:#0d6efd;
        }

        .about p{
            text-align:center;
            line-height:1.8;
        }

        .skills{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
            gap:20px;
        }

        .skill{
            background:white;
            padding:20px;
            text-align:center;
            border-radius:10px;
            box-shadow:0 2px 10px rgba(0,0,0,.1);
        }

        .projects{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
            gap:20px;
        }

        .project{
            background:white;
            padding:20px;
            border-radius:10px;
            box-shadow:0 2px 10px rgba(0,0,0,.1);
        }

        .contact{
            text-align:center;
        }

        footer{
            background:#222;
            color:white;
            text-align:center;
            padding:20px;
        }

        @media(max-width:768px){

            nav{
                flex-direction:column;
            }

            nav ul{
                margin-top:15px;
            }

            .hero h1{
                font-size:30px;
            }

        }

    </style>

</head>
<body>

<header>

<nav>

<h2>Portfolio</h2>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>

</header>

<section class="hero">

<div>

<img src="profile.jpg" alt="Profile Picture">

<h1>Javed Daganda</h1>

<p>BS Information Systems Student | Aspiring Web Developer</p>

<a href="#contact" class="btn">Contact Me</a>

</div>

</section>

<section id="about" class="about">

<h2>About Me</h2>

<p>
Hello! I'm Javed Daganda, a Bachelor of Science in Information Systems student.
I enjoy creating websites, developing Java applications, and learning new
technologies. I am passionate about solving problems through programming
and continuously improving my technical skills.
</p>

</section>

<section id="skills">

<h2>Skills</h2>

<div class="skills">

<div class="skill">
<h3>HTML</h3>
<p>Responsive Web Design</p>
</div>

<div class="skill">
<h3>CSS</h3>
<p>Modern UI Design</p>
</div>

<div class="skill">
<h3>Java</h3>
<p>Java Swing Applications</p>
</div>

<div class="skill">
<h3>MySQL</h3>
<p>Database Management</p>
</div>

<div class="skill">
<h3>Microsoft Office</h3>
<p>Word, Excel, PowerPoint</p>
</div>

<div class="skill">
<h3>Problem Solving</h3>
<p>Analytical Thinking</p>
</div>

</div>

</section>

<section id="projects">

<h2>Projects</h2>

<div class="projects">

<div class="project">

<h3>Inventory Management System</h3>

<p>
A Java Swing application with MySQL database for managing products,
stock levels, expiry dates, and employee records.
</p>

</div>

<div class="project">

<h3>HealthLine+ ERP System</h3>

<p>
A web-based Barangay Health Station management system with patient records,
appointments, and medical history.
</p>

</div>

<div class="project">

<h3>Personal Portfolio Website</h3>

<p>
A responsive personal portfolio website built using HTML and CSS.
</p>

</div>

</div>

</section>

<section id="contact" class="contact">

<h2>Contact Me</h2>

<p><strong>Email:</strong> youremail@example.com</p>

<p><strong>Phone:</strong> +63 912 345 6789</p>

<p><strong>Facebook:</strong> facebook.com/yourprofile</p>

<p><strong>GitHub:</strong> github.com/yourusername</p>

</section>

<footer>

<p>© 2026 Javed Daganda | All Rights Reserved</p>

</footer>

</body>
</html>
