<template>
    <div class="bgHeader px-2 pt-2">
        <!-- PRIMA SEZIONE HEADER -->
        <div class="d-flex justify-content-end">
            <!-- ICONA ROSSA HEADER -->
            <div class="rounded-circle plusIcon">
                <a href="#">
                    <i class="fa-solid fa-plus"></i>
                </a>
            </div>
        </div>

        <!-- SECONDA SEZIONE HEADER -->
        <div class="container">
            <div class="d-flex justify-content-between align-items-center">
                <!-- LOGO -->
                <img src="/img/takeout-logo.png" alt="">
                <!-- MENU -->
                <ul class="nav">
                    <li class="nav-item">
                        <a class="nav-link text-white" aria-current="page" href="#">
                            <span class="fw-bold">Home</span>
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
    .bgHeader{
        background-image: url("/public/img/home-background-hero-scaled.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
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
</style>