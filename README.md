<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AnimArte San Juan</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <style>
    body {
      background-image: url('/mnt/data/475963764_1631740734130775_3440810953045748882_n.jpg');
      background-size: cover;
      background-repeat: no-repeat;
      background-attachment: fixed;
    }
    nav a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body class="text-gray-800 bg-white bg-opacity-80">

  <!-- Header -->
  <header class="fixed w-full top-0 bg-white/90 shadow z-50 flex justify-between items-center px-4 py-3">
    <div class="flex items-center gap-2">
      <img src="/mnt/data/Diseño%20sin%20título.pdf" alt="Logo AnimArte" class="h-10">
      <span class="text-xl font-bold text-orange-500">AnimArte</span>
    </div>
    <nav class="flex gap-4 text-sm text-orange-600 font-medium">
      <a href="#propuestas">Propuestas</a>
      <a href="#adicionales">Adicionales</a>
      <a href="#quienes">¿Quiénes somos?</a>
      <a href="#contacto">Contacto</a>
      <a href="#formulario">Formulario</a>
    </nav>
  </header>

  <!-- Hero -->
  <section class="pt-28 text-center p-6 bg-orange-100 bg-opacity-80" data-aos="fade-down">
    <h2 class="text-3xl font-bold text-orange-600">¡Bienvenid@ a AnimArte San Juan!</h2>
    <p class="mt-2">Recreación que contagia alegría 🎉</p>
    <a href="#propuestas" class="mt-4 inline-block bg-orange-500 text-white px-6 py-2 rounded-full hover:bg-orange-600 transition">Elegí tu propuesta</a>
  </section>

  <!-- Propuestas -->
  <section id="propuestas" class="p-6" data-aos="fade-up">
    <h3 class="text-2xl font-semibold mb-4 text-orange-600">Propuestas</h3>
    <div class="grid md:grid-cols-2 gap-6">
      <div class="border rounded-xl p-4 shadow hover:shadow-lg transition bg-white/90">
        <img src="/mnt/data/475872232_2200517647008935_6123000362082530224_n.jpg" alt="Kermés" class="rounded mb-2">
        <h4 class="text-xl font-bold">🎪 Kermés <span class="text-green-600">$</span></h4>
        <p>Juegos tradicionales en coloridas carpas que llenan de alegría cualquier espacio.</p>
      </div>
      <div class="border rounded-xl p-4 shadow hover:shadow-lg transition bg-white/90">
        <img src="/mnt/data/8d0e34f1-ea3c-466f-acb2-10aed1360d4f.png" alt="Juegos Cooperativos" class="rounded mb-2">
        <h4 class="text-xl font-bold">🌈 Juegos Cooperativos <span class="text-green-600">$</span></h4>
        <p>Dinámicas con paracaídas y juegos grupales que promueven la alegría y el trabajo en equipo.</p>
      </div>
    </div>
  </section>

  <!-- Adicionales -->
  <section id="adicionales" class="p-6 bg-orange-50 bg-opacity-80" data-aos="fade-up">
    <h3 class="text-2xl font-semibold mb-4 text-orange-600">Adicionales</h3>
    <div class="grid md:grid-cols-2 gap-6">
      <div class="border rounded-xl p-4 shadow hover:shadow-lg transition bg-white/90">
        <img src="/mnt/data/491441543_18074288689849714_2999441093933010812_n.jpg" alt="Espuma" class="rounded mb-2">
        <h4 class="text-xl font-bold">🎨 Maquillaje artístico <span class="text-green-600">$</span></h4>
        <p>Transformamos caritas en personajes mágicos y coloridos.</p>
      </div>
    </div>
  </section>

  <!-- Quiénes somos -->
  <section id="quienes" class="p-6 text-center" data-aos="fade-in">
    <h3 class="text-2xl font-semibold text-orange-600 mb-2">¿Quiénes somos?</h3>
    <p class="max-w-2xl mx-auto bg-white/90 p-4 rounded-xl">Somos una familia que ama jugar, crear y compartir. Nuestro propósito es regalar sonrisas, momentos únicos y experiencias llenas de magia en cada evento. ¡Lo hacemos con el corazón! ❤️</p>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="p-6 bg-orange-100 bg-opacity-90" data-aos="fade-in">
    <h3 class="text-2xl font-semibold text-orange-600 mb-2">Contacto</h3>
    <p class="bg-white/90 p-4 rounded-xl">
      📍 San Juan, Argentina<br>
      📱 WhatsApp: <a href="https://wa.me/5492645411194" class="text-blue-600">+54 9 264 5411194</a><br>
      📧 Mail: <a href="mailto:animarte@gmail.com" class="text-blue-600">animarte@gmail.com</a><br>
      📸 Redes:
      <a href="https://www.instagram.com/s/aGlnaGxpZ2h0OjE3OTg5MjY5NTA2MjE1MTY4" target="_blank" class="text-blue-600">Instagram</a> /
      <a href="https://www.facebook.com/animarte.sanjuan" target="_blank" class="text-blue-600">Facebook</a> /
      <a href="https://maps.app.goo.gl/6ARj9PBmQ12aJtmLA" target="_blank" class="text-blue-600">Google Maps</a>
    </p>
  </section>

  <!-- Formulario -->
  <section id="formulario" class="p-6" data-aos="fade-up">
    <h3 class="text-2xl font-semibold text-orange-600 mb-2">Consultanos</h3>
    <form class="bg-white/90 p-4 rounded-xl grid gap-4 max-w-xl mx-auto">
      <input type="text" placeholder="Nombre y Apellido" class="border p-2 rounded">
      <input type="email" placeholder="Correo electrónico" class="border p-2 rounded">
      <textarea placeholder="Consulta o mensaje..." rows="4" class="border p-2 rounded"></textarea>
      <button type="submit" class="bg-orange-500 text-white py-2 px-4 rounded hover:bg-orange-600">Enviar</button>
    </form>
  </section>

  <!-- Botón WhatsApp flotante -->
  <a href="https://wa.me/5492645411194" class="fixed bottom-4 right-4 bg-green-500 hover:bg-green-600 text-white p-4 rounded-full shadow-lg z-50">
    📲
  </a>

  <script>
    AOS.init();
  </script>
</body>
</html>
