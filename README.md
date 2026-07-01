# personal-portfolio
Personal Portfolio In-progress using React, Vite and Tailwind CSS.

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<meta name="description" content="Prachi Teotia — Backend Developer & AI Integration. Building backend systems and real-world applications."/>
<title>Prachi Teotia — Backend Developer</title>
<link rel="preconnect" href="https://fonts.googleapis.com"/>
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Syne:wght@600;700;800&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet"/>

</head>
<body>

<div id="loader">
  <div class="ld-logo"><span>P</span></div>
  <div><div class="ld-name">Prachi Teotia</div><div class="ld-role">Backend Developer</div></div>
  <div class="ld-bar-wrap"><div class="ld-bar" id="lbar"></div></div>
</div>

<nav id="nav">
  <div class="nl"><span>// </span>prachi.dev</div>
  <ul class="nlinks">
    <li><a href="#about">About</a></li><li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Projects</a></li><li><a href="#experience">Experience</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
  <a href="#contact" class="ncta">Hire Me</a>
  <div class="nbg" id="burger"><span></span><span></span><span></span></div>
</nav>
<div class="mm" id="mm">
  <a href="#about" onclick="this.parentElement.classList.remove('open')">About</a>
  <a href="#skills" onclick="this.parentElement.classList.remove('open')">Skills</a>
  <a href="#projects" onclick="this.parentElement.classList.remove('open')">Projects</a>
  <a href="#experience" onclick="this.parentElement.classList.remove('open')">Experience</a>
  <a href="#contact" onclick="this.parentElement.classList.remove('open')">Contact</a>
</div>

<!-- HERO -->
<section id="hero">
  <div class="dg"></div><div class="hg1"></div><div class="hg2"></div>
  <div class="container">
    <div class="hgrid">
      <div class="htxt fu">
        <div class="sec-tag">Available for opportunities</div>
        <h1 class="hname"><span class="l1">Prachi</span><span class="l2">Teotia</span></h1>
        <div class="htags">
          <span class="htag" style="background:rgba(0,212,170,.08);border:1px solid rgba(0,212,170,.22);color:#00d4aa">Backend Developer</span>
          <span class="htag" style="background:rgba(124,58,237,.08);border:1px solid rgba(124,58,237,.22);color:#a78bfa">AI Integration</span>
          <span class="htag" style="background:rgba(96,165,250,.08);border:1px solid rgba(96,165,250,.22);color:#60a5fa">CS &amp; Design</span>
        </div>
        <p class="hdesc">I build <strong style="color:#00d4aa">backend systems</strong> and <strong style="color:#a78bfa">real-world applications</strong> — focused on clean architecture, solid API design, and solving meaningful problems through code.</p>
        <div class="hbtns">
          <a href="#projects" class="btn-p">View Projects <svg width="14" height="14" viewBox="0 0 14 14" fill="none"><path d="M2 7h10M8 4l3 3-3 3" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"/></svg></a>
          <a href="#contact" class="btn-o">Get in Touch</a>
        </div>
        <div class="hstats">
          <div><div class="sn">2+</div><div class="sl">Projects</div></div>
          <div><div class="sn">4+</div><div class="sl">Certs</div></div>
          <div><div class="sn">3mo</div><div class="sl">Experience</div></div>
          <div><div class="sn">∞</div><div class="sl">Learning</div></div>
        </div>
      </div>
     <!-- <div class="sw fu">
        <div class="samb"></div>
        <div class="sstage">
          <div class="sring ra"></div><div class="sring rb"></div><div class="sring rc"></div>
          <div class="sblob"></div><div class="sshine"></div>
        </div>
        <div class="sbadge btl"><div class="bc">Stack</div><div class="bv" style="color:#00d4aa">Node.js</div></div>
        <div class="sbadge btr"><div class="bc">Focus</div><div class="bv" style="color:#a78bfa">Backend</div></div>
        <div class="sbadge bbl"><div class="bc">Location</div><div class="bv" style="color:#60a5fa">India 🇮🇳</div></div>
        <div class="sbadge bbr"><div class="bc">Status</div><div class="bv" style="color:#00d4aa">Open ✦</div></div>
      </div>
    </div>
    <div class="scroll-h"><p>Scroll to explore</p><div class="scroll-l"></div></div>
  </div>
