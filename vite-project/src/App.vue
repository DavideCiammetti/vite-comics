<script>
  import AppMain from './components/AppMain.vue';
  import AppHeader from './components/AppHeader.vue';
  import AppFooter from './components/AppFooter.vue';
  export default{
    name: 'FirstApp',
    components:{
      AppMain,
      AppHeader,
      AppFooter,
    }
  }
</script>

<template>
  <!-- header -->
  <AppHeader></AppHeader>
   <!-- header -->
   <!-- main -->
  <AppMain></AppMain>
  <!-- main -->
  <!-- footer -->
  <AppFooter></AppFooter>
  <!-- footer -->
</template>

<style scoped>
</style>
