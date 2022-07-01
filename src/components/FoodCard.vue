<template>
    <div class="myCard">
        <img class="pb-3" :src="image" alt="">
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
</style>