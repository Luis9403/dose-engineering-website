<script setup>

</script>

<template>
    <div class="description-wrapper">
        <div class="left-side-illustration">
            <div class="info-background-wrapper">
                <img src="../assets/images/image_1.jpg" alt="">
            </div>
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
    display: grid;
    grid-template-columns: 1fr 1fr;
    width: 90%;
    max-width: 1440px;
    height: 80%;
    margin-top: 30px;
    border-radius: 10px;
    background-color: white;
    box-shadow: #959da533 0px 8px 24px;

    .right-side-text-description {
        display: flex;
        margin: 30px 30px 0 40px;
        flex-direction: column;

        h1 {
            margin: 0 0 0 0;
            text-align: end;
            font-size: 3em;
        }

        p {
            text-align: justify;
            font-size: 1.4em;
        }
    }

    .left-side-illustration {
        height: 100%;
        width: 100%;

        .info-background-wrapper {
            margin: 10%;
        }

        img {
            height: 100%;
            width: 100%;
            object-fit: cover;
        }
    }
}
</style>