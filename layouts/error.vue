<template>
  <div
    class="bg-gradient-to-tr from-gray-900 to-gray-800 text-white min-h-screen flex items-center"
  >
    <div class="container mx-auto p-4 flex flex-wrap items-center">
      <div class="w-full md:w-5/12 text-center p-4">
        <img src="https://themichailov.com/img/not-found.svg" alt="Not Found" />
      </div>
      <div class="w-full md:w-7/12 text-center md:text-left p-4">
        <div class="text-6xl font-medium">404</div>
        <div class="text-xl md:text-3xl font-medium mb-4">
          Oops. Cette page n'existe pas.
        </div>
        <div class="text-lg mb-8">
          Vous avez peut-être mal saisi l'adresse ou la page a peut-être été
          déplacée.
        </div>
        <nuxt-link
          to="/"
          class="border border-yellow-900 text-yellow-900 rounded p-4"
          >Go Accueil</nuxt-link
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
