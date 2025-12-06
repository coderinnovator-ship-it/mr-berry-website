# mr-berry-website
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Mr berry</title>
<meta name="description" content="We sell different types of cars with the best price" />
<style>
  :root{--accent:#0f62fe;--text:#0f1724}
  body{font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Arial;margin:0;background:#f7f8fb;color:var(--text)}
  header{background:linear-gradient(90deg,var(--accent),#7c3aed);color:#fff;padding:28px 18px}
  .wrap{max-width:960px;margin:0 auto;padding:22px}
  .brand{display:flex;gap:14px;align-items:center}
  h1{margin:0;font-size:24px}
  .lead{margin:8px 0 0;opacity:.95}
  .card{background:#fff;border-radius:12px;padding:18px;margin-top:18px;box-shadow:0 8px 30px rgba(15,23,36,0.06)}
  .grid{display:flex;gap:18px;flex-wrap:wrap}
  .col{flex:1;min-width:220px}
  .muted{color:#6b7280}
  a{color:var(--accent);text-decoration:none}
  .hero{display:flex;justify-content:space-between;gap:12px;align-items:center}
  ul{padding-left:18px}
  footer{margin-top:22px;padding:12px;text-align:center;color:#6b7280}
  @media(max-width:720px){.hero{flex-direction:column;align-items:flex-start}}
</style>
</head>
<body>
  <header>
    <div class="wrap">
      <div class="brand">
        <div style="display:flex;align-items:center"><div style="width:56px;height:56px;border-radius:10px;background:linear-gradient(135deg,#0f62fe,#7c3aed);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700">M</div></div>
        <div>
          <h1>Mr berry</h1>
          <div style="margin-top:6px;color:#fff;opacity:.95">我們是最棒的</div>
        </div>
      </div>
    </div>
  </header>

  <div class="wrap">
    <section class="card hero">
      <div style="flex:1">
        <h2 style="margin:0">Selling of cars</h2>
        <p class="muted" style="margin-top:6px">We sell different types of cars with the best price</p>
        <div style="margin-top:12px">
        <p>
          <a href="mailto:coderinnovator@gmail.com">coderinnovator@gmail.com</a>
          
          
        </p>
      <p class="muted">Wuhan china</p></div>
        
      </div>
      <div style="min-width:220px">
        <div style="background:#fafafa;padding:12px;border-radius:10px">
          <strong>Working Hours</strong>
          <p class="muted" style="margin-top:8px">Always available</p>
        </div>
      </div>
    </section>

    <section class="card" id="services">
      <h3>Services</h3>
      <div class="grid">
        <div class="col">
          <p class="muted">Selling of cars</p>
          <ul><li>Fast</li><li>reliable</li></ul>
        </div>
        <div class="col">
          <p class="muted">Why choose us?</p>
          <ul>
            <li>Trusted · Experienced</li>
            <li>Quality & fast delivery</li>
            <li>Affordable pricing</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="card" id="contact">
      <h3>Contact</h3>
      <div class="grid">
        <div class="col">
          <p class="muted">Get in touch</p>
          
        <p>
          <a href="mailto:coderinnovator@gmail.com">coderinnovator@gmail.com</a>
          
          
        </p>
      
        </div>
        <div class="col">
          <p class="muted">Address</p>
          <p>Wuhan china</p>
        </div>
      </div>
    </section>

    <footer>
      &copy; 2025 Mr berry · Built with WebForge
    </footer>
  </div>
</body>
</html>
