<template>
    <div class="bgHeader">
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

        <!-- TERZA SEZIONE HEADER -->

        <!-- QUARTA SEZIONE HEADER -->
    </div>
</template>

<script>


export default {
    components: {
    
    }
}
</script>

<style lang="scss">
    .bgHeader{
        background-image: url("/public/img/home-background-hero-scaled.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        background-position: bottom center;
        height: 100%;
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
</style>