</section>

<!-- ABOUT -->
<section id="about" class="section">
  <div class="container">
    <div class="sec-tag fu">01 — About</div>
    <h2 class="fu" style="font-family:'Syne',sans-serif;font-weight:800;font-size:clamp(2rem,4vw,3rem);letter-spacing:-.025em;color:#fff;margin-bottom:3rem">Building with <span class="g-text">intent.</span></h2>
    <div class="agrid">
      <div class="atxt fu">
        <p>I'm a <strong>B.Tech Computer Science &amp; Design</strong> student at IMS Engineering College, Ghaziabad — actively building toward a career in backend development and software engineering.</p>
        <p>My focus is writing <strong style="color:#00d4aa">backend logic that actually works</strong> — authentication flows, relational data modeling, REST API design, and making systems communicate cleanly.</p>
        <p>I'm also exploring <strong style="color:#a78bfa">AI integration and prompt engineering</strong> — the next generation of developers needs to be fluent in both systems and AI.</p>
        <div class="ameta glass">
          <div class="amrow"><span class="amk">Education</span><span class="amv">B.Tech CS &amp; Design, IMS Engineering College</span></div>
          <div class="amrow"><span class="amk">Location</span><span class="amv">Ghaziabad, India</span></div>
          <div class="amrow"><span class="amk">Focus</span><span class="amv">Backend Development · AI Integration</span></div>
          <div class="amrow"><span class="amk">Status</span><span class="amv" style="color:#00d4aa">Open to internships &amp; fresher roles</span></div>
        </div>
      </div>
      <div class="tgrid fu">
        <div class="tcard glass"><div class="tico">⚙️</div><div class="ttl">Backend First</div><div class="tds">API design, data modeling, auth systems — logic over aesthetics.</div></div>
        <div class="tcard glass"><div class="tico">🧠</div><div class="ttl">CS Fundamentals</div><div class="tds">DSA, OS, DBMS — building with understanding, not just tutorials.</div></div>
        <div class="tcard glass"><div class="tico">⚡</div><div class="ttl">AI Aware</div><div class="tds">Prompt engineering and API-level AI — ready for the AI-native stack.</div></div>
        <div class="tcard glass"><div class="tico">📐</div><div class="ttl">System Thinker</div><div class="tds">I design how pieces connect before I write a single line of code.</div></div>
      </div>
    </div>
  </div>
</section>

