<script setup>
import SearchBar from './components/SearchBar.vue'
</script>
<template>
  <header></header>
  <main>
    <a href="https://github.com/0x10-z/free-exercise-db-es" target="_blank" class="github"
      ><img
        decoding="async"
        loading="lazy"
        width="149"
        height="149"
        src="https://github.blog/wp-content/uploads/2008/12/forkme_right_red_aa0000.png?resize=149%2C149"
        class="attachment-full size-full github"
        alt="Fork me on GitHub"
        data-recalc-dims="1"
    /></a>
    <section>
      <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16 lg:px-12">
        <h1
          class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white"
        >
          Conjunto de ejercicios
        </h1>
        <p
          class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 xl:px-48 dark:text-gray-400"
        >
          Esta es una interfaz para un conjunto de datos abiertos de dominio público de más de 800
          ejercicios y fotos, consulta el
          <a href="https://www.github.com/yuhonas/free-exercise-db/" class="underline"
            >repositorio</a
          >
          para más detalles, incluyendo cómo obtener los datos del backend, disfruta 💪
        </p>

        <div
          class="flex flex-col mb-8 lg:mb-16 space-y-4 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4"
        >
          <div>
            <SearchBar />
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<style scoped>
a.github {
  position: absolute;
  top: 0px;
  right: 0px;
}
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

header {
  line-height: 1.5;
}
</style>
