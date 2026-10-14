
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: #f8fafc;
      line-height: 1.6;
    }

    nav {
      padding: 20px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #334155;
    }

    nav a, .links a {
      color: #cbd5e1;
      text-decoration: none;
      margin-left: 16px;
    }

    section {
      padding: 65px 8%;
      max-width: 1050px;
      margin: auto;
    }

    .hero { padding-top: 100px; padding-bottom: 100px; }

    .tag { color: #38bdf8; font-weight: bold; }

    h1 { font-size: clamp(38px, 7vw, 64px); line-height: 1.1; }
    h2 { font-size: 30px; }

    p { color: #cbd5e1; }

    .btn {
      display: inline-block;
      background: #38bdf8;
      color: #0f172a;
      padding: 12px 20px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 12px;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 18px;
    }

    .card {
      background: #1e293b;
      padding: 22px;
      border-radius: 12px;
      border: 1px solid #334155;
    }

    footer {
      text-align: center;
      padding: 25px;
      border-top: 1px solid #334155;
      color: #94a3b8;
    }
  </style>
</head>
<body>

  <nav>
    <strong>My Portfolio</strong>
    <div class="links">
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <section class="hero">
    <p class="tag">HELLO, I'M</p>
    <h1>Your Name<br>Future Developer.</h1>
    <p>
      I'm learning to build beautiful websites and
      creating projects that solve real problems.
    </p>
    <a class="btn" href="#projects">Explore My Work</a>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>
      Write a short introduction about yourself, your
      education, skills, interests, and career goals.
    </p>
    <p><strong>Skills:</strong> HTML · CSS · JavaScript · GitHub</p>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Project One</h3>
        <p>Describe a website or project you created.</p>
        <a href="https://github.com/" target="_blank"
           rel="noopener noreferrer">View Project →</a>
      </div>
      <div class="card">
        <h3>Project Two</h3>
        <p>Explain what you built and what you learned.</p>
        <a href="https://github.com/" target="_blank"
           rel="noopener noreferrer">View Project →</a>
      </div>
      <div class="card">
        <h3>Project Three</h3>
        <p>Add another project you are proud of.</p>
        <a href="https://github.com/" target="_blank"
           rel="noopener noreferrer">View Project →</a>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Interested in working together? Feel free to reach out.</p>
    <a class="btn" href="mailto:your-email@example.com">
      Email Me
    </a>
    <p>
      <a href="https://github.com/" target="_blank"
         rel="noopener noreferrer">GitHub</a>
      ·
      <a href="https://www.linkedin.com/" target="_blank"
         rel="noopener noreferrer">LinkedIn</a>
    </p>
  </section>

  <footer>© 2026 Your Name. All rights reserved.</footer>

</body>
</html>
