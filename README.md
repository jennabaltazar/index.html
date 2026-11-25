<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jenna Baltazar — Web Design Portfolio</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
      background-color: #f8fafc;
      color: #1e293b;
      line-height: 1.6;
    }
    /* Navigation */
    header {
      background: #ffffff;
      border-bottom: 1px solid #e2e8f0;
      padding: 18px 24px;
      position: sticky;
      top: 0;
    }
    .nav-container {
      max-width: 1000px;
      margin: 0 auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-weight: 700;
      font-size: 1.2rem;
      color: #0f172a;
      text-decoration: none;
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #475569;
      font-weight: 500;
    }
    nav a:hover {
      color: #2563eb;
    }
    /* Hero Section */
    .hero {
      max-width: 800px;
      margin: 70px auto 50px;
      padding: 0 24px;
      text-align: center;
    }
    .hero h1 {
      font-size: 2.5rem;
      color: #0f172a;
      margin-bottom: 16px;
    }
    .hero p {
      font-size: 1.15rem;
      color: #475569;
      margin-bottom: 28px;
    }
    .btn {
      display: inline-block;
      padding: 12px 26px;
      background-color: #2563eb;
      color: #ffffff;
      text-decoration: none;
      border-radius: 8px;
      font-weight: 600;
      transition: background 0.2s;
    }
    .btn:hover {
      background-color: #1d4ed8;
    }
    /* Sections */
    .section {
      max-width: 1000px;
      margin: 60px auto;
      padding: 0 24px;
    }
    .section-title {
      font-size: 1.75rem;
      margin-bottom: 24px;
      text-align: center;
      color: #0f172a;
    }
    /* 3-Column Project Grid */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 24px;
    }
    .card {
      background: #ffffff;
      border-radius: 12px;
      overflow: hidden;
      border: 1px solid #e2e8f0;
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .card:hover {
      transform: translateY(-4px);
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.06);
    }
    .card-thumb {
      height: 160px;
      background: linear-gradient(135deg, #dbeafe, #e0e7ff);
      display: flex;
      align-items: center;
      justify-content: center;
      color: #1e40af;
      font-weight: 600;
    }
    .card-body {
      padding: 20px;
    }
    .card-body h3 {
      margin-bottom: 8px;
      font-size: 1.2rem;
    }
    .card-body p {
      color: #475569;
      font-size: 0.95rem;
      margin-bottom: 16px;
    }
    .card-link {
      color: #2563eb;
      text-decoration: none;
      font-weight: 600;
      font-size: 0.95rem;
    }
    /* About & Contact */
    .box {
      background: #ffffff;
      padding: 36px;
      border-radius: 14px;
      border: 1px solid #e2e8f0;
      text-align: center;
    }
    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin-top: 20px;
    }
    .skill-tag {
      background: #eff6ff;
      color: #1d4ed8;
      padding: 6px 14px;
      border-radius: 999px;
      font-size: 0.9rem;
      font-weight: 500;
    }
    footer {
      text-align: center;
      padding: 30px 24px;
      color: #64748b;
      font-size: 0.9rem;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <div class="nav-container">
      <a href="#" class="logo">Jenna Baltazar</a>
      <nav>
        <a href="#work">Work</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <section class="hero">
    <h1>Hi, I'm Jenna Baltazar</h1>
    <p>A collection of my web design projects, practice layouts, and custom websites built with HTML and CSS.</p>
    <a href="#work" class="btn">View My Work</a>
  </section>

  <section id="work" class="section">
    <h2 class="section-title">Selected Projects</h2>
    <div class="grid">
      <div class="card">
        <div class="card-thumb">Project Preview 1</div>
        <div class="card-body">
          <h3>My Resume</h3>
          <p>Designing and building clean, responsive websites and landing pages with HTML and CSS.</p>
          <a href="#" class="card-link">View Project →</a>
        </div>
      </div>

      <div class="card">
        <div class="card-thumb">Project Preview 2</div>
        <div class="card-body">
          <h3>Personal Blog Layout</h3>
          <p>A minimalist reading layout designed with clear typography, spacing, and responsive article cards.</p>
          <a href="#" class="card-link">View Project →</a>
        </div>
      </div>

      <div class="card">
        <div class="card-thumb">Project Preview 3</div>
        <div class="card-body">
          <h3>Service Business Website</h3>
          <p>A modern business homepage highlighting core services, client testimonials, and a clear contact section.</p>
          <a href="#" class="card-link">View Project →</a>
        </div>
      </div>
    </div>
  </section>

  <section id="about" class="section">
    <div class="box">
      <h2 class="section-title">About Me</h2>
      <p>I am a web designer focused on creating clean, responsive, and easy-to-navigate websites. I enjoy turning ideas into simple, well-structured pages using HTML and CSS.</p>
      <div class="skills">
        <span class="skill-tag">Web Design</span>
        <span class="skill-tag">Landing Pages</span>
        <span class="skill-tag">Responsive Layouts</span>
        <span class="skill-tag">HTML5</span>
        <span class="skill-tag">CSS3</span>
      </div>
    </div>
  </section>

  <section id="contact" class="section">
    <div class="box">
      <h2 class="section-title">Get In Touch</h2>
      <p style="margin-bottom: 20px;">Looking for help with a website or landing page? Feel free to reach out.</p>
      <a href="mailto:jennabaltazar24@gmail.com" class="btn">Email Me</a>
    </div>
  </section>

  <footer>
    © 2026 Jenna Baltazar. Built and hosted on GitHub Pages.
  </footer>

</body>
</html>
