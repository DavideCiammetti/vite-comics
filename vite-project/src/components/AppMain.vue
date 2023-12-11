<script>
    import AppMainMenu from './AppMainMenu.vue';
    import CardsData from './cardsData.vue';
    export default{
        name :'main', 
        components:{
            AppMainMenu,
            CardsData,
        }
    }
</script>

<template>
    <main id="main">
         <!--cards informative -->
        <CardsData/>  
        <AppMainMenu/>
    </main>
</template>

<style lang="scss">
@use '../style/partials/variables.scss' as *;

    main{
        background-color: $bg-black;
    }
</style>
