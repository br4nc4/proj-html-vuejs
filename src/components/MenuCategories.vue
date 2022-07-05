<template>
    <div>
        <div class="container">
            <!-- TITOLO E BOTTONE MENU CATEGORIES -->
            <div class="d-flex justify-content-between pdMenu">
                <span class="fs-1 fw-bold">Menu Categories</span>
                <div>
                    <button type="button" class="btn btn-danger myButton rounded-pill">
                        VIEW THE FULL MENU
                        <span class="ps-2 mySpan">
                            <i class="fa-solid fa-circle-arrow-right"></i>
                        </span>
                    </button>
                </div>
            </div>

            <!-- IMMAGINI MENU CATEGORIES 4 COLONNE -->
            <div class="row row-cols-4 pdGrid">
                    <div class="col px-0 d-flex justify-content-center align-items-center position-relative">
                        <img class="myImg" src="/img/appetizers-menu-background.jpg" alt="">
                        <div class="overlay text-white fw-bold">APPETIZERS</div>
                    </div>
                    <div class="col px-0 d-flex justify-content-center align-items-center position-relative">
                        <img class="myImg" src="/img/burgers-menu-background.jpg" alt="">
                        <div class="overlay text-white fw-bold">BURGERS</div>
                    </div>
                    <div class="col px-0 d-flex justify-content-center align-items-center position-relative">
                        <img class="myImg" src="/img/pizza-menu-background.jpg" alt="">
                        <div class="overlay text-white fw-bold">PIZZAS</div>
                    </div>
                    <div class="col px-0 d-flex justify-content-center align-items-center position-relative">
                        <img class="myImg" src="/img/fries-menu-background.jpg" alt="">
                        <div class="overlay text-white fw-bold">FRIES</div>
                    </div>
                    <div class="col px-0 d-flex justify-content-center align-items-center position-relative">
                        <img class="myImg" src="/img/sides-menu-background.jpg" alt="">
                        <div class="overlay text-white fw-bold">SIDES</div>
                    </div>
                    <div class="col px-0 d-flex justify-content-center align-items-center position-relative">
                        <img class="myImg" src="/img/desserts-menu-background.jpg" alt="">
                        <div class="overlay text-white fw-bold">DESSERTS</div>
                    </div>
                    <div class="col px-0 d-flex justify-content-center align-items-center position-relative">
                        <img class="myImg" src="/img/beverages-menu-background.jpg" alt="">
                        <div class="overlay text-white fw-bold">BEVERAGES</div>
                    </div>
                    <div class="col-3 px-0 d-flex justify-content-center align-items-center position-relative">
                        <img class="myImg" src="/img/specials-menu-background.jpg" alt="">
                        <div class="overlay text-white fw-bold">SPECIALS</div>
                    </div>
            </div>

            <!-- 4 ICONE LEAF CORN MILK MEAT -->
            <div class="d-flex align-items-center justify-content-around">
                <div class="icons">
                    <img src="/img/leaf.png" alt="">
                    <p>Vegetarian</p>
                </div>
                <div class="icons">
                    <img src="/img/corn.png" alt="">
                    <p>Gluten Free</p>
                </div>
                <div class="icons">
                    <img src="/img/milk.png" alt="">
                    <p>Dairy Free</p>
                </div>
                <div class="icons">
                    <img src="/img/meat.png" alt="">
                    <p>Keto Friendly</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>
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
    padding: 0.4rem 1.3rem;
    }
    .mySpan i{
        transform: scale(0.9);
    }
    .myImg{
        width: 100%;
        height: 180px;
        object-fit: cover;
        object-position: top center;
        padding: 0.5rem;
    }
    .container{
        max-width: 1050px;
    }
    .icons img{
        transform: scale(0.8)
    }
    .icons{
        text-align: center;
        font-weight: 700;
    }
    .pdMenu{
        padding-top: 110px;
        padding-bottom: 50px;
    }
    .pdGrid{
        margin-bottom: 40px;
    }
    .overlay{
        position: absolute;
        top: 8px;
        left: 8px;
        bottom: 0;
        right: 0;
        width: 246.5px;
        height: 164px;
        background-color: rgba(0, 0, 0, 0.4);
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>