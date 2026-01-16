<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Hamza | IIT · Game Developer · Software Engineer · Competitive Coder</title>
  <meta name="description" content="Portfolio of IT work done by Hamza" />

 
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">  <!-- Devicon icons -->

  <style>
    :root {
      --bg: #020617;
      --card: #0f172a;
      --text: #e5e7eb;
      --muted: #9ca3af;
      --accent: #38bdf8;
      --focus: #22d3ee; /* Makes for a mature & composed color palette */
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Arial, sans-serif;
      background: linear-gradient(180deg, #020617, #020617 30%, var(--bg));
      color: var(--text);
      line-height: 1.65;
    }

    a { color: var(--accent); text-decoration: none; }
    a:hover, a:focus { text-decoration: underline; }
    a:focus-visible { outline: 3px solid var(--focus); outline-offset: 3px; }

    header, main, footer {
      max-width: 1100px;
      margin: auto;
      padding: 1.5rem;
    }

    header h1 {
      font-size: clamp(2.2rem, 4vw, 3rem);
      margin-bottom: 0.5rem;
    }

    header p { color: var(--muted); max-width: 720px; }

    nav {
      margin-top: 1.5rem;
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
    }

    nav a {
      background: rgba(56,189,248,0.12);
      padding: 0.45rem 0.75rem;
      border-radius: 0.5rem;
      font-size: 0.9rem;
      font-weight: 600;
    }

    section { margin-top: 3rem; }

    section h2 {
      font-size: 1.75rem;
      margin-bottom: 1rem;
      border-left: 4px solid var(--accent);
      padding-left: 0.75rem;
    }

    .card {
      background: linear-gradient(180deg, rgba(255,255,255,0.04), rgba(255,255,255,0.01));
      border: 1px solid rgba(255,255,255,0.08);
      border-radius: 1rem;
      padding: 1.25rem;
      margin-bottom: 1rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 1.25rem;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-top: 0.5rem;
    }

    .tag {
      font-size: 0.8rem;
      padding: 0.35rem 0.6rem;
      border-radius: 999px;
      background: rgba(56,189,248,0.18);
      color: #e0f2fe;
      display: inline-flex;
      align-items: center;
      gap: 0.35rem;
    }

    .tag i {
      font-size: 1rem;
    }

    footer {
      margin-top: 4rem;
      border-top: 1px solid rgba(255,255,255,0.08);
      text-align: center;
      color: var(--muted);
      font-size: 0.85rem;
    }
  </style>
</head>

<body>

<header>
  <h1>Hi, I am Hamza 👋</h1>
  <p>
    IIT student passionate about Game Development and Software Engineering,
    with a strong focus on Unity, C#, and building innovative interactive systems.
  </p>

  <nav aria-label="Primary navigation">
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#skills">Tech Stack</a>
    <a href="#certifications">Certifications</a>
    <a href="#github">GitHub</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
  
<!--ABOUTME-->
<section id="about">
  <h2>💫 About Me</h2>
  <div class="card">
    <p>
      I am an Industrial IT student who enjoys developing complex game mechanics,
      solving real-world system design problems, and engineering interactive experiences.
    </p>
    <p>
      My interests include software architecture, systems design, game engines, machine learning and
      performance-oriented programming fit for collaborative work.
    </p>
  </div>
</section>

<!-- PROJECTS-->
<section id="projects">
  <h2>👩🏻‍💻 Projects</h2>
  <div class="grid">
    <div class="card">
      <h3>Game Development</h3>
      <p>Unity-based games and gameplay prototypes.</p>
      <div class="tags">
        <span class="tag"><i class="devicon-unity-plain"></i> Unity</span>
        <span class="tag"><i class="devicon-csharp-plain"></i> C#</span>
        <span class="tag">🎨 Pixel Art</span>
      </div>
    </div>
    <div class="card">
      <h3>Software Engineering</h3>
      <p>Problem solving, APIs, and scalable application logic.</p>
      <div class="tags">
        <span class="tag"><i class="devicon-javascript-plain"></i> JavaScript</span>
        <span class="tag"><i class="devicon-python-plain"></i> Python</span>
        <span class="tag"><i class="devicon-cplusplus-plain"></i> C++</span>
      </div>
    </div>
  </div>
</section>

<!-- SKILLS-->
<section id="skills">
  <h2>💻 Tech Stack & Tools</h2>
  <div class="card">
    <p><strong>Languages:</strong></p>
    <div class="tags">
      <span class="tag"><i class="devicon-csharp-plain"></i> C#</span>
      <span class="tag"><i class="devicon-cplusplus-plain"></i> C++</span>
      <span class="tag"><i class="devicon-javascript-plain"></i> JavaScript</span>
      <span class="tag"><i class="devicon-typescript-plain"></i> TypeScript</span>
      <span class="tag"><i class="devicon-python-plain"></i> Python</span>
    </div>
    <p><strong>Frameworks & Engines:</strong></p>
    <div class="tags">
      <span class="tag"><i class="devicon-unity-plain"></i> Unity</span>
      <span class="tag"><i class="devicon-unrealengine-original"></i> Unreal</span>
      <span class="tag"><i class="devicon-react-original"></i> React</span>
      <span class="tag"><i class="devicon-nodejs-plain"></i> Node.js</span>
      <span class="tag">🛠 Visual Studio</span>
      <span class="tag">📝 VS Code</span>
    </div>
    <p><strong>Tools:</strong></p>
    <div class="tags">
      <span class="tag"><i class="devicon-github-original"></i> GitHub</span>
      <span class="tag"><i class="devicon-azure-plain"></i> Azure</span>
      <span class="tag">📊 Power BI</span>
      <span class="tag">🎨 Aseprite</span>
      <span class="tag">🎬 Premiere Pro</span>
    </div>
  </div>
</section>

<!--CERTIFICATES-->
<section id="certifications">
  <h2>🏵️ Certifications</h2>
  <div class="card">
    <p><strong>Game Design & Development Specialization 1</strong></p>
    <img src="https://img.shields.io/badge/Michigan%20State%20University-Coursera-005DAA?style=for-the-badge&logo=coursera&logoColor=white" alt="GD Certificate">
    <p>
      <a href="https://www.coursera.org/account/accomplishments/verify/THWH5WZQK7NA" target="_blank" rel="noopener">
        🔗 View Certificate
      </a>
    </p>
    <img src="https://img.shields.io/badge/Udemy-Course-A435F0?style=for-the-badge&logo=udemy&logoColor=white" alt="Udemy Certificate">
    <p>
      <a href="https://www.udemy.com/certificate/UC-745407f0-2df5-4ae0-a991-c96a1ccfdbd7/" target="_blank" rel="noopener">
        🔗 View Certificate
      </a>
    </p>
    <img src="https://img.shields.io/badge/University%20of%20Turku-Finland-003580?style=for-the-badge" alt="University of Turku">
    <p>
      <a href="https://www.linkedin.com/in/hamza-sahqani-651135388/" target="_blank" rel="noopener">
        🔗 View Certificate
      </a>
    </p>
  </div>
</section>

<!--gitHub-->
<section id="github">
  <h2>📊 GitHub</h2>
  <div class="card">
    👉 <a href="https://github.com/MHamzaS45" target="_blank" rel="noopener">
      github.com/MHamzaS45
    </a>
  </div>
</section>

<!--CONTACT-->
<section id="contact">
  <h2>🌐 Contact</h2>
  <div class="card">
    <p>
      <a href="https://www.linkedin.com/in/hamza-sahqani-651135388/" target="_blank" rel="noopener">
        🔗 LinkedIn
      </a>
    </p>
    <p>
      <a href="https://uwut09.itch.io/" target="_blank" rel="noopener">
        🕹️ itch.io
      </a>
    </p>
  </div>
</section>

</main>

<footer>
  <p>© Hosted on GitHub Pages</p>
</footer>

</body>
</html>
