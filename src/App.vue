<script setup>
// import HelloWorld from './components/HelloWorld.vue'
import info from './components/Info.vue'
import about from './components/About.vue'
import experience from './components/Experience.vue'
import expertise from './components/Expertise.vue'
import contact from './components/Contact.vue'


function scroll() {
  const p2 = document.querySelector(".about")
  p2.scrollIntoView({ behavior: "smooth" })
}
function scrollexp() {
  const p2 = document.querySelector(".exp")
  p2.scrollIntoView({ behavior: "smooth" })
}
function scrollexpr() {
  const p2 = document.querySelector(".expr")
  p2.scrollIntoView({ behavior: "smooth" })
}
function scrollcon() {
  const p2 = document.querySelector(".contact")
  p2.scrollIntoView({ behavior: "smooth" })
}
</script>

<template>
  <header class="flex justify-around space-x-28">
    <div class="logo p-5 flex"><a href="#"><img class="" width="150" src="/Mohamed.svg"></a></div>
    <div class="nav p-5 space-x-10">
      <button @click="scroll" class="text-xl">About Me</button>
      <button @click="scrollexp" class="text-xl">Experience</button>
      <button @click="scrollexpr" class="text-xl">Expertise</button>
      <button @click="scrollcon" class="text-xl">Contact</button>
    </div>
  </header>
  <div class="line w-11/12 h-0.5 bg-gray-800 rounded-full mx-auto mt-2"></div>
  <main>
    <info />
    <about />
    <experience />
    <expertise />
    <contact />
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
