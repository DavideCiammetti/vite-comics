<script>
    export default{
        name :'main', 
    }
</script>

<template>
    <main id="main">
        <!-- menu -->
        <div class="menu-container">
            <ul>
                <li class="list-menu">
                    <div class="img-container padd-img">
                        <img src="../../public/img/buy-comics-digital-comics.png" alt="buy.img" >
                    </div>
                   <p> digital comics</p>
                </li>
                <li class="list-menu">
                    <div class="img-container"> 
                        <img src="../../public/img/buy-comics-merchandise.png" alt="buy.img">
                    </div>
                   <p> dc merchandise</p>
                </li>
                <li class="list-menu">
                    <div class="img-container">   
                        <img src="../../public/img/buy-comics-subscriptions.png" alt="buy.img">
                    </div>
                 <p> subscription</p>
                </li>
                <li class="list-menu">
                   <div class="img-container padd-img"> 
                        <img src="../../public/img/buy-comics-shop-locator.png" alt="buy.img" >
                    </div>
                    <p>comic shop locator</p>
                </li>
                <li class="list-menu">
                  <div class="img-container">  
                    <img src="../../public/img/buy-dc-power-visa.svg" alt="buy.img">
                </div>
                   <p> dc power visa</p>
                </li>
            </ul>
        </div>
         <!-- menu -->
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
.menu-container{
    background-color: $bg-blue;
    display: $d-flex;
    justify-content: center;
    padding: 1.3125rem;

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
.info-container{
    background-color: rgb(93, 93, 93);

        ul{
            display: $d-flex;
            list-style: none;
            margin-left: 6.25rem;

                .under-li{
                    display: $d-flex;
                    flex-direction: column;
                }
        }
}
</style>
