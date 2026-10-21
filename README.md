# Bab-s_portfolio
About Me
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Babalola Olamilekan Emmanuel | Data Analyst</title>
<meta name="description" content="Data analysis portfolio of Babalola Olamilekan Emmanuel: projects in Excel, SQL, Python and Power BI.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@500;700;800&family=Source+Serif+4:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet">
<style>
:root{
  --paper:#F2F5F7; --ink:#13222C; --muted:#4F626E; --line:#C9D4DA;
  --teal:#0F6B6E; --gold:#D9A400; --panel:#E7EDF1;
  --head:"Bricolage Grotesque",system-ui,sans-serif;
  --body:"Source Serif 4",Georgia,serif;
}
@media (prefers-color-scheme:dark){
  :root{--paper:#10191F; --ink:#E8EEF1; --muted:#9FB0BA; --line:#2B3B45; --teal:#4FC3C6; --gold:#F0BE2E; --panel:#17242C;}
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--paper);color:var(--ink);font:18px/1.65 var(--body)}
a{color:var(--teal)}
a:focus-visible,button:focus-visible{outline:3px solid var(--gold);outline-offset:3px}
.wrap{max-width:980px;margin:0 auto;padding:0 24px}
header.top{display:flex;justify-content:space-between;align-items:center;padding:20px 0;border-bottom:1px solid var(--line)}
header.top strong{font-family:var(--head);font-size:1rem}
nav a{font-family:var(--head);font-weight:500;font-size:.95rem;margin-left:20px;color:var(--ink);text-decoration:none}
nav a:hover{color:var(--teal)}

/* hero */
.hero{display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:center;padding:72px 0 64px}
.hero h1{font-family:var(--head);font-weight:800;font-size:clamp(2.2rem,5vw,3.6rem);line-height:1.05;margin:0 0 20px;letter-spacing:-.02em}
.hero p{margin:0 0 24px;max-width:46ch;color:var(--muted)}
.btns{display:flex;gap:12px;flex-wrap:wrap}
.btn{font-family:var(--head);font-weight:700;font-size:.95rem;padding:12px 20px;border-radius:6px;text-decoration:none;border:2px solid var(--teal)}
.btn.main{background:var(--teal);color:var(--paper)}
.btn.alt{color:var(--teal)}
.chart{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:18px}
.chart figcaption{font-size:.85rem;color:var(--muted);margin-top:8px}
.chart svg{width:100%;height:auto;display:block}

section{padding:56px 0;border-top:1px solid var(--line)}
h2{font-family:var(--head);font-weight:800;font-size:1.9rem;margin:0 0 24px;letter-spacing:-.01em}
.about{display:grid;grid-template-columns:1fr 1fr;gap:40px}
.about p{margin:0 0 16px}

/* skills */
.skills{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:28px}
.skills h3{font-family:var(--head);font-size:1rem;margin:0 0 8px;color:var(--teal)}
.skills ul{margin:0;padding:0;list-style:none;color:var(--muted)}
.skills li{padding:3px 0}

/* projects */
.proj{display:grid;grid-template-columns:200px 1fr;gap:8px 32px;padding:28px 0;border-top:1px solid var(--line)}
.proj:first-of-type{border-top:0;padding-top:0}
.proj h3{font-family:var(--head);font-size:1.3rem;margin:0 0 6px}
.tools{font-family:var(--head);font-size:.85rem;color:var(--muted);margin:0}
.proj p{margin:0 0 10px}
.result{border-left:4px solid var(--gold);padding-left:14px;font-style:italic}
.links a{font-family:var(--head);font-weight:600;font-size:.95rem;margin-right:18px}

/* experience */
.job{display:grid;grid-template-columns:200px 1fr;gap:8px 32px}
.job h3{font-family:var(--head);margin:0;font-size:1.1rem}
.job .when{color:var(--muted);font-size:.95rem}

footer{padding:40px 0 56px;border-top:1px solid var(--line);color:var(--muted);font-size:.95rem}
.contact{font-size:1.15rem}
.contact a{margin-right:20px;font-family:var(--head);font-weight:600}

@media (max-width:760px){
  .hero,.about,.proj,.job{grid-template-columns:1fr}
  .hero{padding-top:48px}
  nav a{margin-left:14px}
}
@media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}}
</style>
</head>
<body>
<div class="wrap">

