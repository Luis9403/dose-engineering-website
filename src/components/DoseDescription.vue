<script setup>

</script>

<template>
    <div class="description-wrapper">
        <div class="left-side-illustration">
            <img src="../assets/images/image_1.jpg" alt="">
        </div>

        <div class="right-side-text-description">
            <div class="big-text-wrapper">
                <h1>Who we are?</h1>
            </div>
            <div class="small-text-description">
                <p>Lorem ipsum dolor sit amet, 
                    consectetur adipisicing elit. 
                    Illo ipsum assumenda harum perferendis eius dicta fugit iure nemo. 
                    Alias ad incidunt nam sit! Ipsa cumque velit corrupti rerum, dignissimos sapiente.</p>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>

.description-wrapper {
    display: flex;
    width: 100%;
    max-width: 1440px;
    height: 100%;

    .right-side-text-description {
        display: flex;
        flex-direction: column;
    }

    .left-side-illustration {
        height: 100%;
        width: 50%;

        img {
            height: 80%;
            width: 80%;
            object-fit: cover;
        }
    }
}
</style>