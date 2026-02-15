<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lucas Gonzalez | Portafolio IT</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    *{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
    body{background:#0f172a;color:#e5e7eb;line-height:1.6}
    header{padding:80px 20px;text-align:center;background:linear-gradient(135deg,#2563eb,#0ea5e9)}
    header h1{font-size:2.8rem;font-weight:700}
    header p{margin-top:10px;font-size:1.2rem}
    section{padding:60px 20px;max-width:1100px;margin:auto}
    h2{font-size:2rem;margin-bottom:20px;color:#38bdf8}
    .skills,.projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
    .card{background:#020617;padding:20px;border-radius:16px;box-shadow:0 10px 25px rgba(0,0,0,.4)}
    .card h3{margin-bottom:10px;color:#e0f2fe}
    .card p{font-size:.95rem;color:#cbd5f5}
    footer{text-align:center;padding:30px;background:#020617}
    a.btn{display:inline-block;margin-top:15px;padding:12px 20px;background:#38bdf8;color:#020617;border-radius:30px;text-decoration:none;font-weight:600}
  </style>
</head>
<body>

<header>
  <h1>Lucas Gonzalez</h1>
  <p>Desarrollador Web Junior | Sistemas de Inventario | IT</p>
  <a class="btn" href="#contacto">Contactarme</a>
</header>

<section id="sobre-mi">
  <h2>Sobre mí</h2>
  <p>Soy desarrollador web junior enfocado en la creación de sistemas de inventario y aplicaciones web funcionales. Tengo experiencia con PHP, MySQL y desarrollo frontend, y estoy en constante aprendizaje en el área IT.</p>
</section>

<section id="habilidades">
  <h2>Habilidades</h2>
  <div class="skills">
    <div class="card"><h3>Frontend</h3><p>HTML, CSS, JavaScript, diseño responsive</p></div>
    <div class="card"><h3>Backend</h3><p>PHP, MySQL, XAMPP</p></div>
    <div class="card"><h3>Sistemas</h3><p>Control de stock, entradas y salidas, códigos de barras</p></div>
    <div class="card"><h3>Otros</h3><p>Canva, GitHub, nociones de QA, mantenimiento y reparación de equipos informáticos</p></div>
  </div>
</section>

<section id="proyectos">
  <h2>Proyectos</h2>
  <div class="projects">
    <div class="card">
      <h3>InventSystem</h3>
      <p>Sistema web para gestionar inventario de productos terminados. Incluye login, registro, entradas y salidas de stock y reportes.</p>
    </div>
    <div class="card">
      <h3>Login & Registro</h3>
      <p>Sistema de autenticación con PHP y MySQL usando XAMPP.</p>
    </div>
    <div class="card">
      <h3>Publicidad Digital</h3>
      <p>Diseños y publicaciones para Facebook e Instagram utilizando Canva.</p>
    </div>
  </div>
</section>

<section id="contacto">
  <h2>Contacto</h2>
  <p>📧 Email: lucas@email.com</p>

</section>

<footer>
  <p>© 2026 Lucas Gonzalez - Portafolio IT</p>
</footer>

</body>
</html>
