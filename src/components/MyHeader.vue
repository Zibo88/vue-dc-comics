<template>
   <header class="container flex">
       <div class="logo">
           <img src="../assets/img/dc-logo.png" alt="DC logo">
       </div>
        <!-- nav -->
           <nav>
               <ul class="header-menu"> 
                   <li v-for="link, index in menuLinks" :key="index" :class="{'current' : link.currentElement == true}">
                       <a :href="link.url" :class="{'current' : link.currentElement == true}">{{link.name}} </a>
                   </li>
               </ul>
           </nav>
   </header>
</template>

<script>
export default {
    name: 'MyHeader',
    data(){
       return {
           menuLinks: [
               {
                name: 'CHARACTERS',
                url: '#',
                currentElement: false,
               },
               {
                name: 'COMICS',
                url: '#',
                currentElement: true,
               },
               {
                name: 'MOVIES',
                url: '#',
                currentElement: false,
               },
               {
                name: 'TV',
                url: '#',
                currentElement: false,
               },
               {
                name: 'GAMES',
                url: '#',
                currentElement: false,
               },
               {
                name: 'COLLECTIBLES',
                url: '#',
                currentElement: false,
               },
               {
                name: 'VIDEOS',
                url: '#',
                currentElement: false,
               },
               {
                name: 'FANS',
                url: '#',
                currentElement: false,
               },
               {
                name: 'NEWS',
                href: '#',
                currentElement: false,
               },
               {
                name: 'SHOP',
                url: '#',
                currentElement: false,
               },

           ]
           

        }
    }
    
}
</script>

<style lang="scss" scoped>
@import '../style/variables';
@import '../style/common';
header {
    height: 80px;
    padding: 20px 0;
    align-items: center;
    justify-content: space-between;
    .logo{
        img{
            width: 50px;
            display: inline;
            margin-left: 10px;
        }
    }

    .header-menu{
        display: flex;
        color: $main_color;
        
        li{
            padding: 0 10px;
            font-size: 10px;
            a{
                color: black;
                font-weight: 700;
                line-height: 80px;
            }
            a.current{
                color: $main_color;
            }
        }
    }

}
</style>