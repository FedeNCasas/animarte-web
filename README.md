<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Seleccionar Adicionales</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gradient-to-br from-yellow-50 via-pink-50 to-orange-100 min-h-screen p-8">
  <div class="max-w-3xl mx-auto bg-white shadow-lg rounded-xl p-6">
    <h1 class="text-3xl font-bold text-center text-orange-500 mb-4">🎁 Elegí tus adicionales</h1>
    <form id="formAdicionales" class="space-y-4">
      <div class="space-y-2">
        <label class="flex items-center gap-2">
          <input type="checkbox" name="adicionales" value="Slime">
          🎈 Slime - $10.000
        </label>
        <label class="flex items-center gap-2">
          <input type="checkbox" name="adicionales" value="Maquillaje artístico">
          🎨 Maquillaje artístico - $10.000
        </label>
        <label class="flex items-center gap-2">
          <input type="checkbox" name="adicionales" value="Globología">
          🎈 Globología - $10.000
        </label>
        <label class="flex items-center gap-2">
          <input type="checkbox" name="adicionales" value="Inflables">
          🏰 Inflables - $20.000
        </label>
        <label class="flex items-center gap-2">
          <input type="checkbox" name="adicionales" value="Deslizadores inflables">
          🛷 Deslizadores inflables - $20.000
        </label>
        <label class="flex items-center gap-2">
          <input type="checkbox" name="adicionales" value="Burbujas gigantes">
          🔵 Burbujas gigantes - $15.000
        </label>
        <label class="flex items-center gap-2">
          <input type="checkbox" name="adicionales" value="Fiesta de la espuma">
          🎊 Fiesta de la espuma - $25.000
        </label>
        <label class="flex items-center gap-2">
          <input type="checkbox" name="adicionales" value="Sin adicionales" id="sinAdicionales">
          ❌ Sin adicionales
        </label>
      </div>
      <div class="text-center mt-6">
        <button type="submit" class="bg-orange-500 hover:bg-orange-600 text-white px-6 py-3 rounded-full shadow font-semibold transition">Continuar por WhatsApp</button>
      </div>
    </form>
  </div>

  <script>
    const form = document.getElementById('formAdicionales');
    const sinAdicionales = document.getElementById('sinAdicionales');

    form.addEventListener('submit', function (e) {
      e.preventDefault();
      const seleccionados = [];
      form.querySelectorAll('input[type=checkbox]:checked').forEach(input => {
        if (input.value !== 'Sin adicionales') seleccionados.push(input.value);
      });

      const mensaje = seleccionados.length > 0 ?
        `Hola, quiero reservar una propuesta con los siguientes adicionales: ${seleccionados.join(', ')}` :
        `Hola, quiero reservar una propuesta sin adicionales.`;

      const url = `https://wa.me/5492645123339?text=${encodeURIComponent(mensaje)}`;
      window.open(url, '_blank');
    });
  </script>
</body>
</html>
