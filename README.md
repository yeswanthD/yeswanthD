<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Yeswanth Doppalapudi — Generative & Agentic AI Engineer</title>
  <meta name="description" content="Portfolio of Yeswanth Doppalapudi — Generative AI Engineer, Prompt Engineer, Agentic AI Engineer" />
  <link rel="icon" href="data:;base64,iVBORw0KGgo=" />
  <style>
    :root{
      --bg:#070712; --card:#0e0f17; --muted:#98a0b3; --accent:#00e7ff; --accent2:#7c4dff;
      --glass: rgba(255,255,255,0.04);
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,#04050a 0%, #0b0c12 100%);color:#e6eef8;min-height:100vh;}
    .container{max-width:1100px;margin:32px auto;padding:28px}

    /* hero */
    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center}
    .hero-card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:28px;border-radius:14px;box-shadow:0 6px 30px rgba(2,6,23,0.7);}
    h1{margin:0 0 12px 0;font-size:34px;letter-spacing:-0.6px}
    p.lead{margin:0 0 18px;color:var(--muted);font-size:16px;line-height:1.45}

    /* running text / ticker */
    .ticker{display:flex;gap:14px;align-items:center;font-weight:600;color:var(--accent)}
    .ticker .dot{width:10px;height:10px;border-radius:50%;background:linear-gradient(90deg,var(--accent),var(--accent2));box-shadow:0 6px 18px rgba(0,231,255,0.08)}
    .ticker-wrap{overflow:hidden;width:100%;}
    .ticker-track{display:inline-block;white-space:nowrap;transform:translateX(0);animation:slide 12s linear infinite}
    .ticker-item{display:inline-block;margin-right:40px;font-size:15px;color:#bfefff}
    @keyframes slide{0%{transform:translateX(0)}50%{transform:translateX(-50%)}100%{transform:translateX(0)}}

    /* banner image */
    .banner{width:100%;height:260px;border-radius:12px;background:#091026 center/cover no-repeat;display:flex;align-items:center;justify-content:center;overflow:hidden}
    .banner img{width:100%;height:100%;object-fit:cover;display:block}

    /* projects */
    .projects{display:grid;grid-template-columns:repeat(2,1fr);gap:18px;margin-top:20px}
    .card{background:var(--card);padding:16px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    .card h3{margin:0 0 8px 0}
    .card p{margin:0;color:var(--muted);font-size:14px}
    .badges{margin-top:12px;display:flex;gap:8px;flex-wrap:wrap}
    .badge{background:var(--glass);padding:6px 10px;border-radius:999px;color:var(--muted);font-size:13px;border:1px solid rgba(255,255,255,0.02)}

    /* contact */
    .contact{display:flex;gap:12px;align-items:center;margin-top:22px}
    .btn{background:linear-gradient(90deg,var(--accent),var(--accent2));padding:10px 14px;border-radius:10px;color:#021; font-weight:700;text-decoration:none}

    footer{margin-top:40px;color:var(--muted);font-size:13px;text-align:center}

    /* responsive */
    @media (max-width:900px){.hero{grid-template-columns:1fr;}.banner{height:180px}.projects{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <div class="container">
    <div class="hero">
      <div class="hero-card">
        <h1>Hi 👋 I'm <strong style="color:var(--accent)">Yeswanth Doppalapudi</strong></h1>
        <p class="lead">Generative AI Engineer • Prompt Engineer • Agentic AI Engineer. I design and build AI systems that think, act, and evolve — combining ML/DL, prompt engineering, and deployable microservices to ship real-world solutions.</p>

        <div class="ticker">
          <div class="dot"></div>
          <div class="ticker-wrap">
            <div class="ticker-track" id="tickerTrack">
              <span class="ticker-item">Generative AI Engineer</span>
              <span class="ticker-item">Agentic AI Engineer</span>
              <span class="ticker-item">Prompt Engineer</span>
              <span class="ticker-item">AI Technical Trainer</span>
              <span class="ticker-item">Python & Deployment</span>
              <span class="ticker-item">Always Learning ✨ Always Building 🚀</span>
              <!-- repeat to create seamless loop -->
              <span class="ticker-item">Generative AI Engineer</span>
              <span class="ticker-item">Agentic AI Engineer</span>
            </div>
          </div>
        </div>

        <div class="contact">
          <a class="btn" href="mailto:yeswanth.ai369@gmail.com">Contact Me</a>
          <a class="btn" href="https://github.com/yeswanthD" target="_blank" style="background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--accent)">GitHub</a>
        </div>

        <div style="margin-top:18px;color:var(--muted);font-size:14px">Open to internships, collaborations, and mentorship — happy to help students and teams build AI projects.</div>
      </div>

      <div>
        <div class="banner">
          <!-- Replace the src with your hosted banner GIF or PNG (assets/banner.gif) -->
          <img src="assets/banner.png" alt="Banner - replace with your animated GIF or image" />
        </div>

        <div class="projects">
          <div class="card">
            <h3>🏡 House Price Prediction</h3>
            <p>End-to-end regression pipeline with feature engineering, training, and model serialization.</p>
            <div class="badges"><span class="badge">Python</span><span class="badge">scikit-learn</span><span class="badge">Pandas</span></div>
          </div>

          <div class="card">
            <h3>🌾 Rice Leaf Disease Detection</h3>
            <p>CNN model for detecting multiple leaf diseases with augmentation and evaluation scripts.</p>
            <div class="badges"><span class="badge">TensorFlow</span><span class="badge">Keras</span><span class="badge">CNN</span></div>
          </div>

          <div class="card">
            <h3>💬 Conversational AI Chatbot</h3>
            <p>Context-aware chatbot with intent & sentiment recognition and response ranking.</p>
            <div class="badges"><span class="badge">Transformers</span><span class="badge">Flask</span><span class="badge">NLP</span></div>
          </div>

          <div class="card">
            <h3>📈 Stock Trend Predictor (GUI)</h3>
            <p>Tkinter GUI to run KNN-based trend experiments and visualize results.</p>
            <div class="badges"><span class="badge">Python</span><span class="badge">Tkinter</span><span class="badge">scikit-learn</span></div>
          </div>
        </div>

      </div>
    </div>

    <footer>
      <div>Built by <strong>Yeswanth Doppalapudi</strong> — Generative & Agentic AI Engineer</div>
      <div style="margin-top:8px;color:var(--muted)">Deploy with GitHub Pages: create a repo named <code>yourusername.github.io</code>, add this file as <code>index.html</code>, push, and enable Pages in repo settings.</div>
    </footer>
  </div>

  <script>
    // Small accessibility tweak: pause ticker on hover
    const track = document.getElementById('tickerTrack');
    track.addEventListener('mouseenter', ()=> track.style.animationPlayState='paused');
    track.addEventListener('mouseleave', ()=> track.style.animationPlayState='running');
  </script>
</body>
</html>
