<script>
    export default{
        name :'main', 
    }
</script>

<template>
    <main id="main">
        <!-- menu -->
        <div class="menu-container">
            menu
        </div>
         <!-- menu -->
          <!-- info -->
        <div class="info-container">
            info
        </div>
         <!-- info -->
    </main>
</template>

<style scoped lang="scss">
@use '../style/partials/variables.scss' as *;

main{
    height: 300px;
}
.menu-container{
    background-color: $bg-blue;
    height: 100px;
}
.info-container{
    background-color: rgb(93, 93, 93);
    height: 200px;
}
</style>
