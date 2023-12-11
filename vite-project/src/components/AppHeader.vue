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
        <div class="jumbo">

        </div>
     </header>
</template>

<style scoped>
    .jumbo{
        height: 400px;
        background: url("../../public/img/jumbotron.jpg");
        background-size: cover;
    }
</style>
