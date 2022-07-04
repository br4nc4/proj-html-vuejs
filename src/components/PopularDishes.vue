<template class="position-relative">
    <div class="myPosition container">
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
            <div class="d-flex justify-content-center gap-4 pb-4">
                <div v-for="(card, i) in menuFood" :key="i">
                    <FoodCard
                    :image="card.imgSrc"
                    :title="card.foodName"
                    :price="card.price">
                    </FoodCard>
                </div>
            </div>

            <!-- BUTTON -->
            <div class="text-center">
                <button type="button" class="btn btn-danger myButton rounded-pill">
                    START YOUR ORDER
                    <span class="ps-2 mySpan">
                        <i class="fa-solid fa-circle-arrow-right"></i>
                    </span>
                </button>
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
        padding-top: 40px;
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
    .myButton{
    --bs-btn-color: #fff;
    --bs-btn-bg: #ce1a26;
    --bs-btn-border-color: #dc3545;
    --bs-btn-hover-color: #fff;
    --bs-btn-hover-bg: #bb2d3b;
    --bs-btn-hover-border-color: #b02a37;
    --bs-btn-focus-shadow-rgb: 225,83,97;
    --bs-btn-active-color: #fff;
    --bs-btn-active-bg: #b02a37;
    --bs-btn-active-border-color: #a52834;
    --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
    --bs-btn-disabled-color: #fff;
    --bs-btn-disabled-bg: #dc3545;
    --bs-btn-disabled-border-color: #dc3545;
    font-size: 12px;
    font-weight: 700;
    padding: 0.4rem 1.5rem;
    }
    .mySpan i{
        transform: scale(0.9);
    }
    .myPosition{
        padding-bottom: 70px;
        position: absolute;
        top: 67.5%;
        left: 50%;
        transform: translate(-50%);
        background-color: white;
        z-index: 3;
    }
    .container{
        max-width: 1050px;
    }
</style>