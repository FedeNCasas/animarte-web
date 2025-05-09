<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AnimArte San Juan</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>
<body class="bg-white text-gray-800">

  <!-- Header -->
  <header class="fixed w-full top-0 bg-white shadow z-50 flex justify-between items-center p-4">
    <h1 class="text-orange-500 font-bold text-xl">AnimArte</h1>
    <div class="flex gap-4">
      <a href="https://www.instagram.com/s/aGlnaGxpZ2h0OjE3OTg5MjY5NTA2MjE1MTY4" target="_blank" class="text-orange-500">IG</a>
      <a href="https://www.facebook.com/animarte.sanjuan" target="_blank" class="text-orange-500">FB</a>
      <a href="https://maps.app.goo.gl/6ARj9PBmQ12aJtmLA" target="_blank" class="text-orange-500">Maps</a>
    </div>
  </header>

  <!-- Hero -->
  <section class="pt-24 text-center p-6 bg-orange-100" data-aos="fade-down">
    <h2 class="text-3xl font-bold text-orange-600">¡Bienvenid@ a AnimArte San Juan!</h2>
    <p class="mt-2">Recreación que contagia alegría 🎉</p>
    <a href="#propuestas" class="mt-4 inline-block bg-orange-500 text-white px-6 py-2 rounded-full hover:bg-orange-600 transition">Elegí tu propuesta</a>
  </section>

  <!-- Propuestas -->
  <section id="propuestas" class="p-6" data-aos="fade-up">
    <h3 class="text-2xl font-semibold mb-4 text-orange-600">Propuestas</h3>
    <div class="grid md:grid-cols-2 gap-6">
      <div class="border rounded-xl p-4 shadow hover:shadow-lg transition">
        <img src="/mnt/data/475872232_2200517647008935_6123000362082530224_n.jpg" alt="Kermés" class="rounded mb-2">
        <h4 class="text-xl font-bold">🎪 Kermés <span class="text-green-600">$</span></h4>
        <p>Juegos tradicionales en coloridas carpas que llenan de alegría cualquier espacio.</p>
      </div>
      <div class="border rounded-xl p-4 shadow hover:shadow-lg transition">
        <img src="/mnt/data/8d0e34f1-ea3c-466f-acb2-10aed1360d4f.png" alt="Juegos Cooperativos" class="rounded mb-2">
        <h4 class="text-xl font-bold">🌈 Juegos Cooperativos <span class="text-green-600">$</span></h4>
        <p>Dinámicas con paracaídas y juegos grupales que promueven la alegría y el trabajo en equipo.</p>
      </div>
    </div>
  </section>

  <!-- Adicionales -->
  <section class="p-6 bg-orange-50" data-aos="fade-up">
    <h3 class="text-2xl font-semibold mb-4 text-orange-600">Adicionales</h3>
    <div class="grid md:grid-cols-2 gap-6">
      <div class="border rounded-xl p-4 shadow hover:shadow-lg transition">
        <img src="/mnt/data/491441543_18074288689849714_2999441093933010812_n.jpg" alt="Espuma" class="rounded mb-2">
        <h4 class="text-xl font-bold">🎨 Maquillaje artístico <span class="text-green-600">$</span></h4>
        <p>Transformamos caritas en personajes mágicos y coloridos.</p>
      </div>
    </div>
  </section>

  <!-- Quiénes somos -->
  <section class="p-6 text-center" data-aos="fade-in">
    <h3 class="text-2xl font-semibold text-orange-600 mb-2">¿Quiénes somos?</h3>
    <p class="max-w-2xl mx-auto">Somos una familia que ama jugar, crear y compartir. Nuestro propósito es regalar sonrisas, momentos únicos y experiencias llenas de magia en cada evento. ¡Lo hacemos con el corazón! ❤️</p>
  </section>

  <!-- Contacto -->
  <section class="p-6 bg-orange-100" data-aos="fade-in">
    <h3 class="text-2xl font-semibold text-orange-600 mb-2">Contacto</h3>
    <p>
      📍 San Juan, Argentina<br>
      📱 WhatsApp: <a href="https://wa.me/5492645123339" class="text-blue-600">+54 9 264 5123339</a><br>
      📧 Mail: <a href="mailto:animarte@gmail.com" class="text-blue-600">animarte@gmail.com</a><br>
      📸 Redes:
      <a href="https://www.instagram.com/s/aGlnaGxpZ2h0OjE3OTg5MjY5NTA2MjE1MTY4" target="_blank" class="text-blue-600">Instagram</a> /
      <a href="https://www.facebook.com/animarte.sanjuan" target="_blank" class="text-blue-600">Facebook</a> /
      <a href="https://maps.app.goo.gl/6ARj9PBmQ12aJtmLA" target="_blank" class="text-blue-600">Google Maps</a>
    </p>
  </section>

  <!-- Botón WhatsApp flotante -->
  <a href="https://wa.me/5492645123339" class="fixed bottom-4 right-4 bg-green-500 hover:bg-green-600 text-white p-4 rounded-full shadow-lg z-50">
    📲
  </a>

  <!-- Servicios Detallados -->
  <section class="p-6" data-aos="fade-in">
    <h3 class="text-2xl font-semibold text-orange-600 mb-4">Servicios y Precios</h3>
    <div class="bg-white shadow p-4 rounded-xl">
      <p><strong>Pack Básico:</strong> Dos profes, dos horas de juegos divertidos, deportivos y tradicionales, sin decoración extra ni sonido. <br>💰 <strong>$70.000</strong></p>
      <p class="mt-2"><strong>Propuesta Premium:</strong> Dos profes, 2 horas de animación con sonido, decoración con banderines y paracaídas, juegos personalizados. <br>💰 <strong>$120.000</strong></p>
      <p class="mt-4"><strong>Adicionales:</strong> Slime, maquillaje, globología, inflables, deslizadores inflables, burbujas gigantes, fiesta de la espuma.</p>
      <p class="mt-4"><strong>Servicio de Candy - Animarte Candy:</strong></p>
      <ul class="list-disc pl-6">
        <li><strong>Opción 1:</strong> 30 copos - 1 hora - $60.000</li>
        <li><strong>Opción 2:</strong> 30 copos + 30 pochoclos - 1 hora - $80.000</li>
        <li><strong>Opción 3:</strong> Carro dulce libre por 1 hora - $120.000 (eventos infantiles)</li>
        <li><strong>Copos para retirar:</strong> $1.000 c/u - más de 30 unidades $800 c/u</li>
      </ul>
    </div>
  </section>

  <script>
    AOS.init();
  </script>
</body>
</html>
