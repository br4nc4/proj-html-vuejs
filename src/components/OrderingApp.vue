<template>
    <div class="pt-5 myBg">
        <div class="container pt-5">
            <div class="d-flex justify-content-start pt-3">
                <div class="pt-2">
                    <div class="pb-5">
                        <p class="text-white fw-bold fs-2 mb-0">Download Our</p>
                        <p style="color: #fcdc31;" class="myText fw-bold mb-0">Ordering App</p>
                    </div>
                    <div class="d-flex pt-2 gap-3">
                        <img class="myImg" src="/img/app-store-badge-200x67.png" alt="">
                        <img class="myImg" src="/img/play-store-badge-200x67.png" alt="">
                    </div>
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
    /* .myImg{
        width: 100%;
        object-fit: cover;
        object-position: top center;
        height: 520px;
    } */
    .myBg{
        background-image: url("/public/img/app-ordering-scaled.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        background-position: top center;
        height: 510px;
    }
    .container{
        max-width: 1032px;
    }
    .myText{
        font-size: 70px;
        line-height: 60px;
    }
    .myImg{
        width: 145px;
    }
</style>