<!-- SKILLS -->
<section id="skills" class="section" style="background:rgba(255,255,255,.01);border-top:1px solid var(--border);border-bottom:1px solid var(--border)">
  <div class="container">
    <div class="sec-tag fu">02 — Skills</div>
    <h2 class="fu" style="font-family:'Syne',sans-serif;font-weight:800;font-size:clamp(2rem,4vw,3rem);letter-spacing:-.025em;color:#fff;margin-bottom:3rem">Tech I work <span style="background:linear-gradient(135deg,#a78bfa,#7c3aed);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text">with.</span></h2>
    <div class="skgrid">
      <div class="skcard glass fu" style="--a:#00d4aa"><style>.skcard:nth-child(1)::before{background:#00d4aa}</style>
        <div class="ckh"><div class="cki" style="background:rgba(0,212,170,.08);border:1px solid rgba(0,212,170,.18)">⚙️</div><div><span class="ckl">Category</span><span class="ckn">Backend</span></div></div>
        <div class="sbars">
          <div class="srow"><div class="slr"><span class="sln">Node.js</span><span class="slp" style="color:#00d4aa">70%</span></div><div class="str"><div class="sf" data-w="70" style="background:linear-gradient(90deg,#00d4aa88,#00d4aa)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">Express.js</span><span class="slp" style="color:#00d4aa">70%</span></div><div class="str"><div class="sf" data-w="70" style="background:linear-gradient(90deg,#00d4aa88,#00d4aa)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">REST APIs</span><span class="slp" style="color:#00d4aa">75%</span></div><div class="str"><div class="sf" data-w="75" style="background:linear-gradient(90deg,#00d4aa88,#00d4aa)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">SQL</span><span class="slp" style="color:#00d4aa">72%</span></div><div class="str"><div class="sf" data-w="72" style="background:linear-gradient(90deg,#00d4aa88,#00d4aa)"></div></div></div>
        </div>
      </div>
      <div class="skcard glass fu"><div class="ckh"><div class="cki" style="background:rgba(167,139,250,.08);border:1px solid rgba(167,139,250,.18)">&lt;/&gt;</div><div><span class="ckl">Category</span><span class="ckn">Languages</span></div></div>
        <div class="sbars">
          <div class="srow"><div class="slr"><span class="sln">Java</span><span class="slp" style="color:#a78bfa">78%</span></div><div class="str"><div class="sf" data-w="78" style="background:linear-gradient(90deg,#a78bfa88,#a78bfa)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">JavaScript</span><span class="slp" style="color:#a78bfa">72%</span></div><div class="str"><div class="sf" data-w="72" style="background:linear-gradient(90deg,#a78bfa88,#a78bfa)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">HTML / CSS</span><span class="slp" style="color:#a78bfa">85%</span></div><div class="str"><div class="sf" data-w="85" style="background:linear-gradient(90deg,#a78bfa88,#a78bfa)"></div></div></div>
        </div>
      </div>
      <div class="skcard glass fu"><div class="ckh"><div class="cki" style="background:rgba(96,165,250,.08);border:1px solid rgba(96,165,250,.18)">🧠</div><div><span class="ckl">Category</span><span class="ckn">CS Fundamentals</span></div></div>
        <div class="sbars">
          <div class="srow"><div class="slr"><span class="sln">DSA</span><span class="slp" style="color:#60a5fa">70%</span></div><div class="str"><div class="sf" data-w="70" style="background:linear-gradient(90deg,#60a5fa88,#60a5fa)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">OOP</span><span class="slp" style="color:#60a5fa">78%</span></div><div class="str"><div class="sf" data-w="78" style="background:linear-gradient(90deg,#60a5fa88,#60a5fa)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">DBMS</span><span class="slp" style="color:#60a5fa">72%</span></div><div class="str"><div class="sf" data-w="72" style="background:linear-gradient(90deg,#60a5fa88,#60a5fa)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">Operating Systems</span><span class="slp" style="color:#60a5fa">65%</span></div><div class="str"><div class="sf" data-w="65" style="background:linear-gradient(90deg,#60a5fa88,#60a5fa)"></div></div></div>
        </div>
      </div>
      <div class="skcard glass fu"><div class="ckh"><div class="cki" style="background:rgba(232,121,249,.08);border:1px solid rgba(232,121,249,.18)">🛠</div><div><span class="ckl">Category</span><span class="ckn">Tools &amp; Cloud</span></div></div>
        <div class="sbars">
          <div class="srow"><div class="slr"><span class="sln">Git &amp; GitHub</span><span class="slp" style="color:#e879f9">80%</span></div><div class="str"><div class="sf" data-w="80" style="background:linear-gradient(90deg,#e879f988,#e879f9)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">Postman</span><span class="slp" style="color:#e879f9">75%</span></div><div class="str"><div class="sf" data-w="75" style="background:linear-gradient(90deg,#e879f988,#e879f9)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">AWS Basics</span><span class="slp" style="color:#e879f9">50%</span></div><div class="str"><div class="sf" data-w="50" style="background:linear-gradient(90deg,#e879f988,#e879f9)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">Azure Basics</span><span class="slp" style="color:#e879f9">45%</span></div><div class="str"><div class="sf" data-w="45" style="background:linear-gradient(90deg,#e879f988,#e879f9)"></div></div></div>
        </div>
      </div>
      <div class="skcard glass fu"><div class="ckh"><div class="cki" style="background:rgba(94,250,220,.06);border:1px solid rgba(94,250,220,.16)">⚡</div><div><span class="ckl">Category</span><span class="ckn">AI &amp; Analytics</span></div></div>
        <div class="sbars">
          <div class="srow"><div class="slr"><span class="sln">Prompt Engineering</span><span class="slp" style="color:#5efadc">75%</span></div><div class="str"><div class="sf" data-w="75" style="background:linear-gradient(90deg,#5efadc88,#5efadc)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">AI API Integration</span><span class="slp" style="color:#5efadc">60%</span></div><div class="str"><div class="sf" data-w="60" style="background:linear-gradient(90deg,#5efadc88,#5efadc)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">Tableau</span><span class="slp" style="color:#5efadc">55%</span></div><div class="str"><div class="sf" data-w="55" style="background:linear-gradient(90deg,#5efadc88,#5efadc)"></div></div></div>
        </div>
      </div>
      <div class="skcard glass fu"><div class="ckh"><div class="cki" style="background:rgba(96,165,250,.08);border:1px solid rgba(96,165,250,.18)">🎨</div><div><span class="ckl">Category</span><span class="ckn">Frontend</span></div></div>
        <div class="sbars">
          <div class="srow"><div class="slr"><span class="sln">React.js</span><span class="slp" style="color:#60a5fa">65%</span></div><div class="str"><div class="sf" data-w="65" style="background:linear-gradient(90deg,#60a5fa88,#60a5fa)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">Tailwind CSS</span><span class="slp" style="color:#60a5fa">70%</span></div><div class="str"><div class="sf" data-w="70" style="background:linear-gradient(90deg,#60a5fa88,#60a5fa)"></div></div></div>
          <div class="srow"><div class="slr"><span class="sln">Responsive Design</span><span class="slp" style="color:#60a5fa">80%</span></div><div class="str"><div class="sf" data-w="80" style="background:linear-gradient(90deg,#60a5fa88,#60a5fa)"></div></div></div>
        </div>
      </div>
    </div>
    <div class="mqwrap fu"><div class="mqtrack" id="mq"></div></div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects" class="section">
  <div class="container">
    <div class="sec-tag fu">03 — Projects</div>
    <h2 class="fu" style="font-family:'Syne',sans-serif;font-weight:800;font-size:clamp(2rem,4vw,3rem);letter-spacing:-.025em;color:#fff;margin-bottom:3rem">What I've <span style="background:linear-gradient(135deg,#00d4aa,#60a5fa);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text">built.</span></h2>
    <div class="plist">
      <div class="pcard glass fu" style="border:1px solid rgba(0,212,170,.12)">
        <div style="position:absolute;inset:0;background:radial-gradient(ellipse at 80% 0%,rgba(0,212,170,.06),transparent 60%);pointer-events:none;border-radius:var(--rl)"></div>
        <div class="phead">
          <div class="pbadges"><span class="pnum">01</span><span class="pbadge" style="background:rgba(0,212,170,.08);border:1px solid rgba(0,212,170,.22);color:#00d4aa">Featured</span><span class="pbadge" style="background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.07);color:rgba(255,255,255,.38)">Full Stack</span></div>
          <a href="https://github.com/PrachiTeotia1" target="_blank" class="plink" style="color:#00d4aa;border-color:rgba(0,212,170,.22);background:rgba(0,212,170,.06)"><svg width="12" height="12" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg> GitHub</a>
        </div>
        <div class="pname">SkillMate</div><div class="psub" style="color:#00d4aa">Skill Exchange Platform</div>
        <div class="pbody">
          <div><div class="psl">Problem &amp; Solution</div><p class="ptxt">Students struggle to find peers with complementary skills. SkillMate solves this with intelligent backend matching, secure auth, and real-time session management — replacing transactional platforms with community-driven collaboration.</p></div>
          <div><div class="psl">Backend Work</div><div class="ppts">
            <div class="ppt"><span class="arr" style="color:#00d4aa">→</span>Built 12+ RESTful API endpoints for auth, profiles, matching &amp; sessions</div>
            <div class="ppt"><span class="arr" style="color:#00d4aa">→</span>JWT authentication with role-based access control</div>
            <div class="ppt"><span class="arr" style="color:#00d4aa">→</span>5-table normalized MySQL schema with sub-50ms queries</div>
            <div class="ppt"><span class="arr" style="color:#00d4aa">→</span>Weighted matching algorithm improving accuracy by ~60%</div>
          </div></div>
        </div>
        <div class="pstack"><span class="spill">Node.js</span><span class="spill">Express.js</span><span class="spill">MySQL</span><span class="spill">JWT Auth</span><span class="spill">REST API</span><span class="spill">JavaScript</span><span class="spill">Git</span></div>
      </div>
      <div class="pcard glass fu" style="border:1px solid rgba(124,58,237,.12)">
        <div style="position:absolute;inset:0;background:radial-gradient(ellipse at 80% 0%,rgba(124,58,237,.07),transparent 60%);pointer-events:none;border-radius:var(--rl)"></div>
        <div class="phead">
          <div class="pbadges"><span class="pnum">02</span><span class="pbadge" style="background:rgba(124,58,237,.08);border:1px solid rgba(124,58,237,.22);color:#a78bfa">Completed</span><span class="pbadge" style="background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.07);color:rgba(255,255,255,.38)">Web App</span></div>
          <a href="https://github.com/PrachiTeotia1" target="_blank" class="plink" style="color:#a78bfa;border-color:rgba(124,58,237,.22);background:rgba(124,58,237,.06)"><svg width="12" height="12" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg> GitHub</a>
        </div>
        <div class="pname">PetHome</div><div class="psub" style="color:#a78bfa">Pet Adoption Platform</div>
        <div class="pbody">
          <div><div class="psl">Problem &amp; Solution</div><p class="ptxt">Stray animals lack a digital channel to reach adopters. PetHome bridges this with structured listings, smart filtering, and a multi-step adoption flow — making the process accessible and organized for shelters and adopters alike.</p></div>
          <div><div class="psl">What I Built</div><div class="ppts">
            <div class="ppt"><span class="arr" style="color:#a78bfa">→</span>Dynamic multi-filter search (species, age, location) in vanilla JS</div>
            <div class="ppt"><span class="arr" style="color:#a78bfa">→</span>3-step validated adoption form handling 20+ listings</div>
            <div class="ppt"><span class="arr" style="color:#a78bfa">→</span>Real-time status system (Available / Pending / Adopted)</div>
            <div class="ppt"><span class="arr" style="color:#a78bfa">→</span>Zero bugs across Chrome, Firefox &amp; Edge</div>
          </div></div>
        </div>
        <div class="pstack"><span class="spill">HTML5</span><span class="spill">CSS3</span><span class="spill">JavaScript</span><span class="spill">Responsive Design</span><span class="spill">Git</span></div>
      </div>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience" class="section" style="background:rgba(255,255,255,.012);border-top:1px solid var(--border);border-bottom:1px solid var(--border)">
  <div class="container">
    <div class="sec-tag fu">04 — Experience</div>
    <h2 class="fu" style="font-family:'Syne',sans-serif;font-weight:800;font-size:clamp(2rem,4vw,3rem);letter-spacing:-.025em;color:#fff;margin-bottom:3rem">Where I've <span style="background:linear-gradient(135deg,#60a5fa,#a78bfa);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text">worked.</span></h2>
    <div class="egrid">
      <div class="etl fu">
        <div class="eti">
          <div class="edot"></div>
          <div class="edate">Nov 2024 — Jan 2025</div>
          <div class="erole">Web Development Intern</div>
          <div class="eco">@ <span class="cn">ContentTree</span> · <span class="cl">Noida, India</span></div>
          <p class="edesc">Contributed to production web development — working on real client-facing code, iterating on live websites, and managing content publishing workflows in a professional team environment.</p>
          <ul class="ebuls">
            <li>Developed 3+ client-facing web pages, improving UI consistency across sections</li>
            <li>Maintained 10+ post content publishing pipeline, cutting turnaround by 25%</li>
            <li>Resolved cross-browser layout bugs across Chrome, Firefox &amp; Edge — ~40% reduction</li>
            <li>Collaborated with a team of 4 using Git, pull requests &amp; code reviews</li>
          </ul>
          <div class="echips"><span class="echip">HTML</span><span class="echip">CSS</span><span class="echip">JavaScript</span><span class="echip">Git</span><span class="echip">CMS</span></div>
        </div>
      </div>
      <div class="spanel fu">
        <div>
          <div class="sphead">Education</div>
          <div class="ecards">
            <div class="ecard glass" style="border:1px solid rgba(167,139,250,.18)"><div class="edeg" style="color:#a78bfa">B.Tech · CS &amp; Design</div><div class="esc">IMS Engineering College</div><div class="emeta">Sep 2023 – Present · Ghaziabad · AKTU</div></div>
            <div class="ecard glass" style="border:1px solid rgba(96,165,250,.18)"><div class="edeg" style="color:#60a5fa">Class XII · Science</div><div class="esc">S.C.A. Memo. Sr. Sec. School</div><div class="emeta">2022 – 2023 · Percentage: 83.6%</div></div>
          </div>
        </div>
        <div>
          <div class="sphead">Certifications</div>
          <div class="clist">
            <div class="citem" style="border-left-color:#00d4aa;background:rgba(0,212,170,.03)"><div><div class="cn2">HTML &amp; CSS Bootcamp</div><div class="cd">Nov 2024</div></div></div>
            <div class="citem" style="border-left-color:#a78bfa;background:rgba(167,139,250,.03)"><div><div class="cn2">JavaScript Bootcamp</div><div class="cd">Nov 2024</div></div></div>
            <div class="citem" style="border-left-color:#60a5fa;background:rgba(96,165,250,.03)"><div><div class="cn2">Git &amp; GitHub Bootcamp</div><div class="cd">Dec 2024</div></div></div>
            <div class="citem" style="border-left-color:#e879f9;background:rgba(232,121,249,.03)"><div><div class="cn2">Postman API Fundamentals — Student Expert</div><div class="cd">2024</div></div></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="section">
  <div class="container">
    <div class="sec-tag fu">05 — Contact</div>
    <div class="cgrid">
      <div class="fu">
        <h2 class="chl">Let's build<br/><span class="g-text">something.</span></h2>
        <p class="cdesc">I'm actively looking for internship and fresher opportunities in backend development. If you have a project, team, or role that aligns — let's talk.</p>
        <a href="mailto:prachiteotia19@gmail.com" class="btn-p">Send an Email <svg width="14" height="14" viewBox="0 0 14 14" fill="none"><path d="M2 7h10M8 4l3 3-3 3" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"/></svg></a>
      </div>
      <div class="fu">
        <div class="clinks">
          <a href="mailto:prachiteotia19@gmail.com" class="clink glass" style="border:1px solid rgba(255,255,255,.07)"><div class="cci" style="background:rgba(0,212,170,.07);border:1px solid rgba(0,212,170,.18);color:#00d4aa">@</div><div><span class="ccl">Email</span><span class="ccv">prachiteotia19@gmail.com</span></div><span class="cca">→</span></a>
          <a href="https://linkedin.com/in/prachi-teotia-094b07292" target="_blank" class="clink glass" style="border:1px solid rgba(255,255,255,.07)"><div class="cci" style="background:rgba(96,165,250,.07);border:1px solid rgba(96,165,250,.18);color:#60a5fa">in</div><div><span class="ccl">LinkedIn</span><span class="ccv">prachi-teotia-094b07292</span></div><span class="cca">→</span></a>
          <a href="https://github.com/PrachiTeotia1" target="_blank" class="clink glass" style="border:1px solid rgba(255,255,255,.07)"><div class="cci" style="background:rgba(167,139,250,.07);border:1px solid rgba(167,139,250,.18);color:#a78bfa">&lt;/&gt;</div><div><span class="ccl">GitHub</span><span class="ccv">PrachiTeotia1</span></div><span class="cca">→</span></a>
          <a href="tel:+919927420020" class="clink glass" style="border:1px solid rgba(255,255,255,.07)"><div class="cci" style="background:rgba(232,121,249,.07);border:1px solid rgba(232,121,249,.18);color:#e879f9">☎</div><div><span class="ccl">Phone</span><span class="ccv">+91 9927420020</span></div><span class="cca">→</span></a>
        </div>
        <div class="locnote"><p>Based in</p><strong>Ghaziabad, India 🇮🇳</strong><em>Open to remote &amp; on-site roles</em></div>
      </div>
    </div>
  </div>
</section>

<footer class="container">
  <div class="flm"><div class="flmk"><span>P</span></div><span class="fcp">© 2025 Prachi Teotia</span></div>
  <div class="fst"><div class="fdot"></div>Available for opportunities</div>
  <div class="fbu">Pure HTML · CSS · JavaScript</div>
</footer>

<script>

</script>
</body>
</html>
