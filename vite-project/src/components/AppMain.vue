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
        <AppMainMenu></AppMainMenu>
          <!-- info -->
        <div class="info-container">
            <ul>
                <li class="list-info under-li">
                    <li class="list-info">3</li>
                    2
                </li>
                <li class="list-info">1</li>
                <li class="list-info">1</li>
                <li class="list-info">1</li>
            </ul>
        </div>
         <!-- info -->
    </main>
</template>

<style scoped lang="scss">
@use '../style/partials/variables.scss' as *;

.info-container{
    background-color: rgb(93, 93, 93);

        ul{
            display: $d-flex;
            list-style: none;
            margin-left: 5.5rem;

                .under-li{
                    display: $d-flex;
                    flex-direction: column;
                }
        }
}
</style>
