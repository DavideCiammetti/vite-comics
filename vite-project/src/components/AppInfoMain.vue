<script>
    export default{
        name :'main-info', 
    }
</script>

<template>
     <!-- info -->
    <div class="info-container">
        <!-- lista 1 -->
        <div class="list-container">
            <!-- list elements -->
            <div class="content-list">
                <ul>
                    <li class="info-list">
                        <h3>
                            <strong>DC COMICS</strong>
                        </h3>
                    </li>
                    <li class="info-list">
                        <a href="#">Charter</a>
                    </li>
                    <li class="info-list">
                        <a href="#">Comics</a>
                    </li>
                    <li class="info-list">
                        <a href="#">Movie</a>
                    </li>
                    <li class="info-list">
                        <a href="#">Tv</a>
                    </li>
                    <li class="info-list">
                        <a href="#">Games</a>
                    </li>
                    <li class="info-list">
                        <a href="#">Videos</a>
                    </li>
                    <li class="info-list">
                        <a href="#">News</a>
                    </li>
                </ul>
            </div>
              <!-- list elements -->
                <!-- list shop -->
            <div class="content-list">
                <ul>
                    <li class="info-list">
                        <h3 class="shop-margin">
                            <strong>SHOP</strong>
                        </h3>
                    </li>
                    <li class="info-list">
                        <a href="#">Shop DC</a>
                    </li>
                    <li class="info-list">
                        <a href="#">Shop DC Collectibles</a>
                    </li>
                </ul>
            </div>
             <!-- list shop -->
        </div>
        <!-- lista 1 -->
        <!-- lista 2 -->
        <div class="list-container"> 
            <ul>
                <li class="info-list">
                    <h3>
                        <strong>DC</strong>
                    </h3>
                </li>
                <li class="info-list">
                    <a href="#">Terms of Use</a>
                </li>
                <li class="info-list">
                    <a href="#">Privacy Policy (New)</a>
                </li>
                <li class="info-list">
                    <a href="#">Ad Choices</a>
                </li>
                <li class="info-list">
                    <a href="#">Advertising</a>
                </li>
                <li class="info-list">
                    <a href="#">Jobs</a>
                </li>
                <li class="info-list">
                    <a href="#">Subscriptions</a>
                </li>
                <li class="info-list">
                    <a href="#">Talent Workshop</a>
                </li>
                <li class="info-list">
                    <a href="#">CPSC Certicates</a>
                </li>
                <li class="info-list">
                    <a href="#">Ratings</a>
                </li>
                <li class="info-list">
                    <a href="#">Shop Helps</a>
                </li>
                <li class="info-list">
                    <a href="#">Contact Us</a>
                </li>
            </ul>
        </div>
         <!-- lista 2 -->
          <!-- lista 3 -->
        <div class="list-container">
            <ul>
                <li class="info-list">
                    <h3>
                        <strong>SITES</strong>
                    </h3>
                </li>
                <li class="info-list">
                    <a href="#">DC</a>
                </li>
                <li class="info-list">
                    <a href="#">MAD Magazine</a>
                </li>
                <li class="info-list">
                    <a href="#">DC Kids</a>
                </li>
                <li class="info-list">
                    <a href="#">DC Universe</a>
                </li>
                <li class="info-list">
                    <a href="#">DC Power Vista</a>
                </li>
            </ul>
        </div>
        <!-- lista 3 -->
        <div class="dc-img-big">
            <img src="../../public/img/dc-logo-bg.png" alt="dc-big">
         </div>
    </div>
         <!-- info -->
</template>

<style scope lang="scss">
@use '../style/partials/variables.scss' as *;

.info-container{
    background: url('../../public/img/footer-bg.jpg');
    background-size: cover;
    padding: 35px 0;
    display: $d-flex;
    position: relative;

        ul{
            list-style: none;
            margin-left: 5.5rem;

                .under-li{
                    display: $d-flex;
                    flex-direction: column;
                }
                a{
                    text-decoration: none;
                    color: #959595;
                }
                h3{
                    color: white;
                    font-size: 21px;
                    margin-bottom: 15px;
                }
                .shop-margin{
                    margin-top: 10px;
                }
        }

        .dc-img-big{
            position: absolute;
            left: 55%;
            bottom: -34%;
        }
}

</style>