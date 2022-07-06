<template>
    <div class="myJumbotron position-relative px-2 pt-2">
        <div class="bgJumbo"><img src="/img/home-background-hero-scaled.jpg" alt=""></div>
        <div class="position-relative">
            <!-- PRIMA SEZIONE HEADER -->
            <div class="d-flex justify-content-end pb-4">
            <!-- ICONA ROSSA HEADER -->
            <div class="rounded-circle plusIcon">
                <a href="#">
                    <i class="fa-solid fa-plus"></i>
                </a>
            </div>
            </div>

        <!-- SECONDA SEZIONE HEADER -->
            <div class="container pb-3">
                <div class="d-flex justify-content-between align-items-center">
                    <!-- LOGO -->
                    <img src="/img/takeout-logo.png" alt="">
                    <!-- MENU -->
                    <ul class="nav">
                        <li class="nav-item">
                            <a class="nav-link text-white" aria-current="page" href="#">
                                <span class="fw-bold">Home</span>
                                <span class="ps-2 homeLink">
                                    <i class="fa-solid fa-angle-down"></i>
                                </span>
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" aria-current="page" href="#">
                                <span class="fw-bold">Order Online</span>
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" aria-current="page" href="#">
                                <span class="fw-bold">About</span>
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" aria-current="page" href="#">
                                <span class="fw-bold">News</span>
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" aria-current="page" href="#">
                                <span class="fw-bold">Contact Us</span>
                            </a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white myLink" aria-current="page" href="#">
                                <i class="fa-solid fa-cart-shopping"></i>
                            </a>
                        </li>
                    </ul>
                </div>
            </div>

        <!-- TERZA SEZIONE HEADER -->
            <div class="d-flex justify-content-end">
            <div class="d-flex flex-column gap-2">
                <div class="rounded mySquare bg-white">
                    <img class="myImg" id="firstImg" src="/img/folders.png" alt="">
                    <small class="fw-bold">Demos</small>
                </div>
                <div class="rounded mySquare bg-white">
                    <img class="myImg" id="secondImg" src="/img/price.png" alt="">
                    <small class="fw-bold">On Sale</small>
                </div>
            </div>
            </div>
        <!-- QUARTA SEZIONE HEADER -->
            <div class="container myContainer">
                <div class="d-flex justify-content-start">
                    <div class="textBlock">
                        <p class="text-white fw-bold fs-2 mb-0">Hungry?</p>
                        <p class="myText fw-bold mb-0">Great Food</p>
                        <p class="myText fw-bold text-white">Delivered</p>
                        <button type="button" class="btn btn-danger myButton rounded-pill">
                            VIEW OUR MENU
                            <span class="ps-2 mySpan">
                                <i class="fa-solid fa-circle-arrow-right"></i>
                            </span>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>


export default {
    components: {
    
    }
}
</script>

<style lang="scss" scoped>
    #firstImg{
        width: 30px;
    }
    #secondImg{
        width: 38px;
    }
    .myJumbotron{
        min-height: 1000px;
    }
    .bgJumbo{
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
    }
    .bgJumbo img{
        width: 100%;
        height: 95%;
        object-fit: cover;
        object-position: 50% 80%;
    }
    .plusIcon{
        background-color: #bf1e23;
        width: 40px;
        height: 40px;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .plusIcon i{
        color: white;
        transform: scale(0.7);
    }
    .myLink i{
        transform: scale(0.7);
    }
    .nav-item:first-child span{
        color: #fcdc31;
    }
    .mySquare{
        width: 50px;
        height: 50px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    .mySquare small{
        font-size: 11px;
        color: #61605e;
    }
    .myText{
        font-size: 70px;
        line-height: 70px;
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
    padding: 0.4rem 1.4rem;
    }
    .textBlock:last-child p{
        margin-bottom: 30px;
        &:nth-child(2){
            color: #fcdc31;
        }
    }
    .mySpan i{
        transform: scale(0.9);
    }
    .myContainer{
        padding-top: 80px;
    }
    .container{
        max-width: 1050px;
    }
    .homeLink i{
        transform: scale(0.8);
    }
</style>
