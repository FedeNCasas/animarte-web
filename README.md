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
      box-shadow: 0 2px 10px rgba(0,0,0,0.15);
    }
    .logo {
      height: 60px;
    }
    nav {
      display: flex;
      gap: 1.5rem;
      align-items: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      font-size: 1rem;
    }
    nav a img {
      height: 24px;
      vertical-align: middle;
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
      transition: all 0.3s ease-in-out;
    }
    .section-container:nth-child(even) {
      background-color: #fff8f0;
    }
    h2 {
      color: #ff7f00;
      font-size: 2.5rem;
      margin-bottom: 1.5rem;
      animation: fadeIn 1s ease-out;
    }
    .button-destacado {
      background: linear-gradient(90deg, #ff7f00, #ffcd00);
      border: none;
      color: white;
      padding: 1.2rem 2.5rem;
      font-size: 1.4rem;
      font-weight: bold;
      border-radius: 50px;
      text-decoration: none;
      box-shadow: 0 4px 12px rgba(0,0,0,0.25);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .button-destacado:hover {
      transform: scale(1.08);
      box-shadow: 0 6px 16px rgba(0,0,0,0.3);
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
      z-index: 1000;
    }
    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(20px);}
      to {opacity: 1; transform: translateY(0);}
    }
    .inicio-bg {
      background: linear-gradient(135deg, #ffe8c2, #fff0dc);
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Logo AnimArte" class="logo">
    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#propuestas">Propuestas</a>
      <a href="#adicionales">Adicionales</a>
      <a href="#quienes">¿Quiénes somos?</a>
      <a href="#contacto">Contacto</a>
      <a href="https://www.instagram.com/animarte.sanjuan/" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram"></a>
      <a href="https://www.facebook.com/animarte.sanjuan" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook"></a>
    </nav>
  </header>

  <section id="inicio" class="section-container inicio-bg">
    <h2>¡Bienvenid@ al mundo de la diversión!</h2>
    <p style="max-width: 600px; font-size: 1.2rem; color: #444; margin-bottom: 2rem;">
      En AnimArte hacemos que cada evento sea inolvidable. Con propuestas creativas y animación profesional, transformamos tu celebración en pura magia 🎉
    </p>
    <a href="#propuestas" class="button-destacado">Elegí tu propuesta</a>
  </section>

  <section id="propuestas" class="section-container">
    <h2>Propuestas Principales</h2>
    <div style="max-width: 800px; text-align: left;">
      <div style="margin-bottom: 2rem;">
        <h3>🎪 Kermés <span style="color: #28a745;">$</span></h3>
        <p>Una propuesta llena de juegos clásicos, feria, y mucha diversión para todas las edades.</p>
      </div>
      <div style="margin-bottom: 2rem;">
        <h3>🥁 Taller de Murga <span style="color: #28a745;">$</span></h3>
        <p>Ritmo, disfraces y mucha energía en un taller donde todos pueden expresarse al ritmo de los tambores.</p>
      </div>
      <div style="margin-bottom: 2rem;">
        <h3>🏃‍♂️ Propuesta Deportiva <span style="color: #28a745;">$</span></h3>
        <p>Ideal para grupos grandes. Juegos físicos, postas, desafíos y trabajo en equipo.</p>
      </div>
      <div style="margin-bottom: 2rem;">
        <h3>💦 Propuesta Acuática <span style="color: #28a745;">$</span></h3>
        <p>Perfecta para el verano. Juegos con agua, inflables húmedos y mucha risa.</p>
      </div>
      <div style="margin-bottom: 2rem;">
        <h3>🤝 Juegos Cooperativos <span style="color: #28a745;">$</span></h3>
        <p>Actividades donde el foco está en el trabajo grupal, la empatía y la diversión sin competencia.</p>
      </div>
      <div style="margin-bottom: 2rem;">
        <h3>🎨 Propuesta Artística <span style="color: #28a745;">$</span></h3>
        <p>Un espacio creativo con pintura, manualidades y creación libre. Ideal para dejar volar la imaginación.</p>
      </div>
    </div>
  </section>

  <section id="adicionales" class="section-container">
    <h2>Adicionales</h2>
    <div style="max-width: 800px; text-align: left;">
      <div onclick="toggleImage(this)" style="margin-bottom: 2rem; cursor: pointer;">
        <h3>🎨 Maquillaje <span style='color: #28a745;'>$</span></h3>
        <p>Colores, purpurina y mucha creatividad para que cada niñ@ se convierta en lo que imagine.</p>
        <img class="adicional-image" style="display:none; width:100%; max-width:500px; border-radius:10px;" src="https://via.placeholder.com/500x300.png?text=Maquillaje+Infantil" alt="Maquillaje">
      </div>
      <div onclick="toggleImage(this)" style="margin-bottom: 2rem; cursor: pointer;">
        <h3>🫧 Fiesta de la Espuma <span style='color: #28a745;'>$</span></h3>
        <p>Una explosión de burbujas para saltar, reír y refrescarse con alegría.</p>
        <img class="adicional-image" style="display:none; width:100%; max-width:500px; border-radius:10px;" src="https://via.placeholder.com/500x300.png?text=Fiesta+de+la+Espuma" alt="Espuma">
      </div>
      <div onclick="toggleImage(this)" style="margin-bottom: 2rem; cursor: pointer;">
        <h3>🎈 Globología <span style='color: #28a745;'>$</span></h3>
        <p>Figuras y animales hechos con globos para llevar magia a cada rincón del evento.</p>
        <img class="adicional-image" style="display:none; width:100%; max-width:500px; border-radius:10px;" src="https://via.placeholder.com/500x300.png?text=Globolog%C3%ADa" alt="Globología">
      </div>
      <div onclick="toggleImage(this)" style="margin-bottom: 2rem; cursor: pointer;">
        <h3>🛝 Inflables y Deslizadores <span style='color: #28a745;'>$</span></h3>
        <p>Juegos gigantes para saltar, correr y deslizarse. ¡Diversión garantizada!</p>
        <img class="adicional-image" style="display:none; width:100%; max-width:500px; border-radius:10px;" src="https://via.placeholder.com/500x300.png?text=Inflables+y+Deslizadores" alt="Inflables">
      </div>
      <div onclick="toggleImage(this)" style="margin-bottom: 2rem; cursor: pointer;">
        <h3>🧪 Slime <span style='color: #28a745;'>$</span></h3>
        <p>Taller sensorial donde crean, juegan y se llevan su slime a casa.</p>
        <img class="adicional-image" style="display:none; width:100%; max-width:500px; border-radius:10px;" src="https://via.placeholder.com/500x300.png?text=Taller+de+Slime" alt="Slime">
      </div>
      <div onclick="toggleImage(this)" style="margin-bottom: 2rem; cursor: pointer;">
        <h3>🫧 Burbujas Gigantes <span style='color: #28a745;'>$</span></h3>
        <p>¡Un espectáculo visual! Burbujas enormes para mirar, tocar y explotar.</p>
        <img class="adicional-image" style="display:none; width:100%; max-width:500px; border-radius:10px;" src="https://via.placeholder.com/500x300.png?text=Burbujas+Gigantes" alt="Burbujas">
      </div>
    </div>
  </section>

  <a class="floating-whatsapp" href="https://wa.me/542645123339" target="_blank">WhatsApp</a>

  <script>
    function toggleImage(element) {
      element.classList.toggle('active');
    }
  </script>
</body>
</html>
