<template>
  <div class="app">Hello <World /></div>
</template>

<script>
import World from './World.vue'


export default {
  name: "Hello",

  components: {
    World
  }
};
</script>

<style>
.app {
  color: red;
}
</style>
