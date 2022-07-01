<template>
    <div>
        <img :src="image" alt="">
        <div>
            <h5 class="">{{title}}</h5>
            <p>{{price}}</p>
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

</style>