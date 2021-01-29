<template>
  <div class="relative z-10 w-full h-60 px-12 bg-white flex justify-between">
    <nuxt-link
      to="/"
      class="block h-full flex items-center text-lg md:text-2xl font-bold tracking-widest text-gray-700 uppercase hover:text-gray-400"
      ><Logo
    /></nuxt-link>

    <a
      href="#"
      class="relative block px-3 bg-gray-700 text-white text-center tracking-widest uppercase text-xs font-bold pt-8 pb-6 flex flex-col items-center justify-between bg-gray-900"
    >
      <span>menu</span>
      <div class="flex items-end justify-center">
        <span class="block h-5 w-1 bg-yellow-900"></span>
        <span class="block h-8 w-1 bg-yellow-900 mx-1"></span>
        <span class="block h-5 w-1 bg-yellow-900"></span>
      </div>
    </a>
  </div>
</template>
