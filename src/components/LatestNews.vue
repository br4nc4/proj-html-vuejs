<template>
    <div class="myPadding">
        <div class="container">
            <div class="d-flex justify-content-between pdTitle">
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
                    <img class="myImg first" src="/img/pancake-burger-600x450.jpg" alt="">
                    <div class="text-center">
                        <p class="myTitle fw-bold mb-0">NEW: The Pancake Burger</p>
                    </div>
                    <div class="myText">
                        <small class="text-secondary">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi sodaiers ipsum vel elementum vehicula. Suspendisse sit amet aliquet ex. Pellentesque commodo tortor vel mi</small>
                    </div>
                </div>

                <div class="">
                    <img class="myImg second" src="/img/new-milkshake-menu-600x450.jpg" alt="">
                    <div class="text-center">
                        <p class="myTitle fw-bold mb-0">New Milkshake Menu</p>                        
                    </div>
                    <div class="myText"> 
                        <small class="text-secondary">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi sodaiers ipsum vel elementum vehicula. Suspendisse sit amet aliquet ex. Pellentesque commodo tortor vel mi</small>
                    </div>
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
        width: 512.5px;
    }
    .myDflex{
        justify-content: space-between;
    }
    .myTitle{
        font-size: 35px;
    }
    .first{
        padding-right: 20px;
        margin-bottom: 28px;
    }
    .second{
        padding-left: 20px;
        margin-bottom: 28px;
    }
    .myText{
        text-align: center;
        margin: 0 30px;
    }
    .myPadding{
        padding-top: 125px;
        padding-bottom: 150px;
    }
    .pdTitle{
        padding-bottom: 50px;
    }
</style>

