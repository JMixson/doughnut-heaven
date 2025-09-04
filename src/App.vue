<script setup lang="ts">
import Navbar from './components/Navbar.vue';
</script>

<template>
  <Navbar />

  <header class="grid cols-2">
    <div>
      <h1>Doughnut Heaven</h1>
      <p>
        Step into a delicious universe dedicated to the one and only doughnut!
        From the classic glaze to the most inventive creations, we're here to
        celebrate every fluffy, frosted, and filled variety. This is a place for
        doughnut dreamers, connoisseurs, and anyone who believes a doughnut can
        make any day better. Get ready to explore the sweet, sweet world of
        doughnuts!
      </p>
    </div>
    <div>
      <img
        src="./assets/img/assortment-of-doughnuts.png"
        alt="Assortment of doughnuts"
      />
    </div>
  </header>

  <main>
    <section id="love">
      <h2>Why We Love Doughnuts</h2>
      <p>
        What's not to love? Is it the pillowy softness of a perfectly risen
        yeast doughnut? The satisfying bite of a rich cake doughnut? Or perhaps
        the endless creativity in toppings, fillings, and glazes? For us, it’s
        all of that and more. Doughnuts are more than just a treat; they're a
        bite of happiness, a sprinkle of nostalgia, and a testament to the
        simple joys in life. Join us as we explore the history, the art, and the
        sheer delight that doughnuts bring to the world.
      </p>
    </section>
  </main>
</template>

<style scoped>
header {
  padding: 50px var(--padding-sides);
}
</style>
