<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <div class="center flex-col justify-center h-full w-full">
      <img class="mx-auto px-10 m-5 my-auto" width="150" src="/circles.svg">
      <h1 class="text-center text-5xl font-semibold">In progress</h1>
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}


@media (min-width: 1024px) {
  header {
    color: var(--vt-c-text-dark-1);
    /* display: flex; */
    /* place-items: center; */
    /* padding-right: calc(var(--section-gap) / 2); */
  }



}

.center {
  margin: auto;
  width: 100%;
  /* border: 3px solid green; */
  padding: 20px;
}
</style>
