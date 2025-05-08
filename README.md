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
    .button-destacado {
      background: linear-gradient(45deg, #ff7f00, #ffcd00);
      border: none;
      color: white;
      padding: 1rem 2rem;
      font-size: 1.2rem;
      font-weight: bold;
      border-radius: 10px;
      text-decoration: none;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      transition: transform 0.2s ease;
    }
    .button-destacado:hover {
      transform: scale(1.05);
    }
    .proposal-list {
      display: flex;
      flex-direction: column;
      gap: 1.5rem;
    }
    .proposal-item, .adicional-item {
      background-color: #fff0e0;
      padding: 1rem;
      border: 2px solid #ff7f00;
      border-radius: 10px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    .proposal-item:hover, .adicional-item:hover {
      background-color: #ffe2c2;
    }
    .proposal-image, .adicional-image {
      display: none;
      margin-top: 1rem;
    }
    .proposal-item.active .proposal-image,
    .adicional-item.active .adicional-image {
      display: block;
      width: 100%;
      max-width: 500px;
      border-radius: 10px;
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
      <a href="#inicio">Inicio</a>
      <a href="#propuestas">Propuestas</a>
      <a href="#adicionales">Adicionales</a>
      <a href="#quienes">¿Quiénes somos?</a>
      <a href="#contacto">Contacto</a>
      <a class="btn-instagram" href="https://www.instagram.com/animarte.sanjuan/" target="_blank">Instagram</a>
    </nav>
  </header>

  <section id="inicio" class="section-container">
    <h2>Bienvenid@ a AnimArte</h2>
    <a href="#propuestas" class="button-destacado">Elegí tu propuesta</a>
  </section>

  <section id="propuestas" class="section-container">
    <h2>Propuestas Principales</h2>
    <div class="proposal-list">
      <div class="proposal-item" onclick="toggleImage(this)">🎪 <strong>Kermés</strong> – Juegos tradicionales llenos de color
        <img class="proposal-image" src="https://via.placeholder.com/500x300.png?text=Ni%C3%B1os+jugando+Kerm%C3%A9s" alt="Kermés">
      </div>
      <div class="proposal-item" onclick="toggleImage(this)">🥁 <strong>Taller de Murga</strong> – Ritmo, expresión y disfraces
        <img class="proposal-image" src="https://via.placeholder.com/500x300.png?text=Murga+con+ni%C3%B1os" alt="Murga">
      </div>
      <div class="proposal-item" onclick="toggleImage(this)">🏃‍♂️ <strong>Propuesta Deportiva</strong> – Actividad física y desafíos
        <img class="proposal-image" src="https://via.placeholder.com/500x300.png?text=Juegos+deportivos+infantiles" alt="Deportiva">
      </div>
      <div class="proposal-item" onclick="toggleImage(this)">💦 <strong>Propuesta Acuática</strong> – Diversión a puro agua
        <img class="proposal-image" src="https://via.placeholder.com/500x300.png?text=Ni%C3%B1os+con+agua" alt="Acuática">
      </div>
      <div class="proposal-item" onclick="toggleImage(this)">🤝 <strong>Juegos Cooperativos</strong> – Trabajar en equipo jugando
        <img class="proposal-image" src="https://via.placeholder.com/500x300.png?text=Cooperaci%C3%B3n+entre+ni%C3%B1os" alt="Cooperativos">
      </div>
      <div class="proposal-item" onclick="toggleImage(this)">🎨 <strong>Propuesta Artística</strong> – Pintura, creatividad y arte
        <img class="proposal-image" src="https://via.placeholder.com/500x300.png?text=Arte+infantil" alt="Artística">
      </div>
    </div>
  </section>

  <section id="adicionales" class="section-container">
    <h2>Adicionales</h2>
    <div class="proposal-list">
      <div class="adicional-item" onclic
