<template>

<MainMenuHeader/>
<MainMenuHero/>
<MainMenuFooter id="bottom"/>

</template>

<script setup>
    import MainMenuHero from '../components/MainMenuHero.vue';
    import MainMenuHeader from '../components/MainMenuHeader.vue';  
    import MainMenuFooter from '../components/MainMenuFooter.vue';
</script>

<style scoped>

#bottom {
    position: absolute;
    bottom: 0%;
}

</style>

