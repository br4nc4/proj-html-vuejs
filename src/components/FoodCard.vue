<template>
    <div class="myCard position-relative">
        <img class="pb-3" :src="image" alt="">

        <div class="overlay">
            <div class="rounded-circle myCircle">
                <img src="/img/check-square.png" alt="">
            </div>
            <div class="text-center text-white fw-bold hoverText">VIEW CART</div>
        </div>

        <div class="myText">
            <p id="name" class="fw-bold fs-4 text-center mb-2">{{title}}</p>
            <p id="price" class="text-center">{{price}}</p>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        image: String,
        title: String,
        price: String,
    }
}
</script>

<style lang="scss" scoped>
    #name{
        color: #212934;
    }
    #price{
        color: #d12246;
        font-size: 15px;
    }
    .myCard img{
        width: 320px;
    }
    .myCard{
        &:hover{
            .overlay{
                opacity: 1;
            }
        }
    }
    .overlay{
        position: absolute;
        top: 0;
        left: 0;
        bottom: 0;
        right: 0;
        background-color: rgba(0,0,0,0.2);
        opacity: 0;
        height: 456px;
    }
    .myCircle{
        width: 70px;
        height: 70px;
        background-color: rgba(0,0,0,0.8);
        display: flex;
        justify-content: center;
        align-items: center;
        position: absolute;
        top: 40%;
        left: 50%;
        transform: translate(-50%);
    }
    .hoverText{
        top: 58%;
        position: absolute;
        left: 50%;
        transform: translate(-50%);
        font-size: 15px;
    }
    .myCircle img{
        width: 35px;
        filter: invert(100%);
        filter: brightness(10);
    }
</style>