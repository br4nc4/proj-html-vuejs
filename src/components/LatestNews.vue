<template>
    <div>
        <div class="container">
            <div class="d-flex justify-content-between">
                <span class="fs-1 fw-bold">Latest News</span>
                <div>
                    <button type="button" class="btn btn-danger myButton rounded-pill">
                        READ MORE NEWS
                        <span class="ps-2 mySpan">
                            <i class="fa-solid fa-circle-arrow-right"></i>
                        </span>
                    </button>
                </div>
            </div>
            <div class="d-flex myDflex">
                <div class="">
                    <img class="myImg" src="/img/pancake-burger-600x450.jpg" alt="">
                </div>

                <div class="">
                    <img class="myImg" src="/img/new-milkshake-menu-600x450.jpg" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

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
    padding: 0.4rem 1.2rem;
    }
    .mySpan i{
        transform: scale(0.9);
    }
    .container{
        max-width: 1050px;
    }
    .myImg{
        width: 490px;
    }
    .myDflex{
        gap: 45px;
    }
</style>

