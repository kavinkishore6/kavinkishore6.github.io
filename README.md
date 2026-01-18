<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kavin Kishore | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }

    body {
      background: #0f172a;
      color: #e5e7eb;
      line-height: 1.6;
    }

    nav {
      position: fixed;
      top: 0;
      width: 100%;
      padding: 15px 40px;
      background: rgba(15,23,42,0.9);
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 100;
    }

    nav a {
      color: #e5e7eb;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
    }

    nav a:hover {
      color: #38bdf8;
    }

    header {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      color: #38bdf8;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }

    .top-buttons {
      margin-top: 20px;
    }

    .top-buttons a {
      text-decoration: none;
      color: #0f172a;
      background: #38bdf8;
      padding: 10px 20px;
      border-radius: 8px;
      margin: 0 10px;
      font-weight: 600;
      transition: background 0.3s ease;
    }

    .top-buttons a:hover {
      background: #0ea5e9;
    }

    section {
      padding: 80px 10%;
    }

    h2 {
      color: #38bdf8;
      margin-bottom: 30px;
      font-size: 2rem;
      text-align: center;
    }

    .card {
      background: #020617;
      padding: 25px;
      border-radius: 16px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
      margin-bottom: 30px;
    }

    .card h3 {
      margin-bottom: 15px;
    }

    ul {
      list-style: none;
    }

    ul li {
      margin-bottom: 10px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #020617;
    }

    /* Skills grid */
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    /* Contact section */
    .contact-wrapper {
      text-align: center;
    }

    .contact-wrapper p {
      margin-bottom: 40px;
      color: #cbd5f5;
    }

    .contact-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 30px;
    }

    .contact-card {
      background: #020617;
      padding: 35px 20px;
      border-radius: 18px;
      box-shadow: 0 15px 35px rgba(0,0,0,0.25);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .contact-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 20px 45px rgba(0,0,0,0.35);
    }

    .contact-card img {
      width: 44px;
      margin-bottom: 15px;
    }

    .contact-card a {
      color: #e5e7eb;
      text-decoration: none;
      font-weight: 500;
    }

    @media(max-width: 768px) {
      header h1 { font-size: 2.2rem; }
      section { padding: 60px 5%; }
    }
  </style>
</head>

<body>

<nav>
  <div><strong>Portfolio</strong></div>
  <div>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#experience">Experience</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<header>
  <h1>Kavin Kishore Senthil</h1>
  <p>Java Full Stack Developer</p>
  <div class="top-buttons">
   
    <a href="https://github.com/kavinkishore6" target="_blank">View GitHub</a>
  </div>
</header>

<section id="about">
  <h2>About Me</h2>
  <div class="card">
    <ul>
      <li>Java Full Stack Developer with 2.5+ years of experience in building scalable enterprise applications across the full SDLC.</li>
      <li>Hands-on experience with Java, Spring Boot, REST APIs, SQL, and full-stack development for manufacturing clients.</li>
      <li>Worked with global clients including Toyo Tyres and RHI Magnesita, delivering reliable production-grade systems.</li>
      <li>Strong in backend development, API design, database integration, debugging, and performance optimization.</li>
      <li>Actively solving DSA problems on LeetCode (150+) and continuously improving problem-solving skills.</li>
    </ul>
  </div>
</section>


<section id="skills">
  <h2>Skills</h2>
  <div class="skills-grid">

    <div class="card">
      <h3>🖥️ Backend</h3>
      <ul>
        <li>Java</li>
        <li>Spring Boot</li>
        <li>FTPC Framework</li>
      </ul>
    </div>

    <div class="card">
      <h3>💻 Frontend</h3>
      <ul>
        <li>HTML5</li>
        <li>CSS3</li>
        <li>JavaScript</li>
        <li>Thymeleaf</li>
      </ul>
    </div>

    <div class="card">
      <h3>🗄️ Database</h3>
      <ul>
        <li>MySQL</li>
        <li>PostgreSQL</li>
        <li>SQL</li>
      </ul>
    </div>

    <div class="card">
      <h3>🛠️ Tools & Testing</h3>
      <ul>
        <li>Git, GitHub</li>
        <li>Eclipse, VS Code</li>
        <li>Postman, Swagger</li>
        <li>Twilio Integration</li>
      </ul>
    </div>

    <div class="card">
      <h3>📋 Methodologies</h3>
      <ul>
        <li>Agile</li>
        <li>Waterfall</li>
      </ul>
    </div>

  </div>
