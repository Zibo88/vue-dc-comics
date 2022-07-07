<template>
        <div class="single-card">
            <img :src="featuresCard.thumb" :alt="featuresCard.series">
            <h3>{{featuresCard.series}}</h3>
        </div>
</template>

<script>
export default {
    name:'ProductCard',
    props: {
        featuresCard: Object
    }
}
</script>

<style lang="scss" scoped>
@import '../style/common';
.single-card{
    margin: 2px;
    width: calc((100% / 6) - 4px);
    img{
        max-width: 180px;
        max-height: 180px;
        margin: 0 auto;
        overflow: hidden;
    }
    h3{
        font-size: 12px;
        margin: 5px 0;
    }
}
</style>