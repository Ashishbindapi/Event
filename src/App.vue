<template>
  <div id="app" class="container">
    <div class="row">
      <div class="col">
        <EventMenu />
      </div>
    </div>
  </div>
</template>

<script>
import EventMenu from './components/EventMenu.vue';

export default {
  name: 'AppBootstrap',
  components: {
    EventMenu,
  }
};
</script>

<style>
body {
  background-image: url('./assets/Asset 74png.png');
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  width: 100%;
  overflow: hidden;
}

@media screen and (max-width: 768px) {
  body {
    background-size: contain;
  }
}
</style>
