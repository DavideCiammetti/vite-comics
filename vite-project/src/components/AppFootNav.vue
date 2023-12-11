<script>
     export default{
        name :'footer-navbar',
    }
</script>

<template>
    <div class="foot-container">
        <div class="button-container">
            <button>SIGN-UP NOW!</button>
        </div>
        <div class="social-container">
            <p class="follow"><strong>FOLLOW US</strong></p>
            <ul>
                <li class="social-ico">
                    <img src="../../public/img/footer-facebook.png" alt="facebook.img">
                </li>
                <li class="social-ico">
                    <img src="../../public/img/footer-twitter.png" alt="twitter.im">
                </li>
                <li class="social-ico">
                    <img src="../../public/img/footer-youtube.png" alt="youtube.img">
                </li>
                <li class="social-ico">
                    <img src="../../public/img/footer-pinterest.png" alt="pinterest.img">
                </li>
                <li class="social-ico">
                    <img src="../../public/img/footer-periscope.png" alt="periscope.img">
                </li>
            </ul>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables.scss' as *;

    .foot-container{
        display: $d-flex;
        justify-content: space-around;
        background-color: $foot-bg;
        height: 130px;
        align-items: center;
        position: relative;
        z-index: 22222;
            .social-container{
                display: $d-flex;
                align-items: center;
                    .follow{
                        margin-right: 7px;
                        color: $bg-blue;
                    }

                    ul{
                    display: $d-flex;
                    list-style: none;
                        .social-ico{
                            color: white;
                            padding: 10px;
                        }
            }
            }

            button{
                color: white;
                background-color: $foot-bg;
                padding: 17px;
                border: 2px solid $bg-blue;
            }
    }
</style>
