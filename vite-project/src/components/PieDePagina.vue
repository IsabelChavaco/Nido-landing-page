<template>
    <footer class="bg-white border-t mt-12 py-8 text-center text-sm text-gray-500">
      <div class="container mx-auto px-4">
        <div class="flex flex-col md:flex-row justify-between items-center">
          <!-- Logo y navegación -->
          <div class="flex flex-col items-center md:items-start">
            <div class="flex items-center mb-2">
              <img src="/logo-nido.svg" alt="NIDO" class="h-6 mr-2" />
              <span class="font-bold text-black">NIDO</span>
            </div>
            <div class="flex space-x-4 mb-4 md:mb-0">
              <a href="#" class="hover:text-black">Inicio</a>
              <a href="#" class="hover:text-black">Esto es NIDO</a>
              <a href="#" class="hover:text-black">Comunidad</a>
              <a href="#" class="hover:text-black">Programas</a>
            </div>
            <div class="flex space-x-4 text-gray-600 text-lg">
              <a href="#"><i class="fab fa-facebook"></i></a>
              <a href="#"><i class="fab fa-instagram"></i></a>
              <a href="#"><i class="fab fa-twitter"></i></a>
              <a href="#"><i class="fas fa-envelope"></i></a>
            </div>
          </div>
  
          <!-- Dirección -->
          <div class="mt-6 md:mt-0">
            <p class="text-gray-700">Avenida 123 # 12 – 34 Cali, Colombia</p>
            <div class="flex justify-center md:justify-end mt-2">
              <span class="mr-1">🌐</span>
              <select class="text-sm border rounded px-2 py-1">
                <option value="es">Español</option>
                <option value="en" selected>English</option>
              </select>
            </div>
          </div>
        </div>
  
        <!-- Derechos -->
        <div class="mt-6 text-gray-400">
          © 2025 NIDO
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'PieDePagina',
  }
  </script>
  
  <style scoped>
  /* Puedes incluir estilos adicionales si no usas Tailwind */
  </style>
