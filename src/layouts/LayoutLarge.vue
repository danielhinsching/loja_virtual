<script setup>
import LargeAside from '../components/templates/large/LargeAside.vue';
import LargeHeader from '../components/templates/large/LargeHeader.vue';
import LargeFooter  from '../components/templates/large/LargeFooter.vue';
</script>
<template>
    <header>
        <LargeHeader/>        
    </header>
    <aside>
        <LargeAside/>
    </aside>
    <main>
        <RouterView/>
    </main>
    <footer>
        <LargeFooter/>
    </footer>
</template>