</section>

<section id="experience">
  <h2>Work Experience</h2>
  <div class="card">
    <h3>Rockwell Automation – Associate Software Engineer</h3>
    <p>Chennai | 2.5 Years</p>
    <ul>
      <li>Gathered client requirements and created Functional Design Specifications</li>
      <li>Developed enterprise applications using Java and FTPC framework</li>
      <li>Implemented PLC tag integration for real-time data exchange</li>
      <li>Optimized backend and frontend for better system performance</li>
      <li>Delivered features via Agile sprints with documentation and code reviews</li>
      <li>Provided production support for live manufacturing applications</li>
    </ul>
  </div>
</section>

<section id="projects">
  <h2>Projects</h2>

  <div class="card">
    <h3>Movie Ticket Booking System</h3>
    <p>Tech Stack: Java, Spring Boot, MySQL, HTML, CSS, JavaScript, Thymeleaf</p>
    <ul>
      <li>Role-based authentication for Admin and Users</li>
      <li>Movie, theatre, show, and seat management modules</li>
      <li>Booking workflow with transaction history tracking</li>
      
      <li>GitHub: <a href="https://github.com/kavinkishore6/Movie-Ticket-Booking-System" target="_blank">Repo Link</a></li>
    </ul>
  </div>

  <div class="card">
    <h3>E-Commerce Application</h3>
    <p>Tech Stack: Java, Spring Boot, MySQL, Razorpay, HTML, CSS, JavaScript, Thymeleaf</p>
    <ul>
      <li>Admin & Customer role-based access control</li>
      <li>Product catalog, cart, and order tracking modules</li>
      <li>Razorpay payment gateway integration</li>
      
      <li>GitHub: <a href="https://github.com/kavinkishore6/EcommerceApplication" target="_blank">Repo Link</a></li>
    </ul>
  </div>

  <div class="card">
    <h3>JobConnect Portal — Full Stack Job Portal</h3>
    <p>Tech Stack: Java, Spring Boot, PostgreSQL, Twilio, Swagger, HTML, CSS, JavaScript, Thymeleaf</p>
    <ul>
      <li>Recruiter-candidate platform with job posting and application tracking</li>
      <li>REST APIs documented using Swagger</li>
      <li>Twilio SMS notifications improves recruiter response time </li>
      <li>Secure authentication and role-based access control</li>
      <li>GitHub: <a href="https://github.com/kavinkishore6/Jobconnect-Portal" target="_blank">Repo Link</a></li>
    </ul>
  </div>

</section>

<section id="contact">
  <h2>Contact</h2>

  <div class="contact-wrapper">
    <p>Have an opportunity or idea? Let’s talk</p>

    <div class="contact-grid">

      <div class="contact-card">
        <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png">
        <p><a href="mailto:kavinred@gmail.com">kavinred@gmail.com</a></p>
      </div>

      <div class="contact-card">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg">
        <p>
          <a href="https://www.linkedin.com/in/kavin-kishore-b8a1051b9/" target="_blank">
            LinkedIn
          </a>
        </p>
      </div>

      <div class="contact-card">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg">
        <p>
          <a href="https://github.com/kavinkishore6" target="_blank">
            GitHub
          </a>
        </p>
      </div>

    </div>
  </div>
</section>

<footer>
  <p>© 2026 Kavin Kishore. All Rights Reserved.</p>
</footer>

</body>
</html>
