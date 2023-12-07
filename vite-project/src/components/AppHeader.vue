<script>
     export default{
        name :'header', 
    }
</script>

<template>
     <header id="header">
        <div class="nav-container">div1</div>
        <div class="content-container">div2</div>
     </header>
</template>

<style scoped lang="scss">
@use '../style/partials/variables.scss' as*;

.content-container{
    background-color: $bg-black;
}

</style>
