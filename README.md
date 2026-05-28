
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>Hamza | Game Developer • Software Engineer</title>

  <meta
    name="description"
    content="Portfolio of Hamza — IIT Student, Game Developer, Software Engineer, and Competitive Programmer."
  />

  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css"
  />

  <style>
    :root {
      --bg: #020617;
      --card: #0f172a;
      --card2: #111827;
      --text: #e5e7eb;
      --muted: #94a3b8;
      --accent: #38bdf8;
      --border: rgba(255,255,255,0.08);
    }

    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: Inter, system-ui, sans-serif;
      background: linear-gradient(180deg, #020617, #0f172a);
      color: var(--text);
      line-height: 1.7;
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    header {
      padding: 5rem 1.5rem 3rem;
      text-align: center;
      border-bottom: 1px solid var(--border);
    }

    .container {
      width: min(1100px, 92%);
      margin: auto;
    }

    h1 {
      font-size: clamp(2.8rem, 6vw, 4.5rem);
      margin-bottom: 0.5rem;
    }

    .subtitle {
      color: var(--muted);
      max-width: 700px;
      margin: auto;
      font-size: 1.05rem;
    }

    .notice {
      margin: 0 auto 2rem;
      max-width: 700px;
      background: rgba(56,189,248,0.1);
      border: 1px solid rgba(56,189,248,0.25);
      padding: 1rem;
      border-radius: 1rem;
      color: #dbeafe;
    }

    nav {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 1rem;
      margin-top: 2rem;
    }

    nav a {
      padding: 0.7rem 1rem;
      border-radius: 999px;
      background: rgba(255,255,255,0.05);
      border: 1px solid var(--border);
      transition: 0.2s ease;
    }

    nav a:hover {
      background: rgba(56,189,248,0.12);
      text-decoration: none;
      transform: translateY(-2px);
    }

    section {
      padding: 5rem 0;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 2rem;
      border-left: 4px solid var(--accent);
      padding-left: 1rem;
    }

    .card {
      background: linear-gradient(180deg, var(--card), var(--card2));
      border: 1px solid var(--border);
      border-radius: 1.3rem;
      padding: 1.5rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1.5rem;
    }

    .project-card h3 {
      margin-top: 0;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 0.6rem;
      margin-top: 1rem;
    }

    .tag {
      background: rgba(56,189,248,0.15);
      color: #dbeafe;
      padding: 0.4rem 0.75rem;
      border-radius: 999px;
      font-size: 0.85rem;
      display: inline-flex;
      align-items: center;
      gap: 0.35rem;
    }

    .btn {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.75rem 1rem;
      border-radius: 0.8rem;
      background: rgba(56,189,248,0.14);
      border: 1px solid rgba(56,189,248,0.25);
      color: white;
      font-weight: 600;
      transition: 0.2s ease;
    }

    .btn:hover {
      background: rgba(56,189,248,0.25);
      transform: translateY(-2px);
      text-decoration: none;
    }

    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 1.5rem;
    }

    footer {
      padding: 3rem 1rem;
      border-top: 1px solid var(--border);
      text-align: center;
      color: var(--muted);
    }

    @media (max-width: 768px) {
      header {
        padding-top: 4rem;
      }

      section {
        padding: 3rem 0;
      }
    }
  </style>
</head>

<body>
  <header>
    <div class="container">
      <div class="notice">
        <strong>Important:</strong>
        This portfolio is still under construction and constantly being updated.
      </div>

      <h1>Hamza 👋</h1>

      <p class="subtitle">
        IIT Student • Game Developer • Software Engineer • Competitive Programmer
      </p>

      <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Tech Stack</a>
        <a href="#certifications">Certifications</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>
