<script setup>

</script>

<template>
    <div class="container">
        <div class="gradient"></div>
        <img src="../assets/images/image_4.jpg" alt="">
    </div>
</template>

<style lang="scss" scoped>
.container {
    height: 600px;
    width: 100%;
    position: relative;

    .gradient{
        height: 100%;
        width: 100%;
        background-image: linear-gradient(to right, #0f0f0f, #0f0f0fe7, #00000000);
        position: absolute;
    }
    img {
        height: 100%;
        width: 100%;
        object-fit: cover;
        display: block;
       }
}
</style>