<template>
  <div id="app">
    <PokeForm title="PokeGuia"/>
  </div>
</template>

<script>
import PokeForm from "./components/PokeForm.vue";

export default {
  name: "app",
  components: {
    PokeForm
  },

}
</script>

<style>

html {
  background-image: "./assets/wallpaper.jpg";
}

</style>