<script setup lang="ts">
//import Home from './components/Home.vue'
//import TheWelcome from './components/TheWelcome.vue'
import {ref} from 'vue'

const count = ref(0)
</script>

<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <Home msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main> -->
  <div id="app">
    <button @click="count++">
    Count is: {{count}}
    </button>
  </div>
  <div>
    text
  </div>
</template>

<style >

#app {
  color: white;
}

body {
  background-color:black;
}
/*header {
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

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}*/
</style>
