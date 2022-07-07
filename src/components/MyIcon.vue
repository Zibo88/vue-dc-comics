<template>
   <section class="container">
       <div class="icon-section flex">
           
           <!-- prima icona -->
           <div>
               <a class="icon flex" href="#">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="comics digital logo">
                    <span>DIGITAL COMICS</span>
               </a>
              
           </div>

           <!-- seconda icona -->
            <div>
                <a class="icon flex" href="#">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="comics digital logo">
                    <span>DC MERCHANDISE</span>
                </a>
           </div>

           <!-- terza icona -->
            <div>
               <a class="icon flex" href="#">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="comics digital logo">
                    <span>SUBSCRIPTION</span>
               </a>
           </div>

           <!-- quarta icona -->
            <div>
                <a class="icon flex" href="#">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="comics digital logo">
                    <span>COMIC SHOP LOCATOR</span>
                </a>
           </div>

           <!-- quinta icona -->
            <div>
               <a class="icon flex" href="#">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="comics digital logo">
                    <span>DC POWER VISA</span>
               </a>
           </div>
       </div>
   </section>
</template>

<script>
export default {
    name: 'MyIcon'
}
</script>

<style lang="scss" scoped>
@import '../style/variables';
@import '../style/common';

.icon-section{
    background-color: $main_color;
    padding: 0 20px;
    justify-content: space-between;
    align-items: center;
    .icon.flex{
        align-items: center;
        font-size: 13px;
        color: white;

       
    }
    .icon.flex:hover{
        color: black;
        
    }
    img{
        width: 100px;
        padding: 20px;
    }
}
</style>