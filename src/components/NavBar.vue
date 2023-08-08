<script setup>
import { RouterLink } from 'vue-router';
import { Icon } from '@iconify/vue';
</script>

<template>
    <header style="background-color: #0f0f0f;">
        <nav class="container">
            <div class="top-left-dose-branding">
                <RouterLink to="/" class="dose-branding">
                    <img src="../assets/dose-logo.svg" alt="">
                    <div class="branding-name">
                        <h1>dose engineering</h1>
                    </div>
                </RouterLink>
            </div>

            <div class="top-right-navigation">
                <div class="navigation-links-wrapper">
                    <RouterLink to="/">home</RouterLink>
                    <RouterLink to="/services">services</RouterLink>
                    <RouterLink to="/about">about</RouterLink>
                </div>
                <div class="separation-bar"></div>
                <button class="language-button">
                    <Icon 
                        icon="fontisto:world-o" 
                        class="icon" 
                        color="white"
                        width="20"
                        />
                    <h1>EN</h1>
                </button>
            </div>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Saira+Condensed:wght@300;400;700&display=swap');


header {
    display: flex;
    justify-content: center;
    width: 100%;
    height: 70px;
    margin: 0 auto;
    border-bottom: 1px solid #303030;
}
.container {
    display: flex;
    width: 100%;
    max-width: 1440px;
    height: 100%;
    background-color: #0f0f0f;
    justify-content: space-between;
    align-items: center;
    padding: 0;
    margin: 0 10px 0 10px;

    .top-left-dose-branding .dose-branding {
        display: flex;
        text-decoration: none;

        img {
            width: 35px;
            margin-right: 8px;
        }

        .branding-name {
            font-family: 'Saira Condensed', 'sans-serif';
            letter-spacing: 0.03em;
            font-size: 20px;
            color: white;
            text-transform: uppercase;
            text-decoration: none;
        }
    }

    .top-right-navigation {
        display: flex;
        align-items: center;

        .navigation-links-wrapper {
            display: flex;

            a {
                font-family: 'Saira Condensed', sans-serif;
                font-weight: bold;
                font-size: 1.2em;
                color: white;
                margin-right: 20px;
                text-decoration: none;
                text-transform: uppercase;
                border-bottom: 1px solid transparent;
                transition: 300ms ease-in-out;
                
                &:hover {
                    border-bottom: 1px solid white;
                }
            }
        }

        .language-button {
            display: flex;
            height: 30px;
            align-items: center;
            background-color: #424242;
            border: 0;
            border-radius: 10px;

            .icon {
                margin-right: 5px;
            }

            h1 {
                font-family: 'Saira Condensed', sans-serif;
                font-weight: bold;
                font-size: 1.5em;
                color: white;

            }

        }
    }
}

</style>