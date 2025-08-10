# Earninggames
Fake cash
ठीक है 👍
मैं आपका earninggames का final website code नीचे दे रहा हूँ — इसमें About, Services और Contact section सब भर दिए हैं।
इसके बाद मैं आपको GitHub Pages पर live करने के स्टेप्स भी दूँगा।


---

Final earninggames Website Code

इसे आप index.html के नाम से सेव करें:

<!doctype html>
<html lang="hi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>earninggames</title>
  <meta name="description" content="Games khelkar earning ka mauka - सिर्फ़ मनोरंजन के लिए.">
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --accent:#06b6d4;
      --muted:#94a3b8;
      --glass: rgba(255,255,255,0.04);
      --radius:14px;
      --fw-heading:700;
      --fw-body:400;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background:linear-gradient(180deg,#071025 0%, #07182b 100%);
      color:#e6eef6;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
    }
    .container{max-width:980px;margin:40px auto;padding:24px;}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{
      width:56px;height:56px;border-radius:10px;background:linear-gradient(135deg,var(--accent),#3b82f6);
      display:flex;align-items:center;justify-content:center;font-weight:800;color:#021022;
      box-shadow: 0 6px 18px rgba(3,7,18,0.6);
      font-family: system-ui, sans-serif;
    }
    nav a{color:var(--muted);text-decoration:none;margin-left:18px;font-size:15px}
    .hero{display:grid;grid-template-columns:1fr;gap:20px;margin-top:32px;padding:28px;background:var(--glass);border-radius:16px;backdrop-filter: blur(6px);}
    h1{font-size:28px;margin:0;color:white;font-weight:var(--fw-heading)}
    p.lead{color:var(--muted);margin:6px 0 0 0}
    .cta{margin-top:14px}
    .btn{
      display:inline-block;padding:10px 18px;border-radius:10px;text-decoration:none;font-weight:600;
      background:linear-gradient(90deg,var(--accent),#7c3aed);color:#021022;
      box-shadow: 0 8px 20px rgba(11,22,40,0.45);
    }
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:18px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); padding:16px;border-radius:12px}
    .card h3{margin:0 0 8px 0;font-size:16px}
    footer{margin-top:28px;padding:18px;text-align:center;color:var(--muted);font-size:14px}
    @media (max-width:880px){.grid{grid-template-columns:repeat(2,1fr)}}
    @media (max-width:560px){
      header{flex-direction:column;align-items:flex-start}
      .grid{grid-template-columns:1fr}
      .logo{width:48px;height:48px}
      h1{font-size:22px}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">EG</div>
        <div>
          <div style="font-weight:700">earninggames</div>
          <div style="font-size:13px;color:var(--muted)">Games khelkar earning ka mauka</div>
        </div>
      </div>
      <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero" id="home">
      <div>
        <h1>earninggames में आपका स्वागत है</h1>
        <p class="lead">Games khelkar earning ka maza lijiye — यह सिर्फ़ मनोरंजन के लिए है, असली पैसा नहीं.</p>
        <div class="cta">
          <a class="btn" href="#services">Play Now</a>
        </div>
      </div>
    </section>

    <section style="margin-top:18px" id="services">
      <h2 style="margin:0 0 12px 0">Services</h2>
      <div class="grid">
        <div class="card">
          <h3>Spin & Win</h3>
          <p style="color:var(--muted)">Wheel घुमाइये और points कमाइये.</p>
        </div>
        <div class="card">
          <h3>Quiz Play</h3>
          <p style="color:var(--muted)">Trivia questions का जवाब देकर points पाएं.</p>
        </div>
        <div class="card">
          <h3>Lucky Card Flip</h3>
          <p style="color:var(--muted)">Cards पलटकर surprise rewards जीतें.</p>
        </div>
      </div>
    </section>

    <section style="margin-top:20px" id="about">
      <h2>About</h2>
      <p style="color:var(--muted)">
        earninggames में हम आपको मजेदार games और challenges देते हैं,
        जिनसे आप points कमा सकते हैं। यह केवल मनोरंजन के लिए है — कोई
        असली पैसा या transaction नहीं होता।
      </p>
    </section>

    <section style="margin-top:18px" id="contact">
      <h2>Contact</h2>
      <p style="color:var(--muted)">Email: <strong>contact@earninggames.com</strong></p>
    </section>

    <footer>
      © <span id="year"></span> earninggames — Entertainment Only.
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>


---
