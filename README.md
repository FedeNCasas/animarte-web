<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AnimArte San Juan</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff;
    }
    header {
      background-color: #ff7f00;
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 1.8rem;
    }
    nav {
      display: flex;
      gap: 1.5rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      font-size: 1rem;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .section-container {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 4rem 2rem;
    }
    .section-container:nth-child(even) {
      background-color: #fff8f0;
    }
    h2 {
      color: #ff7f00;
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    .content-box {
      max-width: 800px;
    }
    .floating-whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25d366;
      color: white;
      padding: 0.8rem 1rem;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 2px 6px rgba(0,0,0,0.3);
    }
    .btn-instagram {
      background-color: white;
      color: #ff7f00;
      padding: 0.4rem 0.8rem;
      border-radius: 5px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>AnimArte San Juan</h1>
    <nav>
      <a href="#propuestas">Propuestas</a>
      <a href="#adicionales">Adicionales</a>
      <a href="#quienes">¿Quiénes somos?</a>
      <a href="#contacto">Contacto</a>
      <a class="btn-instagram" href="https://www.instagram.com/animarte.sanjuan/" target="_blank">Instagram</a>
    </nav>
  </header>

  <section id="propuestas" class="section-container">
    <div class="content-box">
      <h2>Propuestas Principales</h2>
      <p>🎪 Kermés – Juegos tradicionales llenos de color<br>
      🥁 Taller de Murga – Ritmo, expresión y disfraces<br>
      🏃‍♂️ Propuesta Deportiva – Actividad física y desafíos<br>
      💦 Propuesta Acuática – Diversión a puro agua<br>
      🤝 Juegos Cooperativos – Trabajar en equipo jugando<br>
      🎨 Propuesta Artística – Pintura, creatividad y arte</p>
    </div>
  </section>

  <section id="adicionales" class="section-container">
    <div class="content-box">
      <h2>Adicionales</h2>
      <p>🎨 Maquillaje<br>
      🫧 Fiesta de la espuma<br>
      🎈 Globología<br>
      🛝 Inflables y deslizadores<br>
      🧪 Slime<br>
      🫧 Burbujas gigantes</p>
    </div>
  </section>

  <section id="quienes" class="section-container">
    <div class="content-box">
      <h2>¿Quiénes somos?</h2>
      <p>Somos una empresa familiar con más de 10 años de experiencia en el mundo de la recreación. Amamos lo que hacemos y eso se nota en cada sonrisa que provocamos.</p>
    </div>
  </section>

  <section id="contacto" class="section-container">
    <div class="content-box">
      <h2>Contacto</h2>
      <p>Podés pedir tu presupuesto o agendar directamente tu evento desde <a href="https://wa.me/542645123339" target="_blank">WhatsApp</a> y te ayudamos a armar una propuesta a medida para vos ✨</p>
    </div>
  </section>

  <a class="floating-whatsapp" href="https://wa.me/542645123339" target="_blank">WhatsApp</a>
</body>
</html>
