<template>
  <div class="root">
    <p class="episodes-title">Episodes</p>
    <episodes class="mt-10" />

    <p class="episodes-title">Characters</p>
    <characters />

    <p class="episodes-title">Locations</p>
    <locations />
  </div>
</template>

<script>
import Episodes from "../components/Episodes";
import Characters from "../components/Characters.vue";
import Locations from "../components/Locations.vue";

export default {
  name: "Home",

  components: {
    Episodes,
    Characters,
    Locations,
  },
};
</script>

<style scoped>
.episodes-title {
  text-align: center;
  margin-top: 2%;
  margin-bottom: 2%;
  font-size: 3em;
  letter-spacing: 5px;
}
</style>
