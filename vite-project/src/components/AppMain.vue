<script>
    import AppMainMenu from './AppMainMenu.vue';
    import AppInfoMain from './AppInfoMain.vue';
    export default{
        name :'main', 
        components:{
            AppMainMenu,
            AppInfoMain,
        }
    }
</script>

<template>
    <main id="main">
        <AppMainMenu></AppMainMenu>
        <AppInfoMain></AppInfoMain>
    </main>
</template>

<style scoped lang="scss">
@use '../style/partials/variables.scss' as *;
</style>
