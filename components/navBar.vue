<template>
  <!-- Navbar goes here -->
  <nav class="bg-white shadow-lg">
    <!--Define el contenedor y un efecto de popup con la sombra-->
    <div class="max-w-6xl mx-auto px-4">
      <!--tiene los estilos necesarios para definir caracteristicas para el 
      contenedor. Como un limite en el ancho de 1152px-->
      <div class="flex justify-between space-x-7">
        <!--Define el comportamiento flexible-->
        <!--<div class="flex space-x-7"> space-x-7 aplica a los elementos hijos un margin-left: 1.75rem; /* 28px */
					
				</div>-->
        <!-- Website Logo -->
        <div>
          <a href="#" class="flex items-center py-4 px-2">
            <img src="logo.png" alt="Logo" class="h-8 w-8 mr-2" />
            <span class="font-semibold text-gray-500 text-lg">Navigation</span>
          </a>
        </div>
        <!-- Primary Navbar items -->
        <div class="hidden md:flex items-center space-x-1">
          <!--hidden class hides the navbar items when viewed in a small screen size.-->
          <a href="" class="py-4 px-2 text-green-500 border-b-4 border-green-500 font-semibold">Home</a>
          <!--transition class makes the hover effect have a delay to make it appealing.
              duration-300 class adds a transition delay of 300 milliseconds.-->
          <a href=""
            class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300">Services</a>
          <a href="" class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300">About</a>
          <a href="" class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300">Contact
            Us</a>
        </div>
        <div class="md:hidden  items-center">
          <button class="outline-none mobile-menu-button">
            <svg class="w-6 h-6 text-gray-500" x-show="!showMenu" fill="none" stroke-linecap="round"
              stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor">
              <path d="M4 6h16M4 12h16M4 18h16"></path>
            </svg>
          </button>
        </div>
      </div>

    </div>
  </nav>
</template>
