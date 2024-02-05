<script setup>
// import HelloWorld from './components/HelloWorld.vue'
import info from './components/Info.vue'
</script>

<template>
  <header class="flex justify-around space-x-28">
    <div class="logo p-5 flex"><a href="#"><img class="" width="150" src="/Mohamed.svg"></a></div>
    <div class="nav p-5 space-x-10">
      <button class="text-xl">About Me</button>
      <button class="text-xl">Experience</button>
      <button class="text-xl">Education</button>
      <button class="text-xl">Contact</button>
    </div>
  </header>
  <div class="line w-11/12 h-0.5 bg-gray-800 rounded-full mx-auto mt-2"></div>
  <main>
    <info />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}


@media (min-width: 1024px) {
  header {
    color: var(--vt-c-text-dark-2);
    /* display: flex; */
    /* place-items: center; */
    /* padding-right: calc(var(--section-gap) / 2); */
  }
}
</style>
