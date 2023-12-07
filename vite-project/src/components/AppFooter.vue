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
   <AppInfoMain></AppInfoMain>
   <AppFootNav></AppFootNav>
</template>

<style scoped lang="scss">
@use '../style/partials/variables.scss' as *;
</style>