<header class="top">
  <strong>Babalola Olamilekan Emmanuel</strong>
  <nav aria-label="Main">
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    <a href="#experience">Experience</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
<div class="hero">
  <div>
    <h1>I turn financial records into clear decisions.</h1>
    <p>I'm a data analyst based in Ibadan, Nigeria. I clean messy data, find the pattern, and present it so a business owner can act on it. My background is in accounting operations and economics education.</p>
    <div class="btns">
      <a class="btn main" href="#projects">See my projects</a>
      <a class="btn alt" href="#contact">Get in touch</a>
    </div>
  </div>
  <figure class="chart" style="margin:0">
    <!-- Replace these numbers with a real chart from one of your projects -->
    <svg viewBox="0 0 320 200" role="img" aria-label="Sample bar chart of monthly sales with the best month highlighted">
      <g stroke="var(--line)" stroke-width="1">
        <line x1="20" y1="170" x2="310" y2="170"/>
        <line x1="20" y1="120" x2="310" y2="120"/>
        <line x1="20" y1="70" x2="310" y2="70"/>
      </g>
      <g fill="var(--teal)">
        <rect x="32" y="110" width="30" height="60"/>
        <rect x="76" y="95" width="30" height="75"/>
        <rect x="120" y="100" width="30" height="70"/>
        <rect x="164" y="70" width="30" height="100"/>
        <rect x="252" y="85" width="30" height="85"/>
      </g>
      <rect x="208" y="35" width="30" height="135" fill="var(--gold)"/>
      <text x="223" y="26" text-anchor="middle" font-family="Bricolage Grotesque, sans-serif" font-size="12" font-weight="700" fill="var(--ink)">Peak</text>
      <g font-family="Bricolage Grotesque, sans-serif" font-size="11" fill="var(--muted)" text-anchor="middle">
        <text x="47" y="187">Jan</text><text x="91" y="187">Feb</text><text x="135" y="187">Mar</text>
        <text x="179" y="187">Apr</text><text x="223" y="187">May</text><text x="267" y="187">Jun</text>
      </g>
    </svg>
    <figcaption>Sample chart. Swap in your own work.</figcaption>
  </figure>
</div>

<section id="about">
  <h2>About me</h2>
  <div class="about">
    <div>
      <p>I started in accounts, where I learned that numbers only matter when someone uses them. That is why I focus on analysis that answers a question: what sold, what cost too much, what to do next.</p>
      <p>I now build dashboards and reports with Excel, SQL, Python and Power BI.</p>
    </div>
    <div>
      <p>I'm open to junior and mid-level data analyst roles, as well as freelance reporting and dashboard work for small businesses.</p>
      <p><a href="https://github.com/YOUR-USERNAME">See my code on GitHub</a></p>
    </div>
  </div>
</section>

<section id="projects">
  <h2>Projects</h2>

  <!-- Copy this block for each project. Replace the text and links. -->
  <article class="proj">
    <div>
      <h3>Sales Performance Dashboard</h3>
      <p class="tools">Excel · Power BI</p>
    </div>
    <div>
      <p><strong>Question:</strong> Which products and months drive the most revenue for a small retail business?</p>
      <p><strong>What I did:</strong> Cleaned two years of sales records, built a monthly trend view, and ranked products by profit margin.</p>
      <p class="result">Result: Found that the top three products made most of the profit. Describe your real finding here.</p>
      <p class="links"><a href="#">View dashboard</a><a href="#">Code and data</a></p>
    </div>
  </article>

  <article class="proj">
    <div>
      <h3>Customer Churn Analysis</h3>
      <p class="tools">Python · pandas · Matplotlib</p>
    </div>
    <div>
      <p><strong>Question:</strong> Which customers are most likely to stop buying?</p>
      <p><strong>What I did:</strong> Explored a public customer dataset, built charts of churn by segment, and tested simple predictors.</p>
      <p class="result">Result: Add your key number and recommendation here.</p>
      <p class="links"><a href="#">Notebook</a><a href="#">Write-up</a></p>
    </div>
  </article>

  <article class="proj">
    <div>
      <h3>Expense and Budget Tracker Analysis</h3>
      <p class="tools">SQL · Excel</p>
    </div>
    <div>
      <p><strong>Question:</strong> Where is money leaking out of a monthly budget?</p>
      <p><strong>What I did:</strong> Wrote SQL queries to group expenses by category and flag months that went over budget.</p>
      <p class="result">Result: Add your key finding here.</p>
      <p class="links"><a href="#">SQL queries</a><a href="#">Report</a></p>
    </div>
  </article>
</section>

<section id="skills">
  <h2>Skills</h2>
  <div class="skills">
    <div><h3>Analysis</h3><ul><li>Data cleaning</li><li>Exploratory analysis</li><li>Financial reporting</li></ul></div>
    <div><h3>Tools</h3><ul><li>Excel (pivot tables, formulas)</li><li>SQL</li><li>Python (pandas, Matplotlib)</li><li>Power BI</li></ul></div>
    <div><h3>Working style</h3><ul><li>Clear written summaries</li><li>Accuracy with figures</li><li>Presenting to non-technical people</li></ul></div>
  </div>
</section>

<section id="experience">
  <h2>Experience</h2>
  <div class="job">
    <div class="when">1 year 7 months</div>
    <div>
      <h3>Account Officer, Fadvic Ventures</h3>
      <p>Handled day-to-day accounting records, reconciliations and financial reports. Add two or three results with numbers, for example: "Cut month-end reporting time from 5 days to 3."</p>
    </div>
  </div>
</section>
</main>

<footer id="contact">
  <h2>Contact</h2>
  <p class="contact">
    <a href="mailto:your.email@example.com">your.email@example.com</a>
    <a href="https://www.linkedin.com/in/YOUR-LINKEDIN">LinkedIn</a>
    <a href="https://github.com/YOUR-USERNAME">GitHub</a>
  </p>
  <p>Ibadan, Oyo State, Nigeria</p>
</footer>

</div>
</body>
</html>
