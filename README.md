<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Hamza | IIT  · Game Developer . Software Engineer . Competitive Coder </title>
  <meta name="description" content="Portfolio of IT work done by Hamza" />

  <style>
    :root {
      --bg: #020617;
      --card: #0f172a;
      --text: #e5e7eb;
      --muted: #9ca3af;
      --accent: #38bdf8;
      --focus: #22d3ee;                      <! A color palette that signifies maturity and composure >
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Arial, sans-serif;     <! A nice font for a sleek design >
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
      gap: 0.4rem;
      margin-top: 0.5rem;
    }

    .tag {
      font-size: 0.75rem;
      padding: 0.25rem 0.5rem;
      border-radius: 999px;
      background: rgba(56,189,248,0.18);
      color: #e0f2fe;
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
    IIT student passionate about <strong>Game Development</strong> and <strong>Software Engineering</strong>,
    with a strong focus on Unity, C#, and building innovative interactive systems.
  </p>

  <nav aria-label="Primary navigation">
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#skills">Tech Stack and Tools</a>
    <a href="#certifications">Certifications</a>
    <a href="#github">GitHub</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
  <section id="about">
    <h2>💫 About Me</h2>
    <div class="card">
      <p>
        I am a student majoring in Industrial IT, actively working on developing innovative solutions—
        whether that means engineering complex game mechanics or solving real-world
        system design problems, with the help of skills and knowledge that I have obtained from different aspects of my life.
      </p>
      <p>
        I enjoy building interactive experiences using modern tools and frameworks,
        and I constantly seek opportunities to deepen my understanding of
        game engines, software architecture, systems design, performance-oriented programming as well as machine learning capabilities.
      </p>
    </div>
  </section>

  <section id="projects">
    <h2> 👩🏻‍💻📓✍🏻💡 Projects 👩🏻‍💻📓✍🏻💡 </h2>
    <div class="grid">
      <div class="card">
        <h3>Projects</h3>
        <p>
          A collection of Unity-based games and prototypes exploring mechanics,
          physics systems, and gameplay architecture.
        </p>
        <div class="tags">
          <span class="tag">Unity</span>
          <span class="tag">C#</span>
          <span class="tag">Game Development and Design</span>
          <span class ="tag">Pixel Art (with Aseprite)</span>
        </div>
      </div>
      <div class="card">
        <h3>Software & Engineering Work</h3>
        <p>
          Software engineering projects focusing on problem solving, data handling,
          APIs, and scalable application logic.
        </p>
        <div class="tags">
          <span class="tag">![JavaScript]</span>
          <span class="tag">![Python]</span>
          <span class="tag">![C++]</span>
        </div>
      </div>
    </div>
  </section>

  <section id="skills">
    <h2>💻 Tech Stack & Tools 💻 </h2>
    <div class="card">
      <p><strong>Languages:</strong> ![C#], ![C++], ![JavaScript], ![TypeScript], ![Python]</p>
      <p><strong>Frameworks & Engines:</strong> ![Unity, ![Unreal Engine, ![React, ![Node.js]</p>
      <p><strong>Tools:</strong> ![GitHub, ![Azure, ![Power BI], ![Pandas], ![Aseprite], ![Libresprite], ![Adobe Photoshop], [Premiere Pro]</p>
      <p><strong>Platforms:</strong> ![Itch.io], ![Xbox]</p>
    </div>
  </section>

  <section id="certifications">
  <h2>🏵️ Certifications 🏵️ </h2>
  <div class = "card">
      <p>
        <strong>Game Design and Development Specialization 1</strong> 
        <a href="https://www.coursera.org/account/accomplishments/verify/THWH5WZQK7NA" t
        
                                                                         
      </p>

  <section id="github">
    <h2>📊 GitHub</h2>
    <div class="card">
      <p>
        Explore repositories of projects, commits, and ongoing work done by me on GitHub.
      </p>
      <p>
        👉 <a href="https://github.com/MHamzaS45" target="_blank" rel="noopener">github.com/MHamzaS45</a>
      </p>
    </div>
  </section>

  <section id="contact">
    <h2>🌐 Contact 🌐 </h2>
    <div class="card">
      <p>
        Connect with me on LinkedIn:
      </p>
      <p>
        [in] <a href="https://www.linkedin.com/in/hamza-sahqani-651135388/" target="_blank" rel="noopener"> LinkedIn </a>
      </p>
      <p>
        Follow on itch.io
        🕹️ <a href="https://uwut09.itch.io/" target = "_blank" rel="noopener"> Itch.io </a>
     </p>
    </div>
  </section>
</main>

<footer>
  <p>
    ©  Hosted on GitHub Pages
  </p>  
</footer>

</body>
</html>
