<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
    <div class="container">
        <div class="brand-name">
            dose engineering
        </div>
        <div class="services-description-wrapper">
            <div class="big-text-service-description">
                <h1>Transform all your assets to the digital world</h1>
            </div>
            <div class="small-text-service-description">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum praesentium, dolorum soluta adipisci error sunt alias corrupti sequi? Praesentium, ad tempora.
            </div>
            <RouterLink to="/services" class="router-link">
                <button class="button">
                    <p>Go to Services</p>
                </button>
            </RouterLink>
        
        </div>
    </div>
</template>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Saira+Condensed:wght@300;400;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;400;700&display=swap');

.container {
    display: flex;
    flex-direction: column;
    position: absolute;
    transform: translate(0, 50%);

    .brand-name {
        font-family: 'Saira Condensed', 'sans-serif';
        letter-spacing: 0.05em;
        font-size: 1.2em;
        color: white;
        text-transform: uppercase;
        font-weight: 400;
    }

    .services-description-wrapper {
        width:80%;
        color:white;
    }
        .big-text-service-description {
            font-family: 'Roboto', sans-serif;
            font-size: 1.2em;
            line-height: 2em;

        }

        .small-text-service-description {
            font-family: 'Roboto', sans-serif;
            opacity: 0.7;
        }

        .router-link {
            text-decoration: none;
        }

        button {
            display: flex;
            align-items: center;
            font-family: 'Roboto', sans-serif;
            font-weight: bold;
            font-size: 1.2em;
            margin-top: 40px;
            height: 40px;
            border-radius: 7px;
            border: 2px solid transparent;
            width: fit-content;
            transition: 250ms ease-in-out;
            cursor: pointer;

            &:hover {
                border: 2px solid rgb(61, 61, 61);

            }
        }
        
            p {
                margin: 0 10px 0 10px;
            }
}
</style>