<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>AI Second Brain — Early Access</title>
  <meta name="description" content="An AI agent that turns your notes into actions automatically. Join the waitlist and share feedback." />
  <style>
    :root{
      --bg:#0b0c10;--panel:#111217;--text:#e6e6e6;--muted:#b9bbc6;--accent:#7c5cff;--accent-2:#38bdf8;--ok:#22c55e;
    }
    *{box-sizing:border-box}
    body{margin:0;font:16px/1.6 system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial,sans-serif;background:radial-gradient(1200px 600px at 80% -20%,rgba(124,92,255,.15),transparent),radial-gradient(800px 400px at 0% -10%,rgba(56,189,248,.12),transparent),var(--bg);color:var(--text)}
    a{color:inherit}
    .container{max-width:1000px;margin:0 auto;padding:24px}
    .badge{display:inline-flex;align-items:center;gap:8px;background:rgba(124,92,255,.15);border:1px solid rgba(124,92,255,.35);color:#dcd6ff;padding:8px 12px;border-radius:999px;font-weight:600;font-size:14px}
    header{padding:64px 0 24px}
    h1{font-size:44px;line-height:1.1;margin:18px 0 12px;letter-spacing:-0.02em}
    h2{font-size:28px;margin:0 0 12px}
    p.lead{color:var(--muted);font-size:18px;margin:0 0 20px}
    .cta{display:flex;gap:12px;flex-wrap:wrap}
    .btn{background:linear-gradient(135deg,var(--accent),var(--accent-2));border:none;color:white;padding:12px 18px;border-radius:14px;font-weight:700;cursor:pointer;text-decoration:none}
    .btn.secondary{background:#1b1e27;color:var(--text);border:1px solid #2a2f3a}
    .card{background:linear-gradient(180deg,#12131a,#0f1117);border:1px solid #232735;border-radius:18px;padding:20px}
    .grid{display:grid;gap:16px}
    @media(min-width:800px){.grid.cols-3{grid-template-columns:repeat(3,1fr)}.grid.cols-2{grid-template-columns:repeat(2,1fr)}}
    .feature h3{margin:8px 0 6px;font-size:18px}
    .muted{color:var(--muted)}
    .step{display:flex;gap:12px}
    .step-num{flex:0 0 36px;height:36px;border-radius:10px;background:#1b1e27;border:1px solid #2a2f3a;display:flex;align-items:center;justify-content:center;font-weight:800;color:#c9ccf5}
    .footer{padding:48px 0 24px;color:#9aa0aa;font-size:14px}
    .kudos{display:inline-block;margin-top:10px;color:#c3c7ff}
    .section{padding:36px 0}
    .form-embed{width:100%;min-height:600px;border:none;background:#0e1117;border-radius:14px}
    .note{font-size:14px;color:#AAB1C2}
    .pill{display:inline-block;padding:4px 10px;border-radius:999px;background:#142135;border:1px solid #22314a;color:#d2e5ff;font-size:12px;font-weight:700}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <span class="badge">🚀 Early Access • Built by a 15‑year‑old student</span>
      <h1>Your notes, turned into actions — automatically.</h1>
      <p class="lead">An AI agent that manages your digital life like a second brain. Tell it what you want — it organizes notes, creates tasks, and plans your week.</p>
      <div class="cta">
        <a href="#waitlist" class="btn">Get early access</a>
        <a href="#how" class="btn secondary">How it works</a>
      </div>
      <span class="kudos">Hi! I’m a 15‑year‑old high school student building this. I’d love your feedback — fill out the form below. 🙌</span>
    </header>
<
    <section class="section">
      <div class="grid cols-3">
        <div class="card feature">
          <div class="pill">Natural language</div>
          <h3>Give simple instructions</h3>
          <p class="muted">“Summarize my notes into tasks.” “Plan my week from deadlines.” The agent does the work.</p>
        </div>
        <div class="card feature">
          <div class="pill">Works with notes</div>
          <h3>Reads your workspace</h3>
          <p class="muted">Connect your notes; it organizes pages, links tasks to projects, and keeps things tidy.</p>
        </div>
        <div class="card feature">
          <div class="pill">Automates</div>
          <h3>Creates tasks & reminders</h3>
          <p class="muted">Auto‑creates to‑dos, dates, and a weekly plan. Optional calendar sync.</p>
        </div>
      </div>
    </section>
<
    <section id="how" class="section">
      <h2>How it works</h2>
      <div class="grid cols-2">
        <div class="card step"><div class="step-num">1</div><div><strong>Connect notes</strong><div class="muted">Bring your notes (or start fresh). The agent can read and organize them.</div></div></div>
        <div class="card step"><div class="step-num">2</div><div><strong>Give an instruction</strong><div class="muted">Use plain language: “Turn meeting notes into action items.”</div></div></div>
        <div class="card step"><div class="step-num">3</div><div><strong>Agent acts</strong><div class="muted">It updates your workspace — pages, tasks, links — automatically.</div></div></div>
        <div class="card step"><div class="step-num">4</div><div><strong>Review & tweak</strong><div class="muted">You stay in control. Approve edits, set reminders, and ship.</div></div></div>
      </div>
    </section>
<
    <section id="waitlist" class="section">
      <h2>Join the waitlist & share feedback</h2>
      <p class="muted">I’m a 15‑year‑old high school student making this solo. Your feedback shapes what I build next — please leave your email and how you’d use it.</p>
      <!-- 📝 Replace the iframe below with your Google Form embed code (make sure to set the email question as required). Add &embedded=true at the end of the URL. -->
      <iframe class="form-embed" src="https://docs.google.com/forms/d/e/1FAIpQLSfhcuPI3aIuLLNwZ8R0v0aofBgHtvb058qdlQ2tZf0Fl40JNw/viewform?usp=sharing&ouid=112591996445788615123" title="Feedback Form"></iframe>
      <p class="note">If the form doesn’t load, you can open it in a new tab: <a href="https://docs.google.com/forms/d/e/1FAIpQLSfhcuPI3aIuLLNwZ8R0v0aofBgHtvb058qdlQ2tZf0Fl40JNw/viewform?usp=sharing&ouid=112591996445788615123" target="_blank" rel="noopener">Open feedback form</a></p>
    </section>
<
    <section class="section">
      <div class="card">
        <h3>Privacy-first</h3>
        <p class="muted">Your notes are yours. For the MVP, we’ll keep data local or request explicit permission before connecting any external tools.</p>
      </div>
    </section>
<
    <footer class="footer">
      <div class="muted">© <span id="year"></span> AI Second Brain · Built by a student  </div>
    </footer>
  </div>
  <script>document.getElementById('year').textContent=new Date().getFullYear()</script>
</body>
</html>
# second-brain-landing
