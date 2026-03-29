<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Daniël Kalmann Consultancy — Procurement Excellence & Digital Transformation</title>
<meta name="description" content="Independent procurement consultant helping organizations optimize processes, implement digital solutions, and achieve sustainable savings through digital transformation.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=DM+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --navy:#0b1d3a;--navy-deep:#0a1628;--gold:#c8a55a;--gold-light:#d4c5a0;
  --gold-muted:#b09860;--surface:#f7f5f0;--text:#e8e4da;--text-muted:#a09880;
  --border:rgba(200,165,90,0.2);
}
body{font-family:'DM Sans',system-ui,sans-serif;background:var(--navy-deep);color:var(--text);-webkit-font-smoothing:antialiased}
h1,h2,h3,h4,blockquote{font-family:'Playfair Display',serif}
a{text-decoration:none;color:inherit}
.uppercase{text-transform:uppercase}.tracking-wide{letter-spacing:0.3em}

/* NAV */
nav{position:fixed;top:0;left:0;right:0;z-index:50;background:rgba(10,22,40,0.95);backdrop-filter:blur(12px);border-bottom:1px solid var(--border)}
.nav-inner{max-width:72rem;margin:0 auto;padding:0 1.5rem;height:4rem;display:flex;align-items:center;justify-content:space-between}
.nav-logo{font-family:'Playfair Display',serif;font-size:1.25rem;font-weight:600;color:var(--text)}
.nav-logo span{color:var(--gold)}
.nav-links{display:flex;align-items:center;gap:2rem}
.nav-links a{font-size:.8rem;font-weight:500;color:rgba(212,197,160,0.8);letter-spacing:0.1em;text-transform:uppercase;transition:color .2s}
.nav-links a:hover{color:var(--gold)}
.nav-cta{margin-left:.5rem;padding:.5rem 1.25rem;font-size:.8rem;font-weight:600;background:var(--gold);color:var(--navy-deep);border-radius:.25rem;text-transform:uppercase;letter-spacing:0.1em;transition:background .2s}
.nav-cta:hover{background:var(--gold-light)}
.mobile-toggle{display:none;background:none;border:none;color:var(--gold-light);font-size:1.5rem;cursor:pointer}

