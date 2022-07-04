<template>
    <div>
        <PopularDishes></PopularDishes>
        <MegaTwentyPercentBg></MegaTwentyPercentBg>
        <MenuCategories></MenuCategories>
        <OrderingApp></OrderingApp>
    </div>
</template>

<script>
import PopularDishes from './PopularDishes.vue';
import MegaTwentyPercentBg from './MegaTwentyPercentBg.vue';
import MenuCategories from './MenuCategories.vue';
import OrderingApp from './OrderingApp.vue';


export default {
    components: {
    PopularDishes,
    MegaTwentyPercentBg,
    MenuCategories,
    OrderingApp
}
}
</script>

<style lang="scss">

</style>