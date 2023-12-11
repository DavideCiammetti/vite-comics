<script>
    import AppDcLogo from './AppDcLogo.vue';
     export default{
        name :'nav', 
        components:{
            AppDcLogo,
        }
    }
</script>

<template>
    <div class="nav-container">
        <AppDcLogo></AppDcLogo>
        <nav class="navbar">
            <ul class="list-container">
                <li class="list">charters</li>
                <li class="list">comics</li>
                <li class="list">movies</li>
                <li class="list">tv</li>
                <li class="list">games</li>
                <li class="list">collectibles</li>
                <li class="list">videos</li>
                <li class="list">fans</li>
                <li class="list">news</li>
                <li class="list">shop</li>
            </ul>
        </nav>
    </div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables.scss' as*;
// navbar container
.nav-container{
    display: $d-flex;
    justify-content: space-around;
    // navbar
    .navbar{
        display: $d-flex;
        align-items: center;
    }
        // ul
        .list-container{
            display: $d-flex;
        }
            // li
            .list{
                text-transform: uppercase;
                padding: .8125rem;
            }
}
// navbar container

</style>
