<template>
  <div class="container_bg">
    <div class="container">
      <TextContentComponent />
      <AnimeBallsComponent />
    </div>
  </div>
</template>

<script setup>
import TextContentComponent from './components/TextContentComponent.vue';
import AnimeBallsComponent from './components/AnimeBallsComponent.vue';
</script>

<style scoped>
.container_bg {
  height: 100vh;
  width: 100vw;
  overflow-x: hidden;
  background-image: url('./assets/bg_desk.jpg');
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}

.container {
  height: 100%;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
}

@media (max-width: 450px) {
  .container_bg {
    background-image: url('./assets/bg_mob.jpg');
  }
  .container {
    align-items: flex-start;
    padding-top: 60px;
  }
}
</style>
