# velocitylens.com
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Velocity Lens — Action & Aviation Photography</title>
  <meta name="description" content="Professional action photography portfolio — motorsports, aviation, wildlife, horse racing. Book shoots or request licensing.">
  <meta name="theme-color" content="#0b0b0d">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#070709;
      --card:#0f1113;
      --muted:#9aa0a6;
      --accent:#ffd166;
      --glass: rgba(255,255,255,0.03);
      --max-width:1200px;
      color-scheme: dark;
      font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;background:linear-gradient(180deg,var(--bg),#050506);color:#e9eef2}
    a{color:inherit;text-decoration:none}
    .container{max-width:var(--max-width);margin:0 auto;padding:28px}

    /* Header */
    header{display:flex;align-items:center;justify-content:space-between;padding:18px 0}
    .brand{display:flex;gap:14px;align-items:center}
    .logo{height:52px;width:52px;border-radius:10px;background:linear-gradient(135deg,#111 0%, #1c1f22 60%);display:flex;align-items:center;justify-content:center;font-weight:800;font-size:18px;color:var(--accent);box-shadow:0 6px 18px rgba(0,0,0,0.6)}
    .brand h1{margin:0;font-size:18px;letter-spacing:0.6px}
    .nav{display:flex;gap:14px;align-items:center}
    .nav a{padding:8px 12px;border-radius:8px;font-weight:600;color:var(--muted)}

    /* Hero */
    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;padding:48px 0}
    .hero-left{padding-right:8px}
    .kicker{font-weight:600;color:var(--muted);letter-spacing:1px;font-size:13px}
    .headline{font-size:40px;line-height:1.02;margin:12px 0;font-weight:800}
    .sub{color:var(--muted);max-width:56ch}
    .cta{display:flex;gap:12px;margin-top:22px}
    .btn{background:linear-gradient(90deg,var(--accent),#ffb86b);color:#071018;padding:12px 18px;border-radius:10px;font-weight:700;border:none;cursor:pointer}
    .btn.ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--muted)}

    /* Right panel: showreel / highlight */
    .card{background:var(--card);border-radius:14px;padding:16px;box-shadow:0 10px 30px rgba(0,0,0,0.6)}
    .showreel{height:320px;border-radius:10px;overflow:hidden;background:#000;display:flex;align-items:center;justify-content:center}
    .showreel video{width:100%;height:100%;object-fit:cover}
    .meta{display:flex;justify-content:space-between;align-items:center;margin-top:12px}
    .meta small{color:var(--muted)}

    /* Panels / Gallery */
    .panels{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin:40px 0}
    .panel{background:linear-gradient(180deg,var(--glass),transparent);border-radius:12px;overflow:hidden;min-height:240px;display:flex;flex-direction:column}
    .panel img{width:100%;height:220px;object-fit:cover;display:block}
    .panel .panel-body{padding:12px}
    .panel h3{margin:0;font-size:16px}
    .panel p{margin:8px 0 0;color:var(--muted);font-size:13px}

    /* Gallery grid */
    .gallery{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin:30px 0}
    .gallery img{width:100%;height:160px;object-fit:cover;border-radius:8px}

    /* Contact */
    .contact{display:flex;gap:24px;align-items:flex-start;padding:30px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01))}
    form{flex:1;display:flex;flex-direction:column;gap:10px}
    label{font-size:13px;color:var(--muted)}
    input,textarea,select{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:12px;border-radius:8px;color:inherit;min-width:0}
    textarea{min-height:120px;resize:vertical}
    .socials{min-width:220px}
    .socials a{display:flex;align-items:center;gap:10px;padding:10px;border-radius:8px;background:rgba(255,255,255,0.02);margin-bottom:8px}

    footer{padding:30px 0;color:var(--muted);text-align:center}

    /* Responsive */
    @media (max-width:1000px){
      .hero{grid-template-columns:1fr;}
      .gallery{grid-template-columns:repeat(2,1fr)}
      .panels{grid-template-columns:repeat(2,1fr)}
    }
    @media (max-width:560px){
      .container{padding:18px}
      .headline{font-size:28px}
      .gallery img{height:120px}
      .panels{grid-template-columns:1fr}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo" aria-hidden>VL</div>
        <div>
          <h1>Velocity Lens</h1>
          <div style="font-size:12px;color:var(--muted)">Professional Action & Aviation Photography</div>
        </div>
      </div>
      <nav class="nav" aria-label="Main navigation">
        <a href="#portfolio">Portfolio</a>
        <a href="#showreel">Showreel</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <section class="hero">
        <div class="hero-left">
          <div class="kicker">Action. Precision. Storytelling.</div>
          <h2 class="headline">World‑class action photography — motorsports, aviation, wildlife.</h2>
          <p class="sub">I capture high‑speed moments with clarity and cinematic style. Compact, refined portfolio for companies and clients who demand precision and energy. Based in North Yorkshire — available for commission and licensing.</p>
          <div class="cta">
            <button class="btn" onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Request a Quote</button>
            <button class="btn ghost" onclick="document.getElementById('portfolio').scrollIntoView({behavior:'smooth'})">View Portfolio</button>
          </div>
        </div>

        <aside class="card">
          <div class="showreel" id="showreel">
            <video autoplay muted loop playsinline poster="">
              <source src="/media/showreel.mp4" type="video/mp4">
            </video>
          </div>
          <div class="meta">
            <small>Showreel highlights — 00:45</small>
            <small style="color:var(--muted)">North Yorkshire / Available UK‑wide</small>
          </div>
        </aside>
      </section>

      <section id="portfolio">
        <h2 style="margin:0 0 12px">Featured Work</h2>
        <div class="panels">
          <article class="panel">
            <img src="/media/motorsports-1.jpg" alt="Motorsports action shot">
            <div class="panel-body">
              <h3>Motorsports</h3>
              <p>High‑speed composition capturing cars, riders and the intensity of racing.</p>
            </div>
          </article>

          <article class="panel">
            <img src="/media/aviation-1.jpg" alt="Aircraft in flight">
            <div class="panel-body">
              <h3>Aviation</h3>
              <p>Aircraft & aerial action shots with crisp detail and cinematic framing.</p>
            </div>
          </article>

          <article class="panel">
            <img src="/media/wildlife-1.jpg" alt="Wildlife action shot">
            <div class="panel-body">
              <h3>Wildlife & Equestrian</h3>
              <p>Swift moments in nature — from horse racing to wildlife encounters.</p>
            </div>
          </article>
        </div>

        <div class="gallery" aria-hidden>
          <img loading="lazy" src="/media/thumb1.jpg" alt="">
          <img loading="lazy" src="/media/thumb2.jpg" alt="">
          <img loading="lazy" src="/media/thumb3.jpg" alt="">
          <img loading="lazy" src="/media/thumb4.jpg" alt="">
        </div>
      </section>

      <section id="contact" style="margin-top:24px">
        <div class="contact">
          <form action="https://formspree.io/f/your-form-id" method="POST" autocomplete="on" novalidate>
            <input type="hidden" name="_subject" value="Website enquiry — Velocity Lens">
            <label for="name">Name</label>
            <input id="name" name="name" type="text" placeholder="Company / Contact name" required>

            <label for="email">Email</label>
            <input id="email" name="email" type="email" placeholder="you@company.com" required>

            <label for="details">Brief project details</label>
            <textarea id="details" name="details" placeholder="Type event, date, location, brief budget or usage" required></textarea>

            <label for="budget">Budget (optional)</label>
            <input id="budget" name="budget" type="text" placeholder="Approx. £ / $">

            <div style="display:flex;gap:10px;margin-top:10px">
              <button type="submit" class="btn">Send Enquiry</button>
              <button type="button" class="btn ghost" onclick="window.open('https://instagram.com/yourhandle','_blank')">Instagram</button>
            </div>
          </form>

          <aside class="socials">
            <div style="font-weight:700;margin-bottom:8px">Connect</div>
            <a href="#" onclick="window.open('https://instagram.com/yourhandle','_blank')">Instagram <small style="color:var(--muted);margin-left:auto">@yourhandle</small></a>
            <div style="margin-top:12px;color:var(--muted);font-size:13px">Available for commissions and licensing. Travel across UK and Europe.</div>
          </aside>
        </div>
      </section>

      <footer>
        <div>© <span id="yr"></span> Velocity Lens — professional photography. No personal info shown.</div>
      </footer>
    </main>
  </div>

  <script>
    document.getElementById('yr').textContent = new Date().getFullYear();
    document.querySelector('form').addEventListener('submit', function(e){
      var email = document.getElementById('email');
      if(!email.value){
        e.preventDefault();
        alert('Please enter a valid email address');
        email.focus();
        return false;
      }
    });
    document.addEventListener('keydown', function(e){
      if(e.key === 'g'){
        document.getElementById('portfolio').scrollIntoView({behavior:'smooth'});
      }
    });
  </script>
</body>
</html>
