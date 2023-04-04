<script setup>
import { RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue';
import Sidebar from './components/Sidebar.vue';
import KolpolokFooter from './components/KolpolokFooter.vue'
</script>

<template>
      <div>
        <Navbar/>
      </div>
      <div class="d-sm-flex">
        <div>
          <Sidebar/>
        </div>
      <div class="p-2 flex-grow-1">
      <RouterView />
      </div>
      </div>
      <div>
        <KolpolokFooter/>
      </div>
</template>

<style scoped>
/*
header {
  line-height: 1.5;
  max-height: 100vh;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}*/

</style>
