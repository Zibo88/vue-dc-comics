<template>
   <section class="container">
       <div class="icon-section flex">
           <!-- prima icona -->
           <div class="icon flex">
               <img src="../assets/img/buy-comics-digital-comics.png" alt="comics digital logo">
               <span>DIGITAL COMICS</span>
           </div>

           <!-- seconda icona -->
            <div class="icon flex">
               <img src="../assets/img/buy-comics-merchandise.png" alt="comics digital logo">
               <span>DC MERCHANDISE</span>
           </div>

           <!-- terza icona -->
            <div class="icon flex">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="comics digital logo">
               <span>SUBSCRIPTION</span>
           </div>

           <!-- quarta icona -->
            <div class="icon flex">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="comics digital logo">
               <span>COMIC SHOP LOCATOR</span>
           </div>

           <!-- quinta icona -->
            <div class="icon flex">
               <img src="../assets/img/buy-dc-power-visa.svg" alt="comics digital logo">
               <span>DC POWER VISA</span>
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
    .icon{
        align-items: center;
        font-size: 13px;
        color: white;
    }
    img{
        width: 100px;
        padding: 20px;
    }
}
</style>