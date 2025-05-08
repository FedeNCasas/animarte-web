<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AnimArte San Juan</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff8f0;
      background-image: url('https://images.unsplash.com/photo-1600880292203-757bb62b4baf');
      background-size: cover;
      background-repeat: no-repeat;
      background-attachment: fixed;
    }
    header {
      background-color: rgba(255, 127, 0, 0.95);
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }
    header h1 {
      margin: 0;
      font-size: 1.5rem;
    }
    nav {
      display: flex;
      gap: 1rem;
      align-items: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .btn-instagram {
      background-color: white;
      color: #ff7f00;
      padding: 0.4rem 0.8rem;
      border-radius: 5px;
      font-weight: bold;
    }
    section {
      padding: 2rem;
      background-color: rgba(255, 255, 255, 0.9);
      margin: 1rem;
      border-radius: 12px;
    }
    h2 {
      color: #ff7f00;
    }
    .propuesta, .adicional {
      margin-bottom: 1rem;
      padding: 1rem;
      background-color: #fff;
      border-left: 5px solid #ff7f00;
    }
    form {
      background-color: #f9f9f9;
      padding: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    input, select, textarea {
      width: 100%;
      padding: 0.5rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      background-color: #ff7f00;
      color: white;
      padding: 0.8rem 1.2rem;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background-color: #e76f00;
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

  <section id="propuestas">
    <h2>Propuestas Principales</h2>
    <div class="propuesta">🎪 <strong>Kermés:</strong> Juegos tradicionales para todas las edades.</div>
    <div class="propuesta">🥁 <strong>Taller de Murga:</strong> Ritmo, vestuario y expresión corporal.</div>
    <div class="propuesta">🏃‍♂️ <strong>Propuesta Deportiva:</strong> Carreras, juegos y desafíos físicos.</div>
    <div class="propuesta">💦 <strong>Propuesta Acuática:</strong> Juegos con agua para días de calor.</div>
    <div class="propuesta">🤝 <strong>Juegos Cooperativos:</strong> Diversión que une sin competir.</div>
    <div class="propuesta">🎨 <strong>Propuesta Artística:</strong> Talleres de arte, pintura y manualidades.</div>
  </section>

  <section id="adicionales">
    <h2>Adicionales que podés sumar</h2>
    <div class="adicional">Slime</div>
    <div class="adicional">Maquillaje artístico</div>
    <div class="adicional">Fiesta de la espuma</div>
    <div class="adicional">Globología</div>
    <div class="adicional">Inflables</div>
    <div class="adicional">Deslizadores inflables</div>
    <div class="adicional">Burbujas gigantes</div>
  </section>

  <section id="quienes">
    <h2>¿Quiénes somos?</h2>
    <p>Somos AnimArte San Juan, una empresa familiar con más de una década de experiencia en eventos recreativos. Amamos lo que hacemos, cuidamos cada detalle y nos apasiona ver sonrisas en cada festejo.</p>
  </section>

  <section id="contacto">
    <h2>Pedí tu presupuesto</h2>
    <p>También podés agendar tu evento directamente desde <a href="https://wa.me/542645123339" target="_blank">nuestro WhatsApp</a> y coordinamos juntos el mejor plan para tu día especial.</p>
    <form>
      <label for="nombre">Nombre</label>
      <input type="text" id="nombre" name="nombre" required>

      <label for="evento">Tipo de evento</label>
      <input type="text" id="evento" name="evento" required>

      <label for="fecha">Fecha del evento</label>
      <input type="date" id="fecha" name="fecha">

      <label for="ubicacion">Ubicación</label>
      <input type="text" id="ubicacion" name="ubicacion">

      <label for="cantidad">Cantidad de niñ@s y edades</label>
      <textarea id="cantidad" name="cantidad"></textarea>

      <label for="propuesta">Propuesta elegida</label>
      <select id="propuesta" name="propuesta">
        <option>Kermés</option>
        <option>Taller de Murga</option>
        <option>Propuesta Deportiva</option>
        <option>Propuesta Acuática</option>
        <option>Juegos Cooperativos</option>
        <option>Propuesta Artística</option>
      </select>

      <label for="adicionales">Adicionales (opcional)</label>
      <textarea id="adicionales" name="adicionales" placeholder="Slime, maquillaje, inflables, etc."></textarea>

      <label for="contacto">WhatsApp o Email</label>
      <input type="text" id="contacto" name="contacto" required>

      <button type="submit">Enviar</button>
    </form>
  </section>

  <a class="floating-whatsapp" href="https://wa.me/542645123339" target="_blank">WhatsApp</a>
</body>
</html>
