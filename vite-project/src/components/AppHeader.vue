<script>
 import AppDcLogo from './AppDcLogo.vue';
    import AppNavHead from './AppNavHead.vue';
     export default{
        name :'header', 
        components:{
            AppDcLogo,
            AppNavHead,
        }
    }
</script>

<template>
     <header id="header">
        <AppNavHead></AppNavHead>
     </header>
</template>

<style scoped>
</style>
