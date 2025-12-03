<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Inner Spring Martial Arts and Health — André Cronjé</title>
  <meta name="description" content="Inner Spring Martial Arts and Health — Taiji, Qigong and internal arts with André Cronjé. Classes for health, private training, workshops and online lessons." />
  <link rel="stylesheet" href="styles.css" />
  <link rel="icon" href="data:;base64,iVBORw0KGgo=">
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <div class="brand">
        <h1 class="site-title">Inner Spring</h1>
        <p class="site-sub">Martial Arts &amp; Health — André Cronjé</p>
      </div>
      <nav class="site-nav" aria-label="Main">
        <a href="#about">About</a>
        <a href="#classes">Classes</a>
        <a href="#media">Media</a>
        <a href="#contact">Contact</a>
      </nav>
      <button class="menu-toggle" aria-label="Open menu" onclick="document.body.classList.toggle('nav-open')">☰</button>
    </div>
  </header>

  <main>
    <!-- HERO -->
    <section class="hero">
      <div class="container hero-inner">
        <div class="hero-text">
          <h2>Inner Spring Martial Arts &amp; Health</h2>
          <p class="lead">Taijiquan, Qigong and internal training for longevity, vitality and refined power. Classes for 50+ health-focused students and advanced private training for martial artists.</p>
          <div class="hero-ctas">
            <a class="btn primary" href="#classes">See Classes</a>
            <a class="btn ghost" href="#contact">Book a Trial</a>
          </div>
        </div>

        <div class="hero-media" aria-hidden="true">
          <!-- Replace this block with an embedded video or hero image -->
          <div class="hero-placeholder">Hero video / image — replace with your footage</div>
        </div>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" class="section">
      <div class="container">
        <h3>About André Cronjé</h3>
        <p class="short">Cinematographer turned Taiji teacher — over 20 years of practice and teaching in Taijiquan, Qigong and Kung Fu, now teaching in Los Angeles.</p>

        <div class="about-grid">
          <div class="about-text">
            <p><strong>Background &amp; approach.</strong> I trained and taught Yang-style Taijiquan and internal arts for over two decades, combining traditional lineage practices with modern health-focused instruction. My work in film—including credits on high-profile documentary projects—shaped a visual, patient, and observational teaching style. I focus on clarity of structure, body mechanics, and internal feeling.</p>

            <p><strong>Who trains here.</strong> My student base ranges from people aged 50+ seeking improved balance, mobility, and wellbeing, to high-level martial artists wanting private refinement of internal power and application. Classes emphasize safety, fundamentals, and progressive learning so students build confidence and depth over time.</p>
          </div>

          <div class="about-features">
            <ul>
              <li><strong>20+ years</strong> of practice & teaching</li>
              <li><strong>Documentary cinematography</strong> background (creative, observant teacher)</li>
              <li><strong>Private training</strong> for serious practitioners</li>
              <li><strong>Workshops & retreats</strong> — small, focused groups</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- CLASSES -->
    <section id="classes" class="section alt">
      <div class="container">
        <h3>Classes & Offerings</h3>
        <p class="muted">Tailored to health, longevity and skill development. In-person in Los Angeles, plus online options.</p>

        <div class="grid">
          <article class="card">
            <h4>Beginner Taiji — Foundations</h4>
            <p>Gentle, structured entry to Taijiquan. Build balance, posture, and basic forms. Ideal for 50+ students focused on health.</p>
          </article>

          <article class="card">
            <h4>Intermediate &amp; Application</h4>
            <p>Deepen form, sensitivity, and introduction to push-hands and partner work. For committed students with at least basic practice.</p>
          </article>

          <article class="card">
            <h4>Private Lessons</h4>
            <p>One-on-one refinement for martial artists and serious students. Technical correction, internal energy work and personal progression plans.</p>
          </article>

          <article class="card">
            <h4>Workshops & Retreats</h4>
            <p>Monthly workshops and occasional weekend retreats — movement, theory and Qigong for restoration.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- MEDIA -->
    <section id="media" class="section">
      <div class="container">
        <h3>Media & Showreel</h3>
        <p class="muted">Sample lessons, short demos and workshop highlights. Replace placeholders with your YouTube/Vimeo links.</p>

        <div class="media-grid">
          <div class="media-card">
            <div class="media-thumb">Video #1 (Showreel)</div>
            <p>Short showreel — replace with Vimeo/YouTube embed</p>
          </div>
          <div class="media-card">
            <div class="media-thumb">Lesson Preview</div>
            <p>Sample 10-minute class excerpt for new students</p>
          </div>
          <div class="media-card">
            <div class="media-thumb">Workshop Clips</div>
            <p>Highlights from recent workshops & retreats</p>
          </div>
        </div>
      </div>
    </section>

    <!-- TESTIMONIALS -->
    <section id="testimonials" class="section alt small">
      <div class="container">
        <h3>Student Feedback</h3>
        <div class="testimonials">
          <blockquote>"André's classes restored my balance and confidence — gentle, clear and deeply knowledgeable." <cite>— S. P., LA</cite></blockquote>
          <blockquote>"Private sessions accelerated my internal sensitivity — practical, patient, and exacting." <cite>— M. R., Private Student</cite></blockquote>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="section">
      <div class="container contact-grid">
        <div>
          <h3>Contact & Bookings</h3>
          <p>Email: <a href="mailto:andre@innerspringma.com">andre@innerspringma.com</a> (replace with your address)</p>
          <p>Location: Los Angeles, CA — in-person classes & online training available.</p>
          <p>Social: <a href="#" id="insta">Instagram</a> • <a href="#" id="youtube">YouTube</a></p>
        </div>

        <form class="contact-form" onsubmit="window.location='mailto:andre@innerspringma.com?subject=Class inquiry&body='+encodeURIComponent(document.getElementById('msg').value); return false;">
          <label>
            Your name
            <input type="text" id="name" name="name" placeholder="Your name" required>
          </label>
          <label>
            Message
            <textarea id="msg" name="message" rows="4" placeholder="Tell me about your goals or class enquiry" required></textarea>
          </label>
          <button type="submit" class="btn primary">Send Email</button>
        </form>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <small>© <span id="year"></span> Inner Spring Martial Arts and Health — André Cronjé</small>
    </div>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
