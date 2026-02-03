# FUTURE_FS_01
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title> S.KUSHALA | Full Stack Web Developer</title>

  <!-- SEO Meta -->
  <meta name="description" content="Personal portfolio website showcasing projects, skills, and experience of a Full Stack Web Developer Intern." />

  <link rel="stylesheet" href="css/style.css" />
</head>
<body>

  <!-- ===== NAVBAR ===== -->
  <header>
    <nav class="navbar">
      <h2 class="logo">YourName</h2>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- ===== HOME ===== -->
  <section id="home" class="section home">
    <h1>Hello, I'm <span>S.KUSHALA</span></h1>
    <h3>Full Stack Web Developer Intern</h3>
    <p>I build responsive and user-friendly web applications.</p>
    <div class="btn-group">
      <a href="#projects" class="btn">View Projects</a>
      <a href="assets/resume.pdf" class="btn btn-outline" download>Download Resume</a>
    </div>
  </section>

  <!-- ===== ABOUT ===== -->
  <section id="about" class="section">
    <h2>About Me</h2>
    <p>
      I am a passionate Full Stack Web Development intern with strong knowledge of
      HTML, CSS, JavaScript, and backend fundamentals. I enjoy building real-world
      projects and continuously improving my skills.
    </p>
    <p><strong>Education:</strong> B.Tech / B.Sc / Diploma (Your Course)</p>
    <p><strong>Career Goal:</strong> To become a professional Full Stack Developer.</p>
  </section>

  <!-- ===== SKILLS ===== -->
  <section id="skills" class="section">
    <h2>Skills</h2>
    <div class="skills-container">
      <div class="skill-card">HTML</div>
      <div class="skill-card">CSS</div>
      <div class="skill-card">JavaScript</div>
      <div class="skill-card">Node.js</div>
      <div class="skill-card">Git & GitHub</div>
      <div class="skill-card">VS Code</div>
    </div>
  </section>

  <!-- ===== PROJECTS ===== -->
  <section id="projects" class="section">
    <h2>Projects</h2>
    <div class="project-container">

      <div class="project-card">
        <h3>Portfolio Website</h3>
        <p>Personal portfolio website built using HTML, CSS, and JavaScript.</p>
        <p><strong>Tech:</strong> HTML, CSS, JS</p>
        <a href="#" target="_blank">GitHub</a> |
        <a href="#" target="_blank">Live Demo</a>
      </div>

      <div class="project-card">
        <h3>Mini Web App</h3>
        <p>A simple web application demonstrating frontend skills.</p>
        <p><strong>Tech:</strong> HTML, CSS, JS</p>
        <a href="#" target="_blank">GitHub</a>
      </div>

    </div>
  </section>

  <!-- ===== CONTACT ===== -->
  <section id="contact" class="section">
    <h2>Contact Me</h2>
    <form id="contactForm">
      <input type="text" id="name" placeholder="Your Name" required />
      <input type="email" id="email" placeholder="Your Email" required />
      <textarea id="message" placeholder="Your Message" required></textarea>
      <button type="submit" class="btn">Send Message</button>
      <p id="formStatus"></p>
    </form>
  </section>

  <!-- ===== FOOTER ===== -->
  <footer>
    <p>© 2026 S.KUSHALA | Full Stack Web Developer</p>
  </footer>

  <script src="js/script.js"></script>
</body>
</html>
