<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Perfil - Angela Becerra Amado</title>
  <style>
    :root{
      --bg:#f7f8fb; --card:#ffffff; --accent:#6c63ff; --muted:#6b7280;
      --glass: rgba(255,255,255,0.6);
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,var(--bg),#eef2ff);min-height:100vh;display:flex;align-items:center;justify-content:center;padding:32px}
    .container{width:100%;max-width:900px;background:var(--card);border-radius:14px;box-shadow:0 8px 30px rgba(20,20,50,0.08);overflow:hidden;border:1px solid rgba(16,24,40,0.04)}
    header{display:flex;gap:16px;align-items:center;padding:28px;background:linear-gradient(90deg,#fafafa,var(--glass));}
    .avatar{width:96px;height:96px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#ff9bd3);display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-size:28px}
    .title h1{margin:0;font-size:20px}
    .title p{margin:4px 0 0;color:var(--muted);font-size:14px}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px;padding:24px}
    .card{background:var(--card);padding:18px;border-radius:12px;border:1px solid rgba(16,24,40,0.03)}
    .label{font-size:12px;color:var(--muted);margin-bottom:6px}
    .value{font-size:16px;font-weight:600}
    .list{display:flex;flex-direction:column;gap:10px}
    .chip{display:inline-block;background:#f1f5ff;color:#1f2937;padding:6px 10px;border-radius:999px;font-size:13px;border:1px solid rgba(99,102,241,0.12)}
    footer{padding:18px;border-top:1px solid rgba(16,24,40,0.03);display:flex;justify-content:space-between;align-items:center}
    .meta{color:var(--muted);font-size:13px}
    /* responsive */
    @media (max-width:780px){.grid{grid-template-columns:1fr;}.avatar{width:72px;height:72px;font-size:22px}}
  </style>
</head>
<body>
  <div class="container" role="main">
    <header>
      <div class="avatar" aria-hidden="true">AB</div>
      <div class="title">
        <h1>Angela Becerra Amado</h1>
        <p>Estudiante • Semestre III</p>
      </div>
      <div style="margin-left:auto;text-align:right">
        <div style="font-size:13px;color:var(--muted)">Edad</div>
        <div style="font-weight:700">19 años</div>
      </div>
    </header>

    <div class="grid">
      <section class="card">
        <h3 style="margin:0 0 12px">Información académica</h3>
        <div class="list">
          <div>
            <div class="label">En dónde estudias</div>
            <div class="value">Universidad San Pablo &amp; Instituto del Sur</div>
          </div>

          <div>
            <div class="label">Curso</div>
            <div class="value">Pensamiento Computacional</div>
          </div>

          <div>
            <div class="label">Maestro</div>
            <div class="value">Ernesto Cuadros Vargas</div>
          </div>
        </div>

        <hr style="margin:16px 0;border:none;border-top:1px solid #f1f5f9" />

        <h3 style="margin:0 0 12px">Intereses y hobbies</h3>
        <div class="list">
          <div>
            <div class="label">Intereses</div>
            <div class="value">Las Artes</div>
          </div>
          <div>
            <div class="label">Hobbies</div>
            <div class="value">Dibujar y pintar</div>
          </div>
        </div>
      </section>

      <aside class="card">
        <h3 style="margin:0 0 12px">Contacto rápido</h3>
        <p style="margin:0 0 12px;color:var(--muted)">Aquí puedes añadir información de contacto, enlaces a portafolio o redes sociales.</p>

        <div style="display:flex;flex-wrap:wrap;gap:8px">
          <span class="chip">Semestre III</span>
          <span class="chip">Edad: 19</span>
          <span class="chip">Pensamiento Computacional</span>
        </div>

        <hr style="margin:14px 0;border:none;border-top:1px solid #f1f5f9" />

        <div>
          <div class="label">Profesor</div>
          <div class="value">Ernesto Cuadros Vargas</div>
        </div>

      </aside>
    </div>

    <footer>
      <div class="meta">Perfil generado automáticamente</div>
      <div style="font-size:13px;color:var(--muted)">Última actualización: <strong>26/10/2025</strong></div>
    </footer>
  </div>
</body>
</html>
<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Contacto - Angela Becerra Amado</title>
  <style>
    :root{
      --bg:#f8fafc;--card:#ffffff;--accent:#8b5cf6;--muted:#64748b;
      font-family:Inter,system-ui,-apple-system,'Segoe UI',Roboto,'Helvetica Neue',Arial;
    }
    body{margin:0;background:linear-gradient(180deg,var(--bg),#eef2ff);min-height:100vh;display:flex;align-items:center;justify-content:center;padding:32px}
    .container{width:100%;max-width:700px;background:var(--card);border-radius:16px;box-shadow:0 8px 30px rgba(20,20,50,0.08);overflow:hidden;border:1px solid rgba(16,24,40,0.04)}
    header{padding:28px;text-align:center;background:linear-gradient(90deg,#fafafa,var(--accent));color:white}
    header h1{margin:0;font-size:24px}
    main{padding:24px;display:flex;flex-direction:column;gap:20px}
    .info{display:flex;flex-direction:column;gap:8px}
    a{color:var(--accent);text-decoration:none}
    a:hover{text-decoration:underline}
    .card{background:var(--card);padding:16px;border-radius:12px;border:1px solid rgba(16,24,40,0.05)}
    .label{font-size:13px;color:var(--muted)}
    .value{font-size:16px;font-weight:600;margin-top:4px}
    footer{text-align:center;padding:18px;border-top:1px solid rgba(16,24,40,0.05);color:var(--muted);font-size:13px}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Contacto de Angela Becerra Amado</h1>
      <p style="font-size:14px;margin-top:6px">Estudiante de Administración de Negocios y Diseño de Modas</p>
    </header>

    <main>
      <div class="card">
        <div class="label">LinkedIn</div>
        <div class="value"><a href="https://www.linkedin.com/in/angela-becerra-0b6ab6345/" target="_blank">https://www.linkedin.com/in/angela-becerra-0b6ab6345/</a></div>
      </div>

      <div class="card">
        <div class="label">Correo electrónico</div>
        <div class="value"><a href="mailto:angela.becerraamado@gmail.com">angela.becerraamado@gmail.com</a></div>
      </div>

      <div class="card">
        <div class="label">Instagram</div>
        <div class="value"><a href="https://www.instagram.com/rosa_roja2023" target="_blank">@rosa_roja2023</a></div>
      </div>

      <div class="card">
        <div class="label">Carreras</div>
        <div class="value">Administración de Negocios y Diseño de Modas</div>
      </div>
    </main>

    <footer>
      <p>© 2025 Angela Becerra Amado — Página de contacto personal</p>
    </footer>
  </div>
</body>
</html>
