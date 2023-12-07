<script>
    import AppMainMenu from './AppMainMenu.vue';
    export default{
        name :'main', 
        components:{
            AppMainMenu,
        }
    }
</script>

<template>
    <main id="main">
        <div class="content-container">
            <span>
                <a href="#">Content goes here</a>
            </span>
        </div>
        <AppMainMenu></AppMainMenu>
    </main>
</template>

<style scoped lang="scss">
@use '../style/partials/variables.scss' as *;
// secondo container
.content-container{
    background-color: $bg-black;
    color: $col-white;
    padding: 56px 0 48px 0;
    
        span{
            margin-left: 5.5rem;
            a{
                text-decoration: none;
                color: $col-white;
                font-size: 25px;
            }
        }
}
// secondo container
</style>
