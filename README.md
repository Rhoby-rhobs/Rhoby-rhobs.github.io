<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Robelynne Sheanne Clarete — Administrative Support Specialist</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Newsreader:ital,wght@0,400;0,500;1,400;1,500&family=Public+Sans:wght@400;500;600;700;800&family=IBM+Plex+Mono:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg: #FBF9F4;
    --bg-panel: #F1EEE4;
    --ink: #23262A;
    --ink-soft: #5C6167;
    --sage: #3E6A5C;
    --sage-deep: #2B4C42;
    --sage-soft: #DEE8E3;
    --ochre: #A6702C;
    --berry: #A75468;
    --berry-soft: #F3DEE3;
    --sky: #3F6C8C;
    --sky-soft: #DCE7EE;
    --line: #E1DCCC;
    --card-bg: #FFFFFF;
    --radius: 14px;
  }

  * { box-sizing: border-box; }
  html{ scroll-behavior: smooth; }

  body{
    margin: 0;
    background: var(--bg);
    color: var(--ink);
    font-family: "Public Sans", -apple-system, sans-serif;
    font-size: 16px;
    line-height: 1.62;
    -webkit-font-smoothing: antialiased;
  }

  .wrap{ max-width: 900px; margin: 0 auto; padding: 0 28px; }

  .hero{ padding: 60px 0 20px; }
  .hero-grid{ display: grid; grid-template-columns: 220px 1fr; gap: 40px; align-items: center; }
  .photo-wrap{ position: relative; }
  .photo-frame{
    width: 200px; height: 200px; border-radius: 28px; overflow: hidden;
    border: 3px solid var(--card-bg); box-shadow: 0 10px 30px rgba(43,76,66,0.18);
    transform: rotate(-3deg); background: var(--sage-soft);
  }
  .photo-frame img{ width: 100%; height: 100%; object-fit: cover; display: block; }
  .photo-sticker{
    position: absolute; bottom: -12px; right: -16px; background: var(--ochre); color: #FFF9EE;
    font-family: "IBM Plex Mono", monospace; font-size: 11px; font-weight: 600; letter-spacing: 0.04em;
    padding: 7px 12px; border-radius: 30px; transform: rotate(6deg); box-shadow: 0 6px 14px rgba(166,112,44,0.35);
  }
  .eyebrow{
    font-family: "IBM Plex Mono", monospace; font-size: 12.5px; text-transform: uppercase; letter-spacing: 0.13em;
    color: var(--sage-deep); display: inline-flex; align-items: center; gap: 8px; margin-bottom: 14px;
  }
  .eyebrow::before{ content:""; width:7px; height:7px; background: var(--sage); border-radius:50%; display:inline-block; }
  h1{
    font-family: "Public Sans", sans-serif; font-weight: 800; font-size: clamp(30px, 5vw, 44px);
    letter-spacing: -0.02em; line-height: 1.06; margin: 0 0 10px;
  }
  .squiggle-phrase{ position: relative; white-space: nowrap; }
  .squiggle-phrase svg{ position: absolute; left: 0; bottom: -8px; width: 100%; height: 12px; }
  .role-line{ font-family: "Newsreader", serif; font-style: italic; font-size: clamp(16px, 2.2vw, 19px); color: var(--sage-deep); margin: 0 0 18px; }
  .contact-row{ display: flex; flex-wrap: wrap; gap: 9px; }
  .chip{
    font-family: "IBM Plex Mono", monospace; font-size: 12.5px; color: var(--ink); background: var(--card-bg);
    border: 1px solid var(--line); padding: 8px 13px; border-radius: 20px; text-decoration: none;
    display: inline-flex; align-items: center; gap: 7px; transition: border-color .15s ease, transform .15s ease;
  }
  .chip:hover{ border-color: var(--sage); transform: translateY(-1px); }
  .chip .dot{ width: 6px; height: 6px; border-radius: 50%; background: var(--sage); flex-shrink: 0; }
  .cta-btns{ display:flex; gap: 10px; flex-wrap: wrap; margin-top: 16px; }
  .btn{
    font-family: "IBM Plex Mono", monospace; font-size: 13.5px; text-decoration: none; padding: 11px 20px;
    border-radius: 30px; transition: transform .15s ease; display: inline-flex; align-items: center; gap: 8px;
  }
  .btn-primary{ background: var(--sage-deep); color: #F4F1E8; }
  .btn-secondary{ background: var(--card-bg); color: var(--ink); border: 1px solid var(--line); }
  .btn:hover{ transform: translateY(-2px); }

  @media (max-width: 620px){
    .hero-grid{ grid-template-columns: 1fr; text-align: center; }
    .photo-wrap{ justify-self: center; }
    .contact-row, .cta-btns{ justify-content: center; }
  }

  .stat-strip{ padding: 40px 0 10px; }
  .stat-grid{ display: grid; grid-template-columns: repeat(4,1fr); gap: 14px; }
  .stat{ background: var(--card-bg); border: 1px solid var(--line); border-radius: var(--radius); padding: 18px 16px; text-align: center; }
  .stat .icon{ font-size: 20px; display:block; margin-bottom: 8px; }
  .stat .num{ font-family: "IBM Plex Mono", monospace; font-size: 24px; font-weight: 600; color: var(--ochre); display:block; margin-bottom: 4px; }
  .stat .label{ font-size: 12.5px; color: var(--ink-soft); line-height: 1.3; }
  @media (max-width: 620px){ .stat-grid{ grid-template-columns: repeat(2,1fr); } }

  section{ padding: 46px 0; }
  .section-head{ display:flex; align-items:baseline; gap:12px; margin-bottom:22px; }
  .section-head .icon{ font-size: 18px; }
  .section-head h2{ font-size: 21px; font-weight: 700; letter-spacing:-0.01em; margin:0; }

  .about-text{ max-width: 640px; color: var(--ink-soft); font-size: 16px; }

  .tag-cluster{ display:flex; flex-wrap:wrap; gap:10px; }
  .tag{ background: var(--sage-soft); color: var(--sage-deep); font-size: 13.5px; font-weight: 600; padding: 8px 14px; border-radius: 20px; }
  .tag.alt{ background: var(--sky-soft); color: var(--sky); }
  .tag.alt2{ background: var(--berry-soft); color: var(--berry); }

  .tool-grid{ display:flex; flex-wrap:wrap; gap: 10px; }
  .sticky{
    font-family: "IBM Plex Mono", monospace; font-size: 12.5px; color: var(--ink); background: var(--card-bg);
    border: 1px solid var(--line); padding: 8px 12px; border-radius: 8px; box-shadow: 0 3px 8px rgba(35,38,42,0.05);
  }
  .sticky:nth-child(3n){ transform: rotate(-2deg); }
  .sticky:nth-child(3n+1){ transform: rotate(1.5deg); }
  .sticky:nth-child(3n+2){ transform: rotate(-1deg); }

  .process-row{ display:grid; grid-template-columns: repeat(3,1fr); gap: 16px; }
  .process-step{ background: var(--card-bg); border: 1px solid var(--line); border-radius: var(--radius); padding: 22px 20px; }
  .process-step .step-num{
    font-family: "IBM Plex Mono", monospace; font-size: 12px; color: var(--sage); background: var(--sage-soft);
    display: inline-block; padding: 4px 9px; border-radius: 12px; margin-bottom: 12px;
  }
  .process-step h3{ font-size: 16px; margin: 0 0 8px; }
  .process-step p{ font-size: 14px; color: var(--ink-soft); margin: 0; }
  @media (max-width: 700px){ .process-row{ grid-template-columns: 1fr; } }

  .job-card{
    background: var(--card-bg); border: 1px solid var(--line); border-left: 4px solid var(--sage);
    border-radius: var(--radius); padding: 26px 28px; margin-bottom: 20px;
  }
  .job-card:last-child{ margin-bottom: 0; }
  .job-status{
    display:inline-block; font-family:"IBM Plex Mono", monospace; font-size:11px; letter-spacing:0.06em;
    text-transform:uppercase; color: var(--sage-deep); background: var(--sage-soft); padding:3px 10px; border-radius:20px; margin-bottom:12px;
  }
  .job-title{ font-size:17.5px; font-weight:700; margin:0 0 4px; }
  .job-org{ color: var(--sage-deep); font-weight:600; }
  .job-list{ margin:12px 0 14px; padding:0; list-style:none; }
  .job-list li{ position:relative; padding-left:20px; margin-bottom:8px; font-size:14.5px; }
  .job-list li::before{ content:"→"; position:absolute; left:0; color:var(--sage); font-size:13px; }
  .achievements{ border-top:1px dashed var(--line); padding-top:14px; }
  .a-label{ font-family:"IBM Plex Mono", monospace; font-size:11px; text-transform:uppercase; letter-spacing:0.1em; color:var(--ink-soft); margin-bottom:9px; }
  .a-item{ display:flex; gap:11px; margin-bottom:7px; font-size:14px; align-items:baseline; }
  .a-item .mark{ font-family:"IBM Plex Mono", monospace; color:var(--ochre); font-weight:600; flex-shrink:0; }

  .fact-grid{ display:grid; grid-template-columns: repeat(3,1fr); gap: 14px; }
  .fact-card{ background: var(--berry-soft); border-radius: var(--radius); padding: 18px 18px; font-size: 13.5px; color: var(--berry); border: 1px dashed var(--berry); }
  .fact-card .icon{ font-size: 18px; display:block; margin-bottom: 8px; }
  @media (max-width: 700px){ .fact-grid{ grid-template-columns: 1fr 1fr; } }
  @media (max-width: 460px){ .fact-grid{ grid-template-columns: 1fr; } }

  .testimonial{
    background: var(--sky-soft); border-radius: var(--radius); padding: 26px 28px;
    font-family: "Newsreader", serif; font-style: italic; font-size: 17px; color: var(--sky);
  }
  .testimonial cite{ display:block; margin-top: 14px; font-family:"IBM Plex Mono", monospace; font-style: normal; font-size: 12.5px; color: var(--ink-soft); }

  .edu-row{
    display:flex; justify-content:space-between; align-items:baseline; flex-wrap:wrap; gap:10px;
    background: var(--card-bg); border:1px solid var(--line); border-radius: var(--radius); padding: 20px 24px;
  }
  .edu-row .deg{ font-weight:700; font-size:15.5px; }
  .edu-row .school{ color: var(--ink-soft); font-size:14px; }
  .edu-row .yr{ font-family:"IBM Plex Mono", monospace; font-size:13px; color: var(--ink-soft); }

  footer{ padding: 50px 0 64px; text-align:center; }
  .foot-note{ margin-top: 30px; font-size:12.5px; color: var(--ink-soft); font-family:"IBM Plex Mono", monospace; }

  .reveal{ opacity:0; transform: translateY(14px); transition: opacity .6s ease, transform .6s ease; }
  .reveal.in{ opacity:1; transform: translateY(0); }
  @media (prefers-reduced-motion: reduce){ .reveal{ opacity:1; transform:none; transition:none; } html{ scroll-behavior:auto; } }

  a:focus-visible, .chip:focus-visible, .btn:focus-visible{ outline: 2px solid var(--sage-deep); outline-offset: 2px; }
</style>
</head>
<body>

<header class="hero">
  <div class="wrap">
    <div class="hero-grid">
      <div class="photo-wrap reveal">
        <div class="photo-frame">
          <img src="photo.jpg" alt="Robelynne Sheanne Clarete">
        </div>
        <div class="photo-sticker">open to work</div>
      </div>
      <div>
        <div class="eyebrow">Administrative Support Specialist</div>
        <h1>Hi, I'm Robelynne — I keep <span class="squiggle-phrase">remote teams<svg viewBox="0 0 200 12" preserveAspectRatio="none"><path d="M2 8 Q 25 2, 50 8 T 100 8 T 150 8 T 198 8" fill="none" stroke="#A6702C" stroke-width="3" stroke-linecap="round"/></svg></span> running on time.</h1>
        <p class="role-line">10+ years of workflow coordination, documentation & database management, remote operations.</p>
        <div class="contact-row">
          <a class="chip" href="mailto:ev.robelynnedelapaz@gmail.com"><span class="dot"></span>ev.robelynnedelapaz@gmail.com</a>
          <a class="chip" href="tel:+639156243162"><span class="dot"></span>+63 915 624 3162</a>
          <span class="chip"><span class="dot"></span>Philippines · Remote</span>
          <a class="chip" href="#" id="linkedin-chip"><span class="dot"></span>LinkedIn — add your URL</a>
        </div>
        <div class="cta-btns">
          <a class="btn btn-primary" href="mailto:ev.robelynnedelapaz@gmail.com">✉️ Let's talk</a>
          <a class="btn btn-secondary" href="#" id="resume-link">⬇️ Download résumé (add link)</a>
        </div>
      </div>
    </div>
  </div>
</header>

<div class="stat-strip">
  <div class="wrap">
    <div class="stat-grid reveal">
      <div class="stat"><span class="icon">🗂️</span><span class="num">10+</span><span class="label">years in admin & ops support</span></div>
      <div class="stat"><span class="icon">✅</span><span class="num">300+</span><span class="label">pages kept at 98–99% accuracy</span></div>
      <div class="stat"><span class="icon">📈</span><span class="num">95%</span><span class="label">team productivity gain</span></div>
      <div class="stat"><span class="icon">⚡</span><span class="num">50%+</span><span class="label">less drafting time via AI workflows</span></div>
    </div>
  </div>
</div>

<section>
  <div class="wrap">
    <div class="section-head reveal"><span class="icon">👋</span><h2>About</h2></div>
    <p class="about-text reveal">I support daily business operations for remote teams — coordinating tasks, managing documentation and databases, and keeping cross-functional work moving without things slipping through the cracks. Colleagues know me for accuracy under volume, clear communication, and a habit of improving the process rather than just completing the task in front of me. I'm currently open to my next role after my previous position was made redundant.</p>
  </div>
</section>

<section>
  <div class="wrap">
    <div class="section-head reveal"><span class="icon">🧩</span><h2>Core Skills</h2></div>
    <div class="tag-cluster reveal">
      <span class="tag">Ops Coordination</span>
      <span class="tag alt">Workflow & Task Management</span>
      <span class="tag alt2">Calendar Coordination</span>
      <span class="tag">Stakeholder Communication</span>
      <span class="tag alt">Documentation & Databases</span>
      <span class="tag alt2">Process Improvement</span>
      <span class="tag">Reporting & QA</span>
      <span class="tag alt">Cross-functional Collaboration</span>
      <span class="tag alt2">Data Accuracy & Compliance</span>
      <span class="tag">CMS & Content Management</span>
      <span class="tag alt">Problem-Solving & Multitasking</span>
    </div>
  </div>
</section>

<section>
  <div class="wrap">
    <div class="section-head reveal"><span class="icon">🛠️</span><h2>Tools & Platforms</h2></div>
    <div class="tool-grid reveal">
      <span class="sticky">WordPress</span><span class="sticky">Niche Builder</span><span class="sticky">Jira</span>
      <span class="sticky">Confluence</span><span class="sticky">Google Analytics</span><span class="sticky">Search Console</span>
      <span class="sticky">SEMRush</span><span class="sticky">Ahrefs</span><span class="sticky">Qualtrics</span>
      <span class="sticky">Datawrapper</span><span class="sticky">Figma</span><span class="sticky">Canva</span>
      <span class="sticky">Photoshop</span><span class="sticky">Google Workspace</span><span class="sticky">Microsoft 365</span>
      <span class="sticky">Slack</span><span class="sticky">Intercom</span><span class="sticky">Trello</span>
      <span class="sticky">Xero</span><span class="sticky">ChatGPT</span><span class="sticky">Gemini</span><span class="sticky">Copilot</span>
    </div>
  </div>
</section>

<section>
  <div class="wrap">
    <div class="section-head reveal"><span class="icon">🔄</span><h2>How I Work</h2></div>
    <div class="process-row reveal">
      <div class="process-step">
        <span class="step-num">01 — Understand</span>
        <h3>Get the full picture</h3>
        <p>Learn the workflow, tools, and priorities before touching anything, so fixes don't create new problems.</p>
      </div>
      <div class="process-step">
        <span class="step-num">02 — Organize</span>
        <h3>Build the system</h3>
        <p>Set up the documentation, calendars, and processes that keep the work visible and on schedule.</p>
      </div>
      <div class="process-step">
        <span class="step-num">03 — Deliver</span>
        <h3>Run it reliably</h3>
        <p>Keep it accurate day to day, catch issues early, and report clearly on what's done and what's next.</p>
      </div>
    </div>
  </div>
</section>

<section>
  <div class="wrap">
    <div class="section-head reveal"><span class="icon">💼</span><h2>Experience</h2></div>

    <div class="job-card reveal">
      <div class="job-status">Jul 2023 – Apr 2026</div>
      <h3 class="job-title">Publishing Support Team Lead <span class="job-org">— Finder</span></h3>
      <ul class="job-list">
        <li>Led daily publishing support operations — workload prioritisation, task delegation, team coaching, and performance monitoring.</li>
        <li>Managed end-to-end content operations across insurance pages, keeping updates accurate, timely, SEO-aligned, and compliant.</li>
        <li>Partnered with Product, Engineering, and Publishing teams on site rebranding, CMS improvements, and database-driven page migrations.</li>
        <li>Used Google Analytics, Search Console, SEMRush, Ahrefs, and competitor research to guide page optimisation and UX improvements.</li>
        <li>Built out publishing workflows, QA processes, and team guidelines to reduce errors and speed up delivery.</li>
      </ul>
      <div class="achievements">
        <div class="a-label">Results</div>
        <div class="a-item"><span class="mark">+95%</span><span>Team productivity, through coaching and clearer task ownership.</span></div>
        <div class="a-item"><span class="mark">+25%</span><span>Organic traffic, plus +18% CTR and 5–8 position ranking gains via SEO-led optimisation.</span></div>
        <div class="a-item"><span class="mark">−50%</span><span>Manual drafting time, using AI-assisted workflows across a 100+ page migration.</span></div>
      </div>
    </div>

    <div class="job-card reveal">
      <div class="job-status">Jun 2015 – Jul 2023</div>
      <h3 class="job-title">Associate Publishing Support <span class="job-org">— Finder</span></h3>
      <ul class="job-list">
        <li>Managed daily CMS and database updates for insurance product pages — pricing, provider details, fees, rates, terms, and market requirements.</li>
        <li>Ran market research and competitor checks to keep Australian financial product pages accurate and competitive.</li>
        <li>Performed QA checks, content audits, and broken-link reviews to maintain accuracy across live pages.</li>
        <li>Supported Publishers and Content Producers with high-volume requests, urgent updates, and ongoing maintenance.</li>
        <li>Handled detailed WordPress formatting and troubleshooting — layout fixes, tables, spacing, and readability.</li>
      </ul>
      <div class="achievements">
        <div class="a-label">Results</div>
        <div class="a-item"><span class="mark">★</span><span>Known internally as the "Formatting Queen" for advanced WordPress formatting and troubleshooting.</span></div>
        <div class="a-item"><span class="mark">−40%</span><span>Formatting and publishing errors, through QA reviews and content audits.</span></div>
        <div class="a-item"><span class="mark">98–99%</span><span>Content accuracy maintained across 300+ live pages while meeting KPI targets.</span></div>
      </div>
    </div>
  </div>
</section>

<section>
  <div class="wrap">
    <div class="section-head reveal"><span class="icon">🎉</span><h2>A Few Fun Facts</h2></div>
    <div class="fact-grid reveal">
      <div class="fact-card"><span class="icon">✏️</span>Add a fun fact — hobby, favorite tool, or quirky habit</div>
      <div class="fact-card"><span class="icon">✏️</span>Add a fun fact — something people are surprised to learn</div>
      <div class="fact-card"><span class="icon">✏️</span>Add a fun fact — what keeps you organized outside of work</div>
    </div>
  </div>
</section>

<section>
  <div class="wrap">
    <div class="section-head reveal"><span class="icon">💬</span><h2>What Colleagues Say</h2></div>
    <div class="testimonial reveal">
      "Add a short quote from a manager or teammate here — even one sentence about reliability or impact goes a long way."
      <cite>— Name, Role at Company (edit or remove this placeholder)</cite>
    </div>
  </div>
</section>

<section class="no-border">
  <div class="wrap">
    <div class="section-head reveal"><span class="icon">🎓</span><h2>Education</h2></div>
    <div class="edu-row reveal">
      <div>
        <div class="deg">Bachelor in Industrial Technology, Major in Computer Technology</div>
        <div class="school">Bulacan State University</div>
      </div>
      <div class="yr">2010</div>
    </div>
  </div>
</section>

<footer>
  <div class="wrap">
    <p class="role-line reveal">Looking for a VA who keeps things running quietly and correctly — with a smile?</p>
    <div class="cta-btns reveal" style="justify-content:center;">
      <a class="btn btn-primary" href="mailto:ev.robelynnedelapaz@gmail.com">✉️ Email me</a>
      <a class="btn btn-secondary" href="tel:+639156243162">📞 Call +63 915 624 3162</a>
    </div>
    <div class="foot-note">Based in the Philippines · Open to remote, full-time & contract roles</div>
  </div>
</footer>

<script>
  const items = document.querySelectorAll('.reveal');
  const io = new IntersectionObserver((entries) => {
    entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('in'); io.unobserve(e.target); } });
  }, { threshold: 0.12 });
  items.forEach(i => io.observe(i));
</script>

</body>
</html>
