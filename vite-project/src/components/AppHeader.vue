<script>
    import AppDcLogo from './AppDcLogo.vue';
     export default{
        name :'header', 
        components:{
            AppDcLogo,
        }
    }
</script>

<template>

     <header id="header">
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
        <div class="content-container">
            <span>
                <a href="#">Content goes here</a>
            </span>
        </div>
     </header>
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
            list-style: none;
        }
            // li
            .list{
                text-transform: uppercase;
                padding: .8125rem;
            }
}
// navbar container
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
