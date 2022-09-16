<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>

  </header>
  <div class="flex">
    <div class="flex flex-col items-center justify-center bg-[#181818] w-full">
      <img src="./assets/images/Pig.png" alt="pig" class="w-96">
      <HelloWorld msg="Roosa Possa"/>
    </div>
    <main>
      <TheWelcome />
    </main>
  </div>

</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }
}
</style>
