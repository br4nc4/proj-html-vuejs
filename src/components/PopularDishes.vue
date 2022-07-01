<template>
    <div>
        <div class="container">
            <!-- TOP LINKS POPULAR DISHES -->
            <div class="d-flex justify-content-around topMenu">
                <div>
                    <i class="fa-regular fa-clock"></i>
                    <span class="ps-3">24/7 DELIVERY</span>
                </div>
                <div>
                    <i class="fa-solid fa-burger"></i>
                    <span class="ps-3">OVER 100 DISCHES</span>
                </div>
                <div>
                    <i class="fa-solid fa-mobile-screen-button"></i>
                    <span class="ps-3">IN APP ORDERING</span>
                </div>
                <div>
                    <i class="fa-solid fa-car"></i>
                    <span class="ps-3">FAST DELIVERY</span>
                </div>
            </div>
            <!-- TITOLO SEZIONE POPULAR DISHES -->
            <div class="text-center pdTit">
                <span class="fs-1 fw-bold">Our Most Popular Dishes</span>
            </div>

            <!-- SEZIONE DELLE FOOD CARD -->
            <div class="d-flex justify-content-center gap-4">
                <div v-for="(card, i) in menuFood" :key="i">
                    <FoodCard
                    :image="card.imgSrc"
                    :title="card.foodName"
                    :price="card.price">
                    </FoodCard>
                </div>
            </div>

            <!-- BUTTON -->
            
        </div>
    </div>
</template>

<script>
import FoodCard from './FoodCard.vue'


export default {
    components: {
    FoodCard
},
    data() {
        return {
            menuFood: [
                {
                    imgSrc: "/img/skin-on-fries-400x571.jpg",
                    foodName: "Skin On Fries",
                    price: "$3.00-$6.00",
                },
                {
                    imgSrc: "/img/choco-cookie-frappe-400x571.jpg",
                    foodName: "Choco Cookie Frappe",
                    price: "$4.99",
                },
                {
                    imgSrc: "/img/donut-burger-400x571.jpg",
                    foodName: "The Donut Burger",
                    price: "$6.99",
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
    .topMenu{
        color: #4b515c;
        padding-bottom: 90px;
    }
    .topMenu span{
        font-size: 14px;
        font-weight: 700;
    }
    .topMenu i{
        transform: scale(0.8);
    }
    .pdTit{
        padding-bottom: 60px;
    }
</style>