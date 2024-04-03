<script setup>
import SmallHeader from '../components/templates/Small/SmallHeader.vue';
import SmallFooter  from '../components/templates/Small/SmallFooter.vue';
</script>
<template>
    <header>
        <SmallHeader/>        
    </header>
    <main>
        <RouterView/>
    </main>
    <footer>
        <SmallFooter/>
    </footer>
</template>