<template>
    <div>
        <img class="banner" src="../assets/img/jumbotron.jpg" alt="jumbotron img">
    </div>
</template>

<script>
export default {
    name:'MyBanner'
}
</script>

<style lang="scss" scoped>
@import '../style/variables';
@import '../style/common';

.banner{
    height: 500px;
    object-fit: cover;
    object-position: top;
}
</style>