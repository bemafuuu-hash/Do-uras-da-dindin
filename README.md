[meus-links-site.html](https://github.com/user-attachments/files/22011956/meus-links-site.html)
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Meus Links</title>
  <meta name="description" content="Site simples com links para WhatsApp e Instagram." />
  <style>
    :root{
      --bg: #0f172a;
      --card: #111827cc;
      --text: #e5e7eb;
      --muted: #94a3b8;
      --accent: #22c55e;
    }
    *{box-sizing:border-box}
    body{
      margin:0; font-family: system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, "Helvetica Neue", Arial, "Apple Color Emoji", "Segoe UI Emoji";
      background: radial-gradient(1200px 600px at 20% -10%, #1e293b, transparent), radial-gradient(800px 600px at 80% 110%, #0b1020, transparent), var(--bg);
      color:var(--text);
      min-height:100svh; display:grid; place-items:center; padding:24px;
    }
    .card{
      width:min(620px,100%);
      background:linear-gradient(180deg, rgba(255,255,255,0.06), rgba(255,255,255,0.02));
      border:1px solid rgba(255,255,255,0.12);
      border-radius:24px; padding:32px; box-shadow:0 20px 80px rgba(0,0,0,0.4);
      backdrop-filter:saturate(140%) blur(10px);
    }
    h1{ margin:0 0 4px; font-size:clamp(24px, 4vw, 36px); letter-spacing:0.2px }
    p.lead{ margin:0 0 24px; color:var(--muted) }
    .links{ display:grid; gap:16px; grid-template-columns:1fr; }
    @media (min-width:560px){ .links{ grid-template-columns:1fr 1fr } }
    .btn{
      display:flex; align-items:center; justify-content:center; gap:12px;
      padding:16px 18px; border-radius:16px; text-decoration:none; font-weight:600; 
      border:1px solid rgba(255,255,255,0.12);
      background:#0b1220; transition: transform .08s ease, box-shadow .2s ease, border-color .2s ease;
      box-shadow:0 6px 24px rgba(0,0,0,.25);
      color:var(--text);
    }
    .btn:hover{ transform: translateY(-2px); box-shadow:0 10px 28px rgba(0,0,0,.35); border-color: rgba(255,255,255,0.22)}
    .btn:active{ transform: translateY(0) scale(.99) }
    .wa{ background: linear-gradient(180deg, rgba(34,197,94,0.18), rgba(34,197,94,0.08)), #0b1220 }
    .ig{ background: linear-gradient(180deg, rgba(236,72,153,0.18), rgba(59,130,246,0.08)), #0b1220 }
    .sub{ font-size:12px; font-weight:500; color:var(--muted); margin-top:8px; text-align:center }
    footer{margin-top:20px; text-align:center; color:var(--muted); font-size:12px}
    code{background:rgba(255,255,255,.08); padding:.15rem .4rem; border-radius:.4rem}
  </style>
</head>
<body>
  <main class="card" role="main">
    <h1>Meus Links</h1>
    <p class="lead">Clique para falar comigo no WhatsApp ou ver meu Instagram.</p>

    <section class="links" aria-label="Links principais">
      <!-- WhatsApp -->
      <a class="btn wa" 
         href="https://wa.me/5521960149010?text=Ol%C3%A1!%20Vim%20pelo%20site." 
         target="_blank" rel="noopener noreferrer" aria-label="Abrir conversa no WhatsApp">
        <span>Falar no WhatsApp</span>
      </a>

      <!-- Instagram -->
      <a class="btn ig" 
         href="https://www.instagram.com/sabores_da_dindim?igsh=MTc5enE5a3V2ajB1ag%3D%3D&utm_source=qr" 
         target="_blank" rel="noopener noreferrer" aria-label="Abrir perfil no Instagram">
        <span>Ver Instagram</span>
      </a>
    </section>

    <p class="sub">Dica: troque o número e o usuário nos links abaixo pelo seu.</p>

    <div style="margin-top:12px; font-size:13px; line-height:1.6">
      <div><strong>WhatsApp:</strong> <code>https://wa.me/<u>5521960149010</u>?text=Ol%C3%A1!%20Vim%20pelo%20site.</code></div>
      <div><strong>Instagram:</strong> <code>https://www.instagram.com/<u>sabores_da_dindim</u></code></div>
    </div>

    <footer>
      Feito com ❤ — você pode hospedar no GitHub Pages, Netlify ou Vercel.
    </footer>
  </main>
</body>
</html>