/* styles.css - nature-inspired palette (Wudang / water + stone) */
:root{
  --bg:#F6FBFA; --panel:#ffffff; --ink:#0e1d23; --muted:#5f7b7c;
  --accent:#2fa6a0; --accent-2:#6bb9b3;
  --container:1100px;
  font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
}
*{box-sizing:border-box}
body{margin:0;background:linear-gradient(180deg,#f3fbfa,#eef6f5);color:var(--ink);line-height:1.6;-webkit-font-smoothing:antialiased}
.container{max-width:var(--container);margin:0 auto;padding:28px}
.site-header{position:sticky;top:0;background:rgba(255,255,255,0.65);backdrop-filter:blur(6px);border-bottom:1px solid rgba(15,29,35,0.06)}
.header-inner{display:flex;align-items:center;justify-content:space-between;gap:18px}
.site-title{margin:0;font-size:1.15rem;font-weight:700;color:var(--ink)}
.site-sub{margin:2px 0 0;font-size:.82rem;color:var(--muted)}
.site-nav a{color:var(--muted);margin-left:18px;text-decoration:none;font-weight:600}
.menu-toggle{display:none;background:none;border:0;font-size:1.2rem}
.hero{padding:64px 0}
.hero-inner{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center}
.lead{color:var(--muted);font-size:1.05rem;margin-top:8px}
.btn{display:inline-block;padding:10px 16px;border-radius:10px;text-decoration:none;font-weight:700;border:1px solid transparent}
.btn.primary{background:var(--accent);color:#fff}
.btn.ghost{background:transparent;color:var(--accent);border:1px solid rgba(47,166,160,0.14)}
.hero-placeholder{height:260px;border-radius:12px;background:linear-gradient(180deg,#dff3f1,#cfece8);display:flex;align-items:center;justify-content:center;color:var(--muted);font-weight:700;border:1px solid rgba(15,29,35,0.03)}
.section{padding:48px 0}
.alt{background:linear-gradient(180deg, rgba(47,166,160,0.03), transparent);border-top:1px solid rgba(15,29,35,0.03)}
.about-grid{display:grid;grid-template-columns:1fr 320px;gap:28px;align-items:start;margin-top:18px}
.short{font-weight:600;color:var(--muted)}
.about-features ul{list-style:none;padding:0;margin:0}
.about-features li{background:linear-gradient(90deg, rgba(47,166,160,0.06), transparent);padding:10px;border-radius:8px;margin-bottom:8px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:18px;margin-top:18px}
.card{background:var(--panel);padding:18px;border-radius:12px;box-shadow:0 6px 20px rgba(12,18,20,0.04);border:1px solid rgba(15,29,35,0.03)}
.media-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:16px}
.media-thumb{height:140px;border-radius:10px;background:linear-gradient(180deg,#e6f7f6,#d3eee9);display:flex;align-items:center;justify-content:center;color:var(--muted);font-weight:600;border:1px solid rgba(15,29,35,0.02)}
.testimonials blockquote{margin:12px 0;padding:14px;border-left:4px solid var(--accent);background:#f6fbfa;border-radius:8px;color:var(--muted)}
.contact-grid{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:start}
.contact-form{display:grid;gap:10px}
.contact-form input, .contact-form textarea{width:100%;padding:10px;border-radius:8px;border:1px solid rgba(15,29,35,0.06);background:transparent}
.site-footer{padding:18px 0;text-align:center;color:var(--muted)}
@media(max-width:880px){
  .hero-inner{grid-template-columns:1fr;text-align:center}
  .about-grid{grid-template-columns:1fr}
  .contact-grid{grid-template-columns:1fr}
  .site-nav{display:none}
  .menu-toggle{display:block}
  body.nav-open .site-nav{position:fixed;left:0;top:70px;background:#fff;padding:20px;width:100%;display:flex;flex-direction:column;gap:12px}
}
