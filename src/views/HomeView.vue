<script setup>
import ServicesTab from '../components/ServicesTab.vue';
import ServicesBackgrounds from '../components/ServicesBackgrounds.vue';
import ServicesDescription from '../components/ServicesDescription.vue';
import DoseDescription from '../components/DoseDescription.vue';
</script>

<template>
  <div class="home-view-wrapper">
    <div class="service-background-wrapper">
      <ServicesBackgrounds />
      <div class="services">
        <ServicesTab class="services-tab"/>
        <div class="services-description">
          <ServicesDescription />
        </div>
      </div>
    </div>

    <div class="dose-description-wrapper">
      <DoseDescription />
    </div>
  </div>
</template>

<style lang="scss" scoped>

.home-view-wrapper {
  width: 100%;

  .service-background-wrapper {
    display: flex;
    justify-content: center;
    width: 100%;
    position: relative;
    
    .services {
      display: flex;
      flex-direction: column;
      width: 90%;
      height: 100%;
      max-width: 1440px;
      position: absolute;

      .services-tab {
        margin-top: 40px;
        width: 100%;
      }

      .services-description {
        display: flex;
        height: 100%;
        width: 100%;
        position: relative;
      }
    }
  }

  .dose-description-wrapper {
    display: flex;
    justify-content: center;
    height: 500px;
    width: 100%;
  }
}

</style>
