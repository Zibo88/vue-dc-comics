<template>
   <section class="container">
       <!-- creo il templeate che voglio stmpare -->
           <ul class="icon-section flex">
               <!-- ciclo le li e ne stampo tante per ogni oggetto dell'array -->
               <li class="icon flex" v-for="link,index in listIcon" :key="index"> 
                   <!-- il templeate è composto da un'li con una img ed un testo -->
                   <!-- utilizzo il link dato dal v-for per ottenere ogni oggetto -->
                   <img :src="link.img" :alt="link.text">
                   {{link.text}} 
                </li>
           </ul> 
   </section>
</template>

<script>
export default {
    name: 'MyIcon',
    data(){
        return{
            listIcon: [
                {
                    img: require('../assets/img/buy-comics-digital-comics.png'),
                    text: 'DIGITAL COMICS'
                },
                {
                    img: require('../assets/img/buy-comics-merchandise.png'),
                    text: 'DC MERCHANDISE'
                },
                {
                    img: require('../assets/img/buy-comics-subscriptions.png'),
                    text: 'SUBSCRIPTIONS'
                },
                {
                    img: require('../assets/img/buy-comics-shop-locator.png'),
                    text: 'SHOP LOCATOR'
                },
                {
                    img: require('../assets/img/buy-dc-power-visa.svg'),
                    text: 'DC POWER VISA'
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../style/variables';
@import '../style/common';

.icon-section.flex{
    background-color: $main_color;
    padding: 0 20px;
    justify-content: space-between;
    align-items: center;
    .icon.flex{
        align-items: center;
        font-size: 13px;
        color: white;

       
    }
    .icon.flex:hover span{
        color: black;
        
    }
    img{
        width: 100px;
        padding: 20px;
        color: white;
    }
}
</style>