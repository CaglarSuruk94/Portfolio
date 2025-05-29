<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Personal Portfolio</title>
  <style>
    *{margin:0;padding:0;box-sizing:border-box;}
    body{font-family:Arial,sans-serif;line-height:1.6;background-color:#f4f4f4;color:#333;max-width:900px;margin:0 auto;padding:20px;}
    header{background-color:#1e90ff;color:white;padding:20px 0;text-align:center;}
    nav a{margin:0 15px;color:white;text-decoration:none;}
    section{margin:40px 0;}
    footer{text-align:center;margin-top:50px;padding:20px;background-color:#1e90ff;color:white;}
    .project{margin-top:20px;padding:15px;border:1px solid #ccc;border-radius:8px;background:white;}
  </style>
</head>
<body>
  <header>
    <h1>Your Name</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <section id="home">
    <h2>Welcome</h2>
    <p>This is my personal portfolio showcasing my work and skills.</p>
  </section>
  <section id="about">
    <h2>About Me</h2>
    <p>I am a web developer passionate about creating clean, responsive, and accessible websites. I have experience with HTML, CSS, JavaScript, and version control using Git & GitHub.</p>
  </section>
  <section id="projects">
    <h2>My Projects</h2>
    <div class="project">
      <h3>Portfolio Website</h3>
      <p>This site was built to showcase my skills and projects. It is fully responsive and written in pure HTML and CSS.</p>
    </div>
    <div class="project">
      <h3>To-Do App</h3>
      <p>A task management app built with HTML, CSS, and JavaScript allowing users to create, complete, and delete tasks.</p>
    </div>
  </section>
  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: your.email@example.com</p>
    <p>LinkedIn: <a href="#">linkedin.com/in/yourname</a></p>
  </section>
  <footer>
    <p>&copy; 2025 Your Name. All rights reserved.</p>
  </footer>
</body>
</html>
