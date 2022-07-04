<template>
    <div>
        <PopularDishes></PopularDishes>
        <MegaTwentyPercentBg></MegaTwentyPercentBg>
        <MenuCategories></MenuCategories>
        <OrderingApp></OrderingApp>
        <LatestNews></LatestNews>
    </div>
</template>

<script>
import PopularDishes from './PopularDishes.vue';
import MegaTwentyPercentBg from './MegaTwentyPercentBg.vue';
import MenuCategories from './MenuCategories.vue';
import OrderingApp from './OrderingApp.vue';
import LatestNews from './LatestNews.vue';


export default {
    components: {
    PopularDishes,
    MegaTwentyPercentBg,
    MenuCategories,
    OrderingApp,
    LatestNews
}
}
</script>

<style lang="scss">

</style>