/* HERO */
.hero{position:relative;min-height:100vh;display:flex;align-items:center;justify-content:center;overflow:hidden;background:linear-gradient(135deg,var(--navy-deep) 0%,var(--navy) 50%,#152847 100%)}
.hero-overlay{position:absolute;inset:0;background:rgba(10,22,40,0.7)}
.hero-content{position:relative;z-index:10;max-width:52rem;margin:0 auto;padding:5rem 1.5rem 2rem;text-align:center}
.hero-label{font-size:.8rem;letter-spacing:0.3em;text-transform:uppercase;color:var(--gold);font-weight:500;margin-bottom:1.5rem}
.hero h1{font-size:clamp(2rem,5vw,3.5rem);font-weight:700;color:var(--text);line-height:1.2;margin-bottom:2rem}
.text-gradient-gold{background:linear-gradient(135deg,var(--gold),var(--gold-light));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
.hero-divider{width:4rem;height:1px;background:var(--gold);margin:0 auto 2rem}
.hero-sub{font-size:1.1rem;color:rgba(212,197,160,0.65);max-width:38rem;margin:0 auto 2.5rem;line-height:1.7}
.hero-btns{display:flex;gap:1rem;justify-content:center;flex-wrap:wrap}
.btn-primary{padding:.75rem 2rem;font-size:.8rem;font-weight:600;text-transform:uppercase;letter-spacing:0.1em;background:var(--gold);color:var(--navy-deep);border-radius:.25rem;transition:background .2s}
.btn-primary:hover{background:var(--gold-light)}
.btn-outline{padding:.75rem 2rem;font-size:.8rem;font-weight:600;text-transform:uppercase;letter-spacing:0.1em;border:1px solid rgba(200,165,90,0.4);color:var(--gold);border-radius:.25rem;transition:all .2s}
.btn-outline:hover{border-color:var(--gold);background:rgba(200,165,90,0.1)}

/* EXPERTISE */
.expertise{padding:6rem 1.5rem;background:var(--surface);color:#1a2a44}
.section-center{max-width:72rem;margin:0 auto;text-align:center}
.section-label{font-size:.8rem;letter-spacing:0.3em;text-transform:uppercase;color:var(--gold-muted);font-weight:500;margin-bottom:.75rem}
.section-title{font-size:clamp(1.75rem,3vw,2.25rem);font-weight:700;color:#1a2a44;margin-bottom:1rem}
.section-sub{color:#6b7280;max-width:36rem;margin:0 auto 3rem;line-height:1.6}
.pillars{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:2rem;text-align:left}
.pillar{background:#fff;border:1px solid #e5e7eb;border-radius:.5rem;padding:2rem;transition:all .3s}
.pillar:hover{border-color:rgba(200,165,90,0.4);box-shadow:0 10px 30px rgba(0,0,0,0.08)}
.pillar-icon{width:3rem;height:3rem;border-radius:.5rem;background:var(--navy);display:flex;align-items:center;justify-content:center;margin-bottom:1.5rem;color:var(--gold);font-size:1.25rem}
.pillar h3{font-size:1.2rem;font-weight:600;color:#1a2a44;margin-bottom:.75rem}
.pillar p{font-size:.875rem;color:#6b7280;line-height:1.6;margin-bottom:1.5rem}
.pillar ul{list-style:none;display:flex;flex-direction:column;gap:.5rem}
.pillar li{display:flex;align-items:center;gap:.5rem;font-size:.875rem;color:rgba(26,42,68,0.8)}
.pillar li::before{content:'';width:6px;height:6px;border-radius:50%;background:var(--gold-muted);flex-shrink:0}

/* ABOUT */
.about{padding:6rem 1.5rem;background:var(--navy-deep)}
.about-grid{max-width:72rem;margin:0 auto;display:grid;grid-template-columns:1fr 1fr;gap:4rem;align-items:center}
.about-label{font-size:.8rem;letter-spacing:0.3em;text-transform:uppercase;color:var(--gold);font-weight:500;margin-bottom:1rem}
.about h2{font-size:clamp(1.75rem,3vw,2.25rem);font-weight:700;color:var(--text);margin-bottom:1.5rem}
.about-divider{width:3rem;height:1px;background:var(--gold);margin-bottom:2rem}
.about blockquote{font-size:1.15rem;font-style:italic;color:rgba(212,197,160,0.65);margin-bottom:2rem;border-left:2px solid rgba(200,165,90,0.4);padding-left:1.5rem;line-height:1.6}
.about p{color:rgba(212,197,160,0.55);line-height:1.7;margin-bottom:1rem}
.about-card{background:rgba(11,29,58,0.5);border:1px solid rgba(200,165,90,0.1);border-radius:.5rem;padding:2rem}
.about-card h3{font-size:1.1rem;font-weight:600;color:var(--text);margin-bottom:1.5rem}
.traits{display:grid;grid-template-columns:1fr 1fr;gap:1.5rem}
.trait{display:flex;align-items:center;gap:.75rem}
.trait-icon{width:2.5rem;height:2.5rem;border-radius:.25rem;background:rgba(200,165,90,0.1);display:flex;align-items:center;justify-content:center;color:var(--gold);font-size:.9rem}
.trait span{font-size:.875rem;color:rgba(212,197,160,0.65)}
.stats{margin-top:2rem;padding-top:2rem;border-top:1px solid rgba(200,165,90,0.1);display:grid;grid-template-columns:1fr 1fr 1fr;gap:1rem;text-align:center}
.stats strong{font-family:'Playfair Display',serif;font-size:1.5rem;font-weight:700;color:var(--gold);display:block}
.stats small{font-size:.7rem;color:rgba(212,197,160,0.45);text-transform:uppercase;letter-spacing:0.15em}

/* CONTACT */
.contact{padding:6rem 1.5rem;background:var(--surface);color:#1a2a44;text-align:center}
.contact-btns{display:flex;gap:1.5rem;justify-content:center;flex-wrap:wrap;margin-bottom:4rem}
.contact-btn{display:flex;align-items:center;gap:.75rem;padding:.75rem 1.5rem;font-size:.8rem;font-weight:600;text-transform:uppercase;letter-spacing:0.08em;border-radius:.25rem;transition:all .2s}
.contact-btn.primary{background:var(--navy);color:var(--text)}
.contact-btn.primary:hover{background:#152847}
.contact-btn.outline{border:1px solid #e5e7eb;color:#1a2a44}
.contact-btn.outline:hover{border-color:var(--gold-muted);color:var(--gold-muted)}

/* FOOTER */
footer{border-top:1px solid #e5e7eb;background:var(--surface)}
.footer-inner{max-width:72rem;margin:0 auto;padding:2rem 1.5rem;display:flex;align-items:center;justify-content:space-between}
.footer-inner p{font-size:.875rem;color:#6b7280}
.footer-logo{font-family:'Playfair Display',serif;font-size:1.1rem;font-weight:600;color:#1a2a44}
.footer-logo span{color:var(--gold-muted)}

/* RESPONSIVE */
@media(max-width:768px){
  .nav-links{display:none}
  .mobile-toggle{display:block}
  .about-grid{grid-template-columns:1fr}
  .pillars{grid-template-columns:1fr}
  .contact-btns{flex-direction:column;align-items:center}
  .footer-inner{flex-direction:column;gap:1rem;text-align:center}
}
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-inner">
    <a href="#" class="nav-logo">
  <img src="logo.png" alt="DKC Logo" style="height:64px;">
</a>
    <div class="nav-links">
      <a href="#expertise">Expertise</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
      <a href="#contact" class="nav-cta">Let's Talk</a>
    </div>
    <button class="mobile-toggle" onclick="document.querySelector('.nav-links').style.display=document.querySelector('.nav-links').style.display==='flex'?'none':'flex'" aria-label="Menu">☰</button>
  </div>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-overlay"></div>
  <div class="hero-content">
    <p class="hero-label">Daniël Kalmann Consultancy</p>
    <h1>Unlocking Procurement<br><span class="text-gradient-gold">Excellence</span> Through<br>Digital Transformation</h1>
    <div class="hero-divider"></div>
    <p class="hero-sub">Independent consultant helping organizations optimize processes, implement digital solutions, and achieve sustainable savings — with a people-first approach.</p>
    <div class="hero-btns">
      <a href="#expertise" class="btn-primary">Explore Services</a>
      <a href="#contact" class="btn-outline">Get in Touch</a>
    </div>
  </div>
</section>

<!-- EXPERTISE -->
<section id="expertise" class="expertise">
  <div class="section-center">
    <p class="section-label">What I Do</p>
    <h2 class="section-title">The Excellence Pillars</h2>
    <p class="section-sub">Focused advisory and delivery service designed to transform your procurement operations into a strategic value driver.</p>
  </div>
  <div class="section-center">
    <div class="pillars">
      <div class="pillar">
        <div class="pillar-icon">⚙️</div>
        <h3>Digital Procurement Strategy</h3>
        <p>Roadmap development, tool selection (SaaS), and GenAI integration — aligning technology with your business goals.</p>
        <ul><li>Roadmap Development</li><li>Tool Selection (SaaS)</li><li>GenAI Integration</li></ul>
      </div>
      <div class="pillar">
        <div class="pillar-icon">🎯</div>
        <h3>Procurement Excellence</h3>
        <p>Strategy-to-execution, data driven procurement, and operating model including procurement operations advisory to elevate your procurement function.</p>
        <ul><li>Operating Model Advisory</li><li>Taxonomy Restructuring</li><li>Strategy Execution</li></ul>
      </div>
      <div class="pillar">
        <div class="pillar-icon">🔧</div>
        <h3>Process Optimization</h3>
        <p>Source-to-Pay implementations and optimization, Taxonomy, and automation for maximum efficiency.</p>
        <ul><li>S2P Implementation</li><li>P2P Optimization</li><li>Automation &amp; Efficiency</li></ul>
      </div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about" class="about">
  <div class="about-grid">
    <div>
      <p class="about-label">About</p>
      <h2>Daniël Kalmann</h2>
      <div class="about-divider"></div>
      <blockquote>"Digital transformation is 20% technology and 80% people and process."</blockquote>
      <p>With over 10 years of experience in Procurement Excellence and Digital Transformation, I bridge the gap between complex business processes and high-end digital solutions.</p>
      <p>My approach is strategic, results-oriented, but always focused on the people who use the tools. Because even the best system fails if nobody actually wants to use it.</p>
      <p>10+ years leading sourcing and procurement projects delivering results in digital procurement, project management, and business performance improvement. Experience in Management Consulting and Corporate positions. Projects in S2P implementation, optimization, category management & strategy, policy & operating model and governance, data cleansing, GenAI, sourcing and RFx and managing and leading teams </p>
    </div>
    <div>
      <div class="about-card">
        <h3>Beyond the Boardroom</h3>
        <div class="traits">
          <div class="trait"><div class="trait-icon">🚴</div><span>Cycling</span></div>
          <div class="trait"><div class="trait-icon">🥊</div><span>Boxing</span></div>
          <div class="trait"><div class="trait-icon">👶</div><span>Proud Dad</span></div>
          <div class="trait"><div class="trait-icon">📍</div><span>Based in Haarlem, NL</span></div>
        </div>
        <div class="stats">
          <div><strong>10+</strong><small>Years</small></div>
          <div><strong>S2P</strong><small>Expert</small></div>
          <div><strong>NL</strong><small>Based</small></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="contact">
  <div class="section-center">
    <p class="section-label">Let's Connect</p>
    <h2 class="section-title">Ready to Transform Your Procurement?</h2>
    <p class="section-sub">Let's discuss how I can help your organization unlock procurement excellence through digital innovation and process optimization.</p>
    <div class="contact-btns">
      <a href="mailto:Kalmann.Daniel@gmail.com" class="contact-btn primary">✉️ Email Me</a>
      <a href="tel:+31682687009" class="contact-btn outline">📞 +31 (0)6 8268 7009</a>
      <a href="https://www.linkedin.com/in/dani%C3%ABl-kalmann/" target="_blank" rel="noopener noreferrer" class="contact-btn outline">🔗 LinkedIn</a>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-inner">
    <p>© 2026 Daniël Kalmann Consultancy. All rights reserved.</p>
    <div class="footer-logo">
  <img src="logo.png" alt="DKC Logo" style="height:64px;">
</div>
  </div>
</footer>

</body>
</html>
