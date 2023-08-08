<script setup>

</script>

<template>
    <div class="container">
        <div class="button">
            <h2>BIM Modeling</h2>
        </div>
        <div class="button">
            <h2>Dynamo Scripts</h2>
        </div>
        <div class="button">
            <h2>Revit API</h2>
        </div>
        <div class="button">
            <h2>Scan to BIM</h2>
        </div>
        
        
        
    </div>
</template>
<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;400;700&display=swap');

.container {
    display: flex;
    border-bottom: 1px solid gray;

    .button {
        margin-right: 30px;
        height: 40px;
        opacity: 0.7;
        border-bottom: 2px solid transparent;
        transition: 150ms ease-in-out;
        cursor: pointer;

        &:hover {
            opacity: 1;
            border-bottom: 2px solid white;
        }

    }
    
    h2 {
        font-family: 'Roboto', sans-serif;
        color: white;
        font-size: 0.9rem;
        font-weight: 400;
    }
}
</style>