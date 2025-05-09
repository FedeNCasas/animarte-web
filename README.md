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
    html {
      scroll-behavior: smooth;
    }
    body {
      background-image: url('/mnt/data/475963764_1631740734130775_3440810953045748882_n.jpg');
      background-size: cover;
      background-repeat: no-repeat;
      background-attachment: fixed;
    }
    nav a {
      transition: all 0.3s ease;
    }
    nav a:hover,
    nav a.active {
      color: #fb923c;
      font-weight: bold;
    }
    .galeria img {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      border: 4px solid #fb923c;
    }
    .galeria img:hover {
      transform: scale(1.05);
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
    }
    #loader {
      position: fixed;
      z-index: 9999;
      background: white;
      width: 100vw;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .loader-logo {
      animation: bounce 1.2s infinite;
    }
    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }
  </style>
</head>
<body class="text-gray-800 bg-white bg-opacity-80">

  <!-- Loader -->
  <div id="loader">
    <img src="/mnt/data/Diseño%20sin%20título.pdf" alt="Cargando AnimArte..." class="h-24 loader-logo">
  </div>

  <!-- Header -->
  <header class="fixed w-full top-0 bg-white/90 shadow z-50 flex justify-between items-center px-6 py-4">
    <div class="flex items-center gap-3">
      <img src="/mnt/data/Diseño%20sin%20título.pdf" alt="Logo AnimArte" class="h-10">
      <span class="text-xl font-bold text-orange-500">AnimArte</span>
    </div>
    <nav class="flex gap-6 text-sm text-gray-800 font-medium">
      <a href="#" class="active">Home</a>
      <a href="#propuestas">Servicios</a>
      <a href="#galeria">Galería</a>
      <a href="#contacto">Contacto</a>
      <a href="#formulario">Reservas</a>
    </nav>
  </header>

  <!-- Hero -->
  <section class="pt-28 text-center p-6 bg-gradient-to-br from-orange-200 via-white to-orange-100 bg-opacity-90" data-aos="fade-down">
    <h2 class="text-4xl font-extrabold text-orange-600 drop-shadow-sm">¡Bienvenid@ a AnimArte San Juan!</h2>
    <p class="mt-4 text-lg">Diversión, color y alegría en cada evento 🎉</p>
    <a href="#propuestas" class="mt-6 inline-block bg-orange-500 text-white px-8 py-3 rounded-full hover:bg-orange-600 transition text-lg font-semibold shadow">Elegí tu propuesta</a>
  </section>

  <!-- Galería -->
  <section id="galeria" class="p-8 bg-white/90" data-aos="fade-in">
    <h3 class="text-3xl font-bold mb-6 text-center text-orange-600">Galería AnimArte 📸</h3>
    <div class="grid md:grid-cols-3 gap-6 galeria">
      <img src="/mnt/data/297741195_6017047334977996_5275350838111807804_n.jpg" class="rounded shadow">
      <img src="/mnt/data/491441543_18074288689849714_2999441093933010812_n.jpg" class="rounded shadow">
      <img src="/mnt/data/475963764_1631740734130775_3440810953045748882_n.jpg" class="rounded shadow">
      <img src="/mnt/data/475872232_2200517647008935_6123000362082530224_n.jpg" class="rounded shadow">
      <img src="/mnt/data/8d0e34f1-ea3c-466f-acb2-10aed1360d4f.png" class="rounded shadow">
    </div>
  </section>

  <!-- Botón WhatsApp flotante -->
  <a href="https://wa.me/5492645123339?text=Hola,%20mas%20informacion%20porfavor,%20nos%20interesa%20contratar%20el%20servicio%20%F0%9F%98%80%F0%9F%98%80" class="fixed bottom-4 right-4 bg-gradient-to-br from-pink-500 via-yellow-400 to-green-400 hover:brightness-110 text-white p-4 rounded-full shadow-lg z-50">
    📲
  </a>

  <script>
    AOS.init();
    window.addEventListener('load', () => {
      const loader = document.getElementById('loader');
      if (loader) loader.style.display = 'none';
    });
  </script>
</body>
</html>
