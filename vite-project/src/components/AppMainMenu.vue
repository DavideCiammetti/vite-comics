<script>
    export default{
        name :'main-menu', 
    }
</script>

<template>
     <!-- menu -->
     <div class="menu-container">
            <ul>
                <li class="list-menu">
                    <div class="img-container padd-img">
                        <img src="../../public/img/buy-comics-digital-comics.png" alt="dc.img" >
                    </div>
                   <p> digital comics</p>
                </li>
                <li class="list-menu">
                    <div class="img-container"> 
                        <img src="../../public/img/buy-comics-merchandise.png" alt="merchandise.img">
                    </div>
                   <p> dc merchandise</p>
                </li>
                <li class="list-menu">
                    <div class="img-container">   
                        <img src="../../public/img/buy-comics-subscriptions.png" alt="subscription.img">
                    </div>
                 <p> subscription</p>
                </li>
                <li class="list-menu">
                   <div class="img-container padd-img"> 
                        <img src="../../public/img/buy-comics-shop-locator.png" alt="comic.img" >
                    </div>
                    <p>comic shop locator</p>
                </li>
                <li class="list-menu">
                  <div class="img-container">  
                    <img src="../../public/img/buy-dc-power-visa.svg" alt="power.img">
                </div>
                   <p> dc power visa</p>
                </li>
            </ul>
        </div>
         <!-- menu -->
</template>

<style scope lang="scss">
@use '../style/partials/variables.scss' as *;
.menu-container{
    background-color: $bg-blue;
    display: $d-flex;
    justify-content: center;
    padding: 1.3125rem;
    position: relative;
    z-index: 22222;

        ul{
            display: $d-flex;
            list-style: none;
                .list-menu{
                    text-transform: uppercase;
                    padding: .9375rem;
                    display: flex;
                    align-items: center;

                        .padd-img img{
                            padding: .4375rem;
                        }
                        .img-container{
                            padding: .4375rem;
                            img{
                                width: 3.4375rem;
                            }
                        }
                        p{
                            color: $col-white;
                        }
                }
        }
}
</style>