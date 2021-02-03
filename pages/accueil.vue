<template>
  <main>
    <div class="-mt-24 pt-24 w-full h-screen bg-white flex flex-wrap">
      <div
        class="px-12 md:-px-0 w-full md:w-4/12 bg-white flex items-center justify-start md:justify-end"
      >
        <div
          class="shadow-xl md:shadow-none px-12 py-12 md:pl-0 md:pr-24 bg-white md:-mr-64 relative z-10"
        >
          <h1
            class="mb-8 text-3xl md:text-5xl text-gray-800 text-bold uppercase font-bold tracking-widest leading-tight"
          >
            institut<br />Beauté<br />Détende
          </h1>
          <h2 class="text-lg md:text-2xl font-serif text-gray-500">
            {{ intro }}
          </h2>

          <span
            class="hidden md:block absolute top-0 right-0 w-48 h-4 bg-gray-900 -mr-24 mt-56"
          ></span>
        </div>
      </div>

      <div class="-mt-64 md:mt-0 w-full md:flex-1">
        <img
          src="~/assets/img/roberto-nickson-YCW4BEhKluw-unsplash (3).jpg"
          class="w-full h-full object-cover"
        />
      </div>
    </div>

    <div class="bg-gray-800 px-12 py-24 flex items-center">
      <div class="hidden md:block w-3/12"></div>

      <div class="flex-1 relative">
        <h2
          class="mb-8 uppercase text-yellow-900 text-2xl font-bold tracking-widest"
        >
          {{ titreAccroche }}
        </h2>
        <p
          class="font-serif text-gray-500 text-white md:text-xl max-w-2xl leading-loose"
        >
          {{ accroche }}
        </p>

        <span
          class="absolute top-0 left-0 w-4 h-full bg-gray-300 -ml-20"
        ></span>
      </div>
    </div>

    <!-- SPACER / -->
    <div class="w-full h-24 border-black bg-white flex justify-end">
      <div class="w-64 bg-gray-800"></div>
    </div>
    <!-- / SPACER -->

    <div class="w-full flex items-center justify-start relative">
      <div class="w-auto md:w-3/12"></div>

      <div class="w-full md:w-8/12 bg-gray-100 py-12 relative flex">
        <nuxt-link
          to="/soins"
          class="block relative z-10 shadow-xl bg-white h-full w-full px-12 md:px-0 md:w-6/12 py-24 md:-ml-24"
        >
          <h3
            class="mb-2 uppercase text-gray-800 pl-3 text-3xl font-bold tracking-widest"
          >
            {{ soins }}
          </h3>
          <p class="text-lg md:text-xl pl-3 font-serif text-gray-400">
            {{ texteSoin }}
          </p>
        </nuxt-link>

        <img
          src="~/assets/img/chalo-garcia-i5TVtJe7TlM-unsplash.jpg"
          class="absolute top-0 border border-yellow-900 left-0 block w-full h-full object-cover"
        />
      </div>

      <div class="w-1/12 absolute top-0 right-0 h-full bg-gray-800"></div>
    </div>

    <!-- SPACER / -->
    <div class="w-full h-12 border-black bg-white flex justify-end">
      <div class="w-64 bg-gray-800"></div>
    </div>
    <!-- / SPACER -->
    <nuxt-link to="/">Accueil</nuxt-link>
    <div class="w-full flex items-center justify-start relative">
      <div class="w-auto md:w-3/12"></div>

      <div class="w-full md:w-8/12 bg-gray-100 py-12 relative flex">
        <nuxt-link
          to="/aqua"
          class="block relative z-10 shadow-xl bg-white h-full w-full px-12 md:px-0 md:w-6/12 py-24 md:-ml-24"
        >
          <h3
            class="mb-2 uppercase text-gray-800 pl-3 text-3xl font-bold tracking-widest"
          >
            {{ aqua }}
          </h3>
          <p class="text-lg md:text-xl pl-3 font-serif text-gray-400">
            {{ texteAqua }}
          </p>
        </nuxt-link>

        <img
          src="~/assets/img/jared-rice-PibraWHb4h8-unsplash.jpg"
          class="absolute top-0 border border-yellow-900 left-0 block w-full h-full object-cover"
        />
      </div>

      <div class="w-1/12 absolute top-0 right-0 h-full bg-gray-800"></div>
    </div>

    <!-- SPACER / -->
    <div class="w-full h-12 border-black bg-white flex justify-end">
      <div class="w-64 bg-gray-800"></div>
    </div>
    <!-- / SPACER -->

    <div class="w-full flex items-center justify-start relative">
      <div class="w-auto md:w-3/12"></div>

      <div class="w-full md:w-8/12 bg-gray-100 py-12 relative flex">
        <nuxt-link
          to="/aqua"
          class="block relative z-10 shadow-xl bg-white h-full w-full px-12 md:px-0 md:w-6/12 py-24 md:-ml-24"
        >
          <h3
            class="mb-2 uppercase text-gray-800 text-3xl font-bold tracking-widest"
          >
            L'espace détente
          </h3>
          <p class="text-lg md:text-xl font-serif text-gray-400">
            Un espace dédié à la détente. et encore du texte parce que nous
            allons manquer de contenu.
          </p>
          <p class="text-lg md:text-xl font-serif text-gray-400">
            Un espace dédié à la détente. et encore du texte parce que nous
            allons manquer de contenu.
          </p>
        </nuxt-link>

        <img
          src="https://images.unsplash.com/photo-1545060894-7b45236d00b3?w=1200"
          class="absolute top-0 border border-yellow-900 left-0 block w-full h-full object-cover"
        />
      </div>

      <div class="w-1/12 absolute top-0 right-0 h-full bg-gray-800"></div>
    </div>

    <!-- SPACER / -->
    <div class="w-full h-24 border-black bg-white flex justify-end">
      <div class="w-64 bg-gray-800"></div>
    </div>
    <!-- / SPACER -->

    <div class="bg-gray-800 text-yellow-900">
      <div
        class="mx-auto max-w-5xl flex flex-wrap justify-center items-center text-center py-20"
      >
        <a href="#" class="w-full md:w-1/3 px-12">
          <h4
            class="mb-2 uppercase text-gray-100 text-lg font-bold tracking-widest"
          >
            Investment Options
          </h4>
          <p class="text-sm md:text-lg font-serif text-gray-400">Get More</p>
        </a>

        <a
          href="#"
          class="w-full md:w-1/3 py-12 px-12 md:border-l-4 md:border-r-4 md:border-gray-700"
        >
          <h4
            class="mb-2 uppercase text-gray-100 text-lg font-bold tracking-widest"
          >
            Accomodation
          </h4>
          <p class="text-sm md:text-lg font-serif text-gray-400">
            Future Tenants
          </p>
        </a>

        <a href="#" class="w-full md:w-1/3 px-12">
          <nuxt-link to="/home"
            >home
            <h4
              class="mb-2 uppercase text-gray-100 text-lg font-bold tracking-widest"
            >
              Land Development
            </h4></nuxt-link
          >
          <p class="text-sm md:text-lg font-serif text-gray-400">The Homes</p>
        </a>
      </div>
    </div>
  </main>
</template>
<script>
export default {
  data() {
    return {
      intro: 'Apartêtre, un espace de détente et de relaxation',
      titreAccroche:
        'le titre de niveau H2 donc référencement et mot clé à inclure. ',
      accroche:
        'la partie accroche avec les mots clé pour institut de beauté sur Argeles sur mer.',
      soins: 'les soins',
      texteSoin:
        "le texte pour la partie soin, soin du corps, épilation et autre joyeuseté d'un institut de beauté",
      aqua: 'la partie sur le spa.',
      texteAqua:
        "la partie vers l'aque, espace de détente et de relaxation dans le sauna etc.",
    }
  },
}
</script>
