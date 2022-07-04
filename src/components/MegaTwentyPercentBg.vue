<template>
    <div class="myContainer container-fluid position-relative px-0">
        <div class="myBg">
            <svg class="fusion-waves-opacity-candy first" fill="white" fill-opacity="0.15" xmlns="http://www.w3.org/2000/svg" viewBox="0 1 1024 216" preserveAspectRatio="none"><path class="st0" d="M0 215.4c19.4.5 38.7 1.6 57.7.3 206.6-15 248.5-126.6 455-143.8 184.8-15.5 285.7 60.9 464.3 41.3 16.9-1.8 32.5-4.4 47.1-7.6L1024 .4H0v215z"/><path class="st1" d="M0 196.4c30.2 1.6 59.6 1.6 86.8-.4C293.4 180.9 284.1 73.4 490.7 56.2c184.9-15.5 278.5 58.2 457.1 38.4 28.3-3.2 53.5-8.2 76.2-14.6V.256H0V196.4z"/><path class="st2" d="M0 169.8c22.2.3 43.8-.2 64.2-1.7C270.8 153.1 262 55.6 468.6 38.4 653.4 22.9 695.4 89.5 874 69.7c54.8-6 104.9-18.3 150-33.7V.256H0V169.8z"/><path class="st3" style="fill-opacity: 1" d="M0 162.1c4-.2 8-.4 11.9-.7C218.4 146.3 239.8 37 446.4 19.8 631.3 4.3 672.7 60.9 851.3 41.1c64-7.2 121.9-20.8 172.7-37.9V.156H0V162.6z"/></svg>
            <!-- <svg class="fusion-waves-opacity-candy second" fill="white" fill-opacity="1" xmlns="http://www.w3.org/2000/svg" viewBox="0 1 1024 216" preserveAspectRatio="none"><path class="st0" d="M0 215.4c19.4.5 38.7 1.6 57.7.3 206.6-15 248.5-126.6 455-143.8 184.8-15.5 285.7 60.9 464.3 41.3 16.9-1.8 32.5-4.4 47.1-7.6L1024 .4H0v215z"/><path class="st1" d="M0 196.4c30.2 1.6 59.6 1.6 86.8-.4C293.4 180.9 284.1 73.4 490.7 56.2c184.9-15.5 278.5 58.2 457.1 38.4 28.3-3.2 53.5-8.2 76.2-14.6V.256H0V196.4z"/><path class="st2" d="M0 169.8c22.2.3 43.8-.2 64.2-1.7C270.8 153.1 262 55.6 468.6 38.4 653.4 22.9 695.4 89.5 874 69.7c54.8-6 104.9-18.3 150-33.7V.256H0V169.8z"/><path class="st3" d="M0 162.1c4-.2 8-.4 11.9-.7C218.4 146.3 239.8 37 446.4 19.8 631.3 4.3 672.7 60.9 851.3 41.1c64-7.2 121.9-20.8 172.7-37.9V.156H0V162.6z"/></svg> -->
            <!-- <svg class="fusion-waves-opacity-candy third" fill="white" fill-opacity="0" xmlns="http://www.w3.org/2000/svg" viewBox="0 1 1024 216" preserveAspectRatio="none"><path class="st0" d="M0 215.4c19.4.5 38.7 1.6 57.7.3 206.6-15 248.5-126.6 455-143.8 184.8-15.5 285.7 60.9 464.3 41.3 16.9-1.8 32.5-4.4 47.1-7.6L1024 .4H0v215z"/><path class="st1" d="M0 196.4c30.2 1.6 59.6 1.6 86.8-.4C293.4 180.9 284.1 73.4 490.7 56.2c184.9-15.5 278.5 58.2 457.1 38.4 28.3-3.2 53.5-8.2 76.2-14.6V.256H0V196.4z"/><path class="st2" d="M0 169.8c22.2.3 43.8-.2 64.2-1.7C270.8 153.1 262 55.6 468.6 38.4 653.4 22.9 695.4 89.5 874 69.7c54.8-6 104.9-18.3 150-33.7V.256H0V169.8z"/><path class="st3" d="M0 162.1c4-.2 8-.4 11.9-.7C218.4 146.3 239.8 37 446.4 19.8 631.3 4.3 672.7 60.9 851.3 41.1c64-7.2 121.9-20.8 172.7-37.9V.156H0V162.6z"/></svg>
            <svg class="fusion-waves-opacity-candy fourth" fill="white" fill-opacity="0" xmlns="http://www.w3.org/2000/svg" viewBox="0 1 1024 216" preserveAspectRatio="none"><path class="st0" d="M0 215.4c19.4.5 38.7 1.6 57.7.3 206.6-15 248.5-126.6 455-143.8 184.8-15.5 285.7 60.9 464.3 41.3 16.9-1.8 32.5-4.4 47.1-7.6L1024 .4H0v215z"/><path class="st1" d="M0 196.4c30.2 1.6 59.6 1.6 86.8-.4C293.4 180.9 284.1 73.4 490.7 56.2c184.9-15.5 278.5 58.2 457.1 38.4 28.3-3.2 53.5-8.2 76.2-14.6V.256H0V196.4z"/><path class="st2" d="M0 169.8c22.2.3 43.8-.2 64.2-1.7C270.8 153.1 262 55.6 468.6 38.4 653.4 22.9 695.4 89.5 874 69.7c54.8-6 104.9-18.3 150-33.7V.256H0V169.8z"/><path class="st3" d="M0 162.1c4-.2 8-.4 11.9-.7C218.4 146.3 239.8 37 446.4 19.8 631.3 4.3 672.7 60.9 851.3 41.1c64-7.2 121.9-20.8 172.7-37.9V.156H0V162.6z"/></svg> -->
            <!-- <img id="first" src="/img/svg-0.png" alt="">
            <img id="second" src="/img/svg-0.png" alt="">
            <img id="third" src="/img/svg-0.png" alt="">
            <img id="fourth" src="/img/svg-0.png" alt=""> -->
            <img src="/img/first-order-background-scaled.jpg" alt=""> 
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .myContainer{
        height: 470px;
        width: 100%;
    }
    .myBg{
        width: 100%;
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
    }
    .myBg img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        object-position: top center;
    }
    .myBg .first{
        position: absolute;
        width: 100%;
        top: 0;
        z-index: 1;
        height: 360px;
    }
    /* .myBg .second{
        position: absolute;
        width: 100%;
        top: -25%;
        z-index: 2;
        height: 340px;
    } */
    /* .myBg .third{
        position: absolute;
        width: 100%;
        top: -44%;
        z-index: 2;
        height: 450px;
    }
    .myBg .fourth{
        position: absolute;
        width: 100%;
        top: -48%;
        z-index: 2;
        height: 450px;
    } */
    /* myBg{
        display: flex;
        flex-direction: column;
    }
    img{
        width: 100%;
        height: 500px;
        object-fit: cover;
        object-position: 0 -20%;
    }
    svg{
        position: absolute;
        top: -15%;
        width: 100%;
        height: 350px;
    }
    .second{
        position: absolute;
        top: 7%;
        width: 100%;
    } */
</style>