<template>
        <!-- esempio di card da stampare -->
        <div class="single-card">
            <!-- l'immagine sarà composta da le caratteristiche dell'oggetto. thumb -->
            <img :src="featuresCard.thumb" :alt="featuresCard.series">
            <!-- il titolo fa sempreparte delle caratteristiche dell'oggetto. series -->
            <h3>{{featuresCard.series}}</h3>
        </div>
</template>

<script>
export default {
    // creo un nuovo component
    name:'ProductCard',
    // creo un props per trasferire le caratteristiche della card come oggetto
    props: {
        featuresCard: Object
    }
}
</script>

<style lang="scss" scoped>
@import '../style/common';
.single-card{
    margin: 2px;
    margin: 0 auto;
    width: calc((100% / 6) - 4px);
    img{
        max-width: 170px;
        max-height: 170px;
        overflow: hidden;
    }
    img:hover{
        transform: scale(1.2);
    }
    h3{
        font-size: 12px;
        margin: 5px 0;
    }
}
</style>