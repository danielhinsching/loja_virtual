<script setup>
import MediumAside from '../components/templates/Medium/MediumAside.vue';
import MediumHeader from '../components/templates/Medium/MediumHeader.vue';
import MediumFooter  from '../components/templates/Medium/MediumFooter.vue';
</script>
<template>
    <header>
        <MediumHeader/>        
    </header>
    <aside>
        <MediumAside/>
    </aside>
    <main>
        <RouterView/>
    </main>
    <footer>
        <MediumFooter/>
    </footer>
</template>