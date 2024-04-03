<script setup>
import MediumAside from '../components/templates/medium/MediumAside.vue'
import MediumHeader from '../components/templates/medium/MediumHeader.vue'
import MediumFooter from '../components/templates/medium/MediumFooter.vue'
</script>
<template>
  <header>
    <MediumHeader />
  </header>
  <aside>
    <MediumAside />
  </aside>
  <main>
    <RouterView />
  </main>
  <footer>
    <MediumFooter />
  </footer>
</template>
