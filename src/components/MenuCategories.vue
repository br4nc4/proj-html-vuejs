<template>
    <div>
        <div class="container">
            <!-- TITOLO E BOTTONE MENU CATEGORIES -->
            <div class="d-flex justify-content-between">
                <span class="fs-1 fw-bold">Menu Categories</span>
                <div>
                    <button type="button" class="btn btn-danger myButton rounded-pill">
                        START YOUR ORDER
                        <span class="ps-2 mySpan">
                            <i class="fa-solid fa-circle-arrow-right"></i>
                        </span>
                    </button>
                </div>
            </div>

            <!-- IMMAGINI MENU CATEGORIES 4 COLONNE -->
            <div class="row row-cols-4">
                    <div class="col px-0 d-flex justify-content-center align-items-center">
                        <img class="myImg" src="/img/appetizers-menu-background.jpg" alt="">
                    </div>
                    <div class="col px-0 d-flex justify-content-center align-items-center">
                        <img class="myImg" src="/img/burgers-menu-background.jpg" alt="">
                    </div>
                    <div class="col px-0 d-flex justify-content-center align-items-center">
                        <img class="myImg" src="/img/pizza-menu-background.jpg" alt="">
                    </div>
                    <div class="col px-0 d-flex justify-content-center align-items-center">
                        <img class="myImg" src="/img/fries-menu-background.jpg" alt="">
                    </div>
                    <div class="col px-0 d-flex justify-content-center align-items-center">
                        <img class="myImg" src="/img/sides-menu-background.jpg" alt="">
                    </div>
                    <div class="col px-0 d-flex justify-content-center align-items-center">
                        <img class="myImg" src="/img/desserts-menu-background.jpg" alt="">
                    </div>
                    <div class="col px-0 d-flex justify-content-center align-items-center">
                        <img class="myImg" src="/img/beverages-menu-background.jpg" alt="">
                    </div>
                    <div class="col-3 px-0 d-flex justify-content-center align-items-center">
                        <img class="myImg" src="/img/specials-menu-background.jpg" alt="">
                    </div>
            </div>

            <!-- 4 ICONE -->
            <div class="d-flex align-items-center">
                <div class="icons">
                    <img src="/img/leaf.png" alt="">
                    <p>Vegetarian</p>
                </div>
                <div class="icons">
                    <img class="pb-1" src="/img/corn.png" alt="">
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
    padding: 0.5rem 1.8rem;
    }
    .mySpan i{
        transform: scale(0.9);
    }
    .myImg{
        width: 100%;
        height: 175px;
        object-fit: cover;
        object-position: top center;
        padding: 0 1rem 1rem 0;
    }
    .container{
        max-width: 1032px;
    }
    .icons img{
        transform: scale(0.8)
    }
    .icons{
        text-align: center;
    }
</style>