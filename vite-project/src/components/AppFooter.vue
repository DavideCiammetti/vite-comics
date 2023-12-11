<script>
import AppInfoMain from './AppInfoMain.vue';
import AppFootNav from './AppFootNav.vue';
     export default{
        name :'footer', 
        components:{
            AppInfoMain,
            AppFootNav,
        }
    }
</script>

<template>
   <footer>
        <AppInfoMain></AppInfoMain>
        <AppFootNav></AppFootNav>
   </footer>
</template>

<style scoped lang="scss">
</style>