# ddd
  <main class="container">

    <!-- ABOUT -->
    <section id="about">
      <h2>💫 About Me</h2>

      <div class="card">
        <p>
          I am an Industrial IT student passionate about Game Development,
          Software Engineering, backend systems, machine learning, and
          performance-oriented programming.
        </p>

        <p>
          I enjoy building scalable software, gameplay systems, APIs,
          interactive experiences, and experimenting with modern technologies.
        </p>

        <a
          class="btn"
          href="https://github.com/MHamzaS45/MHamzaS45.github.io/blob/main/CV%20(2).pdf"
          target="_blank"
        >
          📄 View CV
        </a>
      </div>
    </section>

    <!-- PROJECTS -->
    <section id="projects">
      <h2>👩🏻‍💻 Featured Projects</h2>

      <div class="project-grid">

        <div class="card project-card">
          <h3>Stealth Surveillance Analytics System</h3>
          <p>
            Backend surveillance analytics system built using FastAPI,
            Docker, NumPy, and secure architecture principles.
          </p>

          <div class="tags">
            <span class="tag">FastAPI</span>
            <span class="tag">Docker</span>
            <span class="tag">Security</span>
          </div>

          <a class="btn" href="https://github.com/MHamzaS45/ssas" target="_blank">
            View Project
          </a>
        </div>

        <div class="card project-card">
          <h3>Galactic Attack</h3>
          <p>
            Unity3D arcade shooter focused on gameplay systems and enemy combat.
          </p>

          <div class="tags">
            <span class="tag">
              <i class="devicon-unity-plain"></i> Unity
            </span>
            <span class="tag">
              <i class="devicon-csharp-plain"></i> C#
            </span>
          </div>

          <a
            class="btn"
            href="https://github.com/MHamzaS45/GALACTIC-ATTACK"
            target="_blank"
          >
            View Project
          </a>
        </div>


        <div class="card project-card">
          <h3>C# Backend Rest API </h3>
          <p>
             A containerized Backend Application using ASP.NET Core 9 and C# 
          </p>

          <div class="tags">
            <span class="tag">C#</span>
            <span class="tag">Backend</span>
          </div>

          <a class="btn" href="#">
            Work In Progress
          </a>
        </div>

        <div class="card project-card">
          <h3>PyTorch Mini LLM</h3>
          <p>
            Experimental mini language model project using PyTorch and neural
            network fundamentals.
          </p>

          <div class="tags">
            <span class="tag">PyTorch</span>
            <span class="tag">Neural Networks</span>
          </div>

          <a class="btn" href="#">
            Work In Progress
          </a>
        </div>

        <div class="card project-card">
          <h3>Code Security Analyzer</h3>
          <p>
            AI-powered security analysis tool for source code using Gemini API.
          </p>

          <div class="tags">
            <span class="tag">Python</span>
            <span class="tag">Gemini API</span>
            <span class="tag">GenAI</span>
          </div>

          <a
            class="btn"
            href="https://github.com/MHamzaS45/security-code-analyzer"
            target="_blank"
          >
            View Project
          </a>
        </div>

        <div class="card project-card">
          <h3>Chaos Kitchen</h3>
          <p>
            Supercell AI Hack 2026 submission built with Three.js.
          </p>

          <div class="tags">
            <span class="tag">Three.js</span>
            <span class="tag">GameDev</span>
          </div>

          <a
            class="btn"
            href="https://github.com/MHamzaS45/Chaos-Kitchen---Supercell-AI-Hack-2026-Submission"
            target="_blank"
          >
            View Project
          </a>
        </div>

      </div>
    </section>

    <!-- SKILLS -->
    <section id="skills">
      <h2>💻 Tech Stack</h2>

      <div class="grid">
        <div class="card">
          <h3>Languages</h3>

          <div class="tags">
            <span class="tag"><i class="devicon-python-plain"></i> Python</span>
            <span class="tag"><i class="devicon-csharp-plain"></i> C#</span>
            <span class="tag"><i class="devicon-cplusplus-plain"></i> C++</span>
            <span class="tag"><i class="devicon-javascript-plain"></i> JavaScript</span>
            <span class="tag"><i class="devicon-typescript-plain"></i> TypeScript</span>
          </div>
        </div>

        <div class="card">
          <h3>Frameworks & Engines</h3>

          <div class="tags">
            <span class="tag"><i class="devicon-react-original"></i> React</span>
            <span class="tag"><i class="devicon-nodejs-plain"></i> NodeJS</span>
            <span class="tag"><i class="devicon-unity-plain"></i> Unity</span>
            <span class="tag"><i class="devicon-unrealengine-original"></i> Unreal</span>
          </div>
        </div>

        <div class="card">
          <h3>Tools</h3>

          <div class="tags">
            <span class="tag">AWS</span>
            <span class="tag">Azure</span>
            <span class="tag">Power BI</span>
            <span class="tag">Aseprite</span>
            <span class="tag">GitHub</span>
          </div>
        </div>
      </div>
    </section>

    <!-- CERTIFICATIONS -->
    <section id="certifications">
      <h2>🏅 Certifications</h2>

      <div class="grid">
        <div class="card">
          <h3>Michigan State University</h3>
          <p>Game Design & Development Specialization</p>

          <a
            class="btn"
            href="https://www.coursera.org/account/accomplishments/verify/THWH5WZQK7NA"
            target="_blank"
          >
            View Certificate
          </a>
        </div>

        <div class="card">
          <h3>Udemy</h3>
          <p>Game Development Certification</p>

          <a
            class="btn"
            href="https://www.udemy.com/certificate/UC-745407f0-2df5-4ae0-a991-c96a1ccfdbd7/"
            target="_blank"
          >
            View Certificate
          </a>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact">
      <h2>🌐 Contact</h2>

      <div class="grid">
        <div class="card">
          <h3>GitHub</h3>

          <a class="btn" href="https://github.com/MHamzaS45" target="_blank">
            Visit Profile
          </a>
        </div>

        <div class="card">
          <h3>LinkedIn</h3>

          <a
            class="btn"
            href="https://www.linkedin.com/in/hamza-sahqani-651135388/"
            target="_blank"
          >
            Connect
          </a>
        </div>

        <div class="card">
          <h3>itch.io</h3>

          <a class="btn" href="https://uwut09.itch.io/" target="_blank">
            View Games
          </a>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <p>© 2026 Hamza — Built with GitHub Pages</p>
  </footer>
</body>
</html>

