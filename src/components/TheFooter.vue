<template>
    <div class="container">
        <div class="footer flex">
            <div class="col">
                <ul>
                    <h4>DC COMICS</h4>
                    <li>
                        <a href="">Characters</a>
                    </li>

                    <li>
                        <a href="">Comics</a>
                    </li>

                    <li>
                        <a href="">Movies</a>
                    </li>
                    <li>
                        <a href="">TV</a>
                    </li>
                    <li>
                        <a href="">Game</a>
                    </li>
                    <li>
                        <a href="">Videos</a>
                    </li>
                    <li>
                        <a href="">News</a>
                    </li>
                </ul>
                <!-- 1.2 lista -->
                <ul>
                    <h4>SHOP</h4>
                    <li>
                        <a href="">Shop DC</a>
                    </li>

                    <li>
                        <a href="">Shop DC Collectibles</a>
                    </li>
                </ul>
            </div>

            <!-- seconda colonna -->
            <div class="col">
                 <ul>
                    <h4>DC</h4>
                    <li>
                        <a href="">Term Of Use</a>
                    </li>

                    <li>
                        <a href="">Privacy Police (new)</a>
                    </li>

                    <li>
                        <a href="">Ad Choices</a>
                    </li>
                    <li>
                        <a href="">Ad Avertising</a>
                    </li>
                    <li>
                        <a href="">Subscriptions</a>
                    </li>
                    <li>
                        <a href="">Talent WorkShop</a>
                    </li>
                    <li>
                        <a href="">CPSC Certificates</a>
                    </li>
               
                    <li>
                        <a href="">Shop Help</a>
                    </li>

                    <li>
                        <a href="">Contact us</a>
                    </li>
                </ul>
            </div>

            <!-- terza colonna -->
            <div class="col">
                <ul>
                    <h4>SITES</h4>
                    <li>
                        <a href="">DC</a>
                    </li>

                    <li>
                        <a href="">MAD Megazine</a>
                    </li>

                    <li>
                        <a href="">DC Kids</a>
                    </li>
                    <li>
                        <a href="">DC Universe</a>
                    </li>
                    <li>
                        <a href="">DC Power Visa</a>
                    </li>
                </ul>
            </div>

            <!-- quarta colonna -->
             <div class="footer-img">
              <img src="../assets/img/dc-logo-bg.png" alt="logo dc">
            </div>
        </div>

        <div class="footer-bottom flex">
            <button >
                <a class="btn" href="#">SIGN UP NOW!</a>
                
                </button>

            <div class="footer-icon flex">
                <h3>FOLLOW US</h3>
                <ul class="flex">
                    <li>
                        <a href="#">
                             <img class="social" src="../assets/img/footer-facebook.png" alt="facebook logo">
                        </a>
                    </li>

                   <li>
                        <a href="#">
                             <img class="social" src="../assets/img/footer-periscope.png" alt="periscope logo">
                        </a>
                    </li>

                   <li>
                        <a href="#">
                             <img class="social" src="../assets/img/footer-pinterest.png" alt="pinterest logo">
                        </a>
                    </li>

                    <li>
                        <a href="#">
                             <img class="social" src="../assets/img/footer-twitter.png" alt="twitter logo">
                        </a>
                    </li>

                   <li>
                        <a href="#">
                             <img class="social" src="../assets/img/footer-youtube.png" alt="youtube logo">
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'TheFooter'
}
</script>

<style lang="scss" scoped>
@import '../style/common';
@import '../style/variables';
.container{
    background-image: url(../assets/img/footer-bg.jpg);
    .footer.flex{
        overflow: hidden;
    }
    .col{
        width: 10%;
    }
    .col h4{
        color: white;
        padding: 10px;
    }
    .col li{
        padding: 5px 10px;
    }
    .col li a{
        color: #62788a;
        font-size: 13px;
    }
    .footer-img{
        width: 32%;
        position: relative;
    }.footer-img img{
        position: absolute;
        top: -45px;
        right: -330px;
    }
    .footer-bottom.flex{
        height: 80px;
        background-color: #303030;
        justify-content: space-between;
        align-items: center;
        padding: 10px 20px;
    }.btn{
        color: white;
        border: 2px solid $main_color;
        padding: 10px;
        font-size: 30px;
        background-color:#303030;
        font-weight: 700;
        
    }
    .social{
        width: 45px;
        padding: 0 5px;
    }
    h3{
        color: $main_color;
        font-size: 30px;
    }

    
}